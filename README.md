# BlazorJSFileES2019

Because blazor `blazor.x.js` does not support old devices, we need build blazor js file. https://github.com/dotnet/maui/discussions/27327

## Use

1. Download from https://github.com/Yu-Core/BlazorJSFileES2019/releases. 
2. Create `_framework` folder under the `wwwroot` folder. Copy `blazor.x.es2019.js` to `_framework`
3. Edit `App.razor` or `index.html`. Replace `blazor.x.js` with `blazor.x.es2019.js`

>> If you want to specify the version, fork this repository and run GitHub actions