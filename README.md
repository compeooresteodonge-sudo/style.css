/* General page styling */
body {
    font-family: Arial, sans-serif;
    margin: 20px;
    background-color: #f4f4f4;
    color: #333;
}

main {
    max-width: 700px;
    margin: 0 auto;
}

header {
    text-align: center;
    background-color: #333;
    color: white;
    padding: 15px;
    border-radius: 8px 8px 0 0;
}

section {
    margin: 20px 0;
    padding: 15px;
    border: 1px solid #ccc;
    background-color: white;
    border-radius: 8px;
}

#add-expense {
    background-color: #e6f7ff;
}

#your-expenses {
    background-color: #fffbe6;
}

label {
    display: block;
    margin-top: 10px;
    font-weight: bold;
}

input {
    width: 100%;
    padding: 10px;
    margin-top: 5px;
    box-sizing: border-box;
    border: 1px solid #b9b9b9;
    border-radius: 4px;
}

button {
    margin-top: 15px;
    padding: 10px 16px;
    background-color: #2d8cff;
    color: white;
    border: none;
    border-radius: 6px;
    cursor: pointer;
    font-size: 1rem;
}

button:hover {
    background-color: #1e72d9;
}

#expenses-list {
    list-style: none;
    padding: 0;
    margin: 0;
}

.expense-item,
.empty {
    display: flex;
    justify-content: space-between;
    align-items: center;
    gap: 12px;
    padding: 12px 0;
    border-bottom: 1px solid #e7d8a5;
}

.expense-item div {
    display: flex;
    flex-direction: column;
}

.expense-actions {
    display: flex;
    align-items: center;
    gap: 12px;
}

.delete-btn {
    margin-top: 0;
    padding: 6px 10px;
    background-color: #d9534f;
}

.delete-btn:hover {
    background-color: #b52e2a;
}

#total-expenses {
    margin-top: 15px;
    font-weight: bold;
    font-size: 1.05rem;
}

footer {
    text-align: center;
    margin-top: 30px;
    color: #555;
}
