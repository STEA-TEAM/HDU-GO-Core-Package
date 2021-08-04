# HDU-GO-Core
The core logic for HDU CAS system

## Notice

This library could only be used in [Drogon](https://github.com/drogonframework/drogon) based projects! 

## Usage

```cmake
find_package(HdugoCore REQUIRED PATHS ${PATH_WHERE_PACKAGE_STORED})
target_link_libraries(${PROJECT_NAME} PRIVATE HdugoCore::HdugoCore)
```

