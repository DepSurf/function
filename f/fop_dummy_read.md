# Function: <code>fop_dummy_read</code>

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
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
ssize_t fop_dummy_read(const struct file * filp, const char * buf, const size_t size, const loff_t * ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/landlock/syscalls.c (ffffffff81536ff0)
Location: security/landlock/syscalls.c:104
Inline: True
```
**Symbols:**

```
ffffffff81536ff0-ffffffff81537002: fop_dummy_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
ssize_t fop_dummy_read(const struct file * filp, const char * buf, const size_t size, const loff_t * ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/landlock/syscalls.c (ffffffff81595760)
Location: security/landlock/syscalls.c:104
Inline: True
```
**Symbols:**

```
ffffffff81595760-ffffffff81595772: fop_dummy_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
ssize_t fop_dummy_read(const struct file * filp, const char * buf, const size_t size, const loff_t * ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/landlock/syscalls.c (ffffffff816379f0)
Location: security/landlock/syscalls.c:105
Inline: True
```
**Symbols:**

```
ffffffff816379f0-ffffffff81637a06: fop_dummy_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
ssize_t fop_dummy_read(const struct file * filp, const char * buf, const size_t size, const loff_t * ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/landlock/syscalls.c (ffffffff816eeda0)
Location: security/landlock/syscalls.c:105
Inline: True
```
**Symbols:**

```
ffffffff816eeda0-ffffffff816eedb6: fop_dummy_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
ssize_t fop_dummy_read(const struct file * filp, const char * buf, const size_t size, const loff_t * ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/landlock/syscalls.c (ffffffff81729230)
Location: security/landlock/syscalls.c:105
Inline: True
```
**Symbols:**

```
ffffffff81729230-ffffffff81729246: fop_dummy_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
ssize_t fop_dummy_read(const struct file * filp, const char * buf, const size_t size, const loff_t * ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/landlock/syscalls.c (ffffffff8176a590)
Location: security/landlock/syscalls.c:113
Inline: True
```
**Symbols:**

```
ffffffff8176a590-ffffffff8176a5a6: fop_dummy_read (STB_LOCAL)
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
