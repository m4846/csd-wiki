/*
 * README
 * John Rambo
 * rambo@csd.uoc.gr
 * hy255
 * as2
 */

	Q: Einai dynato oi synarthseis ms_copy, ms_ncopy, ms_concat, ms_nconcat
	   na kalesoun thn assert kai na eleg3oun an h mnhmh proorismou opou
	   grafetai to apotelesma einai arketa megalh?
	A: Mporoume na xrhsimopoihsoumee tin assert gia na eleg3oume an ena
	   string einai NULL h oxi, alla dn fainetai na mporoume na
	   dhmiourghsoume mia syn8hkh pou na mas kalyptei se periptwsh buffer
	   overflow k na mas dinei alh8es h pseydes.

	Q: Einai dynato oi synarthseis ms_ncopy, ms_nconcat, ms_ncompare na
	   kalesoun thn assert kai na eleg3oun an h parametros length exei
	   arnhtikh timh?
	A: Einai logiko na xrhsimopoihsoume assertion gia ekfrash ths morfhs
	   (length > 0) pou 8a mas dwsei false an exei arnitikh timh to length
	   k true alliws.

	Ektos apo tis zhtoumenes synarthseis xrhsimopoih8hke k mia ektos tou
	interface, h findchar pou psaxnei gia first occurence enos char c se
	ena string s (antistoixh ths strchr ths string.h).

	H voh8eia periorizetai se syzhthseis me synadelfous gia tis erwthseis
	pros apanthsh.