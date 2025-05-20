# Function: <code>kernel_read_file_from_path_initns</code>

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
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int kernel_read_file_from_path_initns(const char *path, void **buf, loff_t *size, loff_t max_size, enum kernel_read_file_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff8131d270)
Location: fs/exec.c:1022
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
```
**Symbols:**

```
ffffffff8131d270-ffffffff8131d397: kernel_read_file_from_path_initns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int kernel_read_file_from_path_initns(const char *path, loff_t offset, void **buf, size_t buf_size, size_t *file_size, enum kernel_read_file_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernel_read_file.c (ffffffff81365eb0)
Location: fs/kernel_read_file.c:147
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
```
**Symbols:**

```
ffffffff81365eb0-ffffffff81365fe6: kernel_read_file_from_path_initns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int kernel_read_file_from_path_initns(const char *path, loff_t offset, void **buf, size_t buf_size, size_t *file_size, enum kernel_read_file_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernel_read_file.c (ffffffff8136c8f0)
Location: fs/kernel_read_file.c:147
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
```
**Symbols:**

```
ffffffff8136c8f0-ffffffff8136ca23: kernel_read_file_from_path_initns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int kernel_read_file_from_path_initns(const char *path, loff_t offset, void **buf, size_t buf_size, size_t *file_size, enum kernel_read_file_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernel_read_file.c (ffffffff813bb5c0)
Location: fs/kernel_read_file.c:147
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
```
**Symbols:**

```
ffffffff813bb5c0-ffffffff813bb6ed: kernel_read_file_from_path_initns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int kernel_read_file_from_path_initns(const char *path, loff_t offset, void **buf, size_t buf_size, size_t *file_size, enum kernel_read_file_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernel_read_file.c (ffffffff81441500)
Location: fs/kernel_read_file.c:147
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
```
**Symbols:**

```
ffffffff81441500-ffffffff81441642: kernel_read_file_from_path_initns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t kernel_read_file_from_path_initns(const char *path, loff_t offset, void **buf, size_t buf_size, size_t *file_size, enum kernel_read_file_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernel_read_file.c (ffffffff814d0490)
Location: fs/kernel_read_file.c:147
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
```
**Symbols:**

```
ffffffff814d0490-ffffffff814d05d6: kernel_read_file_from_path_initns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t kernel_read_file_from_path_initns(const char *path, loff_t offset, void **buf, size_t buf_size, size_t *file_size, enum kernel_read_file_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernel_read_file.c (ffffffff81506740)
Location: fs/kernel_read_file.c:147
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
```
**Symbols:**

```
ffffffff81506740-ffffffff81506886: kernel_read_file_from_path_initns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t kernel_read_file_from_path_initns(const char *path, loff_t offset, void **buf, size_t buf_size, size_t *file_size, enum kernel_read_file_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernel_read_file.c (ffffffff8153b460)
Location: fs/kernel_read_file.c:147
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
```
**Symbols:**

```
ffffffff8153b460-ffffffff8153b5a6: kernel_read_file_from_path_initns (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
