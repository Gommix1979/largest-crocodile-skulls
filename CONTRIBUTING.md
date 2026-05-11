# Contributing a specimen

Thanks for wanting to help build this dataset. Here's what we need from a submission.

## What we accept

A specimen entry must come with a verifiable source. That means one or more of:

- A peer-reviewed scientific paper (journal article, conference proceedings)
- A museum accession record with the institution name
- A photograph of the actual skull alongside a measurement reference (ruler, scale bar, or known-size object)
- A field record signed off by a known crocodile researcher

Personal anecdotes, "I saw a really big one once" stories, or unsourced internet claims will not be merged. The literature is already full of those and we're trying to keep this clean.

## What we don't accept

- Specimens with no source
- Measurements that contradict the source without explanation
- Live captive-bred individuals raised in artificial conditions (we focus on wild-origin animals)
- Fossil crocodilians (this database is about extant species)

## How to submit

### Easy path (if you're comfortable with GitHub)

1. Fork this repository
2. Edit `data.csv` directly in the GitHub web editor and add a new row with as much data as you have
3. Submit a pull request using the template that will appear
4. Wait for review

### Easier path (if GitHub feels overwhelming)

Open a new **Issue** on the repo titled "New specimen: [name/location]" and paste in your data plus the source. The maintainer will convert it to a proper entry on your behalf.

## What data we need

**Minimum:**
- Species (scientific name preferred)
- Either an origin (where the animal came from) or a current location (where the skull is)
- At least one measurement: DCL_A, MHW, or TL
- Source citation

**Ideal:**
- All of the above plus
- DCL_A and DCL_B (curve and straight)
- MHW, MCW, IOW (the three head widths)
- TL of the live animal, with a note on whether measured or estimated
- Mandible length
- A specimen name if it had one
- Any notes that would help future researchers (missing tail tip, broken mandible, captive vs wild, etc.)

## Measurement guide

Don't worry if you don't know what the abbreviations mean. Brief version:

| Abbreviation | Meaning | Unit |
|---|---|---|
| DCL_A | Dorsal Cranial Length, along the curve | mm |
| DCL_B | Dorsal Cranial Length, straight line | mm |
| MHW | Maximum Head Width (usually across the back of the mandible) | mm |
| MCW | Maximum Cranial Width (between the squamosals) | mm |
| IOW | Inter-Orbital Width (minimum width between eye sockets) | mm |
| TL | Total Length of the live animal, snout to tail tip | cm |
| Mandible | Lower jaw length | cm |

If your source uses different terminology, include the original term in the Notes column and we'll work out the right column to map it to.

## Review process

Once you submit:
1. The maintainer will review the pull request
2. We may ask for clarification on the source, request a photograph, or check the measurement methodology
3. Once we're satisfied, the entry gets merged and appears on the live site within minutes
4. Your name (or GitHub username, your choice) is preserved in the commit history as the contributor

We won't merge anything we're not confident about. If we decline an entry, we'll explain why and you're welcome to resubmit with additional evidence.

## Code of conduct

Be respectful, be patient with response times, and keep the conversation about the data. Disagreements about measurements or methodology are welcome — we want this dataset to be as accurate as possible.

Cheers.
