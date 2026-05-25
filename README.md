# Topic Reference Literature Skill

A practical Codex skill for researchers who need to turn a rough research idea into a usable literature evidence package.

Give it a topic, and it helps search real literature, verify DOI/PMID metadata, organize evidence by category, force Journal Impact Factor and JCR quartile checks, and generate a Word reference-summary table for project planning, grant writing, thesis proposals, or manuscript preparation.

## What it does

- Searches literature from PubMed, CrossRef, publisher pages, and journal metric sources.
- - Selects at least 20 high-quality references by default for topic-first projects.
  - - Organizes papers into disease background, mechanism, methods/materials, intervention evidence, and evaluation endpoints.
    - - Requires JCR year, Journal Impact Factor, and JCR quartile for journal articles.
      - - Blocks Word generation when too many IF/JCR fields are missing or marked as pending.
        - - Produces a Chinese Word table with each paper's specific role in the project.
         
          - ## Output table
         
          - ```text
            Category | Title | Journal/Source | Year | IF/JCR | DOI/PMID/Link | Role in the project
            ```

            ## Why it is useful

            Most literature workflows stop at search results. This skill goes one step further: it turns papers into a structured, project-ready evidence map. It is especially useful for researchers, clinicians, graduate students, and lab members preparing new topics, grant applications, thesis proposals, or background literature folders.

            ## Install

            Download the packaged skill:

            https://github.com/WAHAHASA/topic-reference-literature-skill/raw/main/topic-reference-literature-skill.zip

            Then unzip it into your Codex skills directory:

            ```bash
            mkdir -p ~/.codex/skills/topic-reference-literature
            unzip topic-reference-literature-skill.zip
            cp -R topic-reference-literature-skill/. ~/.codex/skills/topic-reference-literature/
            ```

            ## Example prompt

            ```text
            Use the reference-literature skill. My topic is ROCK inhibitor-loaded corneal bandage lenses for corneal epithelial/endothelial decompensation. Please search the literature and generate a Word summary table with IF and JCR quartile.
            ```

            ## License

            MIT
            
