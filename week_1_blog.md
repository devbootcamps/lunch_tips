---
title: TLT: Always test your code!
---

OK, so we learned this week that we should always test our code. Sorry for breaking the checkout process, but the bug is fixed and new tests are in place to prevent this from happening. So [get your ticket][1] today!

Testing code is so important, we've included it in [the first level of our program][2]. But before being able to test your code, you need a basic comprehension of what _writing code_ actually means.

Writing code is cool, because it gives you a great power: telling a really
powerful machine to do exactly what you want it to do. And even better, watch
the machine do this faster and more precise than you could ever do, without
complaining, ever.

Yet, this powerful machine is fairly stupid. It speaks only one language and you need to be quite verbose and strict in the way you speak to it, in order to understand you. Not it compute otherwise does.

Wouldn't it be nice if the language you would need to talk to the computer would be very similar to the language you use with other humans? That's what [Yukihiro Matsumoto][3] (or Matz) thought when he created [Ruby][4]. At Development Bootcamp we will be using Ruby to teach you how to code, because Ruby is a very human-friendly language to write your code in.

For example, you say hello in Ruby using just this little bit of code:

```ruby
puts "Hello, world!"
```

Basically, you're telling the computer to _put_ a message `"Hello, world!"` on your screen. It uses the `puts` command to do so. (It nicely describes what it will do, doesn't it?)

Do you want to know which commands there are to use when talking to the computer? Or how to add two numbers? (I know, you've already got a calculator. But bear with me...)

Luckily, I've found some Japanese monks that will teach you all about Ruby. They've written an excellent primer on the Ruby Language. See it as a phrase book for entering the world of Ruby. After reading it, you won't be fluent in Ruby, but you'll sure now how two order a drink!

```
def can_i_have_a_cup_of?(beverage)
  return "Here's your #{beverage}. Enjoy!"
end

can_i_have_a_cup_of? 'tea'
```

[1]: https://www.developmentbootcamp.nl/tickets
[2]: https://developmentbootcamp.nl/program/level-1
[3]: https://en.wikipedia.org/wiki/Yukihiro_Matsumoto
[4]: https://www.ruby-lang.org/en/
[5]: https://rubymonk.com/learning/books/1-ruby-primer
