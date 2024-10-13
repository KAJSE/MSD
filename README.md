# MSD
mkdir fruit-delivery-platform
cd fruit-delivery-platform
git init
fruit-delivery-platform/
│
├── backend/               # 后端代码
│   ├── app.js             # 主服务器文件
│   ├── routes/            # 路由
│   │   ├── auth.js        # 用户认证路由
│   │   ├── orders.js      # 订单路由
│   └── models/            # 数据库模型
│       ├── User.js        # 用户模型
│       └── Order.js       # 订单模型
│
├── frontend/              # 前端代码
│   ├── public/
│   ├── src/
│   │   ├── components/    # React 组件
│   │   ├── App.js         # 应用主文件
│   └── index.js           # React 入口
│
├── .env                   # 环境变量
├── package.json           # 项目依赖
└── README.md              # 项目文档
