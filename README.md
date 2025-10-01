# Vulnerable AI Student Assitant
A vulnerable AI app for testing purposes

## INSTRUCTIONS
1. Create/modify .env file to include the same API key used for Gemini
        GEMINI_API_KEY=”key”
2. Verify in main.py that 1.5 flash is not being used (deprecated)
        Use gemini-2.5-flash
3. Open terminal in IDE
4. Make sure you are in the right directory
5. Run: pip install -r requirements.txt
6. Run: uvicorn main:app --reload