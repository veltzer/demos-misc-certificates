# TOFIX

Findings from a code scan on 2026-10-04.

## Medium

- `README.md:1` - the README is only a title, and the repo holds no demos; `config/project.lua:3` promises "Demos about certificates, self signing, and more". Add the actual demos (e.g. a self-signed CA + server cert with openssl) or describe the repo honestly as a link collection.

## Low

- `links.txt:1` - typo "tomact" (tomcat); the link points at Oracle EDQ 12.1.3 docs, a product-specific page from 2014. Fix the typo and move the link into README.md so the markdown linter covers it.
