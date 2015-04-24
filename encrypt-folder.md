1. Google for _ubuntu encrypt folder_.
2. First result is https://help.ubuntu.com/community/FolderEncryption (last edited in October 2012).
3. Try out `encfs`, which is at version 1.7.4 (released November 2010) at Ubuntu 14.10.
4. https://github.com/vgough/encfs is alive, so there should be a future for this project.
5. encfs 1.7.4 as packaged in Ubuntu is usable as described in `FolderEncryption` page.

## April 24, 2015 update

On April 24, when I updated Ubuntu from 14.10 to 15.04 following `debconf` message showed up:

__Configiring encfs__

_According to a security audit by Taylor Hornby (Defuse Security), the current implementation of Encfs is vulnerable or potentially vulnerable to multiple types of attacks. For example, an attacker with read/write access to encrypted data might lower the decryption complexity for subsequently encrypted data without this being noticed by a legitimate user, or might use timing analysis to deduce information._

_Until these issues are resolved, encfs should not be considered a safe home for sensitive data in scenarios where such attacks are possible._
