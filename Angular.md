# Interesting things
Procedures, tecnologies and functional code 
https://stackedit.io/

# ANGULAR FRAMEWORK
<p>This is a place where I will load stuff and relevant things about Angular!</p>

## How create your first project?

 1. Make sure your development environment includes `Node.js®` and an npm package manager.

2. Install the Angular CLI globally. To install the CLI using  `npm`, open a terminal/console window and enter the following command:

		npm install -g @angular/cli
		
3. In the same terminal/console search your repository folder or your develpment folder, you can do that with `cd` command.
4. When you are in the folder that you want to be, you can start your first project. To create a new workspace and initial app project. Run the CLI command  `ng new`  and provide the name  `my-app`, as shown here:

	    ng new my-app
	    
	It also creates the following workspace and starter project files:

	-   A new workspace, with a root folder named  `my-app`
	-   An initial skeleton app project, also called  `my-app`  (in the  `src`  subfolder)
	-   An end-to-end test project (in the  `e2e`  subfolder)
	-   Related configuration files

	The initial app project contains a simple Welcome app, ready to run.
5. To run the application, Angular includes a server, so that you can easily build and serve your app locally.
			

		    cd my-app 
		    ng serve --open

    The  `ng serve`  command launches the server, watches your files, and rebuilds the app as you make changes to those files.

    The  `--open`  (or just  `-o`) option automatically opens your browser to  `[http](https://angular.io/api/common/http)://localhost:4200/`.

    Your app greets you with a message:

      ![enter image description here](https://angular.io/generated/images/guide/cli-quickstart/app-works.png)

