# Project Plan
## 1 Find a direction
I am very interested in astronomy and exoplanet exploration. I was curious about how artificial intelligence assists scientists to search for potentially habitable exoplanets, the so‑called "second Earth".
At the beginning, my ideas were scattered: I wanted to cover detection methods, real research cases, open datasets and future challenges. When I discussed with AI, I sorted out the overall structure of the project. I decided to build a self‑contained static webpage to turn astronomical research papers and public materials into easy‑to‑read content for high‑school students.

## 2 Research
I studied public resources about exoplanet detection, including NASA open archives, published academic papers, official announcements from Chinese astronomical institutions, and popular science articles.
Key links I refer to:
- NASA Exoplanet Archive
- ExoMiner open‑source project on GitHub
- Publications from Shanghai Astronomical Observatory and Yunnan Astronomical Observatory, CAS

I learned multiple exoplanet detection methods such as transit photometry and radial velocity. I also learned real‑world AI applications including ExoMiner, AstroNet and GPFC algorithm. Those resources provide real‑world data, research cases and reference links which I embed into my webpage.

## 3 Narrow down
My initial idea was to build an interactive tool that can download and analyze real astronomical light‑curve data. However, that requires complex Python backend and JavaScript logic, which is beyond my current development scope.
I narrowed my project scope down to a static educational report webpage. The webpage only explains background knowledge, real‑world AI research cases, open datasets and existing challenges. It will not implement real‑time data computation or original AI model training.

Concrete example: High‑school students open this HTML file in any browser. They can read structured knowledge, view built‑in SVG diagrams, check real‑world data and reference sources without installing extra software.

## 4 Propose a solution
This single‑file HTML+CSS webpage delivers professional astronomy knowledge in high‑school‑friendly language. All illustrations are drawn with inline SVG inside the file, no external images or JavaScript dependencies. The whole project can run offline just by opening the local HTML file.

Compared with original academic papers which are hard for teenagers to understand, my work reorganizes complicated research results into readable chapters, tables and visual diagrams.
Assumption: A static document‑style webpage is sufficient to transfer core knowledge of AI‑aided exoplanet searching. Complex interactive computation is not necessary for this educational goal.

## 5 Define a minimal workflow
First‑version must‑have features:
- Complete static HTML page with all 5 main content chapters
- Built‑in SVG diagram explaining the transit method
- Formatted tables for comparison of detection methods, pain points and open‑source tools
- Reference list with original paper and resource links
- Clean responsive layout, readable on both computer and mobile browser

Features postponed for future iteration:
- JavaScript interactive light‑curve simulation
- Real‑time data fetching from NASA API
- Local simple neural network demo

The minimal meaningful output: Users can open the single HTML file locally or online, read the full popular‑science report and understand how AI helps humans hunt for exoplanets.

## 6 Build it
I have finished the full static webpage project. The output is one single HTML file with embedded CSS and inline SVG graphics. No external files or JavaScript are required.

What I have implemented:
1. Page structure: navigation bar, hero banner, five main content sections, reference footer.
2. Visual elements: self‑contained SVG diagram demonstrating the transit‑planet detection principle.
3. Organized content: comparison tables, case studies for NASA ExoMiner, Google AstroNet and Chinese astronomical research results.
4. Reference section collecting original paper links and public data platforms.

Source code file: `AI如何帮人类寻找第二个地球.html`

Simulated / prepared parts: All research content comes from public papers and official science releases. I did not run original astronomical observation or train my own AI model in this project.

## 7 Feedback and iteration
No real‑world user feedback collected so far.

Planned changes for future iteration:
1. Add simple JS interaction: for example, click‑to‑show light‑curve simulation.
2. Shorten some long paragraphs to improve reading experience.
3. Add more translation for key terms for better bilingual reading experience.
When I get feedback from classmates or teachers, I will revise content and layout accordingly.
