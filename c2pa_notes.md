# C2PA Notes

The **Coalition for Content Provenance and Authenticity (C2PA)** defines a standard for embedding metadata and provenance information directly into media files. Using C2PA in your AI native films allows future researchers and critics to verify the origin and context of each release.

To embed C2PA metadata:

1. **Choose a tool:** There are several open‑source and commercial tools for adding C2PA manifests (e.g., Adobe’s open‑source Content Credentials library).
2. **Prepare your manifest:** At minimum include:
   - **version hash**: a SHA‑256 or similar digest of your Story Brain graph or film cut.
   - **creation date and time**.
   - **engine version**: e.g., Story Brain v1.0.
   - **director**: Hooroo Jackson.
   - **prompt digest**: a hash or summary of your AI prompts and conversations.
3. **Embed into your video file:** Run the C2PA tool to attach the manifest to your MP4 or MOV file. Ensure the manifest references the DOIs for your theory texts.

Embedding C2PA early makes it easy for institutions to verify that the files originate with you and align with your published specification.
