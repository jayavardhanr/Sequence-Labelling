Utils.py
* shared : uses theano shared variables, tf has done away with syntax, need to change it accordingly

Train.py

* opt-parser : can get rid of this and import parameters from a file instead of passsing it on 
commandline

Model.py

* theano.shared() : change this to tensorflow

[All files]

* update function calls: a lot of the keras calls are for the old api, and are deprecated, 
will need to change that


--------------------------------------------------------------------------------------------

Get rid of

* update_tag_scheme
