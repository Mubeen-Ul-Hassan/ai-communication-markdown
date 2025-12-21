# Tables

Markdown tables are useful for organizing information into rows and columns.

A table is created using:

- **Pipes** `|` to separate columns

- **Hyphens** `-` to separate the header from the body

## Basic Table Structure
**Syntax**
```
| Header 1 | Header 2 | Header 3 |
|----------|----------|----------|
| Row 1    | Data     | Data     |
| Row 2    | Data     | Data     |
```

**Example Table**
```
| Name  | Role     | Location |
|-------|----------|----------|
| Alex  | Developer| Remote   |
| Sam   | Designer | New York |
```

## Column Alignment

You can control text alignment using colons `:` in the separator row.

### Alignment options
```
| Left Align | Center Align | Right Align |
|:-----------|:------------:|------------:|
| Text       | Text         | Text        |
```

## Tables Without Perfect Alignment

Markdown does not require perfect spacing. This works the same:

```
| Item | Price | In Stock |
|---|---|---|
| Book | $10 | Yes |
| Pen | $2 | No |
```
