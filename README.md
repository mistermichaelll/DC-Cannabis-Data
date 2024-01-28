# DC-Cannabis-Data
This repository contains monthly data published by the DC Alcoholic Beverage and Cannabis Administration (DC ABCA) pertaining to Washington D.C.'s medical cannabis program.

# About the Program
Washington D.C.'s medical cannabis program is administered by the DC ABCA, which releases monthly data reports. Unfortunately, these reports are provided in PDF format, making it challenging for external researchers, students, or other interested parties to access and utilize the information effectively.

# About this Repository
This repository aims to address the accessibility issue by providing CSV datasets containing the same information found in the PDF reports published by the DC ABCA. The datasets have been compiled through straightforward data entry, with each file corresponding to the relevant table header in the PDF reports.

# Data Entry Notes
- Data in this repository begins from the December 2021 report. For October and November 2021, values were backfilled from the December report. **Going forward, no other entries are backfilled—each month's data corresponds to the values from that month's report.**
- In the February 2023 report, a new resident category was introduced to the report (*Non-DC Residents, Self-Certified Temporary*). The `individual_patients` value in the `patients.csv` file corresponds to the`Total Unique Patients who Purchased` value in the self-certified patients section of the PDF.
- In the October 2023 report, a new category was introduced for the monthly sales report: `Manufacturer`.
- New products were introduced in both the November and December 2023 reports. Though the PDF *does* represent prior two month sales for these new products, I did not backfill the CSV for consistency (eg. one report, one month's entry).

# Sources
The PDF sources are listed below:

## 2023
- [December](https://abca.dc.gov/sites/default/files/dc/sites/abra/page_content/attachments/MCP%20Metrics%20-%20December%202023.pdf)
- [November](https://abca.dc.gov/sites/default/files/dc/sites/abra/page_content/attachments/MCP%20Report%20-%20November%202023.pdf)
- [October](https://abca.dc.gov/sites/default/files/dc/sites/abra/page_content/attachments/MCP%20Metrics%20-%20October%202023.pdf)
- [September](https://abca.dc.gov/sites/default/files/dc/sites/abra/page_content/attachments/MCP%20Metrics%20-%20September%202023.pdf)
- [August](https://abca.dc.gov/sites/default/files/dc/sites/abra/page_content/attachments/MCP%20Metrics%20-%20August%202023.pdf)
- [July](https://abca.dc.gov/sites/default/files/dc/sites/abra/page_content/attachments/MCP%20Metrics%20-%20July%202023.pdfs)
- [June](https://abca.dc.gov/sites/default/files/dc/sites/abra/page_content/attachments/MCP%20Metrics%20-%20June%202023%20%281%29.pdfs)
- [May](https://abca.dc.gov/sites/default/files/dc/sites/abra/page_content/attachments/MCP%20Metrics%20-%20May%202023.pdfs)
- [April](https://abca.dc.gov/sites/default/files/dc/sites/abra/page_content/attachments/MCP%20Metrics%20-%20April%202023.pdf)
- [March](https://abca.dc.gov/sites/default/files/dc/sites/abra/page_content/attachments/MCP%20Metrics%20-%20March%202023%20%282%29.pdfs)
- [February](https://abca.dc.gov/sites/default/files/dc/sites/abra/page_content/attachments/MCP%20Metrics%20Report%20-%20February%202023.pdf)
- [January](https://abca.dc.gov/sites/default/files/dc/sites/abra/page_content/attachments/MCP%20Metrics%20January%202023.pdf)

## 2022
- [December](https://abca.dc.gov/sites/default/files/dc/sites/abra/page_content/attachments/MCP%20Metrics%20Report%20-%20December%202022.pdf)
- [November](https://abca.dc.gov/sites/default/files/dc/sites/abra/page_content/attachments/MCP%20Metrics%20November%202022%20Report.pdf)
- [October](https://abca.dc.gov/sites/default/files/dc/sites/abra/page_content/attachments/MCP%20Metrics%20October%202022.pdf)
- [September](https://abca.dc.gov/sites/default/files/dc/sites/abra/page_content/attachments/MCP%20Metrics%20September%202022.pdf)
- [August](https://abca.dc.gov/sites/default/files/dc/sites/abra/page_content/attachments/MCP%20Metrics%20August%202022%20Report.pdf)
- [July](https://abca.dc.gov/sites/default/files/dc/sites/abra/page_content/attachments/MCP%20Metrics%20July%202022%20Report.pdf)
- [June](https://abca.dc.gov/sites/default/files/dc/sites/abra/page_content/attachments/MCP%20Metrics%20June%202022%20Report.pdf)
- [May](https://abca.dc.gov/sites/default/files/dc/sites/abra/page_content/attachments/MCP%20Metrics%20May%202022.pdf)
- [April](https://abca.dc.gov/sites/default/files/dc/sites/abra/page_content/attachments/MCP%20Metrics%20April%202022%20Report.pdf)
- [March](https://abca.dc.gov/sites/default/files/dc/sites/abra/page_content/attachments/MCP%20Metrics%20March%202022%20Report.pdf)
- [February](https://abca.dc.gov/sites/default/files/dc/sites/abra/page_content/attachments/MCP%20Metrics%20February%202022%20Report.pdf)
- [January](https://abca.dc.gov/sites/default/files/dc/sites/abra/page_content/attachments/MCP%20Metrics%20January%202022.pdf)

## 2021
- [December](https://abca.dc.gov/sites/default/files/dc/sites/abra/publication/attachments/MCP%20Metrics%20December%202021.pdf)
- [November](https://abca.dc.gov/sites/default/files/dc/sites/abra/publication/attachments/MCP%20Metrics%20November%202021_2.pdf)
- [January](https://abca.dc.gov/sites/default/files/dc/sites/abra/publication/attachments/2021-01-27%20MCP%20Program%20Report.pdf)