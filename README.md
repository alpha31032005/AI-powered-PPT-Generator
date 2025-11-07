# AI-Powered PPT Generator using Gemini 2.5 Pro API

#Overview
A Python-based automation tool that generates complete PowerPoint presentations from a user-provided topic.  
The system uses **Gemini 2.5 Pro API** to create slide content and **python-pptx** to build structured and formatted slides automatically.

---

#Features

✔ Generate PPTs from any topic  
✔ Slide-wise title + content generation  
✔ Adds relevant images using the Pexels API  
✔ Clean formatting with titles, bullets, and layout  
✔ Extensible code structure for UI or additional features

---

#Tech Stack
- Python  
- Gemini 2.5 Pro API (google-generativeai)
- python-pptx
- Pillow
- Requests
- dotenv (for secure key handling)

---

#How it Works
1. User provides a topic  
2. Script calls Gemini 2.5 Pro API and generates structured slide content (JSON)  
3. Slides are programmatically created using python-pptx  
4. Optional: Images fetched using Pexels API  
5. Output saved as `.pptx`

---

#Project Structure

ppt_generator.py
requirements.txt
README.md

---

#How to Run
1. Clone repo  
git clone <your-repo-link>

2. Install dependencies  
pip install -r requirements.txt

3. Add your API key in `.env`  
GEMINI_API_KEY=your_api_key_here

4. Run script  
python ppt_generator.py

5. Output will be generated as `presentation.pptx`

---

#Example Topic
topic = "Artificial Intelligence in Agriculture"

---

#Future Improvements
- Streamlit / web-based UI for user input
- Theme customization (colors, layouts, fonts)
- Add charts or image placeholders automatically
- Export to PDF

---

#Author
**Nishant Bayaskar**  
GitHub: https://github.com/alpha31032005
LinkedIn: https://www.linkedin.com/in/nishant-bayaskar-ba1323262/
ini
Copy code
