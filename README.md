# CVLearning
This repository use  for Mike-Liao123 CVLearning
python


ZTE Converged Message Architecture Solution
Should we start?ok,let's start,so thank you everybody,my name is Mike,Cloud Core Network Solution manager from ZTE.

Today in my session,I will introduce ZTE converged message architecture solution,just tell you ZTE how to slove the limitation of the traditional messaging platform,if you allow ,let's continue,if you has any question,pls let me know,ok,so

Let's move to the agenda today,it was devided into three parts,the first part,we will take overview on industry trends,there are two kinds of trends,one trend is user consumption behavior changed,the other is cloud technologies popular use in telecom industry,since having such kinds of trends,how to catch up?so the main part is the second part,zte will give converged message architecture solution to our customers,and at last,we will take a glance of zte successful implementation experience in global of the world.

Ok,so let's have a look,the developing trends of sms/mms and wechat service in China,as we can see from the left table and left influence curves,from 2012 to 2017, the quantities of short message is decreased from 900 billion pcs to 664 billion pcs,it decrease 26%,and especially E2E SMS rapidly decrease from 500 billion pcs to 190 billion pcs,it decline more than 60%,this competetion directly come from the OTT message service,and the same as MMS service, it decrease nearly 25%.
meanwhile,in the right part and influence curve,the active users of Wechat per month, it is booming from 360 million active users to 963 million active users  in last 4 years,it is nearly triple,so we can know see, the user behavior in China has been changed.

Meanwhile,take the whole world in view,with the large popular using of smart phone and mobile internet,a lot of applications run on smart phones,for example,basic social commmunication tools can run on it ,such as linkedin and facebook,linkedin handles trillion messages per day and facebook generates at least 600TB datas in daily,it's huge.And also some other applications like amusement,video,game,mobile payment and LBS service are used in every day,so users consumption behavior are already enchanced.

This is the first main point(Okay,This brings us to the end of the first main point),the second main point is cloud technologies polpular used in the telecom industry,telecom infrastructure needs evolution, 
for example,carrier-grade COTS server used the telecom industry,it can decrease Capex with large capacity deployment, and secondly,the hardware and software can be decoupled,which let operators have more selections of procurement.and thirdly,the cloud architecture can make network more agile and more flexible,and also,cloud technoloies can deploy new applications to shorten time to market,so in this way it can reduce/cut over the TCO and  bring more revenue for operators.

Ok,so compared with the upper advantages,the traditional operators are facing such kinds of challenges.Challenge 1, The traditional sms/voice service revenue are declining,this point we already can learned from upper slide.Challenge 2,since exiting network is designed by the traditional chimney style ,it is difficult to expand and hard to deploy new services,we need to break it.Challenge 3, high opex,in traditinal, the maintenance is a regionally sporadic work,that means different network elements need different maintenance,it leads to high opex,this situation must be changed.Challenge 4,High capex and long time to market,according to our engineering experience,in the legacy network,the period of deploying new service needs nearly 40 working days,it is so long time to make new service to catch up market requirement,the time should be shorten.

Since there are a lot of challenges ,how to slove this problem ,not only facing by operators, but also facing by our vendors,what's kind of solution our ZTE,as a mainstream provider,can offer,
so let's continue the second part,zte converged message architecture solution.

In our zte soluiton,we think that,at least it needs including the following four kinds of features .No 1,platform consolidation ,not only traditional messaging platform,but also IN platform,conference platform and LBS platform need to be combo .No 2,architecture evolution,NFV technology ,openstack technology and big data concept will be used in the networking architecture,regarding to big data concept,later we will tough on more details about it.No 3, service convergence,in our opinon,the voice service,message service and video service must be converged to enhanced the users'serivce experience.No 4,accelarate the period of new service deployment and shorten time to market,since cloud platform has the highlights of scale in/scale out function and can automatic deployment,it can enhance such kind of ability.

Meanwhile,zte converged message architeture solution can offer abundant access adopters layer,it can access sms/mms/vvm client,it also can access the OTT client,sns client,mail server and so on,so it can offer common engine,a cloud and all-ip convergence solution,it can compliant with call progress message and rich communication suite standard,it also can offer message store,manage any type of message and support cloud storage of exchanged message.

Due to the upper features and flexible access adopters,we think that,our converged message architecture can be bring a lot of benefits for our customers,the real benefits to our customers.so let's continues,

Benefit 1,converged message architecture can simplify the network,
As we can see from this picture,The modularized design can make network structure more clear,can emphasize service processiong and messaging data layer,meanwhile,it can not only offer unified interfaces to third party, but also can offer converged open enviroment for deploying new service and unified maintenance.

Benefit 2,cloudification(NFV) to reduce TCO and enable flexibility,
Actually you can see,what zte's solution can do,we can provide virtualized resource pool,unified data layer,so we can put different applications on the top of it,and furthermore,all these NFVI infructure can reused for deploying new service, so it can reduce capex.
And also ,we can build very smart resource management system and big enable system on the top ,so unified O&M system can manage all applications,and besides of this,it also can intergarted with exiting telecom system,such as,OSS system,BSS system,they are all merged together,so it can save opex.
And  what's more,this solution can shorten time to market,deploy new service more sufficient.
So in briefly speaking,it can cut over the TCO and enable system more flexible.

Benefit 3,dynamic license based on demand,
This is very amazing design,as we can see from the figure,sms,mms,vms,lbs,ussd can share the same license pool,that means operator no need locked in some sepecial apps license anymore,which can use license based on demand,so it can increase some apps license while decrease other apps license at some special time to fit for traffic peaks, holyday-specific traffic and other scinarios,and further more,license can sharing between countries,this is very useful for Opcos(operating company) telecom group,such as Telefonica Group,they just wanna build unica nework.

Benefit 4,big data concept to ensure high reliability,
As we known,nowaday,big data concept and artifical intelligence technology are large popular used in the IT areas/Inernet industry,they can grasp the user behavior accurately, they know what the customer like or dislike and so can delivery precise serivce.
And also,zte reconginzed the importance of big data and AI technology and develop it into CT areas/telecom industry,and bring benefits for operators.
As per the point,I will give you an in-depth presentation/analysis on it,(the main idea just like this/I wanna elaborate this point/elaborate as follows)so how to do it?
Step one, data collecting, collect the datas such as user behavior logs,user register,ordering and billing attributes from the system.
and then Step two,what should do to this datas,data clean and data analysis ,we have AI based leaning system,online learning,offline learning on all these datas and build a user behavior knowledge database,including public reference and personal portait,meanwhile,this step normally need third part data system join,you know,we do don't anything outside the law，especially in GDPR background .
and Step three,run the knowledge database,it can give some recommendation,content and forcasting to users, and also give precise market design,in this way it can ensure high reliability ,catch user consumption behavior and create value.
This is the benefit 4.and,then

Benefit 5,uni-message cache for high delivery efficiency,
Regarding to this point,what's kind of ,I would to say,algorithm is very important to enhance the cache delivery efficiency,zte use Fowler-Noll-VO Variant “1a”Hash algorithm ,with high speed and low collision,especially for short charchistic message delivery, and our Converged Message Architecture solution uses this kind of technologh, and so in this way,uni-message cache can work on high delivery efficiency.

Beneift 6,Ready for next generation communication platform-RCS
Our solution can also bulid Rich Communication Suite system,we can provide enhanced message service, such as rich message,group chat and friend circle,we can offered enhanced contacts ,like quick response code,public account and yellow page,and also suppply enhanced call,like HD voice call and group video call,in this way ,it can enhanced communications service,enhanced message,call and contact,and exposure basic capability for telecom operators and enterprises,so frank speaking,our solution can give strong challenge to the OTT service.By the way,this solution already bring benefit to China Mobile,in the latter slide,we will tough on more details.

Ok ,so let's take a summary,converged message architecutre solution can bring significant business benefits,the real benefits to our customers. 
Benefit 1,simplify the network.
No.2,reduce TCO and enable flexibility.
Benefit 3,dynamic license based on demand.
No.4,ensure high reliability.
Benefit 5,high delivery efficiency.
No.6,Ready for next generation communications.

so let's move to the last part,zte successful implementation experience in global of the world,we will take a glance,so here ,until now,I will frankly to say ,there are more than 100 operators,covering more than 1 billion subscribers, selected our converged message architecture solution to deploy their network.
So in this slide I show you some main references for CMA solution,for example,
In Telefonica, ZTE got the contract of covering Latin American countries to deploy VMS by providing converged message architecture solution,it is a good reference.

And in POST Luxemberg,do you know POST,it is a famous and long history telecom group in Europe,we offered virtual platform ,plus our APPs,plus VMware virtulization software.

And also in Claro Argentina,Claro is one of subcompay of Mexico Latin American group in Brazil,we provided fully compatible cloud solution,plus our APPs,plus Cisco blade servers and plus VMware cloud software.

And also in China Mobile,we build the world largest Rich Communication Suite by our converged message architecture platform,it served 100M  license subscribers and 16M active users by end of last year.

Actually we have some other references,just like the virtual messaging platform in 3 or 4 Orange Group countries and also build SMS/MMS/VMS based on CMA platform in Telenor group. 

I wouldn't emphaize one by one ,in the later slides,I will elabrate some sectional details.

Ok,so let's come to case studies,this case study is ZTE Converged Message Architecture solution for POST-Luxemburg.What zte did,actually,
POST-Luxemburg faced a lot of challenges, they have end of life of old Messaging Platform,they have the pressure to reduce OPEX, and pursuing a convergence strategy,they need new solutions,so they invited zte to provide converged message architecture solution for them,to swap exiting system from phsical way to virtualized way. 

So all current messaging equipments are migrated by ZTE E2E virtulized solution,using ZTE applications, zte E2E MANO management system and using VMware cloud software,launch new system coverd 1500 TPS for SMS,120 TPS for MMS and so on.

So what's kind of influence or benefit is happend in POST-Luxemburg,ok,
They embraced a converged platform and client,which can deploy all kinds of messaging applications.and NFV based on cloud can reduce TCO and make network more agile and more flexible, and also the MANO system can make operation & management more earier,more automatic and more intelligent.

This case I should emphasize more,what really zte did and what zte offered in this project,the project was totally divided into three phases,let's see.
In Phase 1,we provided SMS and MMS services based on converged message architecture platform.
In Phase 2,we provide other messaging services based on RCS and the IP SM-GW ,and also interconnect RCS to exiting SMS.
In Phase 3,POST wish to migrate existing JOIN SMS Center and MMS Center to our new converged message architecutre platfrom,zte also well done.

ok,so,Another typic Case is Claro -- Argentina,Claro is one of subcompay of Mexico Latin American group in Brazil.
Their systems are also facing such kinds of challenges ,such as ,Old Messaging Platform End of life;the chimney architecture is hard for operation and management,and pursuing a convergence and cloud strategy.

so what ZTE did, ZTE provided latest CMA solution based on cloud platform for Claro Argentina,we offered fully compatible cloud solution,such as ,we deplyed the hardware in Cisco server,cloud software in VMware and all applicaitons in ZTE.

In this way,they owned 20M subs VMS ,1250 TPS WAP and 50 TPS SMS systems，and furthermore,this platform is the 3rd party compatible cloud platform,that means it is earier and faster to deploy the other applications because of good compatible IOT experience,and also it is a flexibly Geo-Redundancy solution to guaratee the security of the network.

So,let's move to the last case, CMA-RCS for China Mobile,this is a model, a model project for CMA solution. 
In Mobile World Congress(MWC) 2014, China Mobile announced it's "Three New" strategy to upgrade existing call, message and contact systems,to enhance users service experience and satistaction,and more important,keep the No.1 operator position in China.

However,their exiting systems can never catch up this target,for example,both message traffic and revenue declined.and since 2013Q3, the net profit fell for the eight consecutive quarters,and worse to worse,Subs churn to the OTT messages,facing fierce competition from OTT messages application;and also lack of new business model.so,China Mobile urgent need to seek new profit growth and new business model.

So ZTE help them to lauched a world's largest CMA-RCS system,it is Top 1 capacity in global of the world, 100M subscribers license to be served ,and more than 16M active users by the end of 2017, covering the whole country.

So actully,you know,we finished the project completely,upgrade existing Call, Message, Contact to three new entrances,and let the platform more openness and aggregate,build new service channel,aggregate new applications to achieve forward charge and backward sponsor,and also our platform can make the foreground more focus on services while the background can more concentrate on all operation and maintenance. 

ok,so frankly to say,we know what the operators really to need and what's kinds of the challenge they are facing during all the stages,and we can help them to overcome all the challenges,to achieve win2win between each other.

Ok,that's all,thank you.

-----------------------------------------------------------------------------------------------------------------------------------------------

In the last part,we will take a glance of zte presenss on cloud infrasturcture deployment and experience.
Firstly ,let's show one slide,Actually ,until now ,I will frankly to say,zte is the leader of telecom cloud industry with most abundant   
deployment,so we have more than 320 cases,including commerical projects and Poc cases by the end of 2017,it is the No.1 in the industry.
so in this slide,it show you some main cases by the end of 2017,for example,

In the telecom Arstraulia Velcom Belarus,we have the world's 1st full virualized core network,plus zte TECS,plus zte hardware.

And in the VEON,do you know VEON ,it is a Russian telecom group,we are the solo NFVI provider in 12 countries and vEPC in 9 countries,some 
of them are already commerical used in CIS countries and Ukraine. 

And in Telefonica, ZTE got the contract of 7 Latin American countries to bulid vIMS for VoLTE,and also ZTE NFVI for telecom infrasturctures.

And also in China telecom,we provide unified cloud managment to manage all exiting 50 Data Centers,to manage all hardware from different 
vendors,to manage all resources from ZTE ,from VMvare,from Redhat,so it is cloud management systems.

Actually we have some other references,just like the Virtual Messaging platform in 3 or 4 Orange Group countries and also build the world 
largest vHLR/vHSS and NFVI platform in VEON Bangladesh. 

I wouldn't emphaize one by one ,in the later slides,we will show some secantional details.

So here I say some contribution, just take a glance.ZTE plays very important role in different open source communities,we are the driver of 
devepment of open sources communities,so we are platinum members of ONAP,OPFNV and Open daylight,and we are the gold members of openstack,
cloud native and 
DPDK, and we are also the silver members and leading contirbutor members of different kinds of open source communities.So something I would      like to emphaize that is in the openstack ,in the latest verion Pike, our contribution ranks to Top 8,and in ONAP,OPNFV,CEPH,Openshift and 
OVS ,our contribution ranks to Top 2,and also in kubernetes ,our contribution ranks to Top 5,so we can say we are the main contirbutor and 
leader position of open source communities.
   
   And also we got a lot of industry awards and high evaluation from different researches,for example ,from Ovum, IDC and current Analysis to show zte NFVI    
  rated very strong, we are the leading player and got the best core network produce in 5G world awards 2016 and praise from IMS world forum for Rich   
  communications ,and telecomasia for NFV innovation.      
  actually to say,our zte cloud based on infrastructure solution are widly reconginzed by the whole industry.
  
   
   Ok,so let's come to case studies/overview,this case study is vEPC and NFVI for the VEON,actually zte already implemented vEPC for VEON grounp in 9 counties,
it was already for commerical use and also we got the contract to provide unified NFVI for all the opcos and all application,including the 3rd part apps ,such as
Huawei,Nokia and openmind,it is unifed NFVI and deployments.These solution not only including NFVI but also SDN together,it is ,I want to say,in the industry,you can't find another project similar to this project,from scale opint of view and from decouple point of view,so I would to say ,this is a model ,model project in SDN/NFV area.
   
  The second typic case is what we did in Telefonica,actually 2016 we got the contract,from Telefonica,zte was invited to build virtualized IMS to 7 branches of Telefonica in Latin America, zte provided IMS applications and ZTE own TECS Virtulization products,now it is already commerical use and it can offered intelligent automated O&M,reduce workload by 70%.
   
  Ok,so this is another typic case,we told we bulid the world's lagest vSDM for VEON Bangladesh,including end to end solution from ZTE,covering applications,
virtualized HSS,HLR, and conver ZTE TECS in NFVI,also cover ZTE own hardware.
   
   And also ,this is one case I should emphasize,that's zte bulid the world's 1st fully-vitulized core network for Velcom,one of Australia Group branch in Belarus,
ZTE swapped the leagcy Erisson core network including CS,PS,SDM on top of ZTE virtualized core network in 9 months,so zte provide hardware,TECS,as VIM and
hypervise,open stack on top of more than 20 applications,and smooth migration of more than 5.6M subscribers,so I wanna say,this is world's 1st full-virtualized
core network,you will never found the 2rd one,so this is very good references.
  
  This is for Airtel Africa,we got the Virtual SBC project,SBC is a part of vIMS solution,to provide session boarder control and media voice plane.
  in this project,zte also provide SBC application and TECS NFVI product,and hardware,E2E solution.

  
  And also the last case here,it is zte cloud management platform for Shanghai telecom in China,so actually Shanghai telecom has more than 50 data centers,distributed in the different area of Shanghai,and in each different data center,they have different hardware platform from different vendors,such as server from ZTE ,from HP and from huawei,the stroage from HP,EMC and firewall from the Juniper,Cisco,they have a lot of hardware platform,and each data center has different virtualized technologies,for example ,ZTE TECS,VMware,KVM,XEN and redhat,so how to realize unified management for all these different kinds of virtulized technologies,it is challenge for Shanghai telecom,so zte provide unified cloud management system to manage all these hardware and logical resources.On top of it,here mentioned,zte also provide a public cloud business enabler system on the top.

so later,we will come to the next part,I will more focus on four best practice,give you more details information,so here the slides just give you an overview.
  
  so let's comet to the most impantant part today,ZTE best practices sharing and customer value focus on four projects.

  
  The first project is VEON group project,zte provide virtualized EPC and unfied NFVI,here give you an overview,what zte really did and what zte really offered in this project,actually,zte provided real 1st industry SDN/NFV platform for VEON group,distributed NFVI in 12 countires and virtual EPC in 9 countries,so it is real could and network synergy with high performance hardware from ZTE and HPE ,and provide Gi-Lan service chain,it is very interesting case,so if you interested ,later,we can offer more details information for you,today due to time limitation,I wouldn't touch more details.
  
  So here a doze of applications run on top of zte NFVI platfrom,part of them are from zte,for example,AAA,SFC,DNS,EMS ,but part of them are from the 3 rd party,
for example,inluding Huawei virtual EPC and vPEC from Nokia,so mutli-vendors are running on the unified NFVI,
  
  and also due to good support from zte team,we finished all test,including vEPC,NFVI test cases in 3 months,we passed 1455 cases,so it very good acheievement.

   
   so let's see,what would I wanna say in this project,first,we customized a lot of features for VEON,its DPDK plus OVS,plus SR-IOV on same physical NIC,normally   to say why we emphasize it,normally if you found in the industry standard case, that is one NIC, for example,we say one 40G NIC,you should use one for DPDK +OVS,another for SR-IOV,so it separate,in this case,you need run Virtual Machine for DPDK+OVS,Virtual Machine for SR-IOV in different blads and different rack servers,because you cannot share,but in this solution ,you can build virtual machine on DPDK,OVS and SR-IOV on the same blade and even on the same physical NIC,you save the number of NICs and you save the number of hardware,so you just improve the hardware resources,so zte make an example here,take vEPC with 2M subs as example,if you calculate in industry standard,you need 14 blades,but use zte solution,it just needs 11 blades,that means 3 pcs of blades you save,so if bigger resource need,the bigger hadware will be saved.this is benefits you get,frankly speaking ,in the industry,zte is the only vendor who can provide such kind of solution.
 This is first case,second is SDN-based cloud and network synergy coordination in VEON,
   
   As we from beginning ,I said in the VEON project,I think this is real industry SDN/NFV converged solution,commerical case,I am saying the commerical case in the
telecom industry,so SDN will help network more idea,more automation and more flexible in the network point of view,we not only provided physical overlay,but also physical overlay +logic overlay,for example,in the VMware,they just only offers software oveylay,they havn't hardware overlay,becaues they don't have physical switch, and for exmaple Cisco, they just have physical overlay and havn't software overlay,they just active their VTEP point on the top of their switches,but they don't have DVS,but zte  can support both solutions,software based ,hardware based or both,ok,and also we used micro-segmentation and mutli-zone design to guaratee the security of whole infrastures, and we provde TAPaas at the service scnairo for the VEON,to just save the offers,they just configure traffic monitoring one by one,while the migration ,the data will migrated automatically,you don't need configurate once again.so this is benefits you can get from SDN and NFVI converged solution.
So this is first case for veon project,the second we will focus on what is world 1st full-virtulized core network solution,in the Austria group in Belarus.
  
  Actually Velcom is one branch of Austrlia group.What zte did,acutally,Velcom faced a lof of challenges,they have old equipment from Errison,and they just one and half get out of serivce/warraty,and current network capacity is very small and old ,they need new solutions,so they required zte to provide next generation solution to swap exiting solution from physical way to virtualized way,actually zte done in 9 months. 
  
  So all current equipments for Ericsson,sorry some part of them from Cisco are migrated by ZTE E2E virtulized solution,including apps,TECS,hardware and E2E MANO,total 5.6M subs,what's kind of influence is happend in inner TAG,ok,in TAG group,they announced financal report quarter 2016,they announced save 50% TCO,so it means inner TAG,this project is will recognized by the group.
  
   So what we did,actually we provided unified physical and virtual resource co-management for Velcom, you will see this is one of TECS positions,we have dedicated module,such as heathy monitor ,self discovery and so on,it can manage different hardware from different vendors in exiting Velcom,while IPMI,SNMP different  
   interfaces and engines,and in another hand,we can manage different resource pool for different vendors,zte build CT resource pool for Velcom,but also they have IT resource pool based on VMware,how to manage it?We provide unified management portal for physical and virtual resource infrastructures.
    This is first ZTE did ,
   
   And second is ZTE also run public cloud business,but they don't look for separate protal for telecom cloud and public cloud,so they ask zte for help,so we have solutions,we provided zte TECS with TECS directory,play as unified management platform and public cloud business enabled platform to manage all resource pool for different cloud.also by providing unified portal,to realize operation maintenance ,resource maintenance and provide self-serice portal,administration portal ,everything,so unified cloud interfaces for all cloud.So this is what zte already real done to Velcom.

So let's have a look Telefonica,everyone maybe know Telefonica,right?
   
   Actully they are also facing a lot of challenges,they are big enough,but they also have some risk on challenges,they have high TCO,and also looking for smart solutions ,can migrate their legancy network to cloud network,for example ,for this case,they wanna virtualized IMS solution for VoLTE serivce.
   
   What zte did,actually zte build mutli tenancy based VoLTE in 7 Latin American countries,of course ,we don't bulid one virtalize for one Opcos,because it wastes of cost and some Opcos is very small and they are close each other,so for 5 countries of 7 ,we build one vIMS network,and one cloud infrastructure for 7 countries.
 how can we realize it ?from applications layer,they should separate,but for cloud infrastrucute layer,for physical you should one but for logic you should divided into 5 parts,you should different assoluta technologies from different tenancy for different countries,because different countries ,they must have different rights to manage to infrastucture, they cannot mixed together,different country different brand,so in another two countries ,they bulid separately virtualized IMS network,so this is very typic case,it is multi tenancy applications for openstack.
   
   What's kind of,I woluld to say,intelligent key tool to Telefonica,that is intelligent O&M solution,actuall we collect all the loggs from the system,including performance data,running data and even data together,so what should done to this datas,we have AI based leaning system,online learning,offline learning on all these datas and build a expert knowledge database,and we build database engine to analyze these datas, what we will get after analysis?we have gotten abnormal detection and forecast,heathy scoring ,root cause analysis,it can do anything on the result,also you can send this result to the 3rd party for deep analysis,so this is very powerful and intelligence O&M,it can make the O&M more visualable,risks and issues inadvance before they happened, we have enough time to take action.
   
   This is another small feature for Telefonica,what we called, vNIC implicit bond,this is zte dedicated feature ,you will never find this similar feature from other openstack vendors, zte has dedicated pertain on this.(You use a ,actually you know)For one kind of Virtual Machine,at least it should has two NIC,right?Active and standby,you cannot use single NIC,normally,in VM layer ,it will do binding ,to make two NIC to uni-one NIC,A/S target,but it brings extra requirement on VM, so what can bring to this ,what zte can optimized,zte dedicated vNIC technology,zte call implicit bond,on the TECS level ,on the openstack layer but not on the VM layer,so VM don't take care how to bind to vNIC,you only look one vNIC,but on the opeanstack layer we will bind two VF，if we talk about SR-IOV,VF in SR-IOR  is one kind of virtual NIC,we bind two VF into one,which means we bind on virtual layer not on the VM layer,it is safe and can decrease capacity on the virtual machine layer,this is what we bring for Telefonica vNIC implicit Bond,zte dedicated feature.

OK ,let's move to the last case ,in Shanghai telecom,so this case is also very typic.
   
(Shanghai telecom,actually you know) everybody tries to talk edge data center, or mobile edge computing,Shanghai telecom already has more than 50 data centers,distributed  in all area of Shanghai ,you know,shanghai is a big city with the large population of more than 25M people,so in each different data center,they have different hardware platform from different vendors,such as server from ZTE ,from HP and from huawei,it hard to manage and in Shanghai telecom they also run public cloud business,for cloud connection,cloud security and cloud computing and cloud storage.so in normal case you don't have business enable and self-serice and administration portals,how they do this business,cloud business, they rely on people,normally they need some hours and days to active one cloud services,it is insufficient.
   
So what zte provide to them,zte provide E2E solution,firstly we can manage different hardwares from different vendors,Secondly ,we can manage different resource pool on different vendors,ZTE TECS,VMware,Redhat(redhat I didn't mark here,actually it is there),and also they try to bulid other resource pool.
we put TECS openstack on top of it,to be unified interfaces.On top of openstack ,we build very big cloud resource management system and big enable system,on the top ,unified interface for all O&M system and business target.So also zte TECS intergartion with exiting shanghai telecom system,for example,OSS system,BSS system,they are all merged together.
   
   So how we manage to VMware resource pool,we have adopter API interface,we put openstack TECS in between top with vCenter,intertally we matching between VMware parameters to openstack parameters,so it enable shanghai telecom only need to realize on zte TECS,they don't need VMware vCenter anymore,because in our great interface to recevice all lifecycle management operation system on portal,all bottom is VMware resource,you just run one portal to manage all resource pool,whatever, ZTE ,vmware or redhat.so it makes your O&M more sufficient.
   
   
    And also,we are not only resoure management but also bring a agile ,automatic pulic enabler in shanghai telecom,to let you have E2E mintue or second level E2E public cloud service action and orchastration ,because of they have different pulic service,such as security,stroage service,so we provide cloud management system for them.
 
   Ok,we will come the last silde,from O&M point of view,what we can get from zte TECS?we have unified topology display,mutli-layer statisic and unified centerlized alarm management to covering all hardwares and covering all VMs from different vendors and from different data centers,and also real-time KPI monitoring on all the virtualized resources,actuall what I say ,this is not only resouce management centers but also monitoring centers and also show all topologies,you can do all operation&maintenance tasks with single TECS product.
  
  So the last slide,the last sentence I will make summarize today,that is due to zte has a lot of NFV /SDN experience in the CT area,I will say,we are the vendor with most abundant telecom cloud deployment experience,untill now we have more than 1200 deploment cases,from planning&design stages,integration stages,installaion&deployment stages to O&M stages,we know what the operators really to need and what's kinds of the challenge during all the stages,we can help them to overcome all the challenges.
 So many thanks,guys,that's all.
-----------------------------------------------------------------------------------------------------------------------------------------------------------------

Goog morning,ladies and gentlemen,Very honorable to be the first speaker here ,at first ,first of all,
----------------------------
Well,actually ZTE brings what we call carrier Devops and cloud native application to this event,so carrier Devops can help operator to deploy network slice within mintues,and scale in/scale out within seconds.we understand that OTT have a great challenge to the telecommunicaiton industry,but actually the pipe I mean the network is still a black box to the OTT,so the cloud native solution which is released by ZTE can help the OTT to catch up the capability of the network, so the network will never be a black box to the OTT,it cloud be converged with OTT together to provide better service to the end customers,zte provide what we call carrier-grade Devops and carrier-grade network application to the network.So by providing the network on the cloud,we are not only guarantee the security of the cloud, but also guarantee the performance I mean the reliability of the network,And another case, we can deploy our cloud native application on the public cloud ,we introduce what we call cloud native NFV,I mean the box which is identified by 3GPP,can have the open API to expose the capability of the network to the OTT,so the OTT appliication can talk to the network about their requirement.So they are not best architecture,so we can negotiate,we can share the resource and talk to each other,

with the test of Tier 1 operators such as Telefonica and vodafone,We do prove ourseleves this CMA solution can not only run on the clouds but also keep the reliability,security,all regulation requirement just as the legacy telecom network.we can cut over the TCO and also have the capability to migration of the future network such as 5G.

-----------------------------
What's your vision on the digital transformation(Cloudification) in the telecom industry?and how do you see the relationship between welcome developing?Nowadays, the telecom operators are facing the booming of new requirements,and the challenge from the OTT service providers,and I think this situation will be change more serious when 5G and IOT era are coming,so the operators need to be changed, to be more open,more agile and more on-demand,they also need to change their network,their infrastructures,change it to cloudification and change their service to the cloud.ZTE has a full mature,complementary solution for network cloudification for our customers.
ZTE is going fast in the field of network virtualization and cloudification,what is in some of your market achievements so far?
Up to now,zte has gotten more than 240 projects globally about the virtualization and the cloudification of the network with SDN and NFV technologies,in last year 2017,we got more than 40 new projects from our customers on this demand.So we think that, for the industry,the virtulization is mature,it is a mature techmology now,it is not a concept,it can bring benefit ,a real benefit to all customers,and we also have our customers to touch the edge technology,such as open source with ecosystem to use the new technology,to improving their network performance.
-------------------------------


Page 1
Good morning everyone, my name is Zhang Fan, coming from ZTE Corporation. I’m in charge of packet core architecting in mobile network. Today it’s my great honor to be at OPNFV summit in Beijing. It’s my first time to be at the stage of OPNFV summit, but I can feel the power from open source community. It’s a great time to feel the beauty of open source technology together with you. In next 20 minutes I would like to share NFV commercial practice for mobile network. Why I introduce mobile network as a commercial case to speak? The main reason is that the mobile network is the most performance demanding function group which drives infrastructure innovations. If the mobile network on virtualization network is going well, the road of open source must be on the right way.

Page 2
Now the mobile network is in the stage of transformation. Looking back to the past 20 years, the mobile network is changed from closed system to open architecture, from hard-centric to software-centric. All the changes benefit from the development of open source community. On the other hand, the open source is adopted gradually by the telecom applications. The OPNFV is such a community to connect the telecom and open source.

ZTE already have wide cooperation with open source community and global operators to push the development of NFV. Now, ZTE have more than 240 commercial and PoC cases globally. ZTE help our customers to transform their networks from legacy to cloudification. It is not easy to do it. We need to innovate the network, we need to break the traditional chimney style, we need to change the thought of people. During the processing, ZTE always embrace the change and promotes the innovation. For each project, we provide end to end solution and integration responsibility for all components. So we made it. I would like to introduce two typical cases at the moment.

Page 3
The first case is our commercial project for TAG (Telekom Austria Group). Legacy network has a small capacity and old version, long time new service deployment and expensive CAPEX/OPEX. ZTE conducted a major flagship project with focus on migrating and transforming the core architecture. All legacy network functions including EPC, MSC, IMS, PCRF were migrated to a fully virtualized platform on OpenStack.
This project served for 5M subscribers. It is the first project globally that has a size of more than 5M subscribers and a scope of full core network functions.
In data center deployment, there are 3 data centers, they are working in load sharing with geo-redundancy mechanism. Via the high availability design, in case of any DC failure or disaster, no service is interrupted.
In this project, we have more than 20 APPs integrated, but It just took 8 months to finish all the construction and transformation. We cannot imagine such a short time period without NFV deployment.
With this major step towards the next generation network architecture, the customers are able to reduce OPEX/CAPEX and improve efficiency significantly. 
As we shared the hardware and cloud operating system, we need less machine room space, the power requirement is going down, so the TCO is estimated to be saved by more than 50%;
As all APPs are shared a same resource pool, no any application need to allocate a dedicated resource pool. So we can make full use of resources, the resource usage is increased by 70%.
With NFV deployment, this project can get a faster TTM for new service. It’s much be easier to onboard any new service. The TTM can be saved by 35%.
We made a great progress on commercializing the virtualized network.

Page 4
Let’s move to another important case. The key words of this case is openness and fully decoupled. It is a leading architecture and future-oriented NFV solution. 
There are 3 decoupled layers in this project.
The bottom is a common hardware layer. We use different types of hardware: switch, blade server, rack server, storage. They are not only from ZTE, but also from 3rd party. Two types of blades are used, 10GE and 40GE for different applications purpose. We also choose a remote storage with high IOPS capability for web Cache and Video applications.
The middle layer is open cloud operating system. It is a core part of NFV infrastructure. In this project, this layer is provided by ZTE. From the beginning, this layer must be open. It consists of 3 important components. 
The first one is TECS OpenStack, it is ZTE Tulip Elastic Cloud System, based on OpenStack. We made a lot of enhancements on the native OpenStack components to reach the carrier-grade availability, performance, resilience. This component must supply the resource needed to support the various application workloads.
The second one is ZTE ZENIC SDN Controller, cooperating with TECS to achieve intra datacenter and inter datacenter connection.
The third one is TECS Director, it belongs to management level.  it is used to provide a unified management platform for distributed Data centers. It can manage the global resource pool, global policy, global portal and identity authentication across multiple data centers.
The top layer is application layer. In this project, we integrate more than 20 Apps from different vendors. We integrate not only the packet core itself, but including more other functions like Messaging, firewall, NAT, transparent cache, TCP optimization, video optimization as well. The different application characteristic and requirement is quite different, for example, some applications need high data plane throughput, some applications need high CPU processing capability, and some applications need high storage. The requirement is different, how to balance all the applications on one cloud, and how to integrate so many applications more efficiently? It is a big challenge.

Page 5
During the commercial processing, ZTE have a lot of experience and practice to face the challenge and solve the problem, we would like to share with open source communities. The road of ZTE open source practice has begun from 2014. Now we have more than 200 professional developers are working with partners from 13 open source communities. As a platinum member of OPNFV, ZTE participated in 19 projects, and lead projects like Daisy, QTIP, Storperf and big data. In 2016 we have 637 commits to OPNFV, This year we are planning to have more than 800 commits to OPNFV. 
We have Pharos LAB for OPNFV in Shanghai, providing 4 bare metal PODs and 2 virtual PODs. All hardware in this LAB is from ZTE.

Besides OPNFV, ZTE already joined over 70 standards organizations. 
ZTE is gold member of OpenStack and platinum member of OpenDaylight and ONAP. We are looking forward to connecting Global open source community to promote the maturity of SDN/NFV ecosystem by using our rich practice.

Page 6
In term of commercial practice, I would like to share 5 points. From Networking architecture, Automatic deployment, Data plane acceleration, Carrier-grade high reliability to Multi-vendor inter-operability. We think this is top 5 challenges or problems for the commercial network.

Page 7
Coming to No.1 practice, networking architecture.
In the past 20 years, telecom equipment platforms are often closed, the designing is always based on the tightly-coupled software and hardware, But in the commercial NFV network, we need to deploy many Applications, we need to create a large number of routing and connectivities from each other. it’s pretty hard to extend the networking by traditional way.
We proposed to use SDN based VxLAN networking. It is leaf and spine architecture. We deployed ZTE ZENIC SDN Controller, which moves the control plane outside the forwarding plane with providing simple abstractions to describe the components and functions. In the forwarding layer, we deploy 3 types of switch: ToR switch, Aggregation switch and VxLAN GW. The SDN controller uses a south-bound protocol to communicate policy and forward flow table to the OVS or routing devices. 
The unified overlay and underlay networks are working simultaneously. The logical networks are established through VxLAN tunnels. We set VTEP (VxLAN tunnel End Points) at different points. The SDN Controller communicates with VTEP and then creates distributed router. Our designing principle is to make the forwarding path be shortest to get more efficient and fast. Compared to centralized routing, the distributed router can reduce the number of router hops, and optimize the traffic path, most of traffic can be forwarded by the nearest switch. The traffic passing through the VxLAN gateway can be decreased by 50%.


Page 8
Practice No.2 is how to solve the problem of deployment. In NFV network, many components are working together. It’s quite difficult to deploy by manual configuration. We need a fast and automatic way to integrate them more efficiently.
We proposed to use ZTE Daisy. It is an automatic installer and deployment tool for virtualized environment. It’s also a project in OPNFV. With innovation of Daisy, the install processing will be much easier. Now we already used Daisy for commercial network, especially for large-scale network. We made many innovations for this deployment tool.
Cluster is the basic unit of Daisy management. Support to create cluster based on the cluster template. The template can be generated from an existing cluster. The cluster template contains cluster information and the generated host information. The template can be imported and exported.
Support the automatic expansion of compute node. When there is new compute node adding to the network, Daisy can automatically discover and install it. 
When the network configuration is modified, Daisy can update automatically without redeploying the cluster.
Daisy can use multicast mechanism to distribute the image to target nodes. So the target nodes just use the local image to finish the deployment. It will shorten the time of deployment, and save the bandwidth.
Support a variety of disk arrays.
Enhancement on compute node performance. Daisy support adjusting the CPU kernel and NUMA configuration to satisfy the performance requirement of different hosts.

Page 9
No.3 Data plane acceleration optimization.
Data plane acceleration. The performance issue is one of the hot topic in open source community. The explosive growth of data traffic makes it more important than before. We have a lot of services that need high throughput and ultra-low latency, especially 5G and IoT applications.
From the mobile network architecture perspective, the main idea and future target to improve the performance is flattening. In 4G network, even the architecture is changed to a little bit controlling and Forwarding separation, but it is not completely decoupled. When NFV is introduced, decoupled controlling and forwarding can be implemented. The controlling is centralized, while the forwarding is distributed. It is also the architecture.
We have software and hardware acceleration.
ZTE developed DPDK based DVS, which has much more performance than OVS.
We optimize the collaboration with SDN controller, We simplify the forwarding processing. Not all network update procedure must be forwarded to SDN Controller, almost all packets can be processed locally via flow table in compute node without involvement of SDN controller.
We also have enhancements based on open source FD.Io VPP. We combine our mobile service processing and VPP to reach the maximum performance. For example, for dynamic routing, service based forwarding, we can insert new nodes to VPP.
We enabled DVS+SRIOV on one physical port, NUMA, core bonding, to optimize the performance. Totally the software acceleration can get 7.5 times performance.
But it is not enough. As the software acceleration must have bottleneck and CPU processing must have limitation, another idea is hardware based acceleration. We can offload the processing from CPU to hardware. We proposed to use smart NICs to achieve much more performance. We can offload most of the traffic from OVS to hardware NICs, such traffic is processed and forwarded by hardware. This case can be used for DPI processing, IP packet fragment and reassembly, data encryption, firewall. The hardware acceleration can get 5 times performance and 80% CPU offload.

Page 10
Practice No.4 Carrier-grade reliability.
A major characteristic of telecom cloudification is high reliability. The regular reliability requirement is 5 9. We need to find solution to make the reliability more than 5 9.
In traditional physical network, we mainly depend on hardware to get higher reliability. We often use hardware signal to detect the failure and then recover the system. But in NFV, we should take into consideration the software based reliability mechanism.
In compute node, we need to consider all the abnormal scenarios for VM, for example, scaling, switchover, migration, the service can never be interrupted. We also make an enhancement on VM re-born. When we plug out any blade from the rack for maintenance or for some other reason, all the VMs and resources in the blade can be re-born in another compute node automatically. We must use this solution in commercial network.
In networking part, we implemented SR-IOV bonding to achieve high availability for SRIOV NIC. In some operators, packet mirroring is required. ZTE make some enhancements on TAP and extend it as a service. In virtualized environment, the mirroring policy is global, no matter where the VM migrate or scale, the TAP service is always available independently with hardware location.
In Storage part, two or more VMs mount a same virtual disk, in normal case, it only allows one VM to read and write data on this sharing virtual disk. When active VM fails, another VM can continue to read and write on the same virtual disk. We also have enhancement on CEPH.

Page 11
Practice No.5, multi vendor Inter-operability between each other. Of course we have many methods to do the inter-operability, regularly we have horizontal integration, vertical integration, but today I just focus on one point, network service chaining (SFC). During our project, we found there are more and more network functions like fw, nat, transparent cache from different vendors integrated into the network. We need to orchestrate all functions into different chains based on different policies.The policy can be user group, end user location and access network. In order to make new network functions into NFV environment, we provide an open smart service chaining platform to make the integration easier. In this platform, we have 3 functions:
The first is service orchestration, managing the service chain topology.
The second is connecting network functions with NSH encapsulation and forwarding the packets according to the sequence of service chaining. 
The third is providing load balance capability for all network functions. The total service chain is capable of scaling. When the network functions are scale in or out, or have some failure, the chain will be updated accordingly.
On top of ZTE vSSC platform, any new network function can be integrated into the NFV without any customization. We just have some simple configuration, any new function can be added into the network.

Page 12
This is a case to show our inter-operability on OPNFV platform. In April, this year, ZTE participated in the plugfest in Paris. ZTE demonstrated the installation of vIMS, vEPC, vUDC and MANO on OPNFV release Danube. After that, we tested IMS phone call on mobile phone successfully. It clearly demonstrated that the mobile core applications can be working well on OPNFV platform.
In this plugfest, we finished QTIP inter-operability test. QTIP is an OPNFV project for platform performance benchmarking, which is led by ZTE. We tested QTIP on 4 installers and 6 different hardware. This year we plan to deliver storage and network QPI by integrating test cases from other projects like storperf, yardstick.
We are introducing testAPI in OPNFV community. It will be beneficial to publish the test results. This year we plan to support web access and unified authentication and authorization.
Of course during the inter-operability test, we found some compatibility problems. For example, some configuration in nova config is not correct, some default value can be optimized, and SSE3 instruction is not enabled for some VMs. It’s a normal issue. We really need more and more integration test verify and correct compatibility problem and then improve it.

Page 13, Summary
OK. That is all 5 practice to be shared.
Now let me make a short summary for today’s presentation. From the beginning of mobile network, ZTE experienced the development of 2G, 3G, 4G and upcoming 5G. We have a deep understanding for the telecom network, and we have a large number of commercial practice. We are willing to have continuous innovation and enhancements with open source community for future network. Now we are moving to 5G and Cloud native based network, we really need more and more vendors and communities to work together, communicate with each other, and make more contribution. I believe we can do it together.

Before the end of my presentation, I would like to invite you to ZTE booth to visit. You will experience the first Carrier-grade DevOps, you will experience the live demo of network slice and containerized vEPC. I believe it will be a special journey and experience for you during this OPNFV summit.

Thank you very much.

祝贺各位获此殊荣，更要对大家表示感谢！你们代表着一营的先锋，是大家学习的榜样！
也感谢所有奋力拼搏的一营将士们。特别是在公司目前阶段，大家展现出来的激情、自信、坚持、专业、真诚，敢于亮剑，有勇有谋，团结一致，坚守岗位，用实际行动支持公司渡过难关，感谢大家！
任何通往光明的道路都不是笔直的。我们一起坚定信念，众志成城，一定会遇见更美好的明天！

Warm congratulations and deep gratitude to our pioneers !
Also thanks a lot to all  colleague for your hardworking and strive ,especially this period ,always follow  our  passion \self-confidence \persistence \profession \sincerity principle ,make a unite effort ,stick to our posts ,try our best to perform  the responsibility, which is the greatest support we can provide for our company .
No excuse !Nothing is impossible ,Never give up !"Let us keep faith in ourselves and our company, knowing that by passing through storms we will finally become stronger."

                    ZTE CloudStudio - A Leading Cloud O&M Solution With Most Abundant Telecom Enhancement

Should we start?ok,let's start,so thank you everybody,my name is Mike,Cloud Core Network Solution Manager from ZTE.

Today in my session,I will introduce ZTE CloudStudio Solution- A Leading Cloud O&M Solution With Most Abundant Telecom Enhancement ,just tell you ZTE how to enable cloud operation transformation for ICT industry,if you allow ,let's continue,if you has any question,please let me know,ok,so

Let's move to the agenda today,it was devided into three parts,the first part,we will take overview Why CT O&M require telecom enhancement,this is driven by a lot of trends and challenges,for example,with the large popular using of cloud technology in telecom industry,not only service layer need O&M,but also cloud layer need to be O&M,another example,complicated orchestration and network slice needs intellegent operation,since having such kinds of trends and challenges,how to catch up?so the main part is the second part,zte will give cloudstudio solution with most abundant telecom enhancement to our customers,and at last,we will take a glance of ZTE CloudStudio deployment and experience in global of the world.

Ok,so let's have a look,new demands for future network evolution:
No.1,Diverse services are booming rocketly,on one hand,with the large popular using of smart phone and  OTT service,on the other hand,5G is coming ,the applications of more traffic，low latency，massive connectivities will become more and more.
No.2,Rapid innovation,nowadays more focus on service innnovation,according to our engineering experience,in the legacy network,the period of deploying new service for commercial use needs nearly 6 months,it is so long time to make new service to catch up market requirement,the time should be shorten.
No.3,Cost saving,in the traditional ,the network is rigid pipe, each network element needs different O&M and most of them need manual operation.When facing to cloud plaform ,this kind of situation need to be changed,should make operation work more flexible,automatic and intelligent.
So in briefly speaking,with the popular using of cloud technology and 5G dirven,the cloud network operation also should be automatic and intelligent and on demand.This is the first main point,

and the second point,since having such kind of new demands,cloud network management architecture are also facing a lot of challenges,as we can see from this figure:
Challenge 1,cloud management and service management are been separated,requires two views of OSS and NFVO, it is not convenient for related management.
Challeng 2,cloud management operation needs to switch over among multiple systems, lacking of unified portal, difficult to use.
Challeng 3,the interface standard between Os-Ma, Ve-VNFM is not mature, difficult for third-part integration

Since there are a lot of new demands and challenges ,how to slove this problem ,not only facing by operators, but also facing by our vendors,what's kind of solution our ZTE,as a mainstream provider,can offer,
so let's continue the second part,zte CloudStudio solution with most abudant telecom enchancement.

As we can see from this slide,we can offer the first carrier-grade devops solution---CloudStudio solution.As we know ,the method of devops already brought a lot of benefit to IT area,it can make design on-demand,service shorten to market, make IT infrastrucute operation more sufficent and intellegent.Our ZTE also know importance of devops and use it into CT area,and also enchance it.In this way,it can provide a set of complete solution not only including design domain ,but also orchastration domain and assurace domain,it can cover develop procedure and operation procedure,make O&M work on-demand  and intellgent,furthermore ,it can integrated with the 3rd part platform ,portal server and application platform smoothly.

Ok,we know good design is the first step to success in daily life,telecom industry is also the same,fortunately ZTE CloudStudio solution is just based on-demand flexbile design,it can provide excellent design portal,it can smartly uniform service provisioning and service assurance .as we can see from the left part,the service provisioning can offer order decomposing,service procedure,resource instance and service activation,in the right part of figure,we can see it can offer complete service assurance,it can collect the data,monitor service,analyze service and excute policy.In the way,make process design,resource design,policy design and assurance design enabling each other.
This is first key point of zte cloudstudio solution,agile design ,let's continue to the second key point,automatic deployment.

We can use CloudStudio depoly tool to do E2E integrated deployment,it can finish hardware, virtualization layer, NS and VNF integrated installation and deployment. and most of this deploy procedure can automatic,it can  HW self-detection, SW self-installation, NS self-orchestration, NS self-test.and what's more ,it can customized the deploy procedure according to different scenarios.So here ,I will frankly to say,this is very intellegent tools, and by the way,we develop one tools named daizy,not only has been popular commerical used but also riched the openstack communites' components.Regarding to this point,in the latter slide,we can tough on more details about it.

This is the second key point--automatic deployment,and the third key point is intellgent O&M.
Our solution can also provide closed-loop assurance to assist intelligent O&M,
It can offer powerful O&M assurance ability,it can use the method of centralized monitoring, application management, centralized resource, real-time monitoring and other ways to improve system assurance ability.
It can support automated O&M closed-loop,Self-healing closed-loop: detect failure, trigger self-healing policy, automatically restore the problem.
It can also support manual O&M closed-loop,if the failure cannot be automatically restore, the system automatically distributes a O&M work order to carry out the manual O&M closed-loop.
In briefly speaking,we use both automated O&M way and Manual O&M way to provide closed-loop assurance.

Let's take a more intu'itio'nistic overview.This is Dashboard,which can monitor whole network state,as we can see from this picture,there are many kinds of meters to show the network state.
It can evaluate global health state , monitor global VNF and NS state.  
Dashboard can display O&M, resource, alarm, performance, etc.
Multi-layer data association can display physical ,virtual and service layers.
E2E alarm association can display across wireless, transport, core network and other networks.
So it is a very excellent dashboard.

And what's more ,we can setup root cause association analysis based on big data concept and artifical intelligence technology to troubleshooting rapidly.As we known,nowaday,big data concept and artifical intelligence technology are large popular used in the IT areas/Inernet industry,they can grasp the root cause troubleshooting accurately and offer intellegent O&M.
And also,zte reconginzed the importance of big data and AI technology and develop it into CT areas/telecom industry,and bring benefits for operators.
As per the point,I will give you an in-depth presentation/analysis on it,(the main idea just like this/I wanna elaborate this point/elaborate as follows)so how to do it?
Step one, data collecting, collect the datas such as resource usage,alarm logs,performance data from the system.
and then Step two,what should do to this datas,data clean and data analysis ,we have AI based leaning system,online learning,offline learning on all these datas and build a multi-dimensional association cause knowledge database,including but not limited to alarm code association,location association ,performance association and etc.
and Step three,run the knowledge database,it can give horizontal alarm association analysis and vertical association analysis,in this way it can rapidly find root cause,it is a intellegent O&M.

Ok ,so let's take a summary,CloudStudio solution has three highlights.

Highlight 1,it can offer agile design,it can offer what you see in what you get design and this kind of solution can deploy the network design in serval minutes. and furthermore,extensive template library can pre-integrated with thousands of CT and IT applications and components.

Highlight 2,it can offer automated deploy
it can deploy NF/NS in serval minutes and One-key to deploy HW / VIM /APP automatically.

Highlight 3,it can offer intelligent O&M.
make O&M automatic, policy-driven elastic self-healing in seconds
it can give intelligent analysis and O&M,it can offer comprehensive monitoring, intelligent RCA.

So let's move to the last part,we will take a glance of ZTE CloudStudio deployment and experience in global of the world.Firstly ,let's show one slide,actually ,until now ,I will frankly to say,zte is the leader of cloud telecom industry with most abundant deployment,so we have more than 360 cases,including commerical projects and Poc cases by the end of 2018Q2,it is the No.1 in the industry.
So in this slide,it show you some main cases by the end of 2018Q2,for example,

In the telecom Australia Velcom Belarus,we have the world's 1st full virualized core network,plus zte Cloudstudio management system,plus zte TECS and plus HPE hardware.

And in the VEON,do you know VEON ,it is a Russian telecom group,we are the solo NFVI provider in 12 countries and vEPC in 9 countries,some of them are already commerical used in CIS countries and Ukraine,plus zte cloudstudio management system and NFVI. 

And in Telefonica, ZTE got the contract of 7 Latin American countries to bulid vIMS  by multinational orchestration, plus our cloudstudio management system and NFVI for telecom infrasturctures.

And also in China telecom,we provide unified hybird cloud managment to manage all exiting 50 Data Centers,to manage all hardware from different vendors,to manage all resources from ZTE ,from VMvare,from Redhat,so it is cloud management systems.

Actually we have some other references,just like the Virtual Messaging and cloudstudio platform in 3 or 4 Orange Group countries and also build the world largest vHLR/vHSS and cloudstudio platform in VEON Bangladesh. 

I wouldn't emphaize one by one ,in the later slides,I will elabrate some sectional details.

Ok,so let's come to case studies,this case study is Multi-vendor Integration for the VEON,actually zte already implemented vEPC for VEON grounp in 9 counties,it was already for commerical use and also we got the contract to provide unified NFVI and unified management for all the opcos and all application,including the 3rd part apps ,such as Nokia and openmind,it is unifed NFVI and unified management.These solution not only including NFV but also SDN together,it is ,I want to say,in the industry,you can't find another project similar to this project,from scale point of view and from decouple point of view,so I would to say ,this is a model ,model project in SDN/NFV area.

And also ,this is typic case I should emphasize,that's zte bulid the world's 1st fully-vitulized core network for Velcom,one of Australia Group branch in Belarus,ZTE swapped the leagcy Erisson core network including CS,PS,SDM on top of ZTE virtualized core network in 9 months,so zte provide hardware,cloudstudio,as VIM and hypervise, and management system,smoothly migrate more than 5.6M subscribers,so I wanna say,this is world's 1st full-virtualized core network,you will never found the 2rd one,so this is very good references.
  
Ok ,let's move to the last case ,in Shanghai telecom,so this case is also very typic.Shanghai telecom already has more than 50 data centers,distributed  in all area of Shanghai ,you know,shanghai is a big city with the large population of more than 25M people,so in each different data center,they have different hardware platform from different vendors,such as server from ZTE ,from HP and from huawei,it hard to manage.   
So what zte provide to them ? ZTE provide E2E solution,Firstly,we can manage different hardwares from different vendors,Secondly ,we can manage different resource pool on different vendors.We put Cloudstudio on top of it,to be unified interfaces.unified interface for all O&M system and business target.And also zte Cloudstudio intergartion with exiting shanghai telecom system,for example,OSS system,BSS system,they are all merged together.

So I will frankly to say,we are the vendor with most abundant telecom cloud deployment experience,we know what the operators really to need and what's kinds of the challenge during all the stages,we can help them to overcome all the challenges.

So many thanks,guys,that's all.

                    ZTE CloudStudio - A Leading Cloud O&M Solution With Most Abundant Telecom Enhancement

Should we start?ok,let's start,so thank you everybody,my name is Mike,Cloud Core Network Solution manager from ZTE.

Today in my session,I will introduce ZTE CloudStudio Solution- A Leading Cloud O&M Solution With Most Abundant Telecom Enhancement ,just tell you ZTE how to enable cloud operation transformation for ICT industry,if you allow ,let's continue,if you has any question,please let me know,ok,so

Let's move to the agenda today,it was devided into three parts,the first part,we will take overview on Why CT area O&M require telecom enhancement,this is drived by a lot of trends and challenges,for example,with the large popular using of cloud technology in telecom industry,not only service layer need O&M,but also cloud layer need to be O&M,another example,complicated orchestration and network slice needs intellegent operation,since having such kinds of trends and challenges,how to catch up?so the main part is the second part,zte will give cloudstudio solution with most abundant telecom enhancement to our customers,and at last,we will take a glance of ZTE CloudStudio deployment and experience in global of the world.

Ok,so let's have a look,new demands for future network evolution,
No.1,Diverse services are booming rocketly,on one hand,with the large popular using of smart phone and  OTT service,on the other hand,5G is coming ,the applications of more traffic，low latency，massive connectivities will become more and more.
No.2,Rapid innnovation,more focus on service innnovation,according to our engineering experience,in the legacy network,the period of deploying new service needs nearly 6 months,it is so long time to make new service to catch up market requirement,the time should be shorten.
No.3,Cost saving,in the traditional ,the network is rigid pipe, each network element needs different O&M and even manual operation,this kind of situation need to be changed,should make operation work more flexible,automatic and intelligent.
So in briefly speaking,with the popular using of virtualization technology,the virtualized network operation also should be automatic and intelligent.This is the first main point,

and the second point,since having such kind of new demands,cloud network management architecture are also facing a lot of challenges,as we can see from this figure,
Challenge 1,cloud management and service management are been separated,requires two views of OSS and NFVO, it is not convenient for collaborative management.
Challeng 2,cloud management operation needs to switch over among multiple systems, lacking of unified portal, difficult to use.
Challeng 3,the interface standard between Os-Ma and Ve-VNFM is not mature, difficult for third-parity integration

Since there are a lot of new demands and challenges ,how to slove this problem ,not only facing by operators, but also facing by our vendors,what's kind of solution our ZTE,as a mainstream provider,can offer,
so let's continue the second part,zte CloudStudio solution with most abudant telecom enchancement.

As we can see from this slide,we can offer the first carrier-grade devops solution---CloudStudio solution.As we know ,the method of devlop already bringed a lot of benefit to IT area,it can make service shorten to market, make IT infrastrucute operation more sufficent and intellegent.Our ZTE also know importance of such kind of method and use it into CT area,and also enchance it.In this way,it can provide a set of complete solution not only including design domain ,but also orchastration domain and assurace domain,it can cover develop procedure and operation procedure,make O&M work  on demand  and intellgent,furthermore ,it can integrated with the 3rd part platform ,portal server and application platform smoothly.

OK,we know good design is the first step to success in daily life,telecom industry is also the same,fortunately ZTE CloudStudio solution is just based on-demand flexbile design,it can provide excellent design portal,it can uniform service provisioning and service assurance.as we can see from the left part,the service provisioning can offer order decomposing,service procedure,resource instance and service activation,in the right part of figure,we can see it can offer complete service assurance,it can collect the data,monitor service,analyze service and excute policy.In the way,make process design,resource design,policy design and assurance design enabling each other.
This is first key point of our cloudstudio solution,agile design ,let's continue to the second key point,automatic deployment.

We can use CloudStudio depoly tool to do E2E integrated deployment,it can finish hardware, virtualization layer, NS and VNF integrated installation and deployment. and most of this deploy procedure can automatic,it can  HW self-detection, SW self-installation, NS self-orchestration, NS self-test.and what's more ,it can customized the deploy procedure according to different scenarios.So here ,I will frankly to say,this is very good tools and by the way,we develop one tools named daizy,not only popular commerical used but also riched the openstack communites' components.Regarding to this point,in the latter slide,we can tough on more details about it.

This is the second key point--automatic deployment,and the third key point is intellgent O&M.
Our solution can also provide Closed-loop Assurance Assists Intelligent O&M,
It can offer powerful O&M assurance ability,it can use the method of centralized monitoring, application management, centralized resource, real-time monitoring, alarm association monitoring and other approaches to improve system assurance ability.
Automated O&M closed-loop,Self-healing closed-loop: detect failure, trigger self-healing policy, automatically restore the problem.
Elastic closed-loop: detect exceptional index, trigger elastic policy, dynamically adjust resource.
Manual O&M Closed-loop,if the failure cannot be automatically restore, the system automatically distributes a work order and intelligently schedule related O&M resource to carry out the manual O&M closed-loop.
In briefly speaking,we use automated O&M way and Manual O&M way to provide closed-loop assurance.

Let's take a more intu'itio'nistic overview.This is Dashboard,which can monitor whole network state,as we can see from this picture,there are many kinds of KPI meter to show the network state.such as,
Global health state evaluation, monitor global VNF and NS state.  
Dashboard display of O&M, resource, alarm, performance, etc.
Multi-layer data association display of physical ,virtual and service layers.
E2E alarm association display across wireless, transport, core network an other networks.

And what's more ,we setup up root cause association analysis based on big data concept and artifical intelligence technology to troubleshooting rapidly.As we known,nowaday,big data concept and artifical intelligence technology are large popular used in the IT areas/Inernet industry,they can grasp the user behavior accurately and offer intellegent operation.
And also,zte reconginzed the importance of big data and AI technology and develop it into CT areas/telecom industry,and bring benefits for operators.
As per the point,I will give you an in-depth presentation/analysis on it,(the main idea just like this/I wanna elaborate this point/elaborate as follows)so how to do it?
Step one, data collecting, collect the datas such as resource usage,alarm logs,performance data from the system.
and then Step two,what should do to this datas,data clean and data analysis ,we have AI based leaning system,online learning,offline learning on all these datas and build a multi-dimensional association cause knowledge database,including horizontal alarm association analysis across wireless, transport and core and vertical association analysis of service/ virtual/ physical resource.
and Step three,run the knowledge database,it can give multi-dimensional association analysis across layer and special network to rapidly find root cause,it is a intellegent O&M.

Ok ,so let's take a summary,CloudStudio solution has three highlights.
can bring significant business benefits,the real benefits to our customers. 
Highlight 1,it can offer agile design,what you see in what you get WYSIWYG design to finish network design in 3 minutes
Extensive template library pre-integrated with thousands of CT and IT APPs and components

Highlight 2,it can offer automated deploy
it can deploy NF/NS in serval minutes and One-key to deploy HW / VIM / MANO /APP automatically.

Highlight 3,it can offer intelligent O&M.
Automated O&M: policy-driven elastic self-healing in seconds
Intelligent analysis: comprehensive monitoring, intelligent RCA.

so let's move to the last part,we will take a glance of zte presens on CloudStudio deployment and experience.
Firstly ,let's show one slide,Actually ,until now ,I will frankly to say,zte is the leader of telecom cloud industry with most abundant   
deployment,so we have more than 360 cases,including commerical projects and Poc cases by the end of 2018Q2,it is the No.1 in the industry.
so in this slide,it show you some main cases by the end of 2018Q2,for example,

In the telecom Arstraulia Velcom Belarus,we have the world's 1st full virualized core network,plus zte Cloudstudio,plus zte TECS and plus zte hardware.

And in the VEON,do you know VEON ,it is a Russian telecom group,we are the solo NFVI provider in 12 countries and vEPC in 9 countries,some 
of them are already commerical used in CIS countries and Ukraine,plus zte cloudstudio and NFVI. 

And in Telefonica, ZTE got the contract of 7 Latin American countries to bulid vIMS  by multinational orchestration, plus our cloudstudio and NFVI for telecom infrasturctures.

And also in China telecom,we provide unified cloud managment to manage all exiting 50 Data Centers,to manage all hardware from different 
vendors,to manage all resources from ZTE ,from VMvare,from Redhat,so it is cloud management systems.

Actually we have some other references,just like the Virtual Messaging and cloudstudio platform in 3 or 4 Orange Group countries and also build the world largest vHLR/vHSS and cloudstudio platform in VEON Bangladesh. 

Ok,so let's come to case studies,this case study is Multi-vendor Integration for the VEON,actually zte already implemented vEPC for VEON grounp in 9 counties,it was already for commerical use and also we got the contract to provide unified NFVI for all the opcos and all application,including the 3rd part apps ,such as Huawei,Nokia and openmind,it is unifed NFVI and deployments.These solution not only including NFVI but also SDN together,it is ,I want to say,in the industry,you can't find another project similar to this project,from scale opint of view and from decouple point of view,so I would to say ,this is a model ,model project in SDN/NFV area.
   
  The second typic case is what we did in Telefonica,actually 2016 we got the contract,from Telefonica,zte was invited to build virtualized IMS to 7 branches of Telefonica in Latin America, zte provided IMS applications and ZTE own TECS Virtulization products,now it is already commerical use and it can offered intelligent automated O&M,reduce workload by 70%.

 And also ,this is one case I should emphasize,that's zte bulid the world's 1st fully-vitulized core network for Velcom,one of Australia Group branch in Belarus,ZTE swapped the leagcy Erisson core network including CS,PS,SDM on top of ZTE virtualized core network in 9 months,so zte provide hardware,TECS,as VIM and hypervise,open stack on top of more than 20 applications,and smooth migration of more than 5.6M subscribers,so I wanna say,this is world's 1st full-virtualized core network,you will never found the 2rd one,so this is very good references.
  
OK ,let's move to the last case ,in Shanghai telecom,so this case is also very typic.Shanghai telecom already has more than 50 data centers,distributed  in all area of Shanghai ,you know,shanghai is a big city with the large population of more than 25M people,so in each different data center,they have different hardware platform from different vendors,such as server from ZTE ,from HP and from huawei,it hard to manage and in Shanghai telecom they also run public cloud business,for cloud connection,cloud security and cloud computing and cloud storage.so in normal case you don't have business enable and self-serice and administration portals,how they do this business,cloud business, they rely on people,normally they need some hours and days to active one cloud services,it is insufficient.
   
So what zte provide to them,zte provide E2E solution,firstly we can manage different hardwares from different vendors,Secondly ,we can manage different resource pool on different vendors,ZTE TECS,VMware,Redhat(redhat I didn't mark here,actually it is there),and also they try to bulid other resource pool.
we put Cloudstudio on top of it,to be unified interfaces.On top of openstack ,we build very big cloud resource management system and big enable system,on the top ,unified interface for all O&M system and business target.So also zte TECS intergartion with exiting shanghai telecom system,for example,OSS system,BSS system,they are all merged together.
   
So how we manage to VMware resource pool,we have adopter API interface,we put openstack TECS in between top with vCenter,intertally we matching between VMware parameters to openstack parameters,so it enable shanghai telecom only need to realize on zte TECS,they don't need VMware vCenter anymore,because in our great interface to recevice all lifecycle management operation system on portal,all bottom is VMware resource,you just run one portal to manage all resource pool,whatever, ZTE ,vmware or redhat.so it makes your O&M more sufficient.

And also,we are not only resoure management but also bring a agile ,automatic pulic enabler in shanghai telecom,to let you have E2E mintue or second level E2E public cloud service action and orchastration ,because of they have different pulic service,such as security,stroage service,so we provide cloud management system for them.

So I will frankly to say,we are the vendor with most abundant telecom cloud deployment experience,we know what the operators really to need and what's kinds of the challenge during all the stages,we can help them to overcome all the challenges.
So many thanks,guys,that's all.
ZTE Cloud Platform Solution
Should we start?ok,let's start,so thank you everybody,my name is Mike,Cloud Core Network Solution manager from ZTE.

Today in my session,I will introduce ZTE cloud platform solution,just tell you ZTE how to bulid one cloud platform for ICT industry,if you allow ,let's continue,if you has any question,pls let me know,ok,so

Let's move to the agenda today,it was devided into four parts,the first part,we will take overview on industry trends,there are two kinds of trends,one trend is telecom service developed,the other is Value of NFV Transformation For Telecom Operators,since having such kinds of trends,how to catch up?so the main part is the second part,zte will give TECS solution to our customers,and then how to use TECS solution build network,zte will give suggestion on Deployment and Evolution ,and at last,we will take a glance of ZTE ICT Transformation Experience in global of the world.

Ok,so let's have a look,the developing trends of Telecom Service Development,first let's review telecom technology,in traditional,telecom network is closed network,sufficent newtork and strictly follow 3GPP standard,the telecom services are all per-defined,in briefly speaking ,it is very sufficent network when facing traditional serivce like 2G/3G voice and internet service,however, with the requirements of service,cost and innvation changed, especially, with large popular using of IOT and OTT serivce,this kind of network has many blocknecks,the network structure should be changed.

This is the first main point,the second main point is NFV technologies polpular used in the IT industry,the main top operators such as Vodafone,T-mobile and AT&T telecom also think to changed their CT network to NFV infrastructure, let's have a look one by one, what they really want to learn from IT area,as we konw,Vodafone is the No.1 telecom operator in global of the world,the most important thing to them is enlarge their business,since the human network serivce has touch the ceiling,so they try to enboarden their serivce in internet of thing area,they learn IT area to decouple software and hardware and deploy their serivce as fast as possible,this idea is very useful for vertical industry. Next one ,T-Mobile operator from Germany,as we konw Germany is one very strictest country,they learn from NFV technogy by software,they want to build telecom service as software market,so T-moblie branches can build their network and service by picking up software from software warehouse,so this is what T-mobile want. And so what AT&T want to do,
they are very radical,they want to remove their CT genes and totally accept IT genes,they even change their organizational structure to follow IT area,
by the way ,they already changed their edge network and access area to NFV structure.
so we can see,the main top operators already try to their network common infrastructure,agile and more open.

let's continue to have a look, Construction Strategy for CT Cloud and IT Cloud in operators in global of the world,it is the current consensus of mainstream operators to construct CT cloud and IT cloud respectively by Y2020,and then ,as the business mode becomes more clear,it will combo CT and IT cloud around Y2025.As we can see,from the figure,the main stream operators such as Orange,AT&T,Vodafone,T-mobile,Telefonica will construct CT cloud independently, guided by the core network planning department.

Since there are a lot of telecom developing trends ,how to catch up them, and what's kind of solution our ZTE,as a mainstream provider,can offer,so let's continue the second part,zte TECS solution.

In our zte solution,we think that,firstly ,our TECS solution must follow ETSI NFV standards and provides NFVI and VIM functionality in NFV architecture,as we can see from the figure,The NFVI layer including TECS Compute/TECS Storage/TECS Network component, mainly implements virtualization of computing resources, storage resources, and network resources.The VIM layer including TECS Director + TECS OpenStack + TECS OpenPalette,mainly implements unified management of infrastructure resources,in the latter slice,we will touch on more details about them.

In this slide,just show you TECS system architecture,totally divided six parts,firstly,TECS Director:
The main function is offering Unified management platform for distributed DCs/O&M, Cross-DC management
then, TECS OpenStack:Enhancement upon OpenStack/Infrastructure management
TECS OpenPalette：Carrier-grade enhancement upon Kubernetes/Container management
TECS Compute:Compute virtualization, using KVM as Hypervisor，using Docker as container.
TECS Network:Network virtualization, providing OVS and VEG/Cooperating with SDN Controller to provide a  complete SDN solution
TECS Storage:Storage virtualization, supporting the CEPH-based solution.

Let's take more details, TECS Director Software Architecture,as we can see from this slide,it can offers unified portal,user-self portal and administrator portal,it can provide maintenance management,such as serivce catalog,service mgt,service measurement and so on,it also supply operation mgt,just like configuration mgt,report mgt and so on.In the bottom layer--resource management domain,it can provide resource mgt,manage the resources such as VM, Container and Bare Metal.

Let's continue another architecture,TECS OpenPalette Software Architecture,this is ZTE self-defined layer and product,in our openpalette product,we provide container engine and container orchestration to enhace the compute,the storage and the network layer. and what's more ,we defined Container as a service in Paas platform to enhace high performance and telecom network.

Next slide,just show you TECS OpenStack Software Architecture,it can offer excution services,Execution Services are mainly composed by native components of OpenStack.it also can provide operation services, To meet with the Telecom-level service requirements, components related with hardware management, management portal, alarm, performance processing and reliability functions have been added.

Next,TECS Storage Software Architecture,it can provide
Performance acceleration: Memory management and thread scheduling optimization
Data recovery: Configurable data recovery policy
Block interface enhancement: Support standard FC/iSCSI protocol
File interface enhancement: Support standard NFS/CIFS protocol
Object interface enhancement:  Supplement S3 protocol interface
Deployment enhancement: Shorter cluster deployment time; online expansion and upgrade.
Visual O&M: Visual HW resource; log management,  alarm customization and report, performance statistic, and other supplementary functions.

In the upper slides,we we introduced TECS Director / TECS OpenPalette/ TECS OpenStack and TECS storage,we can make a conclusion,This is CT area learned from IT area and  enhanced function over IT area ,so we can say Technologies are unbounded, Applications are different.since IT is Horizontal, centralized architecture bearing compute/storage-intensive services, pursuing scale effect and low cost.
while CT is Layered, distributed architecture bearing network-intensive services, pursuing high performance, high reliability and flexible orchestration.
With the experience of CT, a deep understanding of how virtualization can better support CT services is the key to NFV system integration.

OpenStack needs continuous enhancement to meet the carrier-level requirements of NFV. Open-source versions usually lag behind the development needs of telecom services.so in our solution, ZTE implements telecom enhancements in advance,now the latest version is queen version and ZTE also offer TECS 6.10 version to catch up the newest technology and Providing the CT Enhanced-Features In Advance.

This slide just show you TECS telecom enhanced features,ZTE enhanced the features including but not limit to performance,deployment,security,reliability,O&M and fuction,we just need take a overview ,the telecom enhancement feature is indispensable for telecom services.

So we can make a conclusion about zte distributed cloud solution,the first highlight is high speed,software acceleration and hardware acceleration,the second highlight is integration,cloud and network synergy,resource integration,and heterogeneous cloud unified mgt.the third highlight is intelligent,it can offer automation O&M,intelligent root cause analysis based on big data and AI technology.

This is second part,mainly introduce zte TECS solution,zte can provide enhanced telecom virtulization products based on openstack.so in current,how to use virtulization infrastructure to deploy the network.
let's continue the third part,
Suggestions on Deployment and Evolution
The first deployment is Multi-Level DC Architecture,normally we divided network into Edge DC,regional DC and Core DC,each DC depoly different plane,for example,Edge DC is used for distributed on the user plane/media plane to acheieve fast offloading of traffic, while regional DC and Core DC fous on the control plane,management plane VNFs and the centralized media plane VNFs.

The second deployment is Technical Verification for Virtual Layer Construction,in this slide,the main idea is technical line,for 5G,introdcing and verfying technologies such as SDN and CEPH and container. for construction route,from core to edge,from control to forwarding.

The third deployment is Deployment: Separate Construction of CT Cloud and IT Cloud,as we discussed this item in the upper slides,On the one hand, it is the current consensus of mainstream operators to construct CT cloud and IT cloud respectively by Y2020,On the other hand,Main cause of separate construction is the necessary telecom enhancement for CT cloud.

The last deployment is Deployment: Cloud Network Synergy.we need build one network support SDN and NFV,it is Visual O&M of large-scale networks,and integrate mutli-DC resource pool and DCI,Micro-segmentation + security domain to achieve unified automation of border security.

Another key word is Evolution: Evolution Route of Telecom Cloud Resource Pool,the roadmap just like this,before Y 2018,it designed as 3-layer architecture,2-layer decopling,and then by Y2019,it will realize 3-layer decoupling gradually ,and when Y2020,it uses microservice paas platform,and beyond Y2020,IT cloud and CT cloud will integated each other.

The second Evolution: Containers are More Suitable for Business Innovations,as we know nowadays,the concept of container is popular use in CT area,becaues of its advantages of more lightweight,more rapid and more portability,ZTE also know such kind of advantage and use containers technology in CT area to innovate the business mode.

The third Evolution: Value of CEPH Distributed Storage in NFVI,in current,CEPH storage is popuar distributed storage technology in NFVI,it can provide Universal server + software defined to guarantee the integration of multiple DC resources,Multiple data security protection mechanisms and ICT universal resource pools.so it can bring significant benefit for storage.

The fourth Evolution: Convergent Evolution Path of CT Cloud and IT Cloud,regarding to this point,we gave details in upper slide,so I don't touch on more details here.

The fivth Evolution: Unified Cloud Management, Full Integration of Resources,
Unified Management:VM, container and bare metal/Heterogeneous resource pool/Private cloud, public cloud and hybrid cloud
Unified Orchestration:Multi-resource orchestration/Heterogeneous pool orchestration/Cross-DC unified orchestration
Unified Operation:Unified service catalog and self-service portal  for IaaS and PaaS  (interface integration, custom development)/Unified authentication, single sign-on.

So in this part,we suggest different deployment mode and evolution path, 

so let's move to the last part,ZTE ICT Transformation Experience,we will take a glance of zte experience on cloud infrasturcture deployment and experience.
Firstly ,let's show one slide,actually ,until now ,I will frankly to say,zte is the leader of telecom cloud industry with the most abundant deployment,we have  more than 360 cases,including commerical projects and Poc cases by the end of 2017,it is the No.1 in the industry.
so in this slide,it show you some main cases,for example,

In the telecom Arstraulia Velcom Belarus,we have the world's 1st full virualized core network,plus zte TECS,plus zte hardware.

And in the VEON,do you know VEON ,it is a Russian telecom group,we are the solo NFVI provider in 12 countries and vEPC in 9 countries,some of them are already commerical used in CIS countries and Ukraine. 

And in Telefonica, ZTE got the contract of 7 Latin American countries to bulid mutli-tenancy vIMS for VoLTE,and also ZTE NFVI for telecom infrasturctures.

And also in China telecom,we provide unified cloud managment to manage all exiting 50 Data Centers,to manage all hardware from different vendors,to manage all resources from ZTE ,from VMvare,from Redhat,so it is cloud management systems.

Actually we have some other references,just like the Virtual Messaging platform in 3 or 4 Orange Group countries and also build the world largest vHLR/vHSS and NFVI platform in VEON Bangladesh. 

I wouldn't emphaize one by one ,in the later slides,I will elabrate some sectional details.

 Ok,so let's come to case studies/overview,this case study is Multi-National Cloud Infrastructure For VEON,actually zte already implemented NFVI for VEON grounp in 12 counties,
some of them are already for commerical use and also we got the contract to provide unified NFVI for all the opcos and all application,including the 3rd part apps ,such as Huawei,Nokia and openmind,it is unifed NFVI and deployments.These solution not only including NFVI but also SDN together,it is ,I want to say,in the industry,you can't find another project similar to this project,from scale opint of view and from decouple point of view,so I would to say ,this is a model ,model project in SDN/NFV area.

And another typical case is shanghai telecom,it is zte cloud management platform for Shanghai telecom in China,so actually Shanghai telecom has more than 50 data centers,distributed in the different area of Shanghai,and in each different data center,they have different hardware platform from different vendors,such as server from ZTE ,from HP and from huawei,the stroage from HP,EMC and firewall from the Juniper,Cisco,they have a lot of hardware platform,and each data center has different virtualized technologies,for example ,ZTE TECS,VMware,KVM,XEN and redhat,so how to realize unified management for all these different kinds of virtulized technologies,it is challenge for Shanghai telecom,so zte provide unified cloud management system to manage all these hardware and software.

 And also we got a lot of industry awards and high evaluation from different researches,for example ,from IDC ,Ovum and global data to show zte NFVI    
rated very strong, we are the leading player and got the best core network produce in 5G world awards 2016 and praise from IMS world forum for Rich   
communications ,and telecomasia for NFV innovation.      
actually to say,our zte cloud based on infrastructure solution are widly reconginzed by the whole industry.

So here I say some contribution, just take a glance.ZTE plays very important role in different open source communities,we are the driver of devepment of open sources communities,so we are platinum members of ONAP,OPFNV and Open daylight,and we are the gold members of openstack,cloud native and DPDK, and we are also the silver members and leading contirbutor members of different kinds of open source communities.So something I would like to emphaize that is in the open stack ,in the latest verion Queen, our contribution ranks to Top 8,and in ONAP,OPNFV,CEPH,Openshift and OVS ,our contribution ranks to Top 2,and also in kubernetes ,our contribution ranks to Top 5,so we can say we are the main contirbutor and leader position of open source communities.

We can open SDN/NFV Joint Lab, Foster Industry Ecosystem,we build a complete test environment: CN/RAN/BN/Service,we have some Contribution to OPNFV open source projects and we have four R&D research centers for virtulaztion platform in Nanjing,Shenzhen,shanghai in china and Dusseldorf in Germany.

So the last slide,the last sentence I will make summarize today,that is due to zte has a lot of NFV /SDN experience in the CT area,I will say,we are the vendor with most abundant telecom cloud deployment experience,untill now we have more than 1200 deploment cases,from planning&design stages,integration stages,installaion&deployment stages to O&M stages,we know what the operators really to need and what's kinds of the challenge during all the stages,we can help them to overcome all the challenges.
 So many thanks,guys,that's all.
ZTE Cloud Platform Solution
Should we start?ok,let's start,so thank you everybody,my name is Mike,Cloud Core Network Solution manager from ZTE.

Today in my session,I will introduce ZTE cloud platform solution,just tell you ZTE how to bulid one cloud platform for ICT industry,if you allow ,let's continue,if you has any question,pls let me know,ok,so

Let's move to the agenda today,it was devided into four parts,the first part,we will take overview on industry trends,there are two kinds of trends,one trend is telecom service developed,the other is Value of NFV Transformation For Telecom Operators,since having such kinds of trends,how to catch up?so the main part is the second part,zte will give TECS solution to our customers,and then how to use TECS solution build network,zte will give suggestion on Deployment and Evolution ,and at last,we will take a glance of ZTE ICT Transformation Experience in global of the world.

Ok,so let's have a look,the developing trends of Telecom Service Development,first let's review telecom technology,in traditional,telecom network is closed network,sufficent newtork and strictly follow 3GPP standard,the telecom services are all per-defined,in briefly speaking ,it is very sufficent network when facing traditional serivce like 2G/3G voice and internet service,however, with the requirements of service,cost and innvation changed, especially, with large popular using of IOT and OTT serivce,this kind of network has many blocknecks,the network structure should be changed.

This is the first main point,the second main point is NFV technologies polpular used in the IT industry,the main top operators such as Vodafone,T-mobile and AT&T telecom also think to changed their CT network to NFV infrastructure, let's have a look one by one, what they really want to learn from IT area,as we konw,Vodafone is the No.1 telecom operator in global of the world,the most important thing to them is enlarge their business,since the human network serivce has touch the ceiling,so they try to enboarden their serivce in internet of thing area,they learn IT area to decouple software and hardware and deploy their serivce as fast as possible,this idea is very useful for vertical industry. Next one ,T-Mobile operator from Germany,as we konw Germany is one very strictest country,they learn from NFV technogy by software,they want to build telecom service as software market,so T-moblie branches can build their network and service by picking up software from software warehouse,so this is what T-mobile want. And so what AT&T want to do,
they are very radical,they want to remove their CT genes and totally accept IT genes,they even change their organizational structure to follow IT area,
by the way ,they already changed their edge network and access area to NFV structure.
so we can see,the main top operators already try to their network common infrastructure,agile and more open.

let's continue to have a look, Construction Strategy for CT Cloud and IT Cloud in operators in global of the world,it is the current consensus of mainstream operators to construct CT cloud and IT cloud respectively by Y2020,and then ,as the business mode becomes more clear,it will combo CT and IT cloud around Y2025.As we can see,from the figure,the main stream operators such as Orange,AT&T,Vodafone,T-mobile,Telefonica will construct CT cloud independently, guided by the core network planning department.

Since there are a lot of telecom developing trends ,how to catch up them, and what's kind of solution our ZTE,as a mainstream provider,can offer,so let's continue the second part,zte TECS solution.

In our zte solution,we think that,firstly ,our TECS solution must follow ETSI NFV standards and provides NFVI and VIM functionality in NFV architecture,as we can see from the figure,The NFVI layer including TECS Compute/TECS Storage/TECS Network component, mainly implements virtualization of computing resources, storage resources, and network resources.The VIM layer including TECS Director + TECS OpenStack + TECS OpenPalette,mainly implements unified management of infrastructure resources,in the latter slice,we will touch on more details about them.

In this slide,just show you TECS system architecture,totally divided six parts,firstly,TECS Director:
The main function is offering Unified management platform for distributed DCs/O&M, Cross-DC management
then, TECS OpenStack:Enhancement upon OpenStack/Infrastructure management
TECS OpenPalette：Carrier-grade enhancement upon Kubernetes/Container management
TECS Compute:Compute virtualization, using KVM as Hypervisor，using Docker as container.
TECS Network:Network virtualization, providing OVS and VEG/Cooperating with SDN Controller to provide a  complete SDN solution
TECS Storage:Storage virtualization, supporting the CEPH-based solution.

Let's take more details, TECS Director Software Architecture,as we can see from this slide,it can offers unified portal,user-self portal and administrator portal,it can provide maintenance management,such as serivce catalog,service mgt,service measurement and so on,it also supply operation mgt,just like configuration mgt,report mgt and so on.In the bottom layer--resource management domain,it can provide resource mgt,manage the resources such as VM, Container and Bare Metal.

Let's continue another architecture,TECS OpenPalette Software Architecture,this is ZTE self-defined layer and product,in our openpalette product,we provide container engine and container orchestration to enhace the compute,the storage and the network layer. and what's more ,we defined Container as a service in Paas platform to enhace high performance and telecom network.

Next slide,just show you TECS OpenStack Software Architecture,it can offer excution services,Execution Services are mainly composed by native components of OpenStack.it also can provide operation services, To meet with the Telecom-level service requirements, components related with hardware management, management portal, alarm, performance processing and reliability functions have been added.

Next,TECS Storage Software Architecture,it can provide
Performance acceleration: Memory management and thread scheduling optimization
Data recovery: Configurable data recovery policy
Block interface enhancement: Support standard FC/iSCSI protocol
File interface enhancement: Support standard NFS/CIFS protocol
Object interface enhancement:  Supplement S3 protocol interface
Deployment enhancement: Shorter cluster deployment time; online expansion and upgrade.
Visual O&M: Visual HW resource; log management,  alarm customization and report, performance statistic, and other supplementary functions.

In the upper slides,we we introduced TECS Director / TECS OpenPalette/ TECS OpenStack and TECS storage,we can make a conclusion,This is CT area learned from IT area and  enhanced function over IT area ,so we can say Technologies are unbounded, Applications are different.since IT is Horizontal, centralized architecture bearing compute/storage-intensive services, pursuing scale effect and low cost.
while CT is Layered, distributed architecture bearing network-intensive services, pursuing high performance, high reliability and flexible orchestration.
With the experience of CT, a deep understanding of how virtualization can better support CT services is the key to NFV system integration.

OpenStack needs continuous enhancement to meet the carrier-level requirements of NFV. Open-source versions usually lag behind the development needs of telecom services.so in our solution, ZTE implements telecom enhancements in advance,now the latest version is queen version and ZTE also offer TECS 6.10 version to catch up the newest technology and Providing the CT Enhanced-Features In Advance.

This slide just show you TECS telecom enhanced features,ZTE enhanced the features including but not limit to performance,deployment,security,reliability,O&M and fuction,we just need take a overview ,the telecom enhancement feature is indispensable for telecom services.

So we can make a conclusion about zte distributed cloud solution,the first highlight is high speed,software acceleration and hardware acceleration,the second highlight is integration,cloud and network synergy,resource integration,and heterogeneous cloud unified mgt.the third highlight is intelligent,it can offer automation O&M,intelligent root cause analysis based on big data and AI technology.

This is second part,mainly introduce zte TECS solution,zte can provide enhanced telecom virtulization products based on openstack.so in current,how to use virtulization infrastructure to deploy the network.
let's continue the third part,
Suggestions on Deployment and Evolution
The first deployment is Multi-Level DC Architecture,normally we divided network into Edge DC,regional DC and Core DC,each DC depoly different plane,for example,Edge DC is used for distributed on the user plane/media plane to acheieve fast offloading of traffic, while regional DC and Core DC fous on the control plane,management plane VNFs and the centralized media plane VNFs.

The second deployment is Technical Verification for Virtual Layer Construction,in this slide,the main idea is technical line,for 5G,introdcing and verfying technologies such as SDN and CEPH and container. for construction route,from core to edge,from control to forwarding.

The third deployment is Deployment: Separate Construction of CT Cloud and IT Cloud,as we discussed this item in the upper slides,On the one hand, it is the current consensus of mainstream operators to construct CT cloud and IT cloud respectively by Y2020,On the other hand,Main cause of separate construction is the necessary telecom enhancement for CT cloud.

The last deployment is Deployment: Cloud Network Synergy.we need build one network support SDN and NFV,it is Visual O&M of large-scale networks,and integrate mutli-DC resource pool and DCI,Micro-segmentation + security domain to achieve unified automation of border security.

Another key word is Evolution: Evolution Route of Telecom Cloud Resource Pool,the roadmap just like this,before Y 2018,it designed as 3-layer architecture,2-layer decopling,and then by Y2019,it will realize 3-layer decoupling gradually ,and when Y2020,it uses microservice paas platform,and beyond Y2020,IT cloud and CT cloud will integated each other.

The second Evolution: Containers are More Suitable for Business Innovations,as we know nowadays,the concept of container is popular use in CT area,becaues of its advantages of more lightweight,more rapid and more portability,ZTE also know such kind of advantage and use containers technology in CT area to innovate the business mode.

The third Evolution: Value of CEPH Distributed Storage in NFVI,in current,CEPH storage is popuar distributed storage technology in NFVI,it can provide Universal server + software defined to guarantee the integration of multiple DC resources,Multiple data security protection mechanisms and ICT universal resource pools.so it can bring significant benefit for storage.

The fourth Evolution: Convergent Evolution Path of CT Cloud and IT Cloud,regarding to this point,we gave details in upper slide,so I don't touch on more details here.

The fivth Evolution: Unified Cloud Management, Full Integration of Resources,
Unified Management:VM, container and bare metal/Heterogeneous resource pool/Private cloud, public cloud and hybrid cloud
Unified Orchestration:Multi-resource orchestration/Heterogeneous pool orchestration/Cross-DC unified orchestration
Unified Operation:Unified service catalog and self-service portal  for IaaS and PaaS  (interface integration, custom development)/Unified authentication, single sign-on.

So in this part,we suggest different deployment mode and evolution path, 

so let's move to the last part,ZTE ICT Transformation Experience,we will take a glance of zte experience on cloud infrasturcture deployment and experience.
Firstly ,let's show one slide,actually ,until now ,I will frankly to say,zte is the leader of telecom cloud industry with the most abundant deployment,we have  more than 360 cases,including commerical projects and Poc cases by the end of 2017,it is the No.1 in the industry.
so in this slide,it show you some main cases,for example,

In the telecom Arstraulia Velcom Belarus,we have the world's 1st full virualized core network,plus zte TECS,plus zte hardware.

And in the VEON,do you know VEON ,it is a Russian telecom group,we are the solo NFVI provider in 12 countries and vEPC in 9 countries,some of them are already commerical used in CIS countries and Ukraine. 

And in Telefonica, ZTE got the contract of 7 Latin American countries to bulid mutli-tenancy vIMS for VoLTE,and also ZTE NFVI for telecom infrasturctures.

And also in China telecom,we provide unified cloud managment to manage all exiting 50 Data Centers,to manage all hardware from different vendors,to manage all resources from ZTE ,from VMvare,from Redhat,so it is cloud management systems.

Actually we have some other references,just like the Virtual Messaging platform in 3 or 4 Orange Group countries and also build the world largest vHLR/vHSS and NFVI platform in VEON Bangladesh. 

I wouldn't emphaize one by one ,in the later slides,I will elabrate some sectional details.

 Ok,so let's come to case studies/overview,this case study is Multi-National Cloud Infrastructure For VEON,actually zte already implemented NFVI for VEON grounp in 12 counties,
some of them are already for commerical use and also we got the contract to provide unified NFVI for all the opcos and all application,including the 3rd part apps ,such as Huawei,Nokia and openmind,it is unifed NFVI and deployments.These solution not only including NFVI but also SDN together,it is ,I want to say,in the industry,you can't find another project similar to this project,from scale opint of view and from decouple point of view,so I would to say ,this is a model ,model project in SDN/NFV area.

And another typical case is shanghai telecom,it is zte cloud management platform for Shanghai telecom in China,so actually Shanghai telecom has more than 50 data centers,distributed in the different area of Shanghai,and in each different data center,they have different hardware platform from different vendors,such as server from ZTE ,from HP and from huawei,the stroage from HP,EMC and firewall from the Juniper,Cisco,they have a lot of hardware platform,and each data center has different virtualized technologies,for example ,ZTE TECS,VMware,KVM,XEN and redhat,so how to realize unified management for all these different kinds of virtulized technologies,it is challenge for Shanghai telecom,so zte provide unified cloud management system to manage all these hardware and software.

 And also we got a lot of industry awards and high evaluation from different researches,for example ,from IDC ,Ovum and global data to show zte NFVI    
rated very strong, we are the leading player and got the best core network produce in 5G world awards 2016 and praise from IMS world forum for Rich   
communications ,and telecomasia for NFV innovation.      
actually to say,our zte cloud based on infrastructure solution are widly reconginzed by the whole industry.

So here I say some contribution, just take a glance.ZTE plays very important role in different open source communities,we are the driver of devepment of open sources communities,so we are platinum members of ONAP,OPFNV and Open daylight,and we are the gold members of openstack,cloud native and DPDK, and we are also the silver members and leading contirbutor members of different kinds of open source communities.So something I would like to emphaize that is in the open stack ,in the latest verion Queen, our contribution ranks to Top 8,and in ONAP,OPNFV,CEPH,Openshift and OVS ,our contribution ranks to Top 2,and also in kubernetes ,our contribution ranks to Top 5,so we can say we are the main contirbutor and leader position of open source communities.

We can open SDN/NFV Joint Lab, Foster Industry Ecosystem,we build a complete test environment: CN/RAN/BN/Service,we have some Contribution to OPNFV open source projects and we have four R&D research centers for virtulaztion platform in Nanjing,Shenzhen,shanghai in china and Dusseldorf in Germany.

So the last slide,the last sentence I will make summarize today,that is due to zte has a lot of NFV /SDN experience in the CT area,I will say,we are the vendor with most abundant telecom cloud deployment experience,untill now we have more than 1200 deploment cases,from planning&design stages,integration stages,installaion&deployment stages to O&M stages,we know what the operators really to need and what's kinds of the challenge during all the stages,we can help them to overcome all the challenges.
 So many thanks,guys,that's all.

