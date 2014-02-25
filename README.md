This is a script to build unrealircd debian package.

You need to install dh-make, dh-systemd, devscripts, and autotools-dev
in order to build debian package.

Run build.sh, then you will get debian package.

After you install this pacakge, you need to write
your own /etc/unrealircd/unrealircd.conf.

I have not tested this package works with systemd, it's experimental.

---

これは unrealircd の deb パッケージを作るためのスクリプトです。

deb パッケージを作るためには dh-make, dh-systemd, devscripts, autotools-dev
をインストールする必要があります。

build.sh を実行することで、自動的にパッケージが作られます。

インストール後は、 /etc/unrealircd/unrealircd.conf を自分で作成する必要があります。

systemd でも動かせるはずですが、まだテストされておらず、実験段階です。
