# Piano Score Rearrangement
We propose a **notation-level rearrangement** method that changes the **difficulty level** of piano scores.
Score conversion directly on the notation domain enables us to **process musical information** in the scores **comprehensively**.

![Overview](img/ST+_overview.svg)

## Key Findings
- We can **directly process musical scores** on the **notation** domain.
- We can train a **single model** that convert scores between **multiple diffuculty levels**.
- **Bar-major** score token (ST+) **performs better** than staff-major score token (ST). 
- The **quality** of rearranged scores are **not inferior to** those of **human-made ones**.

## Sample
### Source score 
- Intermediate level (Lv.3)

![Sample1_src](img/sample1_lv3_src.svg) <audio src="audio/sample1_lv3_src.wav" controls></audio>

### Generated scores
- Beginner level (Lv.1)

![Sample1_lv1](img/sample1_lv1.svg) <audio src="audio/sample1_lv1.wav" controls></audio>

- Elementary level (Lv.2)

![Sample1_lv2](img/sample1_lv2.svg) <audio src="audio/sample1_lv2.wav" controls></audio>

- Advanced level (Lv.4)

![Sample1_lv4](img/sample1_lv4.svg) <audio src="audio/sample1_lv4.wav" controls></audio>

## Token Example
Example **score token (ST+) sequences** corresponding to the scores on Fig.4 in the paper.  
The ***level*** token(s) at the beginning are **difficulty conditioning** tokens (see Fig.2 / Section 2.1 in the paper).  
By **changing** these tokens (on the source sequence), users can **control the playing difficulty** of scores. 

![TokenExample](img/token_example.png)

## Code 
coming soon!
