#                        Những Điểm Mới Trong Java 8

## Mục Lục:
+ [Functional Interfaces](https://github.com/trantronghienit/Java8/tree/master#functional-interfaces)
+ [Lambda Expressions](https://github.com/trantronghienit/Java8/tree/master#lambda-expressions)
+ [Method References](https://github.com/trantronghienit/Java8/tree/master#method-references)
+ [Default Methods](https://github.com/trantronghienit/Java8/tree/master#default-methods)
+ [Streams](https://github.com/trantronghienit/Java8/tree/master#streams)
+ [Optional Class](https://github.com/trantronghienit/Java8/tree/master#optional-class)
+ [Nashorn JavaScript](https://github.com/trantronghienit/Java8/tree/master#nashorn-javascript)
+ [New Date/Time API](https://github.com/trantronghienit/Java8/tree/master#new-datetime-api)
+ [Base64](https://github.com/trantronghienit/Java8/tree/master#base64)

## Functional Interfaces
  ### Functional Interfaces là gì ?
+ là 1 annotation đánh dấu rằng Interface đó chỉ có duy nhất 1 hàm trừa tượng , nếu cố ý đặt annotation @FunctionalInterface nhưng  lại cố ý khai báo 2 phương thức trừu tượng java sẽ báo lỗi 
### Cách dùng 
  
```
@FunctionalInterface
public interface Foo {
  void something();
  default void defaultMethod() {
      System.out.println("..");
  }
}
```

### dùng để làm gì ?
+ đánh dấu và ràng buộc chỉ 1 phương thức trừu tượng trong Interface , 

-------------------------------------------------------------------------

## Lambda Expressions

-------------------------------------------------------------------------
## Method References

## Default Methods

## Streams

## Optional Class

## Nashorn JavaScript

## New Date/Time API

## Base64
