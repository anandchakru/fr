# File rename

### Clone
```
git clone https://github.com/anandchakru/fr.git
cd fr
```

### Build
```
mvn clean package
```

### Execute
```
java -jar fr-*-dependencies.jar -a ".jpg" -b "_M.jpg" -c

```

```
usage: java -jar fr-1.0-jar-with-dependencies.jar.jar
 -a <arg>   Old file name, required, eg: ".jpg"
 -b <arg>   New file name, required, eg: "_M.jpg"
 -c         Auto-commit file renames, optional, defaults to false - only
            dry run
 -d <arg>   Directory to perform the renames, optional, defaults to
            current directory
 -e         Recursive, include sub directories, optional, defaults to
            false
 -f         Force-rename, if new file already exists it will be renamed as
            new_file_time, optional, defaults to false
 -v         Verbose output, optional, defaults to false

```