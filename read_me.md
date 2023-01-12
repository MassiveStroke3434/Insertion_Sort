<!-- This insertion project logic Read_me file prepared according to lesson which taken from yazilim_akademisi -->

1-) "Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.":
    Initial insertion_list = [22,27,16,2,18,6]
    - [22,27,16,2,18,6] -> [2,27,16,22,18,6] -> [2,6,16,22,18,27] -> [2,6,16,22,18,27] -> [2,6,16,18,22,27] -> [2,6,16,18,22,27]
        In first iteration we checked all of the values and the lowerest one is 2, so it became the first value. This action happened like switching position with previous first value.
        In second iteration after replace action, we gonna check rest of 5 value, and the lowerest value is 6, so this value became second order.
        This action continue like until all list arranged.

2-) "Big-O gösterimini yazınız.":
    For determine the represent with Big-O:
        In first iteration we need to check all of the values like n. (6 times for this example)
        In second iteration we need to check n-1 values.(5 times)
        This value decrease 1 for each iteration until its arrived 1.
        From this path this Big-O value will be : n+(n-1)+(n-2) --> (n*(n+1))/2 --> The answer is: n^2

3-) "Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız":
    After done with this instertion_sorting the list will be : [2,6,16,18,22,27], if we check the list we will see that 18 became the middle of the list, so this sorting case matching with --> !!Average case !!

4-) "[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız."
        First step: [7,3,5,8,2,9,4,15,6] --> [2,3,5,8,7,9,4,15,6]
        Second step: [2,3,5,8,7,9,4,15,6] --> [2,3,5,8,7,9,4,15,6]
        Third step: [2,3,5,8,7,9,4,15,6] --> [2,3,4,8,7,9,5,15,6]
        Fourth step: [2,3,4,8,7,9,5,15,6] --> [2,3,4,5,7,9,8,15,6]
