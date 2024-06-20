# data-faker-notes
Notes for Data Faker

The java-faker library is a powerful and flexible solution for generating random data in Java applications. With its support for basic data types, enums, nullable data, collections, and custom classes, you can easily generate realistic test data for your unit tests, mock data for demos, and more.

# Options class is used to customized the randomness you want to generate

# FakeValueService provides
## Numerify
- Generates random number

## Letrify
- Generates random string

## Regexify
- Generstes random string based on supplied regex

## Brotify
- Generates both number and string
  - With ? for String
  - With # for number

## Other useful methods
faker.expression("#{//code}")
faker.collections()
faker.stream()

# Related Links
[Documentation](https://www.datafaker.net/documentation/providers/)
[Github Repo](https://github.com/datafaker-net/datafaker/)
