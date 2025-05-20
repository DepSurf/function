# Function: <code>security_file_fcntl</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int security_file_fcntl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8133df70)
Location: security/security.c:825
Inline: False
Direct callers:
  - fs/fcntl.c:SyS_fcntl
```
**Symbols:**

```
ffffffff8133df70-ffffffff8133dfcb: security_file_fcntl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int security_file_fcntl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813735d0)
Location: security/security.c:847
Inline: False
Direct callers:
  - fs/fcntl.c:SyS_fcntl
```
**Symbols:**

```
ffffffff813735d0-ffffffff8137362b: security_file_fcntl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int security_file_fcntl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81389f00)
Location: security/security.c:868
Inline: False
Direct callers:
  - fs/fcntl.c:SyS_fcntl
```
**Symbols:**

```
ffffffff81389f00-ffffffff81389f5b: security_file_fcntl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int security_file_fcntl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8139f300)
Location: security/security.c:1480
Inline: False
Direct callers:
  - fs/fcntl.c:compat_SyS_fcntl
  - fs/fcntl.c:SyS_fcntl
```
**Symbols:**

```
ffffffff8139f300-ffffffff8139f35b: security_file_fcntl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int security_file_fcntl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813c4e50)
Location: security/security.c:1438
Inline: False
Direct callers:
  - fs/fcntl.c:compat_SyS_fcntl
  - fs/fcntl.c:SyS_fcntl
```
**Symbols:**

```
ffffffff813c4e50-ffffffff813c4eb1: security_file_fcntl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int security_file_fcntl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813f50f0)
Location: security/security.c:964
Inline: False
Direct callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:__ia32_sys_fcntl
  - fs/fcntl.c:__x64_sys_fcntl
```
**Symbols:**

```
ffffffff813f50f0-ffffffff813f513e: security_file_fcntl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int security_file_fcntl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81410530)
Location: security/security.c:1500
Inline: False
Direct callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:__ia32_sys_fcntl
  - fs/fcntl.c:__x64_sys_fcntl
```
**Symbols:**

```
ffffffff81410530-ffffffff8141057e: security_file_fcntl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int security_file_fcntl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8143dc90)
Location: security/security.c:1519
Inline: False
Direct callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:__ia32_sys_fcntl
  - fs/fcntl.c:__x64_sys_fcntl
```
**Symbols:**

```
ffffffff8143dc90-ffffffff8143dce9: security_file_fcntl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int security_file_fcntl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81457770)
Location: security/security.c:1558
Inline: False
Direct callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:__ia32_sys_fcntl
  - fs/fcntl.c:__x64_sys_fcntl
```
**Symbols:**

```
ffffffff81457770-ffffffff814577be: security_file_fcntl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int security_file_fcntl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814aa570)
Location: security/security.c:1734
Inline: False
Direct callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:__ia32_sys_fcntl
  - fs/fcntl.c:__x64_sys_fcntl
```
**Symbols:**

```
ffffffff814aa570-ffffffff814aa5be: security_file_fcntl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int security_file_fcntl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814c7b80)
Location: security/security.c:1736
Inline: False
Direct callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:__ia32_sys_fcntl
  - fs/fcntl.c:__x64_sys_fcntl
```
**Symbols:**

```
ffffffff814c7b80-ffffffff814c7bce: security_file_fcntl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int security_file_fcntl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814ce1b0)
Location: security/security.c:1786
Inline: False
Direct callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:__ia32_sys_fcntl
  - fs/fcntl.c:__x64_sys_fcntl
```
**Symbols:**

```
ffffffff814ce1b0-ffffffff814ce1fe: security_file_fcntl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int security_file_fcntl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81526f60)
Location: security/security.c:1794
Inline: False
Direct callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:__ia32_sys_fcntl
  - fs/fcntl.c:__x64_sys_fcntl
```
**Symbols:**

```
ffffffff81526f60-ffffffff81526fae: security_file_fcntl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int security_file_fcntl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff815bbb90)
Location: security/security.c:1799
Inline: False
Direct callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:__ia32_sys_fcntl
  - fs/fcntl.c:__x64_sys_fcntl
```
**Symbols:**

```
ffffffff815bbb90-ffffffff815bbbfd: security_file_fcntl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int security_file_fcntl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816679a0)
Location: security/security.c:1841
Inline: False
Direct callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:__ia32_sys_fcntl
  - fs/fcntl.c:__x64_sys_fcntl
```
**Symbols:**

```
ffffffff816679a0-ffffffff81667a0d: security_file_fcntl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int security_file_fcntl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8169ffc0)
Location: security/security.c:2891
Inline: False
Direct callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:__ia32_sys_fcntl
  - fs/fcntl.c:__x64_sys_fcntl
```
**Symbols:**

```
ffffffff8169ffc0-ffffffff816a002d: security_file_fcntl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int security_file_fcntl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816dc8b0)
Location: security/security.c:2969
Inline: False
Direct callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:__ia32_sys_fcntl
  - fs/fcntl.c:__x64_sys_fcntl
```
**Symbols:**

```
ffffffff816dc8b0-ffffffff816dc91d: security_file_fcntl (STB_GLOBAL)
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
int security_file_fcntl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffff8000105433b0)
Location: security/security.c:1558
Inline: False
Direct callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:__arm64_sys_fcntl
```
**Symbols:**

```
ffff8000105433b0-ffff800010543414: security_file_fcntl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int security_file_fcntl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c06f9310)
Location: security/security.c:1558
Inline: False
Direct callers:
  - fs/fcntl.c:__se_sys_fcntl64
  - fs/fcntl.c:__se_sys_fcntl64
  - fs/fcntl.c:__se_sys_fcntl
```
**Symbols:**

```
c06f9310-c06f9374: security_file_fcntl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int security_file_fcntl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c0000000006972c0)
Location: security/security.c:1558
Inline: False
Direct callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:__se_sys_fcntl
```
**Symbols:**

```
c0000000006972c0-c000000000697390: security_file_fcntl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int security_file_fcntl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffe00039f938)
Location: security/security.c:1558
Inline: False
Direct callers:
  - fs/fcntl.c:__se_sys_fcntl
  - fs/fcntl.c:__se_sys_fcntl
```
**Symbols:**

```
ffffffe00039f938-ffffffe00039f984: security_file_fcntl (STB_GLOBAL)
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
int security_file_fcntl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144fd50)
Location: security/security.c:1558
Inline: False
Direct callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:__ia32_sys_fcntl
  - fs/fcntl.c:__x64_sys_fcntl
```
**Symbols:**

```
ffffffff8144fd50-ffffffff8144fd9e: security_file_fcntl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int security_file_fcntl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814407a0)
Location: security/security.c:1558
Inline: False
Direct callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:__ia32_sys_fcntl
  - fs/fcntl.c:__x64_sys_fcntl
```
**Symbols:**

```
ffffffff814407a0-ffffffff814407ee: security_file_fcntl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int security_file_fcntl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144bdf0)
Location: security/security.c:1558
Inline: False
Direct callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:__ia32_sys_fcntl
  - fs/fcntl.c:__x64_sys_fcntl
```
**Symbols:**

```
ffffffff8144bdf0-ffffffff8144be3e: security_file_fcntl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int security_file_fcntl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814631c0)
Location: security/security.c:1558
Inline: False
Direct callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:__ia32_sys_fcntl
  - fs/fcntl.c:__x64_sys_fcntl
```
**Symbols:**

```
ffffffff814631c0-ffffffff8146320e: security_file_fcntl (STB_GLOBAL)
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
