# libspinners-cpp

[![](https://img.shields.io/github/v/tag/thechampagne/libspinners-cpp?label=version)](https://github.com/thechampagne/libspinners-cpp/releases/latest) [![](https://img.shields.io/github/license/thechampagne/libspinners-cpp)](https://github.com/thechampagne/libspinners-cpp/blob/main/LICENSE)

C++ binding for **libspinners** an elegant terminal spinners.

### Example

```cpp
#include <unistd.h> // use #include <windows.h> for windows
#include "spinner.hpp"

int main(void)
{
  spinner::Spinner spin(spinner::SPINNER_SPINNERS_DOTS9, "Waiting for 3 seconds");
  sleep(3);
  spin.stop();
  return 0;
}
```

### References
 - [libspinners](https://github.com/thechampagne/libspinners)

### License

This repo is released under the [MIT](https://github.com/thechampagne/libspinners-cpp/blob/main/LICENSE).
