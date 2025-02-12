# 🚀 dmcpp-port Project

![dmcpp-port](images/dmcpp-port.jpg)

**English** · [简体中文](./README.zh-CN.md) 

---

## Project Preface

In the field of interoperability between C++ and other languages, developers often face complex toolchains and tedious configuration processes. The **dmcpp-port** project was born to solve these problems, aiming to provide C++ developers with a simple, efficient and unified language interoperability solution.

---

## Project Introduction

In the programming world, C++ is like a great route, powerful and full of challenges, while other programming languages are like four separate continents, each with its own characteristics but difficult to communicate with each other. The **dmcpp-port** project, like the **All Blue** in "One Piece", is committed to breaking down language barriers and building a bridge that allows developers to freely travel between different programming worlds.

Just like Luffy looking for **One Piece**, we believe:
- 🐍 **Python**'s elegance is like the East Sea, gentle and vibrant
- 🌿 **Lua**'s lightness is like the South Sea, flexible and full of possibilities
- 🌐 **JavaScript**'s vitality is like the West Sea, ubiquitous
- ⚡ **Go**'s efficiency is like the North Sea, cold and powerful
- 🛡 **C#**'s comprehensiveness is like the Red Line, solid and reliable

Let us embark on this great voyage together and create the **All Blue** for all developers!

---

## Porting Status

| Language         | Status   | Progress | Remarks                                |
|------------------|----------|----------|----------------------------------------|
| 🐍 Python       | Implemented | 100%  | Perfect implementation using **pybind11**, a model example      |
| 🌿 Lua          | Implemented | 100%  | Perfect implementation using **sol2**, a model example         |
| 🌐 JavaScript   | Implemented | 100%  | Using **genepi API**, slightly rough but feasible      |
| 🌐 JavaScript   | Implemented | 100%  | Implemented using **emsdk**, acceptable effect           |
| ⚡ Go           | Not Implemented | 20%   | Only demo completed so far                        |
| 🛡 C#           | Implemented | 50%   | Demo completed, code generator not yet implemented            |

---

## Porting Plan

### 🐍 Python
- **Technology**: Use **pybind11** to complete automatic binding
- **Project Name**: `dmgen4pybind`

### 🌿 Lua
- **Technology**: Use **sol2** to complete automatic binding
- **Project Name**: `dmgen4sol`

### 🌐 JavaScript
- **Technology**: Use **genepi** to complete automatic binding
- **Project Name**: `dmgen4node`

### 🌐 JavaScript (WASM)
- **Technology**: Use **emsdk** to complete automatic binding
- **Project Name**: `dmgen4wasm`

### ⚡ Go
- **Technology**: Use **swig** to complete automatic binding
- **Project Name**: `dmgodemo`

### 🛡 C#
- **Technology**: Use **CppCsharp** to complete binding
- **Project Name**: `dmcsharp-dmprojectinfo`

---

## Development Guide

1. Each language port will create an independent branch.
2. After the port is completed, it will be merged into the main branch.
3. Each language port needs to include unit tests. ✅
4. Ensure API interface consistency. ✅

---

## Contribution Guide

Welcome to contribute code and submit Pull Requests, please follow the following specifications:
- Create an independent directory for each language port.
- Maintain code style consistency.
- Provide complete documentation and test cases. 📚

---

## Summary

The implementation of **pybind11** and **sol2** is perfect, more elegant than solutions for other languages. Although there are still some language porting work in progress, we believe this project will greatly simplify the complexity of cross-language development and bring developers a more efficient way of working. Let us move towards a more active, healthy and creative future together! 🌟🚀

---