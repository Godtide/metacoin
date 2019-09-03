# metacoin
CREATING A PROJECT
To use most Truffle commands, you need to run them against an existing Truffle project. So the first step is to create a Truffle project.

You can create a bare project template, but for those just getting started, you can use Truffle Boxes, which are example applications and project templates. We'll use the MetaCoin box, which creates a token that can be transferred between accounts:

Create a new directory for your Truffle project:

mkdir MetaCoin
cd MetaCoin
Download ("unbox") the MetaCoin box:

truffle unbox metacoin
Note: You can use the truffle unbox <box-name> command to download any of the other Truffle Boxes.

Note: To create a bare Truffle project with no smart contracts included, use truffle init.

Note: You can use an optional --force to initialize the project in the current directory regardless of its state (e.g. even if it contains other files or directories). This applies to both the init and unbox commands. Be careful, this will potentially overwrite files that exist in the directory.

Once this operation is completed, you'll now have a project structure with the following items:

contracts/: Directory for Solidity contracts
migrations/: Directory for scriptable deployment files
test/: Directory for test files for testing your application and contracts
truffle-config.js: Truffle configuration file


