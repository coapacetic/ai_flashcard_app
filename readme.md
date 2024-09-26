# AI Flashcard App

Lightweight AI powered app using the OpenAI API.

<div style="position: relative; padding-bottom: 64.98194945848375%; height: 0;"><iframe src="https://www.loom.com/embed/454ba3b9f7d34b2f8b2115e10673cc0d?sid=5388bf31-9af4-46be-853c-a846a0cba3e3" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;"></iframe></div>

1. Install dependencies
```
pip install flask
pip install openai
```

2. Load your OpenAI key into your .zsh file
```
export OPENAI_API_KEY='XXXXXX-YOUR-KEY-HERE-XXXXXX'
```

3. Run the app
```
flash run
```

4. Type in your topic area, specify what you want on the front and back, and voila! Quiz yourself on the questions!

Example Prompt: Generate flashcards for the first 150 original pokemon. The front of the card should be the Pokemon name and the back should be the type like Psychic or Grass.