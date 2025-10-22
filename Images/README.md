# Images Folder

Central repository for all images used across notes, tasks, and documentation.

## 📁 Folder Structure

- **`screenshots/`** - Screen captures, UI screenshots, browser captures
- **`diagrams/`** - Architecture diagrams, flowcharts, system designs
- **`photos/`** - Photos, whiteboard captures, team photos
- **`icons/`** - Icons, logos, small graphics

## 📝 Usage in Markdown Files

### From DailyNotes
```markdown
![Description](../../Images/screenshots/example.png)
```

### From MeetingNotes
```markdown
![Description](../../Images/diagrams/architecture.png)
```

### From PersonalTasks
```markdown
![Description](../../Images/photos/whiteboard.png)
```

## 📋 File Naming Best Practices

### Use descriptive, kebab-case names:
- ✅ `aws-architecture-diagram.png`
- ✅ `sprint-planning-whiteboard.jpg`
- ✅ `login-screen-screenshot.png`
- ❌ `image1.png`
- ❌ `Screen Shot 2025-10-20.png`

### Include dates for time-sensitive images:
- `2025-10-20_system-status.png`
- `2025-10-20_bug-screenshot.png`

## 🎨 Supported Formats

- **PNG** - Screenshots, diagrams with transparency
- **JPG/JPEG** - Photos, images without transparency
- **SVG** - Scalable vector graphics, icons
- **GIF** - Animated images (use sparingly)

## 📐 Image Size Guidelines

- **Screenshots:** Keep under 2MB, optimize when possible
- **Diagrams:** Export at reasonable resolution (1920px max width)
- **Photos:** Compress to balance quality and file size
- **Icons:** Small, optimized (typically under 100KB)

## 🔗 Quick Reference

### Relative Path Examples

| From Location               | To Images Folder | Example Path                        |
| --------------------------- | ---------------- | ----------------------------------- |
| `_DailyNotes/2025/October/` | `../../Images/`  | `../../Images/screenshots/file.png` |
| `_PersonalTasks/Active/`    | `../../Images/`  | `../../Images/diagrams/file.png`    |
| `_PersonalTasks/Upcoming/`  | `../../Images/`  | `../../Images/photos/file.png`      |
| Root level markdown         | `./Images/`      | `./Images/icons/file.png`           |

## 💡 Tips

1. **Drag & Drop:** In VS Code, you can drag images into markdown (with proper extensions)
2. **Paste from Clipboard:** Some extensions allow pasting images directly
3. **Optimize:** Use image optimization tools before adding large files
4. **Alt Text:** Always include descriptive alt text for accessibility
5. **Backup:** Consider these images in your backup strategy

---

**Last Updated:** October 22, 2025
