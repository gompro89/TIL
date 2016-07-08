#AccessControl
클래스, 함수, 열거형, 프로토콜 등의 접근을 제어

##private
###동일한 파일내에서만 접근가능
##internal
###동일한 프로젝트 및 모듈내에서만 접근가능
##public
###외부 프로젝트 및 묘듈에서 접근가능

## Tip!
1. 함수에 public 을 달고 싶을 때<br> 
ex)<br>
class DataManager: NSObject {<br>
	 public func example() {}<br>
	 <br>
 함수를 포함하고 있는 클래스에도 public 달아줘야한다.
ex)<br>
public class DataManager: NSObject {<br>
	 public func example() {}<br>