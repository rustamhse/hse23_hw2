# Домашнее задание 2
###### Анализ ChIP-Seq данных. Определение участков генома с наличием гистоновых модификаций.
###### Зиёев Рустам Группа 3

## FASTQC



1) ENCFF963ONJ

Measure | Value 
 --- | --- 
Filename | ENCFF963ONJ.fastq
File type | Conventional base calls
Encoding | Sanger / Illumina 1.9
Total Sequences | 44180706
Sequences flagged as poor quality | 0
Sequence length | 50
%GC | 44

<img width="569" alt="ENCFF963ONJ" src="https://user-images.githubusercontent.com/74643940/229348533-33f6eff5-4b72-47cb-8776-e31293aa84d2.PNG">



2) ENCFF686GPG

Measure | Value 
 --- | --- 
Filename | ENCFF686GPG.fastq
File type | Conventional base calls
Encoding | Sanger / Illumina 1.9
Total Sequences | 61063748
Sequences flagged as poor quality | 0
Sequence length | 50
%GC | 42

<img width="569" alt="ENCFF686GPG" src="https://user-images.githubusercontent.com/74643940/229348543-1a4f8f9f-5b1a-4899-b747-c97204099a2f.PNG">



3) ENCFF259JCU - КОНТРОЛЬ

Measure | Value 
 --- | --- 
Filename | ENCFF259JCU.fastq
File type | Conventional base calls
Encoding | Sanger / Illumina 1.9
Total Sequences | 88755850
Sequences flagged as poor quality | 0
Sequence length | 50
%GC | 41

<img width="569" alt="ENCFF259JCU" src="https://user-images.githubusercontent.com/74643940/229348550-8216df24-7536-474e-a8fc-c6146d24422e.PNG">



## Числовые показатели выравнивания

|Name|Total reads|Unpaired reads|Uniquely aligned|Aligned multiple times|
|---|---|---|---|---|
|ENCFF963ONJ|44180706|34638369 \(78\.40%\)|1976087 \(4\.47%\)|7566250 \(17\.13%\)|
|ENCFF686GPG|61063748|49326593 \(80\.78%\)|2700739 \(4\.42%\)|9036416 \(14\.80%\)|
|ENCFF259JCU|88755850|73247706 \(82\.53%\)|3855931 \(4\.34%\)|11652213 \(13\.13%\)|

###### (?) Процент выравниваний был бы гораздо больше, если бы не условие выравнивания исключительно по одной хромосоме.



## Диаграммы Венна

![Intervene_venn (2)-1](https://user-images.githubusercontent.com/74643940/229349201-251cfbe4-35c1-4e0e-ab3f-ef49378357de.png)
![Intervene_venn (1)-1](https://user-images.githubusercontent.com/74643940/229349203-e9e412f4-a9cb-4cfb-8caf-c340f6ad9cc0.png)
![Intervene_venn-1](https://user-images.githubusercontent.com/74643940/229349205-b9ef44e9-cbcb-4046-994a-63419db25cd8.png)
![Intervene_venn (3)-1](https://user-images.githubusercontent.com/74643940/229349206-3a3aaa8c-0f5d-4c3f-a58a-e1bce6d86153.png)

###### Пересечений с результатами с сайта ENCODE сравнительно мало, опять же ввиду выравнивания на одну хромосому.


