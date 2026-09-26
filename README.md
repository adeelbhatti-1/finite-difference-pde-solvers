# Finite Difference Pde Solvers

Finite-difference experiments for steady and transient heat conduction and one-dimensional convection–diffusion.

## Contents

| File | Original filename |
|---|---|
| [notebooks/01_steady_1d_heat_conduction.ipynb](notebooks/01_steady_1d_heat_conduction.ipynb) | FDM_Exam4.ipynb |
| [notebooks/02_steady_2d_heat_conduction.ipynb](notebooks/02_steady_2d_heat_conduction.ipynb) | FDM_Exm3.ipynb |
| [notebooks/03_transient_1d_heat_conduction.ipynb](notebooks/03_transient_1d_heat_conduction.ipynb) | FDM_Exm5.ipynb |
| [notebooks/04_transient_2d_heat_conduction.ipynb](notebooks/04_transient_2d_heat_conduction.ipynb) | FDM_Exam7.ipynb |
| [notebooks/05_convection_diffusion_comparison.ipynb](notebooks/05_convection_diffusion_comparison.ipynb) | FDM_Exm6.ipynb |

## Run

For Python notebooks, install the inferred dependencies:

```bash
python -m pip install -r requirements.txt
python -m jupyterlab
```

Open a notebook and run cells from the beginning. Alternatively upload the notebook to Google Colab. Replace local or Google Drive paths with your own data locations before running. Notebooks are independent unless explicitly stated otherwise. For C++ files, compile and run each example separately with a compatible C++ compiler.

## Status and limitations

The notebooks contain numerical experiments and plots. Check boundary conditions, grid definitions, convergence, and explicit-scheme stability for each new parameter choice. No execution or numerical accuracy claim is made by this packaging step.

This collection was organised from existing files. Code-cell contents were preserved; saved outputs, execution counts, and transient notebook metadata were removed. The notebooks have not been executed as part of this preparation. Dependencies are inferred and unpinned, not a tested environment lockfile.

## Results

Run the examples to regenerate results. No accuracy, performance, or correctness claims are made here.

## Provenance

See [SOURCE_MAP.csv](SOURCE_MAP.csv) for the source archive and original filename. Preserve existing acknowledgements. No blanket open-source licence has been added because rights for adapted course material and datasets have not been established.
