# Tech stack logos

Local assets for the **Tech Stack** section in `README.md`. Icons are served from this repo (not a CDN) so the profile README stays self-contained.

## Layout

```
tech-logos/
├── icons/          # Devicon-style icons (mostly *-original.svg)
├── *.svg           # Standalone brand assets (SciPy, LangChain, etc.)
└── *.png           # Raster logos where SVG was unavailable
```

## README usage

Each icon follows this pattern:

```html
<a href="https://example.com/" title="Name">
  <img src="tech-logos/..." width="40" height="40" alt="Name"/>
</a>
```

Paths are relative to the repo root (works on `github.com/ArefinAlter` profile README).

## Sources

| Source | Used for |
|--------|----------|
| [Devicon](https://github.com/devicons/devicon) | Most `tech-logos/icons/*/*-original.svg` files |
| Official / project sites | `SCIPY.svg`, `langchain.svg`, `ml-flow.svg`, research tools, etc. |

## GitHub dark mode

Monochrome black SVGs are hard to read on GitHub’s dark background when loaded via `<img>`. Prefer **brand colors** with `fill` on each `<path>` (not only on the root `<svg>`).

| Logo | File | Fill color |
|------|------|------------|
| Rust | `icons/rust/rust-original.svg` | `#F46624` |
| LaTeX | `icons/latex/latex-original.svg` | `#008080` |
| Kafka | `icons/apachekafka/apachekafka-original.svg` | `#00B4D8` |

For light/dark theme swapping, GitHub supports `<picture>` with `prefers-color-scheme` ([GitHub docs](https://github.blog/developer-skills/github/how-to-make-your-images-in-markdown-on-github-adjust-for-dark-mode-and-light-mode/)).

## Inventory (README → file)

| Label | Path |
|-------|------|
| Python | `tech-logos/icons/python/python-original.svg` |
| R | `tech-logos/icons/r/r-original.svg` |
| SQL | `tech-logos/icons/postgresql/postgresql-original.svg` |
| JavaScript | `tech-logos/icons/javascript/javascript-original.svg` |
| TypeScript | `tech-logos/icons/typescript/typescript-original.svg` |
| C++ | `tech-logos/icons/cplusplus/cplusplus-original.svg` |
| MATLAB | `tech-logos/icons/matlab/matlab-original.svg` |
| PHP | `tech-logos/icons/php/php-original.svg` |
| LaTeX | `tech-logos/icons/latex/latex-original.svg` |
| Bash | `tech-logos/icons/bash/bash-original.svg` |
| Go | `tech-logos/icons/go/go-original.svg` |
| Julia | `tech-logos/icons/julia/julia-original.svg` |
| Rust | `tech-logos/icons/rust/rust-original.svg` |
| PyTorch | `tech-logos/icons/pytorch/pytorch-original.svg` |
| TensorFlow | `tech-logos/icons/tensorflow/tensorflow-original.svg` |
| scikit-learn | `tech-logos/icons/scikitlearn/scikitlearn-original.svg` |
| Pandas | `tech-logos/icons/pandas/pandas-original.svg` |
| NumPy | `tech-logos/icons/numpy/numpy-original.svg` |
| SciPy | `tech-logos/SCIPY.svg` |
| Gensim | `tech-logos/gensim.png` |
| Hugging Face | `tech-logos/huggingface.svg` |
| LangChain | `tech-logos/langchain.svg` |
| Streamlit | `tech-logos/icons/streamlit/streamlit-original.svg` |
| PyTorch3D | `tech-logos/pytorch3d.svg` |
| LangGraph | `tech-logos/langgraph.svg` |
| SPSS | `tech-logos/icons/spss/spss-original.svg` |
| Stata | `tech-logos/icons/stata/stata-original-wordmark.svg` |
| Wolfram | `tech-logos/icons/wolfram/wolfram-original.svg` |
| Jupyter | `tech-logos/icons/jupyter/jupyter-original.svg` |
| Power BI | `tech-logos/Power_BI_Logo.svg` |
| Tableau | `tech-logos/tableau.svg` |
| Plotly | `tech-logos/icons/plotly/plotly-original.svg` |
| D3.js | `tech-logos/icons/d3js/d3js-original.svg` |
| matplotlib | `tech-logos/icons/matplotlib/matplotlib-original.svg` |
| Next.js | `tech-logos/icons/nextjs/nextjs-original.svg` |
| React | `tech-logos/icons/react/react-original.svg` |
| FastAPI | `tech-logos/icons/fastapi/fastapi-original.svg` |
| Node.js | `tech-logos/icons/nodejs/nodejs-original.svg` |
| GraphQL | `tech-logos/graphql.svg` |
| Tailwind | `tech-logos/icons/tailwindcss/tailwindcss-original.svg` |
| Supabase | `tech-logos/icons/supabase/supabase-original.svg` |
| Django | `tech-logos/django.svg` |
| Docker | `tech-logos/icons/docker/docker-original.svg` |
| Kubernetes | `tech-logos/icons/kubernetes/kubernetes-original.svg` |
| GitHub Actions | `tech-logos/icons/githubactions/githubactions-original.svg` |
| Terraform | `tech-logos/icons/terraform/terraform-original.svg` |
| Ansible | `tech-logos/icons/ansible/ansible-original.svg` |
| Google Cloud | `tech-logos/icons/googlecloud/googlecloud-original.svg` |
| AWS | `tech-logos/aws.svg` |
| Azure | `tech-logos/icons/azure/azure-original.svg` |
| Grafana | `tech-logos/icons/grafana/grafana-original.svg` |
| MLflow | `tech-logos/ml-flow.svg` |
| W&B | `tech-logos/weights_and_biases.svg` |
| Airflow | `tech-logos/icons/apacheairflow/apacheairflow-original.svg` |
| Spark | `tech-logos/icons/apachespark/apachespark-original.svg` |
| Kafka | `tech-logos/icons/apachekafka/apachekafka-original.svg` |
| MySQL | `tech-logos/icons/mysql/mysql-original.svg` |
| PostgreSQL | `tech-logos/icons/postgresql/postgresql-original.svg` |
| MongoDB | `tech-logos/icons/mongodb/mongodb-original.svg` |
| Redis | `tech-logos/icons/redis/redis-original.svg` |
| Git | `tech-logos/icons/git/git-original.svg` |
| Elasticsearch | `tech-logos/icons/elasticsearch/elasticsearch-original.svg` |
| Neo4j | `tech-logos/icons/neo4j/neo4j-original.svg` |
| MAXQDA | `tech-logos/MAXQDA.svg` |
| KoboToolbox | `tech-logos/kobotoolbox.png` |
| NVivo | `tech-logos/nvivo.png` |
