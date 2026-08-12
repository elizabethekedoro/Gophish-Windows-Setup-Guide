<div align="center">

<!-- My Logo -->
<img src="https://github.com/user-attachments/assets/528f0fbb-efde-472d-ac31-566494d96467" height="50%" width="80%" alt="Gophish Logo"/>


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
Click >Download: <br/>
<img src="https://github.com/user-attachments/assets/1f91134e-fc7b-4ba3-8c43-ef90fb0578f8" height="70%" width="70%" alt="Gophish Windows Setup Guide"/>
<br />
<br />

<p align="center">
Scroll down to the Assets section and select the Windows ZIP file: <br/>
<img src="https://github.com/user-attachments/assets/2c19bfe3-93ce-4b55-8805-0a22ca3dbd75" height="70%" width="70%" alt="Gophish Windows Setup Guide"/>
<br />
<br />

<p align="center">
Choose a folder where you want to save the ZIP file and click >Save: <br/>
<img src="https://github.com/user-attachments/assets/f3fba04a-c0a8-4dbc-b762-5a269fe52671" height="70%" width="70%" alt="Gophish Windows Setup Guide"/>
<br />
<br />

<p align="center">
After the download completes, navigate to the Gophish zip file, right-click, and select >Extract All: <br/>
<img src="https://github.com/user-attachments/assets/b880f550-e998-48cf-87d4-62cb88828043" height="70%" width="70%" alt="Gophish Windows Setup Guide"/>
<br />
<br />

<p align="center">
Choose your preferred extraction location and click >Extract: <br/>
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
Right-click the gophish.exe file and select >Run as administrator: <br/>
<img src="https://github.com/user-attachments/assets/ac6561c4-9ad0-4e22-adeb-46bfef4ea593" height="70%" width="70%" alt="Gophish Windows Setup Guide"/>
<br />
<br />

<p align="center">
If Windows prompts you to allow the application through the firewall, click >Allow: <br/>
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

Copy and save these credentials in your Notepad or write them down.

<br />

**Accessing the Gophish Interface/Platform** <br/>
<p align="center">
Open your web browser and navigate to the gophish Server: https://127.0.0.1:3333<br/>
<img src="https://github.com/user-attachments/assets/f5904416-1a42-4597-91b8-95271e368677" height="70%" width="70%" alt="Gophish Windows Setup Guide"/>
<br />
<br />
<p align="center">
Since Gophish uses a self-signed certificate, your browser will display a security warning. Click >Advanced:<br/>
<img src="https://github.com/user-attachments/assets/22003085-d1c0-425d-aa96-661d64407b16" height="70%" width="70%" alt="Gophish Windows Setup Guide"/>
<br />
<br />

<p align="center">
Select, >Proceed to 127.0.0.1 (unsafe):<br/>
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
Click >Sign In:<br/>
<img src="https://github.com/user-attachments/assets/56cf2b39-d1d8-45ee-9352-95f35baa4061" height="70%" width="70%" alt="Gophish Windows Setup Guide"/>
<br />

 <p align="center">
The first time you log in, Gophish will prompt you to reset your password. <br/> Choose a strong password and click >Save Password:<br/>
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
<br /> 
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
        <td style="border: 1px solid #000; padding: 8px;">For Gmail SMTP, use this: "smtp.gmail.com:465". If you test and it does not work, try this: "smtp.gmail.com:587" </td>
    </tr>
   <tr>
        <td style="border: 1px solid #000; padding: 8px;">Username</td>
        <td style="border: 1px solid #000; padding: 8px;">Enter the same Gmail address used in the "SMTP From" field, example: yourgmail@gmail.com</td>
    </tr>
   <tr>
        <td style="border: 1px solid #000; padding: 8px;">Password</td>
        <td style="border: 1px solid #000; padding: 8px;">Do not use your normal Gmail password (It will not work). Instead, <br/> 
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
Status so far: Email sent, as seen in the screenshot below. <br/>
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
You have successfully configured your Sending Profile, and it is now ready for use. <br/>
<img src="https://github.com/user-attachments/assets/c606e89b-19ff-4b1b-86f7-ce56beb85f75" height="70%" width="70%" alt="Gophish Windows Setup Guide"/>
<br />.
<br />
  
</details>


<!-- Step 4 -->
<details>
<summary><b> Step 4: Setting up Landing Page</b></summary>
<br />
<br />
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
        <td style="border: 1px solid #000; padding: 8px;">Enter a name for your landing page. For this tutorial, I will use "Fake Instagram Simulation".</td>
    </tr>
  
   <tr>
        <td style="border: 1px solid #000; padding: 8px;">HTML</td>
        <td style="border: 1px solid #000; padding: 8px;">Click the HTML tab and use the HTML sample I have prepared on my GitHub. <br/> 
          To access the Landing Page Template, click <a href="https://github.com/elizabethekedoro/Gophish-Windows-Setup-Guide/blob/main/Landing%20Page%20Template/Instagram.html" target="_blank">Here</a>
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

- Select >Capture Submitted Data and >Capture Passwords: (This is to ensure the login credentials entered during the simulation will be captured, which you will see at the end of this exercise). <br/> 
- Redirect to: Enter the URL where you want the user to be redirected after submitting the page. eg https://Instagram.com: <br/> 
- Finally, click >Save Page.
 <br/>
 <p align="center">
<img src="https://github.com/user-attachments/assets/a606db0e-fd69-4bf5-b59d-05a4cf78cda3" height="70%" width="70%" alt="Gophish Windows Setup Guide"/>
<br />
<br />

<p align="center">
You have successfully set up your Landing Page, and it is now ready for use. <br/> 
<img src="https://github.com/user-attachments/assets/d7ec6cb1-9d4b-4ae2-8f4e-d160ccf65f8f" height="70%" width="70%" alt="Gophish Windows Setup Guide"/>
<br />
<br />
  
</details>

<!-- Step 5 -->
<details>
<summary><b> Step 5: Setting up Email Template</b></summary>
<br />
<br /> 
<p align="center">
An email template is the content of the email that will be sent to the target(s). You can either import an existing email or create one from scratch. <br/>
<br />
  
<p align="center">
To create an email template, click >Email Templates and then click >New Template: <br/>
<img src="https://github.com/user-attachments/assets/0702a063-a2f0-4687-ad4c-bee310aee0c4" height="70%" width="70%" alt="Gophish Windows Setup Guide"/>
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
        <td style="border: 1px solid #000; padding: 8px;">Enter a name for your template. For this tutorial, I will use "Fake Instagram Simulation." </td>
    </tr>

   </tr>
    <tr>
        <td style="border: 1px solid #000; padding: 8px;">Envelope Sender</td>
        <td style="border: 1px solid #000; padding: 8px;">Enter the sender's name and email address you want recipients to see. Since I am mimicking Instagram,<br/> for this tutorial I will use, "Instagram< security@mail.instagram.com >" </td>
    </tr>  
    <tr>
        <td style="border: 1px solid #000; padding: 8px;">Email Subject</td>
        <td style="border: 1px solid #000; padding: 8px;">This is where you can create a sense of urgency. For this tutorial, I will use:<br/> 
"Urgent: Suspicious Activity on Your Instagram Account" </td>
    </tr>
  
   <tr>
        <td style="border: 1px solid #000; padding: 8px;">HTML</td>
        <td style="border: 1px solid #000; padding: 8px;">Click the HTML tab and use the HTML sample I have prepared on my GitHub. <br/> 
          To access the Email Template, click <a href="https://github.com/elizabethekedoro/Gophish-Windows-Setup-Guide/blob/main/Email%20Template/Instagram.html" target="_blank">Here</a>
        </tr>
    </tr>
</table>

<p align="center">
Copy and paste the HTML code into the >HTML editor: <br/>
<img src="https://github.com/user-attachments/assets/01d356f8-57d0-4e70-b014-11e0f9b48128" height="70%" width="70%" alt="Gophish Windows Setup Guide"/>
<br />
<br />

<p align="center">
To preview what the Email Template looks like, click >Source: <br/>
<img src="https://github.com/user-attachments/assets/412ce4e5-b404-4103-8fd9-98b79c44121f" height="70%" width="70%" alt="Gophish Windows Setup Guide"/>
<br />
<br />

- Select >Add Tracking Image (To track when the email is opened): <br/> 
- Once you are satisfied with the template, click >Save Template: <br/> 
 <br/>
 <p align="center">
<img src="https://github.com/user-attachments/assets/47cc9f3c-25aa-4f83-86c9-95d92fef9912" height="70%" width="70%" alt="Gophish Windows Setup Guide"/>
<br />
<br />

<p align="center">
You have successfully setup your Landing Page and it is now ready for use. <br/> 
<img src="https://github.com/user-attachments/assets/552c3b4e-14b4-4541-84d4-f13fd2c3563f" height="70%" width="70%" alt="Gophish Windows Setup Guide"/>
<br />
<br />
  
</details>


<!-- Step 6 -->

<details>
<summary><b> Step 6: Setting Up Users & Groups</b></summary>
<br/>
<br/>
  
Users & Groups is where you create and organize the group of users you want to send the email to. <br/>
<br />
  
<p align="center">
To create a new group, click >Users & Groups and then click >New Group: <br/>
<img src="https://github.com/user-attachments/assets/e4458b4f-b597-42e4-b38e-ed974eb99d26" height="70%" width="70%" alt="Gophish Windows Setup Guide"/>
<br />
<br />

**Setup the following:**
<table style="border-collapse: collapse; width: 100%;">
<tr>
    <td style="border: 1px solid #000; padding: 8px;">Group Name</td>
    <td style="border: 1px solid #000; padding: 8px;">Enter a name for your group. For this tutorial, I will use <br/>"Fake Instagram Simulation Group."
    </td>
</tr>

<tr>
    <td style="border: 1px solid #000; padding: 8px;">First Name</td>
    <td style="border: 1px solid #000; padding: 8px;">
         Enter the recipient's first name (e.g., Ekedoro)
    </td>
</tr>
  
  <tr>
    <td style="border: 1px solid #000; padding: 8px;">Last Name</td>
    <td style="border: 1px solid #000; padding: 8px;">
         Enter the recipient's last name (e.g., Ekedoro)
    </td>
</tr>

<tr>
    <td style="border: 1px solid #000; padding: 8px;">Email</td>
    <td style="border: 1px solid #000; padding: 8px;">
         Enter the recipient's email (e.g. sekanalyt@gmail.com)
    </td>
</tr>

<tr>
    <td style="border: 1px solid #000; padding: 8px;">Position</td>
    <td style="border: 1px solid #000; padding: 8px;">
        Enter the recipient's position (e.g., CEO)
    </td>
</tr>  
</table>

- Select >Add (After inputting the required details): <br/> 
- Once you are satisfied, click >Save Changes: <br/>
<p align="center">
<img src="https://github.com/user-attachments/assets/334b5e95-e9dd-4307-80a1-0383a46a7846" height="70%" width="70%" alt="Gophish Windows Setup Guide"/>
<br />
<br />

## 📌 Note: Bulk Import Users
 
> If you have multiple users, for example, when conducting a simulation for an organization, you do not have to <br/> enter their information one person at a time. You can import a CSV file containing the users' information.  
> For this tutorial, I am only sending the simulation to myself, so I added my details. <br/>
> Only use your own details unless you have explicit authorization or consent from an individual or organization.

- Select >Add (If you have two or more personal email addresses, you can add them as well): <br/> 
- Once you are satisfied, click >Save Changes: <br/>  
<p align="center">
<img src="https://github.com/user-attachments/assets/494cb252-2f3b-4539-8430-8fd5254d884c" height="70%" width="70%" alt="Gophish Windows Setup Guide"/>
<br />
<br />

<p align="center">
You have set up Users & Groups, and it is now ready for use. <br/> 
<img src="https://github.com/user-attachments/assets/5037429a-67c0-4481-b252-2f6ac412e968" height="70%" width="70%" alt="Gophish Windows Setup Guide"/>
<br />
<br /
</details>



<!-- Step 7 -->

<details>
<summary><b> Step 7: Launching a Phishing Campaign</b></summary>
<br/>
 <br/> 
A campaign combines the email template, landing page, sending profile, and user group you configured in the previous steps. <br/>
<br />
  
<p align="center">
To create a new campaign, click >Campaigns and then click >New Campaign: <br/>
<img src="https://github.com/user-attachments/assets/53065d71-e5a9-48cf-81f7-d842985eb15b" height="70%" width="70%" alt="Gophish Windows Setup Guide"/>
<br />
<br />

**Setup the following:**
<table style="border-collapse: collapse; width: 100%;">
<tr>
    <td style="border: 1px solid #000; padding: 8px;">Campaign Name</td>
    <td style="border: 1px solid #000; padding: 8px;">Enter a name for your campaign. For this tutorial, I will use: <br/>"Fake Instagram Simulation Campaign"
    </td>
</tr>

<tr>
    <td style="border: 1px solid #000; padding: 8px;">Email Template</td>
    <td style="border: 1px solid #000; padding: 8px;">Select "Fake Instagram Simulation", which is the Email Template created earlier.
    </td>
</tr>
  
  <tr>
    <td style="border: 1px solid #000; padding: 8px;">Landing Page</td>
    <td style="border: 1px solid #000; padding: 8px;">
       Select "Fake Instagram Simulation", which is the Landing Page created earlier.
    </td>
</tr>  
</table>

<p align="center">
<img src="https://github.com/user-attachments/assets/8cceaf8f-9fc5-4653-aef7-463e8ee4f99e" height="70%" width="70%" alt="Gophish Windows Setup Guide"/>
<br />

<table style="border-collapse: collapse; width: 100%;">
<tr>
    <td style="border: 1px solid #000; padding: 8px;">URL</td>
    <td style="border: 1px solid #000; padding: 8px;">Enter your local IP address. To find it, open your PC’s Command Prompt, type <br/> "ipconfig" and copy the IPv4 Address into the URL field.
    </td>
</tr>

<tr>
    <td style="border: 1px solid #000; padding: 8px;">Launch Date</td>
    <td style="border: 1px solid #000; padding: 8px;">This field is automatically populated. I recommend selecting the date on which <br/> you are carrying out the exercise.
    </td>
</tr>
  
  <tr>
    <td style="border: 1px solid #000; padding: 8px;">Sending Profile</td>.
    <td style="border: 1px solid #000; padding: 8px;">
       Select "Phishing Simulation", which is the Sending Profile created earlier.
    </td>
</tr>  

 <tr>
    <td style="border: 1px solid #000; padding: 8px;">Groups</td>
    <td style="border: 1px solid #000; padding: 8px;">
       Select "Fake Instagram Simulation Group", which is the Group created earlier.
    </td>
</tr> 

 <tr>
    <td style="border: 1px solid #000; padding: 8px;">Send Test Email</td>
    <td style="border: 1px solid #000; padding: 8px;">
      Click "Send Test Email". (This sends a test email to your inbox so you can review <br/>the message and fix any issues before launching the simulation).
    </td>
</tr>
</table

<br />
<p align="center">
<img src="https://github.com/user-attachments/assets/84d317d8-d5b7-46c9-88c3-34908b4d1edc" height="70%" width="70%" alt="Gophish Windows Setup Guide"/>
<br />
<br />

 **Testing the Phishing Campaign**

 Before launching the campaign, we can test the configuration to make sure everything is working correctly.
- After clicking "Send Test Email": <br/>
- Input your details and click >Send: <br/> (You can use your personal Gmail account or the Gmail account you created specifically for this exercise).
  
<p align="center">
<img src="https://github.com/user-attachments/assets/cad98ac0-fcf9-4175-b50d-386c16aaa5a0" height="70%" width="70%" alt="Gophish Windows Setup Guide"/> <br/>
  
<p align="center">
The email should now be successfully sent. Go to your Gmail inbox to verify that you received it.
    
<br />
<br />

<p align="center">
Here is the email that appears to be from Instagram, which confirms that the configuration is working correctly: <br/>
<img src="https://github.com/user-attachments/assets/71d475fd-6a08-4e70-9df3-91b90af3cc48" height="70%" width="70%" alt="Gophish Windows Setup Guide"/>
<br />
<br />

**Launching the Phishing Campaign**
<br/>
<p align="center">
Return to the Gophish Campaign interface and click >Launch Campaign: <br/>
<img src="https://github.com/user-attachments/assets/324da8d5-c9dc-4b01-86e3-3f52f9177df6" height="70%" width="70%" alt="Gophish Windows Setup Guide"/>
<br />
<br />

<p align="center">
A confirmation pop-up will appear asking whether you are sure you want to launch the campaign. Click >Launch: <br/>
<img src="https://github.com/user-attachments/assets/111279e4-2497-449c-8f29-e6f6963b3fd4" height="70%" width="70%" alt="Gophish Windows Setup Guide"/>
<br />
<br />

<p align="center">
Another pop-up will confirm that your campaign has been scheduled. Click >OK: <br/>
<img src="https://github.com/user-attachments/assets/364cb2e4-3e24-4e2a-97c7-a610aee062e5" height="70%" width="70%" alt="Gophish Windows Setup Guide"/> <br/>
🎉 You have successfully launched your phishing simulation campaign and can now view the results. <br/>  
<br />
<br />
</details>

<br />

<!-- Step 8 -->

<details>
<summary><b> Step 8: Viewing the Phishing Campaign Result in Real-time</b></summary>

<br/>
<br/>
The Dashboard allows you to view the details and results of the campaigns you have launched. <br/>
<br />

<p align="center">
To view the result, click >Dashboard: <br/>

  Here, you will see information such as: <br/>
- Email Sent
- Email Opened
- Clicked Link
- Submitted Data
- Email Reported
  
<p align="center">
<img src="https://github.com/user-attachments/assets/3cd256cd-98e9-4a6c-939c-a37f147d25f6" height="70%" width="70%" alt="Gophish Windows Setup Guide"/>
<br />
<br />

  
<p align="center">
For this exercise, open the email you received in your inbox and click the phishing simulation link. <br/> Enter random credentials into the simulated login page:
<br/>

<p align="center">
Next, return to the Gophish Dashboard and refresh the page. 
<img src="https://github.com/user-attachments/assets/f6780e32-749d-4b70-89fa-76a4cc351deb" height="70%" width="70%" alt="Gophish Windows Setup Guide"/> <br/>
You should now see that the Dashboard has been updated, allowing you to view the results and details of the interaction with the simulated phishing campaign.
<br />
<br />

<p align="center">
It successfully captured the hypothetical data I submitted, demonstrating how a phishing simulation can <br/> show the type of information an attacker may attempt to collect.
<img src="https://github.com/user-attachments/assets/c0c776f1-0425-4e61-bc23-8e16dc1e97a4" height="70%" width="70%" alt="Gophish Windows Setup Guide"/> <br/>

</details>
<br />
<br />

## 🎉 Congratulations!
You have completed the phishing simulation and demonstrated how to configure, launch, and analyze a realistic phishing campaign in a controlled environment. <br />
<br />

> **Always conduct phishing simulations only with proper authorization and use them to strengthen security awareness and defensive practices.**

<br />

Please [contact me](https://www.linkedin.com/in/ekedoro-elizabeth/) if you have any questions.
<br />

##  Video walkthrough
* Coming soon!


<div align="center">

**Made with so much ❤️ by Elizabeth Ekedoro**

*Use responsibly. Use ethically.*

</div>
