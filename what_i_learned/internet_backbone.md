# Internet Backbone

![Imgur](https://i.imgur.com/Lz1TadA.png)

The router in our home is what is giving us Wi-Fi. This router is connected to your modem. The modem is something that transmits signals (requests) to different towers to communicate with your ISP.  

Your ISP is connected to the internet backbone. So, what is the _internet backbone_ exactly? Well, it’s a physical cable that is placed in the bottom of the seafloor that is connected to places all over the world!

[Submarine Cable Map](https://www.submarinecablemap.com/)  This website visually represents all of the cables that are connected to different areas in the world. These cables transport the text files (HTML, CSS, and Javascript) to our browser so that we’re able to access any website on our web browser.

Essentially, you’re allowing this transferring of files from one computer to another, transferring knowledge from Brazil to Portugal to India to *wherever* which means you are apart of a big network.

# Trace Route

![Imgur](https://i.imgur.com/9LYTbY4.png)

The image above is our terminal running the `$ traceroute google.com` command. What trace route does is.. it helps us monitor the transferring of files between your computer and the DNS that Google is located in.

From the example above, we see that it has taken us 9 hops to get to Google. Each hop is a different computer that is trying to pinpoint where Google is so that you can access it!

**Note**: If you see `***` (asterisk) in your output then that means a packet is not acknowledged within the expected timeout (5 seconds), an asterisk is displayed. Sometimes this can be due to your internet connection or `trace route` may show `***` because of widespread use of firewalls and other security practices by the company that owns the server.
