<style>
img {
    max-width: 60%;
    height: auto;
}

.sidebar-nav li {
    color: blue; /* Change color to blue */
}

.search-box {
    border: 2px solid blue; /* Add border */
    border-radius: 5px; /* Add border radius */
    padding: 5px 10px; /* Add padding */
}

.search-btn {
    background-color: blue; /* Change background color */
    color: white; /* Change text color */
    border: none; /* Remove border */
    border-radius: 5px; /* Add border radius */
    padding: 5px 10px; /* Add padding */
    cursor: pointer; /* Add cursor pointer */
}

.search-btn:hover {
    background-color: darkblue; /* Change background color on hover */
}
</style>

# ![Logo](./images/dsslogo.png)

# 1. Login Page

The login page is the entry point for users to access the digital signing service (DSS). It is designed to provide a secure and seamless login experience.

## 1.1. Security

The login page is secured using industry-standard encryption protocols to protect user credentials and data.

### 1.1.1. Login Credentials

Users can log in using their registered email address and password, which are securely stored and encrypted. The user will need to agree to the terms and conditions to proceed, by ticking on the relevant check box.

![Login Credentials](images/1.1.1.jpeg)

### 1.1.2. Two-factor Authentication Option

For enhanced security, account administrators have the option to enable two-factor authentication (2FA), which sends a verification code to the registered email.

### 1.1.3. Password Reset

Users can reset their password using a secure and straightforward process.

The user requesting the password reset clicks on the “Reset password” link

![Password Reset](images/1.1.3(1).jpeg)

and is redirected here 

![Password Reset](images/1.1.3(2).jpeg)

# 2. Home Page

The home page serves as the main dashboard for users, providing quick access to essential features and information.

## 2.1. Left-side Panel

The left-side panel displays navigation options, allowing users to easily switch between different sections of the digital signing service.

### 2.1.1. Avatar

Users can personalize their account by uploading an avatar image, which is displayed on the top-left side of the home page.

![Avatar](images/2.2.0.0.png)

#### More Info

The 'more info' icon represented by the yellow ‘i’ symbol provides additional information or context for specific features or sections of the digital signing service.

### 2.1.2. Sign Out

Users can securely sign out of their account to protect their privacy and data. This can be done by pressing the sign-out button.

## 2.2. Document Upload Panel

The upload document panel allows users to upload documents for digital signing.

![Document Upload Panel](images/2.2.0.jpeg)

## 2.3. Filters Panel (right-side)

The right-side panel has filters that allow the user to switch between different tabs, these being Inbox, Outbox, Complete, Voided, and Saved for Later.

![Filters Panel](images/2.3.0.jpeg)

### 2.3.1. Inbox

The inbox displays documents initiated by other parties that require the logged-in user's signature. The user can sign a document, preview it, or view more details.

![Inbox](images/2.3.1.jpeg)

### 2.3.2. Outbox

The outbox displays documents which the current user has initiated for other parties to sign. The user can preview a document or view more details.

![Outbox](images/2.3.2.jpeg)

### 2.3.3. Complete

The complete section lists successfully signed documents that are relevant to the currently logged-in user. The user can preview a document or view more details.

![Complete](images/2.3.3.jpeg)

### 2.3.4. Voided

The voided section displays documents that have been canceled or invalidated, either by the current user or by other signers. Users are able to preview the document and view more details.

### 2.3.5. Saved for Later

Users can save documents for later action by themselves, other signers, or both. The user is able to sign the document, add other signers, preview, and view more details.

![Saved for Later](images/2.3.5.jpeg)
# 3. Document Signing Process

The document signing process involves several steps to ensure a smooth and secure signing experience for all parties involved.

## 3.1. Uploading a Document

The first step in the signing process is to upload the document that requires signatures. Users can do this from the document upload panel, accessible from the home page. They can either drag and drop PDF documents onto the upload pane or select one from their computers.

![Document Upload](images/3.1.0(1).jpeg)


![Document Upload](images/3.1.0(2).jpeg)

### 3.1.1. Signing Options

Once the document is uploaded, users are presented with several signing options:

- **'I want to sign myself now':** This option takes the user directly to the signing page.
- **'I want to send to others to sign':** Users can choose to send the document to other parties for signing, without signing it themselves.
- **'I want to save for later':** This option saves the document to the 'Saved for Later – Unsigned' tab for future action.
- **'I want to cancel and upload again':** Users can cancel the current upload process and return to the home page.

## 3.2. Signing a Document Initiated by Another Party

When a document is sent to a third-party for signing, the recipient receives a signing request via email.

## 3.3. Signing Process Options

Once on the signing page, the signer is presented with various options to interact with the document:

![Signing Process](images/3.3.0.jpeg)

### 3.3.1. Signature Placement

Users can choose where to place their signature:

#### 3.3.1.1. Sign on Current Page

This option allows users to place their signature only on the current page of the document.

![Sign Current Page](images/3.3.1(3).jpeg)


![Sign Current Page](images/3.3.1(4).jpeg)

#### 3.3.1.2. Sign on All Pages

This option places the signature on the same position across all pages of the document.

### 3.3.2. Stamp

Users can also place a stamp on the document, similar to a signature, but with predefined images or text.

### 3.3.3. Text Annotations

The DSS allows users to add text annotations to the document, positioning them as needed using their cursor.

### 3.3.4. Decline Signing

If the signer chooses not to sign the document, they can select 'Decline Signing' and provide a reason for voiding the process.

![Decline Signing](images/3.3.4.jpeg)

### 3.3.5. Final Signed Document & Signing Report

Once the signing process is complete, both the initiator and all signers receive an email confirming successful signing. The email includes a copy of the signed document and a signing report.

This comprehensive process ensures that documents are securely signed and properly managed within the digital signing service.

# 4. Admin Dashboard

The admin dashboard is a centralized hub for administrators to manage user accounts, settings, and integrations.

## 4.1. Creating New User Account

Administrators can create new user accounts, assign roles, and manage permissions. This can be done by clicking on the ‘Create user’ button on the admin dashboard. The admin will then add the user’s details and submit.

![Create User](images/4.1.0.png)

### 4.1.1. Change Organization Logo

Administrators can customize the front-end of the DSS by uploading the organization's logo. This can be done by clicking on the ‘Change logo’ option on the admin dashboard.

![Change Logo](images/4.1.1.jpeg)

### 4.1.2. System Logs

The system logs provide a detailed log of user activity. The logs can be filtered and exported as the case may apply.

![System Logs](images/4.1.2.jpeg)

### 4.1.3. Mailer Settings

Administrators can configure email settings, such as SMTP server details, for sending notifications and alerts.

### 4.1.4. Integrations

The digital signing service supports integrations with third-party systems, providing flexibility and interoperability. The service provides an SDK which developers can leverage for such integrations.

# 5. FAQs

- Where is the DSS hosted?
  A: The DSS is hosted on Microsoft’s Azure Cloud.

- Can a user upload multiple documents at a time?
  A: This is a feature currently under development and is scheduled for release soon.
