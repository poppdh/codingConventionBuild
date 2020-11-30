# codingConventionBuild

## .htaccess 파일 설정
접속시 index.html로 연결되도록 설정

Options -MultiViews

RewriteEngine On

RewriteCond %{REQUEST_FILENAME} !-f

RewriteRule ^ index.html [QSA,L]
