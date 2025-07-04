The following post will include almost everything that i think grey hack is missing in terms of quality of life and details.
## Browser update
adding multiple tabs on the browser and making the RAM usage act accordingly,
combining it with html's <title> method, you could have tabs with names on them
if powerUI doesnt support that you could create a custom parser to find the title.
another cool feature would be to change the cursor with html page via cursor: default; cursor: pointer;
to hint the user on what he can do, and generally add better UX.
another crucial feature is to link to another website, could be used with `href="www.website.com"`
the scroll bar feature is extremly needed, since we already know its possible with javascript.
you could add the script snippet to the bottom of the code, or you could add it somehow through unity, like many other scrollable apps.
another feature that is really good but very hard to add is multiple html pages, so the link would look like: `"www.website.com/index.html"`
(`www.website.com` would take you automatically to `www.website.com/index.html`)
so you could also href another html file in same directory, and index is the default.
basically like subdomains, you could link to a specific page within a website.
and of course, it wouldnt hurt to add a little bit more fonts for customization.
lastly, remove forcing to use www. prefix on websites.
### Browser update
- Multiple browser tabs
    - Working <title></title> methods
- Cursor modes, at least `pointer`, and `default`
- Linking to outside websites
- Scrollable web pages by default.
- multiple html pages 
- more fonts & remove www. prefix force.
## Ransomware & DDOS.
currently ransomware & ddos have no reason to be used.
### Ransomware
ransomware lockdown requires root permissions, if you have that you might aswell look into Config/Bank.txt
i think a cool feature could be a checkbox of "always remember me" so that it doesnt force you to create bank.txt
### DDOS
DDOS seems to be going in a good direction so far, but my main addition would be - 
to make shops your main source of income, that could mean lowering the rewards from hackshop missions,
in order to sell software and/or hardware
that way you can stop someones main income,
## PDFs
a feature to add PDF files with that, the PDF reader would need an overhaul - to edit PDF files
but it really doesnt have to be complicated, what i like about the PDF files is that they are readable, and .txt are not, if you could add a .pdf file to your website, if you need to make a user manual or some guide of some kind, pdf editing and creating would make it a whole lot more enjoyable for both sides(seller & buyer) 
## Programming & Apps
### Reboot
I hope a reboot feature would come to light, `reboot(computer, bool safemode)` probably makes the most sense
<br>with that, the /bin/reboot source code should be available aswell.
### AdminMonitor.exe
I really liked the old admin monitor.
and now i think with the latest features, adding a way to check if admin/super admin is online(if superadmins sleep or something)
<br>is very important, if you could create your own admin monitor that would be extremly cool.
### Sniffer
i think the sniffer program should pick up when you login to a bank/email
or any form of http communication.. 
any ssh connection etc.. its basically system.log but in real time.
that way you could also encrypt http connection to result in a mini-https
so when someone sniffs your router he might be able to get credentials for bank etc..
The format might be:<br>
```source: localip<br>
destination: publicip
data: mpjpo = vtfsnfb\oqbttxpss = qbttxpss234
simple caesar cipher of +1 **only** to letters.
```
so you could play with encryptions & such<br>
## Filesystem
### Downloads folder
i would assume files by default would go to the Downloads folder of the current user.
### /Public/htdocs
as mentioned before in ##Browser update multiple html files in Public/htdocs would be awesome.
<br>i think the default html name should be renamed from `website.html` to `index.html`

## .deep suffix
instead of a .onion suffix to websites a .deep could be used
<br>This means that you would not be able to resolve the IP via nslookup
<br>but there are downsides:<br>
- This **only** works on rented remote servers **NOT HOME SERVERS**
- using whois on the IP will reveal the domain name(this can be changed but i think its better that way.)
    - putting the IP in the browser will lead to the same webpage
    - Doesnt show up in `Recent websites` or `Popular websites` or `Feeling lucky`
- Optional: encrypts the IP in http logs on server side(imitates the anonimity feature of the actual .onion websites)
    - you can either encrypt it via a simple base64 or number cipher or actually random IP or just redacted etc..
### Conclusion: .deep suffix
this only protects against the usual nslookup and doesnt show either in recent websites nor in popular websites, and not in Feeling lucky.
<br>
This feature grants a simple layer of anonimity at the cost of less convinience or "fame" per say.
## Those are my main inqueries.
if someone else wants to add please do(in the discord server)


