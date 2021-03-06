###################
EDA Playground Help
###################

***********
Quick Start
***********

#. `Log in <http://eda-playground.readthedocs.io/en/latest/login.html>`_. Click the **Log in** button (top right) Then either

* click on Google or Facebook or 
* register by clicking on 'Register for a full account' (which enables all the simulators on EDA Playground)

#. Select your language from the **Testbench + Design** menu.
#. Select your simulator from the **Tools & Simulators** menu. Using certain simulators will require you to supply `additional identifcation information <http://eda-playground.readthedocs.io/en/latest/login.html>`_.
#. Type in your code in the **testbench** and **design** windows. 
#. Click **Run**. 

| `Tutorial <http://eda-playground.readthedocs.io/en/latest/tutorial.html>`

| `EDA Playground on YouTube <https://www.youtube.com/channel/UCP1LfE6VR_YfrcFiYhG_imA>`_ - Tutorials for Verilog, SystemVerilog, UVM, and VHDL, interview questions, news and features, etc.

***********************
What is EDA Playground?
***********************

EDA Playground gives engineers immediate hands-on exposure to simulating SystemVerilog, Verilog, VHDL, C++/SystemC, and other HDLs. All you need is a web browser. The goal is to accelerate learning of design/testbench development with
easier code sharing and simpler access to EDA tools and libraries. 

* With a simple click, run your code and see console output in real time. 
* View waves for your simulation using `EPWave <http://epwave.readthedocs.org>`_ browser-based wave viewer.
* Save your code snippets ("Playgrounds"). 
* Share your code and simulation results with a web link. Perfect for web forum discussions or emails.
  Great for asking questions or sharing your knowledge.
* Quickly try something out

  * Try out a language feature with a small example.
  * Try out a library that you're thinking of using.


.. image:: _static/playground.png
   :alt: Playground
   :width: 100%

****************
Example Usecases
****************
* **Quick prototyping** -- try out syntax or a library/language feature.
* When **asking questions on** `Stack Overflow <http://stackoverflow.com/>`_ or other online forums, attach a link to the
  code and simulation results.
* Use during **technical interviews** to test candidates' SystemVerilog/Verilog coding and debug skills.
* Try verifying using **different verification frameworks**: UVM, SVUnit, plain Verilog, or Python.

******************
Tools & Simulators
******************

For settings and options documentation, see :ref:`Tools & Simulators Options <tools-simulators-options-label>`

Available tools and simulators are below. EDA Playground can support many different tools.
`Contact us <http://www.doulos.com>`_ to add your EDA tool to EDA Playground.

Simulators
==========

* `Synopsys VCS <http://www.synopsys.com/Tools/Verification/FunctionalVerification/Pages/VCS.aspx>`_

  * Commercial simulator for VHDL and SystemVerilog

* `Cadence Incisive <http://www.cadence.com/products/fv/enterprise_simulator/pages/default.aspx>`_

   * Commercial simulator for VHDL and SystemVerilog (VHDL simulation not yet implemented on EDA Playground)

* `Aldec Riviera-PRO <https://www.aldec.com/en/products/functional_verification/riviera-pro>`_

  * Commercial simulator for VHDL and SystemVerilog
  * `Riviera-PRO Product Manual <https://www.aldec.com/en/support/resources/documentation/manuals>`_ (registration required)

..
   * `ModelSim <http://www.mentor.com/products/fv/modelsim/>`_

     * ModelSim supports most of SystemVerilog (including UVM/OVM and SVUnit libraries), and VHDL.
     * :ref:`modelsim-uvm`
     * `SystemVerilog DPI (Direct Programming Interface) Tutorial <https://www.youtube.com/watch?v=HhSAnApHYkU&list=PLScWdLzHpkAeqA7BlGEDHooMeN10IW3_T>`_

* `Incisive Specman Elite <http://www.cadence.com/products/fv/enterprise_specman_elite/pages/default.aspx>`_

  * Commercial simulator that supports `e Verification Language, IEEE 1647 <http://www.cadence.com/products/fv/pages/e_overview.aspx>`_
  * Works with `Cadence Incisive <http://www.cadence.com/products/fv/enterprise_simulator/pages/default.aspx>`_
  * `Hello e World Video Tutorial <https://www.youtube.com/watch?v=A07FJF0RvH0>`_

* `GHDL <http://ghdl.free.fr/>`_

  * an open-source simulator for the VHDL language
  * fully supports the 1987, 1993, 2002 versions of the IEEE 1076 VHDL standard and partially the latest 2008 revision (well enough to support fixed_generic_pkg or float_generic_pkg)
  
* `Icarus Verilog <http://iverilog.icarus.com/>`_

  * Version 0.10.0 (devel) supports several SystemVerilog features.

* `GPL Cver <http://sourceforge.net/projects/gplcver/>`_
* `VeriWell <http://sourceforge.net/projects/veriwell/>`_

Compilers and Interpreters
==========================

* `C++ <http://gcc.gnu.org/>`_
* `Perl <http://www.perl.org/>`_
* `Python <http://www.python.org/>`_
* `Csh (C Shell) <http://en.wikipedia.org/wiki/C_shell>`_

Synthesis Tools
===============

NOTE: The synthesis tools will only process code in the right *Design* pane. The code in the left *Testbench* pane will be ignored.

* `Yosys <http://www.clifford.at/yosys/>`_

  * `Yosys on GitHub <https://github.com/cliffordwolf/yosys>`_

* `The Verilog-to-Routing (VTR) Project <http://code.google.com/p/vtr-verilog-to-routing/>`_

**********
Frameworks
**********

For settings and options documentation, see :ref:`Languages & Libraries Options <languages-libraries-options-label>`

Available frameworks:

SystemVerilog and Verilog
=========================

* `Doulos *Easier UVM* <http://www.doulos.com/knowhow/sysverilog/uvm/easier_uvm_generator/>`_

* `SVUnit <http://www.agilesoc.com/open-source-projects/svunit/>`_ - unit testing framework for Verilog/SystemVerilog
  modules, classes, etc.

  * `SVUnit on SourceForge <http://sourceforge.net/projects/svunit/>`_

* `TL-Verilog <http://www.redwoodeda.com/>`_ - extends SystemVerilog with new language constructs for pipelines and transactions

Python
======

* `MyHDL <http://www.myhdl.org>`_ - a Python based hardware description language (HDL)

  * `MyHDL Manual <http://www.myhdl.org/doc/current/>`_
  * `MyHDL on Bitbucket <https://bitbucket.org/jandecaluwe/myhdl>`_

* `Migen <https://migen.readthedocs.org/en/latest>`_ - a Python toolbox for building complex digital hardware

  * `Migen on GitHub <https://github.com/m-labs/migen>`_
  * `Migen from M-Labs <http://milkymist.org/3/migen.html>`_

* `cocotb <http://cocotb.readthedocs.org/en/latest/index.html>`_ - a coroutine based cosimulation library for writing
  VHDL and Verilog testbenches in Python

  * `cocotb on GitHub <https://github.com/potentialventures/cocotb>`_

*************************
Libraries & Methodologies
*************************

For settings and options documentation, see :ref:`Languages & Libraries Options <languages-libraries-options-label>`

Available libraries and methodologies:

SystemVerilog and Verilog
=========================

* `UVM - Universal Verification Methodology <http://www.accellera.org/downloads/standards/uvm>`_

  * `UVM 1.2 Class Reference <_static/uvm-1.2/index.html>`_

    * `What's New in UVM 1.2 <http://www.youtube.com/watch?v=V2l4lBlsh7k&list=SPScWdLzHpkAdYPk_jgxRgOPisTm3-7U6A>`_ on YouTube

  * `UVM 1.1d Class Reference <https://verificationacademy.com/verification-methodology-reference/uvm/docs_1.1d/html/>`_

* `OVM - Open Verification Methodology <https://verificationacademy.com/topics/verification-methodology>`_

  * `OVM 2.1.2 Class Reference <https://verificationacademy.com/verification-methodology-reference/ovmworld/docs_2.1.2/html/index.html>`_
  * `OVM 2.1.2 User Guide <http://www.specman-verification.com/source_bank/ovm-2.1.2/ovm-2.1.2/OVM_UserGuide.pdf>`_

* OVL - Open Verification Library

  * :download:`OVL Library Reference Manual <_static/ovl_lrm.pdf>`
  * :download:`OVL Quick Reference <_static/ovl_quick_ref.pdf>`

* `ClueLib <https://github.com/cluelogic/cluelib>`_ - A generic class library in SystemVerilog

  * `ClueLib API Documentation <http://cluelogic.com/tools/cluelib/api/framed_html/index.html>`_

* `svlib <http://www.verilab.com/resources/svlib/>`_ - A Programmer's Utility Library for SystemVerilog

  * :download:`svlib User Guide <_static/svlib-userguide-0.3.pdf>`

VHDL
====

* OVL - Open Verification Library

  * :download:`OVL Library Reference Manual <_static/ovl_lrm.pdf>`
  * :download:`OVL Quick Reference <_static/ovl_quick_ref.pdf>`

* PSL - Property Specification Language

  * Natively supported by Riviera-PRO

* `OSVVM <http://osvvm.org/>`_ - Open Source VHDL Verification Methodology

* `UVVM <https://bitvis.no/dev-tools/uvvm/>`_ - Universal VHDL Verification Methodology

C++
===

* `SystemC <http://www.accellera.org/downloads/standards/systemc>`_ - system level design and simulation in C++

  * `SystemC 2.3.1 Class Reference <_static/systemc-2.3.1/sysc/classes.html>`_
  * `TLM 2.0 Class Reference <_static/systemc-2.3.1/tlm/classes.html>`_


*********************
What Users are Saying
*********************

   "This is a really useful web-based utility for anyone who is discussing/sharing/debugging a code segment with a
   colleague or a support person. Also, a very useful follow-up tool for post-training help among students or between
   instructor and students. Simple, easy, useful."

   -- Hemendra Talesara, Verification Technologist at Synapse Design Automation Inc.

   "I think EDA Playground is awesome! Great resource to learn without the hassle of setting up tools!"

   -- Alan Langman, Engineering Consultant

   "I’ve used it a few times now to just check out some issues related to SV syntax and it’s been a big timesaver!"

   -- Eric White, MTS Design Engineer at AMD

   "EDA Playground is sooo useful for interviews. I got a lot more feedback from being able to watch
   someone compile and debug errors. I would highly recommend others to use it if they are asking SV
   related questions."

   -- Ricardo Goto, Verification Engineer

   "I have recommended to use EDAPlayground.com to my team and am also trying to use it more for my debug.
   I find EDAPlayground.com is much easier than logging into my Unix machines."

   -- Subhash Bhogadi, Verification Consultant

   "I just wanted to thank you a lot for creating EDA Playground. I've been using it a lot lately together with
   StackOverflow and it makes asking and answering questions much easier."

   -- Tudor Timisescu, System Verification Engineer at Infineon Technologies

***************************************
Support, Feature Requests and Bug Fixes
***************************************

| Support available on `EDA Playground forum <https://groups.google.com/forum/#!forum/eda-playground>`_
| Or open a bug here: https://github.com/edaplayground/eda-playground/issues (requires GitHub account).

*********************
News and Site Updates
*********************
New features are frequently being added to EDA Playground. Follow the updates on your favorite social media site:

* `@EDAPlayground on Twitter <https://twitter.com/edaplayground>`_
* `EDA Playground on Facebook <https://facebook.com/edaplayground>`_
* `EDA Playground on Google+ <https://plus.google.com/+Edaplayground_EPWave>`_

*******
Credits
*******

**EDA Playground** is maintained by `Doulos <http://www.doulos.com>`_.
