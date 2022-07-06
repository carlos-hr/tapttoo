# EVOB FrontEnd Test

Frontend challenge built for participation in selection process of EVOB company

## Project requirements

---

- Create your project using Next.js and Typescript
- Compose the login screen following the design described in:
  Figma: https://www.figma.com/file/sP4N5PeWWkd3jJuYNdJU36/Teste-Frontend-EVOB?node-id=0%3A1
- Fill in the visual elements (text and logo) received through the endpoint:
  get - https://front.evob.dev.marcomapa.com/front_challenge/info
- Send the filled [email] and [password] fields as form-data to the endpoint:
  post - https://front.evob.dev.marcomapa.com/front_challenge/login
- Display the API returns to the user
  Test data:
  Email: testfront@evob.com.br Password: 123456
  Any other user or password will return: "Usuário/Senha inválidos"

---

What will be evaluated:

- Clean Code;
- Organization;
- Pixel Perfect;
- Best Practices;
- Responsiveness

---

## Final implementation

### Adjustments and improvements

As improvements to the project I made the decision to implement:

- [x] Loader Spinner when making login request;
- [x] Warnings with toast library for user feedback;
- [x] Ajuste de navegação entre páginas no deploy vercel;


### :robot: Technologies:

To develop the application I used Next together with Typescript and styled-components, and API was provided by EVOB to request the data. Using the base url `https://front.evob.dev.marcomapa.com/front_challenge` consulting the method [`GET /info`] to access the visual elements of the application, and the method [`POST /login/`] to authenticate a user.

### :books: Libraries used

  <li>React Icons</li>
  <li>React Loader Spinner</li>
  <li>React Toastify</li>
  <li>Styled Components</li>

## Getting Started

To run the project locally, follow these steps:

Clone this repository on your computer and run the command:

```bash
npm install
# and
npm run dev
# or
yarn dev
```

Open http://localhost:3000 with your browser to see the result.

## Deploy on Vercel

The application is deployed with vercel in the link https://tapttoo.vercel.app/
