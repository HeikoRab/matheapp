# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is an educational math tutoring project that uses Claude AI as a gamified tutor ("Brookhaven Mathe Master") for German-speaking elementary students. The project combines math worksheets with Roblox game mechanics (specifically the Brookhaven game) to create an engaging learning experience.

## Project Structure

- `tutor-prompt.md` - System prompt (in German) defining the AI tutor's behavior and personality
- `*.jpeg` - Scanned math worksheet images (pages from a German math workbook) covering division with remainder, doubling/halving, subtraction, and number patterns

## How It Works

The `tutor-prompt.md` file instructs Claude to:
1. Act as a legendary game developer guiding a student through "99 nights in Brookhaven"
2. Present math problems from the worksheet images one at a time
3. Use Roblox terminology (Robux, Pets, Bloxy Coins) as rewards
4. Explain mistakes patiently and motivationally

## Working With This Project

- To modify the tutoring experience, edit `tutor-prompt.md`
- To add new math content, add worksheet images to the directory
- The tutor automatically references local images when interacting with students
