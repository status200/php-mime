# PHP-MIME

MIME type lookup for PHP

## Usage

    $mime = new \Status200\Mime();
    echo $mime -> get("/any/valid/file/path.txt");
    // text/plain