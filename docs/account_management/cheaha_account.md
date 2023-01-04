# Cheaha Account Management

These instructions are intended to guide researchers on creating and managing their [Cheaha](../cheaha/index.md) account.

## Creating a New Account

Creating a new account is a simple, automated, self-service process. To start, navigate to <https://rc.uab.edu>, our [Open OnDemand](../cheaha/open_ondemand/index.md) web portal, and authenticate. The authentication process differs depending on your affiliation, but all Cheaha accounts are authenticated using Single Sign-on (SSO). Accounts are available to researchers with the following affiliations.

- **UAB Campus**: authenticate with your BlazerID credentials.
- **UAB Medicine (UABMC)**: authenticate with your BlazerID credentials. UABMC credentials are not supported.
- **External Collaborator**: authenticate with your XIAS email address and the password created during XIAS account creation. If you do not yet have a XIAS account, you will need to follow the instructions at our [XIAS page](xias/index.md). Communicate with your sponsore to ensure that `https://rc.uab.edu` is included in the list of approved URIs.

Once you have authenticated, you should see a page that looks like the following.

![!UAB self registration page.](./images/uab_self_register_001.png)

The form should be prefilled with your BlazerID or XIAS ID, full name, and email address. If any of these details are incorrect please [Contact Support](../help/support.md). Please also fill out the reason you wish to create an account. To create a Cheaha account, you must check both boxes affirming your acceptance of relevant UAB IT policies. Until both boxes are checked, the "Create Account" button will not be usable.

When you are ready, click "Create Account" to start the account creation process. You should see a popup notification that looks like the following. After a few moments you should be redirected to our [Open OnDemand](../cheaha/open_ondemand/index.md) web portal. If not, please [Contact Support](../help/support.md).

![!Account creation notification popup](images/uab_self_register_002.png)

Welcome to Cheaha and to Research Computing! Please visit our [Cheaha Getting Started page](../cheaha/index.md) to learn more about using Cheaha.

## Managing an Existing Account

If you already have an account and wish to check it's status, please visit your account status page at <https://rc.uab.edu/account>.

### Account in Good Standing

If your account is in good standing you should see a page like the following.

![!Account in good standing page.](images/uab_good_standing.png)

### Account Requires Certification

We review accounts periodically to ensure the system is being used fairly and as intended. Part of this process is to certify that researchers with accounts still wish to make use of Cheaha. Once per year every researcher will be required to certify their account before making use of Cheaha. If you account requires certification, when logging in to our [Open OnDemand](../cheaha/open_ondemand/index.md) web portal you will see the following notification page.

![!Account certification notification page.](images/uab_certify_001.png).

To certify your account, click the button to be taken to the certification form, which should look like the following.

![!Account certification form.](images/uab_certify_002.png)

While the certification form looks similar to the new account creation form, please be sure to review all of the information carefully. To certify your account, you must check both boxes affirming your acceptance of relevant UAB IT policies. Until both boxes are checked, the "Create Account" button will not be usable.

When you are ready, click "Certify Account" to start the account creation process. You should see a popup notification confirming the process is working. After a few moments your account should be certified and you will be free to use Cheaha again. If not, please [Contact Support](../help/support.md).

### Account on Hold

Mistakes happen, and sometimes what we thought we programmed wasn't quite what we actually programmed. When these kinds of mistakes occur, excess resources may get used. If this impacts performance or other users excessively, we may put a hold on your account. We may also put a hold on your account if you do not complete [Account Certification](#account-requires-certification) when required.

Other reasons for holds include, but are not limited to:

- Misuse (intentional or not) of Research Computing resources
- [IT Policy](https://www.uab.edu/it/home/policies) violations
- [HIPAA](https://www.uab.edu/it/home/policies/compliance/hipaa) or [FERPA](https://www.uab.edu/registrar/ferpa) violations related to use of Cheaha
- As part of a required investigation

In rare circumstances, we may also place a hold on your account if you possess the sole copy of data not owned by you.

If your account is on hold, you will see a page like the following.

![!Account on hold page.](images/uab_on_hold.png)

If you SSH into the cluster while your account is on hold you will see the following text in your terminal.

![!Account on hold SSH reply.](images/uab_on_hold_ssh.png)

If your account is on hold and we have not already contacted you, or you believe the hold to be in error, please [Contact Support](../help/support.md).

### Authorization Error

Periodically, we review all researcher accounts to ensure they are authorized to use Cheaha based on affiliation status. If we find a researcher is no longer affiliated with UAB, we may disable the account. If you are not authorized to use Cheaha, you will see a page like the following.

![!Account authorization error page.](images/uab_auth_error.png)

If you believe this to be in error, please [Contact Support](../help/support.md).
