# bigint
JavaScript's BigInt is a built-in object that provides a way to represent whole numbers larger than the maximum safe integer (Number.MAX_SAFE_INTEGER). This allows you to perform arithmetic operations on large integers without losing precision. BigInt was introduced to JavaScript to handle cases where the precision of large numbers is crucial.

Creating BigInt
You can create a BigInt by appending n to the end of an integer literal or by using the BigInt constructor.

// Using the 'n' suffix
const bigIntLiteral = 1234567890123456789012345678901234567890n;

// Using the BigInt constructor
const bigIntConstructor = BigInt("1234567890123456789012345678901234567890");
