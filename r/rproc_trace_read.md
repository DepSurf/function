# Function: <code>rproc_trace_read</code>

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
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
ssize_t rproc_trace_read(struct file *filp, char *userbuf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_debugfs.c (0)
Location: drivers/remoteproc/remoteproc_debugfs.c:39
Inline: False
```
**Symbols:**

```
ffffffff818f6070-ffffffff818f6136: rproc_trace_read (STB_LOCAL)
ffffffff818f692d-ffffffff818f6939: rproc_trace_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
ssize_t rproc_trace_read(struct file *filp, char *userbuf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_debugfs.c (0)
Location: drivers/remoteproc/remoteproc_debugfs.c:39
Inline: False
```
**Symbols:**

```
ffffffff819cc190-ffffffff819cc257: rproc_trace_read (STB_LOCAL)
ffffffff819cca5f-ffffffff819cca6b: rproc_trace_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
ssize_t rproc_trace_read(struct file *filp, char *userbuf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_debugfs.c (0)
Location: drivers/remoteproc/remoteproc_debugfs.c:126
Inline: False
```
**Symbols:**

```
ffffffff819cb810-ffffffff819cb8d7: rproc_trace_read (STB_LOCAL)
ffffffff81c2ed29-ffffffff81c2ed35: rproc_trace_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
ssize_t rproc_trace_read(struct file *filp, char *userbuf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_debugfs.c (0)
Location: drivers/remoteproc/remoteproc_debugfs.c:126
Inline: False
```
**Symbols:**

```
ffffffff819b09c0-ffffffff819b0a89: rproc_trace_read (STB_LOCAL)
ffffffff81c20fff-ffffffff81c2100b: rproc_trace_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
ssize_t rproc_trace_read(struct file *filp, char *userbuf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_debugfs.c (0)
Location: drivers/remoteproc/remoteproc_debugfs.c:126
Inline: False
```
**Symbols:**

```
ffffffff81a5f050-ffffffff81a5f119: rproc_trace_read (STB_LOCAL)
ffffffff81d329c5-ffffffff81d329d1: rproc_trace_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
ssize_t rproc_trace_read(struct file *filp, char *userbuf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_debugfs.c (0)
Location: drivers/remoteproc/remoteproc_debugfs.c:126
Inline: False
```
**Symbols:**

```
ffffffff81bcf370-ffffffff81bcf477: rproc_trace_read (STB_LOCAL)
ffffffff81efeeab-ffffffff81efeeb7: rproc_trace_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t rproc_trace_read(struct file *filp, char *userbuf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_debugfs.c (ffffffff81d7a3b0)
Location: drivers/remoteproc/remoteproc_debugfs.c:126
Inline: False
```
**Symbols:**

```
ffffffff81d7a3b0-ffffffff81d7a4be: rproc_trace_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t rproc_trace_read(struct file *filp, char *userbuf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_debugfs.c (ffffffff81de84c0)
Location: drivers/remoteproc/remoteproc_debugfs.c:126
Inline: False
```
**Symbols:**

```
ffffffff81de84c0-ffffffff81de85ce: rproc_trace_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t rproc_trace_read(struct file *filp, char *userbuf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_debugfs.c (ffffffff81e9e700)
Location: drivers/remoteproc/remoteproc_debugfs.c:126
Inline: False
```
**Symbols:**

```
ffffffff81e9e700-ffffffff81e9e80e: rproc_trace_read (STB_LOCAL)
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
ssize_t rproc_trace_read(struct file *filp, char *userbuf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_debugfs.c (ffff800010b81fa8)
Location: drivers/remoteproc/remoteproc_debugfs.c:39
Inline: False
```
**Symbols:**

```
ffff800010b81fa8-ffff800010b82090: rproc_trace_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t rproc_trace_read(struct file *filp, char *userbuf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_debugfs.c (c0c654c8)
Location: drivers/remoteproc/remoteproc_debugfs.c:39
Inline: False
```
**Symbols:**

```
c0c654c8-c0c655b0: rproc_trace_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t rproc_trace_read(struct file *filp, char *userbuf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_debugfs.c (c000000000c5ede0)
Location: drivers/remoteproc/remoteproc_debugfs.c:39
Inline: False
```
**Symbols:**

```
c000000000c5ede0-c000000000c5ef10: rproc_trace_read (STB_LOCAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
ssize_t rproc_trace_read(struct file *filp, char *userbuf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_debugfs.c (0)
Location: drivers/remoteproc/remoteproc_debugfs.c:39
Inline: False
```
**Symbols:**

```
ffffffff818973a0-ffffffff81897466: rproc_trace_read (STB_LOCAL)
ffffffff81897c5d-ffffffff81897c69: rproc_trace_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
ssize_t rproc_trace_read(struct file *filp, char *userbuf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_debugfs.c (0)
Location: drivers/remoteproc/remoteproc_debugfs.c:39
Inline: False
```
**Symbols:**

```
ffffffff81907b00-ffffffff81907bc6: rproc_trace_read (STB_LOCAL)
ffffffff819083bd-ffffffff819083c9: rproc_trace_read.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
