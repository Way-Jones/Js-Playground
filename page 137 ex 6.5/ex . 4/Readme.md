<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <script>
        let value = '1000';
        console.log(value); 
        let setValue = function(newValue) {
  let value = newValue;
  console.log(`The value is now ${value}.`);
};
setValue('4000');
console.log(value); // Output: 1000


</script>
</body>
</html>