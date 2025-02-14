# 📝 Ruby Memo App (CLI)
A simple command-line memo application written in Ruby. Users can create, edit, delete, and view memos stored as CSV files.

## 🚀 Features
- Create new memos with a title and content.
- Edit existing memos by overwriting or appending content.
- Delete memos with confirmation.
- List all stored memos.
- User-friendly error handling and input validation.

## 🛠️ Installation & Usage
### **1️⃣ Clone this repository**
```sh
git clone https://github.com/X0377/Ruby-Memo-App-CUI.git
cd Ruby-Memo-App-CUI
```

### **2️⃣ Run the memo application**
```sh
ruby memo.rb
```

## 📖 How to Use
Upon running `memo.rb`, users can:
1. **Create a new memo** by entering a title and content.
2. **Edit an existing memo** by overwriting or appending text.
3. **Delete a memo** with a confirmation prompt.
4. **List all stored memos** in the current directory.

### **📌 Menu Options**
| Option | Action |
|--------|--------|
| `1` | Create a new memo |
| `2` | Edit an existing memo |
| `3` | Delete a memo |
| `4` | List all memos |

## 🏗️ Implementation Details
- Uses **CSV** for data storage.
- Handles empty inputs and incorrect selections gracefully.
- Prevents saving empty memos and offers re-entry prompts.

## 📜 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
