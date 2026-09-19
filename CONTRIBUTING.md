# Contributing Event Documentation

Are you an event organizer, speaker, or documentation lead for an AIML Club OCT session? Follow this guide to archive event materials.

---

## Submission Checklist

Before opening a pull request to archive an event:

1. **Use the Standard Folder Structure:**
   ```text
   EVENTS/[year]/[yyyy-mm-dd-event-name]/
   ├── README.md
   ├── poster/
   ├── presentation/
   └── resources/
   ```
2. **Follow the Template:** Base your event's `README.md` on [`templates/EVENT_TEMPLATE.md`](./templates/EVENT_TEMPLATE.md).
3. **Verify Privacy:** Ensure no personal contact details (phone numbers, private email addresses, student IDs) are included in slide decks, text files, or photos.
4. **Compress Images:** Ensure photographs and posters are compressed (keep each image under 2MB) to keep git repository clones fast and lightweight.
5. **Open Pull Request:** Name your PR `docs(events): archive [event name] [year]`.
