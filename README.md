# Cipers

Repository which impliments a number of standard ciper for encryption of messages.

i) Implementation of the Rota13 Ciper algorithm. The ciper just move the characters of the Latin Alphabet 13 places, so the character 'a' shifts to 'n'. The rest characters are:

Sources a b c d e f g h i j k l m n o p q r s t u v w x y z

Imagine n o p q r s t u v w x y z a b c d e f g h i j k l m

The advantage here is that the encoding and decriptiopn are the same function.

ii) General Shift ciper, the same as ROTA13 except that the number of places the characters are shifted is given by the user.
Note that a further exscrption could be used by using either an alternative alphabet, orLatinwith additional characters. For examlpe spaces commas, need to shift to themselves, within the encoding message.

Extension:

There is many cipers detailed at:

http://www.crypto-it.net/eng/simple/index.html

Implementing these would provide practice and introduce more Python features.
