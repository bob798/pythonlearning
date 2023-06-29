
## beginOf or endOf
```
public static void main(String[] args) {  
System.out.println("beginOfMonth="+DateUtil.beginOfMonth(new Date()));  
System.out.println("endOfMonth="+DateUtil.endOfMonth(new Date()));  
System.out.println("beginOfDay="+DateUtil.beginOfDay(new Date()));  
System.out.println("endOfDay="+DateUtil.endOfDay(new Date()));  
}
```

output 
```
beginOfMonth=2023-06-01 00:00:00
endOfMonth=2023-06-30 23:59:59
beginOfDay=2023-06-27 00:00:00
endOfDay=2023-06-27 23:59:59

```