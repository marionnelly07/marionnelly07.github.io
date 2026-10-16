# marionnelly07.github.io

Personal academic website of Marion Payet. Plain HTML, served by GitHub Pages. No build step.

## Pages
- `index.html`: home (English)
- `fr/index.html`: French page
- `teaching/index.html`: Teaching
- `research-data/index.html`: Research & Data (GDPR information notice + legal notice)

## Other files
- `assets/site.css`: design; `assets/fonts/`: Raleway, self-hosted (no Google requests)
- `files/`: CV, photo, drawing; `files/teaching/`: course materials

## Common edits (GitHub web editor: open a file, pencil icon, edit, "Commit changes")
- **Add a publication or talk:** in `index.html`, copy one `<li class="entry"> … </li>` block, paste it at the top of its list, change the text.
- **Add a course:** in `teaching/index.html`, follow the commented template at the top of the Courses list. Upload materials to `files/teaching/<course-folder>/`.
- **Update your CV:** upload a new `files/Marion_Payet_CV.pdf` (same name).
- **If the information notice changes:** edit the French text in `research-data/index.html` and keep it identical to the version the DPO validated.

Changes are live about one minute after you commit.
