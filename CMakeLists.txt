# CMakeList.txt: CMake-Projekt für "CMakeTestProj". Schließen Sie die Quelle ein, und definieren Sie
# projektspezifische Logik hier.
#
cmake_minimum_required (VERSION 3.8)

project ("CMakeTestProj")

# Fügen Sie der ausführbaren Datei dieses Projekts eine Quelle hinzu.
add_executable (CMakeTestProj "CMakeTestProj.cpp" "CMakeTestProj.h" "Header.h")

# TODO: Fügen Sie bei Bedarf Tests hinzu, und installieren Sie Ziele.
