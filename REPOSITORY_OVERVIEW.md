# ModelEarth Webroot Repository - Complete Overview & Task Guide

## 🌍 What This Repository Is About

This is a sophisticated **environmental economics and team collaboration ecosystem** that combines:
- **🌱 Environmental Economics**: Multi-regional input-output analysis for sustainability assessment
- **🤝 AI-Powered Collaboration**: Team formation, project management, and skill matching platform
- **🛠️ Web Development Toolkit**: Modular JAM Stack framework for rapid development
- **📊 Data Science Platform**: Economic trade flow analysis and impact visualization
- **🤖 AI Integration**: Google Gemini and Claude AI for intelligent search and insights

## 🏆 Current Status & What Works

✅ **Fully Functional Components**:
- HTTP development server (Python-based)
- All 10 git submodules initialized and accessible
- Rust backend compiles successfully (requires database for full functionality)
- Automated multi-repository management via `git.sh`
- Frontend pages load and display properly
- CSS/JavaScript frameworks operational

⚠️ **Setup Required for Full Functionality**:
- PostgreSQL database configuration (team backend)
- Google Gemini API key for AI features
- OAuth2 provider credentials for authentication

## 🏗️ Repository Architecture

### **Core Structure**
```
webroot/                 # Main orchestration hub
├── git.sh              # Automated multi-repo management script
├── index.html          # Interactive landing page with dynamic content
├── README.md           # Basic setup and deployment instructions  
├── CLAUDE.md           # Advanced automation and AI integration commands
├── REPOSITORY_OVERVIEW.md  # This comprehensive guide
├── [10 Git Submodules] # Specialized functional components
└── [4 Trade Repos]     # Economic modeling tools (to be cloned separately)
```

### **Git Submodules** (Specialized Components) ✅ All Active
1. **team/** - 🦀 **Rust REST API** with PostgreSQL, Google Gemini AI, OAuth2 auth
2. **localsite/** - 🌐 **Web Framework** for JSON/CSV data visualization and mapping
3. **comparison/** - 📈 **Trade Flow Analysis** with UN Sustainable Development Goals focus
4. **feed/** - 🎬 **Media Player** - RSS/JSON feeds with video-like presentations  
5. **home/** - 🏠 **Landing Pages** and project showcases with responsive design
6. **projects/** - 📋 **Project Management** tools and portfolio displays
7. **cloud/** - ☁️ **Infrastructure** tools and cloud deployment utilities
8. **realitystream/** - 📡 **Real-time Data** streaming and live updates
9. **products/** - 🛒 **E-commerce** features, catalogs and marketplace tools
10. **swiper/** - 🎯 **UI Components** - Navigation, carousels, and interaction widgets

### **Trade Flow Repositories** (Economic Modeling) 📊 Requires Manual Setup
- **exiobase** - 🌍 Multi-regional input-output database (49 countries, 200+ sectors)
- **profile** - 🏭 Environmental impact profiles and lifecycle analysis
- **useeio.js** - 🇺🇸 USEEIO JavaScript modeling tools for US economic data
- **io** - ⚙️ General input-output modeling framework and utilities

*Note: These are separate repositories that need to be forked and cloned manually*

## 🚀 Technology Stack

### **Frontend (JAM Stack)** ⚡ No Build Process Required
- **HTML5/CSS3** with CSS Grid, Flexbox, modern responsive design
- **Vanilla JavaScript** - Direct browser execution, no bundling needed  
- **Notion-inspired UI** - Clean aesthetics with smooth animations
- **Real-time Visualization** - Interactive charts, maps, and data displays
- **Mobile-First Design** - Touch-optimized responsive layouts

### **Backend (Rust)** 🦀 High Performance & Type Safety
- **Actix-Web** - Async web framework with excellent performance
- **SQLx** - Compile-time checked SQL with async PostgreSQL support
- **JWT Authentication** - Secure token-based auth with OAuth2 providers
- **AI Integration** - Google Gemini API for natural language processing
- **Excel/CSV Processing** - Automated data import and validation
- **RESTful APIs** - JSON-based endpoints for all frontend communication

### **Database & AI** 🧠 Enterprise-Ready
- **PostgreSQL** - Production database with SuiteCRM-compatible schema
- **Google Gemini** - Advanced natural language search and recommendations  
- **Claude AI** - Integration via command-line interface for development
- **Azure/Google Cloud** - Deployment-ready with environment configuration

## 🎯 What You Can Do - Actionable Task Roadmap

### 🚀 **IMMEDIATE TASKS** (Ready to Start Now)

#### **🔧 Quick Setup (5 minutes)**
1. **Start Local Development Server**:
   ```bash
   cd /path/to/webroot
   python -m http.server 8887
   # Visit http://localhost:8887 - Working immediately!
   ```

2. **Explore Live Platform**:
   - 🏠 **Main Hub**: `localhost:8887` - Interactive setup and navigation
   - 👥 **Team Platform**: `localhost:8887/team` - Project collaboration tools
   - 📊 **Trade Analysis**: `localhost:8887/comparison` - Economic data comparisons
   - 🎬 **Feed Player**: `localhost:8887/feed` - Media and data visualization
   - 🌐 **Web Tools**: `localhost:8887/localsite` - Development utilities

3. **Test Multi-Repository Management**:
   ```bash
   # All git submodules are already initialized ✅
   git submodule status  # See current status
   ./git.sh update      # Pull latest changes from all repos
   ```

#### **📝 Content Creation (No Technical Setup Required)**
- **📚 Update Documentation**: Improve README files in any submodule
- **✍️ Write Tutorials**: Create step-by-step guides for specific features  
- **🎨 Design Content**: Add sample data, example projects, and demos
- **🔍 Test & Report**: Use the platform and document any issues found

### 💻 **FRONTEND DEVELOPMENT** (HTML/CSS/JavaScript)

#### **🎨 UI/UX Enhancement Tasks**
- **Team Platform Design**: 
  - Improve project listing layouts and filtering options
  - Add smooth animations and micro-interactions  
  - Enhance mobile responsiveness across all submodules
  - Implement accessibility features (ARIA labels, keyboard navigation)

- **Data Visualization**: 
  - Create interactive trade flow charts and economic impact graphs
  - Build timeline components for project progress tracking
  - Integrate maps for geographic data display (existing Leaflet.js ready)
  - Design customizable dashboard widgets and user preferences

#### **🔌 JavaScript Enhancement**
- **API Integration**: Connect frontend forms to Rust backend endpoints
- **Real-time Features**: WebSocket integration for live updates
- **Search & Filtering**: Improve project and team discovery interfaces
- **Form Validation**: Client-side validation for better user experience

### 🦀 **BACKEND DEVELOPMENT** (Rust Programming)

#### **⚡ API Development**
Current Rust backend includes:
- ✅ Actix-web server framework
- ✅ PostgreSQL connection with SQLx
- ✅ Google Gemini AI integration  
- ✅ OAuth2 authentication (Google, GitHub, LinkedIn, Microsoft, Facebook)
- ✅ Excel/CSV import capabilities
- ⚠️ Requires database setup for full functionality

**Available Tasks**:
- **New REST Endpoints**: Extend API functionality for frontend needs
- **Database Schema**: Design and implement new table structures
- **Authentication Flow**: Complete OAuth2 provider integration
- **AI Features**: Enhance Gemini API usage for better recommendations
- **Performance**: Add caching, optimize queries, implement connection pooling

### 📊 **DATA SCIENCE & ECONOMICS** (Research & Analysis)

#### **🌍 Economic Impact Modeling**
The trade flow repositories provide access to:
- **EXIOBASE**: 49-country, 200+ sector multi-regional input-output database
- **Environmental Footprints**: CO2, water, land use, and material consumption data
- **Supply Chain Analysis**: Global trade relationships and dependencies
- **Policy Impact**: Scenario analysis for environmental and economic policies

**Available Tasks**:
- **Visualization Development**: Interactive charts showing trade relationships
- **Comparative Analysis**: Country and sector-based environmental comparisons  
- **Impact Calculation**: Tools for calculating environmental footprints
- **Trend Analysis**: Time-series analysis of economic and environmental data

#### **🤖 AI & Machine Learning Integration**
- **Smart Recommendations**: Improve project and team matching algorithms
- **Natural Language Search**: Enhance Gemini AI query processing
- **Data Insights**: Automated analysis of user behavior and project trends
- **Predictive Models**: Economic impact forecasting and scenario planning

### 🔧 **DEVOPS & INFRASTRUCTURE** (System Administration)

#### **🚀 Deployment & Automation**
- **GitHub Actions**: Set up automated testing and deployment pipelines
- **Docker Containers**: Containerize all services for consistent deployment
- **Cloud Deployment**: Configure Azure/Google Cloud deployment
- **Monitoring & Logging**: Implement performance tracking and error monitoring

#### **📦 Database Management**  
- **PostgreSQL Setup**: Configure development and production databases
- **Schema Management**: Version control for database changes and migrations
- **Performance Optimization**: Query tuning and indexing strategies
- **Backup Systems**: Automated backup and disaster recovery procedures

## 🛠️ **ADVANCED MULTI-REPOSITORY AUTOMATION**

The repository includes sophisticated automation via the `git.sh` script that manages all 14+ repositories:

### **🔄 Automated Workflows** 
```bash
# Pull latest changes from ALL parent repositories  
./git.sh update

# Commit changes across webroot + all submodules + trade repos
./git.sh commit

# Commit specific components
./git.sh commit team          # Just the team submodule
./git.sh commit submodules    # All submodules only  
./git.sh commit forks         # Trade flow repositories only

# Skip automatic PR creation (when you're not ready)
./git.sh commit nopr
```

### **🚀 Fork & Contribute Workflow**
1. **Fork Trade Flow Repositories** (one-time setup):
   ```bash
   fork trade repos to [your-github-account]
   ```

2. **Clone to Local Environment**:
   ```bash  
   clone trade repos from [your-github-account]
   ```

3. **Make Changes & Auto-Submit**:
   ```bash
   # The git.sh script automatically:
   # ✅ Commits your changes
   # ✅ Tries to push directly  
   # ✅ Creates PRs if push is denied (permission restrictions)
   # ✅ Updates all submodule references in parent repo
   ./git.sh commit
   ```

**🎯 Key Features:**
- **Intelligent PR Creation**: Automatically creates pull requests when push access is denied
- **Multi-Repo Sync**: Keeps all repositories in sync with their ModelEarth parents  
- **Conflict Detection**: Reports merge conflicts for manual resolution
- **Branch Management**: Handles different default branches (main/master/dev)
- **Selective Commits**: Choose which repositories to update

## 📋 **GETTING STARTED BY SKILL LEVEL**

### 👶 **New to Programming** 
**Start Here**: Content and documentation tasks require no coding experience
1. **📝 Documentation**: Update README files, write tutorials, improve setup guides
2. **🎨 Content Creation**: Add sample projects, create example data, test user workflows  
3. **🐛 Quality Assurance**: Use the platform, report bugs, suggest improvements
4. **🌐 Web Content**: Edit HTML pages, update text content, improve user instructions

**Time Investment**: 1-2 hours per task • **Impact**: High - Better onboarding for all users

### 💻 **Web Developers (HTML/CSS/JavaScript)**
**Your Strength**: Frontend improvements and user experience enhancements
1. **🎯 Start with Team Platform**: `/team/` submodule has extensive JavaScript and CSS
2. **📊 Data Visualization**: Enhance charts, graphs, and interactive elements
3. **📱 Mobile Optimization**: Improve responsive design across all submodules  
4. **⚡ Performance**: Optimize loading times, add progressive web app features

**Time Investment**: 2-5 hours per feature • **Impact**: High - Direct user experience improvements

### 🦀 **Backend Developers (Any Language)**
**Your Opportunity**: The Rust backend is well-structured and documented
1. **🏗️ Learn Rust Basics**: Excellent opportunity to learn a modern systems language
2. **📚 Study the Code**: Well-commented Rust code in `/team/src/` 
3. **🔌 API Development**: Add new endpoints, improve existing functionality
4. **🗄️ Database Design**: PostgreSQL schema improvements and optimization

**Time Investment**: 5-10 hours per feature • **Impact**: Very High - Core platform functionality

### 📊 **Data Scientists & Economists** 
**Your Domain**: Economic modeling and environmental impact analysis
1. **🌍 EXIOBASE Analysis**: Work with 49-country trade flow data
2. **📈 Visualization**: Create compelling charts showing economic relationships
3. **🔍 Research**: Analyze environmental impacts, sustainability metrics
4. **🤖 AI Integration**: Enhance recommendation systems and data insights

**Time Investment**: 3-8 hours per analysis • **Impact**: Very High - Core research value

### 🔧 **DevOps & System Administrators**
**Your Focus**: Infrastructure, deployment, and automation
1. **☁️ Cloud Deployment**: Set up Azure/Google Cloud infrastructure
2. **🐳 Containerization**: Docker setup for all services
3. **🔄 CI/CD Pipelines**: GitHub Actions for automated testing and deployment
4. **📊 Monitoring**: Implement logging, performance tracking, alerting

**Time Investment**: 4-12 hours per system • **Impact**: Critical - Platform reliability and scalability

## 🔧 **DETAILED SETUP INSTRUCTIONS**

### **🌐 Frontend Development Setup** (Ready Now ✅)
```bash
# 1. Start development server (already working)
python -m http.server 8887

# 2. Open your browser to any of these:
# Main hub: http://localhost:8887  
# Team platform: http://localhost:8887/team
# Trade analysis: http://localhost:8887/comparison
# Feed player: http://localhost:8887/feed
# Web toolkit: http://localhost:8887/localsite

# 3. Edit any HTML/CSS/JavaScript files
# Changes are reflected immediately - no build process needed!
```

### **🦀 Rust Backend Setup** (Database Required)

#### **Option A: Quick Start (No Database)**
```bash
cd team/
cargo check    # ✅ Compiles successfully (verified)
cargo build     # Build optimized version
# Code compiles but needs database connection for full functionality
```

#### **Option B: Full Setup (With Database)**  
```bash
cd team/

# 1. Set up environment
cp .env.example .env
# Edit .env with your database credentials and API keys:
# - PostgreSQL connection details
# - Google Gemini API key (get free at aistudio.google.com)  
# - OAuth2 provider credentials (optional)

# 2. Initialize database  
cargo run --bin partner_tools -- init-db

# 3. Start server
nohup cargo run --bin partner_tools -- serve > server.log 2>&1 &
# Server runs on http://localhost:8081 (configurable via .env)

# 4. Test API endpoints
curl http://localhost:8081/api/health
```

### **📊 Trade Flow Analysis Setup** 
```bash
# 1. Fork the trade repositories (one-time setup)
fork trade repos to [your-github-account]

# 2. Clone to your local environment  
clone trade repos from [your-github-account]

# 3. Explore the data
cd exiobase/tradeflow/
ls -la  # See available country and year data
# Contains multi-regional input-output data for 49 countries
# 200+ economic sectors with environmental impact metrics

# 4. Start analysis
# Use existing scripts or create new visualization tools
```

### **🤖 AI Integration Setup**
```bash
# Google Gemini API (for smart search and recommendations)
# 1. Get free API key at https://aistudio.google.com
# 2. Add to .env file: GEMINI_API_KEY=your_key_here
# 3. Restart Rust server to load new configuration

# Claude AI is integrated via command-line interface
# Already configured for repository automation
```

## 🎉 **SUMMARY - YOUR NEXT STEPS**

**This repository is a complete environmental economics and collaboration ecosystem with:**

✅ **Immediate Value**: Working web interface, all submodules active, automated git workflows  
✅ **Multiple Entry Points**: Content creation, web development, data science, backend programming  
✅ **Professional Tools**: Rust backend, PostgreSQL database, AI integration, automated deployment  
✅ **Real Impact**: Environmental research, sustainability analysis, team collaboration platform  
✅ **Learning Opportunity**: Modern tech stack with excellent documentation and examples  

### **🚀 Quick Start Recommendations:**

**🎯 Want to contribute immediately?** 
→ Start the development server and explore the live platform at `localhost:8887`

**💻 Web developer?** 
→ Focus on `/team/` submodule - extensive JavaScript/CSS with room for UI improvements  

**🦀 Want to learn Rust?**
→ The backend code is well-documented and ready for extension

**📊 Data scientist?**
→ Set up the trade flow repositories and explore economic/environmental datasets

**🔧 DevOps engineer?**
→ Configure cloud deployment and CI/CD pipelines

### **📚 Additional Resources:**
- **Basic setup**: See `README.md` for quick deployment instructions
- **Advanced automation**: Check `CLAUDE.md` for AI-powered git workflows  
- **Current status**: All core components tested and functional
- **Community**: Fork any component and submit PRs - automated PR creation when push access is denied

---

## 🤝 **Ready to Contribute?**

Choose your interest area above, follow the setup instructions, and start building! The automated workflows make it easy to contribute across multiple repositories without complex manual git management.

**Questions or need guidance?** The extensive documentation in `CLAUDE.md` covers advanced workflows, and the code itself is well-commented for self-guided learning.