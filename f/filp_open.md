# Function: <code>filp_open</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct file *filp_open(const char *filename, int flags, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8120b640)
Location: fs/open.c:989
Inline: False
Direct callers:
  - fs/coredump.c:do_coredump
  - security/integrity/iint.c:integrity_read_file
  - drivers/base/firmware_class.c:_request_firmware
```
**Symbols:**

```
ffffffff8120b640-ffffffff8120b695: filp_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct file *filp_open(const char *filename, int flags, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff81231370)
Location: fs/open.c:982
Inline: False
Direct callers:
  - fs/exec.c:kernel_read_file_from_path
  - fs/coredump.c:do_coredump
  - security/integrity/iint.c:integrity_read_file
```
**Symbols:**

```
ffffffff81231370-ffffffff812313c5: filp_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct file *filp_open(const char *filename, int flags, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff81243920)
Location: fs/open.c:999
Inline: False
Direct callers:
  - fs/exec.c:kernel_read_file_from_path
  - fs/coredump.c:do_coredump
  - security/integrity/iint.c:integrity_read_file
```
**Symbols:**

```
ffffffff81243920-ffffffff81243975: filp_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct file *filp_open(const char *filename, int flags, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8124f0c0)
Location: fs/open.c:1005
Inline: False
Direct callers:
  - fs/exec.c:kernel_read_file_from_path
  - fs/coredump.c:do_coredump
  - security/integrity/iint.c:integrity_read_file
```
**Symbols:**

```
ffffffff8124f0c0-ffffffff8124f115: filp_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct file *filp_open(const char *filename, int flags, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff81271040)
Location: fs/open.c:1005
Inline: False
Direct callers:
  - fs/exec.c:kernel_read_file_from_path
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffff81271040-ffffffff81271095: filp_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct file *filp_open(const char *filename, int flags, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff81296ca0)
Location: fs/open.c:1047
Inline: False
Direct callers:
  - fs/exec.c:kernel_read_file_from_path
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffff81296ca0-ffffffff81296cf5: filp_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct file *filp_open(const char *filename, int flags, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812ab940)
Location: fs/open.c:1034
Inline: False
Direct callers:
  - fs/exec.c:kernel_read_file_from_path
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffff812ab940-ffffffff812ab995: filp_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct file *filp_open(const char *filename, int flags, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812c8140)
Location: fs/open.c:1054
Inline: False
Direct callers:
  - fs/exec.c:kernel_read_file_from_path
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffff812c8140-ffffffff812c8193: filp_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct file *filp_open(const char *filename, int flags, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812d9b50)
Location: fs/open.c:1059
Inline: False
Direct callers:
  - fs/exec.c:kernel_read_file_from_path
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffff812d9b50-ffffffff812d9ba3: filp_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct file *filp_open(const char *filename, int flags, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff81310390)
Location: fs/open.c:1139
Inline: False
Direct callers:
  - fs/exec.c:kernel_read_file_from_path
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffff81310390-ffffffff813103e3: filp_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct file *filp_open(const char *filename, int flags, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8131c650)
Location: fs/open.c:1132
Inline: False
Direct callers:
  - init/main.c:console_on_rootfs
  - init/initramfs.c:do_name
  - fs/kernel_read_file.c:kernel_read_file_from_path
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffff8131c650-ffffffff8131c6a3: filp_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct file *filp_open(const char *filename, int flags, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff813227c0)
Location: fs/open.c:1154
Inline: False
Direct callers:
  - init/main.c:console_on_rootfs
  - init/initramfs.c:do_name
  - fs/kernel_read_file.c:kernel_read_file_from_path
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffff813227c0-ffffffff81322813: filp_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct file *filp_open(const char *filename, int flags, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8136fcb0)
Location: fs/open.c:1172
Inline: False
Direct callers:
  - init/main.c:console_on_rootfs
  - init/initramfs.c:do_name
  - fs/kernel_read_file.c:kernel_read_file_from_path
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffff8136fcb0-ffffffff8136fd03: filp_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct file *filp_open(const char *filename, int flags, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff813ee620)
Location: fs/open.c:1237
Inline: False
Direct callers:
  - init/main.c:console_on_rootfs
  - init/initramfs.c:do_name
  - fs/kernel_read_file.c:kernel_read_file_from_path
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffff813ee620-ffffffff813ee689: filp_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct file *filp_open(const char *filename, int flags, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff81476e70)
Location: fs/open.c:1269
Inline: False
Direct callers:
  - init/main.c:console_on_rootfs
  - init/initramfs.c:do_name
  - fs/kernel_read_file.c:kernel_read_file_from_path
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffff81476e70-ffffffff81476ed9: filp_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct file *filp_open(const char *filename, int flags, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff814ab7c0)
Location: fs/open.c:1366
Inline: False
Direct callers:
  - init/main.c:console_on_rootfs
  - init/initramfs.c:do_name
  - fs/kernel_read_file.c:kernel_read_file_from_path
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffff814ab7c0-ffffffff814ab829: filp_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct file *filp_open(const char *filename, int flags, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff814dcc60)
Location: fs/open.c:1363
Inline: False
Direct callers:
  - init/main.c:console_on_rootfs
  - init/initramfs.c:do_name
  - fs/kernel_read_file.c:kernel_read_file_from_path
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffff814dcc60-ffffffff814dccc9: filp_open (STB_GLOBAL)
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
struct file *filp_open(const char *filename, int flags, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffff80001037eec0)
Location: fs/open.c:1059
Inline: False
Direct callers:
  - fs/exec.c:kernel_read_file_from_path
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffff80001037eec0-ffff80001037ef3c: filp_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct file *filp_open(const char *filename, int flags, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (c05697d8)
Location: fs/open.c:1059
Inline: False
Direct callers:
  - fs/exec.c:kernel_read_file_from_path
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
c05697d8-c0569828: filp_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct file *filp_open(const char *filename, int flags, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (c000000000474cf0)
Location: fs/open.c:1059
Inline: False
Direct callers:
  - fs/exec.c:kernel_read_file_from_path
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
c000000000474cf0-c000000000474d78: filp_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct file *filp_open(const char *filename, int flags, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffe000254ad6)
Location: fs/open.c:1059
Inline: False
Direct callers:
  - fs/exec.c:kernel_read_file_from_path
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffe000254ad6-ffffffe000254b30: filp_open (STB_GLOBAL)
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
struct file *filp_open(const char *filename, int flags, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812d2130)
Location: fs/open.c:1059
Inline: False
Direct callers:
  - fs/exec.c:kernel_read_file_from_path
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffff812d2130-ffffffff812d2183: filp_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct file *filp_open(const char *filename, int flags, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812c2db0)
Location: fs/open.c:1059
Inline: False
Direct callers:
  - fs/exec.c:kernel_read_file_from_path
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffff812c2db0-ffffffff812c2e03: filp_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct file *filp_open(const char *filename, int flags, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812cff40)
Location: fs/open.c:1059
Inline: False
Direct callers:
  - fs/exec.c:kernel_read_file_from_path
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffff812cff40-ffffffff812cff93: filp_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct file *filp_open(const char *filename, int flags, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812e0d50)
Location: fs/open.c:1059
Inline: False
Direct callers:
  - fs/exec.c:kernel_read_file_from_path
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffff812e0d50-ffffffff812e0da3: filp_open (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
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
