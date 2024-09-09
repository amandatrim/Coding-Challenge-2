# Coding-Challenge-2
Developing an application to help diners to easily split their bill
// Task 1: Tip

let billAmount = 50; 

let tip = billAmount >= 50 ? billAmount * 0.2 : billAmount * 0.15;

console.log("Tip amount: $" + tip.toFixed(2));

function calculateTip(bill) {
    return bill >= 50 ? bill * 0.2 : bill * 0.15;
}

// Test the function with a bill value of $100
let testBill = 100;
let testTip = calculateTip(testBill);
console.log(`For a bill of $${testBill}, the tip is $${testTip.toFixed(2)}`);

  
