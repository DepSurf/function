# Function: <code>safesetid_gid_file_read</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t safesetid_gid_file_read(struct file *file, char *buf, size_t len, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/safesetid/securityfs.c (ffffffff8152fe40)
Location: security/safesetid/securityfs.c:289
Inline: False
```
**Symbols:**

```
ffffffff8152fe40-ffffffff8152fe67: safesetid_gid_file_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t safesetid_gid_file_read(struct file *file, char *buf, size_t len, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/safesetid/securityfs.c (ffffffff81536040)
Location: security/safesetid/securityfs.c:289
Inline: False
```
**Symbols:**

```
ffffffff81536040-ffffffff81536067: safesetid_gid_file_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
ssize_t safesetid_gid_file_read(struct file *file, char *buf, size_t len, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/safesetid/securityfs.c (ffffffff81594660)
Location: security/safesetid/securityfs.c:289
Inline: False
```
**Symbols:**

```
ffffffff81594660-ffffffff81594687: safesetid_gid_file_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ssize_t safesetid_gid_file_read(struct file *file, char *buf, size_t len, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/safesetid/securityfs.c (ffffffff81636720)
Location: security/safesetid/securityfs.c:289
Inline: False
```
**Symbols:**

```
ffffffff81636720-ffffffff81636756: safesetid_gid_file_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t safesetid_gid_file_read(struct file *file, char *buf, size_t len, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/safesetid/securityfs.c (ffffffff816ed810)
Location: security/safesetid/securityfs.c:289
Inline: False
```
**Symbols:**

```
ffffffff816ed810-ffffffff816ed846: safesetid_gid_file_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t safesetid_gid_file_read(struct file *file, char *buf, size_t len, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/safesetid/securityfs.c (ffffffff81727c20)
Location: security/safesetid/securityfs.c:289
Inline: False
```
**Symbols:**

```
ffffffff81727c20-ffffffff81727c56: safesetid_gid_file_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t safesetid_gid_file_read(struct file *file, char *buf, size_t len, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/safesetid/securityfs.c (ffffffff81768f50)
Location: security/safesetid/securityfs.c:289
Inline: False
```
**Symbols:**

```
ffffffff81768f50-ffffffff81768f86: safesetid_gid_file_read (STB_LOCAL)
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
