package Newone;

import java.awt.AWTException;
import java.awt.Robot;
import java.awt.event.KeyEvent;

import org.openqa.selenium.By;
import org.openqa.selenium.JavascriptExecutor;
import org.openqa.selenium.Keys;
import org.openqa.selenium.WebDriver;
import org.openqa.selenium.WebElement;
import org.openqa.selenium.chrome.ChromeDriver;
import org.openqa.selenium.interactions.Actions;

public class LoginFitpeo {
public static void main(String[] args) throws AWTException, InterruptedException {
	WebDriver driver=new ChromeDriver();
	driver.get("https://fitpeo.com/");
	Thread.sleep(4000);
	driver.manage().window().maximize();
	driver.get("https://fitpeo.com/revenue-calculator");
	Thread.sleep(4000);
	Robot r=new Robot();
	r.keyPress(KeyEvent.VK_PAGE_DOWN);
	r.keyRelease(KeyEvent.VK_PAGE_DOWN);
	Thread.sleep(4000);
	WebElement sliderRight=driver.findElement(By.xpath("(//input[@max='2000'])[1]"));

	Actions act=new Actions(driver);
	act.dragAndDropBy(sliderRight,+94,0).perform();
	Thread.sleep(4000);
	WebElement e=driver.findElement(By.xpath("//input[@aria-invalid='false']"));
	e.sendKeys(Keys.CONTROL+"a");
	e.sendKeys(Keys.DELETE);
	driver.findElement(By.xpath("//input[@aria-invalid='false']")).sendKeys("560");
	Thread.sleep(4000);
	WebElement e1=driver.findElement(By.xpath("//input[@aria-invalid='false']"));
	e1.sendKeys(Keys.CONTROL+"a");
	e1.sendKeys(Keys.DELETE);
	driver.findElement(By.xpath("//input[@type='number']")).sendKeys("820");
	Thread.sleep(4000);
	r.keyPress(KeyEvent.VK_PAGE_DOWN);
	r.keyRelease(KeyEvent.VK_PAGE_DOWN);
	
	act.dragAndDropBy(sliderRight,+90,0).perform();
	r.keyPress(KeyEvent.VK_PAGE_DOWN);
	r.keyRelease(KeyEvent.VK_PAGE_DOWN);
	Thread.sleep(3000);
	driver.findElement(By.xpath("(//input[@class='PrivateSwitchBase-input css-1m9pwf3'])[1]")).click();
	Thread.sleep(3000);
	driver.findElement(By.xpath("(//input[@class='PrivateSwitchBase-input css-1m9pwf3'])[2]")).click();
	Thread.sleep(3000);
	driver.findElement(By.xpath("(//input[@class='PrivateSwitchBase-input css-1m9pwf3'])[3]")).click();
	Thread.sleep(3000);
	driver.findElement(By.xpath("(//input[@class='PrivateSwitchBase-input css-1m9pwf3'])[8]")).click();
	Thread.sleep(3000);
	
}
}
