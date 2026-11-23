# OECD ICIO replication protocol

## Inputs
ICIO2018_2015.xlsx, ICIO 2018 release for reference year 2015; supporting ReadMe_ICIO_CSV.xlsx.

## Reported values to reproduce (current million USD)
- Manufacturing → manufacturing: 16,173,977.02
- Manufacturing → selected business services: 1,259,256.37
- Selected business services → manufacturing: 2,443,319.79
- Relative flow intensity: 0.2289
- Asymmetry index: 0.3198

## Sensitivity targets
| Specification | RFI | AI |
|---|---:|---:|
| All six services | 0.2289 | 0.3198 |
| Excluding finance and insurance | 0.1783 | 0.2162 |
| Excluding real estate | 0.2103 | 0.3545 |
| Excluding both | 0.1596 | 0.2497 |
| Information and communication | 0.0419 | -0.2355 |
| IT and other information services | 0.0137 | -0.0958 |
| Other business-sector services | 0.1177 | 0.4226 |

## Mandatory independent checks
1. Open the actual workbook and its ReadMe; record matrix dimensions, labels, year, units, industry mapping and excluded rows/columns.
2. Verify orientation of suppliers and users (rows/columns) before naming directions.
3. Define manufacturing and each of six service categories using source codes; explicitly document membership and denominators.
4. Recalculate aggregate flows from matrix cells. Calculate RFI and AI from the exact equations specified in the R2 manuscript; verify signs and denominator conventions.
5. Reproduce each sensitivity scenario independently, not from rounded published numbers.
6. Cross-check every manuscript number, table, abstract claim and interpretation. Document any discrepancy in the Response to Reviewers.
7. Never infer operational data transfers, governance effectiveness, causal effects or modern AI/cloud patterns from monetary intermediate transactions.

The numbers above are manuscript-reported verification targets, not proof that the workbook was loaded in Claude's workspace.
