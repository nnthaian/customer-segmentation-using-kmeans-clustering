This is a dataset for developing a customer segmentation. The dataset summarizes the usage behavior of active credit card holders during the last 6 months. The file is at a customer level with **17 behavioral variables**.

- **BALANCE:** Balance amount left in their account to make purchases.
- **BALANCE_FREQUENCY:** How frequently the Balance is updated, score between 0 and 1 (1 = frequently updated, 0 = not frequently updated).
- **PURCHASES:** Amount of purchases made from account.
- **ONEOFF_PURCHASES:** Maximum purchase amount done in one-go (i.e., one-time payment for a purchase).
- **INSTALLMENTS_PURCHASES:** Amount of purchase done in installment (i.e., multiple payments for a purchase). Observation: PURCHASES = ONEOFF_PURCHASE + INSTALLMENT_PURCHASES).
- **CASH_ADVANCE:** Cash in advance given by the user (a cash advance is when taking money out of the ATM using credit card instead of debit card or ATM card).
- **PURCHASES_FREQUENCY:** How frequently the Purchases are being made, score between 0 and 1 (1 = frequently purchased, 0 = not frequently purchased).
- **ONEOFF_PURCHASES_FREQUENCY:** How frequently Purchases are happening in one-go (1 = frequently purchased, 0 = not frequently purchased).
- **PURCHASES_INSTALLMENTS_FREQUENCY:** How frequently purchases in installments are being done (1 = frequently done, 0 = not frequently done).
- **CASH_ADVANCE_FREQUENCY:** How frequently the cash in advance being paid.
- **CASH_ADVANCE_TRX:** Number of Transactions made with "Cash in Advanced".
- **PURCHASES_TRX:** Number of purchase transactions made.
- **CREDIT_LIMIT:** Limit of Credit Card for user.
- **PAYMENTS:** Amount of payment done by user (i.e., payment for the use of credit card)
- **MINIMUM_PAYMENTS:** Minimum amount of payments made by user.
- **PRC_FULL_PAYMENT:** Percent of full payment paid by user.
- **TENURE:** Tenure of credit card service for user (i.e., how long (in months) you should have held the credit card before they will grant you credit).
