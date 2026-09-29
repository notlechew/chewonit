# Invoice & Receipt Guide — Triad Trails

How to create invoices and receipts. Copy a template below into `invoices/` or `receipts/` and fill in the fields.

## When to use which

- **Invoice** — a request for payment, sent before or after the tour. Payment status: *Unpaid*.
- **Receipt** — proof of payment, issued once money is received. Payment status: *Paid*.

## File naming

```
invoices/YYYY-MM-DD-<client-name>.md   # date = tour date
receipts/YYYY-MM-DD-<client-name>.md
```

Example: `receipts/2026-09-30-gabrielle-chan.md`

## Numbering

- Invoices: `INV-YYYYMMDD-NN`
- Receipts: `RCP-YYYYMMDD-NN`

`YYYYMMDD` is the tour date; `NN` is a running number for that day (01, 02, …).

## Rules

1. Currency is **SGD** unless agreed otherwise.
2. Total = number of guests × price per person. Always show the working.
3. Put the client's name and mobile number under **Attention**.
4. List what the price includes, so the client knows exactly what they paid for.
5. Receipts must state the payment method and payment date.

## Invoice template

```markdown
# INVOICE

**Triad Trails**

| | |
|---|---|
| Invoice no. | INV-YYYYMMDD-NN |
| Issue date | D Month YYYY |
| Due date | D Month YYYY |

**Attention:** <Client name>
**Mobile:** <+country number>

## Details

| Description | Date & time | Qty | Unit price | Amount |
|---|---|---|---|---|
| <Tour name> | D Month YYYY, H:MM a.m./p.m. | N | $XX.00 | $XXX.00 |

**Includes:** <bullet or one-line list of inclusions>

**Total due: SGD $XXX.00**

**Payment status:** Unpaid
**Payment instructions:** <bank / PayNow details>
```

## Receipt template

```markdown
# RECEIPT

**Triad Trails**

| | |
|---|---|
| Receipt no. | RCP-YYYYMMDD-NN |
| Issue date | D Month YYYY |

**Attention:** <Client name>
**Mobile:** <+country number>

## Details

| Description | Date & time | Qty | Unit price | Amount |
|---|---|---|---|---|
| <Tour name> | D Month YYYY, H:MM a.m./p.m. | N | $XX.00 | $XXX.00 |

**Includes:** <bullet or one-line list of inclusions>

**Total paid: SGD $XXX.00**

**Payment method:** <PayNow / cash / bank transfer / card>
**Payment date:** D Month YYYY
**Payment status:** Paid

Thank you for joining Triad Trails.
```
