# Entrega2-HPBBM
Seq=input("enter a DNA sequence:")
DNA=Seq.upper()
Symbol='AUCG'
Newcode='ATCG'
Trans=str.maketrans(Symbol,Newcode)
RealDNA=DNA.translate(Trans)
if 'U' in DNA:
    print('this is an RNA sequence')
    print('Translated RNA-DNA sequence:',RealDNA)
elif 'U' not in DNA:
    print('This is a DNA sequence')
print('end')
          
