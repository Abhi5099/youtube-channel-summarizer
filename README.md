# YouTube Channel Summarizer

## AI-Powered Video Content Digest

Automatically monitors YouTube channels, generates concise summaries using ChatGPT, and delivers key insights via email - perfect for staying updated without watching hours of content.

![Workflow Screenshot](https://github.com/Abhi5099/youtube-channel-summarizer/blob/main/Screenshot%202025-06-02%20043933.png?raw=true)
*Make.com automation flow: YouTube → ChatGPT → Email*

## Key Features
- **Channel Monitoring**: Tracks new videos from specified YouTube channels
- **Smart Summarization**: ChatGPT extracts key points with timestamps
- **Scheduled Delivery**: Receives regular email digests (daily/weekly)
- **Customizable Depth**: Control summary length and detail level

## How It Works
1. **Trigger**: Checks YouTube channel for new videos (hourly/daily)
2. **Processing**:
   - Extracts video transcript or description
   - ChatGPT generates executive summary
   - Identifies key topics and timestamps
3. **Delivery**: Sends formatted email with:
   - Video title and link
   - Bullet-point summary
   - Key takeaways

## Integration
| Service | Role |
|---------|------|
| YouTube API | Video discovery |
| OpenAI ChatGPT | Content summarization |
| Email (Gmail/SMTP) | Report delivery |

## Business Value
- **Saves 2-3 hours/week** per monitored channel
- **Improves content discovery** with AI-curated highlights
- **Customizable** for different detail needs

## Technical Implementation
- No-code workflow using Make.com
- Adaptive prompt engineering for different video types
- Error handling for private/deleted videos
- Configurable scheduling options
