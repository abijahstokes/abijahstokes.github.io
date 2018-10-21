---
layout: post
title:      "Looping vs. Iteration"
date:       2018-10-21 11:02:43 +0000
permalink:  looping_vs_iteration
---

I recently had to learn what I thought was a quite complex concept in Ruby. I was able to use them in lessons which helped me understand them better, but I thought they would be a great topic to write about since somewhere out there that is coming across this concept for the first time might find this post as a relief.

Looping Vs. Iteration (I will talk about Enumerators later :) In Ruby, there are four loop types and they all have distinct characteristics; loop, times, while, and until. Looping allows us to create a program to do something a certain amount of times until a certain condition is met. However, iteration can operate over each element within an array.

Have you ever heard of the phrase, K.I.S.S.? Keep it simple, stupid, which is apparently a programmer's motto. So we have to avoid super verbose codes that could be written in a much simpler way.

What is an example of a Loop being used?

5.times do
   puts "I love green eggs and ham"
end
This is the times loop, and it will print this string 5 times.

Iterators are for more complex situations where you want to run a condition over an entire array. Each is an iterator. This is an example of each being used:

cats = ["Fluffy", "Mac", "Oscar"]
   cats.each do |cat|
        puts " Come to get your food {#cats}!"
    end
This will print out each cat's name in the array individually. How cool is that?
