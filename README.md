# DVWA_Initial_Setup

## Step 1
  Run the DVWA docker through terminal
  ```
  sudo docker run --rm -it -p 80:80 vulnerables/web-dvwwa
  ```
## Step 2
  Open the browser enter `http://localhost/login.php`

## Step 3
  Now enter credentials for Username: `admin` Password: `password`

<p align="center"><img width="240" height="240" alt="image" src="https://github.com/user-attachments/assets/9c6c1812-427c-4518-a57e-7196e2843844" /></p>

## Step 4
  Click on  `Create / Reset Database`
<p align="center"><img width="650" height="200" alt="image" src="https://github.com/user-attachments/assets/b83ad2b3-9b5a-4755-9e3e-47fb6bd7b9c3" /></p>

-----
### Step 5
  Configure Proxy for Burp Suite to work. 
  First open the BurpSuite tool and do the following steps that captured below.
<p align="center"><img width="500" height="200" alt="image" src="https://github.com/user-attachments/assets/8e5ef056-1275-46af-8442-a531a81dadf0" /></p>

### Step 6
  Then head to `Settings` within Burp and do the following configurations.
<p align="center"><img width="500" height="350" alt="image" src="https://github.com/user-attachments/assets/acbe0ef8-d41a-404f-8226-53fb706a9329" /> </p>

### Step 7
  In the meantime locally add the proxy as listed bellow, via `Settings` on the `Network` tab. 
<p align="center"><img width="350" height="200" alt="image" src="https://github.com/user-attachments/assets/5463867f-ceb2-45d6-9e73-a1b198fe479d" /> </p>

### Step 8
  Finally we need to configure the extension called `Foxy Proxy` <br>
 [Click](https://addons.mozilla.org/en-US/firefox/addon/foxyproxy-basic/) to  add the extension. <br>
 Then add the following configurations.
<p align="center"><img width="500" height="240" alt="image" src="https://github.com/user-attachments/assets/0275b518-ba4b-4fb3-ae63-a46d9abaf0e2" /> </p>

  Lastly, do not forget to turn on the proxy!
<p align="center"><img width="170" height="160" alt="image" src="https://github.com/user-attachments/assets/781dc200-16f4-4462-8307-bade22419053" /></p>

-----
