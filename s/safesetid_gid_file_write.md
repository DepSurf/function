# Function: <code>safesetid_gid_file_write</code>

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
ssize_t safesetid_gid_file_write(struct file *file, const char *buf, size_t len, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/safesetid/securityfs.c (ffffffff8152fcc0)
Location: security/safesetid/securityfs.c:249
Inline: False
```
**Symbols:**

```
ffffffff8152fcc0-ffffffff8152fd25: safesetid_gid_file_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t safesetid_gid_file_write(struct file *file, const char *buf, size_t len, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/safesetid/securityfs.c (ffffffff81535ec0)
Location: security/safesetid/securityfs.c:249
Inline: False
```
**Symbols:**

```
ffffffff81535ec0-ffffffff81535f25: safesetid_gid_file_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
ssize_t safesetid_gid_file_write(struct file *file, const char *buf, size_t len, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/safesetid/securityfs.c (ffffffff815944e0)
Location: security/safesetid/securityfs.c:249
Inline: False
```
**Symbols:**

```
ffffffff815944e0-ffffffff81594545: safesetid_gid_file_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ssize_t safesetid_gid_file_write(struct file *file, const char *buf, size_t len, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/safesetid/securityfs.c (ffffffff81636570)
Location: security/safesetid/securityfs.c:249
Inline: False
```
**Symbols:**

```
ffffffff81636570-ffffffff816365e2: safesetid_gid_file_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t safesetid_gid_file_write(struct file *file, const char *buf, size_t len, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/safesetid/securityfs.c (ffffffff816ed620)
Location: security/safesetid/securityfs.c:249
Inline: False
```
**Symbols:**

```
ffffffff816ed620-ffffffff816ed692: safesetid_gid_file_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t safesetid_gid_file_write(struct file *file, const char *buf, size_t len, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/safesetid/securityfs.c (ffffffff81727a30)
Location: security/safesetid/securityfs.c:249
Inline: False
```
**Symbols:**

```
ffffffff81727a30-ffffffff81727aa2: safesetid_gid_file_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t safesetid_gid_file_write(struct file *file, const char *buf, size_t len, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/safesetid/securityfs.c (ffffffff81768d60)
Location: security/safesetid/securityfs.c:249
Inline: False
```
**Symbols:**

```
ffffffff81768d60-ffffffff81768dd2: safesetid_gid_file_write (STB_LOCAL)
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
