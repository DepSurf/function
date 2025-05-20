# Function: <code>__close_range</code>

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
int __close_range(unsigned int fd, unsigned int max_fd, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81345190)
Location: fs/file.c:670
Inline: False
Direct callers:
  - fs/open.c:__ia32_sys_close_range
  - fs/open.c:__x64_sys_close_range
```
**Symbols:**

```
ffffffff81345190-ffffffff81345333: __close_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __close_range(unsigned int fd, unsigned int max_fd, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff8134b510)
Location: fs/file.c:683
Inline: False
Direct callers:
  - fs/open.c:__ia32_sys_close_range
  - fs/open.c:__x64_sys_close_range
```
**Symbols:**

```
ffffffff8134b510-ffffffff8134b6c1: __close_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __close_range(unsigned int fd, unsigned int max_fd, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81399370)
Location: fs/file.c:702
Inline: False
Direct callers:
  - fs/open.c:__ia32_sys_close_range
  - fs/open.c:__x64_sys_close_range
```
**Symbols:**

```
ffffffff81399370-ffffffff8139950b: __close_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __close_range(unsigned int fd, unsigned int max_fd, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff8141bce0)
Location: fs/file.c:729
Inline: False
Direct callers:
  - fs/open.c:__ia32_sys_close_range
  - fs/open.c:__x64_sys_close_range
```
**Symbols:**

```
ffffffff8141bce0-ffffffff8141bed4: __close_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __close_range(unsigned int fd, unsigned int max_fd, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff814a7e60)
Location: fs/file.c:729
Inline: False
Direct callers:
  - fs/open.c:__ia32_sys_close_range
  - fs/open.c:__x64_sys_close_range
```
**Symbols:**

```
ffffffff814a7e60-ffffffff814a8054: __close_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __close_range(unsigned int fd, unsigned int max_fd, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff814dce40)
Location: fs/file.c:730
Inline: False
Direct callers:
  - fs/open.c:__ia32_sys_close_range
  - fs/open.c:__x64_sys_close_range
```
**Symbols:**

```
ffffffff814dce40-ffffffff814dd034: __close_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __close_range(unsigned int fd, unsigned int max_fd, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff8150f790)
Location: fs/file.c:739
Inline: False
Direct callers:
  - fs/open.c:__ia32_sys_close_range
  - fs/open.c:__x64_sys_close_range
```
**Symbols:**

```
ffffffff8150f790-ffffffff8150f9b9: __close_range (STB_GLOBAL)
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
