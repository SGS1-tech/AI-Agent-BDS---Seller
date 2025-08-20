# AI-Agent-BDS---Seller
AI agent for Owner/Seller in Real Estate platform
/ai-agent-app (GitHub repo)
├── pages/
│   └── index.tsx         # Form nhập thông tin + render kết quả AI
├── components/
│   ├── InputForm.tsx     # Nhập thông tin BĐS
│   └── ResultCard.tsx    # Hiển thị gợi ý AI
├── styles/
│   └── globals.css       # Dùng Tailwind
├── utils/
│   └── callDeepseek.ts   # Gửi prompt đến Deepseek API
├── .env.local            # Lưu API key (không public)
├── vercel.json           # Cấu hình deployment
└── README.md
