# Project---River-Kwai-Thai-Massage
Testing the functionality of River Kwai Thai Massage pages

package Pagefunctionality;

import java.util.concurrent.TimeUnit;

import org.openqa.selenium.By;
import org.openqa.selenium.WebDriver;
import org.openqa.selenium.chrome.ChromeDriver;

public class ThaiMassage {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		
	  System.setProperty("webdriver.chrome.driver", "C:\\Users\\user\\Downloads\\chromedriver_win32\\chromedriver.exe");
	  
	  WebDriver driver = new ChromeDriver();
      
	  driver.get("https://ueni.com/en-gb/business/london-e11/massage-salon/river-kwai-thai-massage");  
	  
	  driver.manage().timeouts().implicitlyWait(10, TimeUnit.SECONDS);   
	  
	       //Each page has been tested but the title needs to be fixed
	  
	  driver.findElement(By.cssSelector("#group-0 > div.cl1x0t-1-layout__Wrapper-fCnKct.jyYUZz > div")).click();
	  
	  //driver.findElement(By.cssSelector("#group-1 > div.cl1x0t-1-layout__Wrapper-fCnKct.jyYUZz > div")).click();
	  
	  //driver.findElement(By.cssSelector("#group-2 > div.cl1x0t-1-layout__Wrapper-fCnKct.jyYUZz > div")).click();
	  
	  //driver.findElement(By.cssSelector("#group-3 > div.cl1x0t-1-layout__Wrapper-fCnKct.jyYUZz > div")).click();
	  
	  //driver.findElement(By.cssSelector("#group-4 > div.cl1x0t-1-layout__Wrapper-fCnKct.jyYUZz > div")).click();
	  
	  //driver.findElement(By.cssSelector("#group-5 > div.cl1x0t-1-layout__Wrapper-fCnKct.jyYUZz > div")).click();
	  
	  //driver.findElement(By.cssSelector("#group-6 > div.cl1x0t-1-layout__Wrapper-fCnKct.jyYUZz > div")).click();
	  
	  //driver.findElement(By.cssSelector("#group-7 > div.cl1x0t-1-layout__Wrapper-fCnKct.jyYUZz > div")).click();
	  
	  //driver.findElement(By.cssSelector("#group-8 > div.cl1x0t-1-layout__Wrapper-fCnKct.jyYUZz > div")).click();
	  
	 //driver.findElement(By.cssSelector("#group-9 > div.cl1x0t-1-layout__Wrapper-fCnKct.jyYUZz > div")).click();
	  
	 //driver.findElement(By.cssSelector("#group-10 > div.cl1x0t-1-layout__Wrapper-fCnKct.jyYUZz > div")).click();
   }
}
