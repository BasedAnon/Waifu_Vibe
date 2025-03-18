# Waifu_Vibe

A modified version of [w-AI-fu](https://github.com/GXiaoyang/w-AI-fu_v2) that implements direct NovelAI API calls instead of using the NovelAI npm package.

## Features

- Direct Python implementation of NovelAI API calls
- No dependency on NovelAI SDK
- Same functionality as the original w-AI-fu
- Toggle between SDK and direct API implementation

## Modified Components

- `boilerplate_direct.py` - Direct API client for NovelAI authentication and HTTP requests
- `novel_tts_direct.py` - Text-to-speech functionality with direct API calls
- `novel_llm_direct.py` - Language model generation using direct API calls
- `tts_novelai_direct.ts` - TypeScript interface for the direct TTS implementation
- `llm_novelai_direct.ts` - TypeScript interface for the direct LLM implementation
- Updated dependency loader to support toggling between SDK and direct implementations

## Usage

The application defaults to using the direct API implementation. The functionality remains the same as the original w-AI-fu.

## Installation

Follow the original w-AI-fu installation instructions. No additional dependencies are required for the direct API implementation.

## Credits

This project is a modification of [w-AI-fu by GXiaoyang](https://github.com/GXiaoyang/w-AI-fu_v2).