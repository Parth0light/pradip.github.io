---
layout: post
title: "Verilog Basics – A Beginner’s Guide"
categories: tutorials verilog
---

## Introduction
Verilog is a hardware description language (HDL) used to model digital systems.  
It allows designers to describe hardware at **behavioral, RTL, and gate-level**.

### Example Code
```verilog
module and_gate (input a, input b, output y);
  assign y = a & b;
endmodule
