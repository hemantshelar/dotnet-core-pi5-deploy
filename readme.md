
### Deployment


Refering to [this](https://learn.microsoft.com/en-us/dotnet/iot/deployment) link for the deployment. 

- `dotnet publish --runtime linux-arm64 --self-contained`
- `scp -r /C:/data/learning/pi/dotnet-core-pi5-deploy/bin/Release/net9.0/linux-arm64/publish/* hemant@chickencoop:/home/hemant/pi/dotnet-core-pi5-deploy`    
- `chmod +x ./dotnet-core-pi5-deploy.dll`