# Function: <code>ksys_lseek</code>

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
off_t ksys_lseek(unsigned int fd, off_t offset, unsigned int whence);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812986d0)
Location: fs/read_write.c:304
Inline: False
Direct callers:
  - fs/read_write.c:__x32_compat_sys_lseek
  - fs/read_write.c:__ia32_compat_sys_lseek
  - fs/read_write.c:__ia32_sys_lseek
  - fs/read_write.c:__x64_sys_lseek
```
**Symbols:**

```
ffffffff812986d0-ffffffff8129877e: ksys_lseek (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
off_t ksys_lseek(unsigned int fd, off_t offset, unsigned int whence);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812ad550)
Location: fs/read_write.c:304
Inline: False
Direct callers:
  - fs/read_write.c:__x32_compat_sys_lseek
  - fs/read_write.c:__ia32_compat_sys_lseek
  - fs/read_write.c:__ia32_sys_lseek
  - fs/read_write.c:__x64_sys_lseek
```
**Symbols:**

```
ffffffff812ad550-ffffffff812ad5fe: ksys_lseek (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
off_t ksys_lseek(unsigned int fd, off_t offset, unsigned int whence);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812c9fd0)
Location: fs/read_write.c:304
Inline: False
Direct callers:
  - fs/read_write.c:__x32_compat_sys_lseek
  - fs/read_write.c:__ia32_compat_sys_lseek
  - fs/read_write.c:__ia32_sys_lseek
  - fs/read_write.c:__x64_sys_lseek
```
**Symbols:**

```
ffffffff812c9fd0-ffffffff812ca07c: ksys_lseek (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
off_t ksys_lseek(unsigned int fd, off_t offset, unsigned int whence);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812db9f0)
Location: fs/read_write.c:304
Inline: False
Direct callers:
  - fs/read_write.c:__x32_compat_sys_lseek
  - fs/read_write.c:__ia32_compat_sys_lseek
  - fs/read_write.c:__ia32_sys_lseek
  - fs/read_write.c:__x64_sys_lseek
```
**Symbols:**

```
ffffffff812db9f0-ffffffff812dba9c: ksys_lseek (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
off_t ksys_lseek(unsigned int fd, off_t offset, unsigned int whence);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81311fc0)
Location: fs/read_write.c:304
Inline: False
Direct callers:
  - fs/read_write.c:__x32_compat_sys_lseek
  - fs/read_write.c:__ia32_compat_sys_lseek
  - fs/read_write.c:__ia32_sys_lseek
  - fs/read_write.c:__x64_sys_lseek
```
**Symbols:**

```
ffffffff81311fc0-ffffffff81312078: ksys_lseek (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
off_t ksys_lseek(unsigned int fd, off_t offset, unsigned int whence);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff8131cc90)
Location: fs/read_write.c:304
Inline: False
Direct callers:
  - fs/read_write.c:__x32_compat_sys_lseek
  - fs/read_write.c:__ia32_compat_sys_lseek
  - fs/read_write.c:__ia32_sys_lseek
  - fs/read_write.c:__x64_sys_lseek
```
**Symbols:**

```
ffffffff8131cc90-ffffffff8131cd48: ksys_lseek (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
off_t ksys_lseek(unsigned int fd, off_t offset, unsigned int whence);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81322e00)
Location: fs/read_write.c:304
Inline: False
Direct callers:
  - fs/read_write.c:__x32_compat_sys_lseek
  - fs/read_write.c:__ia32_compat_sys_lseek
  - fs/read_write.c:__ia32_sys_lseek
  - fs/read_write.c:__x64_sys_lseek
```
**Symbols:**

```
ffffffff81322e00-ffffffff81322eb8: ksys_lseek (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
off_t ksys_lseek(unsigned int fd, off_t offset, unsigned int whence);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff813702f0)
Location: fs/read_write.c:304
Inline: False
Direct callers:
  - fs/read_write.c:__x64_compat_sys_lseek
  - fs/read_write.c:__ia32_compat_sys_lseek
  - fs/read_write.c:__ia32_sys_lseek
  - fs/read_write.c:__x64_sys_lseek
```
**Symbols:**

```
ffffffff813702f0-ffffffff813703a8: ksys_lseek (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
off_t ksys_lseek(unsigned int fd, off_t offset, unsigned int whence);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff813eede0)
Location: fs/read_write.c:304
Inline: False
Direct callers:
  - fs/read_write.c:__ia32_compat_sys_lseek
  - fs/read_write.c:__ia32_sys_lseek
  - fs/read_write.c:__x64_sys_lseek
```
**Symbols:**

```
ffffffff813eede0-ffffffff813eeeb3: ksys_lseek (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
off_t ksys_lseek(unsigned int fd, off_t offset, unsigned int whence);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81477710)
Location: fs/read_write.c:293
Inline: False
Direct callers:
  - fs/read_write.c:__ia32_compat_sys_lseek
  - fs/read_write.c:__ia32_sys_lseek
  - fs/read_write.c:__x64_sys_lseek
```
**Symbols:**

```
ffffffff81477710-ffffffff814777d7: ksys_lseek (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
off_t ksys_lseek(unsigned int fd, off_t offset, unsigned int whence);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff814ac9e0)
Location: fs/read_write.c:293
Inline: False
Direct callers:
  - fs/read_write.c:__ia32_compat_sys_lseek
  - fs/read_write.c:__ia32_sys_lseek
  - fs/read_write.c:__x64_sys_lseek
```
**Symbols:**

```
ffffffff814ac9e0-ffffffff814acaaa: ksys_lseek (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
off_t ksys_lseek(unsigned int fd, off_t offset, unsigned int whence);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff814dd4b0)
Location: fs/read_write.c:293
Inline: False
Direct callers:
  - fs/read_write.c:__ia32_compat_sys_lseek
  - fs/read_write.c:__ia32_sys_lseek
  - fs/read_write.c:__x64_sys_lseek
```
**Symbols:**

```
ffffffff814dd4b0-ffffffff814dd57a: ksys_lseek (STB_LOCAL)
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
off_t ksys_lseek(unsigned int fd, off_t offset, unsigned int whence);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffff800010381348)
Location: fs/read_write.c:304
Inline: False
Direct callers:
  - fs/read_write.c:__arm64_compat_sys_lseek
  - fs/read_write.c:__arm64_sys_lseek
```
**Symbols:**

```
ffff800010381348-ffff800010381424: ksys_lseek (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
off_t ksys_lseek(unsigned int fd, off_t offset, unsigned int whence);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (c056ba18)
Location: fs/read_write.c:304
Inline: False
Direct callers:
  - fs/read_write.c:__se_sys_lseek
```
**Symbols:**

```
c056ba18-c056baf4: ksys_lseek (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
off_t ksys_lseek(unsigned int fd, off_t offset, unsigned int whence);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (c000000000477640)
Location: fs/read_write.c:304
Inline: False
Direct callers:
  - fs/read_write.c:__se_compat_sys_lseek
  - fs/read_write.c:__se_sys_lseek
```
**Symbols:**

```
c000000000477640-c000000000477784: ksys_lseek (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
off_t ksys_lseek(unsigned int fd, off_t offset, unsigned int whence);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffe00025642c)
Location: fs/read_write.c:304
Inline: False
Direct callers:
  - fs/read_write.c:__se_sys_lseek
```
**Symbols:**

```
ffffffe00025642c-ffffffe0002564dc: ksys_lseek (STB_GLOBAL)
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
off_t ksys_lseek(unsigned int fd, off_t offset, unsigned int whence);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812d3fd0)
Location: fs/read_write.c:304
Inline: False
Direct callers:
  - fs/read_write.c:__x32_compat_sys_lseek
  - fs/read_write.c:__ia32_compat_sys_lseek
  - fs/read_write.c:__ia32_sys_lseek
  - fs/read_write.c:__x64_sys_lseek
```
**Symbols:**

```
ffffffff812d3fd0-ffffffff812d407c: ksys_lseek (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
off_t ksys_lseek(unsigned int fd, off_t offset, unsigned int whence);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812c4c50)
Location: fs/read_write.c:304
Inline: False
Direct callers:
  - fs/read_write.c:__x32_compat_sys_lseek
  - fs/read_write.c:__ia32_compat_sys_lseek
  - fs/read_write.c:__ia32_sys_lseek
  - fs/read_write.c:__x64_sys_lseek
```
**Symbols:**

```
ffffffff812c4c50-ffffffff812c4cfc: ksys_lseek (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
off_t ksys_lseek(unsigned int fd, off_t offset, unsigned int whence);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812d1de0)
Location: fs/read_write.c:304
Inline: False
Direct callers:
  - fs/read_write.c:__x32_compat_sys_lseek
  - fs/read_write.c:__ia32_compat_sys_lseek
  - fs/read_write.c:__ia32_sys_lseek
  - fs/read_write.c:__x64_sys_lseek
```
**Symbols:**

```
ffffffff812d1de0-ffffffff812d1e8c: ksys_lseek (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
off_t ksys_lseek(unsigned int fd, off_t offset, unsigned int whence);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812e2c40)
Location: fs/read_write.c:304
Inline: False
Direct callers:
  - fs/read_write.c:__x32_compat_sys_lseek
  - fs/read_write.c:__ia32_compat_sys_lseek
  - fs/read_write.c:__ia32_sys_lseek
  - fs/read_write.c:__x64_sys_lseek
```
**Symbols:**

```
ffffffff812e2c40-ffffffff812e2cec: ksys_lseek (STB_GLOBAL)
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
