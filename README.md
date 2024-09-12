
<h1>Inventory Management System</h1>

<h2>Description</h2>

<p>This project is a simple <strong>Inventory Management System</strong> built in Python, which allows users to purchase products, check inventory, and generate sales reports. The program reads from an <code>Inventory.txt</code> file to get product details, allows users to input their purchase requests, updates the inventory accordingly, and logs the sales transactions in a <code>Sales.txt</code> file.</p>

<h2>Features</h2>

<ul>
    <li><strong>Product Inventory Management</strong>: Maintain a list of products with their IDs, names, prices, and available quantities.</li>
    <li><strong>User Purchase</strong>: Allows a user to purchase products by entering product ID and desired quantity.</li>
    <li><strong>Sales Logging</strong>: Automatically logs every sale with user details and the time of the transaction in a <code>Sales.txt</code> file.</li>
    <li><strong>Inventory Update</strong>: Adjusts inventory quantities based on sales and updates the <code>Inventory.txt</code> file.</li>
</ul>

<h2>Project Structure</h2>

<ul>
    <li><code>Inventory.txt</code>: A text file containing details of all the available products in the format: <code>Product ID,Product Name,Price,Quantity</code>.</li>
    <li><code>Sales.txt</code>: A text file where every transaction is logged with user details, product information, and time of purchase.</li>
</ul>

<h2>Installation</h2>

<p>To run this project, you'll need to have Python installed on your machine. Follow these steps to set up the project:</p>

<ol>
    <li><strong>Clone the repository</strong>:
        <pre><code>git clone https://github.com/ArmanAhmed00/Inventory-Management-System.git</code></pre>
    </li>
    <li><strong>Navigate to the project directory</strong>:
        <pre><code>cd Inventory-Management-System</code></pre>
    </li>
    <li><strong>Prepare the <code>Inventory.txt</code> file</strong>:
        <ul>
            <li>Ensure that an <code>Inventory.txt</code> file exists in the same directory as your script with the following format:
                <pre><code>ProductID,ProductName,Price,Quantity
101,Apple,10,50
102,Banana,5,100
</code></pre>
            </li>
        </ul>
    </li>
</ol>

<h2>Usage</h2>

<ol>
    <li><strong>Run the program</strong>:
        <pre><code>python Inventory-Management-System.py</code></pre>
    </li>
    <li><strong>Input Details</strong>:
        <ul>
            <li>The program will prompt the user for their name, phone number, email, product ID, and quantity to purchase.</li>
        </ul>
    </li>
    <li><strong>View Purchase Details</strong>:
        <ul>
            <li>The program will display the details of the purchase including the product name, price, quantity, and total billing amount.</li>
            <li>If the requested quantity exceeds the available quantity, the program will prompt the user to purchase the remaining stock or cancel the purchase.</li>
        </ul>
    </li>
    <li><strong>Check Updated Inventory</strong>:
        <ul>
            <li>After a successful transaction, the inventory will be updated in <code>Inventory.txt</code>, and the sale will be logged in <code>Sales.txt</code>.</li>
        </ul>
    </li>
</ol>

<h2>Example Input/Output</h2>

<p><strong>Input</strong>:</p>
<pre><code>Enter your Name: John Doe
Enter your Phone No: 1234567890
Enter your Mail: johndoe@example.com
Enter product ID: 101
Enter product Quantity: 10
</code></pre>

<p><strong>Output</strong>:</p>
<pre><code>-----------------------------
Product Name     :  Apple
Price            :  10
Quantity         :  10
-----------------------------
Billing Amount   :  100
-----------------------------
Inventory Updated
</code></pre>
<p>After a few transactions, your <code>Sales.txt</code> file might look like this:</p>

<pre><code>John Doe,1234567890,johndoe@example.com,Apple,101,10,100,Fri Sep 13 12:35:29 2024
Jane Smith,0987654321,janesmith@example.com,Banana,102,5,25,Fri Sep 13 13:20:15 2024
</code></pre>

<p>The format for each entry is:</p>
<pre><code>UserName,Phone,Email,ProductName,ProductID,QuantityPurchased,BillingAmount,TimeOfPurchase
</code></pre>
<h2>Contributing</h2>

<p>Contributions are welcome! Please fork this repository and create a pull request with your changes. If you find any issues, feel free to report them.</p>

<h2>License</h2>

<p>This project is open-source and available under the MIT License.</p>

<h2>Contact</h2>

<p>For any inquiries, feel free to reach out to Arman Ahmed via GitHub: <a href="https://github.com/ArmanAhmed00">ArmanAhmed00</a>.</p>
