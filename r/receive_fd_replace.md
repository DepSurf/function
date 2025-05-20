# Function: <code>receive_fd_replace</code>

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
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff811a3587)
Location: include/linux/file.h:108
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int receive_fd_replace(int new_fd, struct file *file, unsigned int o_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff8134bd10)
Location: fs/file.c:1124
Inline: False
```
**Symbols:**

```
ffffffff8134bd10-ffffffff8134bd5b: receive_fd_replace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int receive_fd_replace(int new_fd, struct file *file, unsigned int o_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81399b50)
Location: fs/file.c:1184
Inline: False
```
**Symbols:**

```
ffffffff81399b50-ffffffff81399b9b: receive_fd_replace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int receive_fd_replace(int new_fd, struct file *file, unsigned int o_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff8141c5e0)
Location: fs/file.c:1186
Inline: False
```
**Symbols:**

```
ffffffff8141c5e0-ffffffff8141c642: receive_fd_replace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int receive_fd_replace(int new_fd, struct file *file, unsigned int o_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff814a86e0)
Location: fs/file.c:1196
Inline: False
```
**Symbols:**

```
ffffffff814a86e0-ffffffff814a8742: receive_fd_replace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int receive_fd_replace(int new_fd, struct file *file, unsigned int o_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff814dd6d0)
Location: fs/file.c:1211
Inline: False
```
**Symbols:**

```
ffffffff814dd6d0-ffffffff814dd732: receive_fd_replace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int receive_fd_replace(int new_fd, struct file *file, unsigned int o_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81510120)
Location: fs/file.c:1341
Inline: False
```
**Symbols:**

```
ffffffff81510120-ffffffff81510182: receive_fd_replace (STB_GLOBAL)
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
