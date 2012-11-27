webyana css structure
====================================

#Base

A Base rule is applied to an element using an element selector, a
descendant selector, or a child selector, along with any pseudo classes
It doesn't include any class or ID selectors. It is defining the
default styling for how that element should look in all occurrences
on the page.

* css rest
* There should be no need to use !important in a Base style.

	- body, form {
				margin: 0;
				padding: 0;
				}
				a {
				color: #039;
				}
				a:hover {
				color: #03F;
				}

#Layout

The minor components—such as
a callout, or login form, or a navigation item—sit within the scope
of major components such as a header or footer. I refer to the minor
components as Modules and will dive into those in the next section.
The major components are referred to as Layout styles.

	- #header, #article, #footer {
		width: 960px;
		margin: auto;
		}
		#article {
		border: solid #CCC;
		border-width: 1px 0 0;
		}

#Module

#State

A state is something that augments and overrides all other styles.
For example, an accordion section may be in a collapsed or expanded
state. A message may be in a success or error state.



#Theme