# struts 57

Modified struts show-case for CVE-2018-11776

To test :
http://localhost:8080/struts2-showcase/${(111+111)}/actionChain1.action

The namespace will be interpreted as an OGNL expression and will become :

http://localhost:8080/struts2-showcase/222/register2.action


YB
