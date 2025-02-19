# lab-1
1. git clone - скопируем удаленный репозиторий
2. создадим файлы main.cpp, utils.cpp, util.h
3. CMakeLists.txt
4. mkdir build 
cd build 
cmake
make
 - создадим директорию и соберем в ней проект
5.  git add .
git commit -m "Initial commit: CMake project setup"
- первый коммит
6. git checkout -b featureutils - создадим новую ветку
7. git add .
   git commit -m "feat: Add multiplication function to utils"
  - второй коммит
8. git checkout main
git add .
git commit -m "fix: Update main output message in main branch"
- третий коммит
9. git merge featureutils - слияние веток
