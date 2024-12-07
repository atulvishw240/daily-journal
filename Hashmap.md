>Hashmap aka hashtable

Hashing involves taking an input and generating a corresponding output.
Pure function : always returns the same output for the same input.

>The key difference between Hashing and ciphering (encryption) is reversibility.

>[!question] Why hash code should be a number in the context of Hashmaps?
>This number will serve as the index to the bucket that will store the key value pair. Buckets are storage that we need to store our elements. (Simply, it's an array)

>A hash map does not guarantee insertion order when you iterate over it.

**Collision** : A collision occurs when two different keys generate the exact same hash code. Because they have the same hash code they will land in the same bucket.

>[!question] How using a prime number reduces collision?

