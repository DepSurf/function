# Function: <code>safesetid_file_write</code>

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
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
ssize_t safesetid_file_write(struct file *file, const char *buf, size_t len, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/safesetid/securityfs.c (0)
Location: security/safesetid/securityfs.c:195
Inline: False
```
**Symbols:**

```
ffffffff81499490-ffffffff814997c6: safesetid_file_write (STB_LOCAL)
ffffffff814997c6-ffffffff81499857: safesetid_file_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
ssize_t safesetid_file_write(struct file *file, const char *buf, size_t len, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/safesetid/securityfs.c (0)
Location: security/safesetid/securityfs.c:195
Inline: False
```
**Symbols:**

```
ffffffff814b33b0-ffffffff814b36e6: safesetid_file_write (STB_LOCAL)
ffffffff814b36e6-ffffffff814b3777: safesetid_file_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t safesetid_file_write(struct file *file, const char *buf, size_t len, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/safesetid/securityfs.c (ffffffff81512b30)
Location: security/safesetid/securityfs.c:195
Inline: False
```
**Symbols:**

```
ffffffff81512b30-ffffffff81512b90: safesetid_file_write (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
ssize_t safesetid_file_write(struct file *file, const char *buf, size_t len, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/safesetid/securityfs.c (ffff8000105ab0b0)
Location: security/safesetid/securityfs.c:195
Inline: False
```
**Symbols:**

```
ffff8000105ab0b0-ffff8000105ab440: safesetid_file_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t safesetid_file_write(struct file *file, const char *buf, size_t len, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/safesetid/securityfs.c (c075ac38)
Location: security/safesetid/securityfs.c:195
Inline: False
```
**Symbols:**

```
c075ac38-c075b008: safesetid_file_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t safesetid_file_write(struct file *file, const char *buf, size_t len, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/safesetid/securityfs.c (c000000000728d50)
Location: security/safesetid/securityfs.c:195
Inline: False
```
**Symbols:**

```
c000000000728d50-c000000000729218: safesetid_file_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ssize_t safesetid_file_write(struct file *file, const char *buf, size_t len, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/safesetid/securityfs.c (ffffffe0003f3cb4)
Location: security/safesetid/securityfs.c:195
Inline: False
```
**Symbols:**

```
ffffffe0003f3cb4-ffffffe0003f3fe8: safesetid_file_write (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
ssize_t safesetid_file_write(struct file *file, const char *buf, size_t len, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/safesetid/securityfs.c (0)
Location: security/safesetid/securityfs.c:195
Inline: False
```
**Symbols:**

```
ffffffff814ab990-ffffffff814abcc6: safesetid_file_write (STB_LOCAL)
ffffffff814abcc6-ffffffff814abd57: safesetid_file_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
ssize_t safesetid_file_write(struct file *file, const char *buf, size_t len, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/safesetid/securityfs.c (0)
Location: security/safesetid/securityfs.c:195
Inline: False
```
**Symbols:**

```
ffffffff8149c3b0-ffffffff8149c6e6: safesetid_file_write (STB_LOCAL)
ffffffff8149c6e6-ffffffff8149c777: safesetid_file_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
ssize_t safesetid_file_write(struct file *file, const char *buf, size_t len, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/safesetid/securityfs.c (0)
Location: security/safesetid/securityfs.c:195
Inline: False
```
**Symbols:**

```
ffffffff814a7a30-ffffffff814a7d66: safesetid_file_write (STB_LOCAL)
ffffffff814a7d66-ffffffff814a7df7: safesetid_file_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
ssize_t safesetid_file_write(struct file *file, const char *buf, size_t len, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/safesetid/securityfs.c (0)
Location: security/safesetid/securityfs.c:195
Inline: False
```
**Symbols:**

```
ffffffff814c03c0-ffffffff814c06f6: safesetid_file_write (STB_LOCAL)
ffffffff814c06f6-ffffffff814c0787: safesetid_file_write.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
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
