# n8n Tips

## n8n document 문서 하나로 합치기

```bash
git clone https://github.com/n8n-io/n8n-docs.git
cd n8n-docs
find . -name "*.md" -exec cat {} +  > ../n8n_docs_combined.md
```

