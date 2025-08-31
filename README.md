# Pichai-
myapp/
├── server/                  # Backend Node.js + Express
│   ├── models/             # User, Product, Content, Order, Notification, Message
│   ├── routes/             # auth, cms, shop, orders, chat, admin
│   ├── services/           # payments, recommend, moderation
│   ├── sockets/            # realtime แจ้งเตือน + แชท
│   ├── middlewares/        # auth, roles, csrf, error
│   └── server.js           # Entry point
├── client/                 # Frontend React + Vite
│   ├── src/
│   │   ├── components/     # TopBar, SideNav, NotificationBell, ChatWidget
│   │   ├── features/       # Home, Shop, CMS, Admin, Account
│   │   ├── store/          # Zustand: useAuth, useCart, useNotify
│   │   ├── layouts/        # MainLayout
│   │   ├── routes.jsx      # Routing
│   │   └── App.js
│   └── index.html          # Entry HTML
└── README.md
