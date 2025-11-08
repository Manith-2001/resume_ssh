# Resume over SSH 

Most people nowadays create websites as portfolios and attach them to their resume. In order to try and do something different I created Resume over SSH. 
Easily accessible by anyone in the comfort of their own terminal all they have to do is run the following command:
```bash
ssh -p 23234 resume.home-network.site
```
(Please execuse the weird domain name its a throw away cheap domain that I bought to complete my self hosting needs)

![ssh_resume](https://github.com/user-attachments/assets/1f5aadcd-4951-4fb4-b3ed-3c77752da8c0)

## Set it up for yourself

To use this project you need to have ```docker``` installed.<br>
Add the content that you would like to add for your resume inside the ```resume.md``` file.<br> And Et Voilà! you are set to run your own resume over ssh after 
executing :
```
docker compose up -d
```
Additionally you can also get a VPS and a domain name and set it up just like I have

## TODO :
- I will be adding some figlet art to make it look a bit more stylised
- Add a few more TUI components present in the bubbles repository
- Add a bit more color as it is too monochrome and simple right now
