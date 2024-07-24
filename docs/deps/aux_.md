---
layout: relation
title: 'aux'
shortdef: 'auxiliary'
# The filename "aux" is not allowed on Windows, so we redirect instead
# (see https://github.com/UniversalDependencies/docs/issues/20)
udver: '2'
---

An aux (auxiliary) of a clause is a function word associated with a verbal predicate. In LSE it may consist of an indexing sign that occasionally accompanies a lexical verb, pointing to the core participants.

~~~ conllu
# sent_id = VV-FRE#083
# text = HOMBRE PERSONA CONOCER INDX.AUX MUJER
# gloss_en = MAN PERSON KNOWLEDGE INDX.AUX WOMAN
# text_es = El hombre conoce a la mujer
# text_en = The man meets the woman
1	HOMBRE	_	NOUN	N.P	_	3	nsubj	_	Gloss=MAN
2	PERSONA	_	NOUN	N.Loc	_	1	appos	_	Gloss=PERSON
3	CONOCER	_	VERB	V	_	0	root	_	Gloss=KNOWLEDGE
4	INDX.AUX	_	AUX	Aux	_	3	aux	_	Gloss=INDX.AUX
5	MUJER	_	NOUN	N.P	_	3	obj	_	Gloss=WOMAN
~~~
