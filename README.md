<a id="readme-top"></a>

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/ngdghnam/ROBOG2024-Robotronix/tree/Submission">
    <img src="https://lh3.googleusercontent.com/d/14RW8OZtzXa8hSkXL0p0XoyOk-qumuld_" alt="Logo" width="180" height="80">
  </a>

  <h3 align="center">ROBOG 2024</h3>

  <p align="center">
    TEAM: ROBOTRONIX
  </p>
  <p align="center">
    BOARD: C++
  </p>
  <table>
  <tr>
    <th>Full name</th>
    <th>University</th>
  </tr>
  <tr>
    <td>Nguyễn Đặng Hoài Nam</td>
    <td>University of Economics and Law - VNU-HCM</td>
  </tr>
  <tr>
    <td>Lê Minh Nguyên</td>
    <td>University of Economics and Law - VNU-HCM</td>
  </tr>
  <tr>
    <td>Bùi Nguyễn Thanh Thảo</td>
    <td>University of Economics Ho Chi Minh City</td>
  </tr>
  <tr>
    <td>Vũ Nhật Huy</td>
    <td>Ho Chi Minh City University of Technology - VNU-HCM</td>
  </tr>
  <tr>
    <td>Trần Xuân Hảo</td>
    <td>Ho Chi Minh City University of Technology - VNU-HCM</td>
  </tr>
  <tr>
    <td>Vũ Hoàng Tùng</td>
    <td>Ho Chi Minh City University of Technology - VNU-HCM</td>
  </tr>
</table>
</div>


<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
        <li><a href="#usage">Usage</a></li>
      </ul>
    </li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>


<!-- ABOUT THE PROJECT -->
## About The Project

### English
Today, Robots are on the rise, creating strong waves in many different areas of life. In addition, humanity is also modernizing their own lives. For businesses, they apply human intelligence to optimally support decision-making in business development, apply Robots to automate work processes, etc. For daily life, they are digitizing their own small homes, such as digitizing daily household tasks, weather forecasting, object recognition,... That's why we recommend the Yanshee Robot application for both major aspects of humanity. The main goal of this research is to apply machine learning and large language models along with the use of modern programming techniques running on the small Yanshee robot that people can carry anywhere. Through Agile methodology, the author team has implemented requirements by analyzing, designing, programming, and testing as well as deploying the product and following the motto of "doing their best" with some features such as recognising objects, getting weather information, etc. This research idea contributes to the modernization of households as well as business administrators in accessing and managing data, helping to reduce decision-making time and unnecessary risks to improve productivity—a high level of reliability along with user experience.

Feature:
* Gemini chatbot
* Realtime weather report
* Find and download music
* Play and dance to music
* Objects detection
* Face Recognition

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

This code is written and tested using Visual Studio Code with Python virtual environment.

### Prerequisites

To run this code on Yanshee, you need to have:
* Python 3.11
* YanAPI (from Yanshee Raspberry Pi RaspberianOS)
* ffmpeg (to download and process music)
* API key from Gemini, Spotify, and OpenWeatherMap (this code has included API keys in config.py for convenient purposes)

### Installation

1. Create a virtual environment in the same directory as main.py
2. Copy all files in the folder "YanAPI" into your environment library folder (.venv/Lib/site-packages/)
3. Download ffmpeg (ffmpeg-_(lastest version)_-full_build.7z) from [gyan.dev](https://www.gyan.dev/ffmpeg/builds/)
4. Extract and put the bin folder into ./.venv/ffmpeg-full_build/ (remember to rename the folder)

### Usage

1. Turn on Yanshee Robot and get its IP address
2. Change the IP address in config.py
3. Run main.py to turn on the robot

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

Resources used to make this project possible:

* [YanAPI Documentation](https://yandev.ubtrobot.com/#/en/api?api=YanAPI)
* [Gemini API Cookbook](https://github.com/google-gemini/cookbook/tree/main)
* [Singapore Institute of Technology Library](https://libhelp.singaporetech.edu.sg/search/?t=0&adv=1&topics=Yanshee)

<p align="right">(<a href="#readme-top">back to top</a>)</p>
