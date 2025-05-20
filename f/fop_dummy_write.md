# Function: <code>fop_dummy_write</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t fop_dummy_write(const struct file * filp, const const char * buf, const size_t size, const loff_t * ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/landlock/syscalls.c (0)
Location: security/landlock/syscalls.c:111
Inline: False
```
**Symbols:**

```
ffffffff81537240-ffffffff81537252: fop_dummy_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
ssize_t fop_dummy_write(const struct file * filp, const const char * buf, const size_t size, const loff_t * ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/landlock/syscalls.c (0)
Location: security/landlock/syscalls.c:111
Inline: False
```
**Symbols:**

```
ffffffff815959c0-ffffffff815959d2: fop_dummy_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ssize_t fop_dummy_write(const struct file * filp, const const char * buf, const size_t size, const loff_t * ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/landlock/syscalls.c (0)
Location: security/landlock/syscalls.c:112
Inline: False
```
**Symbols:**

```
ffffffff81637c90-ffffffff81637ca6: fop_dummy_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t fop_dummy_write(const struct file * filp, const const char * buf, const size_t size, const loff_t * ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/landlock/syscalls.c (0)
Location: security/landlock/syscalls.c:112
Inline: False
```
**Symbols:**

```
ffffffff816ef080-ffffffff816ef096: fop_dummy_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t fop_dummy_write(const struct file * filp, const const char * buf, const size_t size, const loff_t * ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/landlock/syscalls.c (0)
Location: security/landlock/syscalls.c:112
Inline: False
```
**Symbols:**

```
ffffffff81729520-ffffffff81729536: fop_dummy_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t fop_dummy_write(const struct file * filp, const const char * buf, const size_t size, const loff_t * ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/landlock/syscalls.c (0)
Location: security/landlock/syscalls.c:120
Inline: False
```
**Symbols:**

```
ffffffff8176ab70-ffffffff8176ab86: fop_dummy_write (STB_LOCAL)
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
