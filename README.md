Comandos para usar VIM
======================
:q          Salir del editor sin guardar                            quit
:q!         Salir del editor sin guardar ni pedir confirmacion      quit ya!
:wq!        Salir del editor guardando sin pedir confirmacion       write & quit ya!

:w f2.txt   Guardar en un fichero f2.txt y seguir                   write en f2.txt 

:e f1.txt   Cierra el fichero actual y abre f1.txt                  edit f1.txt

Comandos Ruby on Rails
======================

rails g migration remove_name_from_productos
rails g migration add_name_to_productos

Post.joins(:categorizations).where(:categorizations => {:category_id => [3, 5]})
Post.joins(:categories).where(:categories=> {:id => [3, 5]})

