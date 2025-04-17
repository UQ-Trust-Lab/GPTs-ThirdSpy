![WechatIMG304](https://github.com/user-attachments/assets/0b8fd423-73a4-4a8a-afa0-f0b1a5710f70)# GPTs-ThirdSpy
An automated framework designed to extract GPTs’ privacy settings

GPTs-ThirdSpy automates the extraction of privacy-related links from GPTs listed in the GPT Store by controlling Google Chrome via AppleScript and cliclick. It reads a list of GPT URLs, opens each one, interacts with the UI, and collects structured privacy data.

##  Requirements
- macOS
- Google Chrome installed
- cliclick installed via Homebrew: brew install cliclick


## Usage
osascript gpts_pp_path_1.scpt \
"/absolute/path/to/input.txt" \
"/absolute/path/to/output.csv" \
"GPT_title_click_position" \
"Privacy_setting_click_position"

GPT_title_click_position:
![截屏2025-04-17 下午3 54 39](https://github.com/user-attachments/assets/cd15f5e7-a0fa-4ade-9621-1dba21b70913)

Privacy_setting_click_position:
![截屏2025-04-17 下午3 56 19](https://github.com/user-attachments/assets/4cebca40-037c-4f5e-985b-8ce5e7efeff4)

### Example
osascript Main.scpt \
"/Users/xx/Desktop/gpts_auto_script/extract_id/gptshunter_id_url.txt" \
"/Users/xx/Desktop/gpts_auto_script/extract_id/gptshunter_path_pp.csv" \
"330,153" \
"400,290"

