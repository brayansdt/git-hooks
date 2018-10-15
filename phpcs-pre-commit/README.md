PHP Codesniffer Pre-Commit Hook for GIT

Forked from: http://github.com/s0enke/git-hooks

REQUIREMENTS

 * PHP CodeSniffer: https://github.com/squizlabs/PHP_CodeSniffer


FEATURES

 * Check Coding style and forbid the commit if violations are found
 * Configuration file for Coding Standard, Path to PHPCS, Ignore List
 * Shows output in a 'less' pipe following the smart git principles

INSTALATION / USAGE
 
 * ```cd your-project-path/.git/hooks```
 * ```curl -O https://raw.githubusercontent.com/brayansdt/git-hooks/master/phpcs-pre-commit/pre-commit```
 * open pre-commit with your text editor and set `PHPCS_BIN` variable to the output of ```which phpcs```
 * save and close the file
 * ```chmod a+x pre-commit```
