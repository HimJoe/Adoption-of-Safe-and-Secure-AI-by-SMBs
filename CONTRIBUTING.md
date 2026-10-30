# Adding a tool to the SME AI Safety Toolkit

Each tool lives in its own folder under `skills/` and follows the same pattern, so an SME can use it with any AI assistant.

## Folder layout

```
skills/<tool-name>/
  SKILL.md          # required: front matter (name, description) and instructions, platform-neutral
  SOP.docx          # recommended: how to set up and run the tool
  <extras>          # optional: PDF, editable Word, templates
```

## Rules for a tool

1. **Platform-neutral.** Do not rely on any one assistant's tools, files or connectors. The tool must work from the conversation alone.
2. **Plain language.** Written for an owner or manager with no security or legal background.
3. **Decision, not approval.** The tool records readiness; the business owner approves.
4. **Clear limits.** Say where legal questions go to a professional.
5. **Attribution.** Keep "Prepared by SafeAlign AI · info@safealignai.io" in the tool and its SOP.
6. **Name.** Lowercase, hyphenated, and not containing "claude" or "anthropic".

## Adding a card to the site

Add a card to the **Tools** section of `index.html`, marking it "Available now" and linking to the tool's folder.

## Suggestions

Open an issue, or email info@safealignai.io.
