# [Runtime-Error](https://begininfiniteloop.wordpress.com/)

My Internal Code Is Corrupted

## [Internal Error

#20220820](https://begininfiniteloop.wordpress.com/2022/08/20/internal-error/)

* * *

![](https://begininfiniteloop.files.wordpress.com/2022/08/img_1998.png?w=1024)

    Do you ever stop and ask yourself “How did I get here? When did this path I’ve been on, start to veer off course? Why did I make those decisions that initially lead me to here?”
    
    
    Every day is the same day over and over again. 
    
    
    It’s like no matter what I do or say, when I go to bed and wake up the next day, everything resets and starts all over again
    
    
    Life has become a simulation that I can’t outrun.

Posted  
by[Dsmith](https://begininfiniteloop.wordpress.com/author/f4ultyc0d3/)[August  
20, 2022August 21,  
2022](https://begininfiniteloop.wordpress.com/2022/08/20/internal-  
error/)Posted  
in[loops](https://begininfiniteloop.wordpress.com/category/loops/)Tags:[errors](https://begininfiniteloop.wordpress.com/tag/errors/),  
[loops](https://begininfiniteloop.wordpress.com/tag/loops/)[Leave a comment on  
Internal Error  
#20220820](https://begininfiniteloop.wordpress.com/2022/08/20/internal-  
error/#respond)

## [JavaScript If – Else Control Statements – Simple

Snippets](https://begininfiniteloop.wordpress.com/2022/04/01/javascript-if-  
else-control-statements-simple-snippets/)

![javascript if else control statements - featured  
image](https://simplesnippets.tech/wp-content/uploads/2018/10/javascript-if-  
else-control-statements-featured-image.jpg)javascript if else control  
statements – featured image

Conditional statements are used to perform different actions based on  
different conditions. In this tutorial post we will study and understand the  
working of **if-eLse Control statements** in Javascript and also see a few  
example programs and variations of the if-else statements in JavaScript.

**Decision Making** in programming is similar to decision making in real life.  
In programming also we face some situations where we want a certain block of  
code to be executed when some condition is fulfilled. This is where  
conditional control statements come into picture.

JavaScript's If-Else conditional statements variations :

  *     * **if**
    		

	* **if-else**

	* **nested-if**

	* **if-else-if**  

These statements allow you to control the flow of your program's execution  
based upon conditions known only during run time.

### **if Statements –**

if statement is the most simple decision making statement. It is used to  
decide whether a certain statement or block of statements will be executed or  
not i.e if a certain condition is true then a block of statement is executed  
otherwise not.

**Syntax** :

    if(condition) 
    {
       // Statements to execute if
       // condition is true
    }
    
    
    Here, **condition** after evaluation will be either true or false. if statement accepts **boolean** values – if the value is true then it will execute the block of statements under it.
    
    
    **Flow Chart**:
    
    
    ![if statement flow diagram in javascript](https://simplesnippets.tech/wp-content/uploads/2018/10/if-statement-flow-diagram-in-javascript.jpg)
    
    
    **Program Example **:
    
    
    <script type = "text/javaScript"> 
    
    // JavaScript program to illustrate If statement 
    
    var i = 10; 
    
    if (i > 15) 
      document.write("10 is less than 15"); 
    
    // This statement will be executed 
    // as if considers one statement by default 
    document.write("If block not executed"); 
    
    < /script>
    
    
    **Output :**
    
    
    If block not executed
    
    
    ##### **if – else statements –**
    
    
    The if statement alone tells us that if a condition is true it will execute a block of statements and if the condition is false it won’t. But what if we want to do something else if the condition is false. Here comes the else statement. We can use the else statement with if statement to execute a block of code when the condition is false.
    
    
    **Syntax**:
    
    
    if (condition)
    {
        // Executes this block if
        // condition is true
    }
    else
    {
        // Executes this block if
        // condition is false
    }
    
    
    **Flow Chart**:
    
    
    ![if-else statement flow diagram in javascript](https://simplesnippets.tech/wp-content/uploads/2018/10/if-else-statement-flow-diagram-in-javascript.jpg)
    
    
    **Program Example **:
    
    
    <html>
     <head>
       <title>IF-Else if - Else Control Statments in javascript</title>
      <script type="text/javascript">
       /*Q1) Find whether is number is EVEN or ODD*/
       var x=7;
       if(x%2==0)
       {
        document.write("<h3>Even Number</h3>");    
       }
       else
       {
        document.write("<h3>Odd Number</h3>"); 
       }
    
      </script>
     </head>
     <body>
     </body>
    </html>
    
    
    **Output :**
    
    
    Odd Number
    
    
    ##### **Nested if statements –**
    
    
    A nested if is an if statement that is the target of another if or else. Nested if statements means an if statement inside an if statement. Yes, JavaScript allows us to nest if statements within if statements. i.e, we can place an if statement inside another if statement.
    
    
    **Syntax:**
    
    
    if (condition1) 
    {
       // Executes when condition1 is true
       if (condition2) 
       {
          // Executes when condition2 is true
       }
    }
    
    
    **Flow Chart**:
    
    
    ![nested if statement flow diagram in javascript](https://simplesnippets.tech/wp-content/uploads/2018/10/nested-if-statement-flow-diagram-in-javascript.jpg)
    
    
    **Program Example **:
    
    
    <html>
     <head>
       <title>IF-Else if - Else Control Statments in javascript</title>
      <script type="text/javascript">
       /*Q3) Find if a number is positive and even*/
       var x=8;
       if(x>0)
       {
        document.write("<h3>Positive Number</h3>");  
        if(x%2==0)
        {
         document.write("<h3>Positive & Even Number</h3>");  
        }  
       }
    
      </script>
     </head>
     <body>
     </body>
    </html>
    
    
    **Output :**
    
    
    Positive & Even Number
    
    
    ##### **if-else if ladder statements –**
    
    
    If you have multiple statements, you can use if-else if ladder to check for multiple conditions. As soon as one of the conditions controlling the if is true, the statement associated with that if is executed, and the rest of the ladder is bypassed. If none of the conditions is true, then the final else statement will be executed.
    
    
    **Syntax:**
    
    
    if (condition)
        statement;
    else if (condition)
        statement;
    .
    .
    else
        statement;
    
    
    **Flow Chart**:
    
    
    
    **Program Example **:
    
    
    <html>
     <head>
       <title>IF-Else if - Else Control Statments in javascript</title>
      <script type="text/javascript">
       /*Q1) Find if a number is positive, negative or 0*/
       var x=8;
       if(x>0)
       {
        document.write("<h3>Positive Number</h3>");  
       }
       else if(x<0)
       {
        document.write("<h3>Negative Number</h3>"); 
       }
       else
       {
        document.write("<h3>Number is 0</h3>"); 
       }
    
      </script>
     </head>
     <body>
     </body>
    </html>
    
    
    **Output **:
    
    
    Positive Number
    
    
    ##### **Watch it on YouTube**
    

* * *

Posted  
by[Dsmith](https://begininfiniteloop.wordpress.com/author/f4ultyc0d3/)[April  
1, 2022](https://begininfiniteloop.wordpress.com/2022/04/01/javascript-if-  
else-control-statements-simple-snippets/)Posted  
in[js](https://begininfiniteloop.wordpress.com/category/js/)Tags:[js](https://begininfiniteloop.wordpress.com/tag/js/)[Leave  
a comment on JavaScript If – Else Control Statements – Simple  
Snippets](https://begininfiniteloop.wordpress.com/2022/04/01/javascript-if-  
else-control-statements-simple-snippets/#respond)

## [JCCC Honors

Journal](https://begininfiniteloop.wordpress.com/2022/04/01/jccc-honors-  
journal/)

Volume 3

Issue 1 *Fall 2011* Article 2

2012

# An Analysis of ADHD Drugs: Ritalin and Adderall

## Awista S Johnson Co He Unty Co Rzada Mmunity College

asherzad@stumail.jccc.edu

Follow this and additional works  
at:<http://scholarspace.jccc.edu/honors_journal>

This Article iHonors Journal by an authors brought to you for fized adminiree  
and opestrator of Sn access by the HcholarSpace @ JConors Program at  
ScholarSpace @ JCCC. For more information, please contactCC. It has  
bebbaile14@jen accepted for inclusion in JCccc.edu. CC

Recommended Citation

Sherzada, Awista (2012) "Available at:<http://scholarspace.jccc.edu/honorAn>  
Analysis of ADHD Drs_journal/vol3/iss1/2ugs: Ritalin and Adderall," *JCCC  
Honors Journal* : Vol. 3: Iss. 1, Article 2.

# An Analysis of ADHD Drugs: Ritalin and Adderall

**Abs** Ritalin and Adde **tract** rall are commonly prescribed drugs for the  
treatment of the attention-deficit hyperactivity

disorder (ADHD) in children, adolescents, and adults. Our study summarizes the  
properties and applications

of thedescribing the simise chemical compoundlarities and ds: meifferences in  
their modethylphenidate (Ritalin, MPHs of action. Inclusiv) and  
dextroamphetamine (ely, these drugs peAdderform by alteringrall)

catecholamine levels in the nervous system for increased stimulation.

    This article is available in JCCC Honors Journal:http://scholarspace.jccc.edu/honors_journal/vol3/iss1/
    

## INTRODUCTION

    Attention-deficit hyperactivity disorder is a psychiatric condition that is treated with a
    class of drugs called psychostimulants whose major function is to increase activity of the central
    nervous system (CNS). The main region of exertion is the dopamine transporter (DAT) in the
    brain. Psychostimulants have been found to be the most effective drugs in reducing symptoms of
    inattention, hyperactivity, and impulsivity in patients with ADHD [1]. To gain an understanding
    of ADHD drugs, this paper will provide an overview of two commonly prescribed drugs:
    Adderall (dextroamphetamines) and Ritalin (methylphenidate), with emphasis on the chemical
    and physical properties, chemical structure, mode of action, dosage, and adverse effects.
    PART I: CHEMICAL AND PHYSICAL PROPERTIES
    Ritalin
    The brand name Ritalin is made up of the chemical compound Methylphenidate (MPH)
    with the IUPAC (abbreviation from the International Union of Pure and Applied Chemistry)
    name methyl phenyl(piperidin-2-yl)acetate [2]. The molecular formula for MPH, C 14 H 19 NO 2 and
    structural formula (pictured below) indicate that the chemical compound consists of the elements
    carbon, hydrogen, and nitrogen with a molecular weight totaling to 233.31 g/mol. MPH is a
    piperidine compound due to the presence of an amine group bonded within a carbon cycle. The
    melting point of this compound is 214 °C [2]. The finished product that makes up MPH is an
    odorless, white solid as crystalline powder [3].
    1
    Sherzada: An Analysis of ADHD Drugs: Ritalin and Adderall
    

Published by ScholarSpace @ JCCC, 2012

    Methylphenidate
    Adderall
    The brand name Adderall is a chemical compound that is made up of powerful blends of
    the amphetamine (abbreviated form from alpha-methylphenethyl amine) salts
    dextroamphetamine and levoamphetamine, which are isomers of the original amphetamine
    molecule and come in a 3:1 ratio [4]. The blend consists of the following:
    One-quarter racemic (d,l-)amphetamine aspartate monohydrate,
    One-quarter dextroamphetamine saccharin,
    One-quarter dextroamphetamine sulfate,
    One-quarter racemic (d,l-)amphetamine sulfate [5].
    The IUPAC name for dextroamphetamine is 1-phenylpropan-2-amine [5]. The molecular
    formula, C 9 H 13 N and structural formula (pictured below) show that the compound consists of the
    elements carbon, hydrogen, and nitrogen with a molecular weight totaling to 135.21 g/mol. The
    2
    JCCC Honors Journal, Vol. 3 [2012], Iss. 1, Art. 2
    

<http://scholarspace.jccc.edu/honors_journal/vol3/iss1/>

    chemical structure also reveals a benzene aromatic ring bonded with an amine side group. Before
    amphetamine is made into a salt or a solid for ingestion, it is a colorless liquid with a boiling
    point of 203-204 °C [6].
    Amphetamine
    PART II: MODE OF ACTION
    Dopamine
    The biggest player in improving symptoms of ADHD is a catecholamine neurotransmitter
    called dopamine. The molecule consists of a benzene ring with two attached hydroxyl side
    groups (see picture below). Studies suggest that a person with ADHD has a dopamine
    dysfunction and lacks the normal levels of the neurotransmitter [7]. Dopamine is biosynthesized
    in the body through an enzyme catalyzed process in which substrates are converted to more
    complex products [7,8]. Furthermore, dopamine is a precursor for the neurotransmitters
    norepinephrine (noradrenaline) and then epinephrine (adrenaline) in their biosynthetic pathways.
    This family of catecholamines is biosynthesized by nervous tissue and the adrenal gland [7].
    After synthesis, dopamine is packaged into vesicles which are then released into the synapse in
    response to a presynaptic action potential. In the nervous system, a synapse is a structure that
    permits a neuron (nerve cell) to pass an electrical or chemical signal to another cell [9] via axons.
    Action potentials generate and travel along axons of neurons to activate synaptic connections
    3
    Sherzada: An Analysis of ADHD Drugs: Ritalin and Adderall
    

Published by ScholarSpace @ JCCC, 2012

    between each other. Regulation of neurotransmitters such as dopamine is achieved through cell-
    cell signaling via synapses. At a chemical synapse, one neuron releases neurotransmitter
    molecules into a small space (the synaptic cleft) that is adjacent to another neuron. These
    molecules then bind to the receptors on the receiving cells side of the synaptic cleft to the post
    synaptic area. Finally, the neurotransmitters must be cleared out of the pre synaptic area
    efficiently in order to be prepared for succeeding signals [10]. The dopaminergic neuron
    dopamine modulates both pre and post synaptic neurotransmission [7]. It is naturally released in
    rewarding experiences. Moreover, dopamine has many functions of regulation in the brain
    including cognition, voluntary movement, motivation, punishment, sleep, mood, attention,
    working memory, and learning [10]. For example, an individual affected with Parkinson’s
    disease experiences dysfunctions in their motor and cognition because the dopamine generating
    cells no longer operate appropriately. Dopamine neurotransmitter plays a crucial role in the
    ability of a person to function and perform all essential daily activities. A synthetic form of
    dopamine has been made, however ingesting the synthesized dopamine drug has no direct affect
    to the CNS (central nervous system) because it cannot pass the blood brain barrier (BBB). For
    this reason, chemical compounds that are smaller molecules such as MPH and amphetamines are
    medically used to increase levels of dopamine and related neurotransmitters in the brain.
    4
    JCCC Honors Journal, Vol. 3 [2012], Iss. 1, Art. 2
    

<http://scholarspace.jccc.edu/honors_journal/vol3/iss1/>

    Dopamine
    Ritalin
    MPH is a chain substituted amphetamine derivative that primarily acts as a
    norepinephrine-dopamine reuptake inhibitor [2]. It is well absorbed from the gastro-intestinal
    (GI) tract after oral administration and reaches peak concentrations in the brain within
    approximately 2 hours [11, 12]. MPH targets the dopamine transporter (DAT) with the affected
    area being the prefrontal cortex in the brain [13]. The main mechanism of action is the
    modulation of the catecholamines, norepinephrine and dopamine. This is achieved by the
    enantiomers d-threo-methylphenidate and l-threo-methylphenidate which bind to DAT [14]. A
    norepinephrine-dopamine reuptake inhibitor increases the amount of norepinephrine and
    dopamine neurotransmitters in the brain by partially blocking DAT, inhibiting it from completely
    removing the dopamine from the synapse [2]. Generally, the inhibition of DAT stops the
    presynaptic neuron from reabsorbing dopamine and norepinephrine, which increases the amount
    of dopamine in the synapse. Persons affected by ADHD tend to have lower levels of dopamine
    neurotransmitters in their synapses and the inhibition of DAT during treatment stimulates the
    5
    Sherzada: An Analysis of ADHD Drugs: Ritalin and Adderall
    

Published by ScholarSpace @ JCCC, 2012

    release of dopamine and norepinephrine into the synapse. MPH has the capability to occupy
    about 50% of the dopamine transporters [2]. Because MPH is a small molecule, it passes through
    the BBB in the mode similar to those of cocaine, but the MPH is less intoxicating and its
    duration of action is longer. Stimulation of dopaminergic activity greatly increases levels of
    dopamine, which ultimately increases attention and motivation, while decreasing distractibility
    and motor hyperactivity [13].
    Adderall
    Adderall is administrated orally and absorbed from the GI (gastrointestinal) tract with
    peak concentration in the brain reached approximately in 3 hours [15]. During its metabolic
    process, the aromatic ring in amphetamine oxidizes to form alpha-hydroxyamphetamine, which
    then undergoes deamination to form phenylacetone, and finally, oxidizes to form benzoic acid
    [15]. Similar to MPH and cocaine, amphetamine is a small molecule allowing it to pass the BBB
    easily. Dextroamphetamine affects the central nervous system by increasing dopamine levels
    while levoamphetamine affects the peripheral nervous system by increasing norepinephrine [16].
    Since dextroamphetamine consists of three quarters of the salts in Adderall, it greatly impacts the
    prefrontal cortex of the brain. In reducing ADHD symptoms, the key function of Adderall is to
    block the reuptake of norepinephrine, dopamine, and serotonin into the presynaptic neuron and
    increase the release of these monoamines into the synaptic space [15]. Like MPH, it is able to
    enhance dopaminergic activity by binding to DAT and prolonging the availability of
    neurotransmitters in the synapse by slowing down their removal [16]. Additionally,
    amphetamine enters the presynaptic neuron building a membrane potential to force dopamine
    molecules out of their storage vesicles and expel them into the synaptic space. This action is
    performed by making the dopamine transporters work in reverse [7]. Subsequently, amphetamine
    6
    JCCC Honors Journal, Vol. 3 [2012], Iss. 1, Art. 2
    

<http://scholarspace.jccc.edu/honors_journal/vol3/iss1/>

    also has the power to inhibit the enzyme that is responsible for the breakdown of
    neurotransmitters called monoamine oxidase [16]. Inhibiting this process leads to the
    accumulation of dopamine, norepinephrine, and serotonin. The potency of dextroamphetamine in
    Adderall greatly and rapidly increases levels of the monoamine neurotransmitters in the synapse,
    ultimately reducing symptoms of inattention, impulsivity, and hyperactivity.
    PART III: DOSAGE AND ADVERSE EFFECTS
    Ritalin
    MPH is available in immediate release form (Ritalin), sustained release form (Ritalin
    SR), and extended release form (Ritalin LA). The immediate release form is available as 5 mg,
    10 mg, 15 mg, 20 mg, and 30 mg tablets and can last anywhere from 3 to 5 hours [17, 18]. The
    immediate release tablet is taken two to three times daily with an average dosage of 20 to 30 mg
    a day [17]. The recommended starting dosage is 5 mg and is adjusted based on the response of
    the individual [17]. Ritalin SR is available as 20 mg, 40 mg, and 60 mg and is taken once or
    twice daily. Ritalin LA is available as 20 mg, 30 mg, 40 mg, and 50 mg capsules [17]. Ritalin LA
    is taken once daily in the morning and can last anywhere from 8 to 12 hours [17, 18]. All forms
    of MPH are not recommended to exceed 60 mg per day [19]. The dosage prescribed to a patient
    is determined by their severity of symptoms, body weight, and rate of metabolism. The common
    adverse effects associated with taking MPH are rapid heart rate, palpitations, nervousness,
    restlessness, insomnia, dry mouth, constipation, nausea, diarrhea, loss of appetite, weight loss,
    and elevation of blood pressure [17]. MPH should not be used in children under six years old nor
    in persons with high blood pressure or any form of heart disease, persons who are nervous or
    have severe insomnia, persons who are taking monoamine oxidase inhibitors and persons who
    have a history of addiction to drugs and alcohol [20]. The Food and Drug Administration (FDA)
    7
    Sherzada: An Analysis of ADHD Drugs: Ritalin and Adderall
    

Published by ScholarSpace @ JCCC, 2012

    also issues an additional “Black Box” warning label which means that medical studies indicate
    these drugs carry a significant risk of serious, or even life-threatening, adverse effects [20].
    Ritalin is classified as a schedule II substance by the FDA because it shares the same abuse
    potential as cocaine and morphine that may lead to severe psychological or physical dependence
    [20]. There is little research on the long term effects of using MPH. It is possible to build up a
    tolerance where the person using the drug will need to take larger doses to achieve the same
    effect [20]. Overtime, the body may become dependent on the drug to function normally. The
    withdrawal symptoms that could arise include tiredness, panic attacks, crankiness, extreme
    hunger, depression and nightmares. These symptoms are mostly psychological and stopping the
    drug suddenly can cause extreme fatigue and severe, even suicidal, depression in adult patients
    [20]. A person should never stop taking MPH abruptly but should do so gradually.
    Adderall
    Adderall is available in instant (Adderall IR) and extended release form (Adderall XR).
    The instant release tablet is taken 2 to 3 times daily; 4 to 6 hours apart each time, and can be
    taken with or without food [21]. The doses available for Adderall IR tablets are 5 mg, 7.5 mg, 10
    mg, 15 mg, 20 mg, and 30 mg breakable tablets. The daily maximum recommended dose is 40
    mg, but some patients may initially require 60 mg [22]. In contrast, Adderall XR is taken only
    once daily in the morning and can be taken with or without food [21]. The doses available for
    Adderall XR capsules are 5 mg, 10 mg, 15 mg, 20 mg, 25 mg, and 30 mg capsules, which are not
    breakable [21]. The daily maximum recommended dose is 30 mg, but some patients may require
    more [22]. Adderall IR and XR are both metabolized by the liver; IR lasts 4 – 6 hours and XR
    lasts 8 – 10 hours [22]. Patients normally start at a low dose and gradually increase as tolerated.
    The most common adverse reactions in children ages 6 to 12 are loss of appetite, insomnia,
    8
    JCCC Honors Journal, Vol. 3 [2012], Iss. 1, Art. 2
    

<http://scholarspace.jccc.edu/honors_journal/vol3/iss1/>

    abdominal pain, emotional liability, vomiting, nervousness, nausea, and fever [23]. In
    adolescents, the common adverse reactions are loss of appetite, insomnia, abdominal pain,
    weight loss, and nervousness [23]. Finally, in adults, the common adverse reactions are dry
    mouth, loss of appetite, insomnia, headache, weight loss, nausea, anxiety, agitation, dizziness,
    tachycardia, diarrhea, asthenia, and urinary tract infections [23]. Adderall should not be used in
    persons who have not tried other psychotherapy before, have high blood pressure or any form of
    heart disease, are very nervous or have severe insomnia, have a history of addiction to drugs or
    alcohol, take monoamine oxidase inhibitors, or have Tourette syndrome, which is one of several
    chronic tic disorders [24]. The FDA also issues a “Black Box” warning label which means that
    medical studies indicate these drugs carry a significant risk of serious, or even life-threatening
    adverse effects. Like Ritalin, Adderall is also classified as a schedule II drug by the FDA due to
    its high abuse potential. Amphetamines have the ability to induce anxiety disorders, psychosis,
    and sexual dysfunction [24]. Because amphetamines are very closely related to MPH, they have
    the same dependence, tolerance, and withdrawal characteristics. It is possible to build up a
    tolerance where the person using the drug will need to take larger doses to achieve the same
    effect [24]. Overtime, the body may become dependent on the drug to function normally. The
    withdrawal symptoms that could arise include tiredness, panic attacks, crankiness, extreme
    hunger, depression and nightmares [24]. These symptoms are psychological and stopping the
    drug suddenly can cause extreme fatigue and severe, even suicidal, depression in adult patients
    [24]. Again, a person should never stop taking Adderall abruptly but should do so gradually. Jack
    M. Gorman, M.D., professor of psychiatry at Columbia University and deputy director of the
    New York State Psychiatric Institute emphasizes: “Adderall is a very powerful drug that
    9
    Sherzada: An Analysis of ADHD Drugs: Ritalin and Adderall
    

Published by ScholarSpace @ JCCC, 2012

    undoubtedly works for ADHD, but there are alternatives with less abuse potential that should be
    tried first.” [24]
    SUMMARY
    MPH and Adderall are both used for the pharmacological treatment of ADHD but differ
    chemically. Moreover, although the both drugs are similar in structure, metabolism, and clinical
    effects, they do differ in their mode of action. MPH is less potent and longer in duration of action
    [2]. In contrast, amphetamines have a quicker onset followed by a “speed crash.” Adderall has
    the ability to make DAT work in a reverse mechanism increasing catecholamine levels to a
    greater and quicker extent than Ritalin. The dosage charts of the two drugs also imply that
    Adderall has higher potency. Hence, the maximum recommended dosage for Ritalin is 60 mg
    compared to Adderall, which is 40 mg. Although dependency is possible with both Ritalin and
    Adderall, the potency of amphetamines in Adderall suggests a higher risk of dependency. It has
    greater ability to interfere with the natural mechanism of DAT, causing much lower levels of
    dopamine in the absence of the drug [2]. Comparable to cocaine, Ritalin and Adderall are
    classified as type II drugs by the FDA because they also have high risks of abuse potential.
    Furthermore, resembling cocaine, Ritalin and Adderall are also monoamine reuptake inhibitors
    of dopamine, norepinephrine, and serotonin. The similarities ADHD drugs have to street drugs
    such as cocaine gives rise to several controversies. However, Ritalin and Adderall are safe and
    effective to use in small doses because studies have proved them to be therapeutic under the
    proper regulations. Unfortunately, ADHD drugs are used as recreational stimulants to self-induce
    euphoria and can be used as a study aid, social aid or party drug [5]. The effects of long term
    usage of Ritalin and Adderall are not clear yet and remain under investigation. Although Ritalin
    and Adderall both act to stimulate the nervous system, there are several notable differences
    10
    JCCC Honors Journal, Vol. 3 [2012], Iss. 1, Art. 2
    

<http://scholarspace.jccc.edu/honors_journal/vol3/iss1/>

    between the two. It is not suggested for one to be better than the other because the effectiveness
    of each drug varies from person to person. The drug selected to use for treatment of ADHD
    symptoms is determined by a trained physician.
    

## REFERENCES

    [1] Attention deficit hyperactivity disorder. Retrieved from National Institute of Mental Health
    website: http://www.nimh.nih.gov/health/publications/attention-deficit-hyperactivity-
    disorder/complete-index.shtml
    [2] Methylphenidate. In Wikipedia Retrieved from http://en.wikipedia.org/wiki/Methylphenidate
    11
    Sherzada: An Analysis of ADHD Drugs: Ritalin and Adderall
    

Published by ScholarSpace @ JCCC, 2012

    [3] Pubchem: Methylphenidate-compound summary. Retrieved from National Center for
    Biotechnology Information website:
    http://pubchem.ncbi.nlm.nih.gov/summary/summary.cgi?cid=4158&loc=ec_rcs#x
    [4] Drug bank: Open data drug & drug target database. (2005, June 13). Retrieved from
    http://www.drugbank.ca/drugs/DB
    [5] Dextroamphetamine. In Wikipedia Retrieved from
    http://en.wikipedia.org/wiki/Dextroamphetamine
    [6] Pubchem: Amphetamine-compound summary. Retrieved from National Center for
    Biotechnology Information website:
    http://pubchem.ncbi.nlm.nih.gov/summary/summary.cgi?cid=3007&loc=ec_rcs
    [7] Dopamine. In Wikipedia Retrieved from http://en.wikipedia.org/wiki/Dopamine
    [8] Biosynthesis. In Wikipedia Retrieved from http://en.wikipedia.org/wiki/Biosynthesis
    [9] Synapse. In Wikipedia Retrieved from http://en.wikipedia.org/wiki/Synapse
    [10] Chemical synapse. In Wikipedia Retrieved from
    http://en.wikipedia.org/wiki/Chemical_synapse
    [11] [Hardman, J.G., L.E. Limbird, P.B. Molinoff, R.W. Ruddon, A.G. Goodman (eds.).
    Goodman and Gilman's The Pharmacological Basis of Therapeutics. 9th ed. New York, NY:
    McGraw-Hill, 1996., p. 221] **PEER REVIEWED**
    [12] [McEvoy, G.K. (ed.). American Hospital Formulary Service-Drug Information 19 98.
    Bethesda, MD: American Society of Health-System Pharmacists, Inc. 1998 (Plus Supplements).,
    p. 1912] **PEER REVIEWED**
    [13] Wilens, T. (2008). Effects of methylphenidate on the catecholaminergic system in attention-
    deficit/hyperactivity disorder (18480677). Retrieved from Journal of Clinical
    PsychopharmacologyPsycho website: http://www.ncbi.nlm.nih.gov/pubmed/
    [14] Volkow ND, Fowler JS, Wang G, Ding Y, Gatley SJ. (2002). Mechanism of action of
    methylphenidate: insights from pet imaging studies.. Retrieved from PubMed website:
    http://www.ncbi.nlm.nih.gov/pubmed/
    [15]Daily med: Adderall. Retrieved from U.S National Library of Medicine website:
    http://dailymed.nlm.nih.gov/dailymed/archives/fdaDrugInfo.cfm?archiveid=
    [16] Adderall. In Wikipedia Retrieved from http://en.wikipedia.org/wiki/Adderall
    [17] Ritalin/ritalin-sr/ritalin-la (methylphenidate). (n.d.). Retrieved from
    
    
    [Click to access ritalin.pdf](http://www.psychatlanta.com/documents/ritalin.pdf)
    
    
    12
    JCCC Honors Journal, Vol. 3 [2012], Iss. 1, Art. 2
    

<http://scholarspace.jccc.edu/honors_journal/vol3/iss1/>

    [18] Willets, S. (2008, September 12).Types of ritalin. Retrieved from
    http://www.ritalinadvisor.com/types
    [19] Ritalin, ritalin sr prescribing information. Retrieved from Novartis Pharmaceuticals
    Corporation website: http://www.pharma.us.novartis.com/product/pi/pdf/ritalin_ritalin-sr.pdf
    [20] Drug enquirer: Latest news and facts about medicines you take. Retrieved from Research
    Publishing Co. website: http://www.ritalinsideeffects.net/
    [21] American Society of Health-System Pharmacists, Inc. Disclaimer.
    (n.d.). Dextroamphetamine and amphetamine. Retrieved from U.S National Library of Medicine
    website: http://www.nlm.nih.gov/medlineplus/druginfo/meds/a601234.html
    [22] The Carlat Psychiatry Report. (n.d.).Adderall ir and xr fact sheet. Retrieved from
    http://thecarlatreport.com/mfs/adderall-ir-and-xr-fact-sheet
    [23] Adderal xr prescribing information. Retrieved from Shire US Inc. website:
    
    
    [Click to access AdderallXR_USA_ENG.PDF](http://pi.shirecontent.com/PI/PDFs/AdderallXR_USA_ENG.PDF)
    
    
    [24] Drug enquirer: Latest news and facts about medicines you take. Retrieved from Research
    Publishing Co. website: http://www.adderall.net/#dextroamphetamine
    13
    Sherzada: An Analysis of ADHD Drugs: Ritalin and Adderall
    

Published by ScholarSpace @ JCCC, 201

Posted  
by[Dsmith](https://begininfiniteloop.wordpress.com/author/f4ultyc0d3/)[April  
1, 2022](https://begininfiniteloop.wordpress.com/2022/04/01/jccc-honors-  
journal/)Posted  
in[adderall](https://begininfiniteloop.wordpress.com/category/adderall/)Tags:[adderall](https://begininfiniteloop.wordpress.com/tag/adderall/)[Leave  
a comment on JCCC Honors  
Journal](https://begininfiniteloop.wordpress.com/2022/04/01/jccc-honors-  
journal/#respond)

# [The Underground World of "Neuroenhancing" Drugs | The New

Yorker](https://begininfiniteloop.wordpress.com/2022/04/01/the-underground-  
world-of-neuroenhancing-drugs-the-new-yorker/)

A young man I'll call Alex recently graduated from Harvard. As a history  
major, Alex wrote about a dozen papers a semester. He also ran a student  
organization, for which he often worked more than forty hours a week; when he  
wasn't on the job, he had classes. Weeknights were devoted to all the  
schoolwork that he couldn't finish during the day, and weekend nights were  
spent drinking with friends and going to dance parties. "Trite as it sounds,"  
he told me, it seemed important to "maybe appreciate my own youth." Since, in  
essence, this life was impossible, Alex began taking Adderall to make it  
possible.

![Illustration of a sleeping woman and a vision of her neuroenhanced self  
typing on a  
laptop](https://media.newyorker.com/photos/59097602019dfc3494ea2bcf/master/w_2560%2Cc_limit/090427_r18418_p646.jpg)Illustration  
of a sleeping woman and a vision of her neuroenhanced self typing on a laptop

Every era has its defining drug. Neuroenhancers are perfectly suited for our  
efficiency-obsessed, BlackBerry-equipped office culture.Illustration by Adrian  
Tomine

Adderall, a stimulant composed of mixed amphetamine salts, is commonly  
prescribed for children and adults who have been given a diagnosis of  
attention-deficit hyperactivity disorder. But in recent years Adderall and  
Ritalin, another stimulant, have been adopted as cognitive enhancers: drugs  
that high-functioning, overcommitted people take to become higher-functioning  
and more overcommitted. (Such use is "off label," meaning that it does not  
have the approval of either the drug's manufacturer or the Food and Drug  
Administration.) College campuses have become laboratories for experimentation  
with neuroenhancement, and Alex was an ingenious experimenter. His brother had  
received a diagnosis of A.D.H.D., and in his freshman year Alex obtained an  
Adderall prescription for himself by describing to a doctor symptoms that he  
knew were typical of the disorder. During his college years, Alex took fifteen  
milligrams of Adderall most evenings, usually after dinner, guaranteeing that  
he would maintain intense focus while losing "any ability to sleep for  
approximately eight to ten hours." In his sophomore year, he persuaded the  
doctor to add a thirty-milligram "extended release" capsule to his daily  
regimen.

Alex recalled one week during his junior year when he had four term papers  
due. Minutes after waking on Monday morning, around seven-thirty, he swallowed  
some "immediate release" Adderall. The drug, along with a steady stream of  
caffeine, helped him to concentrate during classes and meetings, but he  
noticed some odd effects; at a morning tutorial, he explained to me in an  
e-mail, "I alternated between speaking too quickly and thoroughly on some  
subjects and feeling awkwardly quiet during other points of the discussion."  
Lunch was a blur: "It's always hard to eat much when on Adderall." That  
afternoon, he went to the library, where he spent "too much time researching a  
paper rather than actually writing it—a problem, I can assure you, that is  
common to all intellectually curious students on stimulants." At eight, he  
attended a two-hour meeting "with a group focused on student mental-health  
issues." Alex then "took an extended-release Adderall" and worked productively  
on the paper all night. At eight the next morning, he attended a meeting of  
his organization; he felt like "a zombie," but "was there to insure that the  
semester's work didn't go to waste." After that, Alex explained, "I went back  
to my room to take advantage of my tired body." He fell asleep until noon,  
waking "in time to polish my first paper and hand it in."

I met Alex one evening last summer, at an appealingly scruffy bar in the New  
England city where he lives. Skinny and bearded, and wearing faded hipster  
jeans, he looked like the lead singer in an indie band. He was ingratiating  
and articulate, and smoked cigarettes with an ironic air of defiance. Alex was  
happy enough to talk about his frequent use of Adderall at Harvard, but he  
didn't want to see his name in print; he's involved with an Internet start-up,  
and worried that potential investors might disapprove of his habit.

After we had ordered beers, he said, "One of the most impressive features of  
being a student is how aware you are of a twenty-four-hour work cycle. When  
you conceive of what you have to do for school, it's not in terms of nine to  
five but in terms of what you can physically do in a week while still  
achieving a variety of goals in a variety of realms—social, romantic, sexual,  
extracurricular, résumé-building, academic commitments." Alex was eager to  
dispel the notion that students who took Adderall were "academic automatons  
who are using it in order to be first in their class, or in order to be an  
obvious admit to law school or the first accepted at a consulting firm." In  
fact, he said, "it's often people"—mainly guys—"who are looking in some way to  
compensate for activities that are detrimental to their performance." He  
explained, "At Harvard, at least, most people are to some degree realistic  
about it. . . . I don't think people who take Adderall are aiming to be the  
top person in the class. I think they're aiming to be among the best. Or maybe  
not even among the best. At the most basic level, they aim to do better than  
they would have otherwise." He went on, "Everyone is aware of the fact that if  
you were up at 3 *A*.*M.* writing this paper it isn't going to be as good as  
it could have been. The fact that you were partying all weekend, or spent the  
last week being high, watching 'Lost'—that's going to take a toll."

Alex's sense of who uses stimulants for so-called "nonmedical" purposes is  
borne out by two dozen or so scientific studies. In 2005, a team led by Sean  
Esteban McCabe, a professor at the University of Michigan's Substance Abuse  
Research Center, reported that in the previous year 4.1 per cent of American  
undergraduates had taken prescription stimulants for off-label use; at one  
school, the figure was twenty-five per cent. Other researchers have found even  
higher rates: a 2002 study at a small college found that more than thirty-five  
per cent of the students had used prescription stimulants nonmedically in the  
previous year.

Drugs such as Adderall can cause nervousness, headaches, sleeplessness, and  
decreased appetite, among other side effects. An F.D.A. warning on Adderall's  
label notes that "amphetamines have a high potential for abuse" and can lead  
to dependence. (The label also mentions that adults using Adderall have  
reported serious cardiac problems, though the role of the drug in those cases  
is unknown.) Yet college students tend to consider Adderall and Ritalin  
benign, in part because they are likely to know peers who have taken the drugs  
since childhood for A.D.H.D. Indeed, McCabe reports, most students who use  
stimulants for cognitive enhancement obtain them from an acquaintance with a  
prescription. Usually, the pills are given away, but some students sell them.

According to McCabe's research team, white male undergraduates at highly  
competitive schools—especially in the Northeast—are the most frequent  
collegiate users of neuroenhancers. Users are also more likely to belong to a  
fraternity or a sorority, and to have a G.P.A. of 3.0 or lower. They are ten  
times as likely to report that they have smoked marijuana in the past year,  
and twenty times as likely to say that they have used cocaine. In other words,  
they are decent students at schools where, to be a great student, you have to  
give up a lot more partying than they're willing to give up.

&[lt;img alt=""I cant budge this ting. We shoulda popped him before he had  
dinner."" class="ResponsiveImageContainer-dlOMGF byslZC responsive-  
image__image"  
src="https://media.newyorker.com/cartoons/593b663757b86d47b169c90b/master/w_1600%2Cc_limit/090427_a14131_p465.jpg"  
srcSet="https://media.newyorker.com/cartoons/593b663757b86d47b169c90b/master/w_120,c_limit/090427_a14131_p465.jpg  
120w,  
https://media.newyorker.com/cartoons/593b663757b86d47b169c90b/master/w_240,c_limit/090427_a14131_p465.jpg  
240w,  
https://media.newyorker.com/cartoons/593b663757b86d47b169c90b/master/w_320,c_limit/090427_a14131_p465.jpg  
320w,  
https://media.newyorker.com/cartoons/593b663757b86d47b169c90b/master/w_640,c_limit/090427_a14131_p465.jpg  
640w,  
https://media.newyorker.com/cartoons/593b663757b86d47b169c90b/master/w_960,c_limit/090427_a14131_p465.jpg  
960w,  
https://media.newyorker.com/cartoons/593b663757b86d47b169c90b/master/w_1280,c_limit/090427_a14131_p465.jpg  
1280w,  
https://media.newyorker.com/cartoons/593b663757b86d47b169c90b/master/w_1600,c_limit/090427_a14131_p465.jpg  
1600w" sizes="100vw"/>](https://www.newyorker.com/cartoon/a14131)"I can't  
budge this t'ing. We shoulda popped him *before* he had dinner."

The BoredAt Web sites—which allow college students to chat idly while they're  
ostensibly studying—are filled with messages about Adderall. Posts like these,  
from the BoredAtPenn site, are typical: "I have some Adderall—I'm sitting by  
room 101.10 in a grey shirt and headphones"; "I have Adderall for sale 20mg  
for $15"; "I took Adderall at 8 p.m., it's 6:30 a.m. and I've barely blinked."  
On the Columbia site, a poster with an e-mail address from *CUNY* complains  
that her friends take Adderall "like candy," adding, "I don't want to be at a  
disadvantage to everyone else. Is it really that dangerous? Will it fuck me  
up? My grades weren't that great this year and I could do with a bump." A  
Columbia student responds, "It's probably not a good idea if you're not  
prescribed," but offers practical advice anyway: "Keep the dose normal and  
don't grind them up or snort them." Occasional dissents ("I think there should  
be random drug testing at every exam") are drowned out by testimonials like  
this one, from the BoredAtHarvard site: "I don't want to be a pusher or start  
people on something bad, but Adderall is *AMAZING*."

Alex remains enthusiastic about Adderall, but he also has a slightly jaundiced  
critique of it. "It only works as a cognitive enhancer insofar as you are  
dedicated to accomplishing the task at hand," he said. "The number of times  
I've taken Adderall late at night and decided that, rather than starting my  
paper, hey, I'll organize my entire music library! I've seen people  
obsessively cleaning their rooms on it." Alex thought that generally the drug  
helped him to bear down on his work, but it also tended to produce writing  
with a characteristic flaw. "Often, I've looked back at papers I've written on  
Adderall, and they're verbose. They're belaboring a point, trying to create  
this airtight argument, when if you just got to your point in a more direct  
manner it would be stronger. But with Adderall I'd produce two pages on  
something that could be said in a couple of sentences." Nevertheless, his  
Adderall-assisted papers usually earned him at least a B. They got the job  
done. As Alex put it, "Productivity is a good thing."

Last April, the scientific journal *Nature* published the results of an  
informal online poll asking whether readers attempted to sharpen "their focus,  
concentration, or memory" by taking drugs such as Ritalin and Provigil—a newer  
kind of stimulant, known generically as modafinil, which was developed to  
treat narcolepsy. One out of five respondents said that they did. A majority  
of the fourteen hundred readers who responded said that healthy adults should  
be permitted to take brain boosters for nonmedical reasons, and sixty-nine per  
cent said that mild side effects were an acceptable risk. Though a majority  
said that such drugs should not be made available to children who had no  
diagnosed medical condition, a third admitted that they would feel pressure to  
give "smart drugs" to their kids if they learned that other parents were doing  
so.

Such competitive anxieties are already being felt in the workplace. Recently,  
an advice column in *Wired* featured a question from a reader worried about "a  
rising star at the firm" who was "using unprescribed modafinil to work crazy  
hours. Our boss has started getting on my case for not being as productive."  
And on Internet forums such as ImmInst, whose members share a nerdy passion  
for tweaking their cognitive function through drugs and supplements, people  
trade advice about dosages and "stacks"—improvised combinations—of  
neuroenhancers. ("Cut a tablet into fourths and took 25 mg every four hours, 4  
times today, and had a great and productive day—with no side effects.") In one  
recent post, a fifty-two-year-old—who was working full time, studying for an  
advanced degree at night, and "married, etc."—wrote that after experimenting  
with modafinil he had settled on two daily doses of a hundred milligrams each.  
He believed that he was "performing a little better," adding, "I also feel  
slightly more animated when in discussion."

Not long ago, I met with Anjan Chatterjee, a neurologist at the University of  
Pennsylvania, in his office, which is tucked inside the labyrinthine Penn  
hospital complex. Chatterjee's main research interests are in subjects like  
the neurological basis of spatial understanding, but in the past few years, as  
he has heard more about students taking cognitive enhancers, he has begun  
writing about the ethical implications of such behavior. In 2004, he coined  
the term "cosmetic neurology" to describe the practice of using drugs  
developed for recognized medical conditions to strengthen ordinary cognition.  
Chatterjee worries about cosmetic neurology, but he thinks that it will  
eventually become as acceptable as cosmetic surgery has; in fact, with  
neuroenhancement it's harder to argue that it's frivolous. As he notes in a  
2007 paper, "Many sectors of society have winner-take-all conditions in which  
small advantages produce disproportionate rewards." At school and at work, the  
usefulness of being "smarter," needing less sleep, and learning more quickly  
are all "abundantly clear." In the near future, he predicts, some neurologists  
will refashion themselves as "quality-of-life consultants," whose role will be  
"to provide information while abrogating final responsibility for these  
decisions to patients." The demand is certainly there: from an aging  
population that won't put up with memory loss; from overwrought parents bent  
on giving their children every possible edge; from anxious employees in an  
efficiency-obsessed, BlackBerry-equipped office culture, where work never  
really ends.

Chatterjee told me that many people who come to his clinic are cognitively  
preoccupied versions of what doctors call the "worried well." The day I  
visited his office, he had just seen a middle-aged woman, a successful  
Philadelphia lawyer, who mentioned having to struggle a bit to come up with  
certain names. "Here's an example of someone who by most measures is doing  
perfectly fine," Chatterjee said. "She's not having any trouble at work. But  
she notices she's having some problems, and it's very hard to know how much of  
that is just getting older." Of course, people in her position could strive to  
get regular exercise and plenty of intellectual stimulation, both of which  
have been shown to help maintain cognitive function. But maybe they're already  
doing so and want a bigger mental rev-up, or maybe they want something easier  
than sweaty workouts and Russian novels: a pill.

Recently, I spoke on the phone with Barbara Sahakian, a clinical  
neuropsychologist at Cambridge University, and the co-author of a December,  
2007, article in *Nature,* "Professor's Little Helper." Sahakian, who also  
consults for several pharmaceutical companies, and her co-author, Sharon  
Morein-Zamir, reported that a number of their colleagues were using  
prescription drugs like Adderall and Provigil. Because the drugs are easy to  
buy online, they wrote, it would be difficult to stop their spread: "The drive  
for self-enhancement of cognition is likely to be as strong if not stronger  
than in the realms of 'enhancement' of beauty and sexual function." (In places  
like Cambridge, at least.)

When I spoke with Sahakian, she had just flown from England to Scottsdale,  
Arizona, to attend a conference, and she was tired. She might, justifiably,  
have forgone distractions like me, but she had her cell phone with her, and  
though it was a weekend morning some industrious person in the Cambridge news  
office had reached Sahakian in her hotel room, after she got out of the shower  
and before she had to rush to the first session. "We may be healthy and high-  
functioning, and think of ourselves that way, but it's very rare that we are  
actually functioning at our *optimal* level," Sahakian said. "Take me. I'm  
over here, and I've got jet lag and I've got to give a talk tonight and  
perform well, in what will be the middle of the night, U.K. time." She  
mentioned businessmen who have to fly back and forth across the Atlantic: "The  
difference between making a deal and not is huge and they sometimes only have  
one meeting to try and do it." She sympathized with them, but, she added, "we  
are a society that so wants a quick fix that many people are happy to take  
drugs."

&[lt;img alt=""What should you do Heres what you should do invent a time  
machine go back sixteen months and convert everything to cash.""  
class="ResponsiveImageContainer-dlOMGF byslZC responsive-image__image"  
src="https://media.newyorker.com/cartoons/593b663a5d2f45736c34cfba/master/w_1600%2Cc_limit/090427_a13965_p465.jpg"  
srcSet="https://media.newyorker.com/cartoons/593b663a5d2f45736c34cfba/master/w_120,c_limit/090427_a13965_p465.jpg  
120w,  
https://media.newyorker.com/cartoons/593b663a5d2f45736c34cfba/master/w_240,c_limit/090427_a13965_p465.jpg  
240w,  
https://media.newyorker.com/cartoons/593b663a5d2f45736c34cfba/master/w_320,c_limit/090427_a13965_p465.jpg  
320w,  
https://media.newyorker.com/cartoons/593b663a5d2f45736c34cfba/master/w_640,c_limit/090427_a13965_p465.jpg  
640w,  
https://media.newyorker.com/cartoons/593b663a5d2f45736c34cfba/master/w_960,c_limit/090427_a13965_p465.jpg  
960w,  
https://media.newyorker.com/cartoons/593b663a5d2f45736c34cfba/master/w_1280,c_limit/090427_a13965_p465.jpg  
1280w,  
https://media.newyorker.com/cartoons/593b663a5d2f45736c34cfba/master/w_1600,c_limit/090427_a13965_p465.jpg  
1600w" sizes="100vw"/>](https://www.newyorker.com/cartoon/a13965)"What should  
you do? Here's what you should do: invent a time machine, go back sixteen  
months and convert everything to cash."

For the moment, people looking for that particular quick fix have a limited  
choice of meds. But, given the amount of money and research hours being spent  
on developing drugs to treat cognitive decline, Provigil and Adderall are  
likely to be joined by a bigger pharmacopoeia. Among the drugs in the pipeline  
are ampakines, which target a type of glutamate receptor in the brain; it is  
hoped that they may stem the memory loss associated with diseases like  
Alzheimer's. But ampakines may also give healthy people a palpable cognitive  
boost. A 2007 study of sixteen healthy elderly volunteers found that five  
hundred milligrams of one particular ampakine "unequivocally" improved short-  
term memory, though it appeared to detract from episodic memory—the recall of  
past events. Another class of drugs, cholinesterase inhibitors, which are  
already being used with some success to treat Alzheimer's patients, have also  
shown promise as neuroenhancers. In one study, the drug donepezil strengthened  
the performance of pilots on flight simulators; in another, of thirty healthy  
young male volunteers, it improved verbal and visual episodic memory. Several  
pharmaceutical companies are working on drugs that target nicotine receptors  
in the brain, in the hope that they can replicate the cognitive uptick that  
smokers get from cigarettes.

Zack and Casey Lynch are a young couple who, in 2005, launched NeuroInsights,  
a company that advises investors on developments in brain-science technology.  
(Since then, they've also founded a lobbying group, the Neurotechnology  
Industry Organization.) Casey and Zack met as undergraduates at U.C.L.A.; she  
went on to get a master's degree in neuroscience at U.C.S.F., and he became an  
executive at a software company. Last summer, I had coffee with them in the  
Noe Valley neighborhood of San Francisco, and they both spoke with casual  
certainty about the coming market for neuroenhancers. Zack, who has a book  
being published this summer, called "The Neuro Revolution," said, "We live in  
an information society. What's the next form of human society? The _neuro-  
_society." In coming years, he said, scientists will understand the brain  
better, and we'll have improved neuroenhancers that some people will use  
therapeutically, others because they are "on the borderline of needing them  
therapeutically," and others purely "for competitive advantage."

Zack explained that he didn't really like the term "enhancement": "We're not  
talking about superhuman intelligence. No one's saying we're coming out with a  
pill that's going to make you smarter than Einstein! . . . What we're really  
talking about is *enabling* people." He sketched a bell curve on the back of a  
napkin. "Almost every drug in development is something that will take someone  
who's working at, like, forty per cent or fifty per cent, and take them up to  
eighty," he said.

New psychiatric drugs have a way of creating markets for themselves. Disorders  
often become widely diagnosed after drugs come along that can alter a set of  
suboptimal behaviors. In this way, Ritalin and Adderall helped make A.D.H.D. a  
household name, and advertisements for antidepressants have helped define  
shyness as a malady. If there's a pill that can clear up the wavering focus of  
sleep-deprived youth, or mitigate the tip-of-the-tongue experience of middle  
age, then those rather ordinary states may come to be seen as syndromes. As  
Casey put it, "The drugs get better, and the markets become bigger."

"Yes," Zack said. "We call it the lifestyle-improvement market."

The Lynches said that Provigil was a classic example of a related phenomenon:  
mission creep. In 1998, Cephalon, the pharmaceutical company that manufactures  
it, received government approval to market the drug, but only for "excessive  
daytime sleepiness" due to narcolepsy; by 2004, Cephalon had obtained  
permission to expand the labelling, so that it included sleep apnea and  
"shift-work sleep disorder." Net sales of Provigil climbed from a hundred and  
ninety-six million dollars in 2002 to nine hundred and eighty-eight million in

Cephalon executives have repeatedly said that they do not condone off-label  
use of Provigil, but in 2002 the company was reprimanded by the F.D.A. for  
distributing marketing materials that presented the drug as a remedy for  
tiredness, "decreased activity," and other supposed ailments. And in 2008  
Cephalon paid four hundred and twenty-five million dollars and pleaded guilty  
to a federal criminal charge relating to its promotion of off-label uses for  
Provigil and two other drugs. Later this year, Cephalon plans to introduce  
Nuvigil, a longer-lasting variant of Provigil. Candace Steele, a spokesperson,  
said, "We're exploring its possibilities to treat excessive sleepiness  
associated with schizophrenia, bipolar depression, traumatic injury, and jet  
lag." Though she emphasized that Cephalon was not developing Nuvigil as a  
neuroenhancer, she noted, "As part of the preparation for some of these other  
diseases, we're looking to see if there's improvement in cognition."

Unlike many hypothetical scenarios that bioethicists worry about—human clones,  
"designer babies"—cognitive enhancement is already in full swing. Even if  
today's smart drugs aren't as powerful as such drugs may someday be, there are  
plenty of questions that need to be asked about them. How much do they  
actually help? Are they potentially harmful or addictive? Then, there's the  
question of what we mean by "smarter." Could enhancing one kind of thinking  
exact a toll on others? All these questions need proper scientific answers,  
but for now much of the discussion is taking place furtively, among the  
increasing number of Americans who are performing daily experiments on their  
own brains.

Paul Phillips was unusual for a professional poker player. When he joined the  
circuit, in the late nineties, he was already a millionaire: a twenty-  
something tech guy who had started off writing software, helped found an  
Internet portal called go2net, and cashed in at the right moment. He was  
cerebral and, at times, brusque. His nickname was Dot Com. On the  
international poker-tournament scene—where the male players tend to be either  
unabashedly schlumpy or sharply dressed in the manner of a Vegas hotel  
manager—Phillips cultivated a geeky New Wave style. He wore vintage shirts in  
wild geometric patterns; his hair was dyed orange or silver one week, shaved  
off the next. Most unusual of all, Phillips talked freely about taking  
prescription drugs—Adderall and, especially, Provigil—in order to play better  
cards.

He first took up the game in 1995, when he was in college, at U.C. San Diego.  
He recalled, "It was very mathematical, but you could also inject yourself  
into the game and manipulate the other guy with words"—more so than in a game  
like chess. Phillips soon felt that he had mastered the strategic aspects of  
poker. The key variable was execution. At tournaments, he needed to be able to  
stay focused for fourteen hours at a stretch, often for several days, but he  
found it difficult to do so. In 2003, a doctor gave him a diagnosis of  
A.D.H.D., and he began taking Adderall. Within six months, he had won $1.6  
million at poker events—far more than he'd won in the previous four years.  
Adderall not only helped him concentrate; it also helped him resist the  
impulse to keep playing losing hands out of boredom. In 2004, Phillips asked  
his doctor to give him a prescription for Provigil, which he added to his  
Adderall regimen. He took between two hundred and three hundred milligrams of  
Provigil a day, which, he felt, helped him settle into an even more serene and  
objective state of mindfulness; as he put it, he felt "less like a participant  
than an observer—and a very effective one." Though Phillips sees  
neuroenhancers as essentially steroids for the brain, they haven't yet been  
banned from poker competitions.

Last summer, I visited Phillips in the high-desert resort town of Bend,  
Oregon, where he lives with his wife, Kathleen, and their two daughters, Ivy  
and Ruby. Phillips, who is now thirty-six, seemed a bit out of place in Bend,  
where people spend a lot of time skiing and river rafting. Among the friendly,  
faithfully recycling locals, he was making an effort to curb his caustic side.  
Still, when I first sent Phillips an e-mail asking him to explain, more  
precisely, how Provigil affected him, he couldn't resist a smart-ass answer:  
"More precisely: after a pill is consumed, tiny molecules are absorbed into  
the bloodstream, where they eventually cross the blood-brain barrier and  
influence the operation of the wetware up top."

&[lt;img alt=""I said 'neighborhood watch they said 'peeping Tom.""  
class="ResponsiveImageContainer-dlOMGF byslZC responsive-image__image"  
src="https://media.newyorker.com/cartoons/593b663c5d2f45736c34cfbe/master/w_1600%2Cc_limit/090427_a14091_p465.jpg"  
srcSet="https://media.newyorker.com/cartoons/593b663c5d2f45736c34cfbe/master/w_120,c_limit/090427_a14091_p465.jpg  
120w,  
https://media.newyorker.com/cartoons/593b663c5d2f45736c34cfbe/master/w_240,c_limit/090427_a14091_p465.jpg  
240w,  
https://media.newyorker.com/cartoons/593b663c5d2f45736c34cfbe/master/w_320,c_limit/090427_a14091_p465.jpg  
320w,  
https://media.newyorker.com/cartoons/593b663c5d2f45736c34cfbe/master/w_640,c_limit/090427_a14091_p465.jpg  
640w,  
https://media.newyorker.com/cartoons/593b663c5d2f45736c34cfbe/master/w_960,c_limit/090427_a14091_p465.jpg  
960w,  
https://media.newyorker.com/cartoons/593b663c5d2f45736c34cfbe/master/w_1280,c_limit/090427_a14091_p465.jpg  
1280w,  
https://media.newyorker.com/cartoons/593b663c5d2f45736c34cfbe/master/w_1600,c_limit/090427_a14091_p465.jpg  
1600w" sizes="100vw"/>](https://www.newyorker.com/cartoon/a14091)"I said  
'neighborhood watch'; they said 'peeping Tom.'"

In person, he was more obliging. He picked me up at the Bend airport driving a  
black convertible BMW, and we went for coffee at a cheery café called Thump.  
Phillips wore shorts and flip-flops and his black T-shirt displayed an obscure  
programming joke. "Poker is about sitting in one place, watching your  
opponents for a long time, and making better observations about them than they  
make about you," he said. With Provigil, he "could process all the information  
about what was going on at the table and do something about it." Though there  
is no question that Phillips became much more successful at poker after taking  
neuroenhancers, I asked him if his improvement could be explained by a placebo  
effect, or by coincidence. He doubted it, but allowed that it could. Still, he  
said, "there's a sort of clarity I get with Provigil. With Adderall, I'd  
characterize the effect as correction—correction of an underlying condition.  
Provigil feels like enhancement." And, whereas Adderall made him "jittery,"  
Provigil's effects were "completely limited to my brain." He had "zero  
difficulty sleeping."

On the other hand, Phillips said, Provigil's effects "have attenuated over  
time. The body is an amazing adjusting machine, and there's no upside that  
I've been able to see to just taking more." A few years ago, Phillips tired of  
poker, and started playing competitive Scrabble. He was good, but not that  
good. He was older than many of his rivals, and he needed to undertake a lot  
of rote memorization, which didn't come as easily as it once had. "I stopped  
short of memorizing the entire dictionary, and to be really good you have to  
get up to eightand nine-letter words," he told me. "But I did learn every  
word up to five letters, plus maybe ten thousand sevenand eight-letter  
words." Provigil, he said, helped with the memorization process, but "it's not  
going to make you smarter. It's going to make you better able to use the tools  
you have for a sustained period."

Similarly, a journalist I know, who takes the drug when he has to stay up all  
night on deadline, says that it doesn't help in the phase when he's trying to  
figure out what he wants to say or how to structure a story; but, once he's  
arrived at those insights, it helps him stay intent on completing a draft.  
Similarly, a seventy-four-year-old who published a letter in *Nature* last  
year offered a charmingly specific description of his modafinil habit:  
"Previously, I could work competently on the fracture-mechanics of high-silica  
stone (while replicating ancient tool-flaking techniques) for about an hour.  
With modafinil, I could continue for almost three hours."

Cephalon, the Provigil manufacturer, has publicly downplayed the idea that the  
drug can be used as a smart pill. In 2007, the company's founder and C.E.O.,  
Frank Baldino, Jr., told a reporter from the trade journal *Pharmaceutical  
Executive,* "I think if you're tired, Provigil will keep you awake. If you're  
not tired, it's not going to do anything." But Baldino may have been overly  
modest. Only a few studies have been done of Provigil's effects on healthy,  
non-sleep-deprived volunteers, but those studies suggest that Provigil does  
provide an edge, at least for some kinds of challenges. In 2002, researchers  
at Cambridge University gave sixty healthy young male volunteers a battery of  
standard cognitive tests. One group received modafinil; the other got a  
placebo. The modafinil group performed better on several tasks, such as the  
"digit span" test, in which subjects are asked to repeat increasingly longer  
strings of numbers forward, then backward. They also did better in recognizing  
repeated visual patterns and on a spatial-planning challenge known as the  
Tower of London task. (It's not nearly as fun as it sounds.) Writing in the  
journal *Psychopharmacology* , the study's authors said the results suggested  
that "modafinil offers significant potential as a cognitive enhancer."

Phillips told me that, much as he believes in neuroenhancers, he did not want  
to be "the poster boy for smart-in-a-pill." At one point, he said, "We really  
don't know the possible implications for long-term use of these things." (He  
recently stopped taking Provigil every day, replacing it with another  
prescription stimulant.) He found the "arms-race aspect" of cognitive  
enhancement distasteful, and didn't like the idea that parents might force  
their kids to take smart pills. He sighed when I suggested that adults, too,  
might feel coerced into using the drugs. "Yeah, in a competitive field—if  
suddenly a quarter of the people are more equipped, but you don't want to take  
the risks with your body—it could begin to seem terribly unfair," he said. "I  
don't think we need to be turning up the crank another notch on how hard we  
work. But the fact is, the baseline competitive level is going to reorient  
around what these drugs make possible, and you can choose to compete or not."

In the afternoon, we drove over to Phillips's house—a big place, handsome and  
new, with a sweeping deck overhanging the Deschutes River. Inside, toys were  
strewn across the shag carpeting. Phillips was waiting for his wife and  
daughters to come home from the swimming pool, and, sitting in his huge, high-  
ceilinged living room, he looked a little bored. He told me that he had  
recently decided to apply to graduate school in computer programming. It was  
going to be hard—getting out all those applications, convincing graduate  
programs that he was serious about returning to school. But he had, as he put  
it, "exhausted myself on all forms of leisure," and felt nostalgic for his  
last two years of college, when he had discovered computer programming. "That  
was the most purely intellectually satisfying period of my whole life," he  
said. "It transformed my brain from being all over the place to a reasonable  
edifice of knowledge about something." Back then, he hadn't taken any smart  
pills. "I would have been a freakin' dynamo in college if I'd been taking  
them," he said. "But, still, I had to *find* computers. That made a bigger  
difference than anything else—finding something I just couldn't get enough  
of."

Provigil may well confer a temporary advantage on healthy people, but this  
doesn't mean that it's ready to replace your morning espresso. Anjan  
Chatterjee told me that there "just aren't enough studies of these drugs in  
normal people." He said, "In the situations where they do help, do they come  
with a cost?" As he wrote in a recent letter to *Nature* , "Most seasoned  
physicians have had the sobering experience of prescribing medications that,  
despite good intentions, caused bad outcomes." Given that cognitive  
enhancement is a choice, not a necessity, the cost-benefit calculation for  
neuroenhancers should probably be different than it is for, say, heart  
medications.

Provigil can be habit-forming. In a study published recently in the *Journal  
of the American Medical Association* , a group led by Nora Volkow, the  
director of the National Institute on Drug Abuse, scanned the brains of ten  
men after they had been given a placebo, and also after they had been given a  
dose of modafinil. The modafinil appeared to lead to an increase in the brain  
chemical dopamine. "Because drugs that increase dopamine have the potential  
for abuse," Volkow's report concluded, "these results suggest that risk for  
addiction in vulnerable persons merits heightened awareness." (Cephalon, in a  
response to the report, notes that Provigil's label urges physicians to  
monitor patients closely, especially those with a history of drug abuse.) On  
the Web site Erowid, where people vividly, and anonymously, report their  
experiences with legal and illegal drugs, some modafinil users have described  
a dependency on the drug. One man, who identified himself as a former  
biochemistry student, said that he had succeeded in kicking cocaine and opiate  
habits but couldn't stop using modafinil. Whenever he ran out of the drug, he  
said, "I start to freak out." After "4-5 days" without it, "the head fog  
starts to come back."

&[lt;img alt=""A group of taxpayers are here to give you your bonus sir.""  
class="ResponsiveImageContainer-dlOMGF byslZC responsive-image__image"  
src="https://media.newyorker.com/cartoons/593b663ec195de33cba591b4/master/w_1600%2Cc_limit/090427_a14125_p465.jpg"  
srcSet="https://media.newyorker.com/cartoons/593b663ec195de33cba591b4/master/w_120,c_limit/090427_a14125_p465.jpg  
120w,  
https://media.newyorker.com/cartoons/593b663ec195de33cba591b4/master/w_240,c_limit/090427_a14125_p465.jpg  
240w,  
https://media.newyorker.com/cartoons/593b663ec195de33cba591b4/master/w_320,c_limit/090427_a14125_p465.jpg  
320w,  
https://media.newyorker.com/cartoons/593b663ec195de33cba591b4/master/w_640,c_limit/090427_a14125_p465.jpg  
640w,  
https://media.newyorker.com/cartoons/593b663ec195de33cba591b4/master/w_960,c_limit/090427_a14125_p465.jpg  
960w,  
https://media.newyorker.com/cartoons/593b663ec195de33cba591b4/master/w_1280,c_limit/090427_a14125_p465.jpg  
1280w,  
https://media.newyorker.com/cartoons/593b663ec195de33cba591b4/master/w_1600,c_limit/090427_a14125_p465.jpg  
1600w" sizes="100vw"/>](https://www.newyorker.com/cartoon/a14125)"A group of  
taxpayers are here to give you your bonus, sir."

Eliminating foggy-headedness seems to be the goal of many users of  
neuroenhancers. But can today's drugs actually accomplish this? I recently  
posed this question to Anjan Chatterjee's colleague Martha Farah, who is a  
psychologist at Penn and the director of its Center for Cognitive  
Neuroscience. She has been writing about neuroenhancers for several years from  
a perspective that is deeply fascinated and mildly critical, but basically in  
favor—with the important caveat that we need to know much more about how these  
drugs work. I spoke with her one afternoon at her research center, which is in  
a decidedly unfuturistic-looking Victorian house on Walnut Street, in  
Philadelphia. Farah, who is an energetic conversationalist, had bought canned  
espresso drinks for us. Though she does not take neuroenhancers, she has found  
that her interest in them has renewed her romance with the next best thing:  
caffeine.

Farah had just finished a paper in which she reviewed the evidence on  
prescription stimulants as neuroenhancers from forty laboratory studies  
involving healthy subjects. Most of the studies looked at one of three types  
of cognition: learning, working memory, and cognitive control. A typical  
learning test asks subjects to memorize a list of paired words; an hour, a few  
days, or a week later, they are presented with the first words in the pairs  
and asked to come up with the second. The studies on learning showed that  
neuroenhancers did improve retention. The benefits were more apparent in  
studies where subjects had been asked to remember information for several days  
or longer.

Working memory has been likened to a mental scratch pad: you use it to keep  
relevant data in mind while you're completing a task. (Imagine a cross-  
examination, in which a lawyer has to keep track of the answers a witness has  
given, and formulate new questions based on them.) In one common test,  
subjects are shown a series of items—usually letters or numbers—and then  
presented with challenges: Was this number or letter in the series? Was this  
one? In the working-memory tests, subjects performed better on neuroenhancers,  
though several of the studies suggested that the effect depended on how good a  
subject's working memory was to begin with: the better it was, the less  
benefit the drugs provided.

The third category that the studies examined was cognitive control—how  
effectively you can check yourself in circumstances where the most natural  
response is the wrong one. A classic test is the Stroop Task, in which people  
are shown the name of a color (let's say orange) written in a different color  
(let's say purple). They're asked to read the word (which is easy, because our  
habitual response to a word is to read it) or to name the ink color (which is  
harder, because our first impulse is to say "orange"). These studies presented  
a more mixed picture, but over all they showed some benefit "for most normal  
healthy subjects"—especially for people who had inherently poorer cognitive  
control.

Farah told me, "These drugs will definitely help some technically normal  
people—that is, people who don't meet the diagnostic criteria for A.D.H.D. or  
any kind of cognitive impairment." But, she emphasized, "they will help people  
in the lower end of the ability range more than in the higher end." One  
explanation for this phenomenon might be that, the more adept you are at a  
given task, the less room you have to improve. Farah has a hunch that there  
may be another reason that existing drugs, so far, at least, don't offer as  
much help to people with greater intellectual abilities. Drugs like Ritalin  
and Adderall work, in part, by elevating the amount of dopamine in the brain.  
Dopamine is something you want just enough of: too little, and you may not be  
as alert and motivated as you need to be; too much, and you may feel  
overstimulated. Neuroscientists have discovered that some people have a gene  
that leads the brain to break down dopamine faster, leaving less of it  
available; such people are generally a little worse at certain cognitive  
tasks. People with more available dopamine are generally somewhat better at  
the same tasks. It makes sense, then, that people with naturally low dopamine  
would benefit more from an artificial boost.

Of course, learning, working memory, and cognitive control represent just a  
few aspects of thinking. Farah concluded that studies looking at other kinds  
of cognition—verbal fluency, for instance—were too few and too contradictory  
to tell us much. And the effects of neuroenhancers on some vital forms of  
intellectual activity, such as abstract thought and creativity, have barely  
been studied at all. Farah said that the extant literature was concerned with  
"fairly boring kinds of thinking—how long can you stay vigilant while staring  
at a screen and waiting for a little light to blink." She added, "It would be  
great to have studies of more flexible kinds of thought."

Both Chatterjee and Farah have wondered whether drugs that heighten users'  
focus might dampen their creativity. After all, some of our best ideas come to  
us not when we sit down at a desk but, rather, when we're in the shower or  
walking the dog—letting our minds roam. Jimi Hendrix reported that the  
inspiration for "Purple Haze" came to him in a dream; the chemist Friedrich  
August Kekule claimed that he discovered the ring structure of benzene during  
a reverie in which he saw the image of a snake biting its tail. Farah told me,  
"Cognitive psychologists have found that there is a trade-off between  
attentional focus and creativity. And there is some evidence that suggests  
that individuals who are better able to focus on one thing and filter out  
distractions tend to be less creative."

Farah and Chatterjee recently completed a preliminary study looking at the  
effect of one ten-milligram dose of Adderall on sixteen students doing  
standard laboratory tests of creative thinking. They did not find that this  
low dose had a detrimental effect, but both believe that this is only the  
beginning of the vetting that must be done. "More and more of our young people  
are using these drugs to help them work," Farah said. "They've got their  
laptop, their iPhone, and their Adderall. This rising generation of workers  
and leaders may have a subtly different style of thinking and working, because  
they're using these drugs or because they learned to work using these drugs,  
so that even if you take the drugs away they'll still have a certain approach.  
I'm a little concerned that we could be raising a generation of very focused  
accountants."

Farah has also been considering the ethical complications resulting from the  
rise of smart drugs. Don't neuroenhancers confer yet another advantage on the  
kind of people who already can afford private tutors and prep courses? At many  
colleges, students have begun calling the off-label use of neuroenhancers a  
form of cheating. Writing last year in the *Cavalier Daily* , the student  
newspaper of the University of Virginia, a columnist named Greg Crapanzano  
argued that neuroenhancers "create an unfair advantage for the users who are  
willing to break the law in order to gain an edge. These students create work  
that is dependent on the use of a pill rather than their own work ethic." Of  
course, it's hard to imagine a university administration that would require  
students to pee in a cup before they get their blue books. And though secretly  
taking a neuroenhancer for a three-hour exam does seem unfair, condemning the  
drugs' use seems extreme. Even with the aid of a neuroenhancer, you still have  
to write the essay, conceive the screenplay, or finish the grant proposal, and  
if you can take credit for work you've done on caffeine or nicotine, then you  
can take credit for work produced on Provigil.

&[lt;img alt=""If you want a positive outlook youre going to have to turn your  
chair around Walter."" class="ResponsiveImageContainer-dlOMGF byslZC  
responsive-image__image"  
src="https://media.newyorker.com/cartoons/593b664057b86d47b169c915/master/w_1600%2Cc_limit/090427_a13945_p465.jpg"  
srcSet="https://media.newyorker.com/cartoons/593b664057b86d47b169c915/master/w_120,c_limit/090427_a13945_p465.jpg  
120w,  
https://media.newyorker.com/cartoons/593b664057b86d47b169c915/master/w_240,c_limit/090427_a13945_p465.jpg  
240w,  
https://media.newyorker.com/cartoons/593b664057b86d47b169c915/master/w_320,c_limit/090427_a13945_p465.jpg  
320w,  
https://media.newyorker.com/cartoons/593b664057b86d47b169c915/master/w_640,c_limit/090427_a13945_p465.jpg  
640w,  
https://media.newyorker.com/cartoons/593b664057b86d47b169c915/master/w_960,c_limit/090427_a13945_p465.jpg  
960w,  
https://media.newyorker.com/cartoons/593b664057b86d47b169c915/master/w_1280,c_limit/090427_a13945_p465.jpg  
1280w,  
https://media.newyorker.com/cartoons/593b664057b86d47b169c915/master/w_1600,c_limit/090427_a13945_p465.jpg  
1600w" sizes="100vw"/>](https://www.newyorker.com/cartoon/a13945)"If you want  
a positive outlook, you're going to have to turn your chair around, Walter."

Farah questions the idea that neuroenhancers will expand inequality. Citing  
the "pretty clear trend across the studies that say neuroenhancers will be  
less helpful for people who score above average," she said that cognitive-  
enhancing pills could actually become levellers, if they are dispensed  
cheaply. A 2007 discussion paper published by the British Medical Association  
also makes this point: "Equality of opportunity is an explicit goal of our  
education system, giving individuals the best chance of achieving their full  
potential and of competing on equal terms with their peers. Selective use of  
neuroenhancers amongst those with lower intellectual capacity, or those from  
deprived backgrounds who do not have the benefit of additional tuition, could  
enhance the educational opportunities for those groups." If the idea of giving  
a pill as a substitute for better teaching seems repellent—like substituting  
an I.V. drip of synthetic nutrition for actual food—it may nevertheless be  
preferable to a scenario in which only wealthy kids receive a frequent mental  
boost.

Farah was one of several scholars who contributed to a recent article in  
*Nature* , "Towards Responsible Use of Cognitive Enhancing Drugs by the  
Healthy." The optimistic tone of the article suggested that some bioethicists  
are leaning toward endorsing neuroenhancement. "Like all new technologies,  
cognitive enhancement can be used well or poorly," the article declared. "We  
should welcome new methods of improving our brain function. In a world in  
which human workspans and lifespans are increasing, cognitive enhancement  
tools—including the pharmacological—will be increasingly useful for improved  
quality of life and extended work productivity, as well as to stave off normal  
and pathological age-related cognitive declines. Safe and effective cognitive  
enhancers will benefit both the individual and society." The British Medical  
Association report offered a similarly upbeat observation: "Universal access  
to enhancing interventions would bring up the base-line level of cognitive  
ability, which is generally seen to be a good thing."

And yet when enthusiasts share their vision of our neuroenhanced future it can  
sound dystopian. Zack Lynch, of NeuroInsights, gave me a rationale for smart  
pills that I found particularly grim. "If you're a fifty-five-year-old in  
Boston, you have to compete with a twenty-six-year-old from Mumbai now, and  
those kinds of pressures are only going to grow," he began. Countries other  
than the U.S. might tend to be a little looser with their regulations, and  
offer approval of new cognitive enhancers first. "And if you're a company  
that's got forty-seven offices worldwide, and all of a sudden your Singapore  
office is using cognitive enablers, and you're saying to Congress, 'I'm moving  
all my financial operations to Singapore and Taiwan, because it's legal to use  
those there,' you bet that Congress is going to say, 'Well, O.K.' It will be a  
moot question then. It would be like saying, 'No, you can't use a cell phone.  
It might increase productivity!' "

If we eventually decide that neuroenhancers work, and are basically safe, will  
we one day enforce their use? Lawmakers might compel certain  
workers—emergency-room doctors, air-traffic controllers—to take them. (Indeed,  
the Air Force already makes modafinil available to pilots embarking on long  
missions.) For the rest of us, the pressure will be subtler—that queasy  
feeling I get when I remember that my younger colleague is taking Provigil to  
meet deadlines. All this may be leading to a kind of society I'm not sure I  
want to live in: a society where we're even more overworked and driven by  
technology than we already are, and where we have to take drugs to keep up; a  
society where we give children academic steroids along with their daily  
vitamins.

Paul McHugh, a psychiatrist at Johns Hopkins University, has written  
skeptically about cosmetic neurology. In a 2004 essay, he notes that at least  
once a year in his private practice he sees a young person—usually a boy—whose  
parents worry that his school performance could be better, and want a  
medication that will assure it. In most of these cases, "the truth is that the  
son does not have the superior I.Q. of his parents," though the boy may have  
other qualities that surpass those of his parents—he may be "handsome,  
charming, athletic, graceful." McHugh sees his job as trying to get the  
parents to "forget about adjusting him to their aims with medication or  
anything else." When I spoke with him on the phone, McHugh expanded on this  
point: "Maybe it's wrong-footed trying to fit people into the world, rather  
than trying to make the world a better place for people. And if the idea is  
that the only college your child can go to is Harvard, well, maybe *that's*  
the idea that needs righting."

If Alex, the Harvard student, and Paul Phillips, the poker player, consider  
their use of neuroenhancers a private act, Nicholas Seltzer sees his habit as  
a pursuit that aligns him with a larger movement for improving humanity.  
Seltzer has a B.A. from U.C. Davis and a master's degree in security policy  
from George Washington University. But the job that he obtained with these  
credentials—as a researcher at a defense-oriented think tank, in northern  
Virginia—has not left him feeling as intellectually alive as he would like. To  
compensate, he writes papers in his spare time on subjects like "human  
biological evolution and warfare." He also primes his brain with artificial  
challenges; even when he goes to the rest room at the office, he takes the  
opportunity to play memory or logic games on his cell phone. Seltzer, who is  
thirty, told me that he worried that he "didn't have the mental energy, the  
endurance, the—I don't know what to properly call this—the *sponginess* that I  
seem to recall having when I was younger."

Suffice it to say that this is not something you notice when you talk to  
Seltzer. And though our memory is probably at its peak in our early twenties,  
few thirty-year-olds are aware of a deficit. But Seltzer is the Washington-  
wonk equivalent of those models and actors in L.A. who discern tiny wrinkles  
long before their agent does. His girlfriend, a technology consultant whom he  
met in a museum, is nine years younger, and he was already thinking about how  
his mental fitness would stand up next to hers. He told me, "She's twenty-one,  
and I want to stay young and vigorous and don't want to be a burden on her  
later in life." He didn't worry about visible signs of aging, but he wanted to  
keep his mind "nimble and healthy for as long as possible."

Seltzer considers himself a "transhumanist," in the mold of the Oxford  
philosopher Nick Bostrom and the futurist writer and inventor Ray Kurzweil.  
Transhumanists are interested in robots, cryogenics, and living a really,  
really long time; they consider biological limitations that the rest of us  
might accept, or even appreciate, as creaky obstacles to be aggressively  
surmounted. On the ImmInst forums—"ImmInst" stands for "Immortality  
Institute"—Seltzer and other members discuss life-extension strategies and the  
potential benefits of cognitive enhancers. Some of the forum members limit  
themselves to vitamin and mineral supplements. Others use Adderall or  
modafinil or, like Seltzer, a drug called piracetam, which was first marketed  
by a Belgian pharmaceutical company in 1972 and, in recent years, has become  
available in the U.S. from retailers that sell supplements. Although not  
approved for any use by the F.D.A., piracetam has been used experimentally on  
stroke patients—to little effect—and on patients with a rare neurological  
condition called progressive myoclonus epilepsy, for whom it proved helpful in  
alleviating muscle spasms. Data on piracetam's benefits for healthy people are  
virtually nonexistent, but many users believe that the drug increases blood  
flow to the brain.

&[lt;img alt="The Underground World of "Neuroenhancing" Drugs"  
class="ResponsiveImageContainer-dlOMGF byslZC responsive-image__image"  
src="https://media.newyorker.com/cartoons/593b664c8eb5ba7066584315/master/w_1600%2Cc_limit/090427_a13704_p465.jpg"  
srcSet="https://media.newyorker.com/cartoons/593b664c8eb5ba7066584315/master/w_120,c_limit/090427_a13704_p465.jpg  
120w,  
https://media.newyorker.com/cartoons/593b664c8eb5ba7066584315/master/w_240,c_limit/090427_a13704_p465.jpg  
240w,  
https://media.newyorker.com/cartoons/593b664c8eb5ba7066584315/master/w_320,c_limit/090427_a13704_p465.jpg  
320w,  
https://media.newyorker.com/cartoons/593b664c8eb5ba7066584315/master/w_640,c_limit/090427_a13704_p465.jpg  
640w,  
https://media.newyorker.com/cartoons/593b664c8eb5ba7066584315/master/w_960,c_limit/090427_a13704_p465.jpg  
960w,  
https://media.newyorker.com/cartoons/593b664c8eb5ba7066584315/master/w_1280,c_limit/090427_a13704_p465.jpg  
1280w,  
https://media.newyorker.com/cartoons/593b664c8eb5ba7066584315/master/w_1600,c_limit/090427_a13704_p465.jpg  
1600w" sizes="100vw"/>](https://www.newyorker.com/cartoon/a13704)

From the time I first talked to Seltzer, it was clear that although he felt  
cognitive enhancers were of practical use, they also appealed to him on an  
aesthetic level. Using neuroenhancers, he said, "is like customizing  
yourself—customizing your brain." For some people, he went on, it was  
important to enhance their mood, so they took antidepressants; but for people  
like him it was more important "to increase mental horsepower." He added,  
"It's fundamentally a choice you're making about how you want to experience  
consciousness." Whereas the nineties had been about "the personalization of  
technology," this decade was about the personalization of the brain—what some  
enthusiasts have begun to call "mind hacking."

Of course, the idea behind mind-hacking isn't exactly new. Fortifying one's  
mental stamina with drugs of various kinds has a long history. Sir Francis  
Bacon consumed everything from tobacco to saffron in the hope of goosing his  
brain. Balzac reputedly fuelled sixteen-hour bouts of writing with copious  
servings of coffee, which, he wrote, "chases away sleep, and gives us the  
capacity to engage a little longer in the exercise of our intellects." Sartre  
dosed himself with speed in order to finish "Critique of Dialectical Reason."  
My college friends and I wrote term papers with the sweaty-palmed assistance  
of NoDoz tablets. And, before smoking bans, entire office cultures chugged  
along on a collective nicotine buzz—at least, if "Mad Men" is to be believed.  
Seltzer and his interlocutors on the ImmInst forum are just the latest members  
of a seasoned cohort, even if they have more complex pharmaceuticals at their  
disposal.

I eventually met Seltzer in an underground food court not far from the  
Pentagon. We sat down at a Formica table in the dim light. Seltzer was slim,  
had a shaved head, and wore metal-frame glasses; matching his fastidious look,  
he spoke precisely, rarely stumbling over his words. I asked him if he had any  
ethical worries about smart drugs. After a pause, he said that he might have a  
concern if somebody popped a neuroenhancer before taking a licensing exam that  
certified him as, say, a brain surgeon, and then stopped using the drug. Other  
than that, he couldn't see a problem. He said that he was a firm believer in  
the idea that "we should have a fair degree of liberty to do with our bodies  
and our minds as we see fit, so long as it doesn't impinge on the basic  
rights, liberty, and safety of others." He argued, "Why would you *want* an  
upward limit on the intellectual capabilities of a human being? And, if you  
have a very nationalist viewpoint, why wouldn't you want our country to have  
the advantage over other countries, particularly in what some people call a  
knowledge-based economy?" He went on, "Think about the complexity of the  
intellectual tasks that people need to accomplish today. Just trying to  
understand what Congress is doing is not a simple thing! The complexity of  
understanding the gamut of scientific and technical and social issues is  
difficult. If we had a tool that enabled more people to understand the world  
at a greater level of sophistication, how can we prejudice ourselves against  
the notion, simply because we don't like athletes to do it? To me, it doesn't  
seem like the same question. And it deserves its own debate."

Seltzer had never had a diagnosis of any kind of learning disorder. But he  
added, "Though I wouldn't say I'm dyslexic, sometimes when I type prose, after  
I look back and read it, I've frequently left out words or interposed words,  
and sometimes I have difficulty concentrating." In graduate school, he  
obtained a prescription for Adderall from a doctor who didn't ask a lot of  
questions. The drug helped him, especially when his ambitions were relatively  
low. He recalled, "I had this one paper, on nuclear strategy. The professor  
didn't look favorably on any kind of creative thinking." On Adderall, he  
pumped out the paper in an evening. "I just bit my tongue, regurgitated, and  
got a good-enough grade."

On the other hand, Seltzer recalled that he had taken piracetam to write an  
essay on "the idea of harmony as a trope in Chinese political discourse"—it  
was one of the papers he was proudest of. He said, "It was really an  
intellectual challenge to do. I felt that the piracetam helped me to work  
within the realm of the abstract, and make the kind of associations that I  
needed—following this idea of harmony from an ancient religious belief as it  
was translated throughout the centuries into a very important topic in  
political discourse."

After a hiatus of several years, Seltzer had recently resumed taking  
neuroenhancers. In addition to piracetam, he took a stack of supplements that  
he thought helped his brain functioning: fish oils, five antioxidants, a  
product called ChocoMind, and a number of others, all available at the health-  
food store. He was thinking about adding modafinil, but hadn't yet. For  
breakfast every morning, he concocted a slurry of oatmeal, berries, soy milk,  
pomegranate juice, flaxseed, almond meal, raw eggs, and protein powder. The  
goal behind the recipe was efficiency: to rely on "one goop you could eat or  
drink that would have everything you need nutritionally for your brain and  
body." He explained, "Taste was the last thing on my mind; I wanted to be able  
to keep it down—that was it." (He told me this in the kitchen of his  
apartment; he lives with a roommate, who walked in while we were talking,  
listened perplexedly for a moment, then put a frozen pizza in the oven.)

Seltzer's decision to take piracetam was based on his own online reading,  
which included medical-journal abstracts. He hadn't consulted a doctor. Since  
settling on a daily regimen of supplements, he had sensed an improvement in  
his intellectual work and his ability to engage in stimulating conversation.  
He continued, "I feel I'm better able to articulate my thoughts. I'm sure  
you've been in the zone—you're having a really exciting debate with somebody,  
your brain feels alive. I feel that more. But I don't want to say that it's  
this profound change."

I asked him if piracetam made him feel smarter, or just more alert and  
confident—a little better equipped to marshal the resources he naturally had.  
"Maybe," he said. "I'm not sure what being smarter means, entirely. It's a  
difficult quality to measure. It's the gestalt factor, all these qualities  
coming together—not only your ability to crunch some numbers, or remember some  
figures or a sequence of numbers, but also your ability to maintain a certain  
emotional state that is conducive to productive intellectual work. I do feel  
I'm more intelligent with the drugs, but I can't give you a number of I.Q.  
points."

The effects of piracetam on healthy volunteers have been studied even less  
than those of Adderall or modafinil. Most peer-reviewed studies focus on its  
effects on dementia, or on people who have suffered a seizure or a concussion.  
Many of the studies that look at other neurological effects were performed on  
rats and mice. Piracetam's mechanisms of action are not understood, though it  
may increase levels of the neurotransmitter acetylcholine. In 2008, a  
committee of the British Academy of Medical Sciences noted that many of the  
clinical trials of piracetam for dementia were methodologically flawed.  
Another published review of the available studies of the drug concluded that  
the evidence "does not support the use of piracetam in the treatment of people  
with dementia or cognitive impairment," but suggested that further  
investigation might be warranted. I asked Seltzer if he thought he should wait  
for scientific ratification of piracetam. He laughed. "I don't want to," he  
said. "Because it's working."

&[lt;img alt=""In light of recent events Im afraid Im going to have to eat  
some of you."" class="ResponsiveImageContainer-dlOMGF byslZC responsive-  
image__image"  
src="https://media.newyorker.com/cartoons/593b664f8a032b339a0cd72e/master/w_1600%2Cc_limit/090427_a14089_p465.jpg"  
srcSet="https://media.newyorker.com/cartoons/593b664f8a032b339a0cd72e/master/w_120,c_limit/090427_a14089_p465.jpg  
120w,  
https://media.newyorker.com/cartoons/593b664f8a032b339a0cd72e/master/w_240,c_limit/090427_a14089_p465.jpg  
240w,  
https://media.newyorker.com/cartoons/593b664f8a032b339a0cd72e/master/w_320,c_limit/090427_a14089_p465.jpg  
320w,  
https://media.newyorker.com/cartoons/593b664f8a032b339a0cd72e/master/w_640,c_limit/090427_a14089_p465.jpg  
640w,  
https://media.newyorker.com/cartoons/593b664f8a032b339a0cd72e/master/w_960,c_limit/090427_a14089_p465.jpg  
960w,  
https://media.newyorker.com/cartoons/593b664f8a032b339a0cd72e/master/w_1280,c_limit/090427_a14089_p465.jpg  
1280w,  
https://media.newyorker.com/cartoons/593b664f8a032b339a0cd72e/master/w_1600,c_limit/090427_a14089_p465.jpg  
1600w" sizes="100vw"/>](https://www.newyorker.com/cartoon/a14089)"In light of  
recent events, I'm afraid I'm going to have to eat some of you."

It makes no sense to ban the use of neuroenhancers. Too many people are  
already taking them, and the users tend to be educated and privileged people  
who proceed with just enough caution to avoid getting into trouble. Besides,  
Anjan Chatterjee is right that there is an apt analogy with plastic surgery.  
In a consumer society like ours, if people are properly informed about the  
risks and benefits of neuroenhancers, they can make their own choices about  
how to alter their minds, just as they can make their own decisions about  
shaping their bodies.

Still, even if you acknowledge that cosmetic neurology is here to stay, there  
is something dispiriting about the way the drugs are used—the kind of  
aspirations they open up, or don't. Jonathan Eisen, an evolutionary biologist  
at U.C. Davis, is skeptical of what he mockingly calls "brain doping." During  
a recent conversation, he spoke about colleagues who take neuroenhancers in  
order to grind out grant proposals. "It's weird to me that people are taking  
these drugs to write grants," he said. "I mean, if you came up with some  
really interesting paper that was *spurred* by taking some really interesting  
drug—magic mushrooms or something—that would make more sense to me. In the  
end, you're only as good as the ideas you've come up with."

But it's not the mind-expanding sixties anymore. Every era, it seems, has its  
own defining drug. Neuroenhancers are perfectly suited for the anxiety of  
white-collar competition in a floundering economy. And they have a synergistic  
relationship with our multiplying digital technologies: the more gadgets we  
own, the more distracted we become, and the more we need help in order to  
focus. The experience that neuroenhancement offers is not, for the most part,  
about opening the doors of perception, or about breaking the bonds of the  
self, or about experiencing a surge of genius. It's about squeezing out an  
extra few hours to finish those sales figures when you'd really rather  
collapse into bed; getting a B instead of a B-minus on the final exam in a  
lecture class where you spent half your time texting; cramming for the G.R.E.s  
at night, because the information-industry job you got after college turned  
out to be deadening. Neuroenhancers don't offer freedom. Rather, they  
facilitate a pinched, unromantic, grindingly efficient form of productivity.

This winter, I spoke again with Alex, the Harvard graduate, and found that,  
after a break of several months, he had gone back to taking Adderall—a small  
dose every day. He felt that he was learning to use the drug in a more  
"disciplined" manner. Now, he said, it was less about staying up late to  
finish work he should have done earlier, and more "about staying focused on  
work, which makes me want to work longer hours." What employer would object to  
that? ♦

* * *

Posted  
by[Dsmith](https://begininfiniteloop.wordpress.com/author/f4ultyc0d3/)[April  
1, 2022](https://begininfiniteloop.wordpress.com/2022/04/01/the-underground-  
world-of-neuroenhancing-drugs-the-new-yorker/)Posted  
in[adderall](https://begininfiniteloop.wordpress.com/category/adderall/)Tags:[adderall](https://begininfiniteloop.wordpress.com/tag/adderall/)[Leave  
a comment on The Underground World of "Neuroenhancing" Drugs | The New  
Yorker](https://begininfiniteloop.wordpress.com/2022/04/01/the-underground-  
world-of-neuroenhancing-drugs-the-new-yorker/#respond)

# [Long-Term Side Effects of Adderall on Brain, Personality &

Body](https://begininfiniteloop.wordpress.com/2022/04/01/long-term-side-  
effects-of-adderall-on-brain-personality-body/)

What Are The Long-Term Effects of Heavy Adderall Use?

People who abuse a great deal of Adderall over a long period of time may  
experience side effects ranging from sleep difficulties, depression, and  
irritability to mood swings, paranoia, and panic attacks. A list of side  
effects of long-term Adderall abuse are below:

[Spanish Version](https://americanaddictioncenters.org/adderall/long-term-  
effects/esp)

# What is Adderall & How Does it Work?

[Adderall](https://americanaddictioncenters.org/adderall) (amphetamine-  
dextroamphetamine) is a prescription medication composed of amphetamine and  
dextroamphetamine. It is primarily used in the treatment of attention deficit  
hyperactivity disorder ([ADHD](https://americanaddictioncenters.org/adhd-and-  
addiction)) and narcolepsy. At the neurological level, Adderall binds to  
norepinephrine and dopamine receptors in the brain as well as epinephrine  
receptors in the adrenal gland. As a result, there is an increase in the level  
of "feel-good" chemicals in the brain, which improves the individual's  
concentration, alertness, and focus but also causes euphoria.

# Adderall Statistics & Use in the United States

> Close to 50 million prescription stimulant drugs like Adderall were  
> dispensed in 2011 to treat symptoms of attention deficit hyperactivity  
> disorder, or ADHD.

![adderall abuse](https://admin.americanaddictioncenters.org/wp-  
content/uploads/2015/10/adderall-abuse.jpg)adderall abuse

This represents an almost 40 percent rise in these prescriptions since 2007,  
the [Drug Enforcement  
Agency](https://www.deadiversion.usdoj.gov/nflis/spec_rpt_adhd_2012.pdf) (DEA)  
states. ADHD is one of the most common childhood neurobiological disorders.  
The [Centers for Disease Control and  
Prevention](http://www.cdc.gov/nchs/fastats/adhd.htm) (CDC) reported that as  
of July 2015, almost 10 percent, or close to 6 million, American children  
between the ages of 4 and 17 had been diagnosed with ADHD at some point in  
their lifetimes.

AAC is in-network with many insurance providers. Addiction treatment can be  
free depending on your policy.

![adderall abuse rates college](https://admin.americanaddictioncenters.org/wp-  
content/uploads/2015/10/adderall-abuse-rates-college.jpg)adderall abuse rates  
college

As prescriptions for Adderall rise, so may its potential for diversion and  
nonmedical use, which increases its health risks too. Adderall is abused as a  
["smart drug" across college  
campuses](https://americanaddictioncenters.org/adderall/adderall-abuse-among-  
college-students). It may be abused by students to combat pressures of higher  
education, as students perceive it will help them get better grades because  
they can stay up and study for longer.

A study at the University of Kentucky found that 30 percent of its students  
had abused an ADHD stimulant drug like Adderall at some point as a possible  
"study enhancer," *CNN* reports.

Adderall also suppresses the appetite and may also be abused as a weight loss  
drug. Other times it may be used in conjunction with other drugs or alcohol  
recreationally, or to get "high." Mixing Adderall with other substances can be  
very dangerous and may more easily result in a life-threatening overdose or  
negative interaction between the substances.

> Stimulant drugs like Adderall are addictive and using them recreationally  
> may increase the chances of developing a psychological and physical  
> dependence on them.

Adderall's side effects include: physical damage to the brain, internal  
systems, and organs.

# Ways to Get in Contact With Us

If you believe you or someone you love may be struggling with addiction, let  
us hear your story and help you determine a path to treatment.

There are a variety of confidential, free, and no obligation ways to get in  
contact with us to learn more about treatment.

  * Call us at or [get a text](/not-ready-to-talk) for information on various treatment options. There, you can talk to one of our admissions advisors where we can answer any questions you might have about treatment or insurance coverage for you or a loved one.

  * Fill in our online insurance verification form below to find out if your insurance provider may be able to cover the cost of treatment. Our admissions advisors may contact you thereafter to discuss your options.  

Check to see if your insurance is in-network at an American Addiction Centers  
location

We'll instantly check the coverage offered by your insurance provider.

You may receive treatment at one of our facilities at a reduced rate.

Facilities that specialize in addiction treatment

Click on a pin to learn more information on a specific facility location.

View All Facilities

# How Extended Adderall Use Affects the Brain

[Stimulants](https://americanaddictioncenters.org/stimulant-drugs) increase  
concentration and energy levels while decreasing the need for sleep and  
suppressing the appetite. Adderall increases the activity of several  
neurotransmitters, such as serotonin, norepinephrine, and especially dopamine.  
Over time, the changes in dopamine activity can impact our brain's reward  
center, and alter our ability to experience pleasure without the chemical  
support of continued amphetamine use.. The more often Adderall is taken, the  
more ingrained these changes become. A tolerance to the drug may form, and  
more Adderall may be needed at each dose in order to feel the same desired  
effects.

As Adderall leaves the bloodstream, withdrawal symptoms and drug cravings may  
occur, indicating a physical and emotional dependence on the drug. The way in  
which Adderall is abused, along with the amount and duration of abuse can  
affect the dependence level to the drug. Crushing the pills and then injecting  
or snorting them, for example, sends the drug into the brain more rapidly than  
ingesting them whole and having them enter the bloodstream via the digestive  
tract. As a result, injecting or snorting the crushed pills increases the  
chances for a life-threatening overdose and the potential for addiction.  
Addiction is a disease that affects each person individually, and  
environmental and biological factors may also play a role in its onset.

Someone who is dependent on Adderall may have trouble sleeping and  
concentrating, notice a lack of motivation, and feel depressed, irritable,  
lethargic, or fatigued when it is removed from the body. [Abusing  
amphetamines](https://americanaddictioncenters.org/amphetamine) like Adderall  
may raise the risk of aggression and suicidal thoughts, according to *[ABC  
News](https://abcnews.go.com/Health/MindMoodNews/adderall-psychosis-suicide-  
college-students-abuse-study-drug/story?id=12066619&page=2)*. For someone who  
has been abusing Adderall for an extended period of time, the emotional aspect  
of withdrawal may be the most noticeable side effect. Natural production of  
dopamine is reduced, causing low moods and trouble feeling pleasure without  
the drug.

> The more and longer Adderall is abused, the more pronounced the mood swings  
> may be when it is no longer available in the body. Most of these changes in  
> the brain will likely be repaired over time with sustained abstinence and  
> proper care and support, fortunately.

In some cases, Adderall and other prescription stimulants have been reported  
to cause psychosis and schizophrenia-like symptoms, such as paranoid  
delusions, hallucinations, and other behavioral or mood disturbances,  
according to the journal _[Molecular Psychiatry_  
](<https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2670101/>). Anxiety and panic  
attacks may also be triggered by long-term use of an amphetamine stimulant or  
during Adderall withdrawal. The *[U.S. Food and Drug  
Administration](https://www.accessdata.fda.gov/drugsatfda_docs/label/2007/011522s040lbl.pdf)*  
, or FDA, even prints warnings on Adderall labels about potential negative  
psychiatric side effects. Symptoms may be heightened in someone with a history  
of mental illness or an underlying mental health disorder, such as bipolar  
disorder or schizophrenia.

# Physical Side Effects of Adderall

![Adderall side effects](https://admin.americanaddictioncenters.org/wp-  
content/uploads/2015/10/side-effects-of-adderall-use.jpg)Adderall side effects

Stimulants like Adderall raise body temperature, heart rate, and blood  
pressure, and repeated use or abuse, particularly in high doses, can create a  
range of medical issues from a stroke to a seizure to a heart attack.

Adderall can cause damage to the heart and cardiovascular system when used for  
a prolonged period of time, especially when used in excess. The most common  
ADHD medication cardiovascular problems reported are hypertension (high blood  
pressure) and tachycardia (irregular heart rate), as published by _[Brain and  
Body_](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3489818/). Sudden cardiac  
death may also be a potential side effect of Adderall.

Other side effects of abusing Adderall long-term include:

  * Heart disease

  * Dizziness

  * Abdominal pain

  * Weight loss

  * Insomnia

  * Dry mouth

  * Heart palpitations

  * Headaches

  * Tremors

  * Trouble breathing

  * Constipation

  * Hyperactivity

  * Feeling jittery or "on edge"  

> Using Adderall heavily for a long period of time increases all the risk  
> factors and potential long-term side effects, which may get progressively  
> worse.

The heart muscle may be weakened with prolonged stimulant abuse, leading to  
more complications. Changes in the brain, as well as mood and behavior issues  
related to prolonged Adderall abuse, may also continue unless the drug is  
safely removed from the body.

Detox from Adderall is not sufficient treatment, however. It must be followed  
with a substance abuse treatment program to help prevent relapse and support  
long-term recovery.

* * *

# Article Adderall

Posted  
by[Dsmith](https://begininfiniteloop.wordpress.com/author/f4ultyc0d3/)[April  
1, 2022](https://begininfiniteloop.wordpress.com/2022/04/01/long-term-side-  
effects-of-adderall-on-brain-personality-body/)Posted  
in[adderall](https://begininfiniteloop.wordpress.com/category/adderall/)Tags:[adderall](https://begininfiniteloop.wordpress.com/tag/adderall/)[Leave  
a comment on Long-Term Side Effects of Adderall on Brain, Personality &  
Body](https://begininfiniteloop.wordpress.com/2022/04/01/long-term-side-  
effects-of-adderall-on-brain-personality-body/#respond)

## [Neurocognitive, Autonomic, and Mood Effects of Adderall: A Pilot Study of

Healthy College  
Students](https://begininfiniteloop.wordpress.com/2022/04/01/neurocognitive-  
autonomic-and-mood-effects-of-adderall-a-pilot-study-of-healthy-college-  
students/)

Lisa L. Weyandt, Tara L. White, […], and Stephanie A. Bjorn

## Abstract

Prescription stimulant medications are considered a safe and long-term  
effective treatment for Attention Deficit Hyperactivity Disorder (ADHD).  
Studies support that stimulants enhance attention, memory, self-regulation and  
executive function in individuals with ADHD. Recent research, however, has  
found that many college students without ADHD report misusing prescription  
stimulants, primarily to enhance their cognitive abilities. This practice  
raises the question whether stimulants actually enhance cognitive functioning  
in college students without ADHD. We investigated the effects of mixed-salts  
amphetamine (i.e., Adderall, 30 mg) on cognitive, autonomic and emotional  
functioning in a pilot sample of healthy college students without ADHD ( *n* =  
13), using a double-blind, placebo-controlled, within-subjects design. The  
present study was the first to explore cognitive effects in conjunction with  
mood, autonomic effects, and self-perceptions of cognitive enhancement.  
Results revealed that Adderall had minimal, but mixed, effects on cognitive  
processes relevant to neurocognitive enhancement (small effects), and  
substantial effects on autonomic responses, subjective drug experiences, and  
positive states of activated emotion (large effects). Overall, the present  
findings indicate dissociation between the effects of Adderall on activation  
and neurocognition, and more importantly, contrary to common belief, Adderall  
had little impact on neurocognitive performance in healthy college students.  
Given the pilot design of the study and small sample size these findings  
should be interpreted cautiously. The results have implications for future  
studies and the education of healthy college students and adults who commonly  
use Adderall to enhance neurocognition.

**Keywords:** prescription stimulants, Adderall, neurocognitive enhancement,  
college students, prescription stimulant misuse

## 1\. Introduction

Attention-deficit/hyperactivity disorder (ADHD) is a chronic disorder  
characterized by developmentally inappropriate levels of inattention and/or  
hyperactivity-impulsivity that affects approximately 3–10% of school age  
children and adolescents [1]. Research indicates that increasing numbers of  
high school students with ADHD are pursuing college and in a recent national  
survey, 6.4% of male and 3.9% of female freshman reported having ADHD [2].  
College students with ADHD are entitled by the American Disabilities Act to  
receive educational support services, and approximately 25% of college  
students receiving disability support services receive services for ADHD. This  
percentage has increased substantially since 1975 [3]. The prognosis for  
college students with ADHD varies across studies, but most suggest that  
college students with ADHD are at increased risk for academic problems,  
executive function deficits, lower grade point average, compromised academic  
coping skills, and higher than average risk for psychological and  
interpersonal difficulties [4,5,6,7,8,9]. A number of non-pharmacological  
treatments are available for ADHD (e.g., behavioral support therapies,  
cognitive-behavior therapy, biofeedback) and studies attest to their varying  
effectiveness. To date, however, the majority of ADHD treatment outcome  
studies have shown that, in general, the most effective treatment for reducing  
ADHD symptoms is stimulant medication (e.g., amphetamine, methylphenidate)  
although questions remain regarding the magnitude of these effects given  
various methodological problems in the literature [10]. Questions also remain  
regarding the extent to which placebo effects and responding contributes to  
observed improvements in cognitive and behavioral functioning in children and  
adults. For example, Fageera and colleagues [11] recently found a significant  
placebo response in both parents and teachers of children with ADHD during a  
randomized, placebo controlled clinical trial of methylphenidate with more  
robust effects observed in parents than teachers. Mateeton et al. [12]  
reported that lisdexamfetamine (LDX) is efficacious and well tolerated in the  
treatment of ADHD in adults, however its acceptability is no higher than  
placebo. With respect to college students, Weyandt and colleagues [13] were  
the first to demonstrate the effectiveness and safety of lisdexamfetmaine  
dimesylate (LDX; Vyvanse) in college students with ADHD in the context of a  
double-blind, placebo-controlled crossover study. Specifically, DuPaul and  
colleagues [14] and Weyandt et al. [13] found that lisdexamfetmaine dimesylate  
was effective at reducing ADHD symptomatology and at improving cognitive  
skills, including executive functions, in college students with documented  
ADHD.

Although prescription stimulants are often highly effective in reducing ADHD  
symptoms, non-medical use of prescription stimulants among college students  
without the disorder has become increasingly problematic in recent years. Non-  
medical use, or misuse, of stimulants has been defined as taking stimulants  
without a valid prescription and/or use of stimulants other than as prescribed  
[13,15]. Over a decade ago, Babcock and Byrne [16] surveyed 283 students  
regarding misuse of prescription stimulants and found that 16% of the sample  
reported taking Ritalin for "fun"; yet, less than 2% of the sample had a  
current prescription for Ritalin. McCabe, Knight, Teter, and Wechsler [17]  
found that 6.9% of college students surveyed reported lifetime misuse of  
prescription stimulants. Further, DuPont et al. [18] found the most frequently  
reported motive for misuse of stimulant medication was to "work/study" and to  
"party." Similarly, Weyandt et al. [19] Judson and Langdon [20], and Bossaer  
et al. [21] found that college students who misused prescription stimulants  
did so to enhance cognitive functioning, such as concentration, and to  
increase alertness or to stay awake. In a systematic review of 22 studies,  
Weyandt et al. [13] found that 5–35% of college students surveyed had misused  
prescription stimulants primarily for neurocognitive enhancement. Other  
reasons commonly reported by students include recreational use (e.g.,  
partying, pharming, weight loss) and some students (40%) appear to misuse  
prescription stimulants for both cognitive enhancement and recreational  
purposes [15]. Munro, Weyandt, Marraccini, and Oster [22] recently studied  
college students from six public universities located in various regions of  
the United States and reported that students with clinically significant  
executive function deficits reported significantly higher rates of  
prescription stimulant misuse. Prescription stimulant misuse has also been  
reported among college students in other countries including Germany [23],  
Iceland [24], Switzerland [25], and the United Kingdom [26] with rates similar  
to those found in the USA. Interestingly, and similar to results from studies  
conducted in the USA, Gudmundsdottir and colleagues [24] found that ADHD  
symptomatology and anxiety was significantly associated with prescription  
stimulant misuse behavior. Other international studies have reported similar  
findings [27] underscoring that this behavior is present across cultures.

Contrary to student expectations and beliefs, prescription stimulants may not  
lead to neurocognitive enhancement and improved academic performance [15], as  
stimulant misuse has been found to be negatively correlated with academic  
functioning [13,28]. Weyandt and colleagues [13] emphasized that empirical  
studies are needed to determine whether stimulants are truly neurocognitive  
enhancers for college students without ADHD. Ilieva, Boland, and Farah [29]  
explored both the objective and subjective effects of amphetamines on  
cognition among healthy adults and did not find support for significant  
effects of amphetamine on episodic memory, working memory, inhibitory control,  
creativity, intelligence and scholastic achievement. Participants, however,  
did report perceived neurocognitive enhancement suggesting a placebo effect  
likely accounted for the perceived cognitive enhancement. In contrast, Smith  
and Farah [30] conducted a review of studies investigating neurocognitive  
effects of prescription stimulants in healthy adults and reported that both  
amphetamine and methylphenidate were associated with overall improvements  
(accuracy and/or speeded responses) in response inhibition tasks as well as  
perceptual motor and delay rewards tasks. Interestingly, however, stimulants  
were found to impair performance on tasks of response inhibition requiring  
cancellation (i.e., stop signal tasks), cognitive flexibility (i.e., Intra-  
Extra Dimensional Set-shift Task, Wisconsin Card Sorting Task), trail-making  
tasks and reversal learning tasks. Amphetamine can induce reductions and  
increases in incentive-related risk behavior, depending on the individual  
being tested [31]. As Marraccini, Weyandt, Rossi, and Gudmundsdottir [32]  
(noted, these findings suggest that baseline performance is a crucial  
moderator and depending on baseline levels, stimulants may result in  
improvement or worsening of cognitive functioning and those with lower  
baseline functioning may derive the greatest benefits. Other studies, however,  
have reported mixed findings with healthy adults, with some supporting  
positive and large effects of methylphenidate on both immediate and delayed  
working memory and episodic memory [33] as well as processing speed [32]. In  
summary, some preliminary evidence suggests that healthy adults without ADHD  
may receive small to moderate cognitive benefits from prescription stimulant  
medication (e.g., Adderall) in the areas of working memory, response  
inhibition, processing speed, and delayed memory; however, questions remain  
regarding the effects of prescription stimulants on measures of attention,  
executive function (e.g., decision making, verbal fluency, and planning) and  
other aspects of cognition. A dearth of information exists regarding the  
potential effects of Adderall on mood and self-perceived cognitive enhancement  
effects of Adderall.

The acute neurocognitive effects of Adderall will be best understood in the  
larger context of the drug's concurrent effects on emotion, subjective state,  
and self-perceived cognitive ability. These domains are readily evaluated by  
self-report measures such as the Drug Effects Questionnaire, which evaluates  
subjective ratings of drug liking and drug high [34]; the Positive Activation  
scale, which evaluates the presence and intensity of activated emotion such as  
elation and euphoria [35]; and the Perceived Drug Effect Self-Report scale, a  
measure of that evaluates personal perceptions of whether one's cognitive  
ability has improved after drug consumption [29]. Psychostimulant-induced  
changes in activated positive emotion, subjective drug responses, and  
autonomic activation are typically large in size [36,37,38], with a smaller  
evidentiary base regarding psychostimulant drug effects on self-perceptions of  
cognitive functioning [29]. Very few studies evaluate Adderall effects on  
neurocognitive function in the context of drug-induced changes in activated  
emotion, subjective drug experience, autonomic activation, and changes in  
meta-cognition. Joint assessment of Adderall effects on neurocognition, mood,  
activation, and perceived cognitive enhancement would thus provide important  
and highly novel information through which to better understand the potential  
effects of Adderall on neurocognition as opposed to other outcomes that may  
affect drug choice behavior.

Given that misuse of prescription stimulants is widely reported on college  
campuses for the purpose of neurocognitive enhancement, and that students  
typically view these drugs as safe, research is sorely needed to empirically  
address the joint neurocognitive and meta-cognitive activational effects of  
prescription stimulants in college students without ADHD. Therefore, the  
purpose of the present pilot study was to explore: (a) the potential effects  
of the prescription stimulant Adderall on the cognitive performance of healthy  
college students without ADHD in the areas of memory, reading comprehension,  
sustained attention, impulsivity, and executive function relative to placebo;  
and (b) concomitant effects of Adderall on autonomic activation, subjective  
drug responses and activated emotion in healthy college students without ADHD.  
This approach provides an empirical test of Adderall effects on cognitive  
function, emotion and autonomic activity, and concurrent estimates of drug  
impact on each outcome. We hypothesized that participant performance on  
measures of cognition would be significantly enhanced after ingestion of  
Adderall compared to placebo. Specifically, we expected enhanced performance  
after Adderall (30 mg) compared to placebo for (1) reading comprehension; (2)  
working memory; (3) executive function; and (4) greater self-perceptions of  
performance on cognitive tasks. Understanding potential effects of stimulants  
on these outcomes is important for prevention efforts and mitigating  
prescription drug misuse among healthy college students.

## 2\. Methods

### Study Design

This pilot study employed a double-blind, placebo-controlled, within-subjects  
crossover design. Cognitive tasks were administered during the peak period of  
the drug effect, between 90 and 210 min after the capsule was administered.  
The study design is illustrated in [Figure  
1](/pmc/articles/PMC6165228/figure/pharmacy-06-00058-f001/?report=objectonly).

![Figure 1](/pmc/articles/PMC6165228/bin/pharmacy-06-00058-g001.gif)Figure 1

[Figure  
1](/pmc/articles/PMC6165228/figure/pharmacy-06-00058-f001/?report=objectonly)

Experimental Design. Legend: Timing of test sessions. Sessions were 5.5 h in  
duration (330 min. total). X-axis denotes time relative to administration of  
the blinded study capsule at time 0 (black arrow). Neurocognitive testing  
began approximately 90 …

## 3\. Procedure

The study was approved by the Institution Review Board for research with human  
subjects at the University of Rhode Island, Brown University, and the Memorial  
Hospital of Rhode Island in accordance with the Code of Federal Regulations  
(Title 45, Part 46) "Protection of Human Subjects" adopted by the National  
Institutes of Health and the Office for Protection from Research Risks. The  
study was conducted ethically in accordance with the Helsinki Declaration of  
1964 (revised 2013) and the National Advisory Council on Drug Abuse  
Recommended Guidelines for the Administration of Drugs to Human Subjects.

Healthy college student participants (i.e., college students without ADHD or  
other psychiatric conditions) were recruited via campus flyers, announcements  
in courses, and advertisements. Interested students contacted the researchers  
via email or telephone and completed a telephone screening to determine  
initial eligibility, followed by an in-person session in which written  
informed consent was obtained. The Mini-International Neuropsychiatric  
Interview (M.I.N.I. (Version 5.0.0); [39]) was administered to exclude  
participants meeting criteria for other psychiatric disorders from the sample.  
Participants were then scheduled for a medical exam and electrocardiogram  
(EKG) at a local hospital. To be included in the study, participants had to be  
between the ages of 18 and 24, physically healthy, have a normal EKG, and not  
be taking any prescription medication for a chronic medical condition in the  
past 6 months with the exclusion of antibiotics, or birth control pills in  
female participants. Once cleared for the study, participants took part in two  
test sessions in which a capsule was administered and neurocognitive,  
physiological and mood assessments were conducted. Test sessions used a time-  
locked protocol that lasted 5.5 h apiece, with test sessions scheduled at the  
same time of day to eliminate circadian effects. The order of placebo and  
active drug was counterbalanced for order across participants. On each test  
day, participants arrived at the lab and completed a brief pre-protocol  
readiness assessment, and baseline self-report and physiological measures  
(heart rate, diastolic and systolic blood pressure measures). Thirty minutes  
after arrival, participants received an opaque capsule that contained the  
active drug or placebo, which was consumed with a glass of water and verified  
by visual inspection of the oral cavity. Amphetamine mixed salts (i.e.,  
generic Adderall) and placebo (dextrose) were selected as the study drugs  
because Adderall and its generic equivalent is an FDA-approved treatment for  
ADHD that is prone to misuse in college populations, has a known safety  
profile and is one of the most commonly prescribed psychostimulants for adults  
with ADHD (MTA Group, 1999). The 30 mg oral dose was selected because it  
produces significant effects on attention in the context of ADHD, and has a  
well-documented safety profile in young adults [40]. Mixed amphetamine salts  
(30 mg oral) were compounded with dextrose filler and dispensed as individual  
prescriptions in opaque, colored gelatin capsules. The placebo consisted of  
identical gelatin capsules and contained only dextrose. The dosing schedule  
followed a standardized period of fasting (2 h), with neurocognitive  
assessment over a two-hour period 90–210 min post-consumption to ensure that  
cognitive assessments occurred during the peak period of pharmacological  
effects. Autonomic and mood assessment was conducted every 30 min ([Figure  
1](/pmc/articles/PMC6165228/figure/pharmacy-06-00058-f001/?report=objectonly)).

Across the study, 53 college students were contacted who expressed interest in  
the study, 21 of who were ineligible, typically due to recreational drug use  
and medical conditions/medication. Seven individuals opted not to continue  
with the study, and one individual declined the study screening. This resulted  
in 24 in-person interview sessions where participants were informed of the  
nature of the study, provided written consent, and enrolled in the study. Four  
participants were excluded after enrollment, and seven dropped out post-  
consent due to scheduling constraints, lack of continued interest, or new  
medical issues not present at initial screening. The remaining 13 participants  
completed the study in full, yielding 26 sessions of data collection for  
analysis.

## 4\. Instruments

### Neurocognitive Measures

For each participant, the six tasks described below were administered  
randomly, to reduce potential order effects. For each participant, the order  
of tasks was recorded on the first session, and the same sequence was  
administered on their second test session. For all participants, Task 2 and  
Task 5 were never administered sequentially as they each measure aspects of  
oral language, and Task 6 was always presented last. An example order of task  
administration is presented in [Figure  
1](/pmc/articles/PMC6165228/figure/pharmacy-06-00058-f001/?report=objectonly).  
Tasks are described below.

Task 1. Digit Span Forward and Backward [41]. This task evaluates working  
memory and is derived from a subtest of the Wechsler Adult Intelligence Scale,  
fourth edition [41] For Digit Span Forward, the participant was read a  
sequence of numbers and was asked to verbally recall the numbers in the same  
order. For Digit Span Backward, the examinee was read a sequence of numbers  
and was asked to verbally recall the numbers in reverse order. Digit Span  
measures working memory, mental manipulation, cognitive flexibility, rote  
memory and learning, attention, and encoding. The primary dependent variable  
was the total age normed scaled score for digit span forward and backward.  
Total time to complete the Digit Span tasks was approximately 8 min.

Task 2. Story Recall subtest from the Woodcock Johnson–III [42]. This task  
measures aspects of oral language including language development and  
meaningful memory. The task required the participants to recall increasingly  
complex stories. After listening to a passage, the participant was asked to  
recall as many details of the story as they could remember. All participants  
began the task according to their age range as predetermined by the test's  
standardized procedures. The dependent measure on the task was the WJ total  
age normed scale score. Total time to complete the task was 10 min.

Task 3. Conners Continuous Performance Test Third Edition [43]. The CPT 3 was  
administered to measure Inattentiveness, Impulsivity, Sustained Attention, and  
Vigilance. The administration of the CPT 3 involves 360 trials and requires  
respondents to press the spacebar whenever any letter, except the letter "X",  
appears on the computer screen. Measures of Inattentiveness include lower  
Detectability (d'), a larger number of Omissions and Commissions, a slower Hit  
Reaction Time (HRT), as well as greater inconsistencies in response speed (HRT  
Standard Deviation and Variability). On the other hand, a faster HRT and a  
larger number of Commissions and/or Perseverations serve as a measure of  
Impulsivity. T-scores for HRT, errors of Omission and Commission and  
Variability were the dependent variables. Time to complete the CPT 3 was 14  
min.

Task 4. The Behavior Rating Inventory of Executive Function, Adult version  
(BRIEF-A; [44]). This standardized, norm referenced, self-report instrument  
measures executive functions and self-regulation abilities in daily living.  
The three dependent variables from the BRIEF-A were total scores from the  
Behavioral Regulation Index (BRI), Metacognition Index (MI), and Global  
Executive Composite (GEC). The BRIEF-A was included to gather information  
regarding the potential drug effect of Adderall on participants memory of past  
cognition and self-regulation ability. Time to complete task was approximately  
10 min.

Task 5. Gray Oral Reading Tests−Fifth Edition (GORT-5; [45]). This task  
measures oral reading rate, accuracy, fluency, and comprehension. There are  
two test forms, each containing 14 reading sequences and relevant questions.  
The dependent variable was the Oral Reading Index scaled score, which provides  
a combined measure of reading fluency and comprehension. Time to complete the  
task was approximately 20–30 min.

Task 6. Perceived Drug Effect Self-Report (PDE-SR) [29] This is a one-item  
measure of whether participants perceived the drug as influencing their  
performance on neurocognitive tasks and was administered at the end of  
neurocognitive testing. The measure reads: 'The following question refers to  
all tests completed TODAY. How and how much did the drug influence (either  
positively or negatively) your performance on the tests? Please use the scale  
below. Your answer can be any number between 1 and 100." The scale was a line,  
ranging from 1 to 100, labeled as follows: 1 = "drug impaired my performance  
extremely"; 25 = "the drug somewhat impaired my performance"; 50 = "the drug  
had no effect"; 75 = "the drug somewhat improved my performance"; 100 = "the  
drug improved my performance extremely." The dependent variable was the self-  
reported score of the perceived drug effect on neurocognitive performance.

## 5\. Activational Measures

Subjective Drug Effects. Drug Effects Questionnaire (DEQ; [34]). The DEQ  
consists of four questions concerning subjective drug effects. Participants  
indicate on 100-mm lines their response to four items: (1) 'I FEEL some drug  
effects right now', rated from "not at all" to "a lot"; (DEQ-Feel Drug); (2)  
'I LIKE the effects I am feeling right now', rated from "dislike" to "like  
very much" (DEQ-Like); (3) 'I am HIGH', rated from "not at all" to "very much"  
(DEQ-High); and (4) 'I would like MORE of what I consumed right now', rated  
from "not at all" to "very much" (DEQ-Want More). Prescription  
psychostimulants such as d-amphetamine produce robust increases on these  
measures in healthy young adults [36,46,47]. DEQ measures were administered at  
half hour intervals, for a total of 11 timepoints of assessment on each  
session (details in [Figure  
1](/pmc/articles/PMC6165228/figure/pharmacy-06-00058-f001/?report=objectonly)).

Activated Emotion. Positive Activation [35]. Positive Activation (PA) consists  
of 10 ratings of activated positive emotion. Participants circle a response on  
the PA scale from 0 to 9, ranging from the relative absence (0) to the strong  
presence (9) of positively valenced activated emotion (0 = depressed/sluggish;  
1 = dull/tired; 2 = pleasant/fresh; 3 = cheerful/lively; 4 =  
delighted/energetic'; 5 = enthused/peppy; 6 = thrilled/strong; 7 =  
exuberant/vigorous; 8 = elated/exhilarated; 9 = ecstatic/invincible). A  
parallel scale of Negative Activation (NA), developed at the same time by our  
group [35], which consists of 10 ratings of activated negative emotion, was  
evaluated to provide information on specificity and discriminant validity.  
Participants circle a response on the NA scale from 0 to 9, ranging from the  
relative absence (0) to the strong presence (9) of negatively valenced  
activated emotion (0 = placid; 1 = calm; 2 = relaxed; 3 = annoyed; 4 = tense;  
5 = nervous; 6 = distressed; 7 = jittery; 8 = hostile; 9 = contemptful).  
Dopamine agonists and incentive stimuli produce increases in PA in healthy  
volunteers [35,37,47,48]. PA and NA were evaluated by each participant at half  
hour intervals throughout the protocol (11 timepoints per session; [Figure  
1](/pmc/articles/PMC6165228/figure/pharmacy-06-00058-f001/?report=objectonly)).

Autonomic Activation. Heart rate, diastolic blood pressure and systolic blood  
pressure were assessed at half hour intervals (11 time points per session;  
[Figure  
1](/pmc/articles/PMC6165228/figure/pharmacy-06-00058-f001/?report=objectonly)).  
Prescription psychostimulants produce robust increases in autonomic activity  
in young adults [36,49]. The autonomic measures provide substantiating  
evidence of drug exposure and drug efficacy during the protocol.

## 6\. Data Analyses

The neurocognitive hypotheses—that participant performance on measures of  
neurocognition would be significantly better after ingestion of Adderall  
compared to placebo—were tested by paired-samples *t* -tests (1-tailed).  
Cohen's *d* effect sizes were computed to ascertain effect size estimates for  
Adderall effects on neurocognitive performance, with Cohen's *d* values  
between 0.2 and 0.5 considered small effects, 0.5 and 0.8 considered medium  
effects, and above 0.8 considered large effects [50].

Activational hypotheses—that subjective effects, activated emotion and  
autonomic activity would be significantly higher after Adderall than  
placebo—were tested by within-subjects, repeated-measures drug (PBO, Adderall)  
by time (11 time points) 2-way ANOVA. For drug main effects, partial eta-  
squared values were calculated to ascertain effect size estimates of Adderall  
effects on activation across the 5.5 h testing period, with partial eta-  
squared values of 0.01 considered small effects, 0.06 considered medium  
effects, and 0.14 considered large effects [50,51,52] Cohen's *d* effect sizes  
were computed to ascertain effect size estimates for Adderall effects on  
activation at the time point of maximal drug response, with Cohen's *d* values  
between 0.2 and 0.5 considered small effects, 0.5 and 0.8 considered medium  
effects, and above 0.8 considered large effects [50].

## 7\. Statistical Power

Power analyses for within-subjects effects were conducted in G*Power 3.1 using  
an alpha of 0.05 [51,53]. The final sample of 13 had high power (1 − β = 0.86)  
to detect large drug effects ( *d* = 0.80), moderate power (1 − β = 0.52) to  
detect medium drug effects ( *d* ≥ 0.50), and low power (1 − β = 0.17) to  
detect small drug effects ( *d* = 0.20).

## 8\. Results

### 8.1. Descriptive Statistics

[Table  
1](/pmc/articles/PMC6165228/table/pharmacy-06-00058-t001/?report=objectonly)  
depicts the means and standard deviations for neurocognitive performance  
measures during the Adderall and placebo sessions. Adderall had minimal, but  
mixed, effects on cognitive processes relevant to neurocognitive enhancement.  
Drug effects were medium in size on CPT 3—Variability and Digit Span Forward,  
and small in size on BRIEF-A—BRI, CPT 3 Commission Errors, CPT 3 Hit Reaction  
Time, GORT—ORI, and Perceived Drug Effect Self-Report.

![Table  
1](/pmc/articles/PMC6165228/table/pharmacy-06-00058-t001/?report=thumb)Table 1

[Table  
1](/pmc/articles/PMC6165228/table/pharmacy-06-00058-t001/?report=objectonly)

Neurocognitive Task Performance by Drug Condition.

### 8.2. Drug Effects on Activation

Adderall had substantial effects on subjective drug experience, activated  
emotion and autonomic activity (average partial eta-squared = 0.40, range  
0.31–0.52, indicating large effects across the session; and average Cohen's  
*d* = 1.03, range 0.71–1.26, indicating medium to very large effects at the  
peak time point; see [Table  
2](/pmc/articles/PMC6165228/table/pharmacy-06-00058-t002/?report=objectonly)).  
These effects are described in turn.

![Table  
2](/pmc/articles/PMC6165228/table/pharmacy-06-00058-t002/?report=thumb)Table 2

[Table  
2](/pmc/articles/PMC6165228/table/pharmacy-06-00058-t002/?report=objectonly)

Adderall Effects on Autonomic Activity, Subjective State and Activated  
Emotion.

Subjective Drug Effects. Adderall significantly increased ratings of DEQ Feel  
Drug and DEQ Feel High compared to placebo ([Table  
2](/pmc/articles/PMC6165228/table/pharmacy-06-00058-t002/?report=objectonly)).  
For DEQ Feel Drug, there was a significant main effect of drug: *F* (1,12) =  
9.64, *p* = 0.009 and a significant drug by time interaction: *F* (10,120) =  
2.82, *p* = 0.004. These effect are illustrated in [Figure  
2](/pmc/articles/PMC6165228/figure/pharmacy-06-00058-f002/?report=objectonly)A  
and were large in size, partial eta-squared = 0.45; Cohen's *d* = 1.26. For  
DEQ Feel High, there was a significant main effect of drug: *F* (1,12) = 7.06,  
*p* = 0.02, and a significant drug by time interaction: *F* (10,120) = 2.46,  
*p* = 0.01. These effects are illustrated in [Figure  
2](/pmc/articles/PMC6165228/figure/pharmacy-06-00058-f002/?report=objectonly)B  
were large in size, partial eta-squared = 0.37, Cohen's *d* = 1.04.

Activated Emotion. Adderall significantly increased ratings of activated  
positive emotion (PA) compared to placebo (see [Table  
2](/pmc/articles/PMC6165228/table/pharmacy-06-00058-t002/?report=objectonly)).  
For PA, there was a significant main effect of drug: *F* (1,12) = 5.27, *p* =  
0.04, and a significant drug by time interaction: *F* (10,120) = 2.20, *p* =  
0.02. Drug effects on PA are illustrated in [Figure  
2](/pmc/articles/PMC6165228/figure/pharmacy-06-00058-f002/?report=objectonly)C  
and were large in size across the session, partial eta-squared = 0.31, with  
medium effects at the peak time point, Cohen's *d* = 0.71. There was no drug  
effect on negative emotion (NA), *p* > 0.44, n.s. These findings provide  
evidence of specificity and discriminant validity, and indicate a selective  
effect of Adderall on positively valenced states of activated emotion  
following drug consumption.

Autonomic Activity. Adderall significantly increased autonomic activity  
compared to placebo ([Table  
2](/pmc/articles/PMC6165228/table/pharmacy-06-00058-t002/?report=objectonly)).  
For heart rate there was a significant main effect of drug: *F* (1,12) =  
12.84, *p* = 0.004 and a significant drug by time interaction: *F* (10,120) =  
4.30, *p* = 0.00003. Drug effects on heart rate are illustrated in [Figure  
3](/pmc/articles/PMC6165228/figure/pharmacy-06-00058-f003/?report=objectonly)A  
and were large in size, partial eta-squared = 0.52, Cohen's *d* = 1.25. For  
systolic blood pressure there was a significant main effect of drug: *F*  
(1,12) = 10.1, *p* = 0.008, and a significant drug by time interaction: *F*  
(10,120) = 3.36, *p* = 0.001. These effects are illustrated in [Figure  
3](/pmc/articles/PMC6165228/figure/pharmacy-06-00058-f003/?report=objectonly)B  
and were large in size, partial eta-squared = 0.46, Cohen's *d* = 1.05. For  
diastolic blood pressure there was a significant main effect of drug: *F*  
(1,12) = 5.38, *p* = 0.04, and a significant drug by time interaction: *F*  
(10,120) = 3.28, *p* = 0.001. Effects on diastolic blood pressure are  
illustrated in [Figure  
3](/pmc/articles/PMC6165228/figure/pharmacy-06-00058-f003/?report=objectonly)C  
and were large in size, partial eta-squared = 0.31, Cohen's *d* = 0.86. These  
findings substantiate sympathomimetic drug activity during the protocol,  
providing evidence of internal validity of drug exposure ([Table  
2](/pmc/articles/PMC6165228/table/pharmacy-06-00058-t002/?report=objectonly);  
[Figure  
3](/pmc/articles/PMC6165228/figure/pharmacy-06-00058-f003/?report=objectonly)A–C).

### 8.3. Drug Effects on Neurocognitive Functioning

On measures of executive functioning (i.e., CPT 3) Adderall significantly  
reduced Variability *t* (10) = −2.25, *p* = 0.02, and marginally reduced  
Commission Errors, *t* (10) = −1.74, *p* = 0.056, and Hit Reaction Time *t*  
(10) = −1.47, *p* = 0.086 (see [Table  
1](/pmc/articles/PMC6165228/table/pharmacy-06-00058-t001/?report=objectonly)  
and [Table  
3](/pmc/articles/PMC6165228/table/pharmacy-06-00058-t003/?report=objectonly)),  
collectively supporting that Adderall improved attention skills. CPT 3 effects  
are illustrated in [Figure  
4](/pmc/articles/PMC6165228/figure/pharmacy-06-00058-f004/?report=objectonly)  
and [Figure  
5](/pmc/articles/PMC6165228/figure/pharmacy-06-00058-f005/?report=objectonly).  
In contrast, Adderall *worsened* working memory on Digit Span Forward, *t*  
(12) = −1.80, *p* = 0.048 ([Table  
1](/pmc/articles/PMC6165228/table/pharmacy-06-00058-t001/?report=objectonly)  
and [Table  
3](/pmc/articles/PMC6165228/table/pharmacy-06-00058-t003/?report=objectonly)).  
Working memory effects are in [Figure  
6](/pmc/articles/PMC6165228/figure/pharmacy-06-00058-f006/?report=objectonly).  
There were trend-level drug effects on BRIEF-BRI, *t* (12) = 1.54, *p* =  
0.075; and BRIEF-GEC, *t* (12) = 1.35, *p* = 0.10, with a marginal worsening  
of participants perceptions of their past cognitive and self-regulation  
executive functioning in daily activities under Adderall compared to placebo.  
Adderall effects on the GORT and WJ were not statistically significant ( *p* >  
0.13 and 0.23, respectively; n.s.) suggesting that Adderall neither improved  
nor impaired reading performance. There were no statistically significant  
effects of Adderall on participants' perceptions of whether the drug affected  
their own task performance, *p* = 0.30.

![Figure 4](/pmc/articles/PMC6165228/bin/pharmacy-06-00058-g004.gif)Figure 4

[Figure  
4](/pmc/articles/PMC6165228/figure/pharmacy-06-00058-f004/?report=objectonly)

Effects of Adderall on CPT-3 Variability. Legend: Adderall significantly  
improved performance (i.e., reduced Variability): *t* (10) = −2.25, * *p* <  
0.05, Cohen's *d* = −0.73, a medium effect. *N* = 13 participants in each drug  
…

![Figure 5](/pmc/articles/PMC6165228/bin/pharmacy-06-00058-g005.gif)Figure 5

[Figure  
5](/pmc/articles/PMC6165228/figure/pharmacy-06-00058-f005/?report=objectonly)

Effects of Adderall on CPT-3 Commission Errors. Legend: Adderall marginally  
improved performance (i.e., fewer Commission Errors): *t* (10) = −1.74, † *p*  
= 0.056, Cohen's *d* = −0.30, a small effect. *N* = 13 participants in each …

![Figure 6](/pmc/articles/PMC6165228/bin/pharmacy-06-00058-g006.gif)Figure 6

[Figure  
6](/pmc/articles/PMC6165228/figure/pharmacy-06-00058-f006/?report=objectonly)

Effects of Adderall on Working Memory. Legend: Adderall worsened performance  
(i.e., fewer digits remembered): *t* (12) = −1.80, * *p* < 0.05, Cohen's *d* =  
0.47, a medium effect. *N* = 13 participants in each drug condition, 26  
sessions. …

![Table  
3](/pmc/articles/PMC6165228/table/pharmacy-06-00058-t003/?report=thumb)Table 3

[Table  
3](/pmc/articles/PMC6165228/table/pharmacy-06-00058-t003/?report=objectonly)

Specific Adderall Effects on Neurocognition.

## 9\. Discussion

A robust body of literature exists documenting widespread misuse of  
prescription stimulant medication on college campuses primarily for the  
purpose of neurocognitive and academic enhancement [9]. Much less is known,  
however, regarding the direct cognitive effects of prescription stimulants  
when taken non-medically, especially in college students without ADHD. The  
present, pilot study is the first to explore potential cognitive effects in  
conjunction with activational mood, autonomic effects and self-perceptions of  
drug effects on task performance in the same individuals, and provides proof-  
of-concept data and effect size estimates for future work. We hypothesized  
student performance on measures of cognition, activated emotion, subjective  
states and autonomic activity would be enhanced after Adderall relative to  
placebo, however findings indicated that Adderall lead to mixed effects  
including both impairment in cognitive functioning (working memory) and  
improvement in attention performance. These findings are generally consistent  
with meta-analytic findings by [29] who found small effects of amphetamine and  
methylphenidate on working memory and inhibitory control in healthy adults but  
concluded that the effects are "probably modest". It is important to note that  
a robust body of literature exists that supports the positive effects of  
prescription stimulants on neurocognitive functioning in children and adults  
with ADHD (e.g., [14,54,55]), underscoring the importance of baseline  
impairments in performance relative to improved effects.

With respect to autonomic activation and mood effects, our findings revealed  
significant drug-induced changes in activated emotion, subjective drug effects  
and autonomic activation (i.e., heart rate and diastolic and systolic blood  
pressure) that were *large* in effect size. These findings indicate that  
healthy college students experience substantive increases in emotional and  
autonomic activation in the period following Adderall consumption. These  
effects are consistent with the large increases in activated positive emotion,  
subjective drug effects, physiological activity and frontal brain glutamate in  
healthy young adults after consumption of other psychostimulant drugs, such as  
20 mg oral d-amphetamine sulfate [36,38], 20 mg oral Desoyxn® [38], and 0.6  
mg/kg oral methylphenidate [37].

With regard to specific effects of Adderall on neurocognition, the results  
were mixed and much smaller in size. Specifically, the primary finding was  
that Adderall lead to reduced response variability on an executive function  
measure (CPT-3) relative to placebo, supporting enhanced attention skills  
[43]. However, it is important to note that Adderall *impaired* working memory  
performance relative to placebo, and was associated with a trend-level  
*worsening* of participants' ratings of their own past cognitive ability and  
overall ability to self-regulate (BRIEF-A). These findings support that  
Adderall can have neurocognitive effects that are discordant with drug  
expectancies, and while improving attention skills, may simultaneously degrade  
students' confidence in their abilities to problem solve, complete tasks, and  
interact with others [56]. As task-related stress is increased after stimulant  
drug use [57], such effects could increase student motivation to use stimulant  
drugs in response to academic stressors. In contrast to [29], the present  
study did not find evidence that participants perceived the drug had enhanced  
their neurocognitive performance.

Lastly, our findings indicated that Adderall neither improved nor  
deleteriously affected oral reading performance or story recall suggesting  
that Adderall may not enhance academic performance in healthy college students  
although additional empirical studies are needed to explore this finding. In  
addition, no significant effects of Adderall on participants' perception of a  
possible drug effect on cognitive performance (PDE-SR) were found, indicating  
that participants were largely unaware of the effects of Adderall on their own  
neurocognitive performance. Collectively, findings of the present suggest that  
Adderall does not result in robust neurocognitive enhancement benefits in  
healthy college students.

The strengths of the present study include the placebo-controlled, within-  
subjects crossover design; evaluation of a prescription  
psychostimulant—Adderall—that is commonly misused for cognitive enhancement by  
college students; time-locked procedures for drug and placebo administration;  
and investigation of effects in a sample of healthy young adults carefully  
screened for medical and psychiatric disease. Autonomic data confirmed  
sympathomimetic drug activity, providing evidence of internal validity of drug  
exposure. The small to moderate effect sizes of 30 mg Adderall on  
neurocognition observed here support the negligible to small effects  
identified at lower doses (e.g., 10 mg; [58] and indicate that Adderall  
effects on neurocognition are likely small in size across a broad dosing  
range. In contrast, Adderall had large effects on activated positive emotion,  
subjective drug states, and autonomic activity, indicating dissociation  
between the effects of Adderall on activation and neurocognition. The within-  
subjects design provided two times the number of data points per subject  
compared to a between-subjects design and entirely controlled for individual  
differences between the drug and placebo conditions. This design reduces error  
variance and maximizes statistical power compared to alternate study designs  
[59]. The study provides empirically determined effect size estimates to guide  
future work on the effects of Adderall on specific neurocognitive outcomes in  
healthy college students.

Limitations of the study should also be noted. First, given the nature of the  
pilot study, the sample size is quite small and future studies with large  
samples are needed to further explore the neurocognitive effects of  
prescription stimulants. Studies are also needed to investigate potential  
placebo responding on task performance, and on perceived drug effects on task  
performance [11]. In addition, neurocognitive testing was conducted 90–210 min  
post-drug, which is the peak period of drug effects on emotion and autonomic  
activity. Potential drug effects on neurocognition beyond this time period  
were not evaluated. The study had high power to detect large effects, and  
lower power to detect moderate to small effects. As such the likelihood of  
Type II error is greater for small to medium effects. Findings with small to  
medium effect sizes (identified in [Table  
1](/pmc/articles/PMC6165228/table/pharmacy-06-00058-t001/?report=objectonly)  
and [Table  
3](/pmc/articles/PMC6165228/table/pharmacy-06-00058-t003/?report=objectonly))  
will require larger sample sizes in future work. Despite these limitations,  
the present study had adequate power for large effects and indicated  
dissociable effects of Adderall on neurocognition and activation, indicating  
differential acute impact on these outcomes.

In summary, the present pilot study indicates that a moderate dose of Adderall  
has small to minimal effects on cognitive processes relevant to academic  
enhancement (i.e., on reading comprehension, fluency, cognitive functioning),  
in contrast with its significant, large effects on activated positive emotion,  
autonomic activity, and subjective drug responses. This finding supports a  
dissociation between effects of Adderall on activation and neurocognition.  
Furthermore, in the present study, Adderall improved attention performance but  
impaired performance on working memory performance. Such effects appear  
somewhat discordant with drug expectancies in healthy college students who use  
these drugs primarily for purposes of neurocognitive and academic enhancement.  
Overall, the present findings indicate that non-medical use of moderate-dose  
Adderall in healthy college students may improve attention ability but has  
minimal or adverse impact on other cognitive processes and does not enhance  
academic performance, despite the common misuse of stimulant drugs for these  
purposes.

## Acknowledgments

We would like to thank Eva Stolz and Sinda Fekir for their efforts in data  
collection and for assistance with the figures.

## Author Contributions

L.L.W. and T.L.W. conceived the basic idea, initiated, designed and directed  
the study and wrote the manuscript. L.L.W., T.L.W., A.Z.N. and E.S.R. refined  
the procedures for neurocognitive testing. A.Z.N. and E.S.R. acquired the bulk  
of the data under the supervision of T.L.W. K.A.D.L., B.G.G. and T.L.W.  
performed the statistical analyses. L.L.W., T.L.W., B.G.G., K.A.D.L., E.S.R.  
and A.Z.N. provided input on data analysis and the interpretation of results.  
L.L.W., T.L.W., B.G.G., E.S.R., K.A.D.L. and A.Z.N. revised the manuscript.  
All authors read and approved the final manuscript.

## Funding

This research was supported by grants awarded to. L. Weyandt and T. L. White  
(co-PIs) from the Rhode Island Neuroscience Collaborative, the Brown  
University Institute for Brain Science, the George and Ann Ryan Institute for  
Neuroscience, and the Norman Prince Neurosciences Institute. Research reported  
in this publication was also supported by the National Center for Research  
Resources of the National Institutes of Health under Award Number G20  
RR030883, the program project grant P01 AA019072 from the National Institute  
on Alcohol Abuse and Alcoholism, BP-Endure grant R25 NS080686 from the  
National Institute of Neurological Disorders and Stroke (NINDS), NIH Training  
Grant T32 [MH020068](/nuccore/MH020068) from the National Institute of Mental  
Health, and GRFP Fellowship Grant # DGE 1058262 (Nitenson) from the National  
Science Foundation. The funding sources had no other role other than financial  
support. The content is solely the responsibility of the authors and does not  
necessarily represent the official views of the National Institutes of Health.

## Conflicts of Interest

The authors report no competing biomedical financial interests or potential  
conflicts of interest. The founding sponsors had no role in the design of the  
study; in the collection, analyses, or interpretation of data; in the writing  
of the manuscript, and in the decision to publish the results.

## Article Information

Pharmacy (Basel). 2018 Sep; 6(3): 58.

1Department of Psychology, George and Anne Ryan Institute for Neuroscience,  
University of Rhode Island, Kingston, RI 02881, USA

3Department of Behavioral and Social Sciences, School of Public Health, Brown  
University, Providence, RI 02912, USA

4Carney Institute for Brain Science, Brown University, Providence, RI 02912,  
USA

Received 2018 May 9; Accepted 2018 Jun 21.

Articles from Pharmacy: Journal of Pharmacy Education and Practice are  
provided here courtesy of **Multidisciplinary Digital Publishing Institute  
(MDPI)**

## References

1\. American Psychiatric Association . Diagnostic and Statistical Manual of  
Mental Disorders. 5th ed. American Psychiatric Publishing; Arlington, VA, USA:  
2013. [[Google  
Scholar](https://scholar.google.com/scholar_lookup?title=Diagnostic+and+Statistical+Manual+of+Mental+Disorders&publication_year=2013&)]

2\. Pryor J., Eagan K., Palucki Blake L., Hurtado S., Berdan J., Case M. The  
American Freshman: National Norms Fall 2012. Higher Education Research  
Institute; Los Angeles, CA, USA: 2012. [[Google  
Scholar](https://scholar.google.com/scholar_lookup?title=The+American+Freshman:+National+Norms+Fall+2012&author=J.+Pryor&author=K.+Eagan&author=L.+Palucki+Blake&author=S.+Hurtado&author=J.+Berdan&publication_year=2012&)]

3\. Wolf L.E. College students with ADHD and other hidden disabilities. Ann.  
N. Y. Acad. Sci. 2001;931:385. doi: 10.1111/j.1749-6632.2001.tb05792.x.  
[[PubMed](/pubmed/11462755)]  
[[CrossRef](//dx.doi.org/10.1111%2Fj.1749-6632.2001.tb05792.x)] [[Google  
Scholar](https://scholar.google.com/scholar_lookup?journal=Ann.+N.+Y.+Acad.+Sci.&title=College+students+with+ADHD+and+other+hidden+disabilities&author=L.E.+Wolf&volume=931&publication_year=2001&pages=385&pmid=11462755&doi=10.1111/j.1749-6632.2001.tb05792.x&)]

4\. Canu W.H., Carlson G.L. Differences in heterosocial behavior and outcomes  
of ADHD-symptomatic subtypes in a college sample. J. Atten. Disord.  
2003;6:123–133. doi: 10.1177/108705470300600304. [[PubMed](/pubmed/12821877)]  
[[CrossRef](//dx.doi.org/10.1177%2F108705470300600304)] [[Google  
Scholar](https://scholar.google.com/scholar_lookup?journal=J.+Atten.+Disord.&title=Differences+in+heterosocial+behavior+and+outcomes+of+ADHD-  
symptomatic+subtypes+in+a+college+sample&author=W.H.+Canu&author=G.L.+Carlson&volume=6&publication_year=2003&pages=123-133&pmid=12821877&doi=10.1177/108705470300600304&)]

5\. DuPaul G.J., Weyandt L.L., O'Dell S.M., Varejao M. College students with  
ADHD: Current status and future directions. J. Atten. Disord. 2009;13:234–250.  
doi: 10.1177/1087054709340650. [[PubMed](/pubmed/19620623)]  
[[CrossRef](//dx.doi.org/10.1177%2F1087054709340650)] [[Google  
Scholar](https://scholar.google.com/scholar_lookup?journal=J.+Atten.+Disord.&title=College+students+with+ADHD:+Current+status+and+future+directions&author=G.J.+DuPaul&author=L.L.+Weyandt&author=S.M.+O%E2%80%99Dell&author=M.+Varejao&volume=13&publication_year=2009&pages=234-250&pmid=19620623&doi=10.1177/1087054709340650&)]

6\. Gormley M.J., Pinho T., Pollack B., Puzino K., Franklin M.K., Busch C.,  
DuPaul G.J., Weyandt L.L., Anastopoulos A.D. Impact of study skills and parent  
education on first-year GPA among college students with and without ADHD: A  
moderated mediation model. J. Atten. Disord. 2018;22:334–348. doi:  
10.1177/1087054715594422. [[PMC free  
article](/pmc/articles/PMC4715995/?report=reader)]  
[[PubMed](/pubmed/26187415)]  
[[CrossRef](//dx.doi.org/10.1177%2F1087054715594422)] [[Google  
Scholar](https://scholar.google.com/scholar_lookup?journal=J.+Atten.+Disord.&title=Impact+of+study+skills+and+parent+education+on+first-  
year+GPA+among+college+students+with+and+without+ADHD:+A+moderated+mediation+model&author=M.J.+Gormley&author=T.+Pinho&author=B.+Pollack&author=K.+Puzino&author=M.K.+Franklin&volume=22&publication_year=2018&pages=334-348&pmid=26187415&doi=10.1177/1087054715594422&)]

7\. Heiligenstein E., Guenther G., Levy A., Savino F., Fulwiler J.  
Psychological and academic functioning in college students with attention  
deficit hyperactivity disorder. J. Am. Coll. Health. 1999;47:181–185. doi:  
10.1080/07448489909595644. [[PubMed](/pubmed/9919849)]  
[[CrossRef](//dx.doi.org/10.1080%2F07448489909595644)] [[Google  
Scholar](https://scholar.google.com/scholar_lookup?journal=J.+Am.+Coll.+Health&title=Psychological+and+academic+functioning+in+college+students+with+attention+deficit+hyperactivity+disorder&author=E.+Heiligenstein&author=G.+Guenther&author=A.+Levy&author=F.+Savino&author=J.+Fulwiler&volume=47&publication_year=1999&pages=181-185&pmid=9919849&doi=10.1080/07448489909595644&)]

8\. Richards T.L., Rosén L.A., Ramirez C.A. Psychological functioning  
differences among college students with confirmed ADHD, ADHD by self-report  
only, and without ADHD. J. Coll. Stud. Dev. 1999;40:299–304. [[Google  
Scholar](https://scholar.google.com/scholar_lookup?journal=J.+Coll.+Stud.+Dev.&title=Psychological+functioning+differences+among+college+students+with+confirmed+ADHD,+ADHD+by+self-  
report+only,+and+without+ADHD&author=T.L.+Richards&author=L.A.+Ros%C3%A9n&author=C.A.+Ramirez&volume=40&publication_year=1999&pages=299-304&)]

9\. Weyandt L.L., Oster D.R., Gudmundsdottir B.G., DuPaul G.J., Anastopoulos  
A.D. Neuropsychological functioning in college students with and without ADHD.  
Neuropsychology. 2016;31:160–172. doi: 10.1037/neu0000326. [[PMC free  
article](/pmc/articles/PMC5280458/?report=reader)]  
[[PubMed](/pubmed/27831696)] [[CrossRef](//dx.doi.org/10.1037%2Fneu0000326)]  
[[Google  
Scholar](https://scholar.google.com/scholar_lookup?journal=Neuropsychology&title=Neuropsychological+functioning+in+college+students+with+and+without+ADHD&author=L.L.+Weyandt&author=D.R.+Oster&author=B.G.+Gudmundsdottir&author=G.J.+DuPaul&author=A.D.+Anastopoulos&volume=31&publication_year=2016&pages=160-172&pmid=27831696&doi=10.1037/neu0000326&)]

10\. Storebø O.J., Ramstad E., Krogh H.B., Nilausen T.D., Skoog M., Holmskov  
M., Rosendal S., Groth C., Magnusson F.L., Moreira-Maia C.R., et al.  
Methylphenidate for attention-deficit/hyperactivity disorder in children and  
adolescents: Cochrane systematic review with meta-analyses and trial  
sequential analyses of randomised clinical trials. BMJ. 2015;351:h5203. doi:  
10.1136/bmj.h5203. [[PMC free  
article](/pmc/articles/PMC4659414/?report=reader)]  
[[PubMed](/pubmed/26608309)] [[CrossRef](//dx.doi.org/10.1136%2Fbmj.h5203)]  
[[Google  
Scholar](https://scholar.google.com/scholar_lookup?journal=BMJ&title=Methylphenidate+for+attention-  
deficit/hyperactivity+disorder+in+children+and+adolescents:+Cochrane+systematic+review+with+meta-  
analyses+and+trial+sequential+analyses+of+randomised+clinical+trials&author=O.J.+Storeb%C3%B8&author=E.+Ramstad&author=H.B.+Krogh&author=T.D.+Nilausen&author=M.+Skoog&volume=351&publication_year=2015&pages=h5203&pmid=26608309&doi=10.1136/bmj.h5203&)]

11\. Fageera W., Traicu A., Sengupta S.M., Fortier M., Choudhry Z., Labbe A.,  
Grizenko N., Joober R. Placebo responses and its determinants in children with  
ADHD across multiple observers and settings: A randomized clinical trial. Int.  
J. Methods Psychiatr. Res. 2018;27 doi: 10.1002/mpr.1572. [[PMC free  
article](/pmc/articles/PMC6877247/?report=reader)]  
[[PubMed](/pubmed/28664541)] [[CrossRef](//dx.doi.org/10.1002%2Fmpr.1572)]  
[[Google  
Scholar](https://scholar.google.com/scholar_lookup?journal=Int.+J.+Methods+Psychiatr.+Res.&title=Placebo+responses+and+its+determinants+in+children+with+ADHD+across+multiple+observers+and+settings:+A+randomized+clinical+trial&author=W.+Fageera&author=A.+Traicu&author=S.M.+Sengupta&author=M.+Fortier&author=Z.+Choudhry&volume=27&publication_year=2018&pmid=28664541&doi=10.1002/mpr.1572&)]

12\. Maneeton N., Maneeton B., Suttajit S., Reungyos J., Srisurapanont M.,  
Martin S.D. Exploratory meta-analysis on lisdexamfetamine versus placebo in  
adult ADHD. Drug Des. Dev. Ther. 2014;8:1685–1693. doi: 10.2147/DDDT.S68393.  
[[PMC free article](/pmc/articles/PMC4199984/?report=reader)]  
[[PubMed](/pubmed/25336914)] [[CrossRef](//dx.doi.org/10.2147%2FDDDT.S68393)]  
[[Google  
Scholar](https://scholar.google.com/scholar_lookup?journal=Drug+Des.+Dev.+Ther.&title=Exploratory+meta-  
analysis+on+lisdexamfetamine+versus+placebo+in+adult+ADHD&author=N.+Maneeton&author=B.+Maneeton&author=S.+Suttajit&author=J.+Reungyos&author=M.+Srisurapanont&volume=8&publication_year=2014&pages=1685-1693&pmid=25336914&doi=10.2147/DDDT.S68393&)]

13\. Weyandt L.L., Marraccini M.E., Gudmundsdottir B.G., Zavras B.M., Turcotte  
K.D., Munro B.A., Amoroso A.J. Misuse of prescription stimulants among college  
students: A review of the literature and implications for 66 morphological and  
cognitive effects on brain functioning. Exp. Clin. Psychopharmacol.  
2013;21:385–407. doi: 10.1037/a0034013. [[PubMed](/pubmed/24099359)]  
[[CrossRef](//dx.doi.org/10.1037%2Fa0034013)] [[Google  
Scholar](https://scholar.google.com/scholar_lookup?journal=Exp.+Clin.+Psychopharmacol.&title=Misuse+of+prescription+stimulants+among+college+students:+A+review+of+the+literature+and+implications+for+66+morphological+and+cognitive+effects+on+brain+functioning&author=L.L.+Weyandt&author=M.E.+Marraccini&author=B.G.+Gudmundsdottir&author=B.M.+Zavras&author=K.D.+Turcotte&volume=21&publication_year=2013&pages=385-407&pmid=24099359&doi=10.1037/a0034013&)]

14\. DuPaul G.J., Weyandt L.L., Rossi J.S., Vilardo B.A., O'Dell S.M., Carson  
K.M., Verdi G., Swentosky A. Double-blind, placebo-controlled, crossover study  
of the efficacy and safety of lisdexamfetamine dimesylate in college students  
with ADHD. J. Atten. Disord. 2012;16:202–220. doi: 10.1177/1087054711427299.  
[[PubMed](/pubmed/22166471)]  
[[CrossRef](//dx.doi.org/10.1177%2F1087054711427299)] [[Google  
Scholar](https://scholar.google.com/scholar_lookup?journal=J.+Atten.+Disord.&title=Double-  
blind,+placebo-  
controlled,+crossover+study+of+the+efficacy+and+safety+of+lisdexamfetamine+dimesylate+in+college+students+with+ADHD&author=G.J.+DuPaul&author=L.L.+Weyandt&author=J.S.+Rossi&author=B.A.+Vilardo&author=S.M.+O%E2%80%99Dell&volume=16&publication_year=2012&pages=202-220&pmid=22166471&doi=10.1177/1087054711427299&)]

15\. Benson K., Flory K., Humphreys K.L., Lee S.S. Misuse of stimulant  
medication among college students: A comprehensive review and meta-analysis.  
Clin. Child Fam. Psychol. Rev. 2015;18:50–76. doi: 10.1007/s10567-014-0177-z.  
[[PubMed](/pubmed/25575768)]  
[[CrossRef](//dx.doi.org/10.1007%2Fs10567-014-0177-z)] [[Google  
Scholar](https://scholar.google.com/scholar_lookup?journal=Clin.+Child+Fam.+Psychol.+Rev.&title=Misuse+of+stimulant+medication+among+college+students:+A+comprehensive+review+and+meta-  
analysis&author=K.+Benson&author=K.+Flory&author=K.L.+Humphreys&author=S.S.+Lee&volume=18&publication_year=2015&pages=50-76&pmid=25575768&doi=10.1007/s10567-014-0177-z&)]

16\. Babcock Q., Byrne T. Student perceptions of methylphenidate abuse at a  
public liberal arts college. J. Am. Coll. Health. 2000;49:143–145. doi:  
10.1080/07448480009596296. [[PubMed](/pubmed/11125642)]  
[[CrossRef](//dx.doi.org/10.1080%2F07448480009596296)] [[Google  
Scholar](https://scholar.google.com/scholar_lookup?journal=J.+Am.+Coll.+Health&title=Student+perceptions+of+methylphenidate+abuse+at+a+public+liberal+arts+college&author=Q.+Babcock&author=T.+Byrne&volume=49&publication_year=2000&pages=143-145&pmid=11125642&doi=10.1080/07448480009596296&)]

17\. McCabe S.E., Knight J.R., Teter C.J., Wechsler H. Non-medical use of  
prescription stimulants among US college students: Prevalence and correlates  
from a national survey. Addiction. 2005;100:96–106. doi:  
10.1111/j.1360-0443.2005.00944.x. [[PubMed](/pubmed/15598197)]  
[[CrossRef](//dx.doi.org/10.1111%2Fj.1360-0443.2005.00944.x)] [[Google  
Scholar](https://scholar.google.com/scholar_lookup?journal=Addiction&title=Non-  
medical+use+of+prescription+stimulants+among+US+college+students:+Prevalence+and+correlates+from+a+national+survey&author=S.E.+McCabe&author=J.R.+Knight&author=C.J.+Teter&author=H.+Wechsler&volume=100&publication_year=2005&pages=96-106&pmid=15598197&doi=10.1111/j.1360-0443.2005.00944.x&)]

18\. Dupont R.L., Coleman J.J., Bucher R.H., Wilford B.B. NCharacteristics and  
motives of college students who engage in nonmedical use of methylphenidate.  
Am. J. Addict. 2008;17:167–171. [[PubMed](/pubmed/18463991)] [[Google  
Scholar](https://scholar.google.com/scholar_lookup?journal=Am.+J.+Addict.&title=NCharacteristics+and+motives+of+college+students+who+engage+in+nonmedical+use+of+methylphenidate&author=R.L.+Dupont&author=J.J.+Coleman&author=R.H.+Bucher&author=B.B.+Wilford&volume=17&publication_year=2008&pages=167-171&pmid=18463991&)]

19\. Weyandt L.L., Janusis G., Wilson K.G., Verdi G., Paquin G., Lopes J.,  
Varejao M., Dussault C. Nonmedical prescription stimulant use among a sample  
of college students: Relationship with psychological variables. J. Atten.  
Disord. 2009;13:284–296. doi: 10.1177/1087054709342212.  
[[PubMed](/pubmed/19767596)]  
[[CrossRef](//dx.doi.org/10.1177%2F1087054709342212)] [[Google  
Scholar](https://scholar.google.com/scholar_lookup?journal=J.+Atten.+Disord.&title=Nonmedical+prescription+stimulant+use+among+a+sample+of+college+students:+Relationship+with+psychological+variables&author=L.L.+Weyandt&author=G.+Janusis&author=K.G.+Wilson&author=G.+Verdi&author=G.+Paquin&volume=13&publication_year=2009&pages=284-296&pmid=19767596&doi=10.1177/1087054709342212&)]

20\. Judson R., Langdon S.W. Illicit use of prescription stimulants among  
college students: Prescription status, motives, theory of planned behaviour,  
knowledge and self-diagnostic tendencies. Psychol. Health Med. 2009;14:97–104.  
doi: 10.1080/13548500802126723. [[PubMed](/pubmed/19085316)]  
[[CrossRef](//dx.doi.org/10.1080%2F13548500802126723)] [[Google  
Scholar](https://scholar.google.com/scholar_lookup?journal=Psychol.+Health+Med.&title=Illicit+use+of+prescription+stimulants+among+college+students:+Prescription+status,+motives,+theory+of+planned+behaviour,+knowledge+and+self-  
diagnostic+tendencies&author=R.+Judson&author=S.W.+Langdon&volume=14&publication_year=2009&pages=97-104&pmid=19085316&doi=10.1080/13548500802126723&)]

21\. Bossaer J.B., Gray J.A., Miller S.E., Enck G., Gaddipati V.C., Enck R.E.  
The use and misuse of prescription stimulants as "cognitive enhancers" by  
students at one academic health sciences center. Acad. Med. 2013;88:967–971.  
doi: 10.1097/ACM.0b013e318294fc7b. [[PubMed](/pubmed/23702522)]  
[[CrossRef](//dx.doi.org/10.1097%2FACM.0b013e318294fc7b)] [[Google  
Scholar](https://scholar.google.com/scholar_lookup?journal=Acad.+Med.&title=The+use+and+misuse+of+prescription+stimulants+as+%E2%80%9Ccognitive+enhancers%E2%80%9D+by+students+at+one+academic+health+sciences+center&author=J.B.+Bossaer&author=J.A.+Gray&author=S.E.+Miller&author=G.+Enck&author=V.C.+Gaddipati&volume=88&publication_year=2013&pages=967-971&pmid=23702522&doi=10.1097/ACM.0b013e318294fc7b&)]

22\. Munro B.A., Weyandt L.L., Marraccini M.E., Oster D.R. The relationship  
between nonmedical use of prescription stimulants, executive functioning, and  
academic outcomes. Addict. Behav. 2017;65:250–257. doi:  
10.1016/j.addbeh.2016.08.023. [[PubMed](/pubmed/27567397)]  
[[CrossRef](//dx.doi.org/10.1016%2Fj.addbeh.2016.08.023)] [[Google  
Scholar](https://scholar.google.com/scholar_lookup?journal=Addict.+Behav.&title=The+relationship+between+nonmedical+use+of+prescription+stimulants,+executive+functioning,+and+academic+outcomes&author=B.A.+Munro&author=L.L.+Weyandt&author=M.E.+Marraccini&author=D.R.+Oster&volume=65&publication_year=2017&pages=250-257&pmid=27567397&doi=10.1016/j.addbeh.2016.08.023&)]

23\. Mache S., Eickenhorst P., Vitzthum K., Klapp B.F., Groneberg D.A.  
Cognitive-enhancing substance use at German universities: Frequency, reasons  
and gender differences. Wiener Med. Wochenschr. 2012;162:262–271. doi:  
10.1007/s10354-012-0115-y. [[PubMed](/pubmed/22707077)]  
[[CrossRef](//dx.doi.org/10.1007%2Fs10354-012-0115-y)] [[Google  
Scholar](https://scholar.google.com/scholar_lookup?journal=Wiener+Med.+Wochenschr.&title=Cognitive-  
enhancing+substance+use+at+German+universities:+Frequency,+reasons+and+gender+differences&author=S.+Mache&author=P.+Eickenhorst&author=K.+Vitzthum&author=B.F.+Klapp&author=D.A.+Groneberg&volume=162&publication_year=2012&pages=262-271&pmid=22707077&doi=10.1007/s10354-012-0115-y&)]

24\. Gudmundsdottir B.G., Weyandt L.L., Ernudottir G.B. Prescription stimulant  
misuse and ADHD symptomatology among college students in Iceland. J. Atten.  
Disord. 2016 doi: 10.1177/1087054716684379. [[PubMed](/pubmed/28013572)]  
[[CrossRef](//dx.doi.org/10.1177%2F1087054716684379)] [[Google  
Scholar](https://scholar.google.com/scholar_lookup?journal=J.+Atten.+Disord.&title=Prescription+stimulant+misuse+and+ADHD+symptomatology+among+college+students+in+Iceland&author=B.G.+Gudmundsdottir&author=L.L.+Weyandt&author=G.B.+Ernudottir&publication_year=2016&pmid=28013572&doi=10.1177/1087054716684379&)]

25\. Maier L.J., Liechti M.E., Herzig F., Schaub M.P. To dope or not to dope:  
Neuroenhancement with prescription drugs and drugs of abuse among Swiss  
university students. PLoS ONE. 2013;8:e77967. doi:  
10.1371/journal.pone.0077967. [[PMC free  
article](/pmc/articles/PMC3827185/?report=reader)]  
[[PubMed](/pubmed/24236008)]  
[[CrossRef](//dx.doi.org/10.1371%2Fjournal.pone.0077967)] [[Google  
Scholar](https://scholar.google.com/scholar_lookup?journal=PLoS+ONE&title=To+dope+or+not+to+dope:+Neuroenhancement+with+prescription+drugs+and+drugs+of+abuse+among+Swiss+university+students&author=L.J.+Maier&author=M.E.+Liechti&author=F.+Herzig&author=M.P.+Schaub&volume=8&publication_year=2013&pages=e77967&pmid=24236008&doi=10.1371/journal.pone.0077967&)]

26\. Singh I., Bard I., Jackson J. Robust resilience and substantial interest:  
A survey of pharmacological cognitive enhancement among university students in  
the UK and Ireland. PLoS ONE. 2014;9:e105969. doi:  
10.1371/journal.pone.0105969. [[PMC free  
article](/pmc/articles/PMC4214670/?report=reader)]  
[[PubMed](/pubmed/25356917)]  
[[CrossRef](//dx.doi.org/10.1371%2Fjournal.pone.0105969)] [[Google  
Scholar](https://scholar.google.com/scholar_lookup?journal=PLoS+ONE&title=Robust+resilience+and+substantial+interest:+A+survey+of+pharmacological+cognitive+enhancement+among+university+students+in+the+UK+and+Ireland&author=I.+Singh&author=I.+Bard&author=J.+Jackson&volume=9&publication_year=2014&pages=e105969&pmid=25356917&doi=10.1371/journal.pone.0105969&)]

27\. Gudmundsdottir B.G., Weyandt L.L., Munro B.A. Prescription stimulant  
misuse: International findings and implications for policy, prevention, and  
intervention. ADHD Rep. 2016;24:1–14. doi: 10.1521/adhd.2016.24.6.1.  
[[CrossRef](//dx.doi.org/10.1521%2Fadhd.2016.24.6.1)] [[Google  
Scholar](https://scholar.google.com/scholar_lookup?journal=ADHD+Rep.&title=Prescription+stimulant+misuse:+International+findings+and+implications+for+policy,+prevention,+and+intervention&author=B.G.+Gudmundsdottir&author=L.L.+Weyandt&author=B.A.+Munro&volume=24&publication_year=2016&pages=1-14&doi=10.1521/adhd.2016.24.6.1&)]

28\. Arria A.M., O'Grady K.E., Caldeira K.M., Vincent K.B., Wish E.D.  
Nonmedical use of prescription stimulants and analgesics: Associations with  
social and academic behaviors among college students. J. Drug Issues.  
2008;38:1045–1060. doi: 10.1177/002204260803800406. [[PMC free  
article](/pmc/articles/PMC2857807/?report=reader)]  
[[PubMed](/pubmed/20414361)]  
[[CrossRef](//dx.doi.org/10.1177%2F002204260803800406)] [[Google  
Scholar](https://scholar.google.com/scholar_lookup?journal=J.+Drug+Issues&title=Nonmedical+use+of+prescription+stimulants+and+analgesics:+Associations+with+social+and+academic+behaviors+among+college+students&author=A.M.+Arria&author=K.E.+O%E2%80%99Grady&author=K.M.+Caldeira&author=K.B.+Vincent&author=E.D.+Wish&volume=38&publication_year=2008&pages=1045-1060&pmid=20414361&doi=10.1177/002204260803800406&)]

29\. Ilieva I., Boland J., Farah M.J. Objective and subjective cognitive  
enhancing effects of mixed amphetamine salts in healthy people.  
Neuropharmacology. 2013;64:496–505. doi: 10.1016/j.neuropharm.2012.07.021.  
[[PubMed](/pubmed/22884611)]  
[[CrossRef](//dx.doi.org/10.1016%2Fj.neuropharm.2012.07.021)] [[Google  
Scholar](https://scholar.google.com/scholar_lookup?journal=Neuropharmacology&title=Objective+and+subjective+cognitive+enhancing+effects+of+mixed+amphetamine+salts+in+healthy+people&author=I.+Ilieva&author=J.+Boland&author=M.J.+Farah&volume=64&publication_year=2013&pages=496-505&pmid=22884611&doi=10.1016/j.neuropharm.2012.07.021&)]

31\. White T.L., Lejuez C.W., de Wit H. Personality and gender differences in  
effects of D-amphetamine on risk-taking. Exp. Clin. Psychopharmacol.  
2007;15:599–609. doi: 10.1037/1064-1297.15.6.599. [[PubMed](/pubmed/18179313)]  
[[CrossRef](//dx.doi.org/10.1037%2F1064-1297.15.6.599)] [[Google  
Scholar](https://scholar.google.com/scholar_lookup?journal=Exp.+Clin.+Psychopharmacol.&title=Personality+and+gender+differences+in+effects+of+D-amphetamine+on+risk-  
taking&author=T.L.+White&author=C.W.+Lejuez&author=H.+de+Wit&volume=15&publication_year=2007&pages=599-609&pmid=18179313&doi=10.1037/1064-1297.15.6.599&)]

32\. Marraccini M.E., Weyandt L.L., Rossi J.S., Gudmundsdottir B.G.  
Neurocognitive enhancement or impairment? A systematic meta-analysis of  
prescription stimulant effects on processing speed, decision-making, planning,  
and cognitive perseveration. Exp. Clin. Psychopharmacol. 2016;24:269–284. doi:  
10.1037/pha0000079. [[PMC free  
article](/pmc/articles/PMC4968888/?report=reader)]  
[[PubMed](/pubmed/27454675)] [[CrossRef](//dx.doi.org/10.1037%2Fpha0000079)]  
[[Google  
Scholar](https://scholar.google.com/scholar_lookup?journal=Exp.+Clin.+Psychopharmacol.&title=Neurocognitive+enhancement+or+impairment?+A+systematic+meta-  
analysis+of+prescription+stimulant+effects+on+processing+speed,+decision-  
making,+planning,+and+cognitive+perseveration&author=M.E.+Marraccini&author=L.L.+Weyandt&author=J.S.+Rossi&author=B.G.+Gudmundsdottir&volume=24&publication_year=2016&pages=269-284&pmid=27454675&doi=10.1037/pha0000079&)]

33\. Repantis D., Schlattmann P., Laisney O., Heuser I. Modafinil and  
methylphenidate for neuroenhancement in healthy individuals: A systematic  
review. Pharmacol. Res. 2010;62:187–206. doi: 10.1016/j.phrs.2010.04.002.  
[[PubMed](/pubmed/20416377)]  
[[CrossRef](//dx.doi.org/10.1016%2Fj.phrs.2010.04.002)] [[Google  
Scholar](https://scholar.google.com/scholar_lookup?journal=Pharmacol.+Res.&title=Modafinil+and+methylphenidate+for+neuroenhancement+in+healthy+individuals:+A+systematic+review&author=D.+Repantis&author=P.+Schlattmann&author=O.+Laisney&author=I.+Heuser&volume=62&publication_year=2010&pages=187-206&pmid=20416377&doi=10.1016/j.phrs.2010.04.002&)]

34\. Morean M.E., de Wit H., King A., Sofuoglu M., Rueger S.Y., O'Malley S.  
The Drug Effects Questionnaire: Psychometric support across multiple  
substances. Psychopharmacology. 2013;227:177–192. doi:  
10.1007/s00213-012-2954-z. [[PMC free  
article](/pmc/articles/PMC3624068/?report=reader)]  
[[PubMed](/pubmed/23271193)]  
[[CrossRef](//dx.doi.org/10.1007%2Fs00213-012-2954-z)] [[Google  
Scholar](https://scholar.google.com/scholar_lookup?journal=Psychopharmacology&title=The+Drug+Effects+Questionnaire:+Psychometric+support+across+multiple+substances&author=M.E.+Morean&author=H.+de+Wit&author=A.+King&author=M.+Sofuoglu&author=S.Y.+Rueger&volume=227&publication_year=2013&pages=177-192&pmid=23271193&doi=10.1007/s00213-012-2954-z&)]

35\. Morrone J.V., Depue R.A., Scherer A.J., White T.L. Film-induced incentive  
motivation and positive activation in relation to agentic and affiliative  
components of extroversion. Pers. Ind. Differ. 2000;29:199–216. doi:  
10.1016/S0191-8869(99)00187-7.  
[[CrossRef](//dx.doi.org/10.1016%2FS0191-8869%5C\(99%5C\)00187-7)] [[Google  
Scholar](https://scholar.google.com/scholar_lookup?journal=Pers.+Ind.+Differ.&title=Film-  
induced+incentive+motivation+and+positive+activation+in+relation+to+agentic+and+affiliative+components+of+extroversion&author=J.V.+Morrone&author=R.A.+Depue&author=A.J.+Scherer&author=T.L.+White&volume=29&publication_year=2000&pages=199-216&doi=10.1016/S0191-8869%5C\(99%5C\)00187-7&)]

36\. White T.L., Lott D., de Wit H. Personality and the subjective effects of  
acute amphetamine in healthy volunteers. Neuropsychopharmacology.  
2006;31:1064–1074. doi: 10.1038/sj.npp.1300939. [[PubMed](/pubmed/16237380)]  
[[CrossRef](//dx.doi.org/10.1038%2Fsj.npp.1300939)] [[Google  
Scholar](https://scholar.google.com/scholar_lookup?journal=Neuropsychopharmacology&title=Personality+and+the+subjective+effects+of+acute+amphetamine+in+healthy+volunteers&author=T.L.+White&author=D.+Lott&author=H.+de+Wit&volume=31&publication_year=2006&pages=1064-1074&pmid=16237380&doi=10.1038/sj.npp.1300939&)]

37\. Depue R.A., Fu Y. On the nature of extroversion: Variation in conditioned  
contextual activation of dopamine-facilitated affective, cognitive, and motor  
processes. Front. Hum. Neurosci. 2013;7:288. doi: 10.3389/fnhum.2013.00288.  
[[PMC free article](/pmc/articles/PMC3682132/?report=reader)]  
[[PubMed](/pubmed/23785330)]  
[[CrossRef](//dx.doi.org/10.3389%2Ffnhum.2013.00288)] [[Google  
Scholar](https://scholar.google.com/scholar_lookup?journal=Front.+Hum.+Neurosci.&title=On+the+nature+of+extraversion:+Variation+in+conditioned+contextual+activation+of+dopamine-  
facilitated+affective,+cognitive,+and+motor+processes&author=R.A.+Depue&author=Y.+Fu&volume=7&publication_year=2013&pages=288&pmid=23785330&doi=10.3389/fnhum.2013.00288&)]

38\. White T.L., Monnig M., Walsh E., Nitenson A.Z., Harris A.D., Cohen R.A.,  
Porges E.C., Woods A.J., Lamb D.G., Boyd C.A., et al. Psychostimulant Drug  
Effects on Glutamate, Glx, and Creatine in the Anterior Cingulate Cortex and  
Subjective Response in Healthy Humans. Neuropsychopharmacology.  
2018;43:1498–1509. doi: 10.1038/s41386-018-0027-7. [[PMC free  
article](/pmc/articles/PMC5983539/?report=reader)]  
[[PubMed](/pubmed/29511334)]  
[[CrossRef](//dx.doi.org/10.1038%2Fs41386-018-0027-7)] [[Google  
Scholar](https://scholar.google.com/scholar_lookup?journal=Neuropsychopharmacology&title=Psychostimulant+Drug+Effects+on+Glutamate,+Glx,+and+Creatine+in+the+Anterior+Cingulate+Cortex+and+Subjective+Response+in+Healthy+Humans&author=T.L.+White&author=M.+Monnig&author=E.+Walsh&author=A.Z.+Nitenson&author=A.D.+Harris&volume=43&publication_year=2018&pages=1498-1509&pmid=29511334&doi=10.1038/s41386-018-0027-7&)]

39\. Sheehan D.V., Lecrubier Y., Sheehan K.H., Amorim P., Janavs J., Weiller  
E., Hergueta T., Baker R., Dunbar G.C. The Mini-International Neuropsychiatric  
Interview (M.I.N.I.): The development and validation of a structured  
diagnostic psychiatric interview for DSM-IV and ICD-10. J. Clin. Psychiatry.  
1998;59(Suppl. 20):22–57. [[PubMed](/pubmed/9881538)] [[Google  
Scholar](https://scholar.google.com/scholar_lookup?journal=J.+Clin.+Psychiatry&title=The+Mini-  
International+Neuropsychiatric+Interview+%5C\(M.I.N.I.%5C\):+The+development+and+validation+of+a+structured+diagnostic+psychiatric+interview+for+DSM-  
IV+and+ICD-10&author=D.V.+Sheehan&author=Y.+Lecrubier&author=K.H.+Sheehan&author=P.+Amorim&author=J.+Janavs&volume=59&issue=Suppl.+20&publication_year=1998&pages=22-57&pmid=9881538&)]

40\. Weyandt L.L., Oster D.R., Marraccini M.E., Gudmundsdottir B.G., Munro  
B.A., Zavras B.M., Kuhar B. Pharmacological interventions for adolescents and  
adults with ADHD: Stimulant and nonstimulant medications and misuse of  
prescription stimulants. Psychol. Res. Behav. Manag. 2014;7:223–249. doi:  
10.2147/PRBM.S47013. [[PMC free  
article](/pmc/articles/PMC4164338/?report=reader)]  
[[PubMed](/pubmed/25228824)] [[CrossRef](//dx.doi.org/10.2147%2FPRBM.S47013)]  
[[Google  
Scholar](https://scholar.google.com/scholar_lookup?journal=Psychol.+Res.+Behav.+Manag.&title=Pharmacological+interventions+for+adolescents+and+adults+with+ADHD:+Stimulant+and+nonstimulant+medications+and+misuse+of+prescription+stimulants&author=L.L.+Weyandt&author=D.R.+Oster&author=M.E.+Marraccini&author=B.G.+Gudmundsdottir&author=B.A.+Munro&volume=7&publication_year=2014&pages=223-249&pmid=25228824&doi=10.2147/PRBM.S47013&)]

41\. Wechsler D. Wechsler Adult Intelligence Scale. 4th ed. Pearson; San  
Antonio, TX, USA: 2008. [[Google  
Scholar](https://scholar.google.com/scholar_lookup?title=Wechsler+Adult+Intelligence+Scale&author=D.+Wechsler&publication_year=2008&)]

42\. Woodcock R.W., McGrew K.S., Mather N. Woodcock-Johnson III. Riverside  
Publishing; Itasca, IL, USA: 2001. [[Google  
Scholar](https://scholar.google.com/scholar_lookup?title=Woodcock-  
Johnson+III&author=R.W.+Woodcock&author=K.S.+McGrew&author=N.+Mather&publication_year=2001&)]

43\. Multi-Health Systems Inc . Conners' Continuous Performance Test. 3rd ed.  
MHS; North Tonawanda, NY, USA: 2014. [[Google  
Scholar](https://scholar.google.com/scholar_lookup?title=Conners%E2%80%99+Continuous+Performance+Test&publication_year=2014&)]

44\. Gioia G.A., Isquith P.K., Guy S.C., Kenworthy L. The Behavior Rating  
Inventory of Executive Function Professional Manual. Psychological Assessment  
Resources; Odessa, FL, USA: 2000. [[Google  
Scholar](https://scholar.google.com/scholar_lookup?title=The+Behavior+Rating+Inventory+of+Executive+Function+Professional+Manual&author=G.A.+Gioia&author=P.K.+Isquith&author=S.C.+Guy&author=L.+Kenworthy&publication_year=2000&)]

45\. Wiederholt J.L., Bryant B.R. Gray Oral Reading Test. 3rd ed. Pro-Ed;  
Austin, TX, USA: 1992. [[Google  
Scholar](https://scholar.google.com/scholar_lookup?title=Gray+Oral+Reading+Test&author=J.L.+Wiederholt&author=B.R.+Bryant&publication_year=1992&)]

46\. White T.L., Justice A.J.H., de Wit H. Differential subjective effects of  
D-amphetamine by gender, hormone levels and menstrual cycle phase. Pharmacol.  
Biochem. Behav. 2002;73:729–741. doi: 10.1016/S0091-3057(02)00818-3.  
[[PubMed](/pubmed/12213517)]  
[[CrossRef](//dx.doi.org/10.1016%2FS0091-3057%5C\(02%5C\)00818-3)] [[Google  
Scholar](https://scholar.google.com/scholar_lookup?journal=Pharmacol.+Biochem.+Behav.&title=Differential+subjective+effects+of+D-amphetamine+by+gender,+hormone+levels+and+menstrual+cycle+phase&author=T.L.+White&author=A.J.H.+Justice&author=H.+de+Wit&volume=73&publication_year=2002&pages=729-741&pmid=12213517&doi=10.1016/S0091-3057%5C\(02%5C\)00818-3&)]

47\. White T.L. Beyond sensation seeking: A conceptual framework for  
individual differences in psychostimulant drug effects in healthy humans.  
Curr. Opin. Behav. Sci. 2017;13:63–70. doi: 10.1016/j.cobeha.2016.10.008.  
[[PMC free article](/pmc/articles/PMC5244826/?report=reader)]  
[[PubMed](/pubmed/28111627)]  
[[CrossRef](//dx.doi.org/10.1016%2Fj.cobeha.2016.10.008)] [[Google  
Scholar](https://scholar.google.com/scholar_lookup?journal=Curr.+Opin.+Behav.+Sci.&title=Beyond+sensation+seeking:+A+conceptual+framework+for+individual+differences+in+psychostimulant+drug+effects+in+healthy+humans&author=T.L.+White&volume=13&publication_year=2017&pages=63-70&pmid=28111627&doi=10.1016/j.cobeha.2016.10.008&)]

48\. Depue R.A. Interpersonal behavior and the structure of personality:  
Neurobehavioral foundation of agentic extroversion and affiliation. In: Turhan  
C., editor. Biology of Personality and Individual Differences. Guilford Press;  
New York, NY, USA: 2006. pp. 60–92. [[Google  
Scholar](https://scholar.google.com/scholar_lookup?title=Biology+of+Personality+and+Individual+Differences&author=R.A.+Depue&publication_year=2006&)]

49\. White T.L., Grover V.K., de Wit H. Cortisol effects of D-amphetamine  
relate to traits of fearlessness and aggression but not anxiety in healthy  
humans. Pharmacol. Biochem. Behav. 2006;85:123–131. doi:  
10.1016/j.pbb.2006.07.020. [[PubMed](/pubmed/16934318)]  
[[CrossRef](//dx.doi.org/10.1016%2Fj.pbb.2006.07.020)] [[Google  
Scholar](https://scholar.google.com/scholar_lookup?journal=Pharmacol.+Biochem.+Behav.&title=Cortisol+effects+of+D-amphetamine+relate+to+traits+of+fearlessness+and+aggression+but+not+anxiety+in+healthy+humans&author=T.L.+White&author=V.K.+Grover&author=H.+de+Wit&volume=85&publication_year=2006&pages=123-131&pmid=16934318&doi=10.1016/j.pbb.2006.07.020&)]

51\. Cohen J. Statistical Power Analysis for the Behavioral Sciences. Lawrence  
Erlbaum Associates Inc.; Mahwah, NJ, USA: 1988. [[Google  
Scholar](https://scholar.google.com/scholar_lookup?title=Statistical+Power+Analysis+for+the+Behavioral+Sciences&author=J.+Cohen&publication_year=1988&)]

52\. Richardson J.T.E. Eta squared and partial eta squared as measures of  
effect size in educational research. Educ. Res. Rev. 2011;6:135–147. doi:  
10.1016/j.edurev.2010.12.001.  
[[CrossRef](//dx.doi.org/10.1016%2Fj.edurev.2010.12.001)] [[Google  
Scholar](https://scholar.google.com/scholar_lookup?journal=Educ.+Res.+Rev.&title=Eta+squared+and+partial+eta+squared+as+measures+of+effect+size+in+educational+research&author=J.T.E.+Richardson&volume=6&publication_year=2011&pages=135-147&doi=10.1016/j.edurev.2010.12.001&)]

53\. Faul F., Erdfelder E., Buchner A., Lang A.G. Statistical power analyses  
using G*Power 3.1: Tests for correlation and regression analyses. Behav. Res.  
Methods. 2009;41:1149–1160. doi: 10.3758/BRM.41.4.1149.  
[[PubMed](/pubmed/19897823)]  
[[CrossRef](//dx.doi.org/10.3758%2FBRM.41.4.1149)] [[Google  
Scholar](https://scholar.google.com/scholar_lookup?journal=Behav.+Res.+Methods&title=Statistical+power+analyses+using+G*Power+3.1:+Tests+for+correlation+and+regression+analyses&author=F.+Faul&author=E.+Erdfelder&author=A.+Buchner&author=A.G.+Lang&volume=41&publication_year=2009&pages=1149-1160&pmid=19897823&doi=10.3758/BRM.41.4.1149&)]

54\. Hawk L.W., Fosco W.D., Colder C.R., Waxmonsky J.G., Pelham W.E., Rosch  
K.S. How do stimulant treatments for ADHD work? Evidence for mediation by  
improved cognition. J. Child Psychol. Psychiatry. 2018 doi:  
10.1111/jcpp.12917. [[PubMed](/pubmed/29733106)]  
[[CrossRef](//dx.doi.org/10.1111%2Fjcpp.12917)] [[Google  
Scholar](https://scholar.google.com/scholar_lookup?journal=J.+Child+Psychol.+Psychiatry&title=How+do+stimulant+treatments+for+ADHD+work?+Evidence+for+mediation+by+improved+cognition&author=L.W.+Hawk&author=W.D.+Fosco&author=C.R.+Colder&author=J.G.+Waxmonsky&author=W.E.+Pelham&publication_year=2018&pmid=29733106&doi=10.1111/jcpp.12917&)]

55\. Pievsky M.A., McGrath R.E. Neurocognitive effects of methylphenidate in  
adults with attention-deficit/hyperactivity disorder: A meta-analysis.  
Neurosci. Biobehav. Rev. 2018;90:447–455. [[PubMed](/pubmed/29751051)]  
[[Google  
Scholar](https://scholar.google.com/scholar_lookup?journal=Neurosci.+Biobehav.+Rev.&title=Neurocognitive+effects+of+methylphenidate+in+adults+with+attention-  
deficit/hyperactivity+disorder:+A+meta-  
analysis&author=M.A.+Pievsky&author=R.E.+McGrath&volume=90&publication_year=2018&pages=447-455&pmid=29751051&)]

56\. Roth R.M., Lance C.E., Isquith P.K., Fischer A.S., Giancola P.R.  
Confirmatory factor analysis of the Behavior Rating Inventory of Executive  
Function-Adult version in healthy adults and application to attention-  
deficit/hyperactivity disorder. Arch. Clin. Neuropsychol. 2013;28:425–434.  
doi: 10.1093/arclin/act031. [[PMC free  
article](/pmc/articles/PMC3711374/?report=reader)]  
[[PubMed](/pubmed/23676185)]  
[[CrossRef](//dx.doi.org/10.1093%2Farclin%2Fact031)] [[Google  
Scholar](https://scholar.google.com/scholar_lookup?journal=Arch.+Clin.+Neuropsychol.&title=Confirmatory+factor+analysis+of+the+Behavior+Rating+Inventory+of+Executive+Function-  
Adult+version+in+healthy+adults+and+application+to+attention-  
deficit/hyperactivity+disorder&author=R.M.+Roth&author=C.E.+Lance&author=P.K.+Isquith&author=A.S.+Fischer&author=P.R.+Giancola&volume=28&publication_year=2013&pages=425-434&pmid=23676185&doi=10.1093/arclin/act031&)]

57\. Childs E., Bershad A.K., de Wit H. Effects of D-amphetamine upon  
psychosocial stress responses. J. Psychopharmacol. 2016;30:608–615. doi:  
10.1177/0269881116650388. [[PubMed](/pubmed/27235381)]  
[[CrossRef](//dx.doi.org/10.1177%2F0269881116650388)] [[Google  
Scholar](https://scholar.google.com/scholar_lookup?journal=J.+Psychopharmacol.&title=Effects+of+D-amphetamine+upon+psychosocial+stress+responses&author=E.+Childs&author=A.K.+Bershad&author=H.+de+Wit&volume=30&publication_year=2016&pages=608-615&pmid=27235381&doi=10.1177/0269881116650388&)]

58\. Cropsey K.L., Schiavon S., Hendricks P.S., Froelich M., Lentowicz I.,  
Fargason R. Mixed-amphetamine salts expectancies among college students: Is  
stimulant induced cognitive enhancement a placebo effect? Drug Alcohol Depend.  
2017;178:302–309. doi: 10.1016/j.drugalcdep.2017.05.024.  
[[PubMed](/pubmed/28686989)]  
[[CrossRef](//dx.doi.org/10.1016%2Fj.drugalcdep.2017.05.024)] [[Google  
Scholar](https://scholar.google.com/scholar_lookup?journal=Drug+Alcohol+Depend.&title=Mixed-  
amphetamine+salts+expectancies+among+college+students:+Is+stimulant+induced+cognitive+enhancement+a+placebo+effect?&author=K.L.+Cropsey&author=S.+Schiavon&author=P.S.+Hendricks&author=M.+Froelich&author=I.+Lentowicz&volume=178&publication_year=2017&pages=302-309&pmid=28686989&doi=10.1016/j.drugalcdep.2017.05.024&)]

59\. Venter A.M., Scott E. Maximizing power in randomized designs when N is  
small. In: Hoyle R.H., editor. Statistical Strategies for Small Sample  
Research. Sage Publications; Thousand Oaks, CA, USA: 1999. pp. 33–57. [[Google  
Scholar](https://scholar.google.com/scholar_lookup?title=Statistical+Strategies+for+Small+Sample+Research&author=A.M.+Venter&author=E.+Scott&publication_year=1999&)]

* * *

# Article Adderall

Posted  
by[Dsmith](https://begininfiniteloop.wordpress.com/author/f4ultyc0d3/)[April  
1, 2022](https://begininfiniteloop.wordpress.com/2022/04/01/neurocognitive-  
autonomic-and-mood-effects-of-adderall-a-pilot-study-of-healthy-college-  
students/)Posted  
in[adderall](https://begininfiniteloop.wordpress.com/category/adderall/)Tags:[adderall](https://begininfiniteloop.wordpress.com/tag/adderall/)[Leave  
a comment on Neurocognitive, Autonomic, and Mood Effects of Adderall: A Pilot  
Study of Healthy College  
Students](https://begininfiniteloop.wordpress.com/2022/04/01/neurocognitive-  
autonomic-and-mood-effects-of-adderall-a-pilot-study-of-healthy-college-  
students/#respond)

## [Loop](https://begininfiniteloop.wordpress.com/2022/03/30/loop/)

while (true) {

    for (let i = 5; i > 0; i--) {
    

console.log

//begin-infinite-loop

}

for (let i = 5; i > 0; i–) {

console.log("Infinite loop");

}

Posted  
by[Dsmith](https://begininfiniteloop.wordpress.com/author/f4ultyc0d3/)[March  
30, 2022](https://begininfiniteloop.wordpress.com/2022/03/30/loop/)Posted  
in[js](https://begininfiniteloop.wordpress.com/category/js/),  
[jserrors](https://begininfiniteloop.wordpress.com/category/jserrors/),  
[loops](https://begininfiniteloop.wordpress.com/category/loops/)Tags:[errors](https://begininfiniteloop.wordpress.com/tag/errors/),  
[js](https://begininfiniteloop.wordpress.com/tag/js/),  
[loops](https://begininfiniteloop.wordpress.com/tag/loops/)[Leave a comment on  
Loop](https://begininfiniteloop.wordpress.com/2022/03/30/loop/#respond)

##

[Musicplayr](https://begininfiniteloop.wordpress.com/2022/03/30/musicplayr/)

"""let now_playing = document.querySelector(".now-playing");

let track_art = document.querySelector(".track-art");

let track_name = document.querySelector(".track-name");

let track_artist = document.querySelector(".track-artist");

let playpause_btn = document.querySelector(".playpause-track");

let next_btn = document.querySelector(".next-track");

let prev_btn = document.querySelector(".prev-track");

let seek_slider = document.querySelector(".seek_slider");

let volume_slider = document.querySelector(".volume_slider");

let curr_time = document.querySelector(".current-time");

let total_duration = document.querySelector(".total-duration");

let track_index = 0;

let isPlaying = false;

let updateTimer;

let curr_track = document.createElement('audio');

let track_list = [

{

name: "Night Owl",

artist: "Broke For Free",

image: "Image URL",

path: "Night_Owl.mp3"

},

{

name: "Enthusiast",

artist: "Tours",

image: "Image URL",

path: "Enthusiast.mp3"

},

{

name: "Shipping Lanes",

artist: "Chad Crouch",

image: "Image URL",

path: "Shipping_Lanes.mp3",

},

];

function loadTrack(track_index) {

clearInterval(updateTimer);

resetValues();

curr_track.src = track_list[track_index].path;

curr_track.load();

track_art.style.backgroundImage =

"url (" + track_list[track_index].image + ")";

track_name.textContent = track_list[track_index].name;

track_artist.textContent = track_list[track_index].artist;

now_playing.textContent =

"PLAYING" + (track_index + 1) + " OF " + track_list.length;

updateTimer = setInterval(seekUpdate, 1000);

curr_track.addEventListener("ended", nextTrack);

random_bg_color();

}

function random_bg_color() {

let red = Math.floor(Math.random() * 256) + 64;

let green = Math.floor(Math.random() * 256) + 64;

let blue = Math.floor(Math.random() * 256) + 64;

let bgColor = "rgb(" + red + ", " + green + ", " + blue + ")";

document.body.style.background = bgColor;

}

function resetValues() {

curr_time.textContent = "00:00";

total_duration.textContent = "00:00";

seek_slider.value = 0;

}

function playpauseTrack() {

if (!isPlaying) playTrack();

else pauseTrack();

}

function playTrack()

curr_track.play();

isPlaying = true;

playpause_btn.innerHTML = ' __';

}

function pauseTrack() {

curr_track.pause();

isPlaying = false;

playpause_btn.innerHTML = ' __';

}

function nextTrack() {

if (track_index < track_list.length – 1)

track_index += 1;

else track_index = 0;

loadTrack(track_index);

playTrack();

}

function prevTrack() {

if (track_index > 0)

track_index -= 1;

else track_index = track_list.length – 1;

loadTrack(track_index);

playTrack();

}

function seekTo() {

seekto = curr_track.duration * (seek_slider.value / 100);

curr_track.currentTime = seekto;

}

function setVolume()

curr_track.volume = volume_slider.value / 100;

}

function seekUpdate() {

let seekPosition = 0;

if (!isNaN(curr_track.duration)) {

seekPosition = curr_track.currentTime * (100 / curr_track.duration);

seek_slider.value = seekPosition;

let currentMinutes = Math.floor(curr_track.currentTime / 60);

let currentSeconds = Math.floor(curr_track.currentTime – currentMinutes * 60);

let durationMinutes = Math.floor(curr_track.duration / 60);

let durationSeconds = Math.floor(curr_track.duration – durationMinutes * 60);

if (currentSeconds < 10) { currentSeconds = "0" + currentSeconds; }

if (durationSeconds < 10) { durationSeconds = "0" + durationSeconds; }if  
(currentMinutes < 10) { currentMinutes = "0" + currentMinutes; }

if (durationMinutes < 10) { durationMinutes = "0" + durationMinutes; }

curr_time.textContent = currentMinutes + ":" + currentSeconds;

total_duration.textContent = durationMinutes + ":" + durationSeconds;

}

}

Posted  
by[Dsmith](https://begininfiniteloop.wordpress.com/author/f4ultyc0d3/)[March  
30,  
2022](https://begininfiniteloop.wordpress.com/2022/03/30/musicplayr/)Posted  
in[js](https://begininfiniteloop.wordpress.com/category/js/)Tags:[js](https://begininfiniteloop.wordpress.com/tag/js/)[Leave  
a comment on  
Musicplayr](https://begininfiniteloop.wordpress.com/2022/03/30/musicplayr/#respond)

##

[javascript](https://begininfiniteloop.wordpress.com/2022/03/30/javascript/)

"""let now_playing = document.querySelector(".now-playing");

let track_art = document.querySelector(".track-art");

let track_name = document.querySelector(".track-name");

let track_artist = document.querySelector(".track-artist");

let playpause_btn = document.querySelector(".playpause-track");

let next_btn = document.querySelector(".next-track");

let prev_btn = document.querySelector(".prev-track");

let seek_slider = document.querySelector(".seek_slider");

let volume_slider = document.querySelector(".volume_slider");

let curr_time = document.querySelector(".current-time");

let total_duration = document.querySelector(".total-duration");

let track_index = 0;

let isPlaying = false;

let updateTimer;

let curr_track = document.createElement('audio');

let track_list = [

{

name: "Night Owl",

artist: "Broke For Free",

image: "Image URL",

path: "Night_Owl.mp3"

},

{

name: "Enthusiast",

artist: "Tours",

image: "Image URL",

path: "Enthusiast.mp3"

},

{

name: "Shipping Lanes",

artist: "Chad Crouch",

image: "Image URL",

path: "Shipping_Lanes.mp3",

},

];

function loadTrack(track_index) {

clearInterval(updateTimer);

resetValues();

curr_track.src = track_list[track_index].path;

curr_track.load();

track_art.style.backgroundImage =

"url (" + track_list[track_index].image + ")";

track_name.textContent = track_list[track_index].name;

track_artist.textContent = track_list[track_index].artist;

now_playing.textContent =

"PLAYING" + (track_index + 1) + " OF " + track_list.length;

updateTimer = setInterval(seekUpdate, 1000);

curr_track.addEventListener("ended", nextTrack);

random_bg_color();

}

function random_bg_color() {

let red = Math.floor(Math.random() * 256) + 64;

let green = Math.floor(Math.random() * 256) + 64;

let blue = Math.floor(Math.random() * 256) + 64;

let bgColor = "rgb(" + red + ", " + green + ", " + blue + ")";

document.body.style.background = bgColor;

}

function resetValues() {

curr_time.textContent = "00:00";

total_duration.textContent = "00:00";

seek_slider.value = 0;

}

function playpauseTrack() {

if (!isPlaying) playTrack();

else pauseTrack();

}

function playTrack() {

curr_track.play();

isPlaying = true;

playpause_btn.innerHTML = ' __';

}

function pauseTrack() {

curr_track.pause();

isPlaying = false;

playpause_btn.innerHTML = ' __';

}

function nextTrack() {

if (track_index < track_list.length – 1)

track_index += 1;

else track_index = 0;

loadTrack(track_index);

playTrack();

}

function prevTrack() {

if (track_index > 0)

track_index -= 1;

else track_index = track_list.length – 1;

loadTrack(track_index);

playTrack();

}

function seekTo() {

seekto = curr_track.duration * (seek_slider.value / 100);

curr_track.currentTime = seekto;

}

function setVolume() {

curr_track.volume = volume_slider.value / 100;

}

function seekUpdate() {

let seekPosition = 0;

if (!isNaN(curr_track.duration)) {

seekPosition = curr_track.currentTime * (100 / curr_track.duration);

seek_slider.value = seekPosition;

let currentMinutes = Math.floor(curr_track.currentTime / 60);

let currentSeconds = Math.floor(curr_track.currentTime – currentMinutes * 60);

let durationMinutes = Math.floor(curr_track.duration / 60);

let durationSeconds = Math.floor(curr_track.duration – durationMinutes * 60);

if (currentSeconds < 10) { currentSeconds = "0" + currentSeconds; }

if (durationSeconds < 10) { durationSeconds = "0" + durationSeconds; }

if (currentMinutes < 10) { currentMinutes = "0" + currentMinutes; }

if (durationMinutes < 10) { durationMinutes = "0" + durationMinutes; }

curr_time.textContent = currentMinutes + ":" + currentSeconds;

total_duration.textContent = durationMinutes + ":" + durationSeconds;

}

}

Posted  
by[Dsmith](https://begininfiniteloop.wordpress.com/author/f4ultyc0d3/)[March  
30,  
2022](https://begininfiniteloop.wordpress.com/2022/03/30/javascript/)Posted  
in[js](https://begininfiniteloop.wordpress.com/category/js/)Tags:[js](https://begininfiniteloop.wordpress.com/tag/js/)[Leave  
a comment on  
javascript](https://begininfiniteloop.wordpress.com/2022/03/30/javascript/#respond)

## [How To Build a Lyrics Website with Laravel Scout and Algolia –

SitePoint](https://begininfiniteloop.wordpress.com/2022/03/30/how-to-build-a-  
lyrics-website-with-laravel-scout-and-algolia-sitepoint/)

In this tutorial, we will create a minimal lyrics web site using Laravel Scout  
and [Algolia](http://algolia.com). To do so, we need a CRUD app to work with  
our data, and a search interface to let users search through the content.  
However, instead of creating the full app from scratch, let's just install the  
[finished CRUD](https://github.com/lavary/lyrics-crud) app that we've created  
for this tutorial.

Algolia is a hosted search engine API, providing us with all the tools and  
resources we'll ever need to create products with awesome search capabilities.

![Search stock vector image](https://uploads.sitepoint.com/wp-  
content/uploads/2015/05/1431991319300_Information_Search.jpg)Search stock  
vector image

By the end of the tutorial, we'll have a product like this:

![Lyrics_Website_With_Algolia_Scout](https://uploads.sitepoint.com/wp-  
content/uploads/2017/07/1499265533lyrics_search_interface-1024x458.png)Lyrics_Website_With_Algolia_Scout  
![Lyrics Details Page](https://uploads.sitepoint.com/wp-  
content/uploads/2017/07/1499265535lyrics_details_page-1024x510.png)Lyrics  
Details Page

## Bootstrapping the Application

I assume you already have your development environment up and running.  
However, If you need a good development environment to get into action right  
away, you should use [Homestead Improved](https://www.sitepoint.com/quick-tip-  
get-homestead-vagrant-vm-running/).

*Stranger to Vagrant? Read[this](https://www.sitepoint.com/re-introducing-  
vagrant-right-way-start-php/). Want to go more in depth? Buy our [book on PHP  
Environments!](http://bit.ly/phpenv-sp)*

Feel free to skip this part if you already have a similar application or you  
have enough experience to build one relatively quickly.

### CRUD Application

The most convenient way to download the pre-built CRUD project is to clone it:

    git clone git@github.com:lavary/lyrics-crud.git coolyrics
    cd coolyrics
    composer install
    
    
    
    ### Setting up the Database
    
    
    Now, let’s create a MySQL database. The settings below apply to the [Homestead Improved](https://www.sitepoint.com/quick-tip-get-homestead-vagrant-vm-running/) environment mentioned above. Change as needed.
    
    
    
    mysql -h localhost -u homestead -psecret
    mysql> CREATE DATABASE lyrics
    
    
    
    After the database has been created, we make a copy of .env.example (located in our project’s root directory) and name it .env. This is where we put our database credentials:
    
    
    
    #...
    
    DB_CONNECTION=mysql
    DB_HOST=127.0.0.1
    DB_PORT=3306
    DB_DATABASE=lyrics
    DB_USERNAME=root
    DB_PASSWORD=password
    
    # ...
    
    
    
    Again, apply to your own preferences as needed.
    
    
    Now, we run the migration command to create the tables:
    
    
    
    php artisan migrate
    
    
    
    ### Filling up the Database with Sample Data
    
    
    A lyrics website contains information about musicians and their work, and, of course, their songs’ lyrics. To make a bare minimum data structure, we have created only two Eloquent models for this project, namely Artist and Song. The Artist model has a one-to-many relationship with the the Song model. This means each artist can have many songs and each song belongs to an artist in our database.
    
    
    Before moving forward to the next section, you may go ahead and insert a few records into the database, starting with your favorite artists and then adding a few songs for each.
    
    
    This is what we have so far:
    
    
    ![Lyrics Songs list](https://uploads.sitepoint.com/wp-content/uploads/2017/07/1499265529lyrics_songs_list-1024x670.png)
    
    
    You can also use the [SQL](https://raw.githubusercontent.com/lavary/lyrics-crud/master/storage/app/lyrics.sql) file included with the project files and dump it into your database with the following command:
    
    
    
    mysql -h localhost -u {USERNAME} -p{PASSWORD} lyrics  < /path/to/the/sql/file
    
    
    
    _You can also import the file by using your favorite MySQL management application, like Sequel Pro, MySQL Workbench or PHPMyAdmin._
    
    
    ## Installing Scout
    
    
    Let’s continue by installing Scout:
    
    
    
    composer require laravel/scout
    
    
    
    Then, we add the service provider to $providers in the config/app.php file:
    
    
    
    Laravel\Scout\ScoutServiceProvider::class,
    
    
    
    Now we need to generate the Scout’s configuration file using the publish:config artisan command:
    
    
    
    php artisan vendor:publish --provider="Laravel\Scout\ScoutServiceProvider"
    
    
    
    As a result, a configuration file named scout.php is generated inside the config directory.  We’ll edit this file later.
    
    
    To make a data model searchable, we need to _use_  the Laravel\Scout\Searchable trait inside the respective model class. That’s the Song model in our case:
    
    
    
    <?php
    
    namespace App;
    
    use Illuminate\Database\Eloquent\Model;
    use Laravel\Scout\Searchable;
    
    class Song extends Model
    {
        use Searchable;
    
        protected $fillable = ['title', 'album', 'lyrics', 'youtube_link'];
    
        public function artist()
        {
            return $this->belongsTo('App\Artist');
        }
    }
    
    
    
    ## Setting up Algolia
    
    
    As planned, we’ll use [Algolia](http://algolia.com) as our search engine API. 
    
    
    First, let’s [create an account](https://www.algolia.com/users/sign_up) to obtain our _application ID_. Scout requires **Application ID** and **Admin API Key** to operate. After the registration is complete, we can find our credentials under **API Keys** in the left menu.
    
    
    ![Algolia API Keys](https://uploads.sitepoint.com/wp-content/uploads/2017/07/1499265553lyrics_algolia_api_keys-1024x417.png)
    
    
    Now, we open the config/scout.php configuration file and put our credentials there:
    
    
    
    <?php
    'algolia' => [
            'id' => env('ALGOLIA_APP_ID', ''),
            'secret' => env('ALGOLIA_SECRET', ''),
        ],
    
    
    
    It’s a good practice to keep the keys in .env  and load them into scout.php using the env() or getenv() functions.
    
    
    To use the Algolia’s API, we need to install Algolia’s SDK for PHP, which is also available as a Composer package:
    
    
    
    composer require algolia/algoliasearch-client-php
    
    
    
    ## Indexing Our Data
    
    
    At this point, we need to create our index on Algolia. Each record in the index is a schema-less JSON object (each one represents a record in our database) with a set of attributes that can be used for **searching, displaying, ranking and filtering** data.
    
    
    Rather than indexing the whole record, we only need to index the data needed for the above operations. This helps keep our index clean and optimized.
    
    
    Apart from that, the index is not a relational database, meaning when searching through the index, we cannot use complex where clauses or SQL joins. To work around this limitation, we should define a custom structure for our index records. On the other hand, we should join all the needed tables, preparing a customized JSON object before indexing.
    
    
    To do this, we override the toSearchableArray() method in the Song model (this method is added to the class by the Laravel\Scout\Searchable trait). By default, the toSearchableArray() method returns the $this->toArray() output as our index object (when sending the index record to Algolia), whereas we need additional data, like **artist’s name**, **genres** and the **image URL**, which reside in another table – the artists table.
    
    
    Here’s how we do it:
    
    
    
    <?php
    
    namespace App;
    
    use Illuminate\Database\Eloquent\Model;
    use Laravel\Scout\Searchable;
    
    class Song extends Model
    {
        use Searchable;
    
        protected $fillable = ['title', 'album', 'lyrics', 'youtube_link'];
    
        public function toSearchableArray()
        {
            $genres = array_map(function($item) {
                return trim($item);
            }, explode(',', $this->artist->genres));
    
            return array_merge( $this->toArray(), ['artist' => $this->artist->name, 'photo' => $this->artist->photo, 'genres' => $genres]);
        }
    
        public function artist()
        {
            return $this->belongsTo('App\Artist');
        }
    }
    
    
    
    Since the genres field may contain a comma-separated value in our database (it has a simple text field in our CRUD app), we separate genres using explode. Then, we iterate over the results, stripping off any unwanted spaces before and after each part – using the map() function:
    
    
    
    <?php
    
    
    $genres = array_map(function($item) {
                return trim($item);
            }, explode(',', $this->artist->genres));
    
    
    
    
    Finally, we merge the output of $this->toArray() with our desired attributes, returning the final array.
    
    
    
    <?php
    
    
    return array_merge( $this->toArray(), ['artist' => $this->artist->name, 'photo' => $this->artist->photo, 'genres' => $genres]);
    
    
    
    
    Why do we need to index a randomly generated string like image URL you may be wondering. We’ll get to this shortly.
    
    
    For the existing records in the database, we can import the index at once with the scout:import artisan command, like this:
    
    
    
    php artisan scout:import "App\Song"
    
    
    
    When the indexing process is completed, we can see the index on Algolia by going to **Indices** and choosing our index name from the drop-down menu:
    
    
    ![Algolia Index Dropdown](https://uploads.sitepoint.com/wp-content/uploads/2017/07/1499265543lyrics_algolia_index_select-1024x283.png)
    
    
    Indexing is not a one-off task. After the initial import, the index needs to be kept in sync with the database. Since we’re using Scout, everything is already taken care of. From now on, any time a record is inserted, updated, or deleted from the database, the respective index record will be affected accordingly – thanks to Laravel’s model observers.
    
    
    To learn more about how Scout manages the indexing process, have a look at the [documentation](https://laravel.com/docs/5.4/scout).
    
    
    ## Configuring Algolia
    
    
    The next thing to do is to configure our Algolia index for optimal operation. These settings can be modified either from the dashboard or programmatically using Algolia’s API.
    
    
    The most important configuration options are the _Searchable attributes_ and the _Custom Ranking Attributes_.
    
    
    The Searchable attributes setting defines which record attributes are used for searching. The order of these attributes also matters as those at the top are considered more important and **control** the ranking.
    
    
    ![Algolia Searchable Attributes](https://uploads.sitepoint.com/wp-content/uploads/2017/07/1499265539lyrics_algolia_searchable_attributes-1024x474.png)
    
    
    The Custom Ranking Attributes option indicates the popularity of each record which also affects the ranking. They can be anything from the number of likes, views, downloads, to comments. That said, we need to include this information in the index.
    
    
    ![Algolia Custom Ranking](https://uploads.sitepoint.com/wp-content/uploads/2017/07/1499265548lyrics_algolia_custom_ranking-1024x169.png)
    
    
    Algolia comes with plenty of configuration options. Going through each setting is beyond the scope of this tutorial. To learn more about the configuration options, you should have a look at [Algolia’s FAQ](https://www.algolia.com/doc/faq/index-configuration/) on configuration and relevance.
    
    
    ## The Website
    
    
    The last thing to do is to implement the search interface within our lyrics website. The good thing about Algolia is that it doesn’t restrict us to any interface implementation. 
    
    
    Traditional search implementations tend to have the search logic on the backend. To achieve this, we can use Eloquent to search through the records, using the search() method (provided by the Searchable trait). This method is a bit slower as the search request goes through different levels of abstraction. It can be done like this:
    
    
    
    <?php
    
    use Illuminate\Http\Request;
    
    Route::get('/search', function (Request $request) {
        return App\Song::search($request->search)->get();
    });
    
    
    
    
    The other way is to directly issue the search requests from the user’s browser to Algolia’s search API, providing a find-as-you-type experience for our users. This method is much faster than the former as there’s no interface involved. This means **every attribute** we want in our search results **should be present** in the index itself. 
    
    
    In this tutorial, we’ll take the second approach. We use Scout for indexing and keeping our index synced with our database, then we use Algolia’s API to do the searching.
    
    
    By taking the second approach, we will have many options to display the results. We can use AngularJS, Vue.js, or Algolia’s two popular libraries, namely [Autocomplete](https://www.algolia.com/doc/guides/search/auto-complete/) and [Instantsearch.js](https://community.algolia.com/instantsearch.js/).
    
    
    For this project, we’ll use Instantsearch.js, which is a library of UI widgets based on React that makes creating search interfaces a breeze.
    
    
    Our lyrics website consists of two pages, the main searching page, and a single page to display the details of a song.
    
    
    First, let’s create the routes and the controllers for these two pages. Then we’ll create the views.
    
    
    **File:** routes/web.php
    
    
    
    <?php
    
    
    Route::get('/',          'LyricsController@search');
    Route::get('song/{id}',  'LyricsController@lyric');
    
    
    
    
    And the controller:
    
    
    
    php artisan make:controller LyricsController
    
    
    
    **File:** app/Http/Controllers/LyricsController.php
    
    
    
    <?php
    
    namespace App\Http\Controllers;
    
    use Illuminate\Http\Request;
    use App\Song;
    
    class LyricsController extends Controller
    {
        public function search()
        {
            return view('search');
        }
    
        public function song(Request $request, $id)
        {
            $song = Song::find($id);
    
            return view('lyrics', compact('song'));
        }
    }
    
    
    
    The song() and search() methods render our website pages.
    
    
    First, let’s create a master layout template for our pages. Inside resources/views/layouts, create a file named basic.blade.php with the following content:
    
    
    **File:** resources/views/layouts/basic.blade.php
    
    
    
    <!DOCTYPE html>
    <html lang="{{ config('app.locale') }}">
    <head>
        <meta charset="utf-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <meta name="viewport" content="width=device-width, initial-scale=1">
    
        <title>{{ config('app.name', 'Coolyrics') }}</title>
    
        <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css" integrity="sha384-BVYiiSIFeK1dGmJRAkycuHAHRg32OmUcww7on3RYdg4Va+PmSTsz/K68vbdEjh4u" crossorigin="anonymous">
    
        <link rel="stylesheet" type="text/css" href="{{ asset('css/styles.css') }}">
    
    </head>
    <body>
    
    @yield('content')
    
    @section('javascript')
    @show
    
    </body>
    </html>
    
    
    
    Having individual Blade sections for the CSS and JavaScript files allows us to have better control over global and page-specific assets as well as internal Javascript code for child templates.
    
    
    There’s also a CSS file loaded into the page – to make the website a little bit more customized. Please feel free to change the styles if you don’t like the look and feel of it. 
    
    
    For the time being, let’s create a file named styles.css under public/css with the following content:
    
    
    **File:** public/css/styles.css
    
    
    
    html, body {
      height: 100%;
    }
    
    h2 {
      color: #888;
      font-size: 30pt;
    }
    
    #header {
      background: #34495e;
      color: #f1c40f;
      height: 80px;
    }
    
    #header .input-group {
      margin-top: 20px;
    }
    
    #header h1 { 
      margin-left: 50px;
      font-size: 20pt;
      font-weight: bold;
    }
    
    #header h1 sup {
      font-size: 8pt;
      font-weight: normal;
      display: inline-block;
    }
    
    .dropdown-menu .ais-menu {
      padding: 5px 5px;
    }
    
    .dropdown-menu .ais-menu--item {
      border-bottom: #ccc 1px dotted;
      padding: 5px 25px 5px 15px;
    }
    
    .dropdown-menu .ais-menu--item:last-child {
      border: 0;
    }
    
    .container {
      padding: 35px;
    }
    
    .container-fluid {
      padding: 40px;
    }
    
    #hits-container {
    }
    
    .ais-hits__empty {
      height: 100%;
      font-size: 15pt;
      font-weight: bold;
      color: #888;
    }
    
    .ais-hits__empty p {
      font-size: 12pt;
      font-weight: normal;
      color: #999;
      padding-top: 5px;
    }
    
    .song {
      border-bottom: #ccc 1px dotted;
      padding: 20px;
    }
    
    .song a.song-link {
      color: #000;
      font-size: 15pt;
      display: block;
    }
    
    .song a.song-link em {
      font-style: normal;
      color: #000;
      font-weight: bold;
    }
    
    .song span {
      color: #888;
      display: block;
    }
    
    .song span.song-artist {
      margin: 3px 0;
    }
    
    .song-youtube-link {
      margin-top: 10px;
    }
    
    #pagination-container {
      text-align: center;
      font-size: 11pt;
      margin: 20px 0;
    }
    
    #login-link {
      font-weight: bold;
      text-transform: uppercase;
      line-height: 80px;
    }
    
    #login-link a {
      color: #fff;  
    }
    
    .band-thumbnail { 
      width: 90px;
      height: 90px;
      background-position: center;
      background-size: cover;
      margin-right: 30px;
      border-radius: 3px;
    }
    
    #lyrics-container {
    
    }
    
    #lyrics-container p {
      font-size: 13pt ;
    } 
    
    h1 { font-size: 30pt;  }
    
    #lyrics-container h1 span {
      color: #000;
    }
    
    #lyrics-header {
      background: #f5f5f5;
      padding: 60px 0;
    }
    
    #lyrics-album-details {
      font-size: 11pt;
      font-weight: normal;
      display: block;
      color: #888;
      margin-bottom: 20px;
    }
    
    #lyrics-album-details .glyphicon {
      color: #ccc;
      margin-right: 5px;
    }
    
    #lyrics-youtube-link {
      position: absolute;
      left: 0; bottom: 0;
      background: #cc181e;
      width: 100%;
      height: 30px;
      line-height: 30px;
    }
    
    #lyrics-youtube-link a {
      color: #fff;
    }
    
    #lyrics-thumbnail {
      position: relative;
      width: 370px;
      height: 220px;
      margin: 0 auto;
    }
    
    #post-meta {
      margin: 15px 0;
    }
    
    #post-meta span {
      color: #ccc;
      font-size: 10pt;
      font-weight: normal;
      margin: 5px 0;
    }
    
    #lyrics-content {
      background-color: #f1f1f1;
      padding: 40px 0;
    }
    
    .btn-xs .glyphicon {
      color: #888;
      font-size: 8pt;
    }
    
    
    
    ### The Lyrics Page
    
    
    Now, we create a file named song.blade.php inside resources/views with the following content:
    
    
    **File:** resources/views/song.blade.php
    
    
    
    @extends('layouts.basic')
    
    <div id="lyrics-container" class="text-center">  
        <div id="lyrics-header">
            <h1>{{$song->title}}</h1>
            <span id="lyrics-album-details">
                {{$song->artist->name}} - {{$song->album}} Album
            </span>  
            <div id="lyrics-thumbnail">
                <img src="{{Storage::url('artists/' . $song->artist->photo)}}">
                <div id="lyrics-youtube-link">
                    <a href="{{$song->youtube_link}}"><i class="glyphicon glyphicon-play"></i> Watch on Youtube</a>
                </div>
            </div>
        </div>
        <div id="lyrics-content">
            <p><strong>"{{$song->title}}"</strong></p>
            <p>{!! nl2br($song->lyrics) !!}</p>
        </div>
    </div> 
    
    
    
    This page is rendered and controlled in the backend – by Laravel. 
    
    
    In this template, we extend the layout and echo out the lyrics’ attributes. This is how it should look:
    
    
    ![Lyrics Details Page](https://uploads.sitepoint.com/wp-content/uploads/2017/07/1499265535lyrics_details_page-1024x510.png)
    
    
    ### The Search Interface
    
    
    Now we get to the main part for which we’ve created everything so far, the search interface. 
    
    
    To create the search interface, we need to combine several widgets of Instantsearch.js and configure each widget to fit our needs.
    
    
    Our search interface will consist of three widgets:
    
    
      * A search field (**SearchBox** widget)
    
      * A section to display the results (**Hits** widget)
    
      * Pagination (**Pagination** widget)
    
    
    All the widgets are wired together out of the box and require no extra development on our side. That is to say, whenever a user enters a value into the search box, all the widgets (search box, hits, pagination, etc.) will respond accordingly.
    
    
    Create a new file named search.blade.php inside the resources/views directory with the following content:
    
    
    **File:** resources/views/search.blade.php
    
    
    
    @extends('layouts.basic')
    
    @section('content')
    
    <div id="header">
        <div class="col-md-2"><h1>Coolyrics</h1></div>
        <div class="col-md-6">
    
              <div id="search-box"></div> 
    
        </div>
    </div>
    
    <div class="container-fluid">
        <div id="hits-container"></div>
        <div id="pagination-container"></div>
    </div>
    
    @endsection
    
    @section('scripts')  
    @parent    
    <https://cdn.jsdelivr.net/jquery/3.1.1/jquery.min.js>
    <https://cdn.jsdelivr.net/instantsearch.js/1/instantsearch.min.js>
    @endsection 
    
    @section('javascript')
    @endsection
    
    
    
    In the content section, we have a container with id search-box where we’re going to place our searchBox widget. We also have containers for hits and pagination widgets.
    
    
    In the scripts section, first, we load the master layout’s scripts using the @parent directive. Then, we add the scripts specific to this template, namely jQuery and Instantsearch.js.
    
    
    We also have a section (javascript) for our template’s internal Javascript code. This is where we instantiate Instantsearch.js and add our widgets.
    
    
    ### Setting up InstantSearch.Js
    
    
    We can use Bower or NPM to install Instantsearch.js, or simply use the CDN like so:
    
    
    **File:** resources/views/search.blade.php
    
    
    
    @section('css')
    <link rel="stylesheet" type="text/css" href="https://cdn.jsdelivr.net/instantsearch.js/1/instantsearch.min.css" />
    @endsection
    
    
    
    And the Javascript file:
    
    
    **File:** resources/views/search.blade.php
    
    
    
    @section('scripts')
    @parent    
    <https://cdn.jsdelivr.net/jquery/3.1.1/jquery.min.js>
    <https://cdn.jsdelivr.net/instantsearch.js/1/instantsearch.min.js>
    @endsection
    
    
    
    ### Initialization
    
    
    Now, we need to create a search object with our given Application Id and API Key. In the resources/views/search.blade.php file, add the following JavaScript code inside the javascript section.
    
    
    **File:** resources/views/search.blade.php
    
    
    
    ...
    
    section('javascript')
    var search = instantsearch({
    
        appId: 'XXXX',
        apiKey: 'XXX',
        indexName: 'songs'
      });
    @endsection
    
    ...
    
    
    
    In the above code, we need to provide three values to instantiate the search object: appId, ApiKey, and indexName.
    
    
    Since we’re doing the initialization in a Javascript environment, the keys are visible to everyone. Knowing this, we **must** use our **Search-Only API Key**, which is limited to search operations only. You can find it under **API Keys** in your Algolia profile.
    
    
    The indexName attribute is the name of the index we want to search through, which is songs in our case.
    
    
    ### Adding the Search Box
    
    
    The searchBox widget creates a smart text field to enter the search keyword.
    
    
    To add the widget, we call the addWidget method on the search object (that we just created), passing an instance of searchBox to it:
    
    
    **File:** resources/views/search.blade.php
    
    
    
    ...
    
    search.addWidget(
        instantsearch.widgets.searchBox({
          container: '#search-box',
          placeholder: 'Search by artist, song, or lyrics',
          wrapInput: false,
          cssClasses: {
            input: 'form-control'
          }
        })
      );
    
    @endsection
    
    ...
    
    
    
    As you can see in the above code, we pass a configuration object when instantiating a widget. This object is used to adjust the widget’s behavior. 
    
    
    The container is the place where our searchBox widget sits. The placeholder is an ordinary HTML placeholder for the text field.   
    
    
    If wrapInput is set to true, the text field itself is wrapped by another <div> element with a class named ais-search-box. 
    
    
    Finally, the cssClasses option specifies the additional classes to be added to the widget. In the above settings, we just add a class to the text field itself. We can add classes to the wrapping element as well.
    
    
    To learn about the other available options for searchBox, you should have a look at the [documentation](https://community.algolia.com/instantsearch.js/documentation/#searchbox).
    
    
    ### Adding the Hits Widget
    
    
    The hits widget displays the search results based on a set of defined templates.
    
    
    Add the following code right after the code for searchBox:
    
    
    **File:** resources/views/search.blade.php
    
    
    
    ...
    
    search.addWidget(
        instantsearch.widgets.hits({
          container: '#hits-container',
          templates: {
            item: $('#hits-temp').html(),
            empty: 'No lyrics was found! <p>We will be adding more lyrics to the database.</p>',
            header: '<h2>Lyrics</h2>'
          }
        })
     );
    
    @endsection
    
    ...
    
    
    
    Again, we have an object of settings to adjust the widget’s behavior. The templates option defines the templates used for rendering different parts of the hits (results) section. In the above code, we define a template for _item_, which is rendered for each item in the result set. We also define a template for any time the search has no results. There’s also another template for the hits _header_ section. 
    
    
    These templates can be either a [Mustache template](https://github.com/janl/mustache.js/) or just a string, returned by an anonymous Javascript function.
    
    
    In our case, the item template is a mustache template stored within a <script> tag, which we fetch with jQuery: 
    
    
    
    // ...
    item: $('#hits-temp').html(),
    // ...
    
    
    
    This is our Mustache template. You can place it any where in the search.blade.php template:
    
    
    **File:** resources/views/search.blade.php
    
    
    
    <script type="text/javascript" id="hits-temp">
    
        <div class="row song">
            <div class="pull-left band-thumbnail" style="background-image: url(/storage/artists/@{{photo}});"></div> 
            <a class="song-link" href="song/@{{objectID}}">@{{{_highlightResult.title.value}}}</a>
            <span class="song-artist">- <a href="?q=@{{artist}}&hPP=20&idx=songs&p=0&is_v=1">@{{artist}}</a> (@{{album}})</span>
            <span class="song-youtube-link"><a href="@{{youtube_link}}" class="btn btn-default btn-xs"><i class="glyphicon glyphicon-play"></i> Watch on Youtube</a></span>
        </div>
    
    </script>
    
    
    
    In this template, we have access to the attributes of each row within the index, like objectID, artist, title, photo, youtube_link, etc.
    
    
    To prevent Blade from rendering mustache directives, we put a @ before each curly brace set, letting Blade know that this expression should be remained untouched and is handled by Instantsearch.js later on.
    
    
    Additionally, Algolia provides an object for each item called _highlightResult. This object contains highlighted text for each attribute based on the search keyword. This is useful to show which part of the results are matched by the searched keyword.
    
    
    
    <a class="song-link" href="song/@{{objectID}}">@{{{_highlightResult.title.value}}}</a>
    
    
    
    Please note that we link each item to its details page.
    
    
    ### Adding Pagination
    
    
    The pagination widget generates the pagination links:
    
    
    **File:** resources/views/search.blade.php
    
    
    
    ...
    
    search.addWidget(
        instantsearch.widgets.pagination({
          container: '#pagination-container'
        })
      );
    
    ...
    
    
    
    To see all the available options for this widget, you should have a look at the [documentation](https://community.algolia.com/instantsearch.js/documentation/#pagination).
    
    
    Finally, we start the search object:
    
    
    **File:** resources/views/search.blade.php
    
    
    
    // ...
    
     search.start();
    
    // ...
    
    
    
    The full code should look like this now:
    
    
    **File:** resources/views/search.blade.php
    
    
    
    @extends('layouts.basic')
    
    @section('content')
    
    <div id="header">
        <div class="col-md-2"><h1>Coolyrics</h1></div>
        <div class="col-md-6">
    
              <div class="input-group" id="search-box">
                 <div class="input-group-btn">
                  <button type="button" class="btn btn-default dropdown-toggle" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
                  <span>Genre</span>
                  <span class="caret"></span></button>
                  <ul id="genres" class="dropdown-menu">
    
                  </ul>
                </div>
              </div>          
        </div>
        <div  id="login-link" class="col-md-4 text-right">
                <a href="{{route('login')}}">Login</a>
        </div>
    </div>
    
    <div class="container-fluid">
        <div id="hits-container"></div>
        <div id="pagination-container"></div>
    </div>
    
    @endsection
    
    @section('scripts')
    
    @parent    
    <https://cdn.jsdelivr.net/jquery/3.1.1/jquery.min.js>
    <https://cdn.jsdelivr.net/instantsearch.js/1/instantsearch.min.js>
    @endsection
    
    @section('javascript')
    
    <script type="text/javascript" id="hits-temp">
    
        <div class="row song">
            <div class="pull-left band-thumbnail" style="background-image: url(/storage/artists/@{{photo}});"></div> 
            <a class="song-link" href="song/@{{objectID}}">@{{{_highlightResult.title.value}}}</a>
            <span class="song-artist">- <a href="?q=@{{artist}}&hPP=20&idx=songs&p=0&is_v=1">@{{artist}}</a> (@{{album}})</span>
            <span class="song-youtube-link"><a href="@{{youtube_link}}" class="btn btn-default btn-xs"><i class="glyphicon glyphicon-play"></i> Watch on Youtube</a></span>
        </div>
    
    </script>
    
    <span></span>
    
    <script>
      var search = instantsearch({
        appId: 'XI8PV16IK6',
        apiKey: '63c96991d445cb2de4fff316ac909c1a',
        indexName: 'songs',
        urlSync: true
      });
    
      search.addWidget(
        instantsearch.widgets.searchBox({
          container: '#search-box',
          placeholder: 'Search by artist, song, or lyrics',
          wrapInput: false,
          cssClasses: {
            input: 'form-control'
          }
        })
      );
    
      search.addWidget(
        instantsearch.widgets.hits({
          container: '#hits-container',
          templates: {
            item: $('#hits-temp').html(),
            empty: 'No lyrics was found! <p>We will be adding more lyrics to the database.</p>',
            header: '<h2>Lyrics</h2>'
          }
        })
      );
    
      search.addWidget(
        instantsearch.widgets.hits({
          container: '#hits-container',
          templates: {
            item: $('#hits-temp').html(),
            empty: 'No lyrics was found! <p>We will be adding more lyrics to the database.</p>',
            header: '<h2>Lyrics</h2>'
          }
        })
      );
    
      search.addWidget(
        instantsearch.widgets.menu({
          container: '#genres',
          attributeName: 'genres',
          limit: 10,
          templates: {
              header: '',
              footer: '',
              item: '<li><a href="@{{url}}">@{{name}}</></li>'
          }
        })
      );
    
      search.addWidget(
        instantsearch.widgets.pagination({
          container: '#pagination-container'
        })
      );
    
      search.start();
    </script>
    
    @endsection
    
    
    
    Now, if we reload the page, we should see an awesome search interface which works right out of the box. No extra coding, no hassle. 
    
    
    ![Lyrics Search interface](https://uploads.sitepoint.com/wp-content/uploads/2017/07/1499265533lyrics_search_interface-1024x458.png)
    
    
    Feel free to play with the interface. Search for different terms and open the links to see how it looks. You can also make some typos on purpose while searching, to see the response. Algolia’s typo tolerance algorithms will automatically detect what your users are searching for and return the correct results.
    
    
    Alright, I think that does it to get started with Scout and Algolia. You can find the full code on [Github](https://github.com/lavary/coolyrics) in case you want to try it for yourself. 
    
    
    To see a working demo of what we built in this tutorial click [here](http://174.138.58.5).
    
    
    ## Wrapping Up
    
    
    We created our minimal lyrics website with the help of Laravel Scout and Algolia. 
    
    
    Please note that this project was just for educational purposes, implemented in the most basic form possible, and hence should not be used in a production environment. Please feel free to modify the code in any way you want.
    
    
    To move even further, you may go to your Algolia profile, and change the settings and see the results. You can also add synonyms for each term, in case you don’t have that term in your database.
    
    
    If you have any questions on the topic or if we’ve missed anything, let us know in the comments below!
    

* * *

Posted  
by[Dsmith](https://begininfiniteloop.wordpress.com/author/f4ultyc0d3/)[March  
30, 2022](https://begininfiniteloop.wordpress.com/2022/03/30/how-to-build-a-  
lyrics-website-with-laravel-scout-and-algolia-sitepoint/)Posted  
in[lyrics](https://begininfiniteloop.wordpress.com/category/lyrics/)Tags:[js](https://begininfiniteloop.wordpress.com/tag/js/)[Leave  
a comment on How to Build a Lyrics Website with Laravel Scout and Algolia –  
SitePoint](https://begininfiniteloop.wordpress.com/2022/03/30/how-to-build-a-  
lyrics-website-with-laravel-scout-and-algolia-sitepoint/#respond)

## Posts Navigation

1 [2](https://begininfiniteloop.wordpress.com/page/2/)  
[3](https://begininfiniteloop.wordpress.com/page/3/) [Older posts  
](https://begininfiniteloop.wordpress.com/page/2/)

[Runtime-Error](https://begininfiniteloop.wordpress.com/), [Website Built with  
WordPress.com](https://wordpress.com/?ref=footer_custom_com).

Privacy & Cookies: This site uses cookies. By continuing to use this website,  
you agree to their use.  
To find out more, including how to control cookies, see here: [ Cookie Policy  
](https://automattic.com/cookies/)

  * [ Follow ]() [ Following ]()

	* [ ![](https://begininfiniteloop.files.wordpress.com/2022/03/image-1.jpg?w=50) Runtime-Error ](https://begininfiniteloop.wordpress.com)

Sign me up

    * Already have a WordPress.com account? [Log in now.](https://wordpress.com/log-in?redirect_to=https%3A%2F%2Fbegininfiniteloop.wordpress.com%2F2022%2F08%2F20%2Finternal-error%2F&signup_flow=account)

  *     * [ ![](https://begininfiniteloop.files.wordpress.com/2022/03/image-1.jpg?w=50) Runtime-Error ](https://begininfiniteloop.wordpress.com)

	* [ Customize ](https://begininfiniteloop.wordpress.com/wp-admin/customize.php?url=https%3A%2F%2Fbegininfiniteloop.wordpress.com%2F)

	* [ Follow ]() [ Following ]()

	* [Sign up](https://wordpress.com/start/)

	* [Log in](https://wordpress.com/log-in?redirect_to=https%3A%2F%2Fbegininfiniteloop.wordpress.com%2F2022%2F08%2F20%2Finternal-error%2F&signup_flow=account)

	* [ Report this content ](http://en.wordpress.com/abuse/?report_url=https://begininfiniteloop.wordpress.com)

	* [ View site in Reader ](https://wordpress.com/read/feeds/128693110)

	* [Manage subscriptions](https://subscribe.wordpress.com/)

	* [Collapse this bar]()

##


##

Loading Comments...

Write a Comment...

Email (Required) Name (Required) Website

###

![](https://pixel.wp.com/b.gif?v=noscript)

Design a site like this with WordPress.com

[Get  
started](https://wordpress.com/start/?ref=marketing_bar)[](https://wordpress.com/start/?ref=marketing_bar)
