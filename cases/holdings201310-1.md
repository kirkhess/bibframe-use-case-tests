# Header

## label

Bound With Example: Method A (simple)

## description

From Leif Andresen: "A binding in one library of more than one text without any connection (example: five short stories published individually, but bundled together of the library in one binding)"  This example makes the bounded volume a type of local, constructed BIBFRAME Work, which contains two additional BIBFRAME Works. There is an Instance of the ConstructedWork and a Holding that points to the Instance.  See, listserv.loc.gov/cgi-bin/wa?A2=ind1310&L=bibframe&T=0&X=566B2540DBDD7AEA03&P=1202

## id

holdings201310-1

## relatedtests

* holdings201310-2
* holdings201310-3

## issues

* modeling holdings
* holdings as annotations
* bound with examples

## tags

* holdings
* annotations

## created

2013-10-22

## status

* open

# ConstructedCollection

* id: <http://library.edu/resources/works/boundwith>
* title: Bounded work of 'Le cosmopolite, ou, Le citoyen du monde' and 'Trapue, reine des Topinamboux, ou La maitresse femme'
* creator: <http://library.edu/organizations/library>
* subject: <http://library.edu/authority/Europe--Description-and-travel--Early-works-to-1800> 
* includes: <http://library.edu/resources/works/work1>
* includes: <http://library.edu/resources/works/work2>

# LanguageMaterial

* id: <http://library.edu/resources/works/work1>
* title: Le cosmopolite, ou, Le citoyen du monde
* creator: <http://library.edu/creator/Fourgeret-de-Monbron,-Louis-Charles,-1706-1760>
* subject: <http://library.edu/authority/Europe--Description-and-travel--Early-works-to-1800> 

# LanguageMaterial

* id: <http://library.edu/resources/works/work2>
* title: Trapue, reine des Topinamboux, ou La maitresse femmee
* creator: <http://library.edu/creator/Desboulmiers,-Jean-Auguste-Julien>
* subject: <http://library.edu/authority/Europe--Description-and-travel--Early-works-to-1800> 

# Instance

* id: <http://library.edu/resources/instances/1>
* instanceOf: <http://library.edu/resources/works/boundwith>
* format: printed
* binding: library

# Holding

* id: <http://library.edu/resources/holdings/1>
* holds: <http://library.edu/resources/instances/1>
* heldBy: <http://library.edu/organizations/library>
* location: Rare books
* shelfMark: D917.F6
* accessRestriction: Must be onsite.
