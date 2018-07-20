Add your answers to the Algorithms exercises here.

Exercise 1:

- A:   O(n)

- B : O(log n)

- C: O(sqrt(n))

- D:  O(n(log n)) 

- E: O(n^3)

- F: O(n)

- G: O(n)

Exercise 2:

- A: function maxDiff(arr) {
    let max = 0;

    for(let i = 0; i < arr.length; i++) {
        if(arr[i] > max) {
            max = arr[i];
        }
    }

    return max;
}


- B: function minEggBreak(eggs, story) {
    let break = true;
    let safe = true;
    let floorBroken = 0;
    for(let i = 0; i < story.length; i++) {
        if(eggs[eggs.length-1] === safe) {
            continue;
        }

        else {
            floorBroken = story[i]
        }
    }

    return floorBroken
}



Exercise 3: 

- A: O(n) since array is sorted and only has to run through it once

- B: O(n(log n)) because the array is split in half for each step