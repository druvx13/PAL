# Public Attribution License (PAL) — Comprehensive Documentation

## 1) Overview

The **Public Attribution License (PAL)** is a permissive public license designed for many content types, including software, code, videos, articles, images, and other textual or media materials.

Core model:
- Broad freedom to use, copy, modify, distribute, display, and commercialize content.
- Minimal mandatory obligations focused on:
  - **Attribution** (Clause 1)
  - **Preservation of the license notice/disclaimer** (Clause 3)
  - **Termination/reinstatement behavior** for non-compliance (Clause 4)

The complete legal text is in `/LICENSE`.

---

## 2) Purpose and Design Intent

PAL is structured to support open sharing on the internet while retaining author recognition and liability protection.

The license aims to be:
- **Open**: allows nearly unrestricted downstream use.
- **Simple**: keeps obligations limited and understandable.
- **Cross-media**: applies to software and non-software content.
- **Protective for authors**: includes explicit no-warranty/no-liability language.

---

## 3) Scope of Application

Under PAL, the licensed “content” can include:
- Source code and binaries
- Documentation and articles
- Blog posts and written works
- Images and graphics
- Video and audiovisual works
- Other digital assets (audio, datasets, 3D models, etc.)

The license text explicitly states broad content coverage.

---

## 4) Rights Granted (Clause 0)

PAL grants permission to:
- Copy
- Modify
- Distribute
- Perform/display
- Create derivatives
- Use commercially

These rights are granted as long as recipients comply with attribution and notice-preservation requirements and accept the liability disclaimer structure.

---

## 5) Obligations and Conditions

### 5.1 Attribution (Clause 1)

You must provide appropriate credit exactly as specified by the Licensor:
- If named identity is provided (real name, pseudonym, username), use that.
- If anonymity is chosen, attribute as **“Anonymous.”**
- For multiple authors, credit all named authors or use Anonymous if they chose collective anonymity.
- You may add your own modification credit, but cannot remove or obscure original attribution.

### 5.2 No Liability / No Warranty (Clause 2)

Licensed content is provided **“AS IS”**, without express or implied warranties.
Authors/copyright holders are not liable for damages arising from use.

### 5.3 Preservation of Notice (Clause 3)

When distributing a copy or separated portion of licensed content, retain the full PAL license text (including disclaimer).

If only a portion is embedded in a larger work:
- You do not need to attach the full license to the entire larger work.
- You still must not remove attribution from the PAL-covered portion.

### 5.4 Termination and Reinstatement (Clause 4)

Rights terminate automatically if you fail Clause 1 or Clause 3.
Rights can be reinstated if non-compliance is corrected within 30 days of discovery or Licensor notice.

### 5.5 No Patent Grant (Clause 5)

PAL does not provide patent rights. Any Licensor patents are not licensed under PAL unless separately granted.

### 5.6 Severability (Clause 6)

If one provision is unenforceable, remaining provisions remain valid.

---

## 6) Classical Step-by-Step Adoption Workflow

This is the recommended classical process for using PAL correctly.

### Step 1 — Identify the work and rights holder(s)
- Confirm what content is being licensed.
- Confirm who owns the rights (single author, team, organization).

### Step 2 — Decide attribution identity
- Choose named attribution (real/pseudonym/username), or
- Choose Anonymous attribution where applicable.

### Step 3 — Add copyright notice
- Add copyright year and author identity.
- Keep wording consistent across distributed copies.

### Step 4 — Attach PAL license text
- Include full `/LICENSE` text with distributed copy/portion as required by Clause 3.
- Ensure disclaimer text remains intact.

### Step 5 — Add practical usage notice
- Add a concise statement that the work is licensed under PAL.
- Indicate where full license text is located.

### Step 6 — Place notice in prominent location
- For repositories: `LICENSE` file and/or top-level documentation.
- For media uploads: metadata, description field, and visible credits where relevant.

### Step 7 — Verify distribution compliance
- Attribution present and accurate.
- License/disclaimer preserved where required.
- No contradictory restrictions introduced.

### Step 8 — Handle updates and derivative releases
- Preserve original attribution.
- Add modifier/contributor credits separately if desired.
- Re-run compliance checks on each release.

### Step 9 — Monitor and cure non-compliance quickly
- If attribution/notice issue is found, correct within 30 days to restore rights under Clause 4.

---

## 7) Compliance Checklist (Operational)

Use this checklist before publication:

- [ ] Author attribution format chosen and documented
- [ ] Copyright notice inserted
- [ ] PAL license statement included
- [ ] Full PAL text attached/preserved where required
- [ ] No-liability disclaimer retained
- [ ] Distribution channel metadata/caption/description updated
- [ ] Derivative modifications credited without removing original credit
- [ ] Final legal text matches `/LICENSE`

---

## 8) Content-Type Guidance (from PAL Appendix)

### Images
- Prefer embedded metadata (EXIF/IPTC/XMP).
- If metadata is unavailable, add companion `LICENSE.txt` or `PAL_NOTICE.txt`.
- For web publication, include visible caption or equivalent notice.

### Video
- Put notice in credits/title card (recommended visibility and readability).
- Embed notice in container metadata when possible.
- Add notice in platform description and pinned context where available.

### Text and code
- For short text, place notice at start/end.
- For longer works, use copyright or license section.
- For code, add file-level comment notice or repository-level `LICENSE`.

### Other media
- Use standard metadata fields or companion `PAL_LICENSE.txt`.
- Ensure a reasonable recipient can discover attribution and terms.

---

## 9) Practical Attribution Templates

### Named author template
`Copyright (C) [year] [author name(s)]`

`Licensed under the Public Attribution License (PAL).`

### Anonymous template
`Copyright (C) [year] Anonymous`

`Licensed under the Public Attribution License (PAL).`

For full legal effect, always preserve and ship the full `/LICENSE` text where required.

---

## 10) Risk and Governance Notes

- PAL is permissive but not obligation-free; attribution and notice duties are mandatory.
- Keep a release checklist and evidence of compliance for each distribution channel.
- If your organization needs patent permissions, negotiate or add a separate patent license.
- For high-risk/commercial deployments, consider legal review for jurisdiction-specific interpretation.

---

## 11) Recommended Repository Practice for PAL Projects

1. Keep the canonical license at `/LICENSE`.
2. Reference PAL in project docs and release artifacts.
3. Use a standard attribution format in source headers or docs.
4. Ensure derivative/repackaged outputs still preserve required notices.
5. Audit final artifacts (source, binary, media metadata, platform descriptions).

---

## 12) Summary

PAL gives broad freedom to reuse and commercialize content with a focused compliance model:
- Keep attribution accurate.
- Preserve the license/disclaimer where required.
- Correct violations promptly to restore rights.

When these steps are consistently followed, PAL supports open distribution with clear author credit and practical legal safeguards.
