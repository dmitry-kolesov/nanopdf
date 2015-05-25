Nanopdf is a lightweight pdf writing library for .NET.

It's goal is to provide a concise pdf library that supports the basic PDF functionality.

An example looks like this:

```
PDFDocument pdf = new PDFDocument();
pdf.draw(10, 10, "hello world", 20);
pdf.drawLine(40, 40, 140, 140);
pdf.save("tmp2.pdf");
```


---


This is alpha software. Things that will be added soon are:

  1. embedded image support
  1. stricter following of the spec ( currently only works with adobe pdf viewers )
  1. Datagrid like support for datasources