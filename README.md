What It Does

Fetches RSS Feeds - Pulls latest news from multiple Nepal news sources
AI Categorization - Uses OpenAI GPT-4o-mini to categorize news into 13 categories
Poll Generation - Automatically creates engaging poll questions with 4 multiple-choice answers
Database Storage - Stores all data in Supabase (polls, posts, votes)
Social Media Posts - Generates platform-optimized content for Facebook, Instagram, and LinkedIn
Admin Dashboard - Beautiful web interface for reviewing and approving posts
Human Approval - Human-in-the-loop workflow before posting to social media
Results Tracking - Calculates vote results and generates charts
Email Notifications - Sends aggregated summaries to admins

🏗️ Architecture
RSS Feeds → AI Processing → Database → Social Posts → Admin Review → Publish
Components:

n8n - Workflow automation platform
Supabase - PostgreSQL database with REST API
OpenAI GPT-4o-mini - AI for categorization and poll generation
SMTP - Email notifications
