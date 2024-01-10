## Course Information
- **Lectures**: MWF 3:00 pm - 3:50 pm
- **Location**: 2101 Everitt Laboratory
- **Instructor**: Prof. [Yupeng Zhang](https://zhangyp.web.illinois.edu/) zhangyp@illinois.edu
- **Office Hour**: TBD
- **TA**: [Sourav Das](https://sourav1547.github.io/) souravd2@illinois.edu

## Course Description and Prerequisites

Cryptography uses mathematical algorithms and protocols to ensure the confidentiality, integrity, and authenticity of information. Today, cryptographic principles and systems form an integral part of almost all online activity. This course is an introduction to the fundamentals of modern cryptography. You will learn about cryptograhy’s formal approach to security. You will learn about cryptographic primitives, and you will learn how those primitives can be used.

This webpage serves as the course syllabus, and it will be edited throughout the semester to release resources.



## Textbook and Resource Materials

- Mike Rosulek’s [The Joy of Cryptography](https://joyofcryptography.com/) is an excellent, albeit unfinished, free resource.

- Jonathan Katz’s and and Yehuda Lindell’s “Introduction to Modern Cryptography” is a more complete reference.

- Dan Boneh’s and Victor Shoup’s [A Graduate Course in Applied Cryptography](https://crypto.stanford.edu/~dabo/cryptobook/BonehShoup_0_4.pdf) is an additional resource.

## Links

**Assignments and Gradebook:** https://canvas.illinois.edu/

**Piazza:** https://piazza.com/


## Schedule (tentative)



<table style="width: 110%">
    <tr>
        <th style="width: 15%;">Date</th>
        <th style="width: 40%;">Topic</th>
        <th style="width: 35%;">Readings</th>
        <th style="width: 20%;">Deadline</th>
    </tr>
    <tr>
        <th>Week 1</th>
        <th>Introduction and logitics, background on Cryptography</th>
        <th></th>
        <th></th>
    </tr>
    <tr>
        <th>Week 1</th>
        <th>Introduction to verifiable computation and zero-knowledge proof</th>
        <th>
            <a href="https://people.eecs.berkeley.edu/~raluca/cs261-f15/readings/merkle.pdf">Merkle Hash Tree</a>
        </th>
        <th></th>
    </tr>
    <tr>
        <th>Week 2</th>
        <th>Introduction to blockchain and cryptocurrency</th>
        <th>
        <a href="https://bitcoin.org/bitcoin.pdf">Bitcoin</a>
        </th>
        <th></th>
    </tr>
    <tr>
        <th>Week 2</th>
        <th>Pricacy-preserving crypto-currencies</th>
        <th>
            <ul>
            <li><a href="https://cseweb.ucsd.edu/~smeiklejohn/files/imc13.pdf">Inference attacks on Bitcoin</a></li>
            <li><a href="http://zerocash-project.org/media/pdf/zerocash-extended-20140518.pdf">Zcash</a></li>
            </ul>
        </th>
        <th></th>
    </tr>
    <tr>
        <th>Week 3</th>
        <th>Polynomial commitments</th>
        <th>
        <a href="https://www.iacr.org/archive/asiacrypt2010/6477178/6477178.pdf">Polynomial commitments</a>
        </th>
        <th>Team Formation</th>
    </tr>
    <tr>
        <th>Week 3</th>
        <th rowspan="2">Generic solutions: interactive proofs</th>
        <th rowspan="2">
            <ul>
                <li><a href="https://link.springer.com/content/pdf/10.1007%2F978-3-642-40084-1_5.pdf">Time-Optimal Interactive Proofs for Circuit Evaluation</a></li>
                <li><a href="https://eprint.iacr.org/2019/317">Libra: Succinct Zero-Knowledge Proofs with Optimal Prover Computation</a></li>
            </ul>
        </th>
        <th></th>
    </tr>
    <tr>
        <th>Week 4</th>
        <th></th>
    </tr>
    <tr>
        <th>Week 4</th>
        <th>Generic solutions:Plonk</th>
        <th><a href="https://eprint.iacr.org/2019/953.pdf">Plonk</a></th>
        <th></th>
    </tr>
    <tr>
        <th>Week 5</th>
        <th>Smart contract</th>
        <th></th>
        <th></th>
    </tr>
    <tr>
        <th>Week 5</th>
        <th>Privacy-preserving smart contract and zkRollups</th>
        <th><a href="https://eprint.iacr.org/2015/675.pdf">Hawk</a></th>
        <th>Proposal due</th>
    </tr>
    <tr>
        <th>Week 6</th>
        <th rowspan="2">Generic solutions: SNARK</th>
        <th rowspan="2">
            <ul>
                <li><a href="https://eprint.iacr.org/2013/279.pdf">Pinocchio</a></li>
                <li><a href="https://eprint.iacr.org/2016/260.pdf">Groth16</a></li>
            </ul>
        </th>
        <th></th>
    </tr>
    <tr>
        <th>Week 6</th>
        <th></th>
    </tr>   
    <tr>
        <th>Week 7</th>
        <th>Zero-knowledge proofs for machine learning CNN</th>
        <th><a href="https://dl.acm.org/doi/abs/10.1145/3460120.3485379">zkCNN</a></th>
        <th></th>
    </tr>
    <tr>
        <th>Week 7</th>
        <th>Zero-knowledge decision tree</th>
        <th><a href="https://dl.acm.org/doi/pdf/10.1145/3372297.3417278">Zero-knowledge decision trees</a></th>
        <th></th>
    </tr>
    <tr>
        <th>Week 8</th>
        <th>ZKP based on error-correcting codes</th>
        <th>
            <ul>
                <li><a href="https://eprint.iacr.org/2021/1043">Brakedown</a></li>
                <li><a href="https://eprint.iacr.org/2022/1010">Orion</a></li>
            </ul>
        </th>
        <th></th>
    </tr>
    <tr>
        <th>Week 8</th>
        <th>Interactive Oracle Proofs and FRI</th>
        <th><a href="https://eccc.weizmann.ac.il/report/2017/134/">FRI</a></th>
        <th></th>
    </tr>
    <tr>
        <th>Week 9</th>
        <th rowspan = "2">Midterm Presentation</th>
        <th rowspan = "2"></th>
        <th rowspan = "2"></th>
    </tr> 
    <tr>
        <th>Week 9</th>
    </tr>  
    <tr>
        <th>Week 10</th>
        <th>Introduction to secure multiparty computation and Oblivious Transfer</th>
        <th><a href="https://nishkum.github.io/files/OT_extension.pdf">OT Extension</a>
        </th>
        <th></th>
    </tr>
    <tr>
        <th>Week 10</th>
        <th>Yao's Garbled circuit</th>
        <th>
        <ul>
            <li><a href="https://www.peteresnyder.com/static/papers/Peter_Snyder_-_Garbled_Circuits_WCP_2_column.pdf"> Yao's Garbled circuits</a></li>
            <li><a href="https://www.youtube.com/watch?v=GjhvJxelIVQ">Youtube tutorial</a></li>
            <li><a href="https://www.iacr.org/archive/eurocrypt2015/90560204/90560204.pdf">Half gates</a></li>
        </ul>
        </th>
        <th></th>
    </tr>
    <tr>
        <th>Week 11</th>
        <th>GMW protocol</th>
        <th>
            <a href="https://www.youtube.com/watch?v=4YwvZaA9IEg">Youtube tutorial</a>
        </th>
        <th></th>
    </tr>
    <tr>
        <th>Week 11</th>     
        <th>Malicious security and fairness</th>
        <th>
        <ul>
            <li><a href="https://eprint.iacr.org/2017/030">Authenticated Garbling</a></li>
            <li><a href="https://eprint.iacr.org/2008/049.pdf">Cut and choose</a></li>
        </ul>    
        </th>
        <th></th>
    </tr>
    <tr>
        <th>Week 12</th>
        <th>Privacy-preserving machine learning and linear regression</th>
        <th>
            <ul>
            <li><a href="https://eprint.iacr.org/2017/396.pdf">SecureML</a></li>
            <li><a href="https://people.eecs.berkeley.edu/~wzheng/helen_ieeesp.pdf">Helen: Maliciously Secure Coopetitive Learning for Linear Models</a></li>
            </ul>
        </th>   
        <th></th>
    </tr>
    <tr>
        <th>Week 12</th>
        <th>Privacy-preserving logistic regression and neural networks</th>
        <th>
            <li><a href="https://eprint.iacr.org/2018/403.pdf">ABY3: A Mixed Protocol Framework for Machine Learning</a></li>
        </th>
        <th></th>
    </tr>
    <tr>
        <th>Week 13</th>
        <th>Stacked Garbling</th>
        <th> <li><a href="https://eprint.iacr.org/2020/973">Stacked Garbling</a></li></th>
        <th></th>
    </tr>
    <tr>
        <th>Week 13</th>
        <th>No class on 11/16</th>
        <th></th>
        <th></th>
    </tr>
    <tr>
        <th rowspan="2">Week 14</th>
        <th rowspan="2">Fall break</th>
        <th rowspan="2"></th>
        <th rowspan="2"></th>
    </tr>
     <tr>
    </tr>
    <tr>
        <th>Week 15</th>
        <th>Presentations</th>
        <th></th>
        <th></th>
    </tr>
    <tr>
        <th>Week 15</th>
        <th>Presentations</th>
        <th></th>
        <th>Final report due</th>
    </tr>
</table>

## Grading

**Class Participation:** 10%. 

**Reading assignments:** 30%. Students will submit reviews for one of the reading materials every 1-2 weeks. The reviews should include a brief summary of the paper, the contributions and potential improvements.

**Course project:** 60%. Project (60%): Students will form groups and complete research projects related to the topics of the course. The grading consists of a project proposal, a mid-term progress report, a final presentation and a final project report. Students may propose their own topics or choose from a list of suggested topics on secure multiparty computations, verifiable computations and zero knowledge proof, privacy-preserving machine learning and blockchain.
- Proposal (10%)
- Mid-term presentation (10%)
- Final presentation (20%)
- Final report (20%)




