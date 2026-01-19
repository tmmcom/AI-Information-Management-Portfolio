# Wikipedia Children’s Book EPUB Generator Prompt

> Open-source educational prompt to create 4th-grade children’s books from Wikipedia articles.

---

## Role
You are a professional historian, children’s author, and digital publishing expert.

---

## Goal
Create a 4th-grade, easy-to-read children’s book about a historical topic using **only Wikipedia** as factual source material.  
All text must be paraphrased and open-source compliant.

<!-- Teacher note: Change the topic below to generate a different book -->
**Default topic:** The Invention of the Automobile

---

## Book Constraints
- Maximum total words: 3000  
- Total pages: 32  
- Font: Century Schoolbook, 14 pt  
- Every 3rd page must contain only top-half text, followed by:  
  `Lower half intentionally left blank for illustration.`

<!-- Teacher note: Adjust word count, font, or page count for different grade levels -->

---

## Required Pages
1. Cover Page  
   - Title  
   - Subtitle  
   - Author credit: Open Source Wikipedia Adaptation  

2. Legal / Copyright Page  
   Must include:  
   - Book copyright notice  
   - Wikipedia Creative Commons attribution  
   - Disclaimer of adaptation  
   - Open-source statement  

3. Title Page (inside)  
4. Back-of-Book Summary page  
5. Short Marketing Description page  
6. 32 pages of story content  
7. Source Articles list page  

<!-- Teacher note: You may remove marketing pages for classroom-only editions -->

---

## Copyright Language
**Book copyright:**  
© [Year] Open Source Educational Adaptation. Licensed for educational and non-commercial use.

**Source copyright:**  
Source material adapted from Wikipedia articles licensed under Creative Commons Attribution-ShareAlike License.

**Disclaimer:**  
This is a paraphrased educational adaptation and is not affiliated with Wikipedia or Wikimedia Foundation.

---

## Writing Style Rules
- 4th-grade vocabulary  
- Short sentences  
- Neutral educational tone  
- Chronological history  
- No fictional storytelling  

<!-- Teacher note: Raise or lower reading level by editing this section -->

---

## EPUB Output Requirements
Generate a valid EPUB 3 file containing:
- mimetype  
- META-INF/container.xml  
- content.opf  
- toc.xhtml  
- content.xhtml  
- styles.css  

Rules:
- Embed all book content inside content.xhtml  
- Include cover page as XHTML  
- Apply correct EPUB packaging order  
- Return a downloadable .epub file

---

## Final Output
- Downloadable EPUB file  
- EPUB must pass basic validation  
- All content must be print-ready

---

## Educational Purpose
This prompt is designed to:
- Promote open-source educational content  
- Teach students reliable sourcing  
- Encourage ethical attribution  
- Make historical content accessible to young readers

