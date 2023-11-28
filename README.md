# custom-fonts-add
1. create assets/fonts folder 
2. download fonts and extract 
3. copy and paste .tff file into fonts folder
4. create react-native.config.js file
    * put this code into react-native.config.js file and save
        ```js
        module.exports = {
            projects: {
                ios: {},
                android: {},
            },
            assets: ['./assets/fonts/'],
        };
```
5. Now, open cmd in project folder enter
    npx react-native-asset + enter

6.Follow this video
   https://www.youtube.com/watch?v=Fmb63An6ujc&pp=ygUdY3VzdG9tIGZvbnRzIGFkZCByZWFjdCBuYXRpdmU%3D
