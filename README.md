Business Idea Generator, an AI application that generates a business idea on demand. For this project I used Next.js as my frontend, FastAPI as the backend web framework, Clerk for user authentication, and OpenAI as my AI of choice. To run this code you need 4 environment variables which will be listed below. After those have been added to run the Next.js code you need 'npm run dev' and 'uvicorn main:app --reload'

    - NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY (From Clerk)
    - CLERK_SECRET_KEY (From Clerk)
    - JWKS URL(From Clerk)
    - OpenAI API Key (From OpenAI)
