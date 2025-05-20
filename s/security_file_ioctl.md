# Function: <code>security_file_ioctl</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int security_file_ioctl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8133de10)
Location: security/security.c:759
Inline: False
Direct callers:
  - fs/ioctl.c:SyS_ioctl
  - fs/compat_ioctl.c:compat_SyS_ioctl
```
**Symbols:**

```
ffffffff8133de10-ffffffff8133de6b: security_file_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int security_file_ioctl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81373470)
Location: security/security.c:781
Inline: False
Direct callers:
  - fs/ioctl.c:SyS_ioctl
  - fs/compat_ioctl.c:compat_SyS_ioctl
  - fs/compat_ioctl.c:do_ioctl
```
**Symbols:**

```
ffffffff81373470-ffffffff813734cb: security_file_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int security_file_ioctl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81389da0)
Location: security/security.c:802
Inline: False
Direct callers:
  - fs/ioctl.c:SyS_ioctl
  - fs/compat_ioctl.c:compat_SyS_ioctl
  - fs/compat_ioctl.c:do_ioctl
```
**Symbols:**

```
ffffffff81389da0-ffffffff81389dfb: security_file_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int security_file_ioctl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8139f1a0)
Location: security/security.c:1414
Inline: False
Direct callers:
  - fs/ioctl.c:SyS_ioctl
  - fs/compat_ioctl.c:compat_SyS_ioctl
  - fs/compat_ioctl.c:do_ioctl
```
**Symbols:**

```
ffffffff8139f1a0-ffffffff8139f1fb: security_file_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int security_file_ioctl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813c4cc0)
Location: security/security.c:1372
Inline: False
Direct callers:
  - fs/ioctl.c:SyS_ioctl
  - fs/compat_ioctl.c:compat_SyS_ioctl
  - fs/compat_ioctl.c:do_ioctl
```
**Symbols:**

```
ffffffff813c4cc0-ffffffff813c4d21: security_file_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int security_file_ioctl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813f4fc0)
Location: security/security.c:898
Inline: False
Direct callers:
  - fs/ioctl.c:ksys_ioctl
  - fs/compat_ioctl.c:__x32_compat_sys_ioctl
  - fs/compat_ioctl.c:__ia32_compat_sys_ioctl
  - fs/compat_ioctl.c:do_ioctl
```
**Symbols:**

```
ffffffff813f4fc0-ffffffff813f500e: security_file_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int security_file_ioctl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81410400)
Location: security/security.c:1434
Inline: False
Direct callers:
  - fs/ioctl.c:ksys_ioctl
  - fs/compat_ioctl.c:__x32_compat_sys_ioctl
  - fs/compat_ioctl.c:__ia32_compat_sys_ioctl
  - fs/compat_ioctl.c:do_ioctl
```
**Symbols:**

```
ffffffff81410400-ffffffff8141044e: security_file_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int security_file_ioctl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8143db30)
Location: security/security.c:1453
Inline: False
Direct callers:
  - fs/ioctl.c:ksys_ioctl
  - fs/compat_ioctl.c:__x32_compat_sys_ioctl
  - fs/compat_ioctl.c:__ia32_compat_sys_ioctl
  - fs/compat_ioctl.c:do_ioctl
```
**Symbols:**

```
ffffffff8143db30-ffffffff8143db89: security_file_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int security_file_ioctl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81457580)
Location: security/security.c:1493
Inline: False
Direct callers:
  - fs/ioctl.c:ksys_ioctl
  - fs/compat_ioctl.c:__x32_compat_sys_ioctl
  - fs/compat_ioctl.c:__ia32_compat_sys_ioctl
  - fs/compat_ioctl.c:do_ioctl
```
**Symbols:**

```
ffffffff81457580-ffffffff814575ce: security_file_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int security_file_ioctl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814a7550)
Location: security/security.c:1663
Inline: False
Direct callers:
  - fs/ioctl.c:__do_compat_sys_ioctl
  - fs/ioctl.c:ksys_ioctl
```
**Symbols:**

```
ffffffff814a7550-ffffffff814a759e: security_file_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int security_file_ioctl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814c4ad0)
Location: security/security.c:1665
Inline: False
Direct callers:
  - fs/ioctl.c:__do_compat_sys_ioctl
  - fs/ioctl.c:__ia32_sys_ioctl
  - fs/ioctl.c:__x64_sys_ioctl
```
**Symbols:**

```
ffffffff814c4ad0-ffffffff814c4b1e: security_file_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int security_file_ioctl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814cafc0)
Location: security/security.c:1715
Inline: False
Direct callers:
  - fs/ioctl.c:__do_compat_sys_ioctl
  - fs/ioctl.c:__ia32_sys_ioctl
  - fs/ioctl.c:__x64_sys_ioctl
```
**Symbols:**

```
ffffffff814cafc0-ffffffff814cb00e: security_file_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int security_file_ioctl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81523cc0)
Location: security/security.c:1723
Inline: False
Direct callers:
  - fs/ioctl.c:__do_compat_sys_ioctl
  - fs/ioctl.c:__ia32_sys_ioctl
  - fs/ioctl.c:__x64_sys_ioctl
```
**Symbols:**

```
ffffffff81523cc0-ffffffff81523d0e: security_file_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int security_file_ioctl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff815b7a80)
Location: security/security.c:1728
Inline: False
Direct callers:
  - fs/ioctl.c:__do_compat_sys_ioctl
  - fs/ioctl.c:__ia32_sys_ioctl
  - fs/ioctl.c:__x64_sys_ioctl
```
**Symbols:**

```
ffffffff815b7a80-ffffffff815b7aed: security_file_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int security_file_ioctl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81662e50)
Location: security/security.c:1769
Inline: False
Direct callers:
  - fs/ioctl.c:__do_compat_sys_ioctl
  - fs/ioctl.c:__ia32_sys_ioctl
  - fs/ioctl.c:__x64_sys_ioctl
```
**Symbols:**

```
ffffffff81662e50-ffffffff81662ebd: security_file_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int security_file_ioctl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8169b350)
Location: security/security.c:2766
Inline: False
Direct callers:
  - fs/ioctl.c:__do_compat_sys_ioctl
  - fs/ioctl.c:__ia32_sys_ioctl
  - fs/ioctl.c:__x64_sys_ioctl
```
**Symbols:**

```
ffffffff8169b350-ffffffff8169b3bd: security_file_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int security_file_ioctl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816d7d30)
Location: security/security.c:2826
Inline: False
Direct callers:
  - fs/ioctl.c:__ia32_sys_ioctl
  - fs/ioctl.c:__x64_sys_ioctl
```
**Symbols:**

```
ffffffff816d7d30-ffffffff816d7d9d: security_file_ioctl (STB_GLOBAL)
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
int security_file_ioctl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffff800010543138)
Location: security/security.c:1493
Inline: False
Direct callers:
  - fs/ioctl.c:ksys_ioctl
  - fs/compat_ioctl.c:__arm64_compat_sys_ioctl
  - fs/compat_ioctl.c:do_ioctl
```
**Symbols:**

```
ffff800010543138-ffff80001054319c: security_file_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int security_file_ioctl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c06f90d0)
Location: security/security.c:1493
Inline: False
Direct callers:
  - fs/ioctl.c:ksys_ioctl
```
**Symbols:**

```
c06f90d0-c06f9134: security_file_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int security_file_ioctl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c000000000696e10)
Location: security/security.c:1493
Inline: False
Direct callers:
  - fs/ioctl.c:ksys_ioctl
  - fs/compat_ioctl.c:__se_compat_sys_ioctl
  - fs/compat_ioctl.c:do_ioctl
```
**Symbols:**

```
c000000000696e10-c000000000696ee0: security_file_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int security_file_ioctl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffe00039f778)
Location: security/security.c:1493
Inline: False
Direct callers:
  - fs/ioctl.c:ksys_ioctl
```
**Symbols:**

```
ffffffe00039f778-ffffffe00039f7c4: security_file_ioctl (STB_GLOBAL)
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
int security_file_ioctl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144fb60)
Location: security/security.c:1493
Inline: False
Direct callers:
  - fs/ioctl.c:ksys_ioctl
  - fs/compat_ioctl.c:__x32_compat_sys_ioctl
  - fs/compat_ioctl.c:__ia32_compat_sys_ioctl
  - fs/compat_ioctl.c:do_ioctl
```
**Symbols:**

```
ffffffff8144fb60-ffffffff8144fbae: security_file_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int security_file_ioctl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814405b0)
Location: security/security.c:1493
Inline: False
Direct callers:
  - fs/ioctl.c:ksys_ioctl
  - fs/compat_ioctl.c:__x32_compat_sys_ioctl
  - fs/compat_ioctl.c:__ia32_compat_sys_ioctl
  - fs/compat_ioctl.c:do_ioctl
```
**Symbols:**

```
ffffffff814405b0-ffffffff814405fe: security_file_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int security_file_ioctl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144bc00)
Location: security/security.c:1493
Inline: False
Direct callers:
  - fs/ioctl.c:ksys_ioctl
  - fs/compat_ioctl.c:__x32_compat_sys_ioctl
  - fs/compat_ioctl.c:__ia32_compat_sys_ioctl
  - fs/compat_ioctl.c:do_ioctl
```
**Symbols:**

```
ffffffff8144bc00-ffffffff8144bc4e: security_file_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int security_file_ioctl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81462fd0)
Location: security/security.c:1493
Inline: False
Direct callers:
  - fs/ioctl.c:ksys_ioctl
  - fs/compat_ioctl.c:__x32_compat_sys_ioctl
  - fs/compat_ioctl.c:__ia32_compat_sys_ioctl
  - fs/compat_ioctl.c:do_ioctl
```
**Symbols:**

```
ffffffff81462fd0-ffffffff8146301e: security_file_ioctl (STB_GLOBAL)
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
