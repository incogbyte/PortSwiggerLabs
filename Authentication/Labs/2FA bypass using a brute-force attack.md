
1. In this Lab you'll need the Session Handling from Burp suite, to handling features to log back in automatically before sending each request.
2. Configure the Session Handling
![](/static/img/Pasted_image_20231107112426.png)
3. Configure the macro recorder

![](/static/img/Pasted_image_20231107112700.png)

4. Choose the requests and click OK

![](/static/img/Pasted_image_20231107112833.png)

5. Test the macro recorder, verify that the apps ask to you insert the 2FA digits

![](/static/img/Pasted_image_20231107112958.png)
6. Send the login2 to intruder
7. Configure the intruder min/max digits to 4 and the Resource pool to 1 thread

![](/static/img/Pasted_image_20231107113353.png)

![](/static/img/Pasted_image_20231107113422.png)
8. Start the attack and wait until 302 status appears
![](/static/img/Pasted_image_20231107114510.png)
9. Lab solved
![](/static/img/Pasted_image_20231107114543.png)


