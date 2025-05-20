# Function: <code>rproc_coredump_write</code>

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
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
ssize_t rproc_coredump_write(struct file *filp, const char *user_buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_debugfs.c (0)
Location: drivers/remoteproc/remoteproc_debugfs.c:71
Inline: False
```
**Symbols:**

```
ffffffff819cb8e0-ffffffff819cba29: rproc_coredump_write (STB_LOCAL)
ffffffff81c2ed35-ffffffff81c2ed6d: rproc_coredump_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
ssize_t rproc_coredump_write(struct file *filp, const char *user_buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_debugfs.c (0)
Location: drivers/remoteproc/remoteproc_debugfs.c:71
Inline: False
```
**Symbols:**

```
ffffffff819b0a90-ffffffff819b0bb6: rproc_coredump_write (STB_LOCAL)
ffffffff81c2100b-ffffffff81c21043: rproc_coredump_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
ssize_t rproc_coredump_write(struct file *filp, const char *user_buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_debugfs.c (0)
Location: drivers/remoteproc/remoteproc_debugfs.c:71
Inline: False
```
**Symbols:**

```
ffffffff81a5f120-ffffffff81a5f28a: rproc_coredump_write (STB_LOCAL)
ffffffff81d329d1-ffffffff81d32a09: rproc_coredump_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
ssize_t rproc_coredump_write(struct file *filp, const char *user_buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_debugfs.c (0)
Location: drivers/remoteproc/remoteproc_debugfs.c:71
Inline: False
```
**Symbols:**

```
ffffffff81bcfb50-ffffffff81bcfc9f: rproc_coredump_write (STB_LOCAL)
ffffffff81efeee3-ffffffff81efef1b: rproc_coredump_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t rproc_coredump_write(struct file *filp, const char *user_buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_debugfs.c (ffffffff81d7ac20)
Location: drivers/remoteproc/remoteproc_debugfs.c:71
Inline: False
```
**Symbols:**

```
ffffffff81d7ac20-ffffffff81d7adb0: rproc_coredump_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t rproc_coredump_write(struct file *filp, const char *user_buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_debugfs.c (ffffffff81de85e0)
Location: drivers/remoteproc/remoteproc_debugfs.c:71
Inline: False
```
**Symbols:**

```
ffffffff81de85e0-ffffffff81de87b9: rproc_coredump_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t rproc_coredump_write(struct file *filp, const char *user_buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_debugfs.c (ffffffff81e9e820)
Location: drivers/remoteproc/remoteproc_debugfs.c:71
Inline: False
```
**Symbols:**

```
ffffffff81e9e820-ffffffff81e9e9f9: rproc_coredump_write (STB_LOCAL)
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
