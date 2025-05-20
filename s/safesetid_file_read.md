# Function: <code>safesetid_file_read</code>

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
<summary>In <code>5.3</code>: ✅</summary>

```c
ssize_t safesetid_file_read(struct file *file, char *buf, size_t len, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/safesetid/securityfs.c (ffffffff81499410)
Location: security/safesetid/securityfs.c:209
Inline: False
```
**Symbols:**

```
ffffffff81499410-ffffffff81499486: safesetid_file_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ssize_t safesetid_file_read(struct file *file, char *buf, size_t len, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/safesetid/securityfs.c (ffffffff814b3330)
Location: security/safesetid/securityfs.c:209
Inline: False
```
**Symbols:**

```
ffffffff814b3330-ffffffff814b33a6: safesetid_file_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t safesetid_file_read(struct file *file, char *buf, size_t len, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/safesetid/securityfs.c (ffffffff81512b90)
Location: security/safesetid/securityfs.c:209
Inline: False
```
**Symbols:**

```
ffffffff81512b90-ffffffff81512c06: safesetid_file_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/safesetid/securityfs.c (ffffffff8152fda0)
Location: security/safesetid/securityfs.c:263
Inline: True
Direct callers:
  - security/safesetid/securityfs.c:safesetid_gid_file_read
  - security/safesetid/securityfs.c:safesetid_uid_file_read
```
**Symbols:**

```
ffffffff8152fda0-ffffffff8152fe0f: safesetid_file_read.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/safesetid/securityfs.c (ffffffff81535fa0)
Location: security/safesetid/securityfs.c:263
Inline: True
Direct callers:
  - security/safesetid/securityfs.c:safesetid_gid_file_read
  - security/safesetid/securityfs.c:safesetid_uid_file_read
```
**Symbols:**

```
ffffffff81535fa0-ffffffff8153600f: safesetid_file_read.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/safesetid/securityfs.c (ffffffff815945c0)
Location: security/safesetid/securityfs.c:263
Inline: True
Direct callers:
  - security/safesetid/securityfs.c:safesetid_gid_file_read
  - security/safesetid/securityfs.c:safesetid_uid_file_read
```
**Symbols:**

```
ffffffff815945c0-ffffffff8159462f: safesetid_file_read.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/safesetid/securityfs.c (ffffffff81636660)
Location: security/safesetid/securityfs.c:263
Inline: True
Direct callers:
  - security/safesetid/securityfs.c:safesetid_gid_file_read
  - security/safesetid/securityfs.c:safesetid_uid_file_read
```
**Symbols:**

```
ffffffff81636660-ffffffff816366df: safesetid_file_read.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/safesetid/securityfs.c (ffffffff816ed730)
Location: security/safesetid/securityfs.c:263
Inline: True
Direct callers:
  - security/safesetid/securityfs.c:safesetid_gid_file_read
  - security/safesetid/securityfs.c:safesetid_uid_file_read
```
**Symbols:**

```
ffffffff816ed730-ffffffff816ed7af: safesetid_file_read.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/safesetid/securityfs.c (ffffffff81727b40)
Location: security/safesetid/securityfs.c:263
Inline: True
Direct callers:
  - security/safesetid/securityfs.c:safesetid_gid_file_read
  - security/safesetid/securityfs.c:safesetid_uid_file_read
```
**Symbols:**

```
ffffffff81727b40-ffffffff81727bbf: safesetid_file_read.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/safesetid/securityfs.c (ffffffff81768e70)
Location: security/safesetid/securityfs.c:263
Inline: True
Direct callers:
  - security/safesetid/securityfs.c:safesetid_gid_file_read
  - security/safesetid/securityfs.c:safesetid_uid_file_read
```
**Symbols:**

```
ffffffff81768e70-ffffffff81768eef: safesetid_file_read.isra.0 (STB_LOCAL)
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
ssize_t safesetid_file_read(struct file *file, char *buf, size_t len, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/safesetid/securityfs.c (ffff8000105ab000)
Location: security/safesetid/securityfs.c:209
Inline: False
```
**Symbols:**

```
ffff8000105ab000-ffff8000105ab0b0: safesetid_file_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t safesetid_file_read(struct file *file, char *buf, size_t len, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/safesetid/securityfs.c (c075abac)
Location: security/safesetid/securityfs.c:209
Inline: False
```
**Symbols:**

```
c075abac-c075ac38: safesetid_file_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t safesetid_file_read(struct file *file, char *buf, size_t len, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/safesetid/securityfs.c (c000000000728c40)
Location: security/safesetid/securityfs.c:209
Inline: False
```
**Symbols:**

```
c000000000728c40-c000000000728d44: safesetid_file_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ssize_t safesetid_file_read(struct file *file, char *buf, size_t len, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/safesetid/securityfs.c (ffffffe0003f3c30)
Location: security/safesetid/securityfs.c:209
Inline: False
```
**Symbols:**

```
ffffffe0003f3c30-ffffffe0003f3cb4: safesetid_file_read (STB_LOCAL)
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
ssize_t safesetid_file_read(struct file *file, char *buf, size_t len, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/safesetid/securityfs.c (ffffffff814ab910)
Location: security/safesetid/securityfs.c:209
Inline: False
```
**Symbols:**

```
ffffffff814ab910-ffffffff814ab986: safesetid_file_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ssize_t safesetid_file_read(struct file *file, char *buf, size_t len, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/safesetid/securityfs.c (ffffffff8149c330)
Location: security/safesetid/securityfs.c:209
Inline: False
```
**Symbols:**

```
ffffffff8149c330-ffffffff8149c3a6: safesetid_file_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ssize_t safesetid_file_read(struct file *file, char *buf, size_t len, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/safesetid/securityfs.c (ffffffff814a79b0)
Location: security/safesetid/securityfs.c:209
Inline: False
```
**Symbols:**

```
ffffffff814a79b0-ffffffff814a7a26: safesetid_file_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ssize_t safesetid_file_read(struct file *file, char *buf, size_t len, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/safesetid/securityfs.c (ffffffff814c0340)
Location: security/safesetid/securityfs.c:209
Inline: False
```
**Symbols:**

```
ffffffff814c0340-ffffffff814c03b6: safesetid_file_read (STB_LOCAL)
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
