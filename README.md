# Video-To-GIF-Python
 - this code uses the MoviePy library to load a video file, extract a specific segment (from 0 to 5 seconds), and save that segment as a GIF file named "test.gif." This is a simple way to cut a portion of a video and convert it into a GIF using Python.


1️⃣ 𝐈𝐦𝐩𝐨𝐫𝐭𝐢𝐧𝐠 𝐌𝐨𝐯𝐢𝐞𝐏𝐲:
![codeimage-snippet_13](https://github.com/kaniz-codes/Video-To-GIF-Python/assets/138873297/2e63ce0f-f1c5-4f92-bc31-9829c16d933e)
- This line imports the necessary functions and classes from the MoviePy library, which is a Python library for video editing and manipulation.

2️⃣ 𝐋𝐨𝐚𝐝𝐢𝐧𝐠 𝐭𝐡𝐞 𝐕𝐢𝐝𝐞𝐨:
![codeimage-snippet_13 (1)](https://github.com/kaniz-codes/Video-To-GIF-Python/assets/138873297/8fa849a8-c985-468a-b4c4-610b5a8e465a)
- 𝐕𝐢𝐝𝐞𝐨𝐅𝐢𝐥𝐞𝐂𝐥𝐢𝐩("𝐤𝐚𝐧𝐢𝐳.𝐦𝐩𝟒") loads the video file "kaniz.mp4" and creates a VideoFileClip object representing the entire video.
.𝐬𝐮𝐛𝐜𝐥𝐢𝐩(𝟎, 𝟓) extracts a subclip from the original video, starting at 0 seconds and ending at 5 seconds. This creates a new VideoFileClip object representing the specified segment of the video.

3️⃣ 𝐂𝐫𝐞𝐚𝐭𝐢𝐧𝐠 𝐭𝐡𝐞 𝐆𝐈𝐅:
![codeimage-snippet_13 (2)](https://github.com/kaniz-codes/Video-To-GIF-Python/assets/138873297/8c198f68-e6a3-4630-aa49-77d67a539c45)
- 𝐯𝐢𝐝𝐞𝐨.𝐰𝐫𝐢𝐭𝐞_𝐠𝐢𝐟("𝐭𝐞𝐬𝐭.𝐠𝐢𝐟") converts the extracted video segment (subclip) into a GIF file named "test.gif." The .write_gif() method is used to create the GIF.


🐍 𝐅𝐢𝐧𝐚𝐥 𝐂𝐨𝐝𝐞:

![codeimage-snippet_13 (3)](https://github.com/kaniz-codes/Video-To-GIF-Python/assets/138873297/11fefdd1-8a75-4571-a230-2fc22432d9b3)
