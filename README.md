# movie-app

```mermaid
flowchart TD
  A[Fetch Movie from TMDB] --> B[Extract Plot, Keywords, Genres]
  B --> C[Use Sentence Transformer to Embed Plot]
  C --> D[Ask AI (Gemini or OpenAI) for Themes and Moods]
  D --> E[Blend TMDB Keywords, Embeddings, AI Suggestions]
  E --> F[Store Themes/Moods in Movie Model]
```
