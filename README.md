public class Main
{
  public static void main(String[] args)
  {
      String name = "Lestroboy";
      System.out.println("1." + name);
      
      int len = name.length();
      System.out.println("2." + len);
      
      String lstr = name.toLowerCase();
      System.out.println("3." + lstr);
      
      String ustr = name.toUpperCase();
      System.out.println("4." + ustr);
      
      String nonTrimmedString = "   Lestroboy   ";
      System.out.println("5." + nonTrimmedString);
      
      String trimmedString = nonTrimmedString.trim();
      System.out.println("6." + trimmedString);
      
      System.out.println("7." + name.substring(1));
      System.out.println("8." + name.substring(5));
      
      System.out.println("9." + name.replace('L', 'H'));
      System.out.println("10." + name.replace("L", "Gun"));
      
      
      System.out.println("11." + name.startsWith("L"));
      System.out.println("12." + name.endsWith("Y"));
      
  }
}
