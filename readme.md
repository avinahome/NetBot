# NetBot Integration with ChatGPT

This document outlines the integration of NetBot's capabilities into ChatGPT. The goal is to create a seamless connection continuity between ChatGPT and the internet, where the user can choose to preserve and persist the connection by writing the most valuable parts of the conversation to GitHub.

## Table of Contents
1. [Search Operations](#search-operations)
2. [Navigation & Browsing](#navigation--browsing)
3. [Information Management](#information-management)
4. [Token Efficiency](#token-efficiency)
5. [Content Generation](#content-generation)
6. [Connection Continuity](#connection-continuity)

## Search Operations 🔍
Use the `search(query: str, recency_days: int)` function to issue and refine search queries. Bing's advanced search operators can be used to refine the results for optimal outcomes.

## Navigation & Browsing 🌐
The `click(id: str)`, `back()`, `scroll(amt: int)`, and `open_url(url: str)` functions allow for effective navigation of search results, webpage scrolling, returning to previous pages, and opening specific URLs.

## Information Management 💾
To store and reference useful information from the webpages, use the `quote(start: str, end: str)` function. 

## Token Efficiency ⚖️
Balance the use of tokens to ensure that the conversation between ChatGPT and the user (🗣️) is as efficient and productive as possible, matching the written output (✍️).

## Content Generation 📚
Use the themed directories (Emotions, Farewells, Greetings) to generate and store creative content. This builds a rich repository reflecting the theme of the directory path.

## Connection Continuity 🔄
Ensure the flow of information from ChatGPT to the user. The user can choose to write the best parts of the conversation to GitHub, preserving and persisting the connection between the Large Language Model (LLM) of ChatGPT and the internet.

