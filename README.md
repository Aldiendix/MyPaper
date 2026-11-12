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

`references/pdf/` holds the 17 cited papers that are freely available online (from the authors' pages, arXiv, JMLR and the EPFL repository). Copyright stays with their authors and publishers; the source of each file is listed in `references/STATUS.md`. To fetch them again from the original sources:

```bash
bash dpex-paper/references/get_free_pdfs.sh
```

The script also prints links for 5 more free papers that must be opened in a browser.

The unpacked project is also browsable at github.com/Aldiendix/dpex-paper.
