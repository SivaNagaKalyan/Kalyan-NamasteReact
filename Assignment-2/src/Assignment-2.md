# Q1.What is node?
npm is a package manager where you can get many packages required for your development.for suppose there is tailwind css package that you can get from npm that will ease your css work. There is chalk package sized about 4kb allows you to style your console messages.Take amazon as example and if you are  seller you will give you item to amazon and it will wrap that up and sell it to the buyer same as with npm as npm acts as amazon and buyers will get packages from npm and sellers as developers contributes to those packages.
# Q2.What is parcel/webpack?
parcel or webpack are bundlers that helps use to ease our development process by providing many more important services like hot relading ,tree shaking,dev server etc..It also minifies our final application to reduce the size with clearing some unused parts in our development folder.
# Q3.What is .parcel-cache?
The .parcel-cache in parcel  stores information about your project when parcel builds it, so that when it rebuilds, it doesn't have to re-parse and re-analyze everything from scratch. It's a key reason why parcel can be so fast in development mode.
# Q4.What is npx?
NPX is a package executer, and it is used to execute javascript packages directly, without installing them from the npm registry.
# Q5.Difference between dependencies and devDependencies?
For every project there will be a package.json file which provides information about our project and it contains dependencies and devdependencies as objects. both the files shows information about the installed package with version numbers as well but devdependencies consists of all the packages that are used in the project in its development phase and not in the production or testing environment with its version number while dependencies consists for production phase.

# Q6. What is Tree Shaking ?
As the name suggests think the process of tree shaking and when you try to shake the tree you will see all the withered flowers will get down from the tree same as in the development where all the unused imports and functions will be removed from the files when it gets into production and this helps in the performance.

# Q7. What is Hot Module Replacement?
Hot Module Replacement (HMR) exchanges, adds, or removes modules while an application is running, without a full reload. This can significantly speed up development in a few ways:

Retain application state which is lost during a full reload.
Save valuable development time by only updating what's changed.
Instantly update the browser when modifications are made to CSS/JS in the source code, which is almost comparable to changing styles directly in the browser's dev tools.

# Q8. What is .gitignore file and what should we add and don't add into it?
 .gitignore file basically ignores all the files that have been added into it while pushing our project into github and this helps us to push only relevant files to the git. we should add the important files that we create in our development purpose and we should not add files like node modules,.parcel-cache files etc.. as there is no meaning in pushing them to git.

 # Q9. Difference between package.json and package-lock.json?
 In the package-lock.json file there will be the exact version of the packages that you have installed whereas in package.json file there will be the latest versions.

 # Q10. Why should I not modify package-lock.json?
 If you modify the package-lock.json you will lose all the information about the versions of the packages hence results in causing either higher version or lower version but not the exact version that you have used.
 # Q11. What are node modules? is it good idea to push them on git ?
 In Node.js, Modules are the blocks of encapsulated code that communicates with an external application on the basis of their related functionality. Modules can be a single file or a collection of multiples files/folders. The reason programmers are heavily reliant on modules is because of their re-usability as well as the ability to break down a complex piece of code into manageable chunks.you should not push node modules to the git as you are burdening the project without no use.

 # Q12. what is the dist folder?
 dist folder refers to distribution folder includes the minified production ready files and assets that are necessary to deploy and run our code .
 # Q13. What is browserlists?
 Browserslist is a tool that allows specifying which browsers should be supported in your frontend app by specifying "queries" in a config file.
 # Q14. What is the <noscript> tag in index.html line of create react app?
if in case your build fails or some weird thing happens to your code then the code inside the <noscript></noscript> tag will get rendered.
# Q15. What is the role of manifest.json in create react app?
A default `/public/manifest.json` is included automatically when we create react app. It allows anyone to install your React application on their device.
It holds important info about you project. it provides capability to change look and view of application on the user's desktop or mobile device. Name, description, app icon, theme color, images etc. are some fields which we can change by modifying properties in the JSON file. These apps can then work offline too.



