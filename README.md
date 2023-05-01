Download Link: https://assignmentchef.com/product/solved-cecs328-ec4
<br>
<strong>Extra Credit 4. </strong>




Sort a given random array of <em>n </em>numbers where each element is at most <em>k</em> index away from its position in the sorted array.   (Hint: You could make <u>min/max heaps</u> using the first <em>k+1</em> numbers and then 1- delete the root <em>once</em> 2- add the next element to the heap 3-Repeat 1 and 2 until you cover all the elements. The time complexity of your solution should be <em><u>O(nlogk)</u></em>.)

<em><u>Example 1</u></em>: <u>Input:</u> a = [2, 8, 0, 17, 5, 12] , k = 2,

(Hint: a number at index <em>4</em> in our sorted array, can be located in <em>2, 3, 4, 5, 6</em> indices in the given array.) <em><u>Output</u></em>: [0 2 5 8 12 17]




<img decoding="async" data-recalc-dims="1" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2021/10/193.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

 <noscript>

  <img decoding="async" src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2021/10/193.png?w=980&amp;ssl=1" data-recalc-dims="1">

 </noscript>