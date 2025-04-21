curl -L https://storage.googleapis.com/flutter_infra_release/releases/stable/linux/flutter_linux_3.22.0-stable.tar.xz -o flutter.tar.xz
tar -xf flutter.tar.xz# algolens
export PATH="$PATH:/workspaces/algolens/flutter/bin"
flutter create algolens_app
