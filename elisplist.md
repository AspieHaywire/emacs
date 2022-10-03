#+elisp.info (M-x info-display-manual) (elisp.info)
#+aspies read loud out to god so he can confirm it. <-- fact, that's fact.
#+for an aspie music is = to Alcohol, when you read to god u need focus.
#+xdddddddddddddddddddddddddddddddddddddddddddddddd

* DONE Introduction
  honestly, I think I've sent trough it
  more then ones already, lol.

* DONE Conventions
 1. [X] Some Terms::                Explanation of terms we use in this manual.
 2. [X] nil and t::                 How the symbols ‘nil’ and ‘t’ are used.
 3. [X] Evaluation Notation::       The format we use for examples of evaluation.
 4. [X] Printing Notation::         The format we use when examples print text.
 5. [X] Error Messages::            The format we use for examples of errors.
 6. [X] Buffer Text Notation::      The format we use for buffer contents in examples.
 7. [X] Format of Descriptions::  Notation for describing functions, variables, etc.

** example:notation, lol.
   (car '(1 2)) ;; this *lisp expression* that *evals* is also called a *form*
   -> 1         ;; (!) i also remember that *expressions are* made out of *functions*

   *(progn (prin1 'foo) (princ "\n") (prin1 'bar))*
    ;;; *(prog*
     ⊣ foo ;; *(prin1 'foo)*
      ⊣ bar ;; *(prin1 'bar)*
       ⇒ bar ;; *(princ "/n")*
    ;;; *.prog)*

    (functioname namearg2 namearg)
    (foo int int2 int3 int4)
    (foo (int1 (int2 (int3 (int 4)))))

    function (foo :substracts: int1)
    
-----------------------------------------------------
*** the notation:list
    *★* = *point/chorser*
    *⊣* = *prints text, lol*
    *⇒* = *evaluated result/obj*
    *↦* = *results of expansions*
    *≡* = *exact equivalence of two forums*
    *error→* = *get ur lube and horse cock sissy*
    
        
* DONE Format of Descriptions
  1. [X] A Sample Function Description  
  2. [X] A Sample Variable Description

	
* TODO Lisp Data Types
  1. [ ] Printed Representation::  How Lisp objects are represented as text.
  2. [ ] Special Read Syntax::       An overview of all the special sequences.
  3. [ ] Comments::                  Comments and their formatting conventions.
  4. [5/18] Programming Types::         Types found in all Lisp systems.
     1. [X] Integer Typeso
     2. [X] Floating-Point Type (lol (can write it in 5 diffrent ways))
     3. [X] Character Type      (A is a character AB is a string of characters)
     4. [X] Symbol Type
	- foo                 ; A symbol named ‘foo’.
          FOO                 ; A symbol named ‘FOO’, different from ‘foo’.
	  1+                  ; A symbol named ‘1+’
                              ;   (not ‘+1’, which is an integer).
          \+1                 ; A symbol named ‘+1’
                              ;   (not a very readable name).
          \(*\ 1\ 2\)         ; A symbol named ‘(* 1 2)’ (a worse name).
           -*/_~!@$%^&=:<>{}  ; A symbol named ‘+-*/_~!@$%^&=:<>{}’.
                         ;   These characters need not be escaped.
     5. [ ] Sequence Type
     6. [2/3] Cons Call Type
	1. [X] Box Diagrams
	2. [ ] Dotted Pair Notation
	3. [X] Association List Type
     7. [X] Array Type
     8. [0/4] String Type
	1. [ ] Syntax for Strings
	2. [ ] Non-ASCII in Strings
	3. [ ] Nonprinting Characters
	4. [ ] Text Props and Strings
     9. [ ] Vector Type
     10. [ ] Char-Table Type
     11. [ ] Bool-Vector Type
     12. [ ] Hash Table Type
     13. [ ] Function Type
     14. [ ] Macro Type
     15. [ ] Primitive Function Type
     16. [ ] Byte-Code Type
     17. [ ] Record Type
     18. [ ] Type Descriptions
     19. [ ] Autoload Type
     20. [ ] Finalizer Type
  5. [ ] Editing Types::             Types specific to Emacs.
  6. [ ] Circular Objects::          Read syntax for circular structure.
  7. [ ] Type Predicates::           Tests related to types.
  8. [ ] Equality Predicates::       Tests of equality between any two objects.
  9. [ ] Mutability::                Some objects should not be modified.
i
