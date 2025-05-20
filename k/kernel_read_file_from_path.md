# Function: <code>kernel_read_file_from_path</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int kernel_read_file_from_path(char *path, void **buf, loff_t *size, loff_t max_size, enum kernel_read_file_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812396b0)
Location: fs/exec.c:958
Inline: False
Direct callers:
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - drivers/base/firmware_class.c:_request_firmware
```
**Symbols:**

```
ffffffff812396b0-ffffffff81239720: kernel_read_file_from_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int kernel_read_file_from_path(char *path, void **buf, loff_t *size, loff_t max_size, enum kernel_read_file_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff8124c3f0)
Location: fs/exec.c:963
Inline: False
Direct callers:
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - drivers/base/firmware_class.c:_request_firmware
```
**Symbols:**

```
ffffffff8124c3f0-ffffffff8124c460: kernel_read_file_from_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int kernel_read_file_from_path(char *path, void **buf, loff_t *size, loff_t max_size, enum kernel_read_file_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812584f0)
Location: fs/exec.c:989
Inline: False
Direct callers:
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - drivers/base/firmware_class.c:_request_firmware
```
**Symbols:**

```
ffffffff812584f0-ffffffff81258562: kernel_read_file_from_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int kernel_read_file_from_path(const char *path, void **buf, loff_t *size, loff_t max_size, enum kernel_read_file_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff8127a860)
Location: fs/exec.c:970
Inline: False
Direct callers:
  - security/integrity/digsig.c:integrity_load_x509
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - drivers/base/firmware_class.c:_request_firmware
```
**Symbols:**

```
ffffffff8127a860-ffffffff8127a8d2: kernel_read_file_from_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int kernel_read_file_from_path(const char *path, void **buf, loff_t *size, loff_t max_size, enum kernel_read_file_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812a13a0)
Location: fs/exec.c:974
Inline: False
Direct callers:
  - security/integrity/digsig.c:integrity_load_x509
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - drivers/base/firmware_loader/main.c:_request_firmware
```
**Symbols:**

```
ffffffff812a13a0-ffffffff812a141d: kernel_read_file_from_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int kernel_read_file_from_path(const char *path, void **buf, loff_t *size, loff_t max_size, enum kernel_read_file_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812b6640)
Location: fs/exec.c:977
Inline: False
Direct callers:
  - security/integrity/digsig.c:integrity_load_x509
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - drivers/base/firmware_loader/main.c:_request_firmware
```
**Symbols:**

```
ffffffff812b6640-ffffffff812b66bd: kernel_read_file_from_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int kernel_read_file_from_path(const char *path, void **buf, loff_t *size, loff_t max_size, enum kernel_read_file_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812d33a0)
Location: fs/exec.c:978
Inline: False
Direct callers:
  - security/integrity/digsig.c:integrity_load_x509
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
```
**Symbols:**

```
ffffffff812d33a0-ffffffff812d3416: kernel_read_file_from_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int kernel_read_file_from_path(const char *path, void **buf, loff_t *size, loff_t max_size, enum kernel_read_file_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812e4f30)
Location: fs/exec.c:978
Inline: False
Direct callers:
  - security/integrity/digsig.c:integrity_load_x509
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
```
**Symbols:**

```
ffffffff812e4f30-ffffffff812e4fa6: kernel_read_file_from_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int kernel_read_file_from_path(const char *path, void **buf, loff_t *size, loff_t max_size, enum kernel_read_file_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff8131bfe0)
Location: fs/exec.c:1003
Inline: False
Direct callers:
  - security/integrity/digsig.c:integrity_load_x509
  - security/integrity/ima/ima_fs.c:ima_read_policy
```
**Symbols:**

```
ffffffff8131bfe0-ffffffff8131c056: kernel_read_file_from_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int kernel_read_file_from_path(const char *path, loff_t offset, void **buf, size_t buf_size, size_t *file_size, enum kernel_read_file_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernel_read_file.c (ffffffff81365d90)
Location: fs/kernel_read_file.c:127
Inline: False
Direct callers:
  - security/integrity/digsig.c:integrity_load_x509
  - security/integrity/ima/ima_fs.c:ima_read_policy
```
**Symbols:**

```
ffffffff81365d90-ffffffff81365e16: kernel_read_file_from_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int kernel_read_file_from_path(const char *path, loff_t offset, void **buf, size_t buf_size, size_t *file_size, enum kernel_read_file_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernel_read_file.c (ffffffff8136c7d0)
Location: fs/kernel_read_file.c:127
Inline: False
Direct callers:
  - security/integrity/digsig.c:integrity_load_x509
  - security/integrity/ima/ima_fs.c:ima_read_policy
```
**Symbols:**

```
ffffffff8136c7d0-ffffffff8136c856: kernel_read_file_from_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int kernel_read_file_from_path(const char *path, loff_t offset, void **buf, size_t buf_size, size_t *file_size, enum kernel_read_file_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernel_read_file.c (ffffffff813bb4a0)
Location: fs/kernel_read_file.c:127
Inline: False
Direct callers:
  - security/integrity/digsig.c:integrity_load_x509
  - security/integrity/ima/ima_fs.c:ima_read_policy
```
**Symbols:**

```
ffffffff813bb4a0-ffffffff813bb526: kernel_read_file_from_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int kernel_read_file_from_path(const char *path, loff_t offset, void **buf, size_t buf_size, size_t *file_size, enum kernel_read_file_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernel_read_file.c (ffffffff81441460)
Location: fs/kernel_read_file.c:127
Inline: False
Direct callers:
  - security/integrity/digsig.c:integrity_load_x509
  - security/integrity/ima/ima_fs.c:ima_read_policy
```
**Symbols:**

```
ffffffff81441460-ffffffff814414f8: kernel_read_file_from_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t kernel_read_file_from_path(const char *path, loff_t offset, void **buf, size_t buf_size, size_t *file_size, enum kernel_read_file_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernel_read_file.c (ffffffff814d03e0)
Location: fs/kernel_read_file.c:127
Inline: False
Direct callers:
  - security/integrity/digsig.c:integrity_load_x509
  - security/integrity/ima/ima_fs.c:ima_read_policy
```
**Symbols:**

```
ffffffff814d03e0-ffffffff814d0479: kernel_read_file_from_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t kernel_read_file_from_path(const char *path, loff_t offset, void **buf, size_t buf_size, size_t *file_size, enum kernel_read_file_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernel_read_file.c (ffffffff81506690)
Location: fs/kernel_read_file.c:127
Inline: False
Direct callers:
  - security/integrity/digsig.c:integrity_load_x509
  - security/integrity/ima/ima_fs.c:ima_read_policy
```
**Symbols:**

```
ffffffff81506690-ffffffff81506729: kernel_read_file_from_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t kernel_read_file_from_path(const char *path, loff_t offset, void **buf, size_t buf_size, size_t *file_size, enum kernel_read_file_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernel_read_file.c (ffffffff8153b3b0)
Location: fs/kernel_read_file.c:127
Inline: False
Direct callers:
  - security/integrity/digsig.c:integrity_load_x509
  - security/integrity/ima/ima_fs.c:ima_read_policy
```
**Symbols:**

```
ffffffff8153b3b0-ffffffff8153b449: kernel_read_file_from_path (STB_GLOBAL)
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
int kernel_read_file_from_path(const char *path, void **buf, loff_t *size, loff_t max_size, enum kernel_read_file_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffff80001038c9e8)
Location: fs/exec.c:978
Inline: False
Direct callers:
  - security/integrity/digsig.c:integrity_load_x509
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
```
**Symbols:**

```
ffff80001038c9e8-ffff80001038ca88: kernel_read_file_from_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int kernel_read_file_from_path(const char *path, void **buf, loff_t *size, loff_t max_size, enum kernel_read_file_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (c057462c)
Location: fs/exec.c:978
Inline: False
Direct callers:
  - security/integrity/digsig.c:integrity_load_x509
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
```
**Symbols:**

```
c057462c-c05746b8: kernel_read_file_from_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int kernel_read_file_from_path(const char *path, void **buf, loff_t *size, loff_t max_size, enum kernel_read_file_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (c000000000484a00)
Location: fs/exec.c:978
Inline: False
Direct callers:
  - security/integrity/digsig.c:integrity_load_x509
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
```
**Symbols:**

```
c000000000484a00-c000000000484ae8: kernel_read_file_from_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int kernel_read_file_from_path(const char *path, void **buf, loff_t *size, loff_t max_size, enum kernel_read_file_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffe00025dfa2)
Location: fs/exec.c:978
Inline: False
Direct callers:
  - security/integrity/digsig.c:integrity_load_x509
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
```
**Symbols:**

```
ffffffe00025dfa2-ffffffe00025e022: kernel_read_file_from_path (STB_GLOBAL)
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
int kernel_read_file_from_path(const char *path, void **buf, loff_t *size, loff_t max_size, enum kernel_read_file_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812dd510)
Location: fs/exec.c:978
Inline: False
Direct callers:
  - security/integrity/digsig.c:integrity_load_x509
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
```
**Symbols:**

```
ffffffff812dd510-ffffffff812dd586: kernel_read_file_from_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int kernel_read_file_from_path(const char *path, void **buf, loff_t *size, loff_t max_size, enum kernel_read_file_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812ce190)
Location: fs/exec.c:978
Inline: False
Direct callers:
  - security/integrity/digsig.c:integrity_load_x509
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
```
**Symbols:**

```
ffffffff812ce190-ffffffff812ce206: kernel_read_file_from_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int kernel_read_file_from_path(const char *path, void **buf, loff_t *size, loff_t max_size, enum kernel_read_file_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812db320)
Location: fs/exec.c:978
Inline: False
Direct callers:
  - security/integrity/digsig.c:integrity_load_x509
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - drivers/base/firmware_loader/main.c:_request_firmware
```
**Symbols:**

```
ffffffff812db320-ffffffff812db396: kernel_read_file_from_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int kernel_read_file_from_path(const char *path, void **buf, loff_t *size, loff_t max_size, enum kernel_read_file_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812ec2a0)
Location: fs/exec.c:978
Inline: False
Direct callers:
  - security/integrity/digsig.c:integrity_load_x509
  - security/integrity/ima/ima_fs.c:ima_write_policy
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
```
**Symbols:**

```
ffffffff812ec2a0-ffffffff812ec316: kernel_read_file_from_path (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>char *path</code> ➡️ <code>const char *path</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>loff_t offset</code>
</li>
<li>
<b>Param added. </b>
<code>size_t buf_size</code>
</li>
<li>
<b>Param added. </b>
<code>size_t *file_size</code>
</li>
<li>
<b>Param removed. </b>
<code>loff_t *size</code>
</li>
<li>
<b>Param removed. </b>
<code>loff_t max_size</code>
</li>
<li>
<b>Param reordered. </b>
<code>path, buf, size, max_size, id</code> ➡️ <code>path, offset, buf, buf_size, file_size, id</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>ssize_t</code>
</li>
</ul>
</details>
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
