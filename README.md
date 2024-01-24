# Cloudflare Secure Resume Website 

<h2>Description</h2>
In this project, I have successfully developed and deployed a static resume website, leveraging the robust capabilities of AWS S3 and the advanced domain and security features of Cloudflare. The journey began with coding the website from scratch, creating an intuitive and visually appealing interface to showcase my professional journey.

To host the website, I chose Amazon S3 for its reliability and ease of use. I configured an S3 bucket to make it publicly accessible, ensuring my resume was available online. The integration with Cloudflare started with registering a custom domain name, providing a professional touch to my online presence.

A crucial aspect of this project was ensuring website security and performance. I accomplished this by setting up a client certificate with Cloudflare, enabling the use of their CDN services. This not only secured my site but also optimized content delivery. The process involved redirecting my domain to Cloudflare, which then securely connected it to my S3 bucket. This setup ensured that visitors to my site enjoyed a secure, fast, and seamless browsing experience.

Through this project, I have demonstrated my skills in web development, cloud services, and network security, creating a professional online resume that is both secure and scalable.
<br />


<h2>Tools Used</h2>

- <b>AWS S3</b> 
- <b>Cloudflare Domain Registrar/ DNS (Domain Name Service</b>
- <b>Cloudflare Client Certificates</b>
- <b>Cloudflare CDN (Content Delivery Netowkr)</b>

<h2>Environments Used </h2>

- <b>AWS</b>
- <b>Cloudflare</b>

<h2>Project walk-through:</h2>

<p align="center">
Launch S3 Bucket with Custom HTML, CSS, Javascript Coding (with unique name): <br/>
<img src="https://i.imgur.com/3XJxeTP.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Create Domain Name with Cloudflare:  <br/>
<img src="https://i.imgur.com/91yDfPq.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Change Name Servers to Direct to Cloudflare: <br/>
<img src="https://i.imgur.com/B1VJodj.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Use Cloudflare to get Client Certificate Securing Site:  <br/>
<img src="https://i.imgur.com/Meky0c4.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Redirect Traffic from Domain to CDN then Securly Connecting to Resume Site:  <br/>
<img src="https://i.imgur.com/OLjVWL0.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Secure Site with Cloudflare:  <br/>
<img src="https://i.imgur.com/G9O1gNw.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
