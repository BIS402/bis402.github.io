---
title: "Publishing Your Hugo Site on Netlify"
date: 2021-10-24T18:50:26-04:00
draft: true
---

You have a Hugo site created and also have a GitHub repository for the
site. Now, you can deploy the site for free via Netlify.

First, if you do not already have a Netlify account, create one. Then,
login to Netlify.

If you search for your repo and do not find it, select the `Configure
Netlify` on GitHub button.

![Configure Netlify on GitHub](./images/configure-netlify.png)

Then select where, which GitHub account, you want to install Netlify:

![Install Netlify in GitHub](./images/install-netlify.png)

In the `Repository access` section select the `Only select repositories`
radio button and then the `Select repositories` drop down button. After
selecting the desired repository, select the `Save` button.

![Repository access](./images/repo-access.png)

Now you have your repo, select either its `Private` or `Public` visibility
from GitHub. In my case, this repository is `Private`:

![Continuous Deployment section](./images/continue-deploy-section.png)

Finally, make sure that you have the desired `Branch to deploy` selected
and then deploy the site to Netlify by selecting the `Deploy site` button.

![Branch to deploy](./images/branch-to-deploy.png)

Once Netlify has completed the deployment of your site, select the link
and view it.

![Select link](./images/view-deployment.png)

You can rename the subdomain of your site by selecting the `Site settings`
button

![Site settings](./images/site-settings.png)

Then, in the Site information section, select the `Change site name`
button.

![Change site name](./images/change-site-name.png)

Now, you have a published site on Netlify that will update with each
push to you main branch in your GitHub repository.
