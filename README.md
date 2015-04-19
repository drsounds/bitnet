# bitnet
A specification of an alternative web protocol Work in progress

# Introduction
HTML/JavaScript/HTTP is the de facto standard for the internet. However, the payload of HTML is increasing a lot and for slower connections
and low end machines the current web standards can be tedius.

Bitnet is a web protocol split apart from HTML. It is written from the ground.

Forgot everything about HTML/CSS/jQuery etc. And also Wordpress.

Bitnet is something else.

## Core concepts

Bitnet is about an binary, international, universal binary language where web content is described in binary bits, for their meaning in semantic core. Instead of Document-based web navigation, it consists of "node"s that has a binary representation of any existing entity. A node is representing a setence, that has a subject, predicate, and object.

## Node structure

A node is a ontological footprint, which consists of binary setences.

## A setence
The setence consists of 64 bytes signature which represents the setence meaning. 

* first integer describes the subject. 
* next integer describes the predicate. 
* third integer describes the predicate extension.
* fourth integer describes the object.
* fifth integer is the id of the indirect object
* sixth integer is the agent
* seventh integeer is the adverbial
* eight integer is an unique identity.

Then
it follows ASCII text with identifiers of the entities of the setence, divided with 0x00 byte ('\0')



Bitnet is not based on 'web page' pardigam seen today. It is based on "Entities" whose info are requested for various sources in binary format.

The core difference is that bitnet is completely binary.


