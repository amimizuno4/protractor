# protractor
protractor template
20-08-2021 6AM IST
Steps:
1. npm install jscodeshift @wdio/codemod
2. Change 'export const config:Config' to 'exports.Config'
3.npx jscodeshift -t ./node_modules/@wdio/codemod/protractor ./conf/servusca.conf.ts 
4. Step file migtration did not work 
5.installed wdio cli
6.wdio config (cucumber, typescript, reporters)
