
# Documentação da API SCAC v2.1.63

## 📑 Índice Clicável
- [1. Visão Geral](#1-visão-geral)
- [2. Autenticação](#2-autenticação)
- [3. Recursos da API](#3-recursos-da-api)
  - [3.1 Abertura/Fechamento](#31-aberturafechamento)
  - [3.2 Testes de Hardware](#32-testes-de-hardware)
  - [3.3 Sincronização de Dados](#33-sincronização-de-dados)
  - [3.4 Autenticação por PIN](#34-autenticação-por-pin)
  - [3.5 Biometria](#35-biometria)
  - [3.6 PIN na Controladora](#36-pin-na-controladora)
  - [3.7 Custódia](#37-custódia)
  - [3.8 Notificações](#38-notificações)
  - [3.9 Healthcheck](#39-healthcheck)
  - [3.10 Abertura/Fechamento Remoto](#310-aberturafechamento-remoto)
  - [3.11 Vigilantes](#311-vigilantes)
- [4. Esquemas de Dados](#4-esquemas-de-dados)
- [5. Formatos de Resposta](#5-formatos-de-resposta)
- [6. Exemplo de Fluxo de Uso](#6-exemplo-de-fluxo-de-uso)
- [7. Considerações Finais](#7-considerações-finais)

PK    dZR       [Content_Types].xmlMO@/> {Cp(p,D8Y/L:UP.}۲=|&[CD]]W"|ݢ.f7E!IH|60:_BZX 'VƅR=7#pTR'+hPvw"CE.&Vk
8`UF`sv+rgUqxom.wW3SZjok&Wn;V+hZYT}iHzC)'!]2|)$>؈^MmU5U?RA397qC"}[9DN}D_=(@{aHuۂcL,)[a{D>ק?"M^ PK    dZy&K@        _rels/.relsJ1>E%nUD^DM>n~HھQD]Xcf֛+lWbYՂX)_	!xTYl#@e&6fV >+[)ABD_*mHt(Wu}-ooFL5lw?tH`@pSNd18IqCIώPh[.COS^x$ͼ8g<ѸG-$#WzfuރQp0Z}[6PK    dZSi       docProps/core.xmlN0E|EMVEI*JHع45Ml˞6mZ+v;p>7cdYbE*9&g:cQ
I1]Lֈ:#Ĳ54Ԇ!RBSMنV@(# )遁# aL^ث	rlvZO[1۶tc1~ZG`Re(2v3@QRwV2srqv]@[voĥ-s%?td38'a~ݡw=g	i1IAIH,͢G+7g^)wCPK    dZ  l     docProps/app.xmlTn0+]tiAQAC"J1~}9/;;AfNhUPq
"sV]q_ʭ-	tWP{"bpsO+t@޴{Np|e@EvPޘQ0Ohy=5GYFa3yi(وFM 1`hj{tdgm[<#@,p
c@~Fp(  SW퐿XAǠ95C(#jaoXq;K;BD*CZo78X杰@iٺ$}>E˰J.!='$b+c)WCZ]N[5v%~o'k=PGvZh.m1u=w8~		lɌlߗ>W$;U{lOI?OG//	PK    dZ/.S"       word/document.xmlVMo1WX\H""ʡ*i]+BSSxwYHS$\=ymkFC/h.B&YM2H>l?pӾXb`EΥ% `ذZoXsj\0c\
5aPΔƍt*WԴjC)N;AǵsF%Z\#}SQ+"aEj*g3@Um%ߊh=l#!$Z򒞯yATnoEtb{ŮU;WqB?b2bDBi-÷~4&i{P;4qڍo!xVݣqd)Uxr6I$hȐ*N܉luZ@FUt9Czٰu+l[o;^$d<!xBV/eT5D/¸ki_.\	H9|j4i[S΅ՔFAs	@c1V(ͣ	b^	s3zwy޿y?q<wʸNQTv 6 #0@0Ә{&<ڹD4"66ƩT״\sI O`ՠVE5R-O(0Y#jT׳ïi4n/?[A0D4DAԝls*^FQ3v:y8y%o<{IHa?(vƗ{)f#N\ؽeRrYcU>??d9l!LX,QPJrZ=ePK    dZn2       word/_rels/document.xml.relsAO0
n&*F|FڒC[d,C6}'mS;+J8ӅPe<gHUAk 	:6<BMhJM
%Ĳ
$n@FS7ZYDђatz"ͮk?ݚsNV`]#5%`d^
fCM\_V3`ifc DwCC2S3A8%Skk8jєzN	t{?>9XkQWG= 'msڨV`K8ѯ9/PK    dZ;ٚx/  3U    word/styles.xml]]F}_m n va{3M3h_%!@URUVJ;P)WTel~_7ÿ[Vo~|;xZn?o?]ջy<mޅ/~^燗뷫yl7?O9iZ{zw?pXoxh_~>g~ٞ{YnvaNa??>LrGPǇ_/w}8?B=Wm{:F~>$&wjJxلc펛x7~r-z9z#)uyy?DB/ܾ˕1m}\[CfRq/~E|H!įb&tZ~%t	?~yT|;!:χ?_}Y?}8/eft\~ټ<=w77O}^~=nľڿNۏoZF[F6)6z1%'v79&bIy^/V
Ja1RUb>D})|~uvi'
^TT~#(D'
P+?Qo'
,j]H>nNue*$<,?wZR2Ǔحn}cYjbqsaT)jęg]pqI?>QF]s4+Wx(U%OjЈk+E8@Da2#Xe|oW/iX:vm+|!A|_(I#8>fUDT!JHQHR3,+!K-JN/Vʼ֬1QlZ,i;Ĥي13IXm6JR
%Dq!ꓣ,YRBt)!g_yS@
ڼ) mެHR#+p ];%oY8[@N-B%oYh[@N$oA8[@N%./yIp 4 $o)h[@Z$oA8[@N'j!x[@N$Q#[@
Bd%oY8[@N$oA8[@zd$oA8[@NvIR- -yIp - 'yIԓw- 'yIsCv^:DZ Vu}YZֻJ
E'x[msDXql,=.[u]n{Avhx[ӟx>Oɢ?]Dn.@\5pC-y`,ܩߕlJmeV"=z>_%>.C{Ǻfr<y|;v<ydCixLy_{|;$I." u}v.6l3spq
հ\%z;/"	/C,JEx`?17G"o&8MAʐ{St/PR')u68ٗPB~?p&w\&~oS[xߒыOvGo]h](Ʈ4v94h-5M.WR'\oI'YZ9WyʹF8Ls\yWr"u%ӕlC]+):uI'11m}g6A#0=hr񠌗XbC o\߸~voFMIiދ\/czѸ^E {)͇>n6Esp]hBnXR\ ҔKSL_v×&b:rLI&wAN{!܇ߧN=-wJlRUív6)?nE5w卋v+`xq:_7p}wo/CM!FQM?/m7ty=rߠ]'~ kik[T%lB257V-4]jNɜv	%;y{b`x2`= !FGE8<IE߲j?+MDs="Y˾-̫&ϸpN]Dwnq'Jn%.rob	._/7Gc:jbIE߇L+YX潾.f,ZmE=ʷ^g
Xa`7dՌ;42;#J}k7j^U*(Zv AQ"Z_?ez3qsGMe8啳Лx%Yٙ'*E5jO!P3שz	ʗaUuOX7,gjRSU/6c=B}aȨ9k.&> ʜ9󥊷My=uǝFg,֤zn[n0BFIgN"=p0iowkͪJ|}k֥N_l<تQ'*U4lUu{N&tè=pbaM]{	mFHTQktb\*x[j"e><5'V./7-bjLV'nji:r1t\KJG]?BT`l uw4NX;ƗCxS	cr3S']x~ꊯo͙Tە^uįn>*EӾզ:فw>%ժ#5Y<RYZR|'1EQdLz[|ļ.y<78ɮ+\(iQGHVuo͒[j;vnl&;IKK-9F&iI'Hftl6ԞS${N`O7|	"9>oPXX4bOu୬#Y
!clt3/%", %M+X6hRk$FIQv!{x,F!-`׵ASkM٩7ލ9m=ffn:f;Quf2ooGU`,A*c\=>+'\- ӭ)4ǟnoPՓ114G3̭V|}l++LQQpTqe5jdߋK
Y:nG !/)6q@7R+AEDg0Un|yQ*-:c]tmRh4(eq.}~۔)>:(9%uL4JN˚.7/3W㤣3f*Η^3~G8<>8kŷ%510npЧx
{t%4VɕUvmmKWQ\[CF-=1vIVU`4c畋g_}j^&fj %kڋ\eIWfΒrN)D>Ds1f&ZEʀشmvE,Kh^9h3PX[荽Ns6ulvxu	|)Izq9^@7,7c6;Ij_k>7kԲdw	Mh{PpЛs7e	N\FLpbga*Hf7ۚQL3v:&יY'a	8x/ YЛ1?a'sUAm$F&7{8qsv7g>[,\ރx射touT,BodYBo˟\9SACoͷŀS{`<uNu	rXBo:ހ6"F%f8	<*sfHE`Z	}utGUR;mR4r$%~\|>Lɠ%t)r6MoMf]
sHь+IEY6A؊)9SӪ=лi
KmΪV}FBO(=\^KC
I^x&]Jл멅MQoΪ}FBO=\^KC
I^xB}6nzjEԛjuEQ/P9DlzyҨ؈PjZ&u欚mgK/ziåEd;$۩^^O47"ԫEPu=j7gl>^
x'Ks.U^TP/ViU퇣w3-S.ޜU-fz)P/!zTld;i扃v㗠 @.5(3uPG% .(~w:FWH_BDC1;nZsF'WS|Ib͌!kvWfhQ@},ƨi6GSSmIW:nnZ3#LnE~M?CU[ޢowo2*'<dRX*ab.V˨&0Cv~е8F=
&Zjke;"g{_Gi|UW#(ϧT,؜

*
+.&G7KxU=DNE@:{!;?ZD" _@'he;xi|UW$(NIP`s/0*(<dAT09E@][Q,TT,T1i|v)ȸ#gL_մH*+isuy	X9N$0*(<daT09E@][Q9uTT,T1i|v(x7'בhjZ$his4:E@YT,nGWv>-MEPVlV㱽TT	a<P8PPdYi[$IN c ۉ6pE@V>WcO@9=|"+P~LE@" ]-0*(<d
ME=̍nnPVz')T1i|v(x邌i|UW$0?6o/O>|p.e5n%Avhs
ںP]Z
.-~PRU*i(b ɫqa}%(G^q#W'%)5[_V!CUUAx1~%o(i5OdyB59,R R`=kHL9"V_
_l'2 cF`?]7ىZ<?~XL!.|ikM!) r GpD,+,"Ȭ90{eY9N,FJ`٫%)c1c^,&N6B r SD"CNdr3e3!G7щ{cS,F3d1ţx,~ B6ٜSqЦЁ 9(b@,F^v".;Y"{HY9N,F#ZQסIZ=<?XLq}d1v6M!)E 9E 1}1҂tPdɶ6M3!G7щ{FS,FSd1x,~bǹ|0dCm
Huȁc -XLWXEf;Yv}3!G7щ4WjXL~f~{ZQ`Y#$7A2ͻI1R	?v:TxȬ*s&CֶlŴKW+u\~&oIVHut\R:3BNq_c&-6mZJYle^bX'ig-%I 8~W_l+'I8gRdm`hX'i8g-%I 8~W朕-9sZJlM93zE9svdOʜ( K( 9sv-%ILc'Ήe|ƙ=^s֢Z92s{eYyp~pqN9d61<8'sg2x%Yjs6 Ω9g119sZJu@93vE9svdO͑߬6zQArr\ġ-Ӯ3yTCTYlbCߝWݿ,?QI\iv,/ɵOifk/0^5ztIE9^h-o0}ڸQ j]	\Rva]9,ÁEڌ>I<|Yު,Rx#e%$׌1<+%Xb8,paIgXb`={SijV`	f{m,%~]X!^9,aKڌ>K\F̹`ު,vdx;6%$%<+%Xb8,paIgXb	_|G`	꭪nӞ,,w!X$?#xWKpX"dnÒ6cϰ@˟٥{`ު,uxS%$14.<+%Xb8,paIgXb`IrG`	`IRW
WQtS/_^߽=3
J☽,Xo}ؠA*9VӣMw,g ZQLOuwW_5=p#l>Vx-	B{!% %,?뵵Cv+ j&k~aSL2iDlg'hSUG]p~_IZ
"i_!&A~kcwA4MC:idMӈ	T7NӤ4>MӴD4D{eY꽲u	4=%fM5ЩN&D4i3U4驪.o:Mko4vMѴށz@iiͿ羶:@O{+Ddo<tI=4hL|4MzN9M_AD@4KhZh@3D:,vz׬A4MCZ=4hL|{d4ƺӴD4D{K[꽥u	48=mM5ЩN&D4i3U4驪.o8Mkϻ4~Mi:l;ae&qg'-EHXZH.+zdJ_arx~jQ9CY[9[
{d
zظŃwo>!zgg$:H Ba I /'8Adc+0l6PoU/pf(b/`<s6[̰uLHuȁ4 I /'xAZc/p3WmxB!b1ִa) 1  $/(50^y]^&^@U5ǔ~LMlΡ	3A R@mjr ] b@x.H/	^P
a L/!g$AxBkb91~ ~ ~ ~,Hv0!^0F>[/~Vwz/w^(wcNػ̰Hȁl I /'xAm\c/lؓ0
'j`S'x(zU*1A DpTIQ|}oTJw_gN
ĂL=nӊ{o0jbK!?)ݖ6Sg6dg[LZ	pTcԭ vwK};;'}@'0(=O~<գ+qjܞpη
#ś#Ί"_m59*Jvn:BOq	10`4p8jAF*BT
k":lWq{Zh&{OI pK̯F c˛{s"kA:SE)q᥁ڵn:+oAe"7#^vѢzTXqeUT|;6(~
') nuPإ.fZoNEktWLRo&H̯o2pnL:P'0(	`~̯rܞ0,?NS3 0l`L-23?U ktWRoK̯ϙ#(ϯzX>QaDǕW5n__-fS$g %E#C7Omk4>?Eϯv|[up"ԅ2?AAǫN\t\U,YOI pK̯F cϟzR3?H@p]2}m}fQ)kĽsQ'AIlhdƖMR"cNp8&6HZĐCbeE~# SnD~u-U߯EKH5bO_ZO")]O<NՑ6Y3xE	cC%>JTx3qtA=2oʔB>PT3uQu#N3#jw܇jClCڨG)
~/r.x¤;p(TMzT3*
~N?:Ē|u6߽*I?JTz0u=&9soʔ秂?PT3uQuv1Vl{?TW+lL?JTxu=Ptd ~S8?L-@}
~Ʀӏivd=Vl{?TW+
~ѩG?Sw{]AO?6fS1@?}ߔ)7O?S~9P_/go|vݘAz
~XϥMTc`/|s*TCԃuǥoʔ秂?PT3uQvbY(Tou2?oyx*TW^2+;X?9>2\A\׋e)q\f0@DU]
O[˧5d(o=a$A4\iUl~p MUPU	AC>|~	m1%N  re/2 Q0eo" B4`@0L8^< U>8.qײ SplvBpx{7^q\e*⁒8>Lx2	w;;MmVN'8^AԲEq!8{7^q\e*qO8>xpwǻx:Npfg:oJT
p|>qެ	w[sxkǇg:7q8ޔ2{q ǋp&xp4ǻǧcg< o4q8ޔ2{q)&~wy_IX<HF$-pﹽS6Kwޠ*GAKzPQs*PNr5ߍ~!}ܸu85lǳ>z_/1+M PzMҺfЌz\bF-7qnm$A$ObN.%8Q@]ip׹5HR \܎yؒ	,ב23F%3+`o%&FLLZ81Sq1U.SnnJ\5``c:Y'/rsxx+geƦ<VoJV&0(ɢPQiʂ.NXYXxl-,fDbe5\`].002|2go4dMm2/gEج[%V&ʊmyX2+L@fYmX +Xάl2v-PsL vuflIL"攛.eeXN@cesy3[-ge` 3.`"6Q`,?ص쒇1YFO;Ys5R䔛.e0N@c0b7cMm2y0zlbȺU^I;CXA42dV\(+uv:b^a!{G%V1+ؓPgX@+(+l̮2+H9榄`o`be:Yoy>{S2kBlul˺Ube }!2N""ɢPQi?p|sLJA;lz1+H9榄zYY&V5XY093kBlŌsN:VD&>_үn_>ߵN<7YoltһXԌs7A<]׻QD\WǺ&YDƠCl T662n	rw/&|GZ	&Lg{#n@`(~uBi oIPP6*T  kW\&T,ooNP-}**4߻oP!"vT(lM&@PA7UmB=6cjPR**TThINߠ؟.&wCeB#A
@/&r\*Tyg?V
%>P僠B/Bklا0Wr7TA]u\Z	Jv|9A^@*ě'CeBA
@NQVjuO9\u<!B*؄ʚ=!/DeMn+lBE'!{2'{Sh&W  B@f]!	6mj'nRY|P3klwLEEC	<$^&N@UEP2{!	)R)j)d>N Y#0ulf"UBwlt0Y^&R@UEP2[!	)R)mj)̽~Hg)ݩe<lBw<y3q/l)ު"R(	F
𝐄)Ԋ
?NZ?P3kF3w0{\xX#k?]σBF4Ro$@HNU=P!Y#`'Δs3H[Pz.JA|$!B
u"B!)!v2.F
<,⁗u"灗7pPK    dZ`y95  s    word/stylesWithEffects.xml}]FO !}^>]J*_@ȏHȄ~)@3sxy}ݭ66n~<֟_o'y^w]޽=<-_owOVw_7w`88a%_k/uIj}i6urf'n?'~y{6iu_}\=mf~]wj}.~y>_x9bsǟzwsrÛiz7֒OF*8__ڠG/;nq8/xn!o|'Y}l~Vۿo7oVjri+YD:Qvj7iL~l;Jz.E]<=n~9=;:<u;ެ-vկ%C?ֻ}rfg"{2:K?2g_U/;ͩb|r911~2p#QWV߽nxXndiLֶdSϫ4?toM.^w7)"%,?y|ON?XO_6YO/VqŇz|K=?颜\^s'Co-LṣL=-}76%0o%j#jgDԎOΘ	Q;Sv#RmS@g7~vg7~v3?{XH5mH_.7qwCnR[cqlE/OjWob8~MY߷Z{/ϋqu^7w~	z]y,%en_o䡸,p_X>^=|SoS
Ìp<b$|'+xވ*._Xn7ϛgUe,7/vFn_p-c9[fCeX,`f}0HP$X-Zڝ	2ݒb2דdBq_w;>.{O
X#[lw[~KDۮAWF,`pG}T;2)avGnƇFL	X#8nYֈzK[ A-apʩ ST[ )- apFpX#8n %- apFxm S[ A- apFpX#8nֈzK[ A-ap5p8Lni [ 5-apFpX#-o	 k[ 5-on0Ep8n	 k[ 5-apF["8n krI![&I ~|-?--V*``rI[1{ϫᥨ?ok`I?x~v8v:|kk57wxr{ܝ<.d?u^N=0dd.}i\rS8|e|9wc?]ɏOm}w5pm~Dϗ;B#׭ߗ}ۺOŷo[s~ۚۚcy,?;Mz89d>Nd>d{C
`vh#g Os|!{de /_in5]vioWOO#<=!x^Iig U3<H#G}g>st<7>xկ~߁:2kk Wx㾃A}ҍWJDT#x#xl>ՅADFhByZF(OPֺkECC2S˧SP
CqV?>MT4MuNv?>砛:y_O<ur|E>~Zʲ?^6L.7/-no4UOx~{ܞbqCn<&nF9V٭&aO9P9P3KpuG0dv]a7,̥r{ro5knduS3N=fr8=LAAq!QtˎS1xJ?vhfS۠_<ӻPwJ㖞scwy{,~x	Աy[<xn\q=t\DNx鸼"~r,윗8Ѷ`^^>V<J֬{f"rVj|n~AoPIbxؕ]h_3`w8*q9TncLZu?-ՎFp)d!_n!zd+ '_ˠA2
63)={WC9tn>e/ga8	uzf}=guO-PTN'yG7u~!5uML?J^>+'x-A\V74x`rrDIe&座sZwL%핒TD.s?le%kDͦl8gbrޝ.0nuȏߗtg=^aQڧ5mZ|xeCOX՝jh~;Sߝ[Ѫ)ƧZ[yjV9tudxӹfP6f;j_:մ/ԩ@cݔ/	SQM_wu49pqځ3nvɶ?lSWpslȺRxNC^yxKxS~[HT7%]Cz$]\}WryT2A}8 qGzMZr)%Cõi*??2Q|qPk;ݜP{{^9Ě2>0" :Fct4@pqǸBzL11&K#!I= &䀘eeDƴSrdL{I"zv\eTXr2WaGCŏ췛OdW	3R(%
 %/%T/B;W&eoVs[);e3)LCCv_ʫHJǁr1CyYЭd`rzEWMYmK{R}SUt}.l_ޡhth~H
޾-fDڹ*PT~.gҺNyH2eGmodʺX5?zS~*HF2/Q,.~z7ڧ鑴h]IE{4&FAjs)r[xNdܜ|#A>&[Tki朦Q:D)}dae~۩{*Yg԰uM̎Vm_Åu,Y	"zfql/|ZmwFL49a|s0k@	oI4;<[7`
כwz9@a'-䷒K*v/yV<=,P߸я	IP\p\2.,y|AI]Yz(!qaǕa~l IaV3#gYzdåKC
YmR,pk1צ׬:t8
X<Mi~{Ss}+{ۣ[0һ0[6poPCV˨%`m½5Y_YYW½tܛL"`7ܛ?u9{7p{L MEݽlrjbw`{A7~#&vsGX:'d3vҽt<cנNܛfNY7ý{CYmR,po1׼:I4aj/w@ތܛl6N7pMnpuPxl>Eݽlrjbw`{A7N4wr57{7
Qto"ןJ7MM<^.Y,"+s9dQK;Z½ ܛ^8X<ROݾʧ9Wci֌In<o4I5QxyyK{6܂ڲi0Ϟ;%zA+ֵn!nFc)Ɓ}M'vx [ !zdNLW_,{Yɤ'!e'2a'k'+-^Y^|h92M;;0t-C[L(o{k`scO?C2oN=$֤V[>)&5:RZ74zхf9`h[0ZVO<Q$TϐDSy5ϭ
o	oM> ^tYa: UGzke/k<s3$/CuxkMzkS[k[OI#x)ͩ]xkVzk΁5 e`zk޳EwxkO."ie[k<o5gXב?ԋ.5+5C@20TYo"s=e~dzHoIo|"_xkMxk	uo8<oJos9ж`)ocv8e9C:/ToKiK7.m{Z6f	Ɨ	]Vt,=^n9W!iaR~	YG)T[5mFŎD[A! HAb)[@,{آ]TAb &¥|Nu՝ g/Cu'C;o]ԧ-|m)0R*SaDlN-NaPtƵS!  C30(׭N0 Bs0V @n?u*KfC%E"^e.(["]]ivZv."DF^`" q-T 14C7dtN Bs0V@n?u*gCu"^:Աg."@MRʥ!sj)k)AS/D`na#D`#ػt*D `hzGQ8ʪnhwB@(m rA;D=BƄpeH[yŃ Bء	p+VU"3s*0mtd
-`,~d{גN SO8Dzv'D j9r+@f  C#!C^0KjV
~D*1֥	/FLyZD@ !;4{Ū]kйli6:29kX31[XȠ%
 !:,'dN Bs0VZ  "yC>B&J.Һi_bv4/"7 xp@ !;4{Ū]JCb&t.[ZF!La=S3ŏ:`ZҩbiF^8ʪ~hwB@(m rAN"qi8^sw"+~`+j#S~qa
ʛ[@ *<ÁÀ+×[{Or:444HʇK_:_#0Uǌ)ȷ"T- \ǌL*ZCBɭğ^tϯ7ҫr^ɜVdPbW'Z^~J4ȴ4C޼x2o܄ߺaE%^(|~z^ÎןH^1^<bTN%+JlJ~Y7Oc|0xlQgj9~Mx{QxNɂ=
߼^ן+g=vxx;OJKԦdNfW2(+ٓe-߈/?%_dZXf_ho FW(K\u܄߾GQ8*YG׋ļKOfA,UnPR9-_ɠĆdO뗵^#^h|iai~1*Kio܄ߺ$,x٣Ex2BB^~d>=5ܠ6}%sROŞwo뗟/2-,3/4зB|uLxMxym¶aQeҽe^?E_xh
Nd+7(M_ɜT}2:T^#^h|iai~1^o܄ߺoK#$ZeHޗ9ò)OWjwRvA$ {C>YK( YQ ||)W#HKIHW.~ Tbz?Β;*\iM0h^s8VL} (@MpPV\r2e\`J	B0 ٹu Rp4D3s%f h%qZFY Y2f sc=	^B4hfHuB; dP`hW_١,{D3f1hf/L!A4s :!ifK2(0J4+OP'hD3f\`@C4 ٹu Rp4D3s%f h%DK^f 1	+fۣ2)D3fv.T'$#q	Y=@!Ffhv)wD34!aפF%!L!A4r :!ifK2(hW4i)^AR&3ZZ;X9Z+kZ[9c2)]L+.x9{X~M?dqIoi0nȞNO_>qՊf-CaRr7gpރ{٪QT_CC9@@IZ y){zލwD=*䵔uApFpu8O}pSSzl$$*2~l$AuFnq1^^Ny)/EWPQBܲP^AyAy("gF@hFqGIVaS^lMe%64P^Eϖ$(/(1k+HꔷJRTP-\h-d-+l*2~l$Ayf^lITPvR^NyS)/EsPQBܲ2"64P^Eϖ$(/uYPR^}Ny)/ERPQBܲP^AyAy("gF@ha燲j|$yja=~ v,jКj9Jmm_5߱N6HUh:<ojjNayJlQdcmvR2kGVsGȐNi^:D$QH1)Uy'q Rt̙eL3fHvCrʒj@ÉRF,ؐAHXueԴꥃ5|;-մ0k8 ԒXeg5kHMsCY˒k$ˆXÉRF,-bؐAXXuꥃҚ<kZ5jIVPV+XR81,F5-k[A+.ֈ5ZՏQ7[Q)^:k*5T-4?k8 ԒXQgǡbIqcH!YrEk8Z*ֈBVv]25k nXR
St!0WŚbZk8*9 @!N'ɷd5JADhy"^Vʮ5bCb`ckTJ0b:J`Mn5$p6u(kBXCRWURU\(,N5b']kĆb-Ǩ-֨T/t5^rŚbk]=VWJ )4n]霢lU|8w80`1SVք>=Gs]ª.6},|Vt	YD!xE|fq>kܞ)@G6HY0{	-T91T2'CJC%{R AHb?d$Qa&Ig 'DQ#SdyHQT1{MxKr:ՋT]sRTʔjQ'E	,
REYI*fCFT1g=lI*VCSEz(Hb瓒Kn"(CPE%TQɞU$(He-*eUTcFRy9*j|$uX=O)*f/)8OfAU/R\TIS1(SSHŞU$(He-*Ϥ	UTcFR %԰&TQ#S\yHT1{ͻ ؋zzWQŜԻ*eUT'Ew%-*ݻsTH8k@5>:UD@oq"W/RPTIexS1(GŞU$(He-*"UTcFR8fl^Ś`6PE$O9>ge:3Dbc9.G'm˰W%*RTyA<grH-jrQgoA=7؅Q[@nn$QVaH_7k)}rWKuVJ쟕\  ?KR*+2tj Ԕ'ԍ'à4{T#ҺTree)4/>Y؀hd>m:H&7<*7B@D7mn?J*pqyQ썄eXH8pFdQq
A"խ@RmڗId+м\Zaij@DVZ%xQ_p \p	q =yI%n2./}mQ썄Ñݡ	Ny F%)c+*кTQe
4/$T؀hNP>p:-H	gOJZb$H871@9x,!;DH8 pɸ	k~{#pTXq(+@SOI[TcpDZpDڗpDpJ8 t1;/H8p.Coc	HsD0؞2X SGT&?Wf	CY$d)l>ًʨ$r.G}\86  $NTW3Q؏	ew! )pzpE,poIK8| N	"CY$:,*~1HRh]r@2R*l@*H8zjGWd$H871@;xhCL>`cOiR	K8| ͏b%8o(699<&|dARzCЄR+eDt7+5We\yIQ'M,i㑙ѽIz:VXu"Xp3s3mOY:+X
)t :`{_)HdUm6"l='mTjffB#p~G""8  C"%s ;C@jU۝: ]
sq&TK0(vA݈> ׈>1@R4(ݐ!<g?Lc?҈0gg"8E1(l<cd݈? ׈?1<d\B;(W]8/!?!`A0bg%H vY? `:F Bp.\r 0c~<C68? ХCh\=B-Jy<J#Es֞96L(!0p݈? ׈?1#@'x:Ug?A`6?.*sY{,?؀S0?R0
G;r 0c~|? CF^I8 ?Cr}~Ua"9kϜEpcP
泒OxXn75f/C~i۳ٻi8x9N!OhWtxeY_f%:_5&zlh 2#&k1x\ҐZeEmh
Rj0rQ@>Uè_0jFYRް?>wu-(QQ0`WW,p݇ύ}{pigGr6 K	ٞTtNف6y><dN3f8}؉}dE/y깾Nsw6 K	ٞTt]NRN3f[i)s޹Nsvb/±ډ4wiSǝNsw6 K	ٞTt=N9ilSPN3f8}ى|yNsQM3~0i4wi 43NsI9f8QN3f8}ىhKV8rě`],i@ig 7N3AeN8puyJi/;te+~9͑Xp48]H8|X?L%)g>_twJcΦ6c.^qST_NԅYN(bL|est1sS^	GRv"7rZc
*Z;
N!/F<|H5Udmxˣ'YAm67,Kx)aCgW3iL
1ԍŚBi?N^D$.{|(| 
~L)/rq.0|mVEbEqT=SI
rS$"K(%"C+VNN'oVC-ZbZ̽zi,Y>>ܢb栙AOZ n$3٣AF܏夤\rBQeI)'"('"K('"C9rO0*gx	B9rDof*'3w3k!A96U9)ia9nQ9isPN @t+'(D,erƳy(둠,SN(JB9)\hrR(3#^nyQN
re%桜L9œ>Łr"p/JP[(']QNFx߷(rT0}|EA9\;Z n$#7<hr2pH"	FPRRL#pq,(2HHz8Q5E+7wx&:Z4560@rl/m DF0a1G9òA#`#
3ޮ(YPׄrR8PZ#G.#_2кTFe2z4_I~󵠠+'܋=IWgiS63z9('rk'G ўÈ3ŰlPNfp.#A91C9))ZPXrR8DDWNDtD}	Dy('RN("6WɿDX9^졶PN	= iS60Drl/m DrsIg3rz$('m)'?vpDM
V"jIScD:t@;sٛ=3}|nwYxIW| fP֑A0q*yE&Rި$UQN ǹT%+u~5~\RaK).-cU9SSSS]FAL5㒔R0F%u䔢PiB>9999eT9℞_`m(6	0fi]9,9rZ䴏@NEF2Y@(ir&s)ȩQSԏpĽ@NY<%uy"	<iB>&9q4{EOL$gȑӛC  JFANupRIXANGa\DH͒ӺTYrJgp!i󞂜cw0c$gi*9ANThPl ,b%u"!iB>9Iכ3v<DrZx9I+r
rdTG0JJ6iHӒtGj}z!KԹ.&'"r 3;/|lL,R<]hZ^*UYO(@5kpON:8g	E~RDQDΤN饔I77J'а9<bgw4e?<3 g /!5>˾eٗ"EEJgEF`,ҐNEN=wٌ,"x6eXG"`ui,"MXdBȾHЏ܀b+"DkY؟:.O_EWY<\Ej|$Y(")E.a;烒WYiH'Z"G7S0EWYdÒgXsXd],H<Y,/,R:Ƀ,2ð$"DkY;xS#\ }fm"G(bx`XG"`u,"CXdBȾHl8"DkYdst}fmnٌMXs2, PK    dZ?F_  	     word/settings.xmlVr8ߧ`f	qL)$M&l3u } m7O#ۊɖfοsO/vb>
/ D)+*6קla400)`>:}>5`-jz&|V)
k97NsƥXZPFaA2"\9-4rmI*kZB-9q[,k6' Re7_!NvrRW%ęO>p+qaМ;'z&p/ӻCfx&%AQ;8 9zKӍ&%MkR3DJ΢-ѤsEJjɼ^%v,<jQ?ZGݩ6@GHގ	:cojMϿON SiOɹ=0ȰƜ~QR/d^ \H51VTkD&׋+2EJU6ͦ#4N$tq
	/Y|{
2d77Ig$>dju:S?9xk ДVn;NFox/qNp\=usf+7NCjU"O@eZtjU8,{[	pGP-;o>HfHFkC|?vtg:wQe|	CF7[:3_G:,jŚRbQ;ˎ^6eŽ.{Yemq5gCtdLuMMm_6fv#e+ 3إb>'h^j͜N5{Üz"Ƹޡ"/-QLKdXtyFAI
A8R^q݀hPK    dZZS        word/webSettings.xmlj0 {Sd1B2Ap%1-c3Y6&!!.Im2/2Vdc(;
ۤ^B"b2I\9Xb'n?Nq"^i(ҍ(8J3ʳyAG-яܢ-QQoedH8<mRq,YN54i6a,~PhoGuq!kmPK    dZ9sc  
     word/fontTable.xmlݖn0}(Jl*Ɔ{ ۑ@;l0Imz+$tCH!9bZw,&D**p,1|;ˆc)Gߙܶ/Zf(V&|{ut]	ê&b
ɰ6r2,?&e X5Јꙋ syCW"H:ߕ$21mzTa,E@2[fQ0k1HDkf3R+s;Eł"n_XVΚ69f~"JT1@Op۠cKEz6*h!f4$hQcJ`I,芎ج*зv̩oWԧ]9[nƦS2dj^:x<CfUuz\7<릊Wz	3cyu1EVqZ8-yp[Vu\en/_Q6Ӓix7*/ҟdÐޑauc@ e	=18&iUA륍ȝ'h,hnIhȿ
bs1_̿>nL&I0y;i?^T`p>SǬo/ͱ}u&zMF}PK    dZA"  *     word/theme/theme1.xmlZMo6WuE֦CD[l(Q $qaݰ
ð@n_)ي(QrM%"<|_RqLZRy ߦ{$G)kׯ]
yHϯ
\)-!D˹eK#j,yu sj,	۵ÝH+W8{ŞK؇mz0@r!'V9J1GI#D,L?.AJXxU˛ii4^Uһ'жE+~II4tˍrHOt&ZO*7UM=C(Mgmhf>Mzni&h\|@ 0f1KKRѯHvq"/dR֗	b%	2|$A
ĒԜXm}@Yb־}ۗG/^=ǯ\	q/~)wo| ȓ_\I믟o>'EI {; PO*_%%$tsC.L!Epb[1y)벉HǖzbRҡ IM$	؁pPn*z@.ܤ"Mm"
Pst"5laQNG<q!x(ؓ.CJ}СpMCdBR	"n^V#Im(BEvǅ1"y!.j*ݒqAdmC{ې$du]zaM>{2S ئX>z∺XBcjf
sQLv!fzw?VdKlN>:݆aaB@u)s6F2{yO;ig-Jdz׊u[taBvŔ\o\٣h</+jڔX3F'X.L+Økģ \ޟ-}*_5G:[ԉ慡}S▔*'FiQOHJz_LOH)Mi'0M<rWrAY~v0(o݊7t⃃ި6,`àmG~W߶ljnuslZkM݈8\.6%UiZZUh4B0Fyb*u4c*t"u0$uQ::Yud2U/~osBH
N+DtٌO{pF].m7G5'c[^N8-ʄKe\lӘTV ) B?C9'lKUL1`X6a2nJxlLBY(0gbTn;oNٺs65PS~zU*q[?-mO̟PzLUE(\>y
3 +:;_U&[ZYj"jP袳"k9l"+!}HSc~^NH5e:J	7NHb<CămVJ<3GzYrgiA#CC"aөdH1km9@3WcYt*f$/`'#d($Eb/_OW%c|*i^`;,	r8]PK    dZ:ק        customXml/item1.xml
0 ~Eɒɦ:R'
IbވxwpmM4:NEIsp
{FN@AhSgGYux!O*\1Vgp譈	płlW{&4G/i%VP.8a-%
drPK    dZ>ս   '     customXml/_rels/item1.xml.relsϱj0O!heg(XBp!϶KH޾S2smA&Ѩpq6gn q+F0=jdhDA"0o-,U ˄9X.cubgЛ!'SF#al	ޱqk/*c84HVMULV?PK    dZLM   b     customXml/itemProps1.xmln0Ew1hH )kJ]x%l#D{M:5cwt;?n`*'&$T;54#::>i9%"8tvqǭ.$ܼg̶#Hn7z^ɝ?tߋ*.cq&]K~	#^yrU7qeQBs2KV4m]YOQ-q N|ޮ䉭ň$`<1{4"PK    dZЇk       word/numbering.xmlXn8ߧ@F\44@V]F# &10Kc+?3Lvˍ9|Ns6[C,K&R	и@i*(X:'Hl;7Xm̩W+#{vdW1JS3lS26
uPcVq'
kFq&P&X4WPVQqSա1#UhGIrBDK!3o)b2+9K789֔M7%IO6O{5	/)(+gh
qI	o,+9}ͤ9wN?&G6܎퉽V\Wv<o`GOk\URH^'H7wO˱d),KA23Z-!rHP&($MHzO}7`5&*d,B#ZM.Q)$Q>j%h%
R,2Ga+A8:>fb%DEXm [oyAx/&gŞN8t\Cbpb&ŎIGb'@TIx	kL^DB]W]{E/n:ڽ4vdMZŖ$*b8V5|N2Dif3Tdqw&̛O|ڍqOc=:]7&_qQ4@|=UgL]9}_xW|}:窎vMFP^\x]t?:],3nzlcg`<3̰A,0üsk`j`C39'PK    dZg        docProps/thumbnail.jpegVkpU>{7)m(-»2-B+6iڦ6-qIM&awӖN <|TtqPт:RE@G"j5<_ݤ	P_s9{nǢ_{	0exAnp8J6t 跹 khʢbZlI,4Ȇ4[
9jq0O##Hn &y# wXtg^,D!b͔׫:/U45N+rsy!VdOj(wh/bI}17tzb'9cU#|XPd?EjO`yŒZUY</kb`]e:l-p4ݒ{㑟	
5<B_,+m8>kWȳC*5gS:ްjLb$F.jԹd/QK{%-P"FgmLs%J8Gz\Ŵ3σŌA>`'1"z Z
h3w@9zev?QW8ӄH1|
2B0>2HZuv *`T[ّz
箚.g!Or@ĕӓDu}mPug~Ʉ?ī0Q#~%))>ԅtWNxh'*}Zj>jclj.%n>>rop%wz 00PlkdH3dre)=ޒKkZY@R:l25Bg+)秛B|ڮuT $뜮:W&' -2=hj_MyflS~=1
LK2$MgzD_t*7&@&/Y%	[#^厈M3a ytMыx^7\^ނOD@ SR0xcF&pY~ 1{elo6`U`nk c
)rX# aeX:}ʐ4
,q,x`ib䇍-_ҏ_f	#M̯ۇff=i򔜻μ{{Ŷ2{yuM%z[HSsև~ѵ{|㦧~s֗^~e۫;yk箏>}?_9zxo|g8⯿]?u1>h]%#zZ6SruÊ][aٰy{	s#CgM:OKS*Se%:n8#gpJthhhhh3?PK    dZR                   [Content_Types].xmlPK    dZy&K@                  _rels/.relsPK    dZSi                 docProps/core.xmlPK    dZ  l               docProps/app.xmlPK    dZ/.S"                 word/document.xmlPK    dZn2               	  word/_rels/document.xml.relsPK    dZ;ٚx/  3U            U  word/styles.xmlPK    dZ`y95  s            :  word/stylesWithEffects.xmlPK    dZ?F_  	             kp  word/settings.xmlPK    dZZS                Yt  word/webSettings.xmlPK    dZ9sc  
             u  word/fontTable.xmlPK    dZA"  *             x  word/theme/theme1.xmlPK    dZ:ק                  customXml/item1.xmlPK    dZ>ս   '               customXml/_rels/item1.xml.relsPK    dZLM   b               customXml/itemProps1.xmlPK    dZЇk                 word/numbering.xmlPK    dZg                  docProps/thumbnail.jpegPK      a      