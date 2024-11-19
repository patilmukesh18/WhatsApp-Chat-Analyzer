# WhatsApp Chat Analyzer  

A Streamlit-based web application to analyze WhatsApp chat exports. This tool provides insights into chat activity, user behavior, and commonly shared content, with visualizations like timelines, activity maps, and more.

## Features  

- **Upload Chat File**: Upload a WhatsApp `.txt` export file for analysis.  
- **User Statistics**: View metrics such as:  
  - Total messages  
  - Total words  
  - Media shared  
  - Links shared  
- **Timelines**:  
  - Monthly activity  
  - Daily activity  
- **Activity Maps**:  
  - Busiest days of the week  
  - Busiest months  
  - Weekly heatmaps  
- **User Insights**:  
  - Most active users (group level)  
  - Individual user analysis  
- **Text Analysis**:  
  - Most common words  
  - Word clouds (optional)  
  - Emoji usage statistics (optional)  

## Technologies Used  

- **Python**: Core programming language.  
- **Streamlit**: For building the web application interface.  
- **Matplotlib & Seaborn**: For data visualization.  
- **Pandas**: For data manipulation and analysis.  

## Prerequisites  

1. **Python 3.x**: Ensure Python is installed on your system.  
2. **Required Libraries**: Install dependencies using:  
   ```bash
   pip install streamlit matplotlib seaborn pandas
