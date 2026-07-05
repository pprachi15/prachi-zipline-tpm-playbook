<p align="center">
  <img src="https://github.com/user-attachments/assets/8d478fa3-e0b5-451b-afa1-e0c1035447f4" alt="Zipline" width="220">
</p>

<h1 align="center">Technical Program Manager Intern Interview</h1>
<p align="center"><em>A live, click through presentation built for a Zipline interview conversation.</em></p>

---

## What this is

This is a single self contained HTML file that stands in for a slide deck during a live interview. Instead of clicking through static slides, the interviewer watches a real product feeling walkthrough of three programs, a direct mapping to what Zipline needs, and one shipped side project. Everything, including every image, is embedded in the one file, so it opens instantly in any browser with no internet connection required.

Open `interview.html` to run it. There is nothing to install and nothing to configure.

## How it is structured

**Landing page**
A simple violet welcome screen with a single Start button. Clean, on brand, and gets out of the way fast.

**My Experience**
Three program cards to choose from.

<table>
<tr>
<td align="center" width="33%">
  <img src="https://github.com/user-attachments/assets/7dd01922-76d6-418e-a3c8-cf7f40a5e8a1" width="90"><br>
  <strong>Tesla Semi</strong><br>Service Readiness
</td>
<td align="center" width="33%">
  <img src="https://github.com/user-attachments/assets/c7104301-fbf1-4473-b213-68e7f8ea4de0" width="90"><br>
  <strong>Sacramento State</strong><br>Strategic Data Analyst
</td>
<td align="center" width="33%">
  <img src="https://github.com/user-attachments/assets/c7e9470f-77c0-462d-b6f5-1be6fa071212" width="90"><br>
  <strong>Purdue</strong><br>AI Curriculum Funding Pitch
</td>
</tr>
</table>

The Tesla story is the deep dive. It plays out across three checkpoints, Discover the Problem, Align and Measure, and Prepare for Scale, each one built from real program artifacts: customer journey maps, a weighted scoring matrix, a roadmap, a leadership scorecard, and an OKR readiness plan. A truck animates along a curved road between checkpoints, and every screenshot can be clicked to zoom in and clicked again to close.

The Sacramento State and Purdue stories are each a single page summary rather than a multi step journey, built for a quick, complete read without any scrolling.

**My Alignment**
Four things Zipline is looking for, paired one to one with proof from past work. A drone animates in through its delivery sequence, then opens to reveal the matching proof card for each need, tying the Tesla experience directly back to what the interviewer is listening for.

<p align="center">
  <img src="https://github.com/user-attachments/assets/a6c6a9d8-c0c8-4e42-8091-10804832f972" width="150">
  <img src="https://github.com/user-attachments/assets/8a59eb99-56ff-4510-8b60-e32cf6adffe4" width="150">
</p>

**My Innovation**
One more thing, delivered the same way: ReadRoom, an AI native tool built end to end, with a live link to try it.

## Design system

Everything follows the Zipline brand system on purpose, not by accident:

- **Violet** as the primary color across roughly half of every screen
- **Crema** as the background, warm rather than stark white
- A handful of extended accents (terra, orange, red, lime, aqua) used sparingly
- Oswald for headlines, Space Grotesk for subheads and numbers, Inter for body text
- Motion that always feels forward or upward, never abrupt

No placeholder graphics anywhere. Every chart, scorecard, and diagram on screen is a real asset from the actual programs being discussed.

## A few things worth knowing before you present

- Every screenshot and diagram is clickable. Click once to see it full size, click again to put it back.
- The Cal State and Purdue pages are intentionally short and fit one screen. The Tesla Align and Measure checkpoint is the one screen that scrolls, since it carries the most material.
- Numbers on the Cal State and Purdue pages count up automatically the moment those pages open.
- The file is large because every image is embedded as base64 rather than linked externally. That is what makes it fully portable, drop it anywhere and it just works.

---

<p align="center"><sub>Built for a real interview, with real program artifacts, on real Zipline brand guidelines.</sub></p>
