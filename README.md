# Task Sample Project

Project management repository for a fixed-scope client project with defined deliverables.

## 🎯 Project Overview

**Client**: Client Corp  
**Project Type**: Fixed-scope deliverable project  
**Timeline**: August 1 - September 15, 2025 (6 weeks)  
**Budget**: $120,000  
**Team Size**: 12 people  

## 📋 Project Scope

### Deliverables
1. **Design Phase**
   - Complete visual design (25 deliverables)
   - Mobile-responsive designs
   - Interactive prototype
   - Design system documentation

2. **Development Phase**
   - Frontend implementation
   - Backend integration
   - Third-party integrations
   - Performance optimization

3. **Additional Services**
   - Quality assurance
   - Documentation
   - Training materials
   - 30-day post-launch support

## 📁 Repository Structure

### Meta Repository (This Repo)
- **Purpose**: Project coordination, deliverable tracking, client communication
- **Contains**: Requirements, timelines, deliverable checklists
- **Issue Types**: Individual deliverable tasks

### Child Repositories
1. **[task-sample-child-1](../task-sample-child-1)**
   - Design files, assets, and prototypes
   - Team: 4 designers

2. **[task-sample-child-2](../task-sample-child-2)**
   - Development code and implementation
   - Team: 6 developers

## 🔄 Project Workflow

```mermaid
graph LR
    A[Client Requirements] --> B[Create Deliverable Tasks]
    B --> C{Task Type}
    C -->|Design| D[Transfer to Child 1]
    C -->|Development| E[Transfer to Child 2]
    D --> F[Design Work]
    E --> G[Development Work]
    F --> H[Internal Review]
    G --> H
    H --> I[Client Review]
    I --> J{Approved?}
    J -->|Yes| K[Mark Delivered]
    J -->|No| L[Revision Tasks]
    L --> C