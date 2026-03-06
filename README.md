# UK VAT Calculator

# Input price
price = float(input("Enter price: £"))
vat_rate = 20  # UK standard VAT

# Calculations
vat_amount = price * vat_rate / 100
total_price = price + vat_amount
price_ex_vat = price / (1 + vat_rate/100)

# Output
print(f"\nVAT amount: £{vat_amount:.2f}")
print(f"Total price (incl. VAT): £{total_price:.2f}")
print(f"Price excluding VAT: £{price_ex_vat:.2f}")
