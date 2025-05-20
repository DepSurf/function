# Function: <code>rproc_coredump_read</code>

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
<summary>In <code>5.11</code>: Collision ⚠️</summary>

```c
ssize_t rproc_coredump_read(char *buffer, loff_t offset, size_t count, void *data, size_t header_sz);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_coredump.c (ffffffff819caae0)
Location: drivers/remoteproc/remoteproc_coredump.c:172
Inline: False
```
```
In drivers/remoteproc/remoteproc_debugfs.c (ffffffff819cb6f0)
Location: drivers/remoteproc/remoteproc_debugfs.c:42
Inline: False
```
**Symbols:**

```
ffffffff819caae0-ffffffff819cabd0: rproc_coredump_read (STB_LOCAL)
ffffffff819cb6f0-ffffffff819cb778: rproc_coredump_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision ⚠️</summary>

```c
ssize_t rproc_coredump_read(char *buffer, loff_t offset, size_t count, void *data, size_t header_sz);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_coredump.c (ffffffff819afca0)
Location: drivers/remoteproc/remoteproc_coredump.c:176
Inline: False
```
```
In drivers/remoteproc/remoteproc_debugfs.c (ffffffff819b08a0)
Location: drivers/remoteproc/remoteproc_debugfs.c:42
Inline: False
```
**Symbols:**

```
ffffffff819afca0-ffffffff819afd8f: rproc_coredump_read (STB_LOCAL)
ffffffff819b08a0-ffffffff819b0928: rproc_coredump_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision ⚠️</summary>

```c
ssize_t rproc_coredump_read(char *buffer, loff_t offset, size_t count, void *data, size_t header_sz);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_coredump.c (ffffffff81a5e310)
Location: drivers/remoteproc/remoteproc_coredump.c:176
Inline: False
```
```
In drivers/remoteproc/remoteproc_debugfs.c (ffffffff81a5ef10)
Location: drivers/remoteproc/remoteproc_debugfs.c:42
Inline: False
```
**Symbols:**

```
ffffffff81a5e310-ffffffff81a5e3ff: rproc_coredump_read (STB_LOCAL)
ffffffff81a5ef10-ffffffff81a5efb1: rproc_coredump_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision ⚠️</summary>

```c
ssize_t rproc_coredump_read(char *buffer, loff_t offset, size_t count, void *data, size_t header_sz);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_coredump.c (ffffffff81bce570)
Location: drivers/remoteproc/remoteproc_coredump.c:176
Inline: False
```
```
In drivers/remoteproc/remoteproc_debugfs.c (ffffffff81bcf1e0)
Location: drivers/remoteproc/remoteproc_debugfs.c:42
Inline: False
```
**Symbols:**

```
ffffffff81bce570-ffffffff81bce684: rproc_coredump_read (STB_LOCAL)
ffffffff81bcf1e0-ffffffff81bcf2a8: rproc_coredump_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision ⚠️</summary>

```c
ssize_t rproc_coredump_read(char *buffer, loff_t offset, size_t count, void *data, size_t header_sz);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_coredump.c (ffffffff81d794d0)
Location: drivers/remoteproc/remoteproc_coredump.c:176
Inline: False
```
```
In drivers/remoteproc/remoteproc_debugfs.c (ffffffff81d7a200)
Location: drivers/remoteproc/remoteproc_debugfs.c:42
Inline: False
```
**Symbols:**

```
ffffffff81d794d0-ffffffff81d795dd: rproc_coredump_read (STB_LOCAL)
ffffffff81d7a200-ffffffff81d7a2c8: rproc_coredump_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision ⚠️</summary>

```c
ssize_t rproc_coredump_read(char *buffer, loff_t offset, size_t count, void *data, size_t header_sz);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_coredump.c (ffffffff81de7420)
Location: drivers/remoteproc/remoteproc_coredump.c:176
Inline: False
```
```
In drivers/remoteproc/remoteproc_debugfs.c (ffffffff81de8310)
Location: drivers/remoteproc/remoteproc_debugfs.c:42
Inline: False
```
**Symbols:**

```
ffffffff81de7420-ffffffff81de752d: rproc_coredump_read (STB_LOCAL)
ffffffff81de8310-ffffffff81de83d8: rproc_coredump_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision ⚠️</summary>

```c
ssize_t rproc_coredump_read(char *buffer, loff_t offset, size_t count, void *data, size_t header_sz);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_coredump.c (ffffffff81e9d680)
Location: drivers/remoteproc/remoteproc_coredump.c:177
Inline: False
```
```
In drivers/remoteproc/remoteproc_debugfs.c (ffffffff81e9e550)
Location: drivers/remoteproc/remoteproc_debugfs.c:42
Inline: False
```
**Symbols:**

```
ffffffff81e9d680-ffffffff81e9d78d: rproc_coredump_read (STB_LOCAL)
ffffffff81e9e550-ffffffff81e9e618: rproc_coredump_read (STB_LOCAL)
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
