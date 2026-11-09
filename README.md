# Burpsuite_repo


## This repo holds the answers to week4 question 3 


### Subtask 1

<img width="3238" height="295" alt="kuva" src="https://github.com/user-attachments/assets/57cb3912-2d6e-4987-9edb-a06cfd63ed5f" />

<img width="2551" height="1326" alt="kuva" src="https://github.com/user-attachments/assets/c7253c48-710b-4973-a000-e5e3aa506f13" />


### Subtask 2

<img width="2866" height="1192" alt="kuva" src="https://github.com/user-attachments/assets/c63ef429-a8a4-407d-b53a-2c379b588a24" />

the cookie is session id is created by incrementing some variable. This incrementation seems to be based on time as the faster you refresh the token the less it increments, but the more you wait the more the incrementation is. technically this makes it possible to gain access to a users session based on when they logged in.

### Subtask 3

<img width="3445" height="1468" alt="kuva" src="https://github.com/user-attachments/assets/8f3b279e-364a-4ac9-b7d5-b13af0943a36" />

<img width="1549" height="918" alt="kuva" src="https://github.com/user-attachments/assets/643a8f29-19b1-440d-a7a1-01103174a599" />

as we can see from the pictures there seem to be two instances where a combination of username and password worked. in instances 9 and 16 the response length is a bit longer and when we scroll down the response we can see on line 87 that we are welcomed to the secret area. this can be visually seen in the second picture.

### Subtask 4

<img width="3304" height="1645" alt="kuva" src="https://github.com/user-attachments/assets/e3088398-7580-4960-a52c-3286cffcaee5" />


### Subtask 5

start time with the password set to "barb"
<img width="3835" height="2158" alt="kuva" src="https://github.com/user-attachments/assets/c2a7d023-c5d2-4ac1-8bad-51e51926a848" />


ending time
<img width="3769" height="2076" alt="kuva" src="https://github.com/user-attachments/assets/5c658f37-0fae-49a3-941d-d5c0c64d107a" />

all together the bruteforce tookaround 12 minutes to run.

command
<img width="1875" height="205" alt="kuva" src="https://github.com/user-attachments/assets/be4a2fe7-b0c6-4143-ab3d-81e05b935341" />

