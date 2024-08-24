# Git Hooks Setup

## How to Use
Follow these steps to use these Git hooks in your project:
## 1. Clone the Repository
Clone this repository to access the Git hooks:
```bash
git clone https://github.com/DorianSanders/Githooks.git
cd Githooks
```
## 2. Move Hooks to Your Project's Git Directory
```bash
mv pre-commit /path/to/your/project/.git/hooks/
mv pre-push /path/to/your/project/.git/hooks/
```
## 3. Make Hooks Executable
```bash
chmod +x /path/to/your/project/.git/hooks/pre-commit
chmod +x /path/to/your/project/.git/hooks/pre-push
```
