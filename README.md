# Document Indexing System Visual Studio C++ Project
Wordfinder system that responds single word queries. 
This system allows users to enter a single word, then returns a list of documents containing this word.

## Usage
Document Indexing System was written by using Visual Studio (version 2017) that's why you'll need Visual Studio or Dev C++.
To start using with Visual Studio, after downloading all files to the same directory,
Just open the file named **"Source.sln"** with Visual Studio and Follow these steps;

![sample 11](https://user-images.githubusercontent.com/36234545/39473818-70be27aa-4d59-11e8-9039-8c9a0b440cdc.png)

1. You will see **"Solution Explorer"** top right corner of the program, Open **"Header Files"** and **"Source Files"**.

![sample 1](https://user-images.githubusercontent.com/36234545/39473800-5aac3dbc-4d59-11e8-9b16-be59184d2869.png)

3. Open all these files -> **Node.h,** **Node.cpp,** **List.h,** **List.cpp,** and **Source.cpp**.

![sample 3](https://user-images.githubusercontent.com/36234545/39473785-42051482-4d59-11e8-81b8-067a0e4e9c29.png)

The program is ready now, Tabs should look like this; 

![sample 4](https://user-images.githubusercontent.com/36234545/39473916-044ca424-4d5a-11e8-9210-fd4caea32c42.png)

Please make sure that all files are opened correctly.

After everything is done, you can run the program. You can use __CTRL+F5__ to run.

# Important Notes
1. There are __9598__ txt files in the "(any folder name)\Task 2\files" directory. This is our document pool. 
The words will be searched from within this source.

![9858 files](https://user-images.githubusercontent.com/36234545/39474683-d58099ee-4d5d-11e8-99b2-bc9fceb2f7bf.png)

2. You can change the number of files to search from __Source.cpp__. You can write up to 9598 at most.
If you increase this number, the searching part will take longer time.

**->Note that Source.cpp is the main part of the program!**

![amount of files](https://user-images.githubusercontent.com/36234545/39474803-5e85bc7e-4d5e-11e8-951a-283546df3c47.png)

3. There is also a **stopwords.txt** file. This file consists of filtered words, such as ‘a’, ‘an’, ‘the’ etc.
"stop words" usually refers to the most common words in a language.
So, these words will be trimmed and will not be searched when you run the program.

![stop words](https://user-images.githubusercontent.com/36234545/39475242-3605bae0-4d60-11e8-8805-4af9ea80f7a2.png)

4. There are certain searching rules, you will see these on the cmd's screen when you run the program.

![2018-05-01 16_22_17-c__windows_system32_cmd exe](https://user-images.githubusercontent.com/36234545/39475484-03d774ae-4d61-11e8-91a9-f9e04a7046cc.png)



# Samples

---> When you enter a searchable word, program will find a list of documents containing this word.

![fulll](https://user-images.githubusercontent.com/36234545/39475762-3c7344a4-4d62-11e8-80b1-4f1c23838a88.png)

---> When you want to quit the program will show you a summary chart of the linked lists

![finish](https://user-images.githubusercontent.com/36234545/39475852-977358ee-4d62-11e8-87c3-b7f88ca82860.png)



## License
Document Indexing System is licensed under the MIT license. See LICENSE for more information.

## Project Status
You can download the latest release from here.

## Disclaimer
This project was prepared and shared for educational purphoses only. You can use or edit any file as you wish :)
This project may helpful for students who take **Data Structures** Lesson.

## About
Süha TANRIVERDİ Çankaya University, Computer Engineering Department.

# *"	A rolling stones gather no moss ... :) "*
