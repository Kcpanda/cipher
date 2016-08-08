# cipher

puts"You want to shift by how many position"
n=5

a="what a string!"

j=" "
x=a.length
new=String.new
for i in 0...x do
        if(a[i].ord>=97 && a[i].ord<=122-n) then
                j=(a[i].ord+n).chr
                        elsif(a[i].ord>122-n)
                                j=(a[i].ord+n-26).chr
                                        else
                                                j=a[i]
                                                        end

                                                        new.insert( i,j)
                                                        end
                                                        puts new

