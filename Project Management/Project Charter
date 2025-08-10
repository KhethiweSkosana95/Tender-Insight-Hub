# PROJECT CHARTER
## Tender Insight Hub - Cloud-Native SaaS Platform

**Project Code:** NSED742-TIH  
**Project Manager:** Sinethemba Mthembu
**Document Version:** 1.0  
**Date:** August 2025  
**Course:** Software Engineering & Design (NSED742)  
**Instructor:** Dr Silas Verkijika  

---

## 🎯 PROJECT OVERVIEW

### Project Purpose
Develop a production-grade, cloud-native SaaS platform that empowers South African Small and Medium Enterprises (SMEs) to effectively navigate and participate in public procurement opportunities through AI-assisted analysis and collaborative decision-making tools.

### Project Vision
To become the leading digital solution for SME procurement readiness in South Africa, simplifying complex tender processes and democratizing access to government contracting opportunities.

### Project Mission  
Create an intelligent, user-friendly platform that transforms how SMEs discover, analyze, and pursue public tenders by leveraging artificial intelligence, collaborative workflows, and comprehensive business intelligence.

---

## 📋 PROJECT OBJECTIVES

### Primary Objectives
1. **Develop Core SaaS Platform**
   - Build scalable multi-tenant architecture supporting 3 pricing tiers
   - Implement FastAPI backend with PostgreSQL, MongoDB, and Redis integration
   - Create responsive frontend with modern web technologies

2. **Implement AI-Powered Features**
   - Deploy document summarization using open-source NLP models
   - Build intelligent readiness scoring algorithm
   - Enable automated tender-to-company matching

3. **Enable Collaborative Workflows**
   - Support team-based workspaces with role management
   - Implement real-time collaboration features
   - Provide audit trails and activity tracking

4. **Deliver Public API Infrastructure**
   - Create RESTful APIs for third-party integration
   - Implement comprehensive API documentation via Swagger
   - Enable civic tech ecosystem integration

### Success Criteria
- ✅ Platform supports all three SaaS tiers (Free, Basic, Pro)
- ✅ AI summarization achieves 120-word summaries with 85%+ relevance
- ✅ Search functionality returns results within 2 seconds
- ✅ Multi-tenant isolation maintains 100% data security
- ✅ Public APIs achieve 99.5% uptime during testing
- ✅ Platform handles concurrent team collaboration without conflicts

---

## 🎯 SCOPE DEFINITION

### In Scope
**Core Features:**
- Keyword search with advanced filtering (province, deadline, buyer, budget)
- Company profile management with certification tracking
- AI-powered tender document summarization
- Readiness scoring and suitability analysis
- Team workspace with tender tracking and status management
- Multi-tier SaaS subscription management
- Public API endpoints for external integration
- Authentication and authorization system
- Real-time collaboration tools

**Technical Components:**
- FastAPI backend architecture
- PostgreSQL for structured data
- MongoDB for document storage
- Redis for caching and session management
- JWT-based authentication
- GitHub Actions CI/CD pipeline
- Docker containerization
- Swagger API documentation

**Data Sources:**
- OCDS eTenders API integration
- PDF/ZIP document processing
- Company profile data management

### Out of Scope
- Payment processing integration (simulated only)
- Mobile native applications
- Advanced analytics beyond basic reporting
- Integration with private tender platforms
- Multi-language support beyond English
- Advanced AI features beyond summarization and scoring

### Assumptions
- OCDS eTenders API remains accessible and stable
- Team members have access to development environments
- Open-source AI models provide sufficient accuracy
- Cloud hosting resources are available
- GitHub repository access for all team members

### Constraints
- **Technology:** Must use FastAPI, PostgreSQL, MongoDB, Redis
- **Timeline:** Semester project duration (16 weeks)
- **Resources:** 5-6 student team members
- **Budget:** Free/open-source tools only
- **AI Models:** Open-source or free tier models only

---

## 👥 STAKEHOLDERS

### Primary Stakeholders
| Stakeholder | Role | Responsibilities | Influence |
|-------------|------|------------------|-----------|
| **Dr Silas Verkijika** | Course Instructor | Project oversight, evaluation, guidance | High |
| **Development Team** | Project Executors | Design, development, testing, documentation | High |
| **Team Lead (Rotating)** | Project Leadership | Sprint management, decision-making, reporting | High |

### Secondary Stakeholders
| Stakeholder | Interest | Engagement Level |
|-------------|----------|------------------|
| **SME Business Owners** | End user requirements | Medium |
| **Government Procurement** | Data source reliability | Low |
| **Civic Tech Community** | API integration potential | Medium |

---

## 🚀 PROJECT DELIVERABLES

### Technical Deliverables
1. **Backend System**
   - FastAPI application with complete REST API
   - Database schemas and data models
   - Authentication and authorization system
   - Background job processing (Celery)

2. **Frontend Application**
   - Responsive web interface
   - User dashboard and workspace
   - Admin panel for team management
   - API documentation interface

3. **Database Implementation**
   - PostgreSQL schema with sample data
   - MongoDB collections with indexing
   - Redis configuration for caching

4. **AI Integration**
   - Document processing pipeline
   - Summarization service
   - Readiness scoring algorithm

5. **Infrastructure**
   - Docker configuration files
   - CI/CD pipeline setup
   - Deployment documentation

### Documentation Deliverables
1. **Technical Documentation**
   - API documentation (Swagger)
   - Database schema documentation
   - Architecture decision records
   - Deployment and setup guides

2. **Project Management**
   - Requirements specification
   - Project timeline and milestones
   - Risk register and mitigation plans
   - Team roles and responsibilities

3. **Individual Reports**
   - Team Lead reports (one per member)
   - Individual contribution documentation
   - Reflection papers on leadership experience

---

## 📅 HIGH-LEVEL TIMELINE

| Phase | Duration | Key Milestones |
|-------|----------|----------------|
| **Phase 1: Planning & Setup** | Weeks 1-2 | Requirements finalization, team setup, repository creation |
| **Phase 2: Foundation** | Weeks 3-6 | Database design, authentication, basic API structure |
| **Phase 3: Core Features** | Weeks 7-10 | Search functionality, AI integration, workspace features |
| **Phase 4: Advanced Features** | Weeks 11-13 | Collaboration tools, public APIs, SaaS tiers |
| **Phase 5: Integration & Testing** | Weeks 14-15 | End-to-end testing, performance optimization, bug fixes |
| **Phase 6: Deployment & Documentation** | Week 16 | Final deployment, documentation completion, presentations |

---

## 💰 BUDGET & RESOURCES

### Human Resources
- **Team Size:** 5-6 students
- **Total Effort:** Approximately 480-576 person-hours (16 weeks × 6-7 hours/week/person)
- **Skill Requirements:** Python, FastAPI, databases, frontend development, AI/ML

### Technology Resources
- **Development Tools:** Free (VS Code, GitHub, Docker)
- **Hosting:** Cloud free tiers (Heroku, Railway, or similar)
- **Databases:** Free PostgreSQL, MongoDB, Redis instances
- **AI Models:** Open-source models (HuggingFace)

### Infrastructure Costs
- **Estimated Total:** $0 (utilizing free tiers and open-source tools)

---

## ⚠️ RISKS & MITIGATION

### High-Priority Risks
1. **Team Member Availability**
   - *Risk:* Schedule conflicts affecting delivery
   - *Mitigation:* Flexible role rotation, clear communication protocols

2. **Technical Integration Complexity**
   - *Risk:* Difficulty integrating multiple databases and AI components
   - *Mitigation:* Early prototyping, modular architecture design

3. **API Data Reliability**
   - *Risk:* OCDS eTenders API instability
   - *Mitigation:* Mock data preparation, robust error handling

### Medium-Priority Risks
1. **AI Model Performance**
   - *Risk:* Summarization quality below expectations
   - *Mitigation:* Multiple model evaluation, fallback options

2. **Scope Creep**
   - *Risk:* Feature expansion beyond timeline
   - *Mitigation:* Regular scope reviews, change control process

---

## ✅ SUCCESS METRICS

### Functional Metrics
- All core features implemented and tested
- Support for 3 SaaS tiers with proper restrictions
- AI summarization generates coherent 120-word summaries
- Search returns relevant results within performance targets
- Multi-tenant data isolation verified

### Technical Metrics
- 90%+ test coverage for backend code
- API response times under 2 seconds
- Database queries optimized with proper indexing
- CI/CD pipeline successfully deploys code
- Documentation completeness score: 95%

### Project Management Metrics
- On-time delivery of milestones
- Team satisfaction score: 8/10 or higher
- Individual leadership reports completed
- Git commit frequency and code review participation

---

## 📝 APPROVAL

### Project Charter Approval
This project charter defines the scope, objectives, and approach for the Tender Insight Hub development project. Approval indicates agreement with the project direction and commitment to resource allocation.

**Team Lead Approval:** [Signature] ____S.Mthembu___________ Date: ___01 Aug 2025______

**Course Instructor Approval:** [Signature] _________________ Date: _________

---

**Document Control:**
- **Created By:** Sinethemba Mthembu
- **Review Date:** to be confirmed 
- **Next Review:** [to be Confirmed + 2 weeks]
- **Distribution:** Team Members [ Ashwill Herman,Koketso Kgogo,Khethiwe Skosana,Onthatile Kilelo,Sinethemba Mthembu ], Course  Lecturer [Slias Verkijika]
