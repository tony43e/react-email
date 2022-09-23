![React Email cover](https://react-email-assets.vercel.app/react-email.png)

<div align="center"><strong>React Email</strong></div>
<div align="center">Build and send emails using React.<br />High-quality, unstyled components for creating emails.</div>
<br />
<div align="center">
<a href="https://react.email">Website</a> 
<span> · </span>
<a href="https://github.com/zenorocha/react-email">GitHub</a> 
<span> · </span>
<a href="https://react.email/discord">Discord</a>
</div>

## Introduction

A collection of high-quality, unstyled components for creating beautiful emails using React and TypeScript.
It reduces the pain of coding responsive emails with dark mode support. It also takes care of inconsistencies between Gmail, Outlook, and other email clients for you.

## Why

We believe that email is an extremely important medium for people to communicate. However, we need to stop developing emails like 2010, and rethink how email can be done in 2022 and beyond. Email development needs a revamp. A renovation. Modernized for the way we build web apps today.

## Install

Install one of the components from your command line.

#### With yarn

```sh
yarn add @react-email/button -E
```

#### With npm

```sh
npm install @react-email/button -E
```

## Getting started

Add the component to your email template. Include styles where needed.

```jsx
import { Button } from '@react-email/button';

const Email = () => {
  return (
    <Button href="https://example.com" style={{ color: '#61dafb' }}>
      Click me
    </Button>
  );
};
```

## Components

A set of standard components to help you build amazing emails without having to deal with the mess of creating table-based layouts and maintaining archaic markup.

* [Html](https://github.com/zenorocha/react-email/tree/main/packages/html)
* [Head](https://github.com/zenorocha/react-email/tree/main/packages/head)
* [Button](https://github.com/zenorocha/react-email/tree/main/packages/button)
* [Link](https://github.com/zenorocha/react-email/tree/main/packages/a)
* [Image](https://github.com/zenorocha/react-email/tree/main/packages/img)

## Support

All components were tested using the most popular email clients.

| <img src="https://user-images.githubusercontent.com/398893/191876837-b18f9fe6-03d3-45b5-8e9a-b65f11e89c0d.svg" width="48px" height="48px" alt="Gmail logo"> | <img src="https://user-images.githubusercontent.com/398893/191876835-8b7aac96-2828-417b-a42e-289ad10fe003.svg" width="48px" height="48px" alt="Apple Mail"> | <img src="https://user-images.githubusercontent.com/398893/191876838-5fb588ca-7049-484a-a39e-b066cea0d4bf.svg" width="48px" height="48px" alt="Outlook logo"> | <img src="https://user-images.githubusercontent.com/398893/191876840-a09aa330-ffa2-40bf-9571-778569507002.svg" width="48px" height="48px" alt="Yahoo! Mail logo"> | <img src="https://user-images.githubusercontent.com/398893/191876839-c1f6a5d4-a7d1-452b-9a74-8484f149c1d9.svg" width="48px" height="48px" alt="Superhuman logo"> |
|-------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Gmail ✔                                                                                                                                                     | Apple Mail ✔                                                                                                                                                | Outlook ✔                                                                                                                                                     | Yahoo! Mail ✔                                                                                                                                                     | Superhuman ✔                                                                                                                                                     |

## Development

#### Install dependencies

  ```sh
yarn install
  ```

#### Build and run packages

  ```sh
yarn dev
  ```

This will initialize all packages in parallel and watch for changes, including the website which will be available at [localhost:3000](http://localhost:3000).

## Authors

- Bu Kinoshita ([@bukinoshita](https://twitter.com/bukinoshita))
- Zeno Rocha ([@zenorocha](https://twitter.com/zenorocha))

## License

MIT License
