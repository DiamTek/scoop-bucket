<h1 align=\ center\>DiamTek Scoop Bucket</h1>

<p align=\center\>
  Official <a href=\https://scoop.sh\>Scoop</a> bucket for DiamTek software and utilities on Windows.
</p>

---

## 📦 How to Use

### 1. Add this Bucket to Scoop

`powershell
scoop bucket add diamtek https://github.com/DiamTek/scoop-bucket
`

### 2. Install Applications

`powershell
scoop install jvm
`

---

## 📋 Available Applications

| Application | Manifest | Description |
|---|---|---|
| **JVM** | [jvm](bucket/jvm.json) | Native Java Version Manager & SDKMAN! alternative for Windows |

---

## 🔄 Updating Applications

To update this bucket and all installed apps:

`powershell
scoop update
scoop update *
`

Or update JVM specifically:

`powershell
scoop update jvm
`

---

## 🗑️ Removing

`powershell
# Uninstall JVM
scoop uninstall jvm

# Remove bucket
scoop bucket rm diamtek
`

---

## 📄 License

The bucket manifests and repository are released under the [MIT License](LICENSE). Applications installed via this bucket have their own respective licenses.