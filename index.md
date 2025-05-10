---
layout: home
title: Personal Planner
description: A simple, markdown-based personal planner to help you stay organized and track your progress.
---

# Welcome to Your Personal Planner

This is your digital planning space where you can organize your tasks, goals, and notes in a clean, accessible format.

## Quick Navigation

<div class="quick-links">
  <div class="link-card">
    <h3>📅 Daily Tasks</h3>
    <p>Track your daily activities and to-dos</p>
    <a href="daily/" class="button">View Daily Tasks</a>
  </div>

  <div class="link-card">
    <h3>📊 Weekly Planning</h3>
    <p>Plan your week and review progress</p>
    <a href="weekly/" class="button">View Weekly Plans</a>
  </div>

  <div class="link-card">
    <h3>🎯 Monthly Goals</h3>
    <p>Set and track monthly objectives</p>
    <a href="monthly/" class="button">View Monthly Goals</a>
  </div>

  <div class="link-card">
    <h3>📁 Projects</h3>
    <p>Manage your ongoing projects</p>
    <a href="projects/" class="button">View Projects</a>
  </div>

  <div class="link-card">
    <h3>📝 Notes</h3>
    <p>Store important information and references</p>
    <a href="notes/" class="button">View Notes</a>
  </div>
</div>

## Getting Started

1. Choose a section from the quick links above
2. Create new markdown files as needed
3. Use the following format for tasks:
   ```markdown
   ## [Date] Tasks
   
   - [ ] Task 1
   - [ ] Task 2
   - [x] Completed task
   ```

## Tips for Effective Planning

- Use checkboxes for tasks (they work in GitHub's markdown!)
- Add dates to your files for better organization
- Use headers to separate different sections
- Feel free to add images, links, and other markdown features
- Regular review and updates help maintain an effective planning system

<style>
.quick-links {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 1rem;
  margin: 2rem 0;
}

.link-card {
  border: 1px solid #e1e4e8;
  border-radius: 6px;
  padding: 1rem;
  background-color: #f6f8fa;
}

.link-card h3 {
  margin-top: 0;
  color: #0366d6;
}

.button {
  display: inline-block;
  padding: 0.5rem 1rem;
  background-color: #0366d6;
  color: white;
  text-decoration: none;
  border-radius: 4px;
  margin-top: 0.5rem;
}

.button:hover {
  background-color: #024ea4;
}
</style> 