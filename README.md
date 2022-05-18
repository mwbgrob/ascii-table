# ascii table

TODO Badges!



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
