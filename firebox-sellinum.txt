import org.openqa.selenium. WeDriver;
import org.openqaselenium. firefox. FirefoxDriver;
public class SeleniumExample {
public static void main(String[] args) {
I Set the path to the geckodriver executable System.setProperty"webdriver. gecko.driver", "(path/to/geckodriver");
// Create a new instance of the Firefox driver WebDriver driver= new FirefoxDriver;
// Navigate to Google
driver. get("https://www.google.com");
// Close the browser 
driver.quit();
}
}
