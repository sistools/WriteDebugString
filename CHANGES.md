# WriteDebugString - Changes <!-- omit in toc -->


## 0.0.3 - 27th August 2026

* Fixed **cmake/BuildType.cmake** so the default `CMAKE_BUILD_TYPE` is set correctly in the CMake cache (`set(CMAKE_BUILD_TYPE … CACHE …)` instead of `set(CACHE CMAKE_BUILD_TYPE …)`);


## 0.0.2 - 24th August 2026

* Updated the CMake configuration to honour caller-supplied C and C++ standards and report the build type;
* Normalised the CMake executable target name to **writedebugstring**;
* Improved CMake helper scripts with safer path handling, project identity, coloured status diagnostics, and configurable C standards;
* Expanded repository metadata and Visual Studio Code C/C++ configuration;
* Expanded GitHub Actions push-branch coverage;
* Updated the executable version to 0.0.2;
* Added a section-1 reference page and installed it with CMake;


## 0.0.1 - 3rd August 2026

* Initial CMake-based release (**CMakeLists.txt**, helper scripts, and project documentation);
* Added modular GitHub Actions CI (**ci.yml** / **ci-cell.yml**) for Windows (Windows-only tool);
* Added **cmake/BuildType.cmake**;
* Added CMake helper scripts (**prepare_cmake.sh**, **build_cmake.sh**, **clean_cmake.sh**, **remove_cmake_artefacts.sh**) and **run_all_unit_tests.cmd**;
* Added **.sis/script_info_lines.txt** and **.sis/project_name.txt**;
* Project boilerplate bootstrap (**.gitattributes**, **.gitignore**, **.vimrc**, **.vscode/settings.json**, **AUTHORS.md**, **LICENSE**, **README.md**, **INSTALL.md**, **REQUISITES.md**, **TODO.md**, **NEWS.md**);
* Added version macros, **--version**, and explicit **windows.h** include;
* Retired the broken nmake **Makefile**;


<!-- ########################### end of file ########################### -->
