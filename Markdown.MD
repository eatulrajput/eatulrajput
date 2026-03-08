# Symbols in Markdown

To write an alert block in Markdown, use the
blockquote syntax combined with a specific keyword like [!NOTE] or [!WARNING]. This syntax is supported by platforms such as GitHub Docs, MDN Web Docs, and Microsoft Learn. 

## Standard Syntax
The general format is a blockquote where the very first line specifies the alert type in square brackets, prefixed by an exclamation mark. 
The content of the alert follows in subsequent blockquote lines. 

```
> [!TYPE]
> The content of your alert goes here.
> It can span multiple lines and paragraphs within the blockquote.
```

> Each line, including blank lines within the alert, must begin with the > character.

### Supported Alert Types
The following alert types are widely supported in GitHub Flavored Markdown (GFM) and other compatible platforms: 

**NOTE**: For useful, general information.

> [!NOTE]
> Useful information that users should know, even when skimming content.

**TIP**: For optional information or helpful advice.

> [!TIP]
> Helpful advice for doing things better or more easily.

**IMPORTANT**: For crucial information that is necessary for users to succeed.

> [!IMPORTANT]
> Key information users need to know to achieve their goal.

**WARNING**: For urgent information demanding immediate attention to avoid potential problems.

> [!WARNING]
> Urgent info that needs immediate user attention to avoid problems.

