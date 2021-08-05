# Surge-Action


Copy these two lines below to Successfully deploy your app on surge. 
We are adding Surge token in your secrets and change the sample project to your website name.    


      - name: Deploying on Surge
        run: surge ./build Sample-Project.surge.sh --token ${{secrets.SURGE_TOKEN}}
