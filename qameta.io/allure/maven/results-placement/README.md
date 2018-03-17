# Allure + maven + surefire combination places results outside of `target` directory

1. Run `mvn test`
2. Allure metadata will be placed in `./allure-results,` 
not `./target/allure-results`