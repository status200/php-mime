# PHP-MIME

MIME type lookup for PHP

## Usage

```PHP
$mime = new \Status200\Mime();
echo $mime -> get("/any/valid/file/path.txt");
// text/plain
```