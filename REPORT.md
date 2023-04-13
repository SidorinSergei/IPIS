git clone https://github.com/username/repository-name.git](https://github.com/SidorinSergei/IPIS

git add hello_world.cpp

git commit -m "Add hello_world.cpp"

git push

git status

git commit -m "Changed hello_world.cpp to prompt for user name"

git checkout -b patch1

git commit -m "Removed using namespace std;"

git push -u origin patch1

clang-format -style=Mozilla hello_world.cpp

clang-format -style=Mozilla -i hello_world.cpp

git push -u origin patch2

git checkout patch2

git rebase master

git push --force origin patch2
