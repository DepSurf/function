# Function: <code>__do_sys_statx</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long int __do_sys_statx(int dfd, const char *filename, unsigned int flags, unsigned int mask, struct statx *buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff8129fe20)
Location: fs/stat.c:566
Inline: False
Direct callers:
  - fs/stat.c:__ia32_sys_statx
  - fs/stat.c:__x64_sys_statx
```
**Symbols:**

```
ffffffff8129fe20-ffffffff8129fe9d: __do_sys_statx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int __do_sys_statx(int dfd, const char *filename, unsigned int flags, unsigned int mask, struct statx *buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812b4e00)
Location: fs/stat.c:569
Inline: False
Direct callers:
  - fs/stat.c:__ia32_sys_statx
  - fs/stat.c:__x64_sys_statx
```
**Symbols:**

```
ffffffff812b4e00-ffffffff812b4e7d: __do_sys_statx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int __do_sys_statx(int dfd, const char *filename, unsigned int flags, unsigned int mask, struct statx *buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812d1ba0)
Location: fs/stat.c:571
Inline: False
Direct callers:
  - fs/stat.c:__ia32_sys_statx
  - fs/stat.c:__x64_sys_statx
```
**Symbols:**

```
ffffffff812d1ba0-ffffffff812d1c1f: __do_sys_statx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int __do_sys_statx(int dfd, const char *filename, unsigned int flags, unsigned int mask, struct statx *buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812e3730)
Location: fs/stat.c:571
Inline: False
Direct callers:
  - fs/stat.c:__ia32_sys_statx
  - fs/stat.c:__x64_sys_statx
```
**Symbols:**

```
ffffffff812e3730-ffffffff812e37af: __do_sys_statx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff8131b2f5)
Location: fs/stat.c:610
Inline: True
Inline callers:
  - fs/stat.c:__ia32_sys_statx
  - fs/stat.c:__x64_sys_statx
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff81326955)
Location: fs/stat.c:598
Inline: True
Inline callers:
  - fs/stat.c:__ia32_sys_statx
  - fs/stat.c:__x64_sys_statx
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff8132ca65)
Location: fs/stat.c:616
Inline: True
Inline callers:
  - fs/stat.c:__ia32_sys_statx
  - fs/stat.c:__x64_sys_statx
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff8137a1d5)
Location: fs/stat.c:634
Inline: True
Inline callers:
  - fs/stat.c:__ia32_sys_statx
  - fs/stat.c:__x64_sys_statx
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff813f98bc)
Location: fs/stat.c:647
Inline: True
Inline callers:
  - fs/stat.c:__ia32_sys_statx
  - fs/stat.c:__x64_sys_statx
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff814830fc)
Location: fs/stat.c:664
Inline: True
Inline callers:
  - fs/stat.c:__ia32_sys_statx
  - fs/stat.c:__x64_sys_statx
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff814b7d1c)
Location: fs/stat.c:677
Inline: True
Inline callers:
  - fs/stat.c:__ia32_sys_statx
  - fs/stat.c:__x64_sys_statx
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff814ea21c)
Location: fs/stat.c:699
Inline: True
Inline callers:
  - fs/stat.c:__ia32_sys_statx
  - fs/stat.c:__x64_sys_statx
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
long int __do_sys_statx(int dfd, const char *filename, unsigned int flags, unsigned int mask, struct statx *buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffff80001038ba18)
Location: fs/stat.c:571
Inline: False
Direct callers:
  - fs/stat.c:__arm64_sys_statx
```
**Symbols:**

```
ffff80001038ba18-ffff80001038ba98: __do_sys_statx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int __do_sys_statx(int dfd, const char *filename, unsigned int flags, unsigned int mask, struct statx *buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (c0573384)
Location: fs/stat.c:571
Inline: False
Direct callers:
  - fs/stat.c:__se_sys_statx
```
**Symbols:**

```
c0573384-c057340c: __do_sys_statx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int __do_sys_statx(int dfd, const char *filename, unsigned int flags, unsigned int mask, struct statx *buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (c0000000004825d0)
Location: fs/stat.c:571
Inline: False
Direct callers:
  - fs/stat.c:__se_sys_statx
```
**Symbols:**

```
c0000000004825d0-c00000000048268c: __do_sys_statx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int __do_sys_statx(int dfd, const char *filename, unsigned int flags, unsigned int mask, struct statx *buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffe00025ca54)
Location: fs/stat.c:571
Inline: False
Direct callers:
  - fs/stat.c:__se_sys_statx
```
**Symbols:**

```
ffffffe00025ca54-ffffffe00025ca9e: __do_sys_statx (STB_LOCAL)
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
long int __do_sys_statx(int dfd, const char *filename, unsigned int flags, unsigned int mask, struct statx *buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812dbd10)
Location: fs/stat.c:571
Inline: False
Direct callers:
  - fs/stat.c:__ia32_sys_statx
  - fs/stat.c:__x64_sys_statx
```
**Symbols:**

```
ffffffff812dbd10-ffffffff812dbd8f: __do_sys_statx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int __do_sys_statx(int dfd, const char *filename, unsigned int flags, unsigned int mask, struct statx *buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812cc990)
Location: fs/stat.c:571
Inline: False
Direct callers:
  - fs/stat.c:__ia32_sys_statx
  - fs/stat.c:__x64_sys_statx
```
**Symbols:**

```
ffffffff812cc990-ffffffff812cca0f: __do_sys_statx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int __do_sys_statx(int dfd, const char *filename, unsigned int flags, unsigned int mask, struct statx *buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812d9b20)
Location: fs/stat.c:571
Inline: False
Direct callers:
  - fs/stat.c:__ia32_sys_statx
  - fs/stat.c:__x64_sys_statx
```
**Symbols:**

```
ffffffff812d9b20-ffffffff812d9b9f: __do_sys_statx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int __do_sys_statx(int dfd, const char *filename, unsigned int flags, unsigned int mask, struct statx *buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812eaa30)
Location: fs/stat.c:571
Inline: False
Direct callers:
  - fs/stat.c:__ia32_sys_statx
  - fs/stat.c:__x64_sys_statx
```
**Symbols:**

```
ffffffff812eaa30-ffffffff812eaaaf: __do_sys_statx (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
