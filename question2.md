# Student 2's Answer to Question 2

**Q2.** Please assign variables to the individual components of your favorite gene! (e.g. promoter, 5' UTR, start codon, exon1, intron, exon2, stop codon, 3' UTR). Print the entire gene by using the string concatenation operator, on the standard output! Note: Feel free to create a fictional gene sequence by randomly filling in the components.

**Answer**

```python
promoter = "TATAAAAGGCCTTAAG"
five_prime_UTR = "ACGTACGTAGCT"
start_codon = "ATG"
exon1 = "GCTAGCTAGCATCG"
intron = "GTAAGTCTAGCTAG"
exon2 = "CGTAGCTAGCTA"
stop_codon = "TGA"
three_prime_UTR = "AATAAAGCCTTA"

my_fav_gene = promoter + five_prime_UTR + start_codon + exon1 + intron + exon2 + stop_codon + three_prime_UTR

print("My favourite gene sequence is as follows:")
print(my_fav_gene)
