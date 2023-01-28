# libspinners-cpp

[![](https://img.shields.io/github/v/tag/thechampagne/libspinners-hpp?label=version)](https://github.com/thechampagne/libspinners-hpp/releases/latest) [![](https://img.shields.io/github/license/thechampagne/libspinners-hpp)](https://github.com/thechampagne/libspinners-hpp/blob/main/LICENSE)

C++ binding for **libspinners** an elegant terminal spinners.

### API

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

This repo is released under the [MIT](https://github.com/thechampagne/libspinners-hpp/blob/main/LICENSE).
