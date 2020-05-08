# iOS_Interview
iOS Challenge

Coding Challenge 


     
Develop an iPhone-App in Swift for searching and showing music album information provided by the LastFM-API (  https://www.last.fm/de , similiar alternative APIs would be ok).

The app should contain the following screens:

main-screen: This screen shows all the albums found by searching after an artist name, presented in a UICollectionView. A tap on one of these albums opens a detail - page.  The navigationBar contains a search-icon, which opens the search on tap.

Detail Page : Overview with detailed information (name, artist, tracks, etc.) about the album.

Requirements:

- Swift-Version > 4

- >= iOS 10

- API communication in JSON-format

- Use the Codable protocol to serialize the JSON

Optional:

UI and UX is fully up to you. Animations and gestures are not required, but nice to have.

Use the following :
 API key 16f77b0b415193c7754be7a7896ca057
Shared secret 730abfc1ea6c06c21b93fb0007b28a3b

Feel free to be creative  :) 

Good luck!


Coding challenges:

1.Given an array of strings, group anagrams together.

Input: ["eat", "tea", "tan", "ate", "nat", "bat"],
Output:
[
  ["ate","eat","tea"],
  ["nat","tan"],
  ["bat"]
]

2.Given an array nums of n integers, are there elements a, b, c in nums such that a + b + c = 0? Find all unique triplets in the array which gives the sum of zero.

Given array nums = [-1, 0, 1, 2, -1, -4],

A solution set is:
[
  [-1, 0, 1],
  [-1, -1, 2]
]

3.Given a sorted array nums, remove the duplicates in-place such that each element appear only once and return the new length.
Do not allocate extra space for another array, you must do this by modifying the input array in-place with O(1) extra memory.
Given nums = [1,1,2],

Your function should return length = 2, with the first two elements of nums being 1 and 2 respectively.
