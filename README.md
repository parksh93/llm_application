# 소득세법 RAG 실습
## 개요
국가법령정보에 기재되어 있는 소득세법을 저장하여 RAG를 통해 소득세법을 조회한다.

## 사용기술
1. Python 3.11
2. llm-model : gpt-4o
3. document loader : Docx2txtLoader
4. chunck: langchain_text_splitters > RecursiveCharacterTextSplitter
5. embedding : upstageEbedding
6. vectorDB : chroma