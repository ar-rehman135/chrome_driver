# chrome_driver
chrome driver
            var chromeOptions = new ChromeOptions();
            chromeOptions.AddArguments("headless");
            var chromeDriverService = ChromeDriverService.CreateDefaultService();
//            chromeDriverService.HideCommandPromptWindow = true;
            var browser = new ChromeDriver(chromeDriverService,chromeOptions);
