---
layout: paper
title: "Capsicum: practical capabilities for UNIX"
date: 2010-01-01
author: Robet Watson
email: rwatson@freebsd.org
paper: /_assets/other2010_rwatson_capsicum.pdf
---
Capsicum is a lightweight operating system capability and sandbox framework planned for inclusion  in FreeBSD 9. Capsicum extends, rather than replaces, UNIX APIs, providing new kernel primitives (sandboxed capability mode and capabilities) and a userspace sandbox API. These tools support compartmentalisation of monolithic UNIX applications into logical applications, an increasingly common goal supported poorly by discretionary and mandatory access control. We demonstrate our approach by adapting core FreeBSD utilities and Google’s Chromium web browser to use Capsicum primitives, and compare the complexity and robustness of Capsicum with other sandboxing techniques.