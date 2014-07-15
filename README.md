scalaxb 
=======

I am working with [HotelBeds / BedsOnline](http://www.bedsonline.com/public/uk/interface.html) webservices which makes use of [Chameleon Namespaces](http://www.xfront.com/ZeroOneOrManyNamespaces.html#mixed).  Forked scalaxb to support chameleon namespaces as well as added a Scala 2.10 template for generating code with out deprecation warnings.

Usage:
sbt <br>
project app <br>
run --chameleons --scala-version 2.10 &lt;location of your xsds&gt;
