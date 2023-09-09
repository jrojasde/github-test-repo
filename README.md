# github-test-repo

crear un proveedor de identidad

- proveedor de indentidad / crear 
url:  https://token.actions.githubusercontent.com
public:  sts.amazonaws.com
huella de ejemplo:  1c58a3a8518e8759bf075b76b750dfbhasdsad64fcd

- crear un rol ademas crear una politica:

politica de ejemplo:  

{
    "Version": "2012-10-17",
    "Statement": [
        {
            "Sid": "VisualEditor0",
            "Effect": "Allow",
            "Action": "s3:*",
            "Resource": "*"
        }
    ]
}

- agregamos secretos en nuestro github secret ( dentro de las configuracion del repositorio )