# LangGraph Streamlit Project with React and Tailwind Components

This project combines a Python backend using LangGraph and Streamlit with a Next.js frontend for rendering React components with Tailwind CSS.

## Getting Started

### Backend Setup

1. Set up a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

2. Install Python dependencies:
   ```bash
   cd backend
   pip install -r requirements.txt
   ```

3. Create a `.env` file in the `backend/` directory with the following content:
   ```
   OPENAI_API_KEY=your_openai_api_key_here
   E2B_API_KEY=your_e2b_api_key_here
   BROWSER=none
   ```

4. Create a `sandboxid.txt` file in the `backend/` directory with the following content:
   ```
   your_sandbox_id_here
   ```

5. Run the Streamlit app:
   ```bash
   streamlit run main.py
   ```

### Frontend Setup

1. Install Node.js dependencies in the root folder:
   ```bash
   npm install
   ```

2. Run the Next.js development server:
   ```bash
   npm run dev
   ```

   Open [http://localhost:3000](http://localhost:3000) to view the React components.

## Project Structure

- `backend/`: Contains the Python backend with LangGraph and Streamlit
- `frontend/`: Houses the Next.js project for React and Tailwind components

## Creating and Rendering React Components

You can create React components with Tailwind CSS in the `frontend/components/` directory. These components can be rendered and controlled through the Streamlit interface.

## Learn More

- [Streamlit Documentation](https://docs.streamlit.io/)
- [LangGraph Documentation](https://python.langchain.com/docs/langgraph)
- [Next.js Documentation](https://nextjs.org/docs)
- [Tailwind CSS Documentation](https://tailwindcss.com/docs)
