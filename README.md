# SkillProof - AI-Driven Soft Skill Verification Platform on Internet Computer

**SkillProof** is an MVP built on the **Internet Computer Protocol (ICP)** that uses AI to verify soft skills and mints the results as NFTs. This platform allows users to securely submit written content for assessment, receive AI-driven evaluations, and have their verified skills minted as NFTs with encrypted metadata. Authentication is managed via **Internet Identity** and **NFID** for enhanced security.

## Features

The MVP will provide the following functionality:
- **Submit written assessments** to evaluate soft skills like critical thinking and written communication.
- **Receive AI-driven feedback** on the submission.
- **Mint skill verification results as NFTs** on the ICP blockchain.
- **Authenticate securely** using Internet Identity and NFID.

## Language Choice

You can implement this platform using one of the following languages:
- **Motoko** (recommended for ICP)
- Typescript (code name Azle on the IC)
- Rust

## Setup

[Installation instructions](Installation.md)

To run the application locally:

Local frontend: http://localhost:3000/

## Project Goals

The SkillProof MVP will focus on the following:
- **AI integration**: Develop a simple AI model to assess written communication and critical thinking skills.
- **User authentication**: Implement secure user login using Internet Identity and NFID.
- **NFT minting**: Create a process to mint verified soft skills as NFTs.
- **Minimal user interface**: Develop a simple React-based frontend for skill submission and result display.

## Backend Development

Focus areas for backend development:
- For **Motoko**: `src/motoko_backend/SkillProofServer.mo`

Functionality to add:
- AI-driven **text analysis and assessment** using NLP models integrated into ICP canisters.
- **Secure NFT minting** based on the skill assessment results.
- **Internet Identity and NFID integration** for user authentication and profile management.

## Key Checks for Skill Submission and NFT Minting

- The user must be authenticated using Internet Identity or NFID.
- Written submissions are processed by the AI model for assessment.
- Skill verification results must be stored securely and linked to an NFT with encrypted metadata.

Optional: Support canister upgrades:
- In **Motoko**: Use `stable` variables in the actor.

[Code Structure](Structure.md)

## Documentation

- [ICP Blockchain Programming Documentation](https://internetcomputer.org/docs/current/developer-docs/)
- [Motoko Language](https://internetcomputer.org/docs/current/motoko/main/motoko)
- [Motoko Base Library](https://internetcomputer.org/docs/current/motoko/main/base)

## Workshop Solution

An example solution with a working backend implementation in Motoko, Typescript, and Rust will be available in the [Git branch `solution`](https://github.com/luc-blaeser/auction/tree/solution) after initial development (Note: Rust and Typescript do not yet support canister upgrades).

## Future Plans

Once the MVP is complete and tested, we aim to expand the SkillProof platform with additional features, such as:
- **Extended AI capabilities** to assess multiple soft skills (e.g., leadership, teamwork, communication).
- **Enhanced user interface and user experience** for better user engagement and easier skill submission.
- **More advanced NFT features**, including detailed metadata encryption for added privacy and security.
- **Enterprise integration** for bulk assessments and team-level skill verification, targeting HR professionals and job seekers.

## Project Roadmap

Post-MVP development includes:
1. Expanding the AI model to assess additional soft skills.
2. Improving the overall UI/UX for broader user adoption.
3. Adding more robust NFT metadata encryption and features.
4. Starting outreach to enterprise clients for feedback and collaboration.
5. Exploring potential monetization models such as:
   - **Freemium models** where basic assessments are free, but advanced features are behind a paywall.
   - **Enterprise licensing** for bulk assessments and skill verification at scale.

## Compensation and Funding

We are requesting **$5,000 USD** (in ICP tokens) to fund the development of this 30-day MVP, which will cover:
- Development team time and resources.
- Canister costs and any other required tooling.

This MVP will serve as a proof-of-concept for the broader platform we aim to build, showing the potential of combining **AI-driven soft skill assessment** with **blockchain-based skill verification** on ICP.

