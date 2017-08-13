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
See [el.md](doc/jsp/el.md)

EL function
-----------------
See [el.md](doc/jsp/el.md)


JSP common config
-----------------

JSTL
-----------------
See [jstl.md](doc/jsp/jstl.md)


Spring form JSP taglibs
=================

See [form.md](doc/spring/form.md)


Spring misc JSP taglibs
=================

See [misc.md](doc/spring/misc.md)



Spring Security JSP taglibs
=================

TBD

Apache Tiles
=================

TBD
