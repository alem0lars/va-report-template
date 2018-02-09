# va-report-template

Simple LaTeX template for Vulnerability Assessment

## Description

Template meant to be used with `report-va` chip.

Inside every template, the variable `context` holds the context.

## Usage example

Copy template to a custom directory and customize it to suit your needs.

Using chip `report-va`:

```
report-va -t $LATEX_REPORT_DIR/src -d $DATA_FILE -o $OUTPUT_REPORT_FILE
```
