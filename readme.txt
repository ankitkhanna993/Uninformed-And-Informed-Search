1. Name: Ankit Khanna
   UTA ID: 1001553616

2. Programming Language : Python3

3. Code Structure: "find_route.py" - defines 4 functions:
    a. input_file : Reads the input file until END Of INPUT and creates a dictionary.
    b. input_file_heuristic : Reads the heuristic file until END Of INPUT and creates a dictionary.
    c. uninformed_search : Implements a graph based uniform cost search
    d. informed_search : Implements A* search

4. Code Execution:
   python3 find_route.py -input_file -source -destination -hueristicFile(optional)
   "python3 find_route.py input1.txt Bremen Kassel" - runs uninformed cost search when heuristics are not given.
   "python3 find_route.py input1.txt Bremen Kassel h_kassel.txt" - runs A* informed cost search when heuristics are given.
