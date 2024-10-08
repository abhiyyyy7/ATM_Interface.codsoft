<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>

<h1>ATM Simulation System</h1>

<p>This project simulates a basic ATM system where users can perform the following operations:</p>
<ul>
    <li>Withdraw money</li>
    <li>Deposit money</li>
    <li>Check account balance</li>
</ul>
<p>The ATM interacts with a <code>BankAccount</code> class, which holds the balance and allows basic banking operations. The <code>ATM</code> class provides a simple menu for users to interact with the system.</p>

<h2>Table of Contents</h2>
<ul>
    <li><a href="#features">Features</a></li>
    <li><a href="#getting-started">Getting Started</a></li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#code-structure">Code Structure</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
</ul>

<h2 id="features">Features</h2>
<ul>
    <li><strong>Withdraw Money</strong>: Users can withdraw money if the balance is sufficient.</li>
    <li><strong>Deposit Money</strong>: Users can deposit any positive amount into their account.</li>
    <li><strong>Check Balance</strong>: The current balance of the account is displayed in a formatted manner.</li>
</ul>

<h2 id="getting-started">Getting Started</h2>

<h3>Prerequisites</h3>
<ul>
    <li><strong>Java JDK 8 or higher</strong></li>
    <li>A Java IDE (such as IntelliJ IDEA, Eclipse) or a text editor with Java support.</li>
</ul>

<h3>Installation</h3>
<ol>
    <li>Clone the repository:
        <pre><code>git clone https://github.com/username/ATM-Simulation.git</code></pre>
    </li>
    <li>Navigate to the project directory:
        <pre><code>cd ATM-Simulation</code></pre>
    </li>
    <li>Open the project in your preferred Java IDE or compile and run it from the terminal.</li>
</ol>

<h3>Running the Application</h3>
<p>To run the application, use the <code>Main</code> class which initializes the <code>ATM</code> and <code>BankAccount</code> and starts the ATM menu.</p>
<pre><code># To run the application in the terminal:
javac com/Codesoft/Main.java
java com.Codesoft.Main
</code></pre>
<p>The default account starts with a balance of <code>1000.00</code>.</p>

<h2 id="usage">Usage</h2>
<p>Once the application starts, you will be presented with an ATM menu like this:</p>
<pre><code>ATM Menu:
1. Withdraw
2. Deposit
3. Check Balance
4. Exit
Please choose an option: 
</code></pre>

<p>Choose an option by entering a number (1-4). For withdrawal and deposit, you will be prompted to enter an amount. The current balance will always be displayed in a formatted output.</p>

<h3>Sample Interaction</h3>
<pre><code>ATM Menu:
1. Withdraw
2. Deposit
3. Check Balance
4. Exit
Please choose an option: 1
Enter the amount to withdraw: 500
Withdrawal successful. Current balance: 500.00

ATM Menu:
1. Withdraw
2. Deposit
3. Check Balance
4. Exit
Please choose an option: 3
Current balance: 500.00

ATM Menu:
1. Withdraw
2. Deposit
3. Check Balance
4. Exit
Please choose an option: 4
Thank you for using our ATM. Goodbye!
</code></pre>

<h2 id="code-structure">Code Structure</h2>
<p>The project contains three main classes:</p>
<ol>
    <li><strong><code>BankAccount</code></strong>: Manages account balance, deposit, and withdrawal operations.</li>
    <li><strong><code>ATM</code></strong>: Handles the user interface, providing a menu for withdrawing, depositing, and checking the balance.</li>
    <li><strong><code>Main</code></strong>: The entry point of the application that creates an instance of <code>ATM</code> and <code>BankAccount</code> and starts the ATM interface.</li>
</ol>

<h2 id="contributing">Contributing</h2>
<p>Feel free to submit issues or contribute to this project by forking the repository and submitting a pull request. All contributions are welcome!</p>

<h3>Steps to Contribute:</h3>
<ol>
    <li>Fork the project.</li>
    <li>Create a new branch for your feature or bug fix:
        <pre><code>git checkout -b feature/your-feature</code></pre>
    </li>
    <li>Make your changes.</li>
    <li>Commit your changes:
        <pre><code>git commit -m 'Add some feature'</code></pre>
    </li>
    <li>Push to the branch:
        <pre><code>git push origin feature/your-feature</code></pre>
</ol>
</body>
</html>
