
# Crypto Seminar, Winter 2022 

This course is officially "CMSC 33251-1: Topics in Computer Security". It is
a PhD-level seminar aimed at covering a few research topics in preparation for
dong research in those areas.

This quarter the seminar is about *obliviously accessing data*. We'll take a
broad look at research on how to efficiently access data at untrusted server
while preserving as much privacy as possible. 

Two topics of initial focus will be *private information retrieval (PIR)* and
*oblivious RAM (ORAM)*. I will give some background lectures on both of these
topics, starting with some older papers. Then we'll move on to more recent
papers together, in search of open problems. We can investigate both applied
and theoretical directions, depending on the group's interests.

**Logistics**: 

- Meetings are Mon-Weds at 1:30-2:50pm in Ryerson 277 (this location may change
  to a conference room after the first meeting). 

- This GitHub repo will serve as our course website.

- This course will not count as an elective. If you need elective credit,
  please speak with me.

**Expected participation**: There are two main expectations. First,
participants in the seminar should attend all 18 meetings, attempt associated
readings beforehand, and be generally prepared to follow the technical content
with questions.  Second, participants will be asked to do a close read on one
topic and lead (or co-lead) at least one meeting on that topic.

## Meeting Schedule

| Meeting | Date | Topic | Paper(s) | Lead by |
| --- | --- | --- | --- | --- |
| **M** (Wk 1) | Mar 28 | Intro to PIR Pt 1 | [CGKS'95](https://madhu.seas.harvard.edu/papers/1995/pir-journ.pdf) | David |
| **W** (Wk 1) | Mar 30 | Intro to PIR Pt 2 | [Ambainis'97](http://citeseerx.ist.psu.edu/viewdoc/download;jsessionid=04CBB5535797D855D0FAE7C8D686DB6B?doi=10.1.1.21.4449&rep=rep1&type=pdf), [BI'01](https://www.cs.bgu.ac.il/~beimel/Papers/BI.pdf), [BIM'00](https://www.cs.bgu.ac.il/~beimel/Papers/BIM.pdf) | David |

| **M** (Wk 2) | Apr 4 | Batch Codes and PIR | [IKOS'04](http://web.cs.ucla.edu/~rafail/PUBLIC/62.pdf) | David |
| **W** (Wk 2) | Apr 6 | PIR and LDCs | [BIKR'02](https://www.cs.bgu.ac.il/~beimel/Papers/BIKRJournal.pdf) | David |

| **M** (Wk 3) | Apr 11 | Offline/Online PIR | [CK'20](https://eprint.iacr.org/2019/1075.pdf), [CHK'22](https://eprint.iacr.org/2022/081)| David |



## Potential Papers to be Covered [updated]

### Private Information Retrieval (PIR)

#### Information-Theoretic PIR - Classic Papers

- [Private Information
  Retrieval](https://madhu.seas.harvard.edu/papers/1995/pir-journ.pdf). B.
  Chor, O. Goldreich, E. Kushilevitz, M. Sudan. FOCS 1995/JACM 1999.

- [Upper bound on the communication complexity of private information
  retrieval](http://citeseerx.ist.psu.edu/viewdoc/download;jsessionid=04CBB5535797D855D0FAE7C8D686DB6B?doi=10.1.1.21.4449&rep=rep1&type=pdf). A. Ambainis, ICALP 1997.

- [Information-Theoretic Private Information Retrieval: A Unified
  Construction](https://www.cs.bgu.ac.il/~beimel/Papers/BI.pdf). A. Beimel, .Y
  Ishai. ICALP 2001.

- [Breaking the O(n1/(2k-1)) Barrier for Information-Theoretic Private
  Information
  Retrieval](https://www.cs.bgu.ac.il/~beimel/Papers/BIKRJournal.pdf). Beimel†
  Y. Ishai, E. Kushilevitz, J. Raymond. FOCS 2002.

- [Batch Codes and Their
  Applications](http://web.cs.ucla.edu/~rafail/PUBLIC/62.pdf).  Y. Ishai, E.
  Kushilevitz, R. Ostrovsky, A. Sahai. STOC 2004.

- 


#### Function Secret Sharing

- [Function Secret
  Sharing](https://link.springer.com/chapter/10.1007/978-3-662-46803-6_12). E.
  Boyle, N. Gilboa, Y. Ishai. EUROCRYPT 2015.

- [Function Secret Sharing: Improvements and
  Extensions](https://eprint.iacr.org/2018/707). E. Boyle, N. Gilboa, Y. Ishai.
  CCS 2016.


#### Offline/Online PIR and PIR-with-Preprocessing

- [Reducing the Servers’ Computation in Private Information
Retrieval: PIR with Preprocessing](https://www.cs.bgu.ac.il/~beimel/Papers/BIM.pdf). A. Beimel, Y. Ishai, T. Malkin. CRYPTO 2000.

- [Private Information Retrieval with Sublinear Online
  Time](https://eprint.iacr.org/2019/1075.pdf). H. Corrigan-Gibbs, D. Kogan.
  EUROCRYPT 2020.

- [Limits of Preprocessing for Single-Server PIR](https://eprint.iacr.org/2022/235). G. Persiano, K. Yeo. SODA 2022.

- [Puncturable Pseudorandom Sets and Private Information Retrieval with
  Near-Optimal Online Bandwidth and Time](https://eprint.iacr.org/2020/1592).
  E. Shi, W. Aqeel, B. Chandrasekaran, Bruce Maggs. CRYPTO 2021.

- [Single-Server Private Information Retrieval with Sublinear Amortized
  Time](https://eprint.iacr.org/2022/081). H. Corrigan-Gibbs and A.
  Henzinger and D. Kogan. EUROCRYPT 2022.

### Single-Server PIR

- [A Survey of Single-Database Private Information Retrieval: Techniques and
  Applications](https://eprint.iacr.org/2007/059.pdf).  R. Ostrovsky, W. E.
  Skeith III. PKC 2007.

- [Towards Doubly Efficient Private Information
  Retrieval](https://eprint.iacr.org/2017/568).  R. Canetti, J.  Holmgren, S.
  Richelson. TCC 2017.

- [Can We Access a Database Both Locally and
  Privately?](https://eprint.iacr.org/2017/567). E. Boyle, Y. Ishai, R. Pass,
  M. Wootters.  TCC 2017.
 
### ORAM - Classic Papers [todo]

- GO


- [Path ORAM: An Extremely Simple Oblivious RAM
  Protocol](https://eprint.iacr.org/2013/280.pdf).  E. Stefanov, M.  van Dijk,
  E. Shi, T-H. H. Chan, C. Fletcher, L. Ren, X. Yu, S. Devadas. CCS 2013/JACM
  2018.


  

- Panorama

- OPRAM


