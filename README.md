# VectorShift: Frontend Technical Assessment

## Overview

This project is a technical assessment implementation that recreates core functionalities of VectorShift's main application. The focus was on building a node-based workflow builder with features like node abstraction, dynamic styling, and backend integration for pipeline validation. The implementation showcases modern web development practices and attention to user experience.

**Frontend:** [Live Site URL](https://vector-shift-project-fe.vercel.app/)
**Backend:** [Live URL](https://vector-shift-project-be.vercel.app/)

**Code Repo:** [Repository URL](https://github.com/drcount-root/VectorShift_Project)

## Demo Video

[Watch the Walkthrough](https://www.loom.com/share/ef12121e21bd49219c661b87a76181d0?sid=7d0892c8-8504-41e9-82ec-6141f30c9542)

## Key Features

- **Node Abstraction**: Implemented a flexible node system supporting various node types (Inputs, Outputs, LLMs, Text)
- **Dynamic Text Node**: Created responsive text nodes with variable parsing and dynamic handle creation
- **Interactive Canvas**: Built using ReactFlow for smooth node-based workflow creation
- **Backend Integration**: FastAPI backend for pipeline validation and DAG verification
- **Modern UI**: Styled using Tailwind CSS and shadcn/ui components
- **Pipeline Validation**: Real-time feedback on pipeline structure and validity

## Technologies Used

- **Frontend Framework**: React.js
- **Workflow Builder**: ReactFlow
- **Styling**: 
  - Tailwind CSS for utility-first styling
  - shadcn/ui for component library
- **Backend**: FastAPI for Python backend services
- **Type Safety**: TypeScript for enhanced development
- **State Management**: React Context API
- **Deployment**: Vercel for frontend hosting

## Implementation Details

### 1. Node Abstraction
- Created a base node abstraction for common functionality
- Implemented specialized node types (Input, Output, LLM, Text)
- Added five custom nodes demonstrating abstraction flexibility

### 2. Text Node Features
- Dynamic resizing based on content
- Variable parsing with {{ variable }} syntax
- Automatic handle creation for parsed variables

### 3. Pipeline Validation
- Backend DAG validation
- Node and edge counting
- User-friendly response display

## Getting Started

Follow these steps to run the project locally.

### Prerequisites

- Node.js 18 or higher
- Python 3.8 or higher
- npm or yarn package manager
- pip
- uvicorn

### Frontend Setup

1. **Clone and Install**
```bash
git clone https://github.com/drcount-root/VectorShift_Project
cd frontend
cp .env.example .env
npm install
```

2. **Start Development Server**
```bash
npm start
```

### Backend Setup

1. **Navigate to Backend Directory**
```bash
cd backend
```

2. **Install Python Dependencies**
```bash
pip install -r requirements.txt
```

3. **Start FastAPI Server**
```bash
uvicorn main:app --reload
```

## Challenges and Solutions

1. **Node Abstraction**
- Challenge: Creating a flexible yet maintainable node system
- Solution: Implemented a base node class with specialized inheritance

2. **Dynamic Text Nodes**
- Challenge: Handling variable parsing and dynamic handles
- Solution: Created regex-based parser with React state management

3. **Backend Integration**
- Challenge: Validating complex graph structures
- Solution: Implemented efficient DAG validation algorithms

## Optimizations

1. **Performance**
- Optimized ReactFlow rendering
- Efficient state management
- Minimized unnecessary re-renders

2. **Code Quality**
- Modular component architecture
- Reusable styling patterns
- Clear separation of concerns

3. **User Experience**
- Intuitive node interactions
- Responsive design
- Clear feedback mechanisms

## Outcome

The implementation successfully meets all assessment requirements while maintaining code quality and user experience. Key achievements include:

- Clean, abstracted node system
- Responsive and intuitive UI
- Efficient backend integration
- Comprehensive pipeline validation
- Modern styling implementation

# Screenshots

![0](https://github.com/user-attachments/assets/fb059c98-545a-4552-ac8f-9a56fe62800b)
![1](https://github.com/user-attachments/assets/93133186-ab30-449a-a07f-7b0699e19415)
![2](https://github.com/user-attachments/assets/920afd4d-dfd3-4931-bf43-c4b3e170046f)
![3](https://github.com/user-attachments/assets/6f7d83aa-a3a0-4e95-adc1-96169dbdc288)
![4](https://github.com/user-attachments/assets/86194e78-9e42-4968-84e7-146a691db318)
