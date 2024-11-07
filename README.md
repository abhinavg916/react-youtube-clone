# React YouTube Clone

![cover](https://github.com/abhinavg916/react-youtube-clone/blob/main/YouTube%20Clone%20Cover.png)

Watch the live production build here i.e. **deployment** - [Live Preview](https://672c96effae3994251b3d588--lively-alfajores-8d4a03.netlify.app/)

**Developed** using Reactjs, Axios, React Router, Material UI and Rapid API

**Steps to run**

- Setup RAPID API
  - Sign into Rapid API then search for "[YouTube v3](https://rapidapi.com/ytdlfree/api/youtube-v31)" and opt for free plan.
  - Select Suggested Videos endpoint from left panel then on right panel select Target as `Nodejs` and Client as `Axios` from the dropdowns.
  - Copy the value of `x-rapidapi-key` from the `options` object.
  - Paste the key's value into `.env` local file of this source code and save the file.
- Run the following commands

```
npm i
npm start
```

- NOTE: Please create your own account on Rapid API platform and use your own key in `.env`
- NOTE: Tested on Node version 18.18.0
