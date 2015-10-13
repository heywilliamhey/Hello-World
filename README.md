# Hello-World
First repo
How does email work? What is DNS?

First the email is composed in a mail client like Microsoft Outlook, for example.

The email is composed of a Header, and a Body. 

The header includes information about the message i.e.; From, Date, To, CC. the email has to 

have an address in the form of user@domain.ext. The body is the message you intend to send.

The email is sent by the mail client to an outgoing mail server via Simple Mail Transfer Protocol, 

SMTP. The SMTP does not read email addresses, it uses an Internet Protocol address or IP 

address. The IP address is needed to get that email or package to the proper location. 

If the SMTP server does not already know the recipient’s IP address it sends the email address 

to a Domain Name Server, DNS server which locates the recipient’s IP address. The website 

www.howtogeek.com, describes the DNS server quite well. “The DNS server is a sort of phone 

or address book for the internet; it translates domains like “arrakis.com” to an IP address like 

“74.238.23.45.”…  This is like your post office consulting maps of where your mail is supposed 

to go, calling their local post office, and checking to see if your friend has a mailbox or P.O. box 

to receive mail.”

The SMTP server can now send the message from the server to the intended domain’s  mail 

exchange server, MTA or Mail Transfer Agent. The MTA will route the package to the correct 

mailbox and will be ready for the other user to read.
