# Test-Garuda-Import

### Demo

### Snytax HTML (Multiple Data / Looping)
```
<garuda-import  src     = "fruits-template" 
				el      = "app"
				@el     = "my_fruit"
				@loop   = "1. Semangka || 
				           2. Pisang   || 
				           3. Apel     || 
				           4. Jeruk    || 
				           5. Rambutan || 
				           6. Duku     || 
				           7. Buah Mata Kucing || 
				           8. Kelengkeng">
</garuda-import>
```

### Snytax HTML (Single Data)
```
<garuda-import  src     = "basic-template" 
				el      = "app"
				_name   = "Garuda Javascript 2"
				_email   = "garuda@gmail.com"
				_adress   = "Indonesia"
				_author   = "Lamhot Simamora"
				_description = "Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
								tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam"
                	>
</garuda-import>
```