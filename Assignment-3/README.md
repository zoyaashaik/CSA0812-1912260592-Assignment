# CSA0812-1912260592-Assignment3

**Name:** Zoyaa Shaik  **Register No.:** 1912260592
**Python version:** 3.15.2  **Libraries:** standard library only (see requirements.txt)

| Task | Command | Result note |
|------|---------|-------------|
| Q1 | `python Q1/q1_rainfall.py` | Slicing for weekly totals; running-sum moving average does about 2n-7 operations versus 7(n-6) for the naive one. |
| Q2 | `python Q2/q2_tuples.py` | `[[0]*cols]*rows` shares one row; list comprehension fixes it. Shallow vs deep copy shown with `is` and `id()`. |
| Q3 | `python Q3/q3_complaints.py` | Dictionary counting is about 10x faster than `list.count()` at 100,000 complaints; Counter is the same order as the dictionary loop. |
| Q4 | `python Q4/q4_electives.py` and `python Q4/q4_venn.py` (then open venn.svg in a browser) | Clash/one/neither with set operators; set membership is thousands of times faster than a list. |
| Q5 | `python Q5/q5_sensors.py` | for-append, list comprehension and map/filter give identical results; the generator saves memory, not time. |
| Q6 | `python Q6/q6_timetable.py` | Station index answers queries faster at the cost of extra memory. |
| Q7 | `python Q7/q7_contacts.py` | Contact merge with a dictionary and union-find is linear; pairwise comparison is quadratic. |
