---
title: Checkouts By Title (Physical Items)
created: '2020-11-10T16:59:03.472198'
modified: '2020-12-04T19:18:40.014621'
state: active
type: dataset
tags:
  - Checkout
  - Circulation
  - Seattle Public Library
  - Spl
groups:
  - Local Government
csv_url: 'https://data.seattle.gov/api/views/5src-czff/rows.csv?accessType=DOWNLOAD'
json_url: 'https://data.seattle.gov/api/views/5src-czff/rows.json?accessType=DOWNLOAD'
layout: post

---
This dataset includes a log of all physical item checkouts from Seattle Public Library. The dataset begins with checkouts that occurring in April 2005.  Renewals are not included. Have a question about this data? Ask us!

Data Notes:
There is a machine-readable data dictionary available to help you understand the collection and item codes. Access from here:

https://data.seattle.gov/Community/Integrated-Library-System-ILS-Data-Dictionary/pbt3-ytbc

Also:
1. "CheckoutDateTime" (the timestamp field) is rounded to the nearest minute.
2. "itemType" is a code from the catalog record that describes the type of item. Some of the more common codes are: acbk (adult book), acdvd (adult DVD), jcbk (children's book), accd (adult CD)
3. "Collection" is a collection code  from the catalog record which describes the item. Here are some common examples: nanf (adult non-fiction), nafic(adult fiction), ncpic(children's picture book),  nycomic (Young adult comic books).
4. "Subjects" includes the subjects and subject subdivisions from the item record.
