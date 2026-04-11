---
title: Agentic Programming
publish: true
tags:
  - ai
  - llm
  - projects
draft: false
---
# Agentic Programming

## What is an Agent?

LLM Agen atau selanjutnya dapat disebut sebagai Agent, adalah paradigma bahwa sebuah system dapat menyelesaikan tugas secara otomatis, tanpa harus melibatkan manusia dalam proses nya.

Sebuah AI Agent selalu memiliki Goal, yaitu tujuan dibuatnya agent tersebut. Biasanya pembuatan sebuah agent diibaratkan seperti role playing atau permainan peran. Peran tersebut dijelaskan melalui prompts yang dapat kita atur sendiri.

## Agent Components

* Prompts
	* System message, biasanya berisi peran, tujuan dan cara menuju tujuan tersebut. Secara lebih lanjut, pelajari [referensi berikut](http://promptengineering.ai/) untuk menentukan type prompt apa yang sesuai dengan kebutuhan.
    - Human message, biasanya berupa input dari user
    - AI message, balasan dari system,
- AI Model
	AI Model adalah otak dari agent. AI model akan memberikan response berdasarkan prompt (persona) yang telah dijelaskan sebelumnya. Secara umum AI Model (LLM) dibagi menjadi dua.
    
    - LLM Model, merupakan general purpose LLM,
    - Chat Model, dioptimalisasikan untuk conversation
    - OpenAI, Antrophic, DeepSeek, Ollama
- Tools
    Sebuah agent dapat dilengkapi dengan tools. Tools ini merupakan bagian terkecil (atomic) dari system. Artinya satu tools seharusnya hanya melakukan satu tugas. Tugas yang dimaksud di sini adalah satu prosedur atau satu langkah prosedural yang memberikan hasil secara langsung. Tools hanya menjadi eksekutor sedangkan LLM sebagai otak yang harus membuat keputusan dan informasi yang sesuai.
	Pada dasarnya tools adalah sebuah fungsi dalam programming. Fungsi tersebut dapat mengambil argument yang dibutuhkan, dan mengembalikan nilai. Nilai ini kemudian dikembalikan kepada AI model sehingga AI model dapat membuat keputusan.
    
## ReAct Agent

Reason & Action Agent adalah salah satu jenis agent yang menerapkan konsep lengkap. Agent yang telah diberi persona (prompt), akan melakukan reasoning dan kemudian melakukan action. Action tersebut dapat berupa memberikan response, atau mengeksekusi satu atau beberapa tools. Konsep ReAct Agent ini merupakan hal mendasar yang kemudian akan digunakan untuk beberapa aplikasi dalam chatbot.

Salah satu framework yang sering digunakan untuk membuat ReAct agent adalah LangChain. LangChain adalah salah satu implementasi dari agentic programming.
