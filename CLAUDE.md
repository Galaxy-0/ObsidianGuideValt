# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Overview

This is an Obsidian-based knowledge vault called "AI学习助手知识库" (AI Learning Assistant Knowledge Base) that serves as a comprehensive documentation system optimized for RAG (Retrieval-Augmented Generation) applications. The repository contains documentation for an AI learning assistant tool integrated with Obsidian, structured specifically for semantic search and Q&A functionality.

## Repository Architecture

### Document Structure
The repository follows a three-tier modular architecture:

1. **Root Level**: Core AI Learning Assistant documentation (numbered 00-05)
2. **操作指南/ (Operation Guides)**: How-to documentation for specific tasks
3. **Obsidian基础指南/ (Obsidian Basic Guides)**: Obsidian software usage Q&A

### Key Design Principles

- **RAG-Optimized**: All documents are designed for embedding and semantic search
- **Modular Independence**: Each document has complete context and can be understood standalone
- **Version Unified**: No version separation (V1.01/V1.1) - all features described as unified system
- **Chinese Language**: Primary language with technical English terms preserved
- **Link Structure**: Uses Obsidian-style `[[document_name]]` internal linking

## Common Development Tasks

### Content Creation and Editing
- **New Documents**: Follow naming convention with numeric prefixes for core docs (e.g., `06_新功能.md`)
- **Internal Links**: Use `[[document_name]]` format for cross-references
- **Image Handling**: Convert all images to detailed text descriptions (no images allowed for RAG compatibility)
- **Version References**: Avoid V1.01/V1.1 distinctions - describe as unified feature modules

### Quality Assurance
- **RAG Testing**: Use `RAG测试示例.md` as template for creating test questions
- **Link Validation**: Ensure all `[[]]` links point to existing documents
- **Context Completeness**: Each document must be understandable without external dependencies

### Document Optimization
- **Remove UI Noise**: Strip out visual descriptions like "红色框标出" (marked in red box)
- **Standardize Format**: Use consistent Markdown formatting
- **Maintain Independence**: Each document should provide complete context for its topic

## File Organization Rules

### Core Documentation (Root Level)
- `00_快速开始.md` - Quick start guide
- `01_概念术语表.md` - Terminology and concepts
- `02_详细安装指南.md` - Detailed installation
- `03_AI对话功能配置.md` - AI model configuration
- `04_常见问题解答.md` - Troubleshooting and FAQ
- `05_功能模块介绍.md` - Feature modules overview

### Specialized Directories
- `操作指南/` - Specific how-to guides
- `Obsidian基础指南/` - Obsidian software documentation
- `RAG测试示例.md` - RAG testing templates

## RAG Optimization Guidelines

### Content Requirements
- Pure text content only (no image dependencies)
- Complete context in each document
- Structured Q&A format where applicable
- Standard Markdown formatting for compatibility

### Link Management
- Use relative paths for internal references
- Maintain bidirectional linking relationships
- Update all affected documents when restructuring

### Testing and Validation
- Validate RAG retrieval using test questions from `RAG测试示例.md`
- Ensure embedding compatibility (text-only content)
- Test semantic search effectiveness with various query types

## Git Workflow

The repository is configured with comprehensive `.gitignore` rules for:
- Obsidian configuration files (`.obsidian/`)
- System files and temporary files
- IDE-specific files
- Personal/private content exclusions

When committing changes:
- Follow the established commit message format
- Include Claude Code co-authorship attribution
- Use descriptive commit messages explaining the documentation changes