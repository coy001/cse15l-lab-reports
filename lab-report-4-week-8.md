# **Lab Report 4**

[My Repository](https://github.com/coy001/MarkdownParse)

[Peer Repository](https://github.com/hsflores7/markdown-parser)

### **1.Test of Snipped 1**

    @Test
    public void snippedOneTest() throws IOException{ 
        Path fileName = Path.of("Snipped1.md");
        String content = Files.readString(fileName);
        ArrayList<String> links = MarkdownParse.getLinks(content);
        List<String> expected = List.of("url.com", "`google.com", "google.com", "ucsd.edu");
        assertEquals(expected, links);
    }
    
My Result:pass

Peer Result:

### **2.Test of Snipped 2**

      @Test
    public void snippedTwoTest() throws IOException{
        Path fileName = Path.of("Snipped2.md");
        String content = Files.readString(fileName);
        ArrayList<String> links = MarkdownParse.getLinks(content);
        List<String> expected = List.of("b.com", "example.com");
        assertEquals(expected, links);      
    }
    
My Result:expected:<[b.com, example.com]> but was:<[a.com(()), example.com]>

Peer Result:

### **3.Test of Snipped 3**

    @Test
    public void snippedThreeTest() throws IOException{
        Path fileName = Path.of("Snipped3.md");
        String content = Files.readString(fileName);
        ArrayList<String> links = MarkdownParse.getLinks(content);
        List<String> expected = List.of("https://sites.google.com/eng.ucsd.edu/cse-15l-spring-2022/schedule",
        "https://sites.google.com/eng.ucsd.edu/cse-15l-spring-2022/schedule",
        "https://cse.ucsd.edu/");
        assertEquals(expected, links);      
    }
    
 My Result:<[https://sites.google.com/eng.ucsd.edu/cse-15l-spring-2022/schedule, https://sites.google.com/eng.ucsd.edu/cse-15l-spring-2022/schedule, https://cse.ucsd.edu/]> but was:<[
https://sites.google.com/eng.ucsd.edu/cse-15l-spring-2022/schedule
, github.com

And there's still some more text after that.

[this link doesn't have a closing parenthesis for a while](https://cse.ucsd.edu/



]>
 
 Peer Result:

### **4.My Screenshot of Test**
![image](https://user-images.githubusercontent.com/103301184/170040406-173f5d08-8cfb-4403-8065-d840c6bfb301.png)

