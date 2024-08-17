# Task 01 (Git Check Implementation)

* Git Check — command validates git tree integrity

## Quick Start

```bash
./cmd/build
./cmd/main YOUR_DIR_PATH YOUR_ROOT_HASH
```

## Installation

### MacOS

```bash
brew install openssl
brew info openssl # get your path to openssl
```

* Update `OPENSSL` variable with your path in [build file](build)

## Testing

```bash
./cmd/test
```

See [test file](test), you can add your own tests here

### Implementation Details

* Status code
  * on success == 0
  * on fail == 1
* Debug Logs
  * One can disable debug logs by settings env variable: `DEBUG=0`
