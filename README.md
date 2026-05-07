This release provides a statically built `resize2fs` binary for the NextDrive CubeJ1.
It enables on-device expansion of ext4 partitions in environments where standard
tools (e2fsprogs) are not available.

### 🔧 Overview
- Designed for CubeJ1’s minimal Android/Linux hybrid environment.
- Built with minimal external dependencies to ensure compatibility.
- Useful for expanding system_b, userdata, and other ext4 partitions directly on the device.
- Complements BusyBox/ToyBox, which do not include resize2fs.

### 📁 Included Files
- resize2fs (executable binary)

### 📝 Usage Example
