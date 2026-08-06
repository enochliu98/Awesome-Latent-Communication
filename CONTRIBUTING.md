# 🤝 Contributing
We sincerely welcome paper updates / contributions of any kind (and please do that lol)! Feel free to *open issues* or *create pull requests*. <br>

## Adding New Papers
If you want to add a new paper, please modify the **Related Works** table in `README.md` and follow its format:

```markdown
| year/month | [**Method**: Title of the Paper](arXiv abstract link) | Overview figure or short introduction | [Code](GitHub link) |
```

### Recommended Guidelines:
- Use the **earliest date** of the paper (the month of the arXiv v1 submission), and insert the row in **ascending order** of date.
- If possible, use arXiv links rather than links from other resources (e.g. conference page), and provide the link to the *abstract* page (`https://arxiv.org/abs/...`) instead of the PDF page.
- If the paper is accepted by a conference or journal, please add the tag ![NAME'YEAR](https://img.shields.io/badge/NAME'YEAR-f1b800) before the title. See existing cases.
- For the introduction column, add an overview figure of the method to the `figs/` folder (keep it as aesthetically pleasing as possible; avoid leaving too much blank space), or provide a concise 1–2 sentence text introduction.
- If the GitHub link is available, please add it as `[Code](link)`; otherwise, use "-" instead.

### Examples

```markdown
| 2025/10 | ![ICLR'26](https://img.shields.io/badge/ICLR'26-f1b800) <br/> [**Cache-to-Cache**: Direct Semantic Communication Between Large Language Models](https://arxiv.org/abs/2510.03215) | ![](figs/r4.png) | [Code](https://github.com/thu-nics/C2C) |
```
```markdown
| 2026/05 | [**LCGuard**: Latent Communication Guard for Safe KV Sharing in Multi-Agent Systems](https://arxiv.org/abs/2605.22786) | Safety layer for KV-based latent communication that learns representation-level transformations before caches are shared. | - |
```
