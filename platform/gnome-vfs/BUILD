OPTS+=" --enable-gnutls --disable-openssl --disable-static --disable-hal --disable-howl"

./configure  --prefix=${GNOME210_PREFIX:-/usr}  \
             --build=$BUILD        \
             --sysconfdir=/etc     \
             --localstatedir=/var  \
             --infodir=${GNOME210_PREFIX:-/usr}/share/info  \
             --mandir=${GNOME210_PREFIX:-/usr}/share/man    \
             --enable-cdda                                  \
             $OPTS                                         &&
default_make
