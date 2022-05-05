class Stack{
	int arr[]= new int[10];
	int top1=-1;
	int top2=10;
	
	void push1(int data){
		if(top1 < top2-1){
			top1++;
			arr[top1]=data;
		}else{
			System.out.println("stack is full");
		}
	}
	
	void push2(int data){
		if(top1 > top2-1){
			top2--;
			arr[top2]=data;
		}else{
			System.out.println("stack is full");
		}
	}
	
	void pop1(){
		if(top1 >= 0){
			int popped = arr[top1];
			top1--;
			System.out.println("popped from stack1"+popped);
		}else{
			System.out.println("stack is empty");
		}
	}
	
	void pop2(){
		if(top2 < 10){
			int popped = arr[top2];
			top2--;
			System.out.println("popped from stack1"+popped);
		}else{
			System.out.println("stack is empty");
		}
	}
	
	void displaystack1(){
		int i;
		for(i=top1;i>=0;--i){
			System.out.println(arr[i]);
		}
	}
	
	void displaystack2(){
		int i;
		for(i=top2;i<10;++i){
			System.out.println(arr[i]);
		}
	}
	
	public static void main(String[] args){
		Stack sc= new Stack();
		sc.push1(5);
		sc.push2(10);
		sc.push2(15);
		sc.push1(11);
		sc.push2(7);
		sc.push2(40);
		
		
		sc.displaystack1();
		sc.displaystack2();
		sc.pop1(11);
		sc.pop2(40);
	}
}