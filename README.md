
<p align="center">
  <img src="https://github.com/KRochaS/ignite-challenge-ii-chapter-iv/blob/master/.github/ignite-reactjs.svg" width="520" > 
</p>
<p align="center">
  <img src="https://github.com/KRochaS/ignite-challenge-ii-chapter-iv/blob/master/.github/logo.svg" width="200" > 
</p>
<p align="center">
  <img src="https://github.com/KRochaS/ignite-challenge-ii-chapter-iv/blob/master/.github/challenge.svg" width="160" > 
</p>

<p align="center">	
   <img src="https://img.shields.io/badge/-ReactJS-DD6B20?style=flat&logoColor=white" />
  
   <img src="https://img.shields.io/badge/-React Query-DD6B20?style=flat&logoColor=white" />
   
  <img src="https://img.shields.io/badge/-React Hook Form-DD6B20?style=flat&logoColor=white" />
   
   <img src="https://img.shields.io/badge/-ChakraUI-DD6B20?style=flat&logoColor=white" />
</p>

## :bar_chart: About
Challenge focused on enhancing skills in ReactJS, React Query, React Hook Form and Chakra UI. The application already boasts various functionalities and stylings. The main objective was to add some code snippets to ensure the proper functioning of the image upload feature.

## :books: Technologies e libs  

- [React](https://pt-br.reactjs.org/)
- [React Query](https://tanstack.com/query/v3/)
- [React Hook Form](https://react-hook-form.com/)
- [Typescript](https://www.typescriptlang.org/)
- [Chakra UI](https://chakra-ui.com/)

##  💡 Technology Features
  #### React Query:     
  - Infinite Queries: Employed in this application to load images stored in the database. The loading mechanism is implemented with a single click on a button.
        <br />
  - Mutations: Typically used for data retrieval, mutations are responsible for creating/editing/removing data. In the application, they are utilized for registering a new image in the database.
         <br />
  - Invalidations: Used to manually mark a query as stale and force data refresh. Applied in this application to mark the image listing query as stale when the mutation to register a new image is successfully executed.

  #### React Hook Form: 
  - useForm: Implementation of input registration for the image registration form, including input validations and error handling.
#### Chakra UI
  - Modal e Toast

## 🔄 Modified Files

- [src/pages/index.tsx](https://github.com/KRochaS/ignite-challenge-ii-chapter-iv/blob/master/src/pages/index.tsx);
- [src/components/Form/FormAddImage.tsx](https://github.com/KRochaS/ignite-challenge-ii-chapter-iv/blob/master/src/components/Form/FormAddImage.tsx);
- [src/components/Modal/ViewImage.tsx](https://github.com/KRochaS/ignite-challenge-ii-chapter-iv/blob/master/src/components/Modal/ViewImage.tsx);
- [src/components/CardList.tsx](https://github.com/KRochaS/ignite-challenge-ii-chapter-iv/blob/master/src/components/CardList.tsx).

##  All To-Do's

- [x] Axios request with param
- [x] Get and return next page param
- [x] Format and flat data array
- [x] Render loading screen
- [x] Render error screen
- [x] Render load more button if data has next page
- [x] Required, less than 10 MB, and accepted formats validations
- [x] Required, min and max length validations
- [x] Required, max length validations
- [x] Mutation API post request
- [x] OnSuccess mutation
- [x] Show error toast if image URL does not exist
- [x] Execute async mutation
- [x] Show success toast
- [x] Show error toast if submit failed
- [x] Clean form, states, and close modal
- [x] Register image input with validations
- [x] Send title errors
- [x] Register title input with validations
- [x] Send description errors
- [x] Register description input with validations
- [x] Modal with image and external link
- [x] Modal useDisclosure
- [x] Selected image URL state
- [x] Function handle view image
- [x] Card grid
- [x] ModalViewImage

## :computer: Application Overview
 
<p align="center">
  <img src="https://github.com/KRochaS/ignite-challenge-ii-chapter-iv/blob/master/.github/upfi.gif" width="986" >
</p>


### Notion Challenge 

The detailed description of the challenge can be found at:

<a href="https://efficient-sloth-d85.notion.site/Desafio-02-Upload-de-imagens-4cf1c3b1c1ad4a66961b6e48558cc3b8#7db52665701341318733d686696a3e09">
  <img src="https://img.shields.io/badge/Notion%20%20-PTBR-DD6B20">
</a>

