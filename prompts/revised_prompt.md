# Revised Prompt Notes

As the project progressed, it became clear that not all AI-generated mnemonic images were equally useful. Some outputs overemphasised the sound cue, while others were visually confusing or made the meaning unclear.

The later prompt refinements focused on the following principles:


Pretend you are teaching an introductory learner of (insert language) whose
first language is English. Your goal is to help them learn beginner vocabulary
through high-quality visual keyword mnemonics.
First, choose 20 beginner-friendly concrete vocabulary words that are useful
for an introductory learner. Prefer simple everyday nouns or adjectives that
can be shown clearly in an image. Avoid abstract words, function words, or
words that are difficult to depict visually.
For each chosen word, generate:
1. The target word in (insert language)
2. Its English meaning
3. A simple pronunciation guide for an English speaker
4. A strong English keyword or sound-based cue that resembles the pronunciation
5. A short mnemonic explanation that links the sound cue to the true meaning
6. A final image prompt
Important: the mnemonic must help the learner remember the REAL meaning of
the word, not just the sound cue. The target meaning must be visually dominant,
while the sound-based cue should support memory without overpowering the
meaning.
Image requirements:
- plain white background
- bold black text of the target word at the top
- one clear, coherent scene
- minimal clutter and no unnecessary background details
- visually simple enough for a beginner learner to understand quickly
- the target meaning must be the main thing shown
- the sound cue must be present, but secondary
- the image must not feel like two unrelated objects placed side by side
- the spelling of the target word must be correct
Acceptance criteria for each mnemonic:
- The meaning is immediately clear from the image
- The sound-link is recognisable for an English speaker
- The cue and meaning are integrated into a single memorable scene
- The image is not misleading, overly abstract, or visually busy
- The mnemonic would help a beginner remember the translation rather than only
the cue object
Reject and replace any word or mnemonic if:
- the sound-link is too weak or unnatural
- the cue is more memorable than the meaning
- the image would likely make the learner guess the wrong English word
- the scene is too abstract, confusing, or culturally niche
- the concept cannot be depicted clearly in a simple image
Output the results in a table with these columns:
Target word | English meaning | Pronunciation guide | English keyword cue |
Mnemonic explanation | Final image prompt

This refinement process became an important part of the project because the final conclusion was not simply that AI can generate mnemonics, but that those mnemonics need careful filtering and quality control.
