# JavaScript Project Boilerplate

## Usage

### Step 1: Clone Boilerplate

``` console
git clone https://github.com/JamesRobertHugginsNgo/javascript-project-boilerplate.git NEW-PROJECT-NAME
```

### Step 2: Open New Folder

``` console
cd NEW-PROJECT-NAME
```

### Step 3: Remove Git Folder

``` console
rm -rf .git
```

### Step 4: Initialize a New Git Repository

``` console
git init
```

### Step 5: Update Main Branch

``` console
git branch -m main
```

### Step 6: Add Files to the New Git Repository

``` console
git add .
```

### Step 7: Commit Added Files to the New Git Repository

``` console
git commit -m "Make initial commit"
```

### Step 8: Remove Readme File

``` console
rm README.md
```

### Step 9: Create a New Readme File

``` console
echo -e '# NEW-PROJECT-NAME' >> README.MD
```

### Step 10: Rename Package.json

``` console
mv package.json package.old.json
```

### Step 11: Initialize NPM Creating a new Package.json

``` console
npm init -y
```

### Step 12: Update New Package.json

Find and copy over the following fields/properties:

- scripts
- devDependencies

### Step 13: Remove Old Package.json

``` console
rm package.old.json
```
