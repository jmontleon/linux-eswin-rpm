# linux-eswin-rpm
This repo is deprecated. Use https://github.com/jmontleon/linux-rockos-rpm instead

This repo contains sources for building a Fedora-like HiFive P550 / EWSIN EIC7700 kernel.

Built kernels can currently be found at https://people.redhat.com/jmontleo/

For files too large to commit:
linux-6.6.Z.tar.xz source is generated from the linux-6.6y branch of:
git://git.kernel.org/pub/scm/linux/kernel/git/stable/linux.git using, for example:
`export ver=6.6.62; mv linux linux-${ver}; tar --exclude-vcs -Jcvf linux-${ver}.tar.xz linux-${ver}; mv linux-${ver} linux`
