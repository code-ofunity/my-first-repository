# my-first-repository
maximumMark = 0
minimumMarks = 100
counter = 0
input classsize
loop counter from 1 to classsize
input studentmarks
if studentmarks > maximumMark then 
maximumMark = studentmarks
end if
if studentmarks < minimumMarks then
 minimumMarks = studentmarks
 end if
end loop
print minimumMarks
print maximumMark
