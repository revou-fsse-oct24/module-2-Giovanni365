# Workaholic Blog
Workaholic blog is collections of articles made by workaholic. It features articles about workplace includes people experience, tips, suggetions and many more. The objective of the blog is to give reader insight about workplace.

# Deployment Guide
This guide is to explain how to deploy Workaholic Blog by using netifly

### **Step 1: Sign Up Netifly and Connect Netifly to Github**
1. Open [netifly](https://www.netlify.com/) and click sign up or login if you already had the account
![Sign Up](./Readme%20Picture/Sign%20up.png)
2. If you choose sign up, you can choose to sign up with github or email
![Github](./Readme%20Picture/Connect%20github.png)
3. After finish sign up, login to your dashboard
![Dashboard](./Readme%20Picture/Dashboard.png)

### **Step 2: Deploy Project on Netifly**
1. To deploy your project on netifly choose import existing project from git
![Import](./Readme%20Picture/Import.png)
2. Choose github to authorize Netlify to access your GitHub repositories and select repository you want to deploy
![Deployment](./Readme%20Picture/Deployment.png)
3. Choose your site name and check the availability of the name. Choose deploy after finish inputing the site name
![Name](./Readme%20Picture/Site%20Name.png)
4. Check the site to ensure your site is working
![Site](./Readme%20Picture/Finish%20Deploying.png)

### **Custom Domain and Configure DNS**
1. To custom domain purchase domain name from a provider. This website use niagahoster to purchase domain name
2. Set up custom domain in netifly
![Setting](./Readme%20Picture/Set%20up.png)
3. Add the purchased custom domain
![Purchased-name](./Readme%20Picture/Purchased%20name.png)
4. In production domains click set up Netifly DNS and verify the purchased domain
![Domain](./Readme%20Picture/Verify%20Domain.png)
5. Netifly will show your domain name servers
![nameserver](./Readme%20Picture/Update%20domain%20name.png)
6. In your domain provider settings, replace the default DNS with Netlify DNS
![change-server](./Readme%20Picture/Change%20nameserver.png)
7. After the DNS records are configured, wait fo a few minutes for deployment with custom domain
![custom-domain-site](./Readme%20Picture/Finish.png)

# Deployed website
Click [here](https://worka-holic.site/) to checkout the deployed workaholic blog with custom domain: worka-holic.site
