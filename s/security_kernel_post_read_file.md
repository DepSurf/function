# Function: <code>security_kernel_post_read_file</code>

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
int security_kernel_post_read_file(struct file *file, char *buf, loff_t size, enum kernel_read_file_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81371cf0)
Location: security/security.c:935
Inline: False
Direct callers:
  - drivers/base/firmware_class.c:firmware_loading_store
```
**Symbols:**

```
ffffffff81371cf0-ffffffff81371d66: security_kernel_post_read_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int security_kernel_post_read_file(struct file *file, char *buf, loff_t size, enum kernel_read_file_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81388620)
Location: security/security.c:956
Inline: False
Direct callers:
  - drivers/base/firmware_class.c:firmware_loading_store
```
**Symbols:**

```
ffffffff81388620-ffffffff81388696: security_kernel_post_read_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int security_kernel_post_read_file(struct file *file, char *buf, loff_t size, enum kernel_read_file_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8139d680)
Location: security/security.c:1593
Inline: False
Direct callers:
  - drivers/base/firmware_class.c:firmware_loading_store
```
**Symbols:**

```
ffffffff8139d680-ffffffff8139d6f6: security_kernel_post_read_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int security_kernel_post_read_file(struct file *file, char *buf, loff_t size, enum kernel_read_file_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813c2f50)
Location: security/security.c:1555
Inline: False
Direct callers:
  - drivers/base/firmware_class.c:firmware_loading_store
```
**Symbols:**

```
ffffffff813c2f50-ffffffff813c2fcc: security_kernel_post_read_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int security_kernel_post_read_file(struct file *file, char *buf, loff_t size, enum kernel_read_file_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813f3b30)
Location: security/security.c:1059
Inline: False
Direct callers:
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
```
**Symbols:**

```
ffffffff813f3b30-ffffffff813f3b97: security_kernel_post_read_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int security_kernel_post_read_file(struct file *file, char *buf, loff_t size, enum kernel_read_file_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8140ef40)
Location: security/security.c:1656
Inline: False
Direct callers:
  - fs/exec.c:kernel_read_file
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
```
**Symbols:**

```
ffffffff8140ef40-ffffffff8140efa7: security_kernel_post_read_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int security_kernel_post_read_file(struct file *file, char *buf, loff_t size, enum kernel_read_file_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8143c300)
Location: security/security.c:1675
Inline: False
Direct callers:
  - fs/exec.c:kernel_read_file
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
```
**Symbols:**

```
ffffffff8143c300-ffffffff8143c374: security_kernel_post_read_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int security_kernel_post_read_file(struct file *file, char *buf, loff_t size, enum kernel_read_file_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81455ea0)
Location: security/security.c:1714
Inline: False
Direct callers:
  - fs/exec.c:kernel_read_file
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
```
**Symbols:**

```
ffffffff81455ea0-ffffffff81455f07: security_kernel_post_read_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int security_kernel_post_read_file(struct file *file, char *buf, loff_t size, enum kernel_read_file_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814a8cd0)
Location: security/security.c:1898
Inline: False
Direct callers:
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
```
**Symbols:**

```
ffffffff814a8cd0-ffffffff814a8d37: security_kernel_post_read_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int security_kernel_post_read_file(struct file *file, char *buf, loff_t size, enum kernel_read_file_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814c6250)
Location: security/security.c:1901
Inline: False
Direct callers:
  - fs/kernel_read_file.c:kernel_read_file
```
**Symbols:**

```
ffffffff814c6250-ffffffff814c62b7: security_kernel_post_read_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int security_kernel_post_read_file(struct file *file, char *buf, loff_t size, enum kernel_read_file_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814cc500)
Location: security/security.c:1951
Inline: False
Direct callers:
  - fs/kernel_read_file.c:kernel_read_file
```
**Symbols:**

```
ffffffff814cc500-ffffffff814cc567: security_kernel_post_read_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int security_kernel_post_read_file(struct file *file, char *buf, loff_t size, enum kernel_read_file_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81525390)
Location: security/security.c:1959
Inline: False
Direct callers:
  - fs/kernel_read_file.c:kernel_read_file
```
**Symbols:**

```
ffffffff81525390-ffffffff815253f7: security_kernel_post_read_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int security_kernel_post_read_file(struct file *file, char *buf, loff_t size, enum kernel_read_file_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff815b9340)
Location: security/security.c:1964
Inline: False
Direct callers:
  - fs/kernel_read_file.c:kernel_read_file
```
**Symbols:**

```
ffffffff815b9340-ffffffff815b93cc: security_kernel_post_read_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int security_kernel_post_read_file(struct file *file, char *buf, loff_t size, enum kernel_read_file_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81664ae0)
Location: security/security.c:2011
Inline: False
Direct callers:
  - fs/kernel_read_file.c:kernel_read_file
```
**Symbols:**

```
ffffffff81664ae0-ffffffff81664b6c: security_kernel_post_read_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int security_kernel_post_read_file(struct file *file, char *buf, loff_t size, enum kernel_read_file_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8169cfc0)
Location: security/security.c:3222
Inline: False
Direct callers:
  - fs/kernel_read_file.c:kernel_read_file
```
**Symbols:**

```
ffffffff8169cfc0-ffffffff8169d04c: security_kernel_post_read_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int security_kernel_post_read_file(struct file *file, char *buf, loff_t size, enum kernel_read_file_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816d9aa0)
Location: security/security.c:3294
Inline: False
Direct callers:
  - fs/kernel_read_file.c:kernel_read_file
```
**Symbols:**

```
ffffffff816d9aa0-ffffffff816d9b2c: security_kernel_post_read_file (STB_GLOBAL)
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
int security_kernel_post_read_file(struct file *file, char *buf, loff_t size, enum kernel_read_file_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffff8000105415c0)
Location: security/security.c:1714
Inline: False
Direct callers:
  - fs/exec.c:kernel_read_file
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
```
**Symbols:**

```
ffff8000105415c0-ffff800010541644: security_kernel_post_read_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int security_kernel_post_read_file(struct file *file, char *buf, loff_t size, enum kernel_read_file_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c06f75b0)
Location: security/security.c:1714
Inline: False
Direct callers:
  - fs/exec.c:kernel_read_file
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
```
**Symbols:**

```
c06f75b0-c06f7640: security_kernel_post_read_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int security_kernel_post_read_file(struct file *file, char *buf, loff_t size, enum kernel_read_file_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c000000000693dc0)
Location: security/security.c:1714
Inline: False
Direct callers:
  - fs/exec.c:kernel_read_file
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
```
**Symbols:**

```
c000000000693dc0-c000000000693e64: security_kernel_post_read_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int security_kernel_post_read_file(struct file *file, char *buf, loff_t size, enum kernel_read_file_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffe00039e2ba)
Location: security/security.c:1714
Inline: False
Direct callers:
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
```
**Symbols:**

```
ffffffe00039e2ba-ffffffe00039e31c: security_kernel_post_read_file (STB_GLOBAL)
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
int security_kernel_post_read_file(struct file *file, char *buf, loff_t size, enum kernel_read_file_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144e480)
Location: security/security.c:1714
Inline: False
Direct callers:
  - fs/exec.c:kernel_read_file
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
```
**Symbols:**

```
ffffffff8144e480-ffffffff8144e4e7: security_kernel_post_read_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int security_kernel_post_read_file(struct file *file, char *buf, loff_t size, enum kernel_read_file_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8143eed0)
Location: security/security.c:1714
Inline: False
Direct callers:
  - fs/exec.c:kernel_read_file
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
```
**Symbols:**

```
ffffffff8143eed0-ffffffff8143ef37: security_kernel_post_read_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int security_kernel_post_read_file(struct file *file, char *buf, loff_t size, enum kernel_read_file_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144a520)
Location: security/security.c:1714
Inline: False
Direct callers:
  - fs/exec.c:kernel_read_file
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
```
**Symbols:**

```
ffffffff8144a520-ffffffff8144a587: security_kernel_post_read_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int security_kernel_post_read_file(struct file *file, char *buf, loff_t size, enum kernel_read_file_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814618f0)
Location: security/security.c:1714
Inline: False
Direct callers:
  - fs/exec.c:kernel_read_file
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
```
**Symbols:**

```
ffffffff814618f0-ffffffff81461957: security_kernel_post_read_file (STB_GLOBAL)
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
