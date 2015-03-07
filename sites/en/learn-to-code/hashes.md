<!-- next_step "functions" -->

# Hashes

* `Hash` is a built-in type
  * aka Map, Dictionary, Associative Array
  * aka key-value pair, attribute-value pair, field-value pair
* Similar to an array where the index can be *anything*, not just a number


## What makes a hash a hash

Like an array...

* You can put any objects inside it
* In any order
* They stay in order

... but with some extra, specialness for assosciating _keys_ and _values_.

* Keys (aka indexes) can be any object
* Values can be any object
* Duplicate _values_ are fine
  * Objects with duplicate _keys_ will be ignored, except for the last pair

## Creating a hash

A simple hash.

    {"AZ" => "Arizona", "CA"=> "California", "DE" => "Delaware"}

This hash uses the state abbreviation as the key. In this example, the keys are String 
objects. Hash keys can be other object types, but for now we will stick with strings.   

# Hash Indexes

* Every pair in the hash has a _key_ and a _value_
* Every _key_ is an object (our examples shows a String key)
* You can retrieve an item _value_ with its _key_

# Hash Indexes Exercise

Try this in IRB:

    states = {"AZ" => "Arizona", "CA"=> "California", "DE" => "Delaware"}

Can you retrieve hash items the same way you do arrays?  Give it a try.

    states[0]

Did you get the results you were expecting?  Why or why not?

Now, try it with the state abbreviation:

    states["AZ"]

How did that work out?

# TODO: 

* examples
* labs


