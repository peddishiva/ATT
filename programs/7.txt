package selenium;

import org.openqa.selenium.By;
import org.openqa.selenium.Keys;
import org.openqa.selenium.WebDriver;
import org.openqa.selenium.WebElement;
import org.openqa.selenium.chrome.ChromeDriver;

public class week7 {
	public static void main(String args[]) throws InterruptedException{
		System.setProperty("webdriver.chromedriver", "C:\\Users\\student\\Downloads\\chromedriver-win64 (7).zip\\chromedriver-win64");
		WebDriver driver=new ChromeDriver();
		driver.get("https://google.com");
		 Thread.sleep(2000);
		 WebElement searchBar= driver.findElement(By.name("q"));
		 searchBar.sendKeys("cmrit hyderabad");
		 searchBar.sendKeys(Keys.ENTER);
		 Thread.sleep(15000);
		 driver.quit();
	}
}