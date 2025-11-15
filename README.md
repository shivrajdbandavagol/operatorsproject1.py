# operatorsproject1.py
A mini project based on the basic operators
#python assignment operators


# Bank Account Simulator using Assignment Operators

print("Welcome to NexEffulgence Bank")
print("----------------------------------")

# Step 1: Initialize account balance
balance = float(input("Enter your starting balance (₹): "))

# Step 2: Deposit money
deposit = float(input("Enter amount to deposit (₹): "))
balance += deposit
print(f"After depositing ₹{deposit}, your balance is ₹{balance}")

# Step 3: Withdraw money
withdraw = float(input("Enter amount to withdraw (₹): "))
balance -= withdraw
print(f"After withdrawing ₹{withdraw}, your balance is ₹{balance}")

# Step 4: Apply interest (for example, 5%)
balance *= 1.05
print(f"After adding 5% interest, your balance is ₹{round(balance, 2)}")

# Step 5: Deduct bank charges (for example, 2%)
balance *= 0.98
print(f"After deducting 2% bank charges, your balance is ₹{round(balance, 2)}")

# Step 6: Find remainder after dividing by 100
balance %= 100
print(f"Remaining amount after full ₹100 notes: ₹{round(balance, 2)}")

# Step 7: Final summary
print("----------------------------------")
print(f"Final balance left in your account: ₹{round(balance, 2)}")
print("Thank you for banking with NexEffulgence Bank")
