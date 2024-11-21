# How to Get Started with our API 
![Dev Portal Logo](https://prd-mktg-konghq-com.imgix.net/images/2023/08/64e10ce8-ui-dev-portal.png?auto=format&fit=max&w=2560)
Welcome to our Developer Portal! This guide will walk you through the steps to create an account, register an application, subscribe to an API, and manage your application credentials using OpenID Connect.
---
## Step 1: Create an Account

To get started, you'll need to create an account on our Developer Portal.

**1. Register on the Developer Portal Homepage**
- Go to [Developer Portal](https://example.com).
- Click on the **Sign Up** button.
- You can register using your email address

**3. Confirm Your Account**
- Check your email for a confirmation link.
- Click on the link to verify your account.
---
## Step 2: Create an Application

After setting up your account, you'll need to create an application to interact with the API.

1. **Navigate to the Applications Section**
- Go to **My Applications** from your dashboard.
- Click on **Create New Application**.

2. **Fill in Application Details**
- Provide a name and description for your application.
- Enter the **Redirect URI** where users will be redirected after authentication.

3. **Save and Obtain Credentials**
- After saving, you’ll receive your `Client ID` and `Client Secret`.
- These credentials are essential for authenticating your application with OpenID Connect.
---
## Step 3: Subscribe to an API

Now that your application is set up, you can subscribe to an API.

**1. Browse Available APIs**
- Go to the **Catalog** from the main menu.
- Choose the API Product you want to subscribe to.

**2. Select a Subscription Plan**
- Review the API’s documentation and select a subscription plan.
- Click on **Subscribe** to link your application with the API.
---
## Step 4: Generate and Manage Your Credentials

With your application registered and API subscription in place, it’s time to generate and manage your application credentials.

**1. Generate and manage OAuth Tokens**
- Use your `Client ID` and `Client Secret` to generate access tokens.
- This can be done using our API or directly from the Developer Portal.
- You can view, revoke, and regenerate tokens from the **My Applications** section.

**3. Authenticate API Requests**
- Include the generated access token in your API requests as a Bearer token.
- This ensures that your requests are authenticated and authorized.
---
## Conclusion

Congratulations! You’ve successfully created an account, registered an application, subscribed to an API, and managed your credentials using OpenID Connect. For more detailed API documentation, visit our [API Docs](https://konghq.com/docs).

If you have any questions or need further assistance, feel free to reach out to our support team.

---
