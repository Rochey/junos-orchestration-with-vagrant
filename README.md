# vagrant-junos

requirements: vagrant and virtual box. junos plugin for vagrant. 

"3_vsrx_vagrant_non_provisionning" has vagrant details for a topo with 3 vsrx (ffp) connected together. 

"3vsrx" has vagrant details for a topo with 3 vsrx (ffp) connected together + ansible provisionner (basic).

"3vsrx-v2" has vagrant details for a topo with 3 vsrx (ffp) connected together + ansible provisionner. 
This ons is more advanced and interresting: ansible uses a jinja2 template to build bgp details for each device and then push the conf

"ubuntu_junos" has vagrant details for a vsrx (ffp) and an ubuntu box (14.04). 
The server is provisonned (pyez, ansible, and some automation content as well). 
so you can use the ubuntu vagrant box to test some automation content against a junos vagrant box. 
so no need to install programs (ansible pyez ...) on your laptop.  




