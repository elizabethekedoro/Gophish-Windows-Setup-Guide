<div align="center">

<!-- Replace with your actual logo -->
<img src="https://github.com/user-attachments/assets/06311142-89fd-4566-a0d6-392c097ec0d1" height="70%" width="100%" alt="Gophish Logo"/>


# Gophish-Windows-Setup-Guide-By-Elizabeth-Ekedoro


</div>

---

## ⚠️ Disclaimer

> **This guide is intended for authorized security testing and security awareness or educational purposes only.**  
> Elizabeth Ekedoro is **not responsible** for any misuse, unauthorized activity, or damage resulting from the use of <br/> the information provided in this guide.  
> Using this tool against any individual or organization **without explicit written permission is illegal**.  
> Unauthorized phishing campaigns may violate individual rights, organizational policies and applicable laws.


<h2>What is Gophish</h2>
Gophish is a free, open-source phishing simulation framework designed to help security professionals conduct <br/> realistic phishing awareness campaigns. It enables you to: 

- Create and send simulated phishing emails.
- Measure how susceptible users are to phishing attacks.
- Identify users who require additional security awareness training.
- Evaluate the effectiveness of organizational security awareness programs.

<h2>Requirements</h2>
Before getting started, ensure you have the following: 

- A Windows computer.
- Internet connection.
- A Gmail account.
- 2FA enabled for the Gmail account.
- Administrator access on your computer.
  <br />
<h2>Project walk-through:</h2>

<details>
<summary><b>Step 1: Installing Gophish</b></summary>
<br />
<p align="center">  
Visit the Gophish website --> https://getgophish.com
<img src="https://github.com/user-attachments/assets/80484d38-676c-40a8-bc9e-14f610e87f22" height="70%" width="70%" alt="Gophish Windows Setup Guide"/>
<br/>
<br/>
  
<p align="center">
Click Download: <br/>
<img src="https://github.com/user-attachments/assets/1f91134e-fc7b-4ba3-8c43-ef90fb0578f8" height="70%" width="70%" alt="Gophish Windows Setup Guide"/>
<br />
<br />

<p align="center">
Scroll down to the Assets section and select the Windows Zip file: <br/>
<img src="https://github.com/user-attachments/assets/2c19bfe3-93ce-4b55-8805-0a22ca3dbd75" height="70%" width="70%" alt="Gophish Windows Setup Guide"/>
<br />
<br />

<p align="center">
Choose a folder where you want to save the ZIP file and click Save: <br/>
<img src="https://github.com/user-attachments/assets/f3fba04a-c0a8-4dbc-b762-5a269fe52671" height="70%" width="70%" alt="Gophish Windows Setup Guide"/>
<br />
<br />

<p align="center">
After the download completes, navigate to the Gophish zip file, Right click and select Extract All: <br/>
<img src="https://github.com/user-attachments/assets/b880f550-e998-48cf-87d4-62cb88828043" height="70%" width="70%" alt="Gophish Windows Setup Guide"/>
<br />
<br />

<p align="center">
Choose your preferred extraction location and click Extract: <br/>
<img src="https://github.com/user-attachments/assets/c51a1a0a-11b1-45b9-aab7-a1fc0b3fbba3" height="70%" width="70%" alt="Gophish Windows Setup Guide"/>
<br />
<br />

<p align="center">
Wait until extraction is complete: <br/>
<img src="https://github.com/user-attachments/assets/1f4992da-764a-467a-b3db-3b18b77051e5" height="70%" width="70%" alt="Gophish Windows Setup Guide"/> <br/>
  <p align="center">
The extracted folder will contain the Gophish executable and all required files.
<br />
<br />

</details>

<!-- Step 2 -->
<details>
<summary><b> Step 2: Configuring Gophish</b></summary>
<br/>
  
<p align="center">
Open the extracted folder / Unzipped File: <br/>
<img src="https://github.com/user-attachments/assets/64930fa2-9aaa-4ee2-8911-fe4ccd64e59e" height="70%" width="70%" alt="Gophish Windows Setup Guide"/>
<br />
<br />

<p align="center">
Right-click the gophish.exe file and select Run as administrator: <br/>
<img src="https://github.com/user-attachments/assets/ac6561c4-9ad0-4e22-adeb-46bfef4ea593" height="70%" width="70%" alt="Gophish Windows Setup Guide"/>
<br />
<br />

<p align="center">
If Windows prompts you to allow the application through the firewall, click Allow: <br/>
<img src="https://github.com/user-attachments/assets/15bce0ec-f10a-4120-8470-4516cd7820bd" height="70%" width="70%" alt="Gophish Windows Setup Guide"/> <br/>

<br />
<br />
<p align="center">
Once Gophish installs successfully, the terminal window will display the default administrator credentials: <br/>
<img src="https://github.com/user-attachments/assets/3ce8b706-0e43-4869-8f04-6ed07f9927e6" height="70%" width="70%" alt="Gophish Windows Setup Guide"/>
<br />
  
Note down the following information: <br/>

- Username: admin.
- Password: Your unique 16-character generated password displayed in your terminal.
- Gophish Server URL: https://127.0.0.1:3333.

Copy and save these credentials in your Notepad.

<br />

**Accessing the Gophish Interface/Platform** <br/>
<p align="center">
Open your web browser and navigate to the gophish Server: https://127.0.0.1:3333<br/>
<img src="https://github.com/user-attachments/assets/f5904416-1a42-4597-91b8-95271e368677" height="70%" width="70%" alt="Gophish Windows Setup Guide"/>
<br />
<br />
<p align="center">
Since Gophish uses a self-signed certificate, your browser will display a security warning. Click Advanced:<br/>
<img src="https://github.com/user-attachments/assets/22003085-d1c0-425d-aa96-661d64407b16" height="70%" width="70%" alt="Gophish Windows Setup Guide"/>
<br />
<br />

<p align="center">
Select, Proceed to 127.0.0.1 (unsafe):<br/>
<img src="https://github.com/user-attachments/assets/28ea8ba4-525e-4ae8-8245-49b7a73d37f0" height="70%" width="70%" alt="Gophish Windows Setup Guide"/> <br/>
<p align="center">
This is expected because the server is running locally.
<br />
<br />

**Logging Into Gophish** <br/>

Enter the following: <br/>

- Username: admin.
- Password: Your unique 16-character generated password displayed your terminal.

<p align="center">
Click Sign In:<br/>
<img src="https://github.com/user-attachments/assets/56cf2b39-d1d8-45ee-9352-95f35baa4061" height="70%" width="70%" alt="Gophish Windows Setup Guide"/>
<br />

 <p align="center">
The first time you log in, Gophish will prompt you to reset your password. <br/> Choose a strong password and click Save Password:<br/>
<img src="https://github.com/user-attachments/assets/4c185f7d-c8a1-4d98-aa53-f18dc3b21abb" height="70%" width="70%" alt="Gophish Windows Setup Guide"/> <br/>

<br />   
<p align="center">
After signing in successfully, you will see the Gophish dashboard.
<img src="https://github.com/user-attachments/assets/b0c8a8ea-302f-411b-a39f-0a4534f91cde" height="70%" width="70%" alt="Gophish Windows Setup Guide"/>
<br />

**The left navigation pane contains the following sections:** <br/>

- Dashboard
- Campaigns
- Users & Groups
- Email Templates
- Landing Pages
- Sending Profiles
- Account Settings
- User Management
- Webhooks
  
<br/> 
</details>


<!-- Step 3 -->

<details>
<summary><b> Step 3: Configuring Sending Profile</b></summary>
<br/>
A Sending Profile contains the SMTP settings Gophish uses to send phishing simulation emails. <br/>
<br />
  
<p align="center">
To create one: Click >Sending Profiles, then click >New Profile: <br/>
<img src="https://github.com/user-attachments/assets/7a5ce8c3-6aca-487b-a3c5-8450484b035e" height="70%" width="70%" alt="Gophish Windows Setup Guide"/>
<br />

**Configure the following:**

<table style="border-collapse: collapse; width: 100%;">
    <tr>
        <th style="border: 1px solid #000; padding: 8px; text-align: left;">Field</th>
        <th style="border: 1px solid #000; padding: 8px; text-align: left;">Description</th>
    </tr>
    <tr>
        <td style="border: 1px solid #000; padding: 8px;">Profile Name</td>
        <td style="border: 1px solid #000; padding: 8px;">Give your profile a descriptive name, example: Phishing Simulation</td>
    </tr>
    <tr>
        <td style="border: 1px solid #000; padding: 8px;">Interface Type</td>
        <td style="border: 1px solid #000; padding: 8px;">This is selected by default.</td>
    </tr>
    <tr>
        <td style="border: 1px solid #000; padding: 8px;">SMTP From</td>
        <td style="border: 1px solid #000; padding: 8px;">Enter the email address that will appear as the sender, example: yourgmail@gmail.com</td>
    </tr>
  <tr>
        <td style="border: 1px solid #000; padding: 8px;">Host</td>
        <td style="border: 1px solid #000; padding: 8px;">For Gmail SMTP, use either "smtp.gmail.com:465" or "smtp.gmail.com:587" </td>
    </tr>
   <tr>
        <td style="border: 1px solid #000; padding: 8px;">Uername</td>
        <td style="border: 1px solid #000; padding: 8px;">Enter the same Gmail address used in the SMTP From field, example: yourgmail@gmail.com</td>
    </tr>
   <tr>
        <td style="border: 1px solid #000; padding: 8px;">Password</td>
        <td style="border: 1px solid #000; padding: 8px;">Do not use your normal Gmail password. Instead, <br/> 
          Click <a href="https://github.com/elizabethekedoro/How-to-Create-App-Password-for-Gmail" target="_blank">Here</a> for a quick step-by-step guide to generate your App Password.
        </tr>
    </tr>
</table>
<br/>
<p align="center">
<img src="https://github.com/user-attachments/assets/eb384151-f9b6-4cfb-8c2d-7ecaba1f48f4" height="70%" width="70%" alt="Gophish Windows Setup Guide"/>
<br />

<p align="center">
After creating your App password, paste the App Password into the Password field.<br/>
Enable >Ignore Certificate Errors, and leave everything else as default <br/>
<img src="https://github.com/user-attachments/assets/f4119871-3053-4784-99df-671e5c98dbad" height="70%" width="70%" alt="Gophish Windows Setup Guide"/>
<br />


<br/>
<br/>

**Testing the Sending Profile Configuration**

<p align="center">
To test your configurations so far: Click > Send Test Email: <br/>
<img src="https://github.com/user-attachments/assets/410ff4f9-5c03-474e-92e2-3ca86700419a" height="70%" width="70%" alt="Gophish Windows Setup Guide"/>
<br />

<p align="center">
Input your details and, click > Send: <br/>
<img src="https://github.com/user-attachments/assets/4929987e-12c8-43fc-88f0-fb36e609b15a" height="70%" width="70%" alt="Gophish Windows Setup Guide"/>
<br />
<br />

<p align="center">
Statu so far: Email Sent as seen in the screenshot below. <br/>
<img src="https://github.com/user-attachments/assets/5ea66d78-10d7-489d-87f7-d085eb2ed952" height="70%" width="70%" alt="Gophish Windows Setup Guide"/>
<br />

<p align="center">
If the email arrives successfully in your inbox, the SMTP configuration is working correctly. <br/>
<img src="https://github.com/user-attachments/assets/ee99431f-0d6c-4944-b591-6cc7e2b5b123" height="70%" width="70%" alt="Gophish Windows Setup Guide"/>
<br />

<p align="center">
Return to the Sending Profile page and click >Save Profile: <br/>
<img src="https://github.com/user-attachments/assets/70bff4b1-3575-4cec-a02e-832f1a9058c3" height="70%" width="70%" alt="Gophish Windows Setup Guide"/>
<br />.
<br />

<p align="center">
You have successfully configured your Sending Profile and it is now ready for use. <br/>
<img src="https://github.com/user-attachments/assets/c606e89b-19ff-4b1b-86f7-ce56beb85f75" height="70%" width="70%" alt="Gophish Windows Setup Guide"/>
<br />.
<br />
  
</details>


<!-- Step 4 -->
<details>
<summary><b> Step 4: Setting up Landing Page</b></summary>
<br />

<p align="center">
A landing page is the webpage a user is redirected to when they click the phishing link contained in an email. <br/>
<br />
  
<p align="center">
To create a landing page, click >Landing Pages on the left-hand pane, then click >New Page: <br/>
<img src="https://github.com/user-attachments/assets/60627790-90ef-4f5e-80ef-d7e386d767a2" height="70%" width="70%" alt="Gophish Windows Setup Guide"/>
<br />
<br />

**Setup the following:**
<table style="border-collapse: collapse; width: 100%;">
    <tr>
        <th style="border: 1px solid #000; padding: 8px; text-align: left;">Field</th>
        <th style="border: 1px solid #000; padding: 8px; text-align: left;">Description</th>
    </tr>
    <tr>
        <td style="border: 1px solid #000; padding: 8px;">Name</td>
        <td style="border: 1px solid #000; padding: 8px;">Enter a name for your landing page. For this tutorial, I will use >Fake Instagram Simulation.</td>
    </tr>
  
   <tr>
        <td style="border: 1px solid #000; padding: 8px;">HTML</td>
        <td style="border: 1px solid #000; padding: 8px;">Click the HTML tab and use the HTML sample I have prepared on my GitHub. <br/> 
          To access the sample, click <a href="https://github.com/elizabethekedoro/Gophish-Windows-Setup-Guide/blob/main/Landing%20Page%20Template/Instagram.html" target="_blank">Here</a>
        </tr>
    </tr>
</table>

<p align="center">
Copy and paste the HTML code into the >HTML editor: <br/>
<img src="https://github.com/user-attachments/assets/c5d66522-d9ff-4116-b4cc-0f8c027a9177" height="70%" width="70%" alt="Gophish Windows Setup Guide"/>
<br />
<br />

<p align="center">
To preview what the landing page looks like, click >Source: <br/>
<img src="https://github.com/user-attachments/assets/86d60cc2-33c4-4ea4-bb5b-f325690c9715" height="70%" width="70%" alt="Gophish Windows Setup Guide"/>
<br />
<br />

<p align="center">
select >Capture Submitted Data and >Capture Passwords: <br/> 
This is to esnure the login credentials entered during the simulation will be captured, which you will see at the end of this exercise.
 <br/>
<img src="https://github.com/user-attachments/assets/a606db0e-fd69-4bf5-b59d-05a4cf78cda3" height="70%" width="70%" alt="Gophish Windows Setup Guide"/>
<br />
<br />

<p align="center">
You have successfully setup your Landing Page and it is now ready for use. <br/> 
<img src="https://github.com/user-attachments/assets/d7ec6cb1-9d4b-4ae2-8f4e-d160ccf65f8f" height="70%" width="70%" alt="Gophish Windows Setup Guide"/>
<br />
<br />
  
</details>

<!-- Step 5 -->
<details>
<summary><b> Step 5: Setting up Email Template</b></summary>

<p align="center">
Sign in to your Google account <br/>
<br />
  
<p align="center">
Click your profile picture: <br/>
<img src="https://github.com/user-attachments/assets/c8ca86fb-fb5f-41cb-a616-3946fae74764" height="70%" width="70%" alt="Gophish Windows Setup Guide"/>
<br />
<br />


</details>


<!-- Step 6 -->

<details>
<summary><b> Step 6: Setting Up Users & Groups</b></summary>

<p align="center">
Sign in to your Google account <br/>
<br />
  
<p align="center">
Click your profile picture: <br/>
<img src="https://github.com/user-attachments/assets/c8ca86fb-fb5f-41cb-a616-3946fae74764" height="70%" width="70%" alt="Gophish Windows Setup Guide"/>
<br />
<br />


</details>


<!-- Step 7 -->

<details>
<summary><b> Step 7: Launching a Phishing Campaign</b></summary>

<p align="center">
Sign in to your Google account <br/>
<br />
  
<p align="center">
Click your profile picture: <br/>
<img src="https://github.com/user-attachments/assets/c8ca86fb-fb5f-41cb-a616-3946fae74764" height="70%" width="70%" alt="Gophish Windows Setup Guide"/>
<br />
<br />

**Testing the Phishing Campaign**

**Launching the Phishing Campaign**
</details>


<!-- Step 8 -->

<details>
<summary><b> Step 8: Viewing the Phishing Campaign Result in Real-time</b></summary>

<p align="center">
Sign in to your Google account <br/>
<br />
  
<p align="center">
Click your profile picture: <br/>
<img src="https://github.com/user-attachments/assets/c8ca86fb-fb5f-41cb-a616-3946fae74764" height="70%" width="70%" alt="Gophish Windows Setup Guide"/>
<br />
<br />

</details>

##  Video walkthrough
* Coming soon!


<div align="center">

**Made with so much ❤️ by Elizabeth Ekedoro**

*Use responsibly. Use ethically.*

</div>
