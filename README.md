
# TryHackMe-Neighbour

A very easy ctf dealing with IDOR.



## Deployment

```bash
First get to the login page by visiting the <IP>
```


```bash
Now as you dont have the credentials, you can view the page source or press CTRL+U to get the guest login credentials( use the guest account!(CTRL+U) ) written below the Login button.
```


```bash
Now visiting the page source, you get the Guest credentials > guest:guest 
```


```bash
Then Getting back to the login page you put in the credentials.
```


```bash
yaay! Now you're a guest and the page says not to peep your neighbour’s profile. Mmmmmmm!
```


```bash
So again we can view the page source.
```


```bash
And now here you got some hints for the admin page and we know we are still logged in guest.
```


```bash
So now as we know that this challenge is IDOR , so try to change the ‘guest’ with ‘admin’ to login as admin.
```


```bash
aaaaaa! You're now logged in as admin and you got the flag > flag{***************}
```


```bash
Now submit the flag.
```
```bash
Thus using IDOR vulnerability, we bypassed the authentication.
```


Hope this was helpful. thank you!
