# Resilience-Engineering-Resources
This is a collection of readings, talks, and other bits regarding the field of Resilience Engineering
[Prologue: Resilience Engineering Concepts](http://erikhollnagel.com/onewebmedia/Prologue.pdf)

> **Hindsight and Safety**

> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Efforts to improve the safety of systems have often – some might say
> always – been dominated by hindsight. This is so both in research and
> in practice, perhaps more surprising in the former than in the latter.
> The practical concern for safety is usually driven by events that have
> happened, either in one’s own company or in the industry as such.
> There is a natural motivation to prevent such events from happening
> again, in concrete cases because they may incur severe losses – of
> equipment and/or of life – and in general cases because they may lead
> to new demands for safety from regulatory bodies, such as national and
> international administrations and agencies. New demands are invariably
> seen as translating into increased costs for companies and are for that
> reason alone undesirable. (This is, however, not an inevitable
> consequence, especially if the company takes a longer time perspective.
> Indeed, for some businesses it makes sense to invest proactively in
> safety, although cases of that are uncommon. The reason for this is that
> sacrificing decisions usually are considered over a short time horizon, in
> terms of months rather than years or in terms of years rather than
> decades.)



[Epilogue: Resilience Engineering Precepts](https://www.researchgate.net/publication/265074845_Epilogue_Resilience_Engineering_Precepts)

**Safety is Not a System Property** 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;One  of  the  recurrent  themes  of  this  book  is  that  safety  is  something  a  system  or  an  organisation  does,  rather  than  something  a  system  or  an  organisation has.  In  other  words,  it  is  not  a  system  property  that,  once  having been put in place, will remain. It is rather a characteristic of how a system performs. This creates the dilemma that safety is shown more by  the  absence  of  certain  events  –  namely  accidents  –  than  by  the  presence  of  something.  Indeed,  the  occurrence  of  an  unwanted  event  need not mean that safety as such has failed, but could equally well be due to the fact that safety is never complete or absolute. 
	
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;In consequence of this, resilience engineering abandons the search for safety as a property, whether defined through adherence to standard rules,  in  error  taxonomies,  or  in  ‘human  error’  counts.  By  doing  so  it  acknowledges  the  danger  of  the  reification  fallacy,  i.e.,  the  tendency  to  convert  a  complex  process  or  abstract  concept  into  a  single  entity  or  thing  in  itself  (Gould,  1981,  p.  24).  Seeing  resilience  as  a  quality  of  functioning has two important consequences.

* We  can  only  measure  the  potential  for  resilience  but  not  resilience  itself.  Safety  has  often  been  expressed  by  means  of  reliability,  measured  as  the  probability  that  a  given  function  or  component  would fail under specific circumstances. It is, however, not enough that systems are reliable and that the probability of failure is below a certain value (cf. Chapter 16); they must also be resilient and have the  ability  to  recover  from  irregular  variations,  disruptions  and  degradation of expected working conditions.
* Resilience   cannot   be   engineered   simply   by   introducing   more   procedures, safeguards, and barriers. Resilience engineering instead requires  a  continuous  monitoring  of  system  performance,  of  how  things  are  done.  In  this  respect  resilience  is  tantamount  to  coping  with  complexity  (Hollnagel  &  Woods,  2005),  and  to  the  ability  to  retain control. 

[Essential Characteristics of Resilience](https://www.researchgate.net/publication/284328979_Essential_characteristics_of_resilience) 

**Avoiding the Error of the Third Kind**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;When  one  uses  the  label  ‘resilience,’  the  first  reaction  is  to  think  of  resilience as if it were adaptability, i.e., as the ability to absorb or adapt to  disturbance,  disruption  and  change.  But  all  systems  adapt  (though  sometimes these processes can be quite slow and difficult to discern) so resilience cannot simply be the adaptive capacity of a system. I want to reserve  resilience  to  refer  to  the  broader  capability  –  how  well  can  a  system  handle  disruptions  and  variations  that  fall  outside  of  the  base  mechanisms/model for being adaptive as defined in that system.  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;This depends on a distinction between understanding how a system is  competent  at  designed-for-uncertainties,  which  defines  a  ‘textbook’  performance  envelope  and  how  a  system  recognizes  when  situations  challenge  or  fall  outside  that  envelope  –  unanticipated  variability  or  perturbations (see parallel analyses in Woods et al., 1990 and Carlson & Doyle,  2000;  Csete  &  Doyle,  2002).Most  discussions  of  definitions  of  ‘robustness’ in adaptive systems debate whether resilience refers to first or second order adaptability (Jen, 2003). In the end, the debates tend to settle  on  emphasizing  the  system’s  ability  to  handle  events  that  fall  outside its design envelope and debate what is a design envelope, what events  challenge  or  fall  outside  that  envelope,  and  how  does  a  system  see   what   it   has   failed   to   build   into   its   design   (e.g.,   see   url:   http://discuss.santafe.edu/robustness/)  


[Incidents - markers of resilience or brittleness?](https://www.researchgate.net/publication/292504952_Incidents_-_markers_of_resilience_or_brittleness)

**Incidents are ambiguous**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The  adaptive  capacity  of  any  system  is  usually  assessed  by  observing  how  it  responds  to  disruptions  or  challenges.  Adaptive  capacity  has  limits  or  boundary  conditions,  and  disruptions  provide  information  about  where  those  boundaries  lie  and  how  the  system  behaves  when  events push it near or over those boundaries. Resilience in particular is concerned with understanding how well the system adapts and to what range  or  sources  of  variation  it  adapts  in  order  to  detect  undesirable  drops  in  adaptive  capacity  and  to  intervene  to  increase  aspects  of  adaptive capacity. 



[Distancing through differencing: An obstacle to organizational learning following accidents](https://www.researchgate.net/publication/292504703_Distancing_through_differencing_An_obstacle_to_organizational_learning_following_accidents)
 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;A critical component of a high resilience in organizations is continuous learning from events, ‘near miss’ incidents, and accidents (Weick et al., 1999;  Ringstad  &  Szameitat,  2000).  As  illustrated  by  the  many  cases  referenced  in  this  book,  incidents  and  failures  provide  information  about  the  resilience  or  brittleness  of  the  system  in  the  face  of  various  disruptions.  This  chapter  explores  some  of  the  barriers  that  can  limit  learning even by generally very high quality organizations.   


[Rule- and role retreat: An empirical study of procedures and resilience](https://www.researchgate.net/publication/50917226_Rule-_and_role_retreat_An_empirical_study_of_procedures_and_resilience)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;To manage complex and dynamic socio-technical systems places demands on teams to deal with a range of more and less foreseeable situations. Three groups of participants with different maritime experiences were studied using the same simulation of a ship to better understand the role of generic competencies (e.g. information management, communication and coordination, decision making, and effect control) play in such high-demand situations. Groups with moderate maritime experience were able to balance contextual knowledge with use of generic competencies to successfully manage unexpected and escalating situations. Novices, lacking contextual knowledge, performed less well. Groups with the most maritime expertise remained committed to presumed procedures and roles and did not perform as well as the other two groups. The results suggest that training to operate complex sociotechnical systems safely and effectively should go beyond procedures and include development of generic competencies. This could provide operators with better tools to enhance organizational resilience in unexpected and escalating situations. 


[Team Coordination in Escalating Situations: An Empirical Study Using Mid-Fidelity
Simulation](http://portal.research.lu.se/ws/files/1376441/3014838.pdf)


&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The performance of teams, with different levels of domain- and crisis management experience, managing unexpected and escalating situations was observed by using a mid-fidelity ship-bridge simulation and analysed by applying the central concepts of joint activity coordination (Klein et al., 2005) as well as Woods’ (2002) theory building on data overload. The coordination strategies used by the teams were evaluated by applying coordination process indicators and the concept of control. The paper discusses how different aspects of team coordination in unexpected and escalating situations, e.g. that teams that maintain a high level of control in escalating situations avoid or minimise the effects of data overload by using explicit and agreed-upon goals rather than sharing as much incoming information as possible. The results presented in this paper shows the
benefits of applying a broad set of theoretical concepts to illuminate the actual demands that escalating situations pose on people's data processing capacities and processes. It also provides guidance on successful performance of teams in such situations and thus support for development of successful strategies for management of them.

[Resilience and the Ability to Anticipate](https://www.researchgate.net/profile/David_Woods11/publication/285487326_Resilience_and_the_ability_to_anticipate/links/5742fb8308ae9ace8418b7f8/Resilience-and-the-ability-to-anticipate.pdf)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The topics   of   anticipation   and   adaptation   run   throughout discussions  of  resilience.  Across  scales, to  be  resilient,  a  system looks  ahead  to  read  the  signs  that  its  adaptive  capacity,  as it currently  is  configured  and  performs,  is  becoming    inadequate  to meet the demands it will or could encounter in the future.  Missing or  discounting  the  signs  that  adaptive  capacity  is  degrading  in  the face of changing demands leaves that system vulnerable to sudden collapse or failures. This chapter synthesizes several patterns about how resilient systems possess the ability to anticipate.
