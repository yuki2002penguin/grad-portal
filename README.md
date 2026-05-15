https://grad-portal-psi.vercel.app/
# GradPortal

大学院生のための統合進捗管理ダッシュボード。授業、研究、就活、生活の全タスクをまとめ管理。

既存のタスク管理ツールは機能が分散しており、大学院生特有の「授業・研究・就職活動」が並行する過酷な状況に最適化されていないと感じていました。そこで、これら全ての進捗を一つのダッシュボードで完結に把握できるツールを自ら開発しました。


### 主な機能
- **統合カレンダー & タスク**: 授業・研究・就活・生活のすべての DDL を自動集約。
- **授業管理**: 12限対応の時間割表と課題(Assignment)の追跡。
- **研究ログ**: マイルストーン管理と、アイデアを逃さない「便利付箋」メモ機能。
- **就活ステータス管理**: 企業ごとの選考フェーズ管理、面接メモ、および選考タスクの DDL 通知。
- **生活予定**: プライベートのイベントや旅行などの期間予定も管理可能。
- **ダークモード UI**: 長時間の作業でも疲れにくい、VS Code 風の洗練されたデザイン。

### 技術スタック
- フロントエンド：HTML5, CSS3, JavaScript (Vanilla JS)。
- データプライバシー：データはブラウザの LocalStorage にのみ保存され、サーバーへは送信されません。
- デプロイ：Vercel または GitHub Pages に対応。

### 使用方法
1. デプロイされた URL にアクセスするだけで使用を開始できます。
2. ログインや会員登録は不要で、データはブラウザに自動保存されます。（※アカウント登録機能やスマートフォンとの連携機能を実装予定）
3. データのバックアップが必要な場合は、ブラウザのデベロッパーツールから LocalStorage をエクスポートしてください。


# GradPortal

An integrated progress management dashboard for graduate students. Manage all tasks for coursework, research, job hunting, and daily life in one place.

### Introduction
I felt that existing task management tools were too fragmented and not optimized for the demanding lifestyle of graduate students, where coursework, research, and job hunting must be managed simultaneously. To solve this, I developed this tool to provide a clear, all-in-one overview of all progress in a single dashboard.

### Key Features
- **Integrated Calendar & Tasks**: Automatically aggregates all deadlines (DDL) from coursework, research, job hunting, and daily life.
- **Course Management**: Timetable support for up to 12 periods and assignment tracking.
- **Research Log**: Milestone management and a "Sticky Note" feature to capture research ideas instantly.
- **Job Hunting Tracker**: Manage selection phases, interview notes, and specific task deadlines for each company.
- **Life Schedule**: Manage private events, trips, and multi-day schedules.
- **Dark Mode UI**: A clean, VS Code-inspired design to reduce eye strain during long working hours.

### Tech Stack
- **Frontend**: HTML5, CSS3, JavaScript (Vanilla JS)
- **Data Privacy**: Data is stored exclusively in the browser's LocalStorage; no data is sent to any server.
- **Deployment**: Compatible with Vercel or GitHub Pages.

### How to Use
1. Simply access the deployed URL to start using the tool.
2. No registration or login is required. Data is automatically saved in your browser. (*Future updates will include user registration and mobile synchronization.*)
3. To back up your data, please export your LocalStorage via the browser's developer tools.
