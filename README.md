# IRIVEN PHP: DataCollector
Iriven DataCollector is a PHP container for key/value pairs


> Usage:

- $Author =  new \Iriven\IrivenPHPDataCollector([
                            'name'          => $name,
                            'email'         => $email,
                            'homepage'      => $homepage,
                            'role'          => $role,
                            'description'   => $description
                        ]);
                        
- $Author->get('name',null);
- $Author->get('email',null);
- $Author->get('homepage',null);
- $Author->get('role',null);
- $Author->get('description',null);

> Other methodes:

** methode 1:
- $Author =  new \Iriven\IrivenPHPDataCollector();
- $Author->add([
                            'name'          => $name,
                            'email'         => $email,
                            'homepage'      => $homepage,
                            'role'          => $role,
                            'description'   => $description
                        ]);

** methode 2:
- $Author =  new \Iriven\IrivenPHPDataCollector();

- $Author->set('name',$name);

- $Author->set('email', $email);

- $Author->set('homepage',$homepage);

- $Author->set('role', $role);

- $Author->set('description',$description);
