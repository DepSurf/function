# Function: <code>fscrypt_ioctl_get_key_status</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int fscrypt_ioctl_get_key_status(struct file *filp, void *uarg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffff8134d1a0)
Location: fs/crypto/keyring.c:892
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
**Symbols:**

```
ffffffff8134d1a0-ffffffff8134d378: fscrypt_ioctl_get_key_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int fscrypt_ioctl_get_key_status(struct file *filp, void *uarg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffff81392a90)
Location: fs/crypto/keyring.c:1036
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
**Symbols:**

```
ffffffff81392a90-ffffffff81392c66: fscrypt_ioctl_get_key_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int fscrypt_ioctl_get_key_status(struct file *filp, void *uarg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffff813a3e00)
Location: fs/crypto/keyring.c:1044
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
```
**Symbols:**

```
ffffffff813a3e00-ffffffff813a3fd3: fscrypt_ioctl_get_key_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int fscrypt_ioctl_get_key_status(struct file *filp, void *uarg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffff813ab040)
Location: fs/crypto/keyring.c:1044
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
```
**Symbols:**

```
ffffffff813ab040-ffffffff813ab213: fscrypt_ioctl_get_key_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int fscrypt_ioctl_get_key_status(struct file *filp, void *uarg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffff813fa8d0)
Location: fs/crypto/keyring.c:1044
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
```
**Symbols:**

```
ffffffff813fa8d0-ffffffff813faaa3: fscrypt_ioctl_get_key_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int fscrypt_ioctl_get_key_status(struct file *filp, void *uarg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffff8146dc30)
Location: fs/crypto/keyring.c:1084
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
```
**Symbols:**

```
ffffffff8146dc30-ffffffff8146de1c: fscrypt_ioctl_get_key_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int fscrypt_ioctl_get_key_status(struct file *filp, void *uarg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffff814ff220)
Location: fs/crypto/keyring.c:1134
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
```
**Symbols:**

```
ffffffff814ff220-ffffffff814ff40e: fscrypt_ioctl_get_key_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int fscrypt_ioctl_get_key_status(struct file *filp, void *uarg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffff81536740)
Location: fs/crypto/keyring.c:1129
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
```
**Symbols:**

```
ffffffff81536740-ffffffff8153691b: fscrypt_ioctl_get_key_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int fscrypt_ioctl_get_key_status(struct file *filp, void *uarg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/keyring.c (0)
Location: fs/crypto/keyring.c:1141
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
```
**Symbols:**

```
ffffffff821c6f04-ffffffff821c6f19: fscrypt_ioctl_get_key_status.cold (STB_LOCAL)
ffffffff8156b7b0-ffffffff8156b9a5: fscrypt_ioctl_get_key_status (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int fscrypt_ioctl_get_key_status(struct file *filp, void *uarg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffff80001040e130)
Location: fs/crypto/keyring.c:892
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
**Symbols:**

```
ffff80001040e130-ffff80001040e430: fscrypt_ioctl_get_key_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fscrypt_ioctl_get_key_status(struct file *filp, void *uarg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (c05dadbc)
Location: fs/crypto/keyring.c:892
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
**Symbols:**

```
c05dadbc-c05daffc: fscrypt_ioctl_get_key_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int fscrypt_ioctl_get_key_status(struct file *filp, void *uarg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (c00000000051b600)
Location: fs/crypto/keyring.c:892
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
**Symbols:**

```
c00000000051b600-c00000000051b868: fscrypt_ioctl_get_key_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int fscrypt_ioctl_get_key_status(struct file *filp, void *uarg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffe0002b731c)
Location: fs/crypto/keyring.c:892
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
**Symbols:**

```
ffffffe0002b731c-ffffffe0002b74b6: fscrypt_ioctl_get_key_status (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int fscrypt_ioctl_get_key_status(struct file *filp, void *uarg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffff81345780)
Location: fs/crypto/keyring.c:892
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
**Symbols:**

```
ffffffff81345780-ffffffff81345958: fscrypt_ioctl_get_key_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int fscrypt_ioctl_get_key_status(struct file *filp, void *uarg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffff81336460)
Location: fs/crypto/keyring.c:892
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
**Symbols:**

```
ffffffff81336460-ffffffff81336638: fscrypt_ioctl_get_key_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int fscrypt_ioctl_get_key_status(struct file *filp, void *uarg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffff81343250)
Location: fs/crypto/keyring.c:892
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
**Symbols:**

```
ffffffff81343250-ffffffff81343428: fscrypt_ioctl_get_key_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int fscrypt_ioctl_get_key_status(struct file *filp, void *uarg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffff81356530)
Location: fs/crypto/keyring.c:892
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
**Symbols:**

```
ffffffff81356530-ffffffff81356708: fscrypt_ioctl_get_key_status (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
