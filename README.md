# Rakshit Jain AcademicPages content bundle

This bundle converts the provided CV into files compatible with the AcademicPages Jekyll template.

## How to use

1. Fork or clone `academicpages/academicpages.github.io`.
2. Copy these folders/files into the root of your AcademicPages repository:
   - `_pages/about.md`
   - `_pages/cv.md`
   - `_pages/awards.md`
   - `_pages/service.md`
   - `_publications/*.md`
   - `_talks/*.md`
   - `_teaching/*.md`
3. Open `_config_snippet.yml` and merge the values into your repo's existing `_config.yml`.
4. Optionally merge `_data/navigation_snippet.yml` into `_data/navigation.yml`.
5. Add your headshot as `images/profile.png` or update the `author.avatar` field.
6. Add missing live URLs later: Google Scholar, ORCID, LinkedIn, DOIs, arXiv links, PDFs, and talk slides.

## Notes

- Publication and talk dates are exact where the CV gave them; otherwise I used the first day of the stated month/year or January 1 for year-only/in-preparation items so Jekyll can sort them.
- I kept the CV's first-author/co-first-author structure in the citation text rather than creating separate pages for categories beyond `preprints` and `manuscripts`.
- Check spelling before publishing. I corrected obvious OCR artifacts such as hyphenation, but left scientific titles intact.
