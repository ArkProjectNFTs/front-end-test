# **Front-end Developer Test for ArkProject**

## **Part 1: Questions**

### **React and Next.js**:
1. Describe a situation where you would use Next.js instead of Create React App. Why?
2. How do you handle SEO in a Next.js application? 
3. What's the difference between `getStaticProps`, `getServerSideProps`, and `getInitialProps` in Next.js?

### **Tailwind CSS**:
1. How would you extend the default configuration of Tailwind in a project? Give an example.
2. Describe a situation where utility-first CSS might not be the best approach. How would you handle it?

### **React Concepts**:
1. Explain the difference between a controlled and an uncontrolled component in React.
2. How would you handle global state in a React application without using any external libraries?
3. Describe the main differences between class components and functional components in React.

### **Typescript in React**:
1. How do you define prop types in a React component using TypeScript?
2. Describe a scenario where using TypeScript with React improved the quality of your code.

### **Web3 & Starknet**:
1. Explain the main differences between Web2 and Web3 from a front-end perspective.
2. How would you handle wallet connections in a Web3 application?
3. Have you worked with Starknet or any other L2/L3 solutions before? Describe your experience.

### **Real-time Data & Hooks**:
1. How would you implement real-time data fetching in a React application?
2. Describe a custom React hook you've written and its use case.

---

## **Part 2: Simplified Coding Challenge**

### **Objective**: 
Create a basic NFT marketplace interface using React, Next.js, Tailwind CSS, and your company's APIs.

### **Resources**:

#### Alchemy (NFT API)

**Documentation**: https://docs.alchemy.com/reference/api-overview

**Https**: https://eth-mainnet.g.alchemy.com/v2/FarmxARHgNUKd8lFkQG_Vzhf68fbTGjT

**Api-Key**: FarmxARHgNUKd8lFkQG_Vzhf68fbTGjT

### **Instructions**:

#### **Setup**:
- Bootstrap a new Next.js project with TypeScript and Tailwind CSS.

#### **Functionality**:
- Showcase all Everai NFTs from this contract address: **0x9a38dec0590abc8c883d72e52391090e948ddf12** using our provided Alchemy API key.
  
- Display the NFTs in a grid layout. Each NFT card should show:
    - NFT Image
    - NFT Name
    - Price (mock it)
    - A "Buy" button

- Implement a search bar at the top of the page.
    - As the user types, filter the displayed NFTs in real-time based on their names.
    - Use React hooks, specifically `useState` and `useEffect`, to manage the search functionality and filtered results.

#### **Design**:
- Style the interface using Tailwind CSS to make it visually appealing.
- Ensure that the design is responsive and looks good on both mobile and desktop views.

### **Submission**:
- Push your code to a GitHub repository.
- Include instructions on how to run the project locally in the README.
- (Optional) Deploy the project to Vercel or Netlify and share the live link.

### **Notes**:
- Focus on code quality, clarity, and the correct use of React principles.
- Handling actual transactions (e.g., "Buy" functionality) is not required for this test. Instead, the "Buy" button can simply display a confirmation message or modal.
