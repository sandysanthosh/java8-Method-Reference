# java8-Method-Reference

https://github.com/sandysanthosh/java8-Method-Reference.wiki.git


#### Flat Map:

```

public static void main(String[] args)
    {
  
        // Creating a List of Strings
        List<String> list = Arrays.asList("Geeks", "GFG",
                                 "GeeksforGeeks", "gfg");
  
        // Using Stream flatMap(Function mapper)
        list.stream().flatMap(str -> 
                         Stream.of(str.charAt(2))).
                         forEach(System.out::println);
    }
}

```

