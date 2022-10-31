## Using the "grep" command

###### Using the grep ".txt" command line
<img width="560" alt="Screen Shot 2022-10-31 at 10 18 59 AM" src="https://user-images.githubusercontent.com/103763994/199069242-046fcd85-cf4f-45ce-846c-4d0f751ba921.png">
This shows the usage of grep -string which basically prints all the lines that contains ".txt", then using "wc" on that to find how many lines and words the output contains. 

###### Example 2: Using the grep -i command line
<img width="621" alt="Screen Shot 2022-10-31 at 10 29 15 AM" src="https://user-images.githubusercontent.com/103763994/199071277-95234eec-6d08-4e29-a2b5-1f2129df81e8.png">
This shows the usage of grep -i "string" which prints the line in the file which contains the inputted string regardless of case sensitivty as seen in the picture above.

###### Example 3: Using the grep -n command line
<img width="591" alt="Screen Shot 2022-10-31 at 10 32 09 AM" src="https://user-images.githubusercontent.com/103763994/199071898-e81ed6eb-2b91-4c95-acc3-5387890b01a5.png">
This shows the usage of grep -i "string" which prints the number of the line in which the inputted string is found within the file. 

## Using the "less" command

###### Example 4: Using the less -p command line
<img width="525" alt="Screen Shot 2022-10-31 at 10 39 00 AM" src="https://user-images.githubusercontent.com/103763994/199073675-77e166d5-d264-41d9-b65f-016fce627ee1.png">
This is the output of running *less -p "jeffordslieberm.txt" find-results.txt*. The -p command automatically hightlights the string that is being searched and displays the results of all the lines in the file only from the line of the searched string and onwards. 

###### Example 5: Using the less -M command line
<img width="551" alt="Screen Shot 2022-10-31 at 10 52 13 AM" src="https://user-images.githubusercontent.com/103763994/199075679-ea17fc3f-4208-401d-8cc7-d31d000e7de9.png">
The -M command (*less -M find-results.txt*) creates a highlighted line at the bottom of the terminal screen that shows how many lines and what percentage of the file you have completed browsing. The percentage updates the lower you go as your nearing the end of the file. 

###### Example 6: Using the less -X command line
<img width="625" alt="Screen Shot 2022-10-31 at 11 05 07 AM" src="https://user-images.githubusercontent.com/103763994/199078149-0d0ae206-ac14-4360-bd37-10598af1e730.png">
The -X command (*less -X find-results.txt*). This would mainly be used for smaller files where you always want to contents of the file ready to read. The -X command leaves the content of the file even after you quit the less "remote take-over". 


## Using the "find" command

###### Example 7: Using the find -size +N command line
<img width="676" alt="Screen Shot 2022-10-31 at 11 18 31 AM" src="https://user-images.githubusercontent.com/103763994/199080714-47fb36c2-29c1-4607-a357-37e9f09e5647.png">
This command filters the repository for all the files that have a size above or below N megabytes. 




