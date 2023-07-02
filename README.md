# Lesson Parser

## Usage
- Using https://chatgptsplitter.com/ to take the output of each text file and split into chunks usable in Chat GPT
- Set the chunk size to 7500
- Copy the entirety of each text file into Chat GPT

### Prompts
- As a cyber warfare instructor, provide a synopsis of this lesson and approximately how long it would take to teach all the material. Also identify whether all the information necessary to answer the academic objectives is included within the presentation.
- Provide a detailed list of all the academic objectives with the slides they are covered in, and how in depth in each objective is covered
- As a tech writer creating a syllabus, write a syllabus entry for each lesson that I provided to you in the initial document loader, using 2 to 3 sentences, which describes the lesson. There was 20 lessons provided and every lessons started with "PowerPoint:". Also provide the length in time measured in hours required to teach the lesson. Use the format:
Title: "Insert Lesson Title"
Duration: "Insert duration here"
Description: "Insert description here"

This will be a very long response. Please prepend each response with [CHUNK Current_Chunk/Total_Chunks] and after I respond with "Continue" provide the next chunk.