# BankAccount
A simple program to understand about Encapsulation

class BankAccount{
	private double balance = 15000;
	
	public double getBalance(){
		return balance;
	}
	public void setBalance(double money){
		if(money >0){
			balance = money;
		}
		else{
			System.out.println("Invaild Amount");
		}
	}
}
public class Ssss{
	public static void main(String[] args){
		BankAccount acc = new BankAccount();
		System.out.println("Current Balance "+acc.getBalance());
		acc.setBalance(23000);
		System.out.println("Updated Account "+acc.getBalance());
		acc.setBalance(-12349);
	
	}
}
