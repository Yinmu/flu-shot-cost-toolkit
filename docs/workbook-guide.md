# Use the comparison workbook

The workbook has two sheets: **Compare**, a blank template for your quotes, and **Example**, an editable demonstration using invented prices. Each sheet calculates independently. Start on Compare; changing Example does not populate Compare.

## Inputs and totals

Yellow cells are editable. Other cells contain labels or formulas. Keep the formula cells intact.

- Each column is one option: a provider/location or a complete plan you want to compare. Give it a meaningful name and quote source.
- Each person has a product, confirmed remaining dose count, unit price, and calculated line cost. Leave all three input cells empty for an unused person.
- Enter doses only after confirming them with the provider. Zero is allowed when there are no remaining doses; an empty dose cell means unknown when the person block contains other inputs.
- Unit prices and other amounts must be nonnegative numbers in USD, with no more than two decimal places. Do not type currency symbols into a numeric cell.
- Extra fees are the total for the whole option, across all people and planned visits. Enter an explicit `0` only after confirming that none apply.
- The discount field starts at `0`, meaning no immediate discount is included. Subtract a discount only once, and only if it is not already reflected in the unit prices.
- Travel starts at **Exclude**. Choose **Include** and enter the total travel cost across all planned visits if you want to count it. This total is added once for the option.

The estimated total at the top links to the full calculation below. It updates when inputs change. No automatic lowest-price or savings badge is shown: the tool cannot verify that products and conditions are equivalent.

## Formula messages

| Message | What to do |
| --- | --- |
| Check people | Review the person blocks; enter at least one complete quote and fix any dose/price messages |
| Add doses / Check doses | Enter a confirmed whole-number dose count; the input field accepts 0–10 for arithmetic, not as a medical recommendation |
| Add price | Enter the amount quoted per dose |
| Check amount / Use cents | Use a nonnegative number up to $1,000,000, with at most two decimal places |
| Add fees | Confirm total additional fees; an unknown charge is not zero |
| Add discount / Check discount | Enter a nonnegative immediate discount no greater than the combined dose costs and extra fees |
| Add travel / Choose travel | Enter travel when included, or choose Include/Exclude from the selector |

Record any insurance or membership conditions with the quote. For an insured estimate, enter the confirmed out-of-pocket amount rather than assuming the published cash price or a zero copay applies.

## Save and share carefully

Download the XLSX and open it in an application that supports spreadsheet formulas. GitHub's file view does not calculate the workbook. If you import it into a cloud spreadsheet service, that service receives the file you upload.

The workbook contains no macros, external data queries or automatic network connections. Clicking an explicit website hyperlink opens the linked site. Save your completed comparison privately. Share the blank template or fictional Example sheet instead of posting a family's details publicly.

The CSV is a separate quote collection sheet. It contains column headings only and has no formulas. It is useful for recording source details before transferring them into the workbook or the online estimator.

Official website: [FluShotsNearMe.com](https://flushotsnearme.com/). Online references and estimator: [flu shot costs without insurance](https://flushotsnearme.com/flu-shot-cost/).
