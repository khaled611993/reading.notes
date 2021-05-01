## LINKS IN HTML
### links creating by useing **a** element with add **href** in the opening tag 
 ### TYPES OF LINKS.
1. **Links from one website to another**:
When you link to a different website, the value of the href attribute will be the full web address for the site.

1. **Links from one page to another on the same website**:
If all the pages of the site are in the same folder, then the value
of the href attribute is just the name of the file,or You can use a shorthand known as a
- **relative URL**:
  - **Same Folder**.
  - **Child Folder**.
  - **Grandchild Folder**.
  - **Parent Folder**.
  - **GrandParent Folder**.
   

1.  **Links from one part of a web page to another part of thesame page**:
by useing ( #:id or .:class) in the href attribute.

1. **Links that open in a new browser window**:
If you want a link to open in a new window, you can use the target attribute on the opening **a** tag. The value of this attribute should be **_blank**.
1. **Links that start up your email program and address a new email to someone**:
the href attribute starts with mailto: and is followed by the email address you want the
email to be sent to.

## Layout:
CSS deals with every element as if it is in its own box. This box will either be a 
- **block-level box** :start on a new line Examples include: **h1 , p , ul , li** .

or an
 - **inline box** :flow in between surrounding text Examples include: **img , b , i .

 ### Controll ing the Position of Elements.

 - **Normal flow**: In normal flow, each block-level element sits on top of the next one(**position:static**)
 - **Relative Positioning**: moves an element in relation to where it would have been in normal flow(**position:relative**)
 - **Ab solute positioning**: When the position property is given a value of absolute, the box is taken out of normal
flow and no longer affects the position of other elements on the page.(**position:absolute**)
 - **Fixed Positioning** :Fixed positioning is a type of absolute positioning that requires the position property to have a value of fixed.(**position:fixed**)
 - **Floating Elements**: The float property allows you to take an element in normal flow and place it as far to the
left or right of the containing element as possible(**Float**)




