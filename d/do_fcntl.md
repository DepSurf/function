# Function: <code>do_fcntl</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff8121eea8)
Location: fs/fcntl.c:243
Inline: True
Inline callers:
  - fs/fcntl.c:SyS_fcntl
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff81246838)
Location: fs/fcntl.c:247
Inline: True
Inline callers:
  - fs/fcntl.c:SyS_fcntl
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff81259828)
Location: fs/fcntl.c:247
Inline: True
Inline callers:
  - fs/fcntl.c:SyS_fcntl
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long int do_fcntl(int fd, unsigned int cmd, long unsigned int arg, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff81265a80)
Location: fs/fcntl.c:324
Inline: False
Direct callers:
  - fs/fcntl.c:compat_SyS_fcntl
  - fs/fcntl.c:SyS_fcntl
```
**Symbols:**

```
ffffffff81265a80-ffffffff81265fe4: do_fcntl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long int do_fcntl(int fd, unsigned int cmd, long unsigned int arg, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff81288360)
Location: fs/fcntl.c:325
Inline: False
Direct callers:
  - fs/fcntl.c:compat_SyS_fcntl
  - fs/fcntl.c:SyS_fcntl
```
**Symbols:**

```
ffffffff81288360-ffffffff812888c4: do_fcntl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long int do_fcntl(int fd, unsigned int cmd, long unsigned int arg, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff812ae800)
Location: fs/fcntl.c:325
Inline: False
Direct callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:__ia32_sys_fcntl
  - fs/fcntl.c:__x64_sys_fcntl
```
**Symbols:**

```
ffffffff812ae800-ffffffff812aed5d: do_fcntl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int do_fcntl(int fd, unsigned int cmd, long unsigned int arg, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff812c38f0)
Location: fs/fcntl.c:325
Inline: False
Direct callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:__ia32_sys_fcntl
  - fs/fcntl.c:__x64_sys_fcntl
```
**Symbols:**

```
ffffffff812c38f0-ffffffff812c3e4e: do_fcntl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
long int do_fcntl(int fd, unsigned int cmd, long unsigned int arg, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fcntl.c (0)
Location: fs/fcntl.c:325
Inline: False
Direct callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:__ia32_sys_fcntl
  - fs/fcntl.c:__x64_sys_fcntl
```
**Symbols:**

```
ffffffff812e0310-ffffffff812e085e: do_fcntl (STB_LOCAL)
ffffffff812e1316-ffffffff812e132e: do_fcntl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int do_fcntl(int fd, unsigned int cmd, long unsigned int arg, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff812f1db0)
Location: fs/fcntl.c:325
Inline: False
Direct callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:__ia32_sys_fcntl
  - fs/fcntl.c:__x64_sys_fcntl
```
**Symbols:**

```
ffffffff812f1db0-ffffffff812f230a: do_fcntl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int do_fcntl(int fd, unsigned int cmd, long unsigned int arg, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff8132a050)
Location: fs/fcntl.c:325
Inline: False
Direct callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:__ia32_sys_fcntl
  - fs/fcntl.c:__x64_sys_fcntl
```
**Symbols:**

```
ffffffff8132a050-ffffffff8132a521: do_fcntl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int do_fcntl(int fd, unsigned int cmd, long unsigned int arg, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff813355c0)
Location: fs/fcntl.c:325
Inline: False
Direct callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:__ia32_sys_fcntl
  - fs/fcntl.c:__x64_sys_fcntl
```
**Symbols:**

```
ffffffff813355c0-ffffffff81335a98: do_fcntl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int do_fcntl(int fd, unsigned int cmd, long unsigned int arg, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff8133b680)
Location: fs/fcntl.c:330
Inline: False
Direct callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:__ia32_sys_fcntl
  - fs/fcntl.c:__x64_sys_fcntl
```
**Symbols:**

```
ffffffff8133b680-ffffffff8133bc08: do_fcntl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int do_fcntl(int fd, unsigned int cmd, long unsigned int arg, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff813892f0)
Location: fs/fcntl.c:334
Inline: False
Direct callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:__ia32_sys_fcntl
  - fs/fcntl.c:__x64_sys_fcntl
```
**Symbols:**

```
ffffffff813892f0-ffffffff81389886: do_fcntl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int do_fcntl(int fd, unsigned int cmd, long unsigned int arg, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff8140a2a0)
Location: fs/fcntl.c:314
Inline: False
Direct callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:__ia32_sys_fcntl
  - fs/fcntl.c:__x64_sys_fcntl
```
**Symbols:**

```
ffffffff8140a2a0-ffffffff8140a8d5: do_fcntl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int do_fcntl(int fd, unsigned int cmd, long unsigned int arg, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff81494bf0)
Location: fs/fcntl.c:315
Inline: False
Direct callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:__ia32_sys_fcntl
  - fs/fcntl.c:__x64_sys_fcntl
```
**Symbols:**

```
ffffffff81494bf0-ffffffff8149512e: do_fcntl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int do_fcntl(int fd, unsigned int cmd, long unsigned int arg, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff814c9c40)
Location: fs/fcntl.c:316
Inline: False
Direct callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:__ia32_sys_fcntl
  - fs/fcntl.c:__x64_sys_fcntl
```
**Symbols:**

```
ffffffff814c9c40-ffffffff814ca176: do_fcntl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int do_fcntl(int fd, unsigned int cmd, long unsigned int arg, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff814fc500)
Location: fs/fcntl.c:316
Inline: False
Direct callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:__ia32_sys_fcntl
  - fs/fcntl.c:__x64_sys_fcntl
```
**Symbols:**

```
ffffffff814fc500-ffffffff814fca44: do_fcntl (STB_LOCAL)
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
long int do_fcntl(int fd, unsigned int cmd, long unsigned int arg, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffff80001039bc90)
Location: fs/fcntl.c:325
Inline: False
Direct callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:__arm64_sys_fcntl
```
**Symbols:**

```
ffff80001039bc90-ffff80001039c4c8: do_fcntl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int do_fcntl(int fd, unsigned int cmd, long unsigned int arg, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (c0581a44)
Location: fs/fcntl.c:325
Inline: False
Direct callers:
  - fs/fcntl.c:__se_sys_fcntl64
  - fs/fcntl.c:__se_sys_fcntl
```
**Symbols:**

```
c0581a44-c05821e4: do_fcntl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int do_fcntl(int fd, unsigned int cmd, long unsigned int arg, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (c000000000496940)
Location: fs/fcntl.c:325
Inline: False
Direct callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:__se_sys_fcntl
```
**Symbols:**

```
c000000000496940-c000000000497200: do_fcntl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffe000268a98)
Location: fs/fcntl.c:325
Inline: True
Inline callers:
  - fs/fcntl.c:__se_sys_fcntl
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
long int do_fcntl(int fd, unsigned int cmd, long unsigned int arg, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff812ea390)
Location: fs/fcntl.c:325
Inline: False
Direct callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:__ia32_sys_fcntl
  - fs/fcntl.c:__x64_sys_fcntl
```
**Symbols:**

```
ffffffff812ea390-ffffffff812ea8ea: do_fcntl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int do_fcntl(int fd, unsigned int cmd, long unsigned int arg, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff812dafd0)
Location: fs/fcntl.c:325
Inline: False
Direct callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:__ia32_sys_fcntl
  - fs/fcntl.c:__x64_sys_fcntl
```
**Symbols:**

```
ffffffff812dafd0-ffffffff812db52a: do_fcntl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int do_fcntl(int fd, unsigned int cmd, long unsigned int arg, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff812e81a0)
Location: fs/fcntl.c:325
Inline: False
Direct callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:__ia32_sys_fcntl
  - fs/fcntl.c:__x64_sys_fcntl
```
**Symbols:**

```
ffffffff812e81a0-ffffffff812e86fa: do_fcntl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int do_fcntl(int fd, unsigned int cmd, long unsigned int arg, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff812f9150)
Location: fs/fcntl.c:325
Inline: False
Direct callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:__ia32_sys_fcntl
  - fs/fcntl.c:__x64_sys_fcntl
```
**Symbols:**

```
ffffffff812f9150-ffffffff812f96c3: do_fcntl (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
