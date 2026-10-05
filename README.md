# Hard Questions Quiz (100 pairs)

A quiz for couples. You pick between 100 pairs of topics. The app ranks 9 life areas and all 100 questions, so you know what to talk about first.

The whole app is one file: `index.html`. It has no dependencies and no build step.

## Run it locally

Double-click `index.html`. It opens in any browser on a laptop or phone.

## Publish on GitHub Pages

1. Create a new public repository on GitHub.
2. Upload `index.html` and this `README.md` to the main branch.
3. Open **Settings > Pages**.
4. Under **Build and deployment**, pick **Deploy from a branch**, then `main` and `/ (root)`. Click **Save**.
5. Wait a minute. The quiz runs at `https://<your-username>.github.io/<repo-name>/`.

## How it works

- Each of the 100 questions has one short statement for the quiz.
- Every question shows up in exactly 2 pairs, each time against a question from another area. No pair repeats.
- The pairs shuffle each time you start a new quiz.
- A question scores 0, 1 or 2, based on how often you picked it.
- An area's score is the share of its matchups you picked it. Areas have different sizes, so a share keeps them fair.
- The results show the questions you picked twice, then every area with its questions sorted by score.

## Save and resume

Progress saves in the browser after each answer. Close the page and open it again to see a **Continue** button.

## Compare with your partner

On the results page, tap **Copy link to my results** and send the link. It holds your 100 scores. Your partner sees your ranking and can take the quiz to compare.

## Edit the questions

Open `index.html` and find `const TOPICS` near the top of the script. Each question is a pair of texts: the short quiz statement, then the full question for the results page.

Keep 100 questions in total so saved progress and share links stay valid.
