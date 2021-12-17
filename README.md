# host.fl
Get information about host computer

## Installation
Run `install.sh` as root.

## Usage
Check `example.fl` for an example.<br/>
Functions: 
* [host/arch](#hostarch)
* [host/hostname](#hosthostname)
* [host/kernel](#hostkernel)
* [host/user](#hostuser)

### host/arch
**IN:** None<br/>
**OUT:** arch_ret

Returns architecture.<br/>
Example:
```
use host/arch
outv arch_ret
```
Output: `x86_64`

### host/hostname
**IN:** None<br/>
**OUT:** hostname_ret

Returns hostname.<br/>
Example:
```
use host/hostname
outv hostname_ret
```
Output: `KatrPC`

### host/kernel
**IN:** None<br/>
**OUT:** kernel_ret

Returns kernel name and version.<br/>
Example:
```
use host/kernel
outv kernel_ret
```
Output: `Linux 5.15.7-arch1-1`

### host/user
**IN:** None<br/>
**OUT:** user_ret

Returns username.<br/>
Example:
```
use host/user
outv user_ret
```
Output: `cinar`
