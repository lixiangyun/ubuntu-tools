# ubuntu_tools
Ubuntu system based docker images tools box

## usage

```
docker pull linimbus/ubuntu-tools
docker run -it --rm linimbus/ubuntu-tools /bin/bash
```

## tools
```
!                               grpck                           readarray
./                              grpconv                         readelf
2to3                            grpunconv                       readlink
2to3-2.7                        gunzip                          readonly
:                               gzexe                           readprofile
MAKEDEV                         gzip                            realpath
[                               h2ph                            reboot
[[                              h2xs                            remove-shell
]]                              halt                            rename
add-shell                       hash                            rename.ul
addgroup                        head                            renice
addpart                         help                            reset
addr2line                       history                         resize2fs
adduser                         host                            resizepart
agetty                          hostid                          return
alias                           hostname                        rev
apt                             hostnamectl                     rgrep
apt-cache                       hwclock                         rlogin
apt-cdrom                       i386                            rm
apt-config                      iconv                           rmdir
apt-get                         iconvconfig                     rmmod
apt-key                         id                              rmt
apt-mark                        if                              rmt-tar
ar                              ifconfig                        route
arch                            ifdown                          routef
arp                             ifquery                         routel
arpd                            ifup                            rpcgen
as                              in                              rsh
awk                             infocmp                         rsync
badblocks                       infotocap                       rtacct
base32                          init                            rtcwake
base64                          initctl                         rtmon
basename                        insmod                          rtstat
bash                            install                         run-mailcap
bashbug                         install-menu                    run-parts
bcc-lua                         install-sgmlcatalog             runcon
bg                              installkernel                   runlevel
bind                            instmodsh                       runuser
bison                           invoke-rc.d                     savelog
bison.yacc                      ionice                          scp
blkdiscard                      ip                              script
blkid                           ip6tables                       scriptreplay
blockdev                        ip6tables-apply                 sdiff
bootctl                         ip6tables-restore               sed
break                           ip6tables-save                  see
bridge                          ipcmk                           select
bugpoint-3.7                    ipcrm                           select-editor
builtin                         ipcs                            sensible-browser
bunzip2                         ipmaddr                         sensible-editor
busctl                          iptables                        sensible-pager
bzcat                           iptables-apply                  seq
bzcmp                           iptables-restore                service
bzdiff                          iptables-save                   set
bzegrep                         iptables-xml                    setarch
bzexe                           iptunnel                        setcap
bzfgrep                         ischroot                        setsid
bzgrep                          isosize                         setterm
bzip2                           jobs                            sfdisk
bzip2recover                    join                            sftp
bzless                          journalctl                      sg
bzmore                          json_pp                         sh
c++                             kill                            sh.distrib
c++filt                         killall5                        sha1sum
c2ph                            kmod                            sha224sum
c89                             l                               sha256sum
c89-gcc                         la                              sha384sum
c99                             last                            sha512sum
c99-gcc                         lastb                           shadowconfig
c_rehash                        lastlog                         shasum
caller                          ld                              shift
capsh                           ld.bfd                          shopt
captoinfo                       ld.gold                         shred
case                            ldattach                        shuf
cat                             ldconfig                        shutdown
catchsegv                       ldconfig.real                   size
cautious-launcher               ldd                             skill
cc                              less                            slabtop
cd                              lessecho                        slattach
cfdisk                          lessfile                        sleep
chage                           lesskey                         slogin
chardet                         lesspipe                        snice
chardetect                      let                             sort
chattr                          lex                             sotruss
chcon                           libnetcfg                       source
chcpu                           line                            splain
chfn                            link                            split
chgpasswd                       linux32                         sprof
chgrp                           linux64                         ss
chmod                           ll                              ssh
chown                           llc-3.7                         ssh-add
chpasswd                        lli-3.7                         ssh-agent
chroot                          lli-child-target-3.7            ssh-argv0
chrt                            llvm-ar-3.7                     ssh-copy-id
chsh                            llvm-as-3.7                     ssh-keygen
cksum                           llvm-bcanalyzer-3.7             ssh-keyscan
clear                           llvm-config-3.7                 start-stop-daemon
clear_console                   llvm-cov-3.7                    stat
cmake                           llvm-cxxdump-3.7                stdbuf
cmp                             llvm-diff-3.7                   strace
comm                            llvm-dis-3.7                    strings
command                         llvm-dsymutil-3.7               strip
compgen                         llvm-dwarfdump-3.7              stty
complete                        llvm-extract-3.7                su
compopt                         llvm-link-3.7                   su-to-root
compose                         llvm-mc-3.7                     sulogin
continue                        llvm-mcmarkup-3.7               sum
coproc                          llvm-nm-3.7                     suspend
corelist                        llvm-objdump-3.7                swaplabel
cp                              llvm-pdbdump-3.7                swapoff
cpack                           llvm-profdata-3.7               swapon
cpan                            llvm-ranlib-3.7                 switch_root
cpan5.22-x86_64-linux-gnu       llvm-readobj-3.7                sync
cpgr                            llvm-rtdyld-3.7                 sysctl
cpp                             llvm-size-3.7                   sysdig
cpp-5                           llvm-stress-3.7                 systemctl
cppw                            llvm-symbolizer-3.7             systemd
csplit                          llvm-tblgen-3.7                 systemd-analyze
csysdig                         ln                              systemd-ask-password
ctest                           lnstat                          systemd-cat
ctrlaltdel                      local                           systemd-cgls
ctstat                          locale                          systemd-cgtop
curl                            localectl                       systemd-delta
cut                             localedef                       systemd-detect-virt
dash                            logger                          systemd-escape
date                            login                           systemd-inhibit
dd                              loginctl                        systemd-machine-id-setup
deb-systemd-helper              logname                         systemd-notify
deb-systemd-invoke              logout                          systemd-path
debconf                         logsave                         systemd-resolve
debconf-apt-progress            losetup                         systemd-run
debconf-communicate             ls                              systemd-stdio-bridge
debconf-copydb                  lsattr                          systemd-tmpfiles
debconf-escape                  lsblk                           systemd-tty-ask-password-agent
debconf-set-selections          lscpu                           tabs
debconf-show                    lsipc                           tac
debugfs                         lslocks                         tail
declare                         lslogins                        tailf
delgroup                        lsmod                           tar
delpart                         lspgpot                         tarcat
deluser                         ltrace                          taskset
depmod                          luajit                          tc
df                              luajit-2.0.4                    tcpdump
dh_dkms                         lzcat                           tee
dh_installxmlcatalogs           lzcmp                           telinit
dh_python2                      lzdiff                          tempfile
dhclient                        lzegrep                         test
dhclient-script                 lzfgrep                         then
diff                            lzgrep                          tic
diff3                           lzless                          time
dig                             lzma                            timedatectl
dir                             lzmainfo                        timeout
dircolors                       lzmore                          times
dirname                         m4                              tipc
dirs                            macho-dump-3.7                  tload
disown                          make                            toe
dkms                            make-first-existing-target      top
dmesg                           mapfile                         touch
dnsdomainname                   mawk                            tput
do                              mcookie                         tr
domainname                      md5sum                          trap
done                            md5sum.textutils                true
dpkg                            mesg                            truncate
dpkg-architecture               mii-tool                        tset
dpkg-buildflags                 mkdir                           tsort
dpkg-buildpackage               mke2fs                          tty
dpkg-checkbuilddeps             mkfifo                          tune2fs
dpkg-deb                        mkfs                            tunelp
dpkg-distaddfile                mkfs.bfs                        type
dpkg-divert                     mkfs.cramfs                     typeset
dpkg-genchanges                 mkfs.ext2                       tzselect
dpkg-gencontrol                 mkfs.ext3                       ulimit
dpkg-gensymbols                 mkfs.ext4                       umask
dpkg-maintscript-helper         mkfs.ext4dev                    umount
dpkg-mergechangelogs            mkfs.minix                      unalias
dpkg-name                       mkhomedir_helper                uname
dpkg-parsechangelog             mklost+found                    uncompress
dpkg-preconfigure               mknod                           unexpand
dpkg-query                      mkpasswd                        uniq
dpkg-reconfigure                mkswap                          unix_chkpwd
dpkg-scanpackages               mktemp                          unix_update
dpkg-scansources                modinfo                         unlink
dpkg-shlibdeps                  modprobe                        unlzma
dpkg-source                     more                            unset
dpkg-split                      mount                           unshare
dpkg-statoverride               mountpoint                      until
dpkg-trigger                    mtrace                          unxz
dpkg-vendor                     mv                              update-alternatives
du                              namei                           update-binfmts
dumpe2fs                        nameif                          update-ca-certificates
dwp                             nawk                            update-catalog
e2freefrag                      ncat                            update-menus
e2fsck                          ndiff                           update-mime
e2image                         netstat                         update-mime-database
e2label                         networkctl                      update-mime-database.real
e2undo                          newgrp                          update-passwd
e4defrag                        newusers                        update-rc.d
echo                            nfnl_osf                        update-xmlcatalog
edit                            nice                            uptime
egrep                           nisdomainname                   useradd
elfedit                         nl                              userdel
elif                            nm                              usermod
else                            nmap                            users
enable                          nohup                           utmpdump
enc2xs                          nologin                         vdir
encguess                        nping                           verify-uselistorder-3.7
env                             nproc                           vigr
esac                            nsenter                         vipw
ethtool                         nslookup                        vmstat
eval                            nstat                           w
exec                            nsupdate                        w.procps
exit                            numfmt                          wait
expand                          obj2yaml-3.7                    wall
expiry                          objcopy                         watch
export                          objdump                         wc
expr                            od                              wdctl
factor                          openssl                         wget
faillog                         opt-3.7                         whereis
faked-sysv                      pager                           which
faked-tcp                       pam-auth-update                 while
fakeroot                        pam_extrausers_chkpwd           who
fakeroot-sysv                   pam_extrausers_update           whoami
fakeroot-tcp                    pam_getenv                      whois
fallocate                       pam_tally                       wipefs
false                           pam_tally2                      x86_64
fc                              pam_timestamp_check             x86_64-linux-gnu-addr2line
fdformat                        partx                           x86_64-linux-gnu-ar
fdisk                           passwd                          x86_64-linux-gnu-as
fg                              paste                           x86_64-linux-gnu-c++filt
fgrep                           patch                           x86_64-linux-gnu-cpp
fi                              pathchk                         x86_64-linux-gnu-cpp-5
file                            pdb                             x86_64-linux-gnu-dwp
file-rename                     pdb2.7                          x86_64-linux-gnu-elfedit
filefrag                        perl                            x86_64-linux-gnu-g++
find                            perl5.22-x86_64-linux-gnu       x86_64-linux-gnu-g++-5
findfs                          perl5.22.1                      x86_64-linux-gnu-gcc
findmnt                         perlbug                         x86_64-linux-gnu-gcc-5
flex                            perldoc                         x86_64-linux-gnu-gcc-ar
flex++                          perlivp                         x86_64-linux-gnu-gcc-ar-5
flock                           perlthanks                      x86_64-linux-gnu-gcc-nm
fmt                             pg                              x86_64-linux-gnu-gcc-nm-5
fold                            pgrep                           x86_64-linux-gnu-gcc-ranlib
for                             piconv                          x86_64-linux-gnu-gcc-ranlib-5
free                            pidof                           x86_64-linux-gnu-gcov
fsck                            ping                            x86_64-linux-gnu-gcov-5
fsck.cramfs                     ping6                           x86_64-linux-gnu-gcov-tool
fsck.ext2                       pinky                           x86_64-linux-gnu-gcov-tool-5
fsck.ext3                       pivot_root                      x86_64-linux-gnu-gprof
fsck.ext4                       pkg-config                      x86_64-linux-gnu-ld
fsck.ext4dev                    pkill                           x86_64-linux-gnu-ld.bfd
fsck.minix                      pl2pm                           x86_64-linux-gnu-ld.gold
fsck.nfs                        pldd                            x86_64-linux-gnu-nm
fsfreeze                        plipconfig                      x86_64-linux-gnu-objcopy
fstab-decode                    pmap                            x86_64-linux-gnu-objdump
fstrim                          pod2html                        x86_64-linux-gnu-pkg-config
function                        pod2man                         x86_64-linux-gnu-ranlib
g++                             pod2text                        x86_64-linux-gnu-readelf
g++-5                           pod2usage                       x86_64-linux-gnu-size
gcc                             podchecker                      x86_64-linux-gnu-strings
gcc-5                           podselect                       x86_64-linux-gnu-strip
gcc-ar                          policy-rc.d                     x86_64-pc-linux-gnu-pkg-config
gcc-ar-5                        popd                            xargs
gcc-nm                          poweroff                        xauth
gcc-nm-5                        pr                              xdg-user-dir
gcc-ranlib                      prename                         xdg-user-dirs-update
gcc-ranlib-5                    print                           xsubpp
gcov                            printenv                        xtables-multi
gcov-5                          printf                          xz
gcov-tool                       prlimit                         xzcat
gcov-tool-5                     prove                           xzcmp
gencat                          ps                              xzdiff
genl                            pstruct                         xzegrep
getcap                          ptar                            xzfgrep
getconf                         ptardiff                        xzgrep
getent                          ptargrep                        xzless
getopt                          ptx                             xzmore
getopts                         pushd                           yacc
getpcaps                        pwck                            yaml2obj-3.7
getty                           pwconv                          yes
git                             pwd                             ypdomainname
git-receive-pack                pwdx                            zcat
git-shell                       pwunconv                        zcmp
git-upload-archive              pyclean                         zdiff
git-upload-pack                 pycompile                       zdump
go                              pydoc                           zegrep
gofmt                           pydoc2.7                        zfgrep
gold                            pygettext                       zforce
gpasswd                         pygettext2.7                    zgrep
gpg                             python                          zic
gpg-zip                         python2                         zipdetails
gpgsplit                        python2.7                       zless
gpgv                            pyversions                      zmore
gprof                           ranlib                          znew
grep                            rarp                            zramctl
groupadd                        raw                             {
groupdel                        rbash                           }
groupmod                        rcp                             
groups                          read   
```
