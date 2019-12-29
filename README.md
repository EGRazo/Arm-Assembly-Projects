# Arm-Assembly-Projects
Projects written in both Arm and C
(Spring 2019 project)

Notes for future purposes:

This is a highly inefficienct way of implementing the Selection Sort in Arm

  In C the selection sort requires two loops, one to compare all elements of the array to a certain element, and the other to change the element being compared too.
  
  In this Arm implementation, I changed the first loop to every single index of the array is being compared to the selected element, even though that element may have already been compared to the other elements. This is inefficient, and in future iterations it should be removed.
