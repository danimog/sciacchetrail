<!-- 
token accesso: EAAD9laf0k4cBAKwBSWjNfW49w177TRQbynHht8Y1qjaQx9wvZCqltZBb6O14UYctWQfYVtsOJZCSgvkNZAm5VIW8sDbZBzfpnPYJ6IQeAcvwWZCRnlcci6nAQEfx4KCZAkgmZBf1qxl28plmuZAsU2attpqrdGSpy1Sk3g6CwIhcD3XlmowMUfW3VJMuatUVKR2CHWWcLHbJb3gZDZD 

id: 1496233471

1496233471

1496233471.M2E4MWE5Zg==.NmJkMzI5ZDg0ZjIx.NDMyN2IzOGFiNDdmOTJjMWIyMTg=

IGQVJWUFFNR1lIMmxyeVMzU2lPQ2lJSXkwdTNFNjBtZAmh3dWtWX280eWJuRE9yWGx0Q1hfbUN5cmYwYURCeXhiMzVTOXQ4Y1l5aGFhaEFhX2xuclVuVGI0SHAyaHBKWEtReGNudk9XcXI5NGVJTXQwQwZDZD

1) https://api.instagram.com/oauth/authorize?client_id=2519018611682768&redirect_uri=https://sciacchetrail.com/auth/&scope=user_profile,user_media&response_type=code

2) AQDzitvtmegxx15SH970Dyig_uAom0nrzUMVepnSkiDusEZM1mvI4dh2zcQ0TPW7TXyqGTwbIUGzZFJCSvuEYxJXITxpmhR4_pi9wo9htDJMAmoXByFZBfi1jsy5GJESF2okCADAw0pkHCMrHbdbssiCNGxpwpmspNNWlNdR-2YRZUi8rZ0HyPhNp3fGldMyg_u-mnpfg8SYdxrGONpzSLTofkevfHawgSyjZyQkxNFHBA

2519018611682768

608c2c719429d50fedefeef36bfebc11

1370d34fd39c54db04228c6d0ca1d16b

curl -X POST \

https://api.instagram.com/oauth/access_token -F client_id=2519018611682768 -F client_secret=608c2c719429d50fedefeef36bfebc11 -F grant_type=authorization_code -F redirect_uri=https://sciacchetrail.com/auth/ -F code=AQDzitvtmegxx15SH970Dyig_uAom0nrzUMVepnSkiDusEZM1mvI4dh2zcQ0TPW7TXyqGTwbIUGzZFJCSvuEYxJXITxpmhR4_pi9wo9htDJMAmoXByFZBfi1jsy5GJESF2okCADAw0pkHCMrHbdbssiCNGxpwpmspNNWlNdR-2YRZUi8rZ0HyPhNp3fGldMyg_u-mnpfg8SYdxrGONpzSLTofkevfHawgSyjZyQkxNFHBA


3) curl -X POST \ https://api.instagram.com/oauth/access_token \ -F client_id=2519018611682768 \ -F client_secret=608c2c719429d50fedefeef36bfebc11 \ -F grant_type=authorization_code \ -F redirect_uri=https://sciacchetrail.com/auth/ \ -F code=AQDzitvtmegxx15SH970Dyig_uAom0nrzUMVepnSkiDusEZM1mvI4dh2zcQ0TPW7TXyqGTwbIUGzZFJCSvuEYxJXITxpmhR4_pi9wo9htDJMAmoXByFZBfi1jsy5GJESF2okCADAw0pkHCMrHbdbssiCNGxpwpmspNNWlNdR-2YRZUi8rZ0HyPhNp3fGldMyg_u-mnpfg8SYdxrGONpzSLTofkevfHawgSyjZyQkxNFHBA

4) {"access_token": "IGQVJXNFNMczBmczVQTFRIX1U3b25ZATEE4V1NUb1N5TUNHV0xDU2I3T2szbU4zNC0yOHo1REx5c20zMUFRWk1PT0RiOU9veWtFQkl3OEVVaEFLVy1pRFZAxdmk4LTJvcS1GNUFGenA3RnVQYWd5eWd4QWw0Qk1fQWRwdmJZA", "user_id": 17841401244153378}% 

5)curl -X GET \ 'https://graph.instagram.com/17841401244153378?fields=id,username&access_token=IGQVJXNFNMczBmczVQTFRIX1U3b25ZATEE4V1NUb1N5TUNHV0xDU2I3T2szbU4zNC0yOHo1REx5c20zMUFRWk1PT0RiOU9veWtFQkl3OEVVaEFLVy1pRFZAxdmk4LTJvcS1GNUFGenA3RnVQYWd5eWd4QWw0Qk1fQWRwdmJZA'

5a)curl -X GET \ 'https://graph.instagram.com/me/media?fields=id,media_url&access_token=IGQVJVbllYU2VYWmkzbXdRekpqMWNLU0VEajR0Nk5qYXFiYm1HaG5HcjZAObjhkSDJ3RDg5bTU5ZAlAwMkJPTWhmS0trMHlEeFdvbEpIT05idk5SSGEweUlRQVk5bm9QT0E4RHpMdkZAB'


6)curl -i -X GET "https://graph.instagram.com/access_token?grant_type=ig_exchange_token&client_secret=608c2c719429d50fedefeef36bfebc11&access_token=IGQVJXNFNMczBmczVQTFRIX1U3b25ZATEE4V1NUb1N5TUNHV0xDU2I3T2szbU4zNC0yOHo1REx5c20zMUFRWk1PT0RiOU9veWtFQkl3OEVVaEFLVy1pRFZAxdmk4LTJvcS1GNUFGenA3RnVQYWd5eWd4QWw0Qk1fQWRwdmJZA"

7) {"access_token":"IGQVJVbllYU2VYWmkzbXdRekpqMWNLU0VEajR0Nk5qYXFiYm1HaG5HcjZAObjhkSDJ3RDg5bTU5ZAlAwMkJPTWhmS0trMHlEeFdvbEpIT05idk5SSGEweUlRQVk5bm9QT0E4RHpMdkZAB","token_type":"bearer","expires_in":5176381}%  



https://api.instagram.com/oauth/authorize?client_id=2519018611682768&redirect_uri=https://sciacchetrail.com&scope=user_profile,user_media&response_type=AQAMLfoXWH4oCo0EXqrX50A8w1tJIp8JqpcWkPRE02WcfI9Lx_kFMtVlHgSPXvl1Pm-GK65rFMyse_Wed8W68ubvvpOLDvRz_ZOKeEJJKd6Mf2SEKJuuWZwMcg7E0dVLXPVL8qkU01JKsIOMTm75inkUW9dmr51bs4986eeU7Eu2leWUjjFnYuzA-3BjziKbrwAzxJG7aXjfvNq-F_WF4kigv5VfADIa46TirLPfGqKDwQ

curl -X POST \ https://api.instagram.com/oauth/access_token \ -F client_id=684477648739411 \ -F client_secret=eb8c7... \ -F grant_type=authorization_code \ -F redirect_uri=https://socialsizzle.herokuapp.com/auth/ \ -F code=AQDp3TtBQQ...


curl -X POST https://api.instagram.com/oauth/access_token -F client_id=2519018611682768 -F client_secret=1370d34fd39c54db04228c6d0ca1d16b -F grant_type=authorization_code -F redirect_uri=https://sciacchetrail.com/auth/ -F code=AQAMLfoXWH4oCo0EXqrX50A8w1tJIp8JqpcWkPRE02WcfI9Lx_kFMtVlHgSPXvl1Pm-GK65rFMyse_Wed8W68ubvvpOLDvRz_ZOKeEJJKd6Mf2SEKJuuWZwMcg7E0dVLXPVL8qkU01JKsIOMTm75inkUW9dmr51bs4986eeU7Eu2leWUjjFnYuzA-3BjziKbrwAzxJG7aXjfvNq-F_WF4kigv5VfADIa46TirLPfGqKDwQ

{"access_token": "IGQVJXRUZAsRDEtRENvVGZAVdkxKQjFyR1Vwb3ZAEeEVJNmR6SlZANX0h1aTNHcExmcUZAxbXoybzRtSnd1NllsdXhmejRxazdOcUU4UEJud19LYkVicm13c0tiNmtHQXBEMkVKbjJFMzg2cVRkMmx3aU9VcG1XWUVPajlnUjgw", "user_id": 17841401244153378}%

curl -X GET \ 'https://graph.instagram.com/17841405793187218?fields=id,username&access_token=IGQVJXRUZAsRDEtRENvVGZAVdkxKQjFyR1Vwb3ZAEeEVJNmR6SlZANX0h1aTNHcExmcUZAxbXoybzRtSnd1NllsdXhmejRxazdOcUU4UEJud19LYkVicm13c0tiNmtHQXBEMkVKbjJFMzg2cVRkMmx3aU9VcG1XWUVPajlnUjgw'

********************************   ********************************

PRENDO INFO SUI MEDIA
curl -X GET 'https://graph.instagram.com/me/media?fields=id,caption&access_token=IGQVJXRUZAsRDEtRENvVGZAVdkxKQjFyR1Vwb3ZAEeEVJNmR6SlZANX0h1aTNHcExmcUZAxbXoybzRtSnd1NllsdXhmejRxazdOcUU4UEJud19LYkVicm13c0tiNmtHQXBEMkVKbjJFMzg2cVRkMmx3aU9VcG1XWUVPajlnUjgw'

curl -X GET https://graph.instagram.com/17953062652316159?fields=id,media_type,media_url,username,timestamp&access_token=IGQVJXRUZAsRDEtRENvVGZAVdkxKQjFyR1Vwb3ZAEeEVJNmR6SlZANX0h1aTNHcExmcUZAxbXoybzRtSnd1NllsdXhmejRxazdOcUU4UEJud19LYkVicm13c0tiNmtHQXBEMkVKbjJFMzg2cVRkMmx3aU9VcG1XWUVPajlnUjgw'

$.ajax({
        url: 'https://graph.instagram.com/me/media?fields=id,caption&access_token=IGQVJXRUZAsRDEtRENvVGZAVdkxKQjFyR1Vwb3ZAEeEVJNmR6SlZANX0h1aTNHcExmcUZAxbXoybzRtSnd1NllsdXhmejRxazdOcUU4UEJud19LYkVicm13c0tiNmtHQXBEMkVKbjJFMzg2cVRkMmx3aU9VcG1XWUVPajlnUjgw',
        beforeSend: function(xhr) {
             xhr.setRequestHeader("Authorization", "IGQVJXRUZAsRDEtRENvVGZAVdkxKQjFyR1Vwb3ZAEeEVJNmR6SlZANX0h1aTNHcExmcUZAxbXoybzRtSnd1NllsdXhmejRxazdOcUU4UEJud19LYkVicm13c0tiNmtHQXBEMkVKbjJFMzg2cVRkMmx3aU9VcG1XWUVPajlnUjgw")
        }, success: function(data){
            console.log(data);
            //process the JSON data etc
        }
})


    $(document).ready(function() {
        $.ajax({
            url: 'https://graph.instagram.com/me/media?fields=id,caption&access_token=',
            type: 'GET',
            dataType: 'json',
            contentType: "application/json",
            beforeSend: function(xhr) {
                 xhr.setRequestHeader("Authentication", "IGQVJXRUZAsRDEtRENvVGZAVdkxKQjFyR1Vwb3ZAEeEVJNmR6SlZANX0h1aTNHcExmcUZAxbXoybzRtSnd1NllsdXhmejRxazdOcUU4UEJud19LYkVicm13c0tiNmtHQXBEMkVKbjJFMzg2cVRkMmx3aU9VcG1XWUVPajlnUjgw")
            },
            success: function(data){
                console.log(data);
            }
        });
    });


-->