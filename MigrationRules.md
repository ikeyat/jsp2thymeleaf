Pure JSP
=================

Directives
-----------------

### page directive
omitted...

### taglib directive
Maybe this looks to be same as Thymeleaf Dialect.

### include directive

Before(JSP)
```jsp
<%@ include file="/WEB-INF/header.jsp"%>
```

After(Thymeleaf) : included html
```html
<div th:fragment="footer-fragment">
  This is a footer.
</div>
```

After(Thymeleaf) : including html
```html
<div th:insert="~{footer :: footer-fragment}"></div>
```
http://www.thymeleaf.org/doc/tutorials/3.0/usingthymeleaf.html#including-template-fragments


Scriptlet
-----------------
Not supported in Thymeleaf.
Please migrate script into Java source code.


Custom taglibs
-----------------
omitted...

Tag file
-----------------
omitted...

EL expression
-----------------

EL function
-----------------

JSP common config
-----------------

JSTL
-----------------

### core

### fmt

### sql
omitted...

### xml
omitted...

### functions

Spring form JSP taglibs
=================

``<form:form>``
-----------------

``<form:input>``
-----------------

``<form:password>``
-----------------

``<form:textarea>``
-----------------

``<form:checkboxes>``
-----------------

``<form:checkbox>``
-----------------

``<form:radiobuttons>``
-----------------

``<form:radiobutton>``
-----------------

``<form:select>``
-----------------

``<form:options>``
-----------------

``<form:option>``
-----------------

``<form:hidden>``
-----------------

``<form:label>``
-----------------

``<form:button>``
-----------------

``<form:errors>``
-----------------


Spring misc JSP taglibs
=================

``<spring:message>``
-----------------

``<spring:theme>``
-----------------

``<spring:argument>``
-----------------

``<spring:hasBindErrors>``
-----------------

``<spring:bind>``
-----------------

``<spring:nestedPath>``
-----------------

``<spring:transform>``
-----------------

``<spring:url>``
-----------------

``<spring:param>``
-----------------

``<spring:htmlEscape>``
-----------------

``<spring:escapeBody>``
-----------------

``<spring:eval>``
-----------------


Spring Security JSP taglibs
=================

TBD

Apache Tiles
=================

TBD
