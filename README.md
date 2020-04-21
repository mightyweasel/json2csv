# json2csv
Basic Nested JSON to CSV

Simple hacked together converter to take nested JSONs and unroll them into rows with repeating data for use in excel.

Hasn't been generalized to work with all input JSON, but should handle [0].a.b[0].c.d style nesting as well as [0].a flat

NOTE: Probably has edge cases that need to be covered. This was put together after an evening of tinkering.