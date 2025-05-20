# Function: <code>urandom_read</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
ssize_t urandom_read(struct file *file, char *buf, size_t nbytes, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff815138c0)
Location: drivers/char/random.c:1458
Inline: False
Direct callers:
  - drivers/char/random.c:SyS_getrandom
```
**Symbols:**

```
ffffffff815138c0-ffffffff815139c5: urandom_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
ssize_t urandom_read(struct file *file, char *buf, size_t nbytes, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81567e90)
Location: drivers/char/random.c:1739
Inline: False
Direct callers:
  - drivers/char/random.c:SyS_getrandom
```
**Symbols:**

```
ffffffff81567e90-ffffffff81568104: urandom_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
ssize_t urandom_read(struct file *file, char *buf, size_t nbytes, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff815945d0)
Location: drivers/char/random.c:1739
Inline: False
Direct callers:
  - drivers/char/random.c:SyS_getrandom
```
**Symbols:**

```
ffffffff815945d0-ffffffff8159482b: urandom_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ssize_t urandom_read(struct file *file, char *buf, size_t nbytes, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff815a8600)
Location: drivers/char/random.c:1767
Inline: False
Direct callers:
  - drivers/char/random.c:SyS_getrandom
```
**Symbols:**

```
ffffffff815a8600-ffffffff815a886d: urandom_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t urandom_read(struct file *file, char *buf, size_t nbytes, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff8160ef10)
Location: drivers/char/random.c:1766
Inline: False
Direct callers:
  - drivers/char/random.c:SyS_getrandom
```
**Symbols:**

```
ffffffff8160ef10-ffffffff8160f16c: urandom_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
ssize_t urandom_read(struct file *file, char *buf, size_t nbytes, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/random.c (0)
Location: drivers/char/random.c:1857
Inline: False
Direct callers:
  - drivers/char/random.c:__ia32_sys_getrandom
  - drivers/char/random.c:__x64_sys_getrandom
```
**Symbols:**

```
ffffffff81648a10-ffffffff81648c65: urandom_read (STB_LOCAL)
ffffffff81649241-ffffffff81649265: urandom_read.cold.44 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
ssize_t urandom_read(struct file *file, char *buf, size_t nbytes, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/random.c (0)
Location: drivers/char/random.c:1882
Inline: False
Direct callers:
  - drivers/char/random.c:__ia32_sys_getrandom
  - drivers/char/random.c:__x64_sys_getrandom
```
**Symbols:**

```
ffffffff81666c30-ffffffff81666e85: urandom_read (STB_LOCAL)
ffffffff81667541-ffffffff81667565: urandom_read.cold.44 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
ssize_t urandom_read(struct file *file, char *buf, size_t nbytes, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/random.c (0)
Location: drivers/char/random.c:1963
Inline: False
Direct callers:
  - drivers/char/random.c:__ia32_sys_getrandom
  - drivers/char/random.c:__x64_sys_getrandom
```
**Symbols:**

```
ffffffff8169c990-ffffffff8169cbff: urandom_read (STB_LOCAL)
ffffffff8169cfe9-ffffffff8169d00d: urandom_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
ssize_t urandom_read(struct file *file, char *buf, size_t nbytes, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/random.c (0)
Location: drivers/char/random.c:2024
Inline: False
Direct callers:
  - drivers/char/random.c:__ia32_sys_getrandom
  - drivers/char/random.c:__x64_sys_getrandom
```
**Symbols:**

```
ffffffff816bf700-ffffffff816bf96f: urandom_read (STB_LOCAL)
ffffffff816bfd41-ffffffff816bfd65: urandom_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
ssize_t urandom_read(struct file *file, char *buf, size_t nbytes, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/random.c (0)
Location: drivers/char/random.c:1842
Inline: False
```
**Symbols:**

```
ffffffff817731d0-ffffffff81773252: urandom_read (STB_LOCAL)
ffffffff81773bfa-ffffffff81773c1e: urandom_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
ssize_t urandom_read(struct file *file, char *buf, size_t nbytes, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/random.c (0)
Location: drivers/char/random.c:1841
Inline: False
```
**Symbols:**

```
ffffffff8178e1a0-ffffffff8178e222: urandom_read (STB_LOCAL)
ffffffff81c0858f-ffffffff81c085b3: urandom_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
ssize_t urandom_read(struct file *file, char *buf, size_t nbytes, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/random.c (0)
Location: drivers/char/random.c:1817
Inline: False
```
**Symbols:**

```
ffffffff81770ab0-ffffffff81770b32: urandom_read (STB_LOCAL)
ffffffff81bfa130-ffffffff81bfa154: urandom_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
ssize_t urandom_read(struct file *file, char *buf, size_t nbytes, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/random.c (0)
Location: drivers/char/random.c:1839
Inline: False
```
**Symbols:**

```
ffffffff817f6520-ffffffff817f65a2: urandom_read (STB_LOCAL)
ffffffff81cfaa26-ffffffff81cfaa4a: urandom_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
ssize_t urandom_read(struct file *file, char *buf, size_t nbytes, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffff8000108b0a50)
Location: drivers/char/random.c:2024
Inline: False
Direct callers:
  - drivers/char/random.c:__arm64_sys_getrandom
```
**Symbols:**

```
ffff8000108b0a50-ffff8000108b0e68: urandom_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t urandom_read(struct file *file, char *buf, size_t nbytes, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (c09aa3e0)
Location: drivers/char/random.c:2024
Inline: False
Direct callers:
  - drivers/char/random.c:__se_sys_getrandom
```
**Symbols:**

```
c09aa3e0-c09aa738: urandom_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t urandom_read(struct file *file, char *buf, size_t nbytes, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (c000000000948360)
Location: drivers/char/random.c:2024
Inline: False
Direct callers:
  - drivers/char/random.c:__se_sys_getrandom
```
**Symbols:**

```
c000000000948360-c0000000009486d8: urandom_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ssize_t urandom_read(struct file *file, char *buf, size_t nbytes, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffe0005621d4)
Location: drivers/char/random.c:2024
Inline: False
Direct callers:
  - drivers/char/random.c:__se_sys_getrandom
```
**Symbols:**

```
ffffffe0005621d4-ffffffe0005623f4: urandom_read (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
ssize_t urandom_read(struct file *file, char *buf, size_t nbytes, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/random.c (0)
Location: drivers/char/random.c:2024
Inline: False
Direct callers:
  - drivers/char/random.c:__ia32_sys_getrandom
  - drivers/char/random.c:__x64_sys_getrandom
```
**Symbols:**

```
ffffffff81685150-ffffffff816853bf: urandom_read (STB_LOCAL)
ffffffff81685791-ffffffff816857b5: urandom_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
ssize_t urandom_read(struct file *file, char *buf, size_t nbytes, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/random.c (0)
Location: drivers/char/random.c:2024
Inline: False
Direct callers:
  - drivers/char/random.c:__ia32_sys_getrandom
  - drivers/char/random.c:__x64_sys_getrandom
```
**Symbols:**

```
ffffffff81662df0-ffffffff8166305f: urandom_read (STB_LOCAL)
ffffffff81663431-ffffffff81663455: urandom_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
ssize_t urandom_read(struct file *file, char *buf, size_t nbytes, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/random.c (0)
Location: drivers/char/random.c:2024
Inline: False
Direct callers:
  - drivers/char/random.c:__ia32_sys_getrandom
  - drivers/char/random.c:__x64_sys_getrandom
```
**Symbols:**

```
ffffffff816b3540-ffffffff816b37af: urandom_read (STB_LOCAL)
ffffffff816b3b81-ffffffff816b3ba5: urandom_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
ssize_t urandom_read(struct file *file, char *buf, size_t nbytes, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/random.c (0)
Location: drivers/char/random.c:2024
Inline: False
Direct callers:
  - drivers/char/random.c:__ia32_sys_getrandom
  - drivers/char/random.c:__x64_sys_getrandom
```
**Symbols:**

```
ffffffff816cdac0-ffffffff816cdd4b: urandom_read (STB_LOCAL)
ffffffff816ce0e1-ffffffff816ce105: urandom_read.cold (STB_LOCAL)
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
