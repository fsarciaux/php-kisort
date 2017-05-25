# php-kisort
case-insensitive sorting by name with key preservation

	uasort($data['files'], function($a, $b){ return strcasecmp($a->name,$b->name); });
