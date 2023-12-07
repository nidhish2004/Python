date = input(&quot;Enter the date to be checked: &quot;)
c=date.split(&quot;/&quot;)
b = list(map(int,c))
input_year=(b[2])
if(input_year%4 == 0):
if(input_year%100 == 0):
if(input_year%400 == 0):
print(&quot;%d is Leap Year&quot; %input_year)
else:
print(&quot;%d is not the Leap Year&quot; %input_year)
else:
print(&quot;%d is the Leap Year&quot; %input_year)
else:
print(&quot;%d is not the Leap Year&quot; %input_year)
x=input_year%4
if x!=0:
print(&quot;Previous Leap year:&quot;, input_year-x)
else:
print(&quot;Next leap year:&quot;, input_year+4)
