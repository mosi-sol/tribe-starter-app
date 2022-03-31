### app-starter
---

tribe web3 proposal -> [watch here](https://relay.tribeplatform.com/general/post/web3-on-tribe-q4sqVCoWdfLyUBB)
tribe react web3 doc -> [read here](https://github.com/mosi-sol/react-sdk-tutorial/blob/main/README.md)

---

# WEB3 on Tribe 

WEB3 on Tribe: 
hello all tribism.

announcement of how to create DAPP (web3 / decentralized application) on Tribe platform.

for declare at the start/begin: 2 ways for doing this perpuse/goal.

### 1- from core (just the main core developers can do this)

***the first way*** : need to implement some dependencies on react(react is the core i think), then make module for users, simple and easy.

### 2- from user dashboard interface.

***the second way*** : at this section -> https://partners.tribe.so/portal/apps you can have own apps(modules). on the **custom code** panel add following code.


```
<script> 
{% if member.username == "Guest" %} 
/*ethereum.enable(); */ 
if(ethereum.isMetaMask) { 
    ethereum.enable(); 
} 
else{ 
    alert('install meta mask'); 
} 
{% else %} 
if(ethereum.isMetaMask) { 
    ethereum.enable(); 
} else{ 
    alert('install meta mask'); 
} 
{% endif %} 
</script>
```

sadly this code need 2 things:

- 1.installed metamask on client side.
- 2.loged in (not locked wallet). <-- fixed

---

this post/proposal just for core team member (siavash mahmoudian), because i want to be a part of TRIBE team as soon :)

my name is mosi (mosipvp[at]gmail).{from 42 person has invited}



### atfer reading this file, now watch [DEMO](https://relay.tribeplatform.com/)
just remember to unlock metamask for testing the code.
