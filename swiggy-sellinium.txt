package Proj;
import org.openga. selenium. By;
import org.openqa.selenium.WebDriver;
import org.openga.selenium. WebElement;
import org.openqa.selenium. chrome.Chrome Driver;
public class loginpage {
public static void main(String s[) {
WebDriver driver = new ChromeDriver0; System.setProperty("webdriver.chrome.driver","C://chromedriver.exe"); driver. get("https://www.swiggy.com/?utm source Google-
Sok&utmmedium CPC&utmcampaign=perffoodn ugooglesearchs o kn a r mbrandv 1 v2 march23 brand em&gclid CiwKCAjwYKjBhB5EiwAiFdSfrdLVA- UKWyVK60DxCwxHLKmh310fjK9ya mDXHMfbNSWaws1oQUvhoCNFsQAvD BwE");
WebElement textBox = driver.findElement(By.className("×4bK8"));
drivermanage().window().maximize(); 
textBox.click();
}
}
