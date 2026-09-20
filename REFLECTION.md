# Project Reflection Drafts

## Probabilistic AI

Generative AI is probabilistic: it predicts a useful next word, line of code, or design suggestion from patterns in its training. That makes it a helpful starting point for brainstorming layouts, translating rough copy, and explaining unfamiliar tools, but it does not make its output automatically correct. For this project, I used AI suggestions as hypotheses and then checked the actual result in the browser. For example, the RTL layout still needed semantic HTML, logical CSS properties, accessible labels, descriptive image alternatives, and a Lighthouse audit. The important lesson for me is that AI can accelerate iteration, while the developer remains responsible for verifying quality, accuracy, and accessibility.

## Interview Question

One project challenge was making a layout feel intentionally right-to-left instead of simply aligning all text to the right. I began by setting the document language and `dir="rtl"`, then used Bootstrap's responsive grid and CSS logical properties such as `inset-inline-start` and `padding-block`. Those properties adapt to both directions without requiring duplicate CSS. I also added a small observer that watches for language or Google Translate direction-class changes and updates the page direction. I tested the finished page with Lighthouse, which gave the accessibility category a score of 100. This showed me how I would approach a real production requirement: build with standards first, then test the outcome rather than assuming it works.

## LinkedIn Post

This week I localized an Intel sustainability webpage for right-to-left reading. I practiced using Bootstrap's responsive grid, Bootstrap Icons, accessible forms, semantic landmarks, and an accordion component. My favorite part was learning that RTL support is more than `text-align: right`: the page needs the correct document direction, logical CSS properties, and testing in both RTL and LTR modes. I also ran Lighthouse and reached a 100 accessibility score. Small details—clear labels, useful alt text, focus styles, and color contrast—make a much better experience for everyone. #WebDevelopment #Accessibility #Bootstrap #Localization #RTL
