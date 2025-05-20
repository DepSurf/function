# Function: <code>f_dupfd</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int f_dupfd(unsigned int from, struct file *file, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff8122aff0)
Location: fs/file.c:947
Inline: False
Direct callers:
  - fs/fcntl.c:SyS_fcntl
  - fs/fcntl.c:SyS_fcntl
```
**Symbols:**

```
ffffffff8122aff0-ffffffff8122b06a: f_dupfd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int f_dupfd(unsigned int from, struct file *file, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81253750)
Location: fs/file.c:953
Inline: False
Direct callers:
  - fs/fcntl.c:SyS_fcntl
  - fs/fcntl.c:SyS_fcntl
```
**Symbols:**

```
ffffffff81253750-ffffffff812537ca: f_dupfd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int f_dupfd(unsigned int from, struct file *file, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812669a0)
Location: fs/file.c:953
Inline: False
Direct callers:
  - fs/fcntl.c:SyS_fcntl
  - fs/fcntl.c:SyS_fcntl
```
**Symbols:**

```
ffffffff812669a0-ffffffff81266a1a: f_dupfd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int f_dupfd(unsigned int from, struct file *file, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812741a0)
Location: fs/file.c:939
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:do_fcntl
```
**Symbols:**

```
ffffffff812741a0-ffffffff8127421c: f_dupfd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int f_dupfd(unsigned int from, struct file *file, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81296aa0)
Location: fs/file.c:942
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:do_fcntl
```
**Symbols:**

```
ffffffff81296aa0-ffffffff81296b1c: f_dupfd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int f_dupfd(unsigned int from, struct file *file, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812bcc40)
Location: fs/file.c:948
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:do_fcntl
```
**Symbols:**

```
ffffffff812bcc40-ffffffff812bccbc: f_dupfd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int f_dupfd(unsigned int from, struct file *file, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812d1f00)
Location: fs/file.c:978
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:do_fcntl
```
**Symbols:**

```
ffffffff812d1f00-ffffffff812d1f7c: f_dupfd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int f_dupfd(unsigned int from, struct file *file, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812eef40)
Location: fs/file.c:984
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:do_fcntl
```
**Symbols:**

```
ffffffff812eef40-ffffffff812eefbc: f_dupfd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int f_dupfd(unsigned int from, struct file *file, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81300a00)
Location: fs/file.c:984
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:do_fcntl
```
**Symbols:**

```
ffffffff81300a00-ffffffff81300a7c: f_dupfd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int f_dupfd(unsigned int from, struct file *file, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81339c40)
Location: fs/file.c:1009
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:do_fcntl
```
**Symbols:**

```
ffffffff81339c40-ffffffff81339cbc: f_dupfd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int f_dupfd(unsigned int from, struct file *file, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff813459a0)
Location: fs/file.c:1196
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:do_fcntl
```
**Symbols:**

```
ffffffff813459a0-ffffffff813459fb: f_dupfd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int f_dupfd(unsigned int from, struct file *file, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff8134bd60)
Location: fs/file.c:1207
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:do_fcntl
```
**Symbols:**

```
ffffffff8134bd60-ffffffff8134bdbb: f_dupfd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int f_dupfd(unsigned int from, struct file *file, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81399ba0)
Location: fs/file.c:1273
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:do_fcntl
```
**Symbols:**

```
ffffffff81399ba0-ffffffff81399bfb: f_dupfd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int f_dupfd(unsigned int from, struct file *file, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff8141c650)
Location: fs/file.c:1275
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:do_fcntl
```
**Symbols:**

```
ffffffff8141c650-ffffffff8141c6b6: f_dupfd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int f_dupfd(unsigned int from, struct file *file, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff814a8760)
Location: fs/file.c:1285
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:do_fcntl
```
**Symbols:**

```
ffffffff814a8760-ffffffff814a87c6: f_dupfd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int f_dupfd(unsigned int from, struct file *file, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff814dd750)
Location: fs/file.c:1300
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:do_fcntl
```
**Symbols:**

```
ffffffff814dd750-ffffffff814dd7b6: f_dupfd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int f_dupfd(unsigned int from, struct file *file, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff815101a0)
Location: fs/file.c:1428
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:do_fcntl
```
**Symbols:**

```
ffffffff815101a0-ffffffff81510206: f_dupfd (STB_GLOBAL)
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
int f_dupfd(unsigned int from, struct file *file, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffff8000103b2988)
Location: fs/file.c:984
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:do_fcntl
```
**Symbols:**

```
ffff8000103b2988-ffff8000103b2a40: f_dupfd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int f_dupfd(unsigned int from, struct file *file, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (c0591c64)
Location: fs/file.c:984
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:do_fcntl
```
**Symbols:**

```
c0591c64-c0591d04: f_dupfd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int f_dupfd(unsigned int from, struct file *file, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (c0000000004ae8e0)
Location: fs/file.c:984
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:do_fcntl
```
**Symbols:**

```
c0000000004ae8e0-c0000000004ae9c8: f_dupfd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int f_dupfd(unsigned int from, struct file *file, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffe0002769ce)
Location: fs/file.c:984
Inline: False
Direct callers:
  - fs/fcntl.c:__se_sys_fcntl
  - fs/fcntl.c:__se_sys_fcntl
```
**Symbols:**

```
ffffffe0002769ce-ffffffe000276a4a: f_dupfd (STB_GLOBAL)
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
int f_dupfd(unsigned int from, struct file *file, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812f8fe0)
Location: fs/file.c:984
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:do_fcntl
```
**Symbols:**

```
ffffffff812f8fe0-ffffffff812f905c: f_dupfd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int f_dupfd(unsigned int from, struct file *file, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812e9c00)
Location: fs/file.c:984
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:do_fcntl
```
**Symbols:**

```
ffffffff812e9c00-ffffffff812e9c7c: f_dupfd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int f_dupfd(unsigned int from, struct file *file, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812f6df0)
Location: fs/file.c:984
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:do_fcntl
```
**Symbols:**

```
ffffffff812f6df0-ffffffff812f6e6c: f_dupfd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int f_dupfd(unsigned int from, struct file *file, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81308060)
Location: fs/file.c:984
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:do_fcntl
```
**Symbols:**

```
ffffffff81308060-ffffffff813080dc: f_dupfd (STB_GLOBAL)
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
