# Function: <code>do_fsync</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int do_fsync(unsigned int fd, int datasync);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff81240660)
Location: fs/sync.c:213
Inline: False
Direct callers:
  - fs/sync.c:SyS_fsync
  - fs/sync.c:SyS_fdatasync
```
**Symbols:**

```
ffffffff81240660-ffffffff812406c2: do_fsync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int do_fsync(unsigned int fd, int datasync);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff812689a0)
Location: fs/sync.c:213
Inline: False
Direct callers:
  - fs/sync.c:SyS_fdatasync
  - fs/sync.c:SyS_fsync
```
**Symbols:**

```
ffffffff812689a0-ffffffff81268a02: do_fsync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int do_fsync(unsigned int fd, int datasync);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff8127b9c0)
Location: fs/sync.c:214
Inline: False
Direct callers:
  - fs/sync.c:SyS_fdatasync
  - fs/sync.c:SyS_fsync
```
**Symbols:**

```
ffffffff8127b9c0-ffffffff8127ba22: do_fsync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int do_fsync(unsigned int fd, int datasync);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff81288d50)
Location: fs/sync.c:214
Inline: False
Direct callers:
  - fs/sync.c:SyS_fdatasync
  - fs/sync.c:SyS_fsync
```
**Symbols:**

```
ffffffff81288d50-ffffffff81288db2: do_fsync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int do_fsync(unsigned int fd, int datasync);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff812ab890)
Location: fs/sync.c:215
Inline: False
Direct callers:
  - fs/sync.c:SyS_fdatasync
  - fs/sync.c:SyS_fsync
```
**Symbols:**

```
ffffffff812ab890-ffffffff812ab8f2: do_fsync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int do_fsync(unsigned int fd, int datasync);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff812d24d0)
Location: fs/sync.c:216
Inline: False
Direct callers:
  - fs/sync.c:__ia32_sys_fdatasync
  - fs/sync.c:__x64_sys_fdatasync
  - fs/sync.c:__ia32_sys_fsync
  - fs/sync.c:__x64_sys_fsync
```
**Symbols:**

```
ffffffff812d24d0-ffffffff812d253d: do_fsync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int do_fsync(unsigned int fd, int datasync);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff812e78b0)
Location: fs/sync.c:216
Inline: False
Direct callers:
  - fs/sync.c:__ia32_sys_fdatasync
  - fs/sync.c:__x64_sys_fdatasync
  - fs/sync.c:__ia32_sys_fsync
  - fs/sync.c:__x64_sys_fsync
```
**Symbols:**

```
ffffffff812e78b0-ffffffff812e791d: do_fsync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int do_fsync(unsigned int fd, int datasync);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff81306160)
Location: fs/sync.c:216
Inline: False
Direct callers:
  - fs/sync.c:__ia32_sys_fdatasync
  - fs/sync.c:__x64_sys_fdatasync
  - fs/sync.c:__ia32_sys_fsync
  - fs/sync.c:__x64_sys_fsync
```
**Symbols:**

```
ffffffff81306160-ffffffff813061cd: do_fsync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int do_fsync(unsigned int fd, int datasync);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff813191e0)
Location: fs/sync.c:216
Inline: False
Direct callers:
  - fs/sync.c:__ia32_sys_fdatasync
  - fs/sync.c:__x64_sys_fdatasync
  - fs/sync.c:__ia32_sys_fsync
  - fs/sync.c:__x64_sys_fsync
```
**Symbols:**

```
ffffffff813191e0-ffffffff8131924d: do_fsync (STB_LOCAL)
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
In fs/sync.c (ffffffff81352fb5)
Location: fs/sync.c:219
Inline: True
Inline callers:
  - fs/sync.c:__ia32_sys_fdatasync
  - fs/sync.c:__x64_sys_fdatasync
  - fs/sync.c:__ia32_sys_fsync
  - fs/sync.c:__x64_sys_fsync
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
In fs/sync.c (ffffffff8135f895)
Location: fs/sync.c:219
Inline: True
Inline callers:
  - fs/sync.c:__ia32_sys_fdatasync
  - fs/sync.c:__x64_sys_fdatasync
  - fs/sync.c:__ia32_sys_fsync
  - fs/sync.c:__x64_sys_fsync
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
In fs/sync.c (ffffffff81366505)
Location: fs/sync.c:218
Inline: True
Inline callers:
  - fs/sync.c:__ia32_sys_fdatasync
  - fs/sync.c:__x64_sys_fdatasync
  - fs/sync.c:__ia32_sys_fsync
  - fs/sync.c:__x64_sys_fsync
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
In fs/sync.c (ffffffff813b4c75)
Location: fs/sync.c:219
Inline: True
Inline callers:
  - fs/sync.c:__ia32_sys_fdatasync
  - fs/sync.c:__x64_sys_fdatasync
  - fs/sync.c:__ia32_sys_fsync
  - fs/sync.c:__x64_sys_fsync
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
In fs/sync.c (ffffffff8143a235)
Location: fs/sync.c:206
Inline: True
Inline callers:
  - fs/sync.c:__ia32_sys_fdatasync
  - fs/sync.c:__x64_sys_fdatasync
  - fs/sync.c:__ia32_sys_fsync
  - fs/sync.c:__x64_sys_fsync
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
In fs/sync.c (ffffffff814c8635)
Location: fs/sync.c:206
Inline: True
Inline callers:
  - fs/sync.c:__ia32_sys_fdatasync
  - fs/sync.c:__x64_sys_fdatasync
  - fs/sync.c:__ia32_sys_fsync
  - fs/sync.c:__x64_sys_fsync
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
In fs/sync.c (ffffffff814fe865)
Location: fs/sync.c:206
Inline: True
Inline callers:
  - fs/sync.c:__ia32_sys_fdatasync
  - fs/sync.c:__x64_sys_fdatasync
  - fs/sync.c:__ia32_sys_fsync
  - fs/sync.c:__x64_sys_fsync
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
In fs/sync.c (ffffffff81533465)
Location: fs/sync.c:206
Inline: True
Inline callers:
  - fs/sync.c:__ia32_sys_fdatasync
  - fs/sync.c:__x64_sys_fdatasync
  - fs/sync.c:__ia32_sys_fsync
  - fs/sync.c:__x64_sys_fsync
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
int do_fsync(unsigned int fd, int datasync);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffff8000103d01e0)
Location: fs/sync.c:216
Inline: False
Direct callers:
  - fs/sync.c:__arm64_sys_fdatasync
  - fs/sync.c:__arm64_sys_fsync
```
**Symbols:**

```
ffff8000103d01e0-ffff8000103d0268: do_fsync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int do_fsync(unsigned int fd, int datasync);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sync.c (c05ab564)
Location: fs/sync.c:216
Inline: False
Direct callers:
  - fs/sync.c:__se_sys_fdatasync
  - fs/sync.c:__se_sys_fsync
```
**Symbols:**

```
c05ab564-c05ab5e4: do_fsync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int do_fsync(unsigned int fd, int datasync);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sync.c (c0000000004d2810)
Location: fs/sync.c:216
Inline: False
Direct callers:
  - fs/sync.c:__se_sys_fdatasync
  - fs/sync.c:__se_sys_fsync
```
**Symbols:**

```
c0000000004d2810-c0000000004d28d8: do_fsync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int do_fsync(unsigned int fd, int datasync);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffe00028c4d2)
Location: fs/sync.c:216
Inline: False
Direct callers:
  - fs/sync.c:__se_sys_fdatasync
  - fs/sync.c:__se_sys_fsync
```
**Symbols:**

```
ffffffe00028c4d2-ffffffe00028c54a: do_fsync (STB_LOCAL)
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
int do_fsync(unsigned int fd, int datasync);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff813117c0)
Location: fs/sync.c:216
Inline: False
Direct callers:
  - fs/sync.c:__ia32_sys_fdatasync
  - fs/sync.c:__x64_sys_fdatasync
  - fs/sync.c:__ia32_sys_fsync
  - fs/sync.c:__x64_sys_fsync
```
**Symbols:**

```
ffffffff813117c0-ffffffff8131182d: do_fsync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int do_fsync(unsigned int fd, int datasync);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff813023d0)
Location: fs/sync.c:216
Inline: False
Direct callers:
  - fs/sync.c:__ia32_sys_fdatasync
  - fs/sync.c:__x64_sys_fdatasync
  - fs/sync.c:__ia32_sys_fsync
  - fs/sync.c:__x64_sys_fsync
```
**Symbols:**

```
ffffffff813023d0-ffffffff8130243d: do_fsync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int do_fsync(unsigned int fd, int datasync);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff8130f5b0)
Location: fs/sync.c:216
Inline: False
Direct callers:
  - fs/sync.c:__ia32_sys_fdatasync
  - fs/sync.c:__x64_sys_fdatasync
  - fs/sync.c:__ia32_sys_fsync
  - fs/sync.c:__x64_sys_fsync
```
**Symbols:**

```
ffffffff8130f5b0-ffffffff8130f61d: do_fsync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int do_fsync(unsigned int fd, int datasync);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff81320db0)
Location: fs/sync.c:216
Inline: False
Direct callers:
  - fs/sync.c:__ia32_sys_fdatasync
  - fs/sync.c:__x64_sys_fdatasync
  - fs/sync.c:__ia32_sys_fsync
  - fs/sync.c:__x64_sys_fsync
```
**Symbols:**

```
ffffffff81320db0-ffffffff81320e1d: do_fsync (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
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
