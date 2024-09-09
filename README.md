# OhSINT

This is an OSINT practice room.

## Note:

An image file is provided, seemingly just an old Windows wallpaper. However, its metadata reveals two interesting details: a GPS location and an author's name. After some digging, we can find further clues.

![Old Windows Wallpaper](https://github.com/sagar-sehrawat/THM-OhSINT-writeup/blob/main/img/windows_old.jpg)

### Metadata Analysis:

![Metadata Analysis](https://github.com/sagar-sehrawat/THM-OhSINT-writeup/blob/main/img/img1.png)
  
From the image's metadata, I found the author's name and their social media handles.

### Social Media Discovery:

After identifying the author, I located their Twitter account and found an interesting avatar.

![Twitter Avatar](https://github.com/sagar-sehrawat/THM-OhSINT-writeup/blob/main/img/img7.png)

#### Q-1: What is this user's avatar of?
- **Answer:** Cat

On their GitHub account, they have only two repositories. After exploring them, I discovered more information.

![GitHub Profile](https://github.com/sagar-sehrawat/THM-OhSINT-writeup/blob/main/img/img3.png)

#### Q-2: What city is this person in?
- **Answer:** London

One Twitter post revealed a BSSID. Using the BSSID, I searched for the SSID they connected to.

![BSSID Twitter Post](https://github.com/sagar-sehrawat/THM-OhSINT-writeup/blob/main/img/img2.png)

After searching the BSSID online and clicking on the map results, I found the person's location is indeed in London. The SSID is `UnileverWiFi`.

#### Q-3: What is the SSID of the WAP he connected to?
- **Answer:** UnileverWiFi

#### Q-4: What is his personal email address?
- **Answer:** OWoodflint@gmail.com (You can find this on their GitHub account.)

#### Q-5: What site did you find his email address on?
- **Answer:** GitHub

![GitHub Email](https://github.com/sagar-sehrawat/THM-OhSINT-writeup/blob/main/img/img4.png)

The person has also mentioned going to New York for a holiday on their WordPress blog.

#### Q-6: Where has he gone on holiday?
- **Answer:** New York

![WordPress Blog](https://github.com/sagar-sehrawat/THM-OhSINT-writeup/blob/main/img/img5.png)

Finally, after searching through their GitHub, Twitter, and WordPress, I found their password hidden within the page source of the WordPress site.

![Password in Source Code](https://github.com/sagar-sehrawat/THM-OhSINT-writeup/blob/main/img/img8.png)

#### Q-7: What is the person's password?
- **Answer:** (Include the discovered password)

![Password Confirmation](https://github.com/sagar-sehrawat/THM-OhSINT-writeup/blob/main/img/img6.png)
