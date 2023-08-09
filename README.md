# Taiga - Open source, Agile project management software

~ _Added by Nimish Kashyap_

**IMPORTANT:** This application requires at least 8GB of RAM and 2 core CPU to operate properly. Make sure you're environment has these requirements.

For persistent storage, you'll be needing around 2 GB of storage for smooth operation with the base variant. You can modify the storage requirements through the application definition during deployment.

Steps - 
1. Select catalog application.
2. Populate Secret and config map accordingly.
3. Deploy the application.
4. Wait for the backgrounds processes (migrations and rabbitmq connections) to setup (around 5 mins)

**NOTE**: If you have your own Domain name configured for TAIGA, then follow this guide:  https://docs.napptive.com/guides/custom_domains.html