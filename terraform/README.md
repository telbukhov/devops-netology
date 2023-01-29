# Описание .gitignore
В в файле /terraform/.gitignore будут проигнорированы все разделы с названием .terraform;
файлы с расширением tfstate, а также с файлы по шаблону *.tfstate.*;
crash-логи; файлы с расширением *.tfvars и *.tfvars.json;
файлы с именами override.tf, override.tf.json, а также файлы по маске *_override.tf и *_override.tf.json;
файлы с названием .terraformrc и terraform.rc.