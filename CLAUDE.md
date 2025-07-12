# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Overview

This is an Obsidian-based knowledge vault called "AI学习助手知识库" (AI Learning Assistant Knowledge Base) that serves as a comprehensive documentation system optimized for RAG (Retrieval-Augmented Generation) applications. The repository contains documentation for an AI learning assistant tool integrated with Obsidian, structured specifically for semantic search and Q&A functionality.

## Repository Architecture

### Current Document Structure
The repository has been reorganized into a logical folder structure:

```
/
├── 核心文档/ (Core Documents)
│   ├── 00_快速开始.md - Quick start guide
│   ├── 01_概念术语表.md - Terminology and concepts
│   ├── 02_详细安装指南.md - Detailed installation
│   ├── 03_AI对话功能配置.md - AI model configuration
│   ├── 04_常见问题解答.md - Troubleshooting and FAQ
│   └── 05_功能模块介绍.md - Feature modules overview
├── 操作指南/ (Operation Guides)
│   ├── 01_配置嵌入模型.md - Embedding model setup
│   ├── 02_使用VaultQA功能.md - VaultQA usage guide
│   ├── 03_配置语音功能.md - Voice features setup
│   └── 04_使用AI人设.md - AI persona customization
├── Obsidian基础指南/ (Obsidian Basic Guides)
│   ├── Obsidian基础概念和入门.md
│   ├── 笔记编写和链接.md
│   ├── 插件和定制化.md
│   ├── 工作流和生产力.md
│   └── 常见问题和技巧.md
├── 开发文档/ (Development Docs)
│   └── RAG测试示例.md - RAG testing templates
├── AI学习助手完整使用文档（rag）.md - Complete reference
└── CLAUDE.md (this file)
```

### Key Design Principles

- **RAG-Optimized**: All documents are designed for embedding and semantic search
- **Modular Independence**: Each document has complete context and can be understood standalone
- **Version Unified**: No version separation - all features described as unified system
- **Chinese Language**: Primary language with technical English terms preserved
- **Link Structure**: Uses Obsidian-style `[[document_name]]` internal linking with folder paths
- **Q&A Format**: All documents use Question-Answer format for better semantic understanding

## Common Development Tasks

### Content Creation and Editing
- **New Documents**: Follow existing naming conventions (numeric prefixes for guides)
- **Internal Links**: Use `[[folder/document_name]]` format for cross-folder references
- **Image Handling**: All images converted to text descriptions (no image files)
- **Version References**: Avoid specific version numbers in content

### Quality Assurance
- **Link Validation**: All internal links must point to existing documents
- **Path Accuracy**: Cross-folder links must include correct path prefix
- **Q&A Consistency**: Maintain uniform Q&A format (Q: followed by **A**:)
- **Context Completeness**: Each document must be self-contained

### Document Optimization
- **Remove Visual References**: No "如下图所示", "红色框标出" etc.
- **Standardize Format**: Consistent Markdown and Q&A structure
- **Eliminate Redundancy**: Core docs provide overview, operation guides provide details
- **Clean File Names**: No version numbers in file names

## File Organization Rules

### Document Categories
1. **核心文档/**: High-level overviews and concepts
2. **操作指南/**: Step-by-step procedures
3. **Obsidian基础指南/**: Obsidian software documentation
4. **开发文档/**: Testing and development resources

### Naming Conventions
- Core docs: `00-05_功能名称.md`
- Operation guides: `01-04_操作名称.md`
- No version numbers in filenames

## RAG Optimization Guidelines

### Content Requirements
- Pure text content only (no images or binary files)
- Complete context in each document
- Q&A format for all instructional content
- Standard Markdown formatting

### Link Management
- Use folder-aware links: `[[操作指南/01_配置嵌入模型]]`
- Maintain link integrity when moving files
- Update all references when renaming documents

### Testing and Validation
- Use `开发文档/RAG测试示例.md` for testing retrieval
- Verify semantic search with various query types
- Ensure all links resolve correctly

## Recent Optimizations (2025-01-12)

### Completed Improvements
1. **Link Fixes**: All internal links corrected to match actual filenames
2. **Path Prefixes**: Added folder paths to cross-directory links
3. **Format Unification**: Converted all docs to Q&A format
4. **Number Cleanup**: Removed Q1/Q2 numbering, unified to Q: format
5. **Version Removal**: Cleaned version numbers from filenames
6. **Content Deduplication**: Replaced duplicate content with link references

### Maintenance Guidelines
- When updating content, check all related documents
- Maintain Q&A format for new content
- Test links after any file reorganization
- Keep this CLAUDE.md updated with structural changes

## Git Workflow

The repository uses standard git practices:
- Descriptive commit messages
- Include change summary in commits
- Test link integrity before pushing
- Document structural changes in CLAUDE.md