Thai Address Detection Tagging
Manual Matching with addresses file.
Making and Testing Solution, Flow of Algorithym on Colab Google
Get Text Sentence Address
|Clean text find and extract name, phone num 
|Tokenize with CustomTokenizer by PythaiNLP
|SpellChecker with Custom wordLists (BoW) by PythaiNLP
Matching Address with addresses file for Validation Data from word_lists
|Show result

```
Tokenize_
['อนงค์ลักษณ์', '9', '/56', 'ม.', '3', 'หมู่', 'บ้านนฤมลศิริ', 'ซอย', '2', 'ซ.', 'บุญศิริ', 'ถ', '.', 'สุขุมวิท', 'บางเมือง', 'เมืองสมุทรปราการ', 'สมุทรปนาการ', '10270', 'โทร', '.']
SpellChecker_
['อนงค์ลักษณ์', '9', '/56', 'ม.', '3', 'หมู่', 'บ้านนฤมลศิริ', 'ซอย', '2', 'ซ.', 'บุญศิริ', 'ถ', '.', 'สุขุมวิท', 'บางเมือง', 'เมืองสมุทรปราการ', 'สมุทรปราการ', '10270', 'โทร', '.']
Matching_
{'province': 'สมุทรปราการ', 'amphoe': 'เมืองสมุทรปราการ', 'district': 'บางเมือง', 'zipcode': '10270', 'name': '', 'phone': '0956029655'}
```
This program on time
- Tagging Word require province, amphoe, district, zipcode.
program Can't
- predict this address.
