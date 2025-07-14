# Registry List for IRI Digital First Standards, by version

This repository tracks industry adoption of the IRI Digital First for Annuity open standards by version. Firms can submit pull requests to indicate their implementation status. This enables transparancy, collaboration, and faster onboarding. 

The registry is a centralized, version-controlled list of each standard and the firms that have implemented them. This registry will allow stakeholders to easily identify which firms have adopted specific standards,and which versions, enabling faster, more seamless integrations. This list highlights firms that are implementation-ready, reducing onboarding time and increasing interoperability across the ecosystem.

## Structure of registry
Firm name
- Implementation status (`Implemented`, `In Progress`, `Planned`)
- Date of implementation
- Verification status
- Contact information
- Optional tags and notes
  
##🔧 Purpose of adopters.yml in This Registry

It captures:
- Which firms have adopted a specific standard
- Which version of that standard they’ve adopted
- What their implementation status is (Implemented, In Progress, or Planned)
- Relevant metadata like contact info, verification, dates, and tags



## Organization of the registry
The standards/ directory is organized by standard and version. Each version contains an adopters.yml file that lists firms who have implemented that version, including status, dates, and metadata.
<pre> <code> ``` /standards/ ├── eAppAPI/ │ ├── v2.0/ │ │ └── adopters.yml │ ├── v2.1/ │ │ └── adopters.yml ├── ReplacementAPI/ │ └── v1.0/ │ └── adopters.yml ``` </code> </pre>



## How to engage, contribute, and give feedback
To add or update your firm's status:
1. Fork this repo
2. Navigate to the appropriate `adopters.yml` file
3. Add your info (see format below)
4. Submit a pull request


## Code of conduct

This registry exists to promote transparency, accelerate implementation, and support collaboration across firms adopting open industry standards. To maintain trust and data integrity, we ask all contributors to follow these guidelines when submitting or updating information.

✅ Acceptable Contributions
Accurate Status Only
- Contributors must provide implementation status that reflects their firm's actual progress:

- Implemented: The firm has deployed the standard in production.

- In Progress: Work is underway to implement the standard.

- Planned: The firm has committed to implement but has not begun.

✅ Authorized Submitters
Only individuals authorized to represent their firm should submit or update entries. If unsure, contact the maintainers before submitting.

✅ Version-Specific Data
All updates must be associated with a specific standard and version (e.g., eAppAPI v2.1). Do not generalize across versions.

✅ Verification Flag
Only the IRI Governance Committee may set verified: true. Firms may submit their implementation, but verification must follow independent IRI Governance Committee review.

✅ Meaningful Metadata
Include relevant metadata where possible, such as:

- Date of implementation
- Contact email for technical inquiries
- Notes or tags (e.g., pilot, fast-track)

🛑 What Not to Do
- Do not submit data on behalf of another firm unless explicitly authorized.
- Do not misrepresent your implementation status.
- Do not edit or remove another firm’s data.
- Do not introduce breaking format changes to YAML/JSON structures.

⚙️ How to Submit an Update
1. Fork the Repository

2. Edit the appropriate adopters.yml file

3. Submit a Pull Request (PR) with a brief description of your change

4. Wait for Maintainer Review
Your submission will be reviewed for accuracy, formatting, and authenticity.

🔍 Review Process
The IRI Governance Committee may:

- Request additional details

- Ask for confirmation of production or confirmation of testing

- Decline or revert changes if they do not meet this code of conduct

🙌 Collaboration & Respect
All contributors are expected to treat others with professionalism and respect. The goal is shared progress—not competition. Disagreements should be handled constructively and in good faith.


