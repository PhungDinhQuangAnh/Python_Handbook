# 🐍 Python Handbook | Sổ tay Python

- This is a **personal Python handbook** created during my **self-study journey**. It covers **core Python concepts** and includes **practice problems with solutions**.  
- Đây là **sổ tay Python cá nhân** được tôi tổng hợp trong quá trình **tự học**. Bao gồm các **kiến thức cốt lõi** và **bài tập có lời giải**.

---

## ✍️ Topics Covered | Các chủ đề 

- **Basics** — Nhập/xuất, biến, kiểu dữ liệu, toán tử
- **Control Flow** — Điều kiện, vòng lặp
- **Data Structures** — List, Tuple, Set, Dict, String
- **Functions & OOP** — Hàm, đệ quy, lớp, kế thừa
- **Files & Errors** — Đọc/ghi tệp, xử lý lỗi
- **Practice** — Bài tập, tư duy logic, dự án nhỏ

---

## 🔗 View Handbook Online | Xem sổ tay trực tuyến

| Language | Colab | GitHub |
|----------|-------|--------|
| 🇺🇸 English    | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/PhungDinhQuangAnh/Python_Handbook/blob/main/python_handbook_en.ipynb) | [![View on GitHub](https://img.shields.io/badge/View%20on-GitHub-blue?logo=github)](./python_handbook_en.ipynb) |
| 🇻🇳 Vietnamese | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/PhungDinhQuangAnh/Python_Handbook/blob/main/python_handbook_vi.ipynb) | [![View on GitHub](https://img.shields.io/badge/Xem%20trên-GitHub-blue?logo=github)](./python_handbook_vi.ipynb) |

---

## 💬 Final Words | Lời kết

**_Happy learning_**, and **_keep the passion for coding alive! ❤️_**  
**_Chúc bạn học tốt_** và **_luôn giữ đam mê với lập trình! ❤️_**

---

## 📚 Beyond Python: AI Landscape | Vượt khỏi Python: Toàn cảnh AI

<pre>
ARTIFICIAL INTELLIGENCE (AI)
│
├── <b>AI TYPES BY CAPABILITY</b> ──► Phân loại AI theo khả năng
│    ├── Narrow AI ──► AI yếu, chỉ làm một việc cụ thể (Weak AI for narrow tasks)
│    ├── General AI ──► AI tổng quát, trí tuệ như con người (Human-like general intelligence)
│    └── Super AI ──► Siêu trí tuệ, vượt xa con người (Superintelligence beyond humans)
│
├── <b>AI TYPES BY FUNCTION</b> ──► Phân loại AI theo chức năng
│    ├── AI Automation ──► Tự động hóa bằng AI (Automating repetitive tasks using AI)
│    ├── AI Agent ──► Tác nhân thông minh (Perceive–decide–act loop)
│    ├── Generative AI ──► Sinh nội dung mới (Generating text, images, audio...)
│    ├── Conversational AI ──► Giao tiếp bằng ngôn ngữ tự nhiên (Natural language interaction)
│    └── Autonomous AI ──► AI tự hành động mà không cần can thiệp (Fully autonomous behavior)
│
├── <b>MACHINE LEARNING (ML)</b> ──► Máy học từ dữ liệu (Machines learn from data)
│    │
│    ├── <b>Supervised Learning</b> ──► Dữ liệu có nhãn (Labeled data)
│    │   ├── <b>Thuật toán truyền thống (Traditional algorithms)</b>:
│    │   │   ├── Logistic Regression, Decision Tree, Random Forest, Gradient Boosting,
│    │   │   └── Linear Regression, Ridge Regression / Lasso Regression, KNN Regression ...
│    │   │
│    │   └── <b>Deep Learning (DL)</b>
│    │       ├── <i>MLP</i>
│    │       ├── <i>CNN</i> ──► Xử lý ảnh, video (Image, video processing)
│    │       ├── <i>RNN</i> ──► Dữ liệu tuần tự (Sequential data)
│    │       │   ├── LSTM 
│    │       │   └── GRU
│    │       ├── <i>Transformer</i> ──► Xử lý đa dạng dữ liệu (Processing diverse types of data)
│    │       │   ├── BERT  
│    │       │   └── GPT  
│    │       └── <i>GNN</i> ──► Xử lý dữ liệu đồ thị (Graph data processing)
│    │           ...
│    │ 
│    ├── <b>Unsupervised Learning</b> ──► Dữ liệu không nhãn (Unlabeled data)
│    │   ├── <b>Thuật toán truyền thống (Traditional algorithms)</b>:
│    │   │   ├── K-Means, DBSCAN, Hierarchical Clustering,
│    │   │   └── PCA, Isolation Forest ...
│    │   │
│    │   └── <b>Deep Learning (DL)</b>
│    │       ├── <i>Autoencoder</i> ──► Nén, tái tạo dữ liệu (Data compression & reconstruction)
│    │       └── <i>GAN</i> ──► Sinh dữ liệu giả (Synthetic data generation) (image, voice, ...)
│    │           ...
│    │
│    ├── <b>Reinforcement Learning</b> ──► Học qua tương tác (Learning through interaction)
│    │   ├── Q-Learning, SARSA, ...
│    │   │
│    │   └── <b>Deep Reinforcement Learning (Deep RL)</b>
│    │       ├── <i>DQN</i> ──► Kết hợp DL + Q-Learning (Combines DL + Q-Learning)
│    │       ├── <i>PPO, A3C</i> ──► Tối ưu chính sách (Policy optimization)
│    │       └── <i>AlphaGo, AlphaZero</i> ──► Ứng dụng thực tế (Real-world applications)
│    │
│    └── <b>Self-Supervised Learning</b> ──► Tự học từ dữ liệu mà không cần nhãn thủ công (Learning by generating labels from raw data)
│        └── Mô hình sử dụng (Used in):
│            ├── <i>BERT</i> ──► Dự đoán từ bị che (Masked word prediction)
│            ├── <i>SimCLR, BYOL</i> ──► Tự học đặc trưng hình ảnh (Visual representation learning)
│            └── <i>GPT</i> (phần tiếp theo từ chính dữ liệu) (Next-token prediction)
│        ........
│
└── <b>AI DOMAINS & APPLICATIONS</b> ──► Các lĩnh vực kỹ thuật & ứng dụng thực tế
     ├── Expert Systems ──► Hệ thống quy tắc (Rule-based systems) (if–then logic)
     ├── Reasoning & Planning ──► Suy luận logic, tìm đường, lập kế hoạch (Logical inference, pathfinding, planning)
     ├── Robotics ──► Cảm biến, điều khiển, tương tác môi trường (Sensors, control, environment interaction)
     ├── Computer Vision (CV) ──► Xử lý hình ảnh & video (Image & video analysis)
     └── Natural Language Processing (NLP) ──► Xử lý ngôn ngữ tự nhiên 
         ...
</pre>
