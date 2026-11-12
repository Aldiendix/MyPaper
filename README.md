# MyPaper

`dpex-paper.rar` is the complete working folder of the journal paper on **DPEX-DJA**, a dual-population hybrid metaheuristic (tabu-search trajectories plus a discrete-Jaya elite pool), evaluated on graph coloring (DIMACS) and Max-Cut (G-set).

The archive contains:

| Folder | Contents |
|---|---|
| `paper/` | LaTeX source, tables, figures, PDF and Word versions |
| `release/` | final v1 and v2 paper, Word file and code listing |
| `src/` | C++ benchmark code and the Python runners and analysis scripts |
| `instances/` | DIMACS coloring and G-set Max-Cut instances |
| `results/` | raw results of every run (JSON) |
| `code_pdf/` | the code listing as a PDF source |
| `references/` | BibTeX, reference status, best-known values, and `get_free_pdfs.sh` |
| `upstream/` | the reference implementation (also at github.com/Aldiendix/nova-first) |

## Extract

```bash
unrar x dpex-paper.rar        # or 7-Zip / WinRAR on Windows
```

## Reference papers

The PDFs of the cited papers are not included: free to read does not mean free to redistribute. After extracting, run

```bash
bash dpex-paper/references/get_free_pdfs.sh
```

It downloads the 16 freely available papers from their legitimate sources (authors' pages, arXiv, JMLR) and prints links for 6 more that must be opened in a browser.

The unpacked project is also browsable at github.com/Aldiendix/dpex-paper.
