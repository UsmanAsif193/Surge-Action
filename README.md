# Surge-Action


Copy these two lines below to Successfully deploy your app on surge. 
Add Surge token in your secrets and change the sample project to your website name.    


      - name: Surge-Deploy-React-App
        uses: UsmanAsif193/Surge-Action@v1.02

      - name: Deploying on Surge
        run: surge ./build Sample-Project.surge.sh --token ${{secrets.SURGE_TOKEN}}
