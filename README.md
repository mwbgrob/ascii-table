# ascii table

[![Latest Stable Version](http://poser.pugx.org/golding/ascii-table/v)](https://packagist.org/packages/golding/ascii-table) [![Total Downloads](http://poser.pugx.org/golding/ascii-table/downloads)](https://packagist.org/packages/golding/ascii-table) [![Latest Unstable Version](http://poser.pugx.org/golding/ascii-table/v/unstable)](https://packagist.org/packages/golding/ascii-table) [![License](http://poser.pugx.org/golding/ascii-table/license)](https://packagist.org/packages/golding/ascii-table) [![PHP Version Require](http://poser.pugx.org/golding/ascii-table/require/php)](https://packagist.org/packages/golding/ascii-table)


Php library with ascii table enum.

## Installation

```shell
composer require golding/ascii-table
```

## Usage
```php

<?php
    require(__DIR__ . '/vendor/autoload.php');
    
    use Golding\ascii\AsciiChar;
    
    $backspace = AsciiChar::BACKSPACE();
    $backspace->getName();
    $backspace->getValue();
    $backspace->is(AsciiChar::BACKSPACE);
    $backspace->isControlChar();
    $backspace->isHorizontalSpace();
    $backspace->isVerticalSpace();
    $backspace->isWhiteSpace();
    $backspace->isPrintableChar();
    $backspace->isLetter();
    $backspace->isDigit();
    $backspace->isExtended();
```

## License
released under the MIT License.
See the [bundled LICENSE file](LICENSE) for details.
