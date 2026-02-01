# program-to-display-the-sum-of-n-numbers-using-a-list
numbers = []
num = int(input(&#39;How many numbers: &#39;))
for n in range(num):
x = int(input(&#39;Enter number &#39;))
numbers.append(x)
print(&quot;Sum of numbers in the given list is :&quot;, sum(numbers))
