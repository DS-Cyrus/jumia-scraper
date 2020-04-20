# Jumia Scraper
This is a scraper to extract product data from Jumia eCommerce site (jumia.co.ke)

## About Jumia Scraper
This a scraper that allows you to scrape product links from the top selling division of https://jumia.co.ke homepage, follow the links and scrape for product data from all these product links. This data can then be used to determine popularity of a product and make recommendations to sellers about the sort of products they should be selling.

Here is the product data that this scraper will collect:
- Product Name
- Brand Name
- Price (Ksh)
- Discount if Available (%)
- Total Number of Reviews
- The Product Rating (out of 5)

*Note* that we make certain assumptions to deduce insights from our product data:
1. Number of reviews correlates directly to the number of product purchases. This data point will help us determine the popularity of a particular product.
2. The product rating does not depict the actual customer satisfaction given the disparity in review count. Therefore, we add one negative and one positive review to better estaimate the customer satisfaction from a product (the more accurate product rating)

# Contributors
This project was done by Cyril Michino (Founder at Chaptr Global)

# License
MIT License: Copyright (c) 2019 Chaptr Education Inc.

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
