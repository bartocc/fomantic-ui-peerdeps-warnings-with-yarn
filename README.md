# How to reproduce the warnings

```shell
git clone https://github.com/bartocc/fomantic-ui-peerdeps-warnings-with-yarn.git
yarn install
```

You should see this kind of output

```
yarn install v1.13.0
[1/4] Resolving packages...
[2/4] Fetching packages...
[3/4] Linking dependencies...
warning " > fomantic-ui@2.7.2" has unmet peer dependency "better-console@*".
warning " > fomantic-ui@2.7.2" has unmet peer dependency "del@*".
warning " > fomantic-ui@2.7.2" has unmet peer dependency "extend@*".
warning " > fomantic-ui@2.7.2" has unmet peer dependency "gulp@*".
warning " > fomantic-ui@2.7.2" has unmet peer dependency "gulp-autoprefixer@*".
warning " > fomantic-ui@2.7.2" has unmet peer dependency "gulp-chmod@*".
warning " > fomantic-ui@2.7.2" has unmet peer dependency "gulp-clean-css@*".
warning " > fomantic-ui@2.7.2" has unmet peer dependency "gulp-clone@*".
warning " > fomantic-ui@2.7.2" has unmet peer dependency "gulp-concat@*".
warning " > fomantic-ui@2.7.2" has unmet peer dependency "gulp-concat-css@*".
warning " > fomantic-ui@2.7.2" has unmet peer dependency "gulp-copy@*".
warning " > fomantic-ui@2.7.2" has unmet peer dependency "gulp-dedupe@*".
warning " > fomantic-ui@2.7.2" has unmet peer dependency "gulp-flatten@*".
warning " > fomantic-ui@2.7.2" has unmet peer dependency "gulp-header@*".
warning " > fomantic-ui@2.7.2" has unmet peer dependency "gulp-if@*".
warning " > fomantic-ui@2.7.2" has unmet peer dependency "gulp-less@*".
warning " > fomantic-ui@2.7.2" has unmet peer dependency "gulp-notify@*".
warning " > fomantic-ui@2.7.2" has unmet peer dependency "gulp-plumber@*".
warning " > fomantic-ui@2.7.2" has unmet peer dependency "gulp-print@*".
warning " > fomantic-ui@2.7.2" has unmet peer dependency "gulp-rename@*".
warning " > fomantic-ui@2.7.2" has unmet peer dependency "gulp-replace@*".
warning " > fomantic-ui@2.7.2" has unmet peer dependency "gulp-rtlcss@*".
warning " > fomantic-ui@2.7.2" has unmet peer dependency "gulp-uglify@*".
warning " > fomantic-ui@2.7.2" has unmet peer dependency "map-stream@*".
warning " > fomantic-ui@2.7.2" has unmet peer dependency "replace-ext@*".
warning " > fomantic-ui@2.7.2" has unmet peer dependency "require-dot-file@*".
warning " > fomantic-ui@2.7.2" has unmet peer dependency "yamljs@*".
[4/4] Building fresh packages...
warning Ignored scripts due to flag.
Done in 1.73s.
```
