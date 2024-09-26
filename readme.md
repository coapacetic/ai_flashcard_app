# AI Flashcard App

Lightweight AI powered app using the OpenAI API.

<div>
    <a href="https://www.loom.com/share/454ba3b9f7d34b2f8b2115e10673cc0d">
      <p>Kyle Coapman - OpenAI Flashcard App - Watch Video</p>
    </a>
    <a href="https://www.loom.com/share/454ba3b9f7d34b2f8b2115e10673cc0d">
      <img style="max-width:300px;" src="https://cdn.loom.com/sessions/thumbnails/454ba3b9f7d34b2f8b2115e10673cc0d-f8fa5e97aebf79ad-full-play.gif">
    </a>
  </div>

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
