# Google Clone with Next.js

It is the clone of the Google where you can search for anything and it will show the exactly same result we've used the Google Custom API through which we made this project, this is full responsive and you can also install it as the PWA. You can visit the links as well not danger in that, but there is one drawback of this that Google only allow 100 request from single API KEY per day. So this application can search only 100 times a day.

## Features

- Realtime and Accurate Google Search
- Full Screen mode
- Installable **PWA**
- Search Any Query
- Full Responsiveness
- Dark Theme support based on user's device

## Technologies used

<p>  
<img title="React JS" width="60" src="https://cdn4.iconfinder.com/data/icons/logos-3/600/React.js_logo-128.png" />
<img title="Next JS" width="60" src="https://iconape.com/wp-content/files/gm/82643/svg/next-js.svg"  />&nbsp;
<img title="Tailwind" width="60" src="https://cdn.icon-icons.com/icons2/2699/PNG/512/tailwindcss_logo_icon_167923.png"> 
<img title="Google Search API" width="60" src="https://cutt.ly/zRgpYnW">
</p>

## Demo

[Click Here to see the Live Demo]()


## Getting Started

Create a directory or a folder

```bash
  mkdir project
```

Clone the project

```bash
  git clone github-url
```

Go to the project directory

```bash
  cd project
```

Install dependencies

```bash
  npm install
  # or
  yarn
```

First, run the development server:

```bash
  npm run dev
  # or
  yarn dev
```

Open http://localhost:3000 with your browser to see the result.

You can start editing the page by modifying pages/index.js. The page auto-updates as you edit the file.

API routes can be accessed on http://localhost:3000/api/hello. This endpoint can be edited in pages/api/hello.js.

The pages/api directory is mapped to /api/\*. Files in this directory are treated as API routes instead of React pages.

## Environment Variables

To run this project, you will need to add the following environment variables to your .env file

`NEXT_PUBLIC_API_KEY` - [Click Here](https://developers.google.com/custom-search/v1/introduction#identify_your_application_to_google_with_api_ke)

- Go to link and click on **Get a Key**
- If you've already created a project than continue with it else create a new one and follow the steps after completing you'll get the API KEY

`NEXT_PUBLIC_CONTEXT_KEY` - [Click Here](https://cse.google.com/cse/create/new)

- Go to link and type `www.google.com` and click **Create**
- then click on `Get Code` 
 - you will get the script file tag in that file such as `<script async src="https://cse.google.com/cse.js?cx=b221ffffddfd63f8a4"></script>` we  only need the `cx` value *copy* that and paste in you `.env` 

## License

[MIT](https://choosealicense.com/licenses/mit/)

## Feedback

If you have any feedback, please reach out to us at jatinsharma089659@gmail.com

## Developer

- [@j471n](https://github.com/j471n/)
