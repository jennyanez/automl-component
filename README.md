# AutoML Preprocessing Component

A KNIME workflow for preprocessing datasets used in classification-oriented AutoML experiments.

This repository contains the workflow artifacts used by the project and complementary test workflows. It is part of the work documented in the companion thesis repository: [thesis-doc](https://github.com/jennyanez/thesis-doc).

## Repository contents

| File | Description |
| --- | --- |
| `AutoML Clasificacion (pre-procesado).knwf` | Main KNIME workflow for classification preprocessing |
| `pruebas.knwf` | Workflow used for tests and experimentation |

## Requirements

- [KNIME Analytics Platform](https://www.knime.com/downloads)
- A dataset prepared for a classification task
- The KNIME extensions required by the nodes included in the workflow

The exact KNIME version and extension list should be kept aligned with the environment used to create or validate the workflows.

## Getting started

1. Install and open KNIME Analytics Platform.
2. Download or clone this repository.
3. Import the `.knwf` file into KNIME:
   - Open the **File** menu.
   - Select **Import KNIME Workflow**.
   - Choose `AutoML Clasificacion (pre-procesado).knwf`.
4. Review the workflow configuration and connect the input to your dataset.
5. Execute the workflow node by node or run it as a complete workflow.
6. Use `pruebas.knwf` when you need to inspect or reproduce the project experiments.

## Expected use

The workflow is intended to support the preprocessing stage before classification experiments. Use it as a reusable KNIME artifact inside an AutoML pipeline, adapting its input and configuration to the dataset being analyzed.

Because KNIME workflows may depend on installed extensions, local paths, node versions, or input-column names, validate the imported workflow in your own KNIME environment before using it in a production pipeline.

## Related work

- [Thesis documentation](https://github.com/jennyanez/thesis-doc)
- [KNIME Analytics Platform](https://www.knime.com/)

## Project status

Academic/research artifact focused on preprocessing for classification tasks in KNIME.
