# Wads_Config_Yaml

Zend_Config extension for YAML file

## Usage

```php
<?php

require_once 'Wads/Config/Yaml.php';

$yaml_file = '/path/to/file.yaml';

$config = new Wads_Config_Yaml($yaml_file);

echo $config['url'];

```

## Interface

### constructor

public function __construct($filename, $section = null, $allowModifications = false)

#### $filename: string
yaml file path

#### $section: string | array
Section you want to retrieve

#### $allowModifications | boolean
Whether to allow changes
