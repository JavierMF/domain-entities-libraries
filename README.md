# Libraries for DDD data types
DDD encourages using Entities and Value Objects to model our bussiness concepts. Wen we develop several projects applying DDD (or even in our first project) we will probably create Entities and Value Objects that have already been  modeled in many other projects. This is an error-prone practice since we will probably forget corner cases or add bugs that have already been faced in open-source libraries. This project is just a recap of libraries in different languages that represent common concepts so we can use as them as data types for our Entities or Value Objects.

PRs with new libraries are very wellcome!

## Money, banking, buying

### Money
 - Java: https://github.com/JodaOrg/joda-money
 - Java: https://javamoney.github.io/  Java Money & Currency JSR
 - PHP: https://github.com/moneyphp/money
 - Ruby: https://github.com/RubyMoney/money 
 - Python: https://pypi.org/project/money/ 
 - Python: https://github.com/vimeo/py-money 
 - Kotlin/Android: https://github.com/tobiasschuerg/android-money
 - Javascript: https://currency.js.org/
 - Javascript: https://github.com/davidkalosi/js-money

### Price

### CreditCardNumber
  - Javascript: https://github.com/braintree/credit-card-type

### CreditCardInfo (number + name + expiration date + cvv/cvc)
  - Java: https://github.com/sualeh/creditcardnumber

### IBAN
  - Java: https://github.com/arturmkrtchyan/iban4j
  - Java: https://github.com/barend/java-iban
  - Multiple: https://rosettacode.org/wiki/IBAN
  - Javascript: https://github.com/arhs/iban.js
  - Javascript: https://github.com/koblas/ibankit-js
  - Go: https://github.com/almerlucke/go-iban
  - Go: https://github.com/go-pascal/iban

### ShoppingCart

## Books and other publications

### ISBN
  - Ruby: https://github.com/tkersey/isbn
  - PHP: https://github.com/Fale/isbn
  - PHP: https://github.com/biblys/isbn
  - PHP: https://github.com/rebuy-de/ean-isbn-library
  - Java: https://commons.apache.org/proper/commons-validator/apidocs/org/apache/commons/validator/routines/ISBNValidator.html

### PublishedResource

### Name

### Author

### OnlineResource


## Contact info

### PhoneNumber
 - Java, C++, Javascript: https://github.com/google/libphonenumber
 - Many languages: https://github.com/google/libphonenumber#third-party-ports

### EmailAddress

### Website


## Documents

### PassportId

### DNI (Spain)

### NIE (Spain)

### SSNumber

## Time

### Timestamp, TimePeriod, WeekDay, Year, Seconds
  - Java: https://docs.oracle.com/javase/8/docs/api/java/time/package-summary.html
  - Java: https://www.joda.org/joda-time/
  - Java: http://www.date4j.net/
  - Java: https://github.com/MenoData/Time4J
  - Kotlin: https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.time/
  - Kotlin: https://github.com/debop/koda-time
  - Kotlin: https://github.com/korlibs/klock
  - Kotlin: https://github.com/Kotlin/kotlinx-datetime
  - PHP: https://www.php.net/manual/en/refs.calendar.php
  - PHP: https://github.com/brick/date-time
  - PHP: https://carbon.nesbot.com/
  - PHP: https://period.thephpleague.com/
  - PHP: https://aeon-php.org/


## Person

### Sex

### Age

### BirthDay

### Nationality



## Physical Dimension

### Height/Width

### Distance



## Physical Location

### Address

### Latitude/Longitude

### Coordinates

### Country


## Other

### URL

### UserName

### IPAddress
  - Java: https://seancfoley.github.io/IPAddress/
  - Java: https://guava.dev/releases/20.0/api/docs/com/google/common/net/InetAddresses.html
  - Java: https://commons.apache.org/proper/commons-validator/apidocs/org/apache/commons/validator/routines/InetAddressValidator.html
  - Python: https://docs.python.org/3/library/ipaddress.html
  - PHP: https://github.com/mlocati/ip-lib
  - PHP: https://github.com/S1lentium/IPToolse

### SemVer
  - Kotlin: https://github.com/swiftzer/semver
  - Kotlin: https://github.com/glwithu06/Semver.kt
  - Java: https://github.com/vdurmont/semver4j
  - Java: https://github.com/zafarkhaja/jsemver
  - Java: https://github.com/jlindsey/java-semver
  - PHP: https://github.com/vierbergenlars/php-semver
  - PHP: https://github.com/composer/semver
  - PHP: https://github.com/naneau/semver

### Quantity

### Language

### HexColor


