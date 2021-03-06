# changelog

This file contains highlights of what changes on each version of the html
package.

#### Pub version 0.12.2+1
  * Exclude `.packages` file from the published package.

#### Pub version 0.12.2
  * Added `Element.endSourceSpan`, containing the span of a closing tag.

#### Pub version 0.12.0+1
  * Support `csslib` version `0.12.0`.

#### Rename to package:html 0.12.0
  * package has been renamed to `html`

#### Pub version 0.12.0
  * switch from `source_maps`' `Span` class to `source_span`'s
    `SourceSpan` class.

#### Pub version 0.11.0+2
  * expand the version constraint for csslib.

#### Pub version 0.10.0+1
  * use a more recent source_maps version.

#### Pub version 0.10.0
  * fix how document fragments are added in NodeList.add/addAll/insertAll.

#### Pub version 0.9.2-dev
  * add Node.text, Node.append, Document.documentElement
  * add Text.data, deprecate Node.value and Text.value.
  * deprecate Node.$dom_nodeType
  * added querySelector/querySelectorAll, deprecated query/queryAll.
    This matches the current APIs in dart:html.
