# Subscription Manager

一個使用 Next.js (React) + FastAPI 的專案範例。

## 安裝步驟（建議分兩個終端機視窗執行）

### 1. 下載專案及安裝依賴

```bash
git clone https://github.com/你的帳號/subscription-manager.git
cd subscription-manager

# 安裝前端依賴
cd frontend
npm install
# 或 yarn

# 安裝後端依賴
cd ../backend
python -m venv venv

# 啟動虛擬環境
# Mac/Linux:
source venv/bin/activate
# Windows:
venv\Scripts\activate.bat

pip install -r requirements.txt


### 啟動前端
cd subscription-manager/frontend
npm run dev
# 或 yarn dev


###啟動後端
cd subscription-manager/backend

# 啟動虛擬環境（如果還沒啟動）
# Mac/Linux:
source venv/bin/activate
# Windows:
venv\Scripts\activate.bat

uvicorn main:app --reload
