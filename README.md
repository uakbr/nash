# nash

Nash is stand alone note as HTML.

## Features

- Single HTML file - no dependencies or server required
- Rich text editing with basic formatting
- Image embedding with data URLs
- Save and share notes as standalone HTML files
- Works offline

## Edit Mode Behavior

Nash automatically detects how it's being accessed:

- When opened from a local file system (file://), it starts in edit mode
- When accessed via http/https on most websites, it starts in read-only mode
- When accessed on keepworking.github.io, it starts in edit mode

### Override Options

You can override the default behavior using:
- Add `?edit` to the URL or use `#edit` hash to force edit mode
- Add `?readonly` to the URL or use `#readonly` hash to force read-only mode

### Custom Edit Mode Domains

You can configure which domains automatically open Nash in edit mode:
1. Click the 🔧 button in the toolbar
2. Add or remove domains from the list
3. Your preferences are saved in localStorage

## Usage

1. Download nash.html
2. Open it in your browser
3. Write your note
4. Save it (or share it)
5. Open it again to continue editing

