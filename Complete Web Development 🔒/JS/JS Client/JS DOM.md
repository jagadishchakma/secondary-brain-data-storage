## DOM
- D = Document = HTML page is like a document. 
- O = Object = HTML document, element, attribte, text are likes a object.
- M = Model = HTML document follow tree data structure for objecting model.
- ### Kye-Notes:
	- End of the day DOM converted into the objects of window property.
	- So, that's why, You can manipulate this DOM object.
	- Or you can do CRUD operations this DOM object.
- ### Path:
	- window.document
	- window.document
- ### Properties:
	- window.document.all
	- window.document.links
	- window.document.title
	- window.document.images
	- window.document.forms
## DOM Manipulation
- ### Read:
	- window.document.getElementById(id); return single
		- ###### properties: Update
			- innerText = get,set inside browser text(get,set both work)
			- textContent = get,set inside element text(get,set both work)
			- innerHTML = get,set inside element(get,set both work)
			- style.property = "value"; single css property
			- style.cssText = "value"; multiple css property
	
	- window.document.getElementsByClassName(name); return array of list
	- window.document.getElementsByTagName(tagname); return aray of list
	- window.document.querySelector(css selector); return single
		- ###### Properties: Update
			- children = get,set children; return array of list
			- parentElement = get,set parent; return array of list
			- nextElementSibling = get,set next element; return single
			- previousElementSibling = get, set previous element, return single
			- insertBefore(newElement,targetElement);
			- appendChild(newElement); one element;
			- append(newChild...); multiple element;
	- window.document.querySelectorAll(css selector); return array of list
- ### Create:
	- docuemnt.createElement(tagname);
		- ###### properties:
			- className = "value"; add class name;
			- setAttribute(key,value) = add attribute;
- ### Delete:
	- select.remove(); remove a element