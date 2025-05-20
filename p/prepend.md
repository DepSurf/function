# Function: <code>prepend</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81222d18)
Location: fs/dcache.c:2822
Inline: True
Inline callers:
  - fs/dcache.c:simple_dname
  - fs/dcache.c:simple_dname
  - fs/dcache.c:simple_dname
  - fs/dcache.c:__dentry_path
  - fs/dcache.c:d_path
  - fs/dcache.c:d_path
  - fs/dcache.c:__d_path
  - fs/dcache.c:d_absolute_path
  - fs/dcache.c:dentry_path
  - fs/dcache.c:SyS_getcwd
  - fs/dcache.c:SyS_getcwd
```
```
In security/apparmor/path.c (ffffffff813797a9)
Location: security/apparmor/path.c:29
Inline: True
Inline callers:
  - security/apparmor/path.c:aa_path_name
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8124eace)
Location: fs/dcache.c:2989
Inline: True
Inline callers:
  - fs/dcache.c:SyS_getcwd
  - fs/dcache.c:SyS_getcwd
  - fs/dcache.c:dentry_path
  - fs/dcache.c:__dentry_path
  - fs/dcache.c:simple_dname
  - fs/dcache.c:simple_dname
  - fs/dcache.c:simple_dname
  - fs/dcache.c:d_path
  - fs/dcache.c:d_path
  - fs/dcache.c:d_absolute_path
  - fs/dcache.c:__d_path
```
```
In security/apparmor/path.c (ffffffff813b28aa)
Location: security/apparmor/path.c:29
Inline: True
Inline callers:
  - security/apparmor/path.c:aa_path_name
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81261ade)
Location: fs/dcache.c:2999
Inline: True
Inline callers:
  - fs/dcache.c:SyS_getcwd
  - fs/dcache.c:SyS_getcwd
  - fs/dcache.c:dentry_path
  - fs/dcache.c:__dentry_path
  - fs/dcache.c:simple_dname
  - fs/dcache.c:simple_dname
  - fs/dcache.c:simple_dname
  - fs/dcache.c:d_path
  - fs/dcache.c:d_path
  - fs/dcache.c:d_absolute_path
  - fs/dcache.c:__d_path
```
```
In security/apparmor/path.c (ffffffff813c9a6a)
Location: security/apparmor/path.c:29
Inline: True
Inline callers:
  - security/apparmor/path.c:aa_path_name
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision ⚠️</summary>

```c
int prepend(char **buffer, int *buflen, const char *str, int namelen);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8126ae80)
Location: fs/dcache.c:3029
Inline: False
Direct callers:
  - fs/dcache.c:SyS_getcwd
  - fs/dcache.c:SyS_getcwd
  - fs/dcache.c:dentry_path
  - fs/dcache.c:__dentry_path
  - fs/dcache.c:simple_dname
  - fs/dcache.c:simple_dname
  - fs/dcache.c:simple_dname
  - fs/dcache.c:d_path
  - fs/dcache.c:d_path
  - fs/dcache.c:d_absolute_path
  - fs/dcache.c:__d_path
```
```
In security/apparmor/path.c (ffffffff813ded70)
Location: security/apparmor/path.c:29
Inline: False
Direct callers:
  - security/apparmor/path.c:aa_path_name
```
**Symbols:**

```
ffffffff8126ae80-ffffffff8126aeae: prepend (STB_LOCAL)
ffffffff813ded70-ffffffff813ded9e: prepend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision ⚠️</summary>

```c
int prepend(char **buffer, int *buflen, const char *str, int namelen);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8128d700)
Location: fs/dcache.c:3041
Inline: False
Direct callers:
  - fs/dcache.c:SyS_getcwd
  - fs/dcache.c:SyS_getcwd
  - fs/dcache.c:dentry_path
  - fs/dcache.c:__dentry_path
  - fs/dcache.c:simple_dname
  - fs/dcache.c:simple_dname
  - fs/dcache.c:simple_dname
  - fs/dcache.c:d_path
  - fs/dcache.c:d_path
  - fs/dcache.c:d_absolute_path
  - fs/dcache.c:__d_path
```
```
In security/apparmor/path.c (ffffffff81405710)
Location: security/apparmor/path.c:29
Inline: False
Direct callers:
  - security/apparmor/path.c:aa_path_name
```
**Symbols:**

```
ffffffff8128d700-ffffffff8128d72e: prepend (STB_LOCAL)
ffffffff81405710-ffffffff8140573e: prepend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision ⚠️</summary>

```c
int prepend(char **buffer, int *buflen, const char *str, int namelen);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/d_path.c (ffffffff812d3640)
Location: fs/d_path.c:11
Inline: False
Direct callers:
  - fs/d_path.c:__ia32_sys_getcwd
  - fs/d_path.c:__ia32_sys_getcwd
  - fs/d_path.c:__x64_sys_getcwd
  - fs/d_path.c:__x64_sys_getcwd
  - fs/d_path.c:dentry_path
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:simple_dname
  - fs/d_path.c:simple_dname
  - fs/d_path.c:simple_dname
  - fs/d_path.c:d_path
  - fs/d_path.c:d_path
  - fs/d_path.c:d_absolute_path
  - fs/d_path.c:__d_path
```
```
In security/apparmor/path.c (ffffffff81436cc0)
Location: security/apparmor/path.c:29
Inline: False
Direct callers:
  - security/apparmor/path.c:aa_path_name
```
**Symbols:**

```
ffffffff812d3640-ffffffff812d366e: prepend (STB_LOCAL)
ffffffff81436cc0-ffffffff81436cee: prepend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision ⚠️</summary>

```c
int prepend(char **buffer, int *buflen, const char *str, int namelen);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/d_path.c (ffffffff812e8a10)
Location: fs/d_path.c:11
Inline: False
Direct callers:
  - fs/d_path.c:__ia32_sys_getcwd
  - fs/d_path.c:__ia32_sys_getcwd
  - fs/d_path.c:__x64_sys_getcwd
  - fs/d_path.c:__x64_sys_getcwd
  - fs/d_path.c:dentry_path
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:simple_dname
  - fs/d_path.c:simple_dname
  - fs/d_path.c:simple_dname
  - fs/d_path.c:d_path
  - fs/d_path.c:d_path
  - fs/d_path.c:d_absolute_path
  - fs/d_path.c:__d_path
```
```
In security/apparmor/path.c (ffffffff81453920)
Location: security/apparmor/path.c:29
Inline: False
Direct callers:
  - security/apparmor/path.c:aa_path_name
```
**Symbols:**

```
ffffffff812e8a10-ffffffff812e8a3e: prepend (STB_LOCAL)
ffffffff81453920-ffffffff8145394e: prepend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision ⚠️</summary>

```c
int prepend(char **buffer, int *buflen, const char *str, int namelen);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/d_path.c (ffffffff81307310)
Location: fs/d_path.c:11
Inline: False
Direct callers:
  - fs/d_path.c:__ia32_sys_getcwd
  - fs/d_path.c:__ia32_sys_getcwd
  - fs/d_path.c:__x64_sys_getcwd
  - fs/d_path.c:__x64_sys_getcwd
  - fs/d_path.c:dentry_path
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:simple_dname
  - fs/d_path.c:simple_dname
  - fs/d_path.c:simple_dname
  - fs/d_path.c:d_path
  - fs/d_path.c:d_path
  - fs/d_path.c:d_absolute_path
  - fs/d_path.c:__d_path
```
```
In security/apparmor/path.c (ffffffff81481290)
Location: security/apparmor/path.c:25
Inline: False
```
**Symbols:**

```
ffffffff81307310-ffffffff81307341: prepend (STB_LOCAL)
ffffffff81481290-ffffffff814812be: prepend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision ⚠️</summary>

```c
int prepend(char **buffer, int *buflen, const char *str, int namelen);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/d_path.c (ffffffff8131a370)
Location: fs/d_path.c:11
Inline: False
Direct callers:
  - fs/d_path.c:__ia32_sys_getcwd
  - fs/d_path.c:__ia32_sys_getcwd
  - fs/d_path.c:__x64_sys_getcwd
  - fs/d_path.c:__x64_sys_getcwd
  - fs/d_path.c:dentry_path
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:simple_dname
  - fs/d_path.c:simple_dname
  - fs/d_path.c:simple_dname
  - fs/d_path.c:d_path
  - fs/d_path.c:d_path
  - fs/d_path.c:d_absolute_path
  - fs/d_path.c:__d_path
```
```
In security/apparmor/path.c (ffffffff8149afc0)
Location: security/apparmor/path.c:25
Inline: False
```
**Symbols:**

```
ffffffff8131a370-ffffffff8131a3a1: prepend (STB_LOCAL)
ffffffff8149afc0-ffffffff8149afee: prepend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision, Selective Inline ⚠️</summary>

```c
int prepend(char **buffer, int *buflen, const char *str, int namelen);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/d_path.c (ffffffff813547cc)
Location: fs/d_path.c:11
Inline: True
Inline callers:
  - fs/d_path.c:__do_sys_getcwd
  - fs/d_path.c:__do_sys_getcwd
  - fs/d_path.c:dentry_path
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:simple_dname
  - fs/d_path.c:simple_dname
  - fs/d_path.c:d_path
  - fs/d_path.c:d_path
  - fs/d_path.c:d_absolute_path
  - fs/d_path.c:__d_path
Direct callers:
  - fs/d_path.c:simple_dname
```
```
In security/apparmor/path.c (ffffffff814f39c0)
Location: security/apparmor/path.c:25
Inline: True
```
**Symbols:**

```
ffffffff813542b0-ffffffff813542e1: prepend (STB_LOCAL)
ffffffff814f39c0-ffffffff814f39ee: prepend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision, Selective Inline ⚠️</summary>

```c
int prepend(char **buffer, int *buflen, const char *str, int namelen);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/d_path.c (ffffffff813610da)
Location: fs/d_path.c:11
Inline: True
Inline callers:
  - fs/d_path.c:__do_sys_getcwd
  - fs/d_path.c:__do_sys_getcwd
  - fs/d_path.c:dentry_path
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:simple_dname
  - fs/d_path.c:simple_dname
  - fs/d_path.c:d_path
  - fs/d_path.c:d_path
  - fs/d_path.c:d_absolute_path
  - fs/d_path.c:__d_path
Direct callers:
  - fs/d_path.c:simple_dname
```
```
In security/apparmor/path.c (ffffffff81510b20)
Location: security/apparmor/path.c:25
Inline: True
```
**Symbols:**

```
ffffffff81360ba0-ffffffff81360bd1: prepend (STB_LOCAL)
ffffffff81510b20-ffffffff81510b4e: prepend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Selective Inline ⚠️</summary>

```c
int prepend(char **buffer, int *buflen, const char *str, int namelen);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/d_path.c (ffffffff81367bba)
Location: fs/d_path.c:11
Inline: True
Inline callers:
  - fs/d_path.c:__do_sys_getcwd
  - fs/d_path.c:__do_sys_getcwd
  - fs/d_path.c:dentry_path
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:simple_dname
  - fs/d_path.c:simple_dname
  - fs/d_path.c:d_path
  - fs/d_path.c:d_path
  - fs/d_path.c:d_absolute_path
  - fs/d_path.c:__d_path
Direct callers:
  - fs/d_path.c:simple_dname
```
```
In security/apparmor/path.c (ffffffff815174d0)
Location: security/apparmor/path.c:25
Inline: True
```
**Symbols:**

```
ffffffff813676a0-ffffffff813676ce: prepend (STB_LOCAL)
ffffffff815174d0-ffffffff815174fe: prepend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Selective Inline ⚠️</summary>

```c
bool prepend(struct prepend_buffer *p, const char *str, int namelen);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/d_path.c (ffffffff813b6965)
Location: fs/d_path.c:56
Inline: True
Inline callers:
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:simple_dname
Direct callers:
  - fs/d_path.c:__do_sys_getcwd
  - fs/d_path.c:dentry_path
  - fs/d_path.c:simple_dname
  - fs/d_path.c:d_path
  - fs/d_path.c:prepend_path
```
```
In security/apparmor/path.c (ffffffff815754d0)
Location: security/apparmor/path.c:25
Inline: True
```
**Symbols:**

```
ffffffff813b61e0-ffffffff813b624c: prepend (STB_LOCAL)
ffffffff815754d0-ffffffff815754fe: prepend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Selective Inline ⚠️</summary>

```c
bool prepend(struct prepend_buffer *p, const char *str, int namelen);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/d_path.c (ffffffff8143bf27)
Location: fs/d_path.c:56
Inline: True
Inline callers:
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:simple_dname
Direct callers:
  - fs/d_path.c:__do_sys_getcwd
  - fs/d_path.c:dentry_path
  - fs/d_path.c:simple_dname
  - fs/d_path.c:d_path
  - fs/d_path.c:prepend_path
```
```
In security/apparmor/path.c (ffffffff81612fb0)
Location: security/apparmor/path.c:25
Inline: False
Direct callers:
  - security/apparmor/path.c:disconnect
  - security/apparmor/path.c:disconnect
```
**Symbols:**

```
ffffffff8143b790-ffffffff8143b812: prepend (STB_LOCAL)
ffffffff81612fb0-ffffffff81612ff6: prepend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision, Selective Inline ⚠️</summary>

```c
bool prepend(struct prepend_buffer *p, const char *str, int namelen);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/d_path.c (ffffffff814ca587)
Location: fs/d_path.c:56
Inline: True
Inline callers:
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:simple_dname
Direct callers:
  - fs/d_path.c:__do_sys_getcwd
  - fs/d_path.c:dentry_path
  - fs/d_path.c:simple_dname
  - fs/d_path.c:d_path
  - fs/d_path.c:prepend_path
```
```
In security/apparmor/path.c (ffffffff816c5be0)
Location: security/apparmor/path.c:25
Inline: False
Direct callers:
  - security/apparmor/path.c:disconnect
  - security/apparmor/path.c:disconnect
```
**Symbols:**

```
ffffffff814c9d90-ffffffff814c9e12: prepend (STB_LOCAL)
ffffffff816c5be0-ffffffff816c5c26: prepend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision, Selective Inline ⚠️</summary>

```c
bool prepend(struct prepend_buffer *p, const char *str, int namelen);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/d_path.c (ffffffff815007c5)
Location: fs/d_path.c:57
Inline: True
Inline callers:
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:simple_dname
Direct callers:
  - fs/d_path.c:__do_sys_getcwd
  - fs/d_path.c:dentry_path
  - fs/d_path.c:simple_dname
  - fs/d_path.c:d_path
  - fs/d_path.c:prepend_path
```
```
In security/apparmor/path.c (ffffffff816fe9c0)
Location: security/apparmor/path.c:25
Inline: False
Direct callers:
  - security/apparmor/path.c:disconnect
  - security/apparmor/path.c:disconnect
```
**Symbols:**

```
ffffffff814fffd0-ffffffff81500052: prepend (STB_LOCAL)
ffffffff816fe9c0-ffffffff816fea06: prepend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision, Selective Inline ⚠️</summary>

```c
bool prepend(struct prepend_buffer *p, const char *str, int namelen);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/d_path.c (ffffffff815353e5)
Location: fs/d_path.c:57
Inline: True
Inline callers:
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:simple_dname
Direct callers:
  - fs/d_path.c:__do_sys_getcwd
  - fs/d_path.c:dentry_path
  - fs/d_path.c:simple_dname
  - fs/d_path.c:d_path
  - fs/d_path.c:prepend_path
```
```
In security/apparmor/path.c (ffffffff8173bf50)
Location: security/apparmor/path.c:25
Inline: False
Direct callers:
  - security/apparmor/path.c:disconnect
  - security/apparmor/path.c:disconnect
```
**Symbols:**

```
ffffffff81534bf0-ffffffff81534c72: prepend (STB_LOCAL)
ffffffff8173bf50-ffffffff8173bf96: prepend (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Collision ⚠️</summary>

```c
int prepend(char **buffer, int *buflen, const char *str, int namelen);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/d_path.c (ffff8000103d1608)
Location: fs/d_path.c:11
Inline: False
Direct callers:
  - fs/d_path.c:__arm64_sys_getcwd
  - fs/d_path.c:__arm64_sys_getcwd
  - fs/d_path.c:dentry_path
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:simple_dname
  - fs/d_path.c:simple_dname
  - fs/d_path.c:simple_dname
  - fs/d_path.c:d_path
  - fs/d_path.c:d_path
  - fs/d_path.c:d_absolute_path
  - fs/d_path.c:__d_path
```
```
In security/apparmor/path.c (ffff800010591210)
Location: security/apparmor/path.c:25
Inline: False
```
**Symbols:**

```
ffff8000103d1608-ffff8000103d1674: prepend (STB_LOCAL)
ffff800010591210-ffff800010591274: prepend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision ⚠️</summary>

```c
int prepend(char **buffer, int *buflen, const char *str, int namelen);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/d_path.c (c05ac364)
Location: fs/d_path.c:11
Inline: False
Direct callers:
  - fs/d_path.c:__se_sys_getcwd
  - fs/d_path.c:__se_sys_getcwd
  - fs/d_path.c:dentry_path
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:simple_dname
  - fs/d_path.c:simple_dname
  - fs/d_path.c:simple_dname
  - fs/d_path.c:d_path
  - fs/d_path.c:d_path
  - fs/d_path.c:d_absolute_path
  - fs/d_path.c:__d_path
```
```
In security/apparmor/path.c (c0741ec4)
Location: security/apparmor/path.c:25
Inline: False
```
**Symbols:**

```
c05ac364-c05ac3bc: prepend (STB_LOCAL)
c0741ec4-c0741f10: prepend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Collision ⚠️</summary>

```c
int prepend(char **buffer, int *buflen, const char *str, int namelen);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/d_path.c (c0000000004d3fe0)
Location: fs/d_path.c:11
Inline: False
Direct callers:
  - fs/d_path.c:__se_sys_getcwd
  - fs/d_path.c:__se_sys_getcwd
  - fs/d_path.c:dentry_path
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:simple_dname
  - fs/d_path.c:simple_dname
  - fs/d_path.c:simple_dname
  - fs/d_path.c:d_path
  - fs/d_path.c:d_path
  - fs/d_path.c:d_absolute_path
  - fs/d_path.c:__d_path
```
```
In security/apparmor/path.c (c000000000704cf0)
Location: security/apparmor/path.c:25
Inline: False
```
**Symbols:**

```
c0000000004d3fe0-c0000000004d404c: prepend (STB_LOCAL)
c000000000704cf0-c000000000704d54: prepend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/d_path.c (ffffffe00028d73e)
Location: fs/d_path.c:11
Inline: True
Inline callers:
  - fs/d_path.c:__se_sys_getcwd
  - fs/d_path.c:__se_sys_getcwd
  - fs/d_path.c:dentry_path
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:simple_dname
  - fs/d_path.c:simple_dname
  - fs/d_path.c:simple_dname
  - fs/d_path.c:d_path
  - fs/d_path.c:d_path
  - fs/d_path.c:d_absolute_path
  - fs/d_path.c:__d_path
```
```
In security/apparmor/path.c (ffffffe0003decde)
Location: security/apparmor/path.c:25
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Collision ⚠️</summary>

```c
int prepend(char **buffer, int *buflen, const char *str, int namelen);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/d_path.c (ffffffff81312950)
Location: fs/d_path.c:11
Inline: False
Direct callers:
  - fs/d_path.c:__ia32_sys_getcwd
  - fs/d_path.c:__ia32_sys_getcwd
  - fs/d_path.c:__x64_sys_getcwd
  - fs/d_path.c:__x64_sys_getcwd
  - fs/d_path.c:dentry_path
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:simple_dname
  - fs/d_path.c:simple_dname
  - fs/d_path.c:simple_dname
  - fs/d_path.c:d_path
  - fs/d_path.c:d_path
  - fs/d_path.c:d_absolute_path
  - fs/d_path.c:__d_path
```
```
In security/apparmor/path.c (ffffffff814935a0)
Location: security/apparmor/path.c:25
Inline: False
```
**Symbols:**

```
ffffffff81312950-ffffffff81312981: prepend (STB_LOCAL)
ffffffff814935a0-ffffffff814935ce: prepend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision ⚠️</summary>

```c
int prepend(char **buffer, int *buflen, const char *str, int namelen);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/d_path.c (ffffffff81303560)
Location: fs/d_path.c:11
Inline: False
Direct callers:
  - fs/d_path.c:__ia32_sys_getcwd
  - fs/d_path.c:__ia32_sys_getcwd
  - fs/d_path.c:__x64_sys_getcwd
  - fs/d_path.c:__x64_sys_getcwd
  - fs/d_path.c:dentry_path
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:simple_dname
  - fs/d_path.c:simple_dname
  - fs/d_path.c:simple_dname
  - fs/d_path.c:d_path
  - fs/d_path.c:d_path
  - fs/d_path.c:d_absolute_path
  - fs/d_path.c:__d_path
```
```
In security/apparmor/path.c (ffffffff81483fc0)
Location: security/apparmor/path.c:25
Inline: False
```
**Symbols:**

```
ffffffff81303560-ffffffff81303591: prepend (STB_LOCAL)
ffffffff81483fc0-ffffffff81483fee: prepend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision ⚠️</summary>

```c
int prepend(char **buffer, int *buflen, const char *str, int namelen);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/d_path.c (ffffffff81310740)
Location: fs/d_path.c:11
Inline: False
Direct callers:
  - fs/d_path.c:__ia32_sys_getcwd
  - fs/d_path.c:__ia32_sys_getcwd
  - fs/d_path.c:__x64_sys_getcwd
  - fs/d_path.c:__x64_sys_getcwd
  - fs/d_path.c:dentry_path
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:simple_dname
  - fs/d_path.c:simple_dname
  - fs/d_path.c:simple_dname
  - fs/d_path.c:d_path
  - fs/d_path.c:d_path
  - fs/d_path.c:d_absolute_path
  - fs/d_path.c:__d_path
```
```
In security/apparmor/path.c (ffffffff8148f640)
Location: security/apparmor/path.c:25
Inline: False
```
**Symbols:**

```
ffffffff81310740-ffffffff81310771: prepend (STB_LOCAL)
ffffffff8148f640-ffffffff8148f66e: prepend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision ⚠️</summary>

```c
int prepend(char **buffer, int *buflen, const char *str, int namelen);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/d_path.c (ffffffff81321f40)
Location: fs/d_path.c:11
Inline: False
Direct callers:
  - fs/d_path.c:__ia32_sys_getcwd
  - fs/d_path.c:__ia32_sys_getcwd
  - fs/d_path.c:__x64_sys_getcwd
  - fs/d_path.c:__x64_sys_getcwd
  - fs/d_path.c:dentry_path
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:simple_dname
  - fs/d_path.c:simple_dname
  - fs/d_path.c:simple_dname
  - fs/d_path.c:d_path
  - fs/d_path.c:d_path
  - fs/d_path.c:d_absolute_path
  - fs/d_path.c:__d_path
```
```
In security/apparmor/path.c (ffffffff814a7550)
Location: security/apparmor/path.c:25
Inline: False
```
**Symbols:**

```
ffffffff81321f40-ffffffff81321f71: prepend (STB_LOCAL)
ffffffff814a7550-ffffffff814a757e: prepend (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct prepend_buffer *p</code>
</li>
<li>
<b>Param removed. </b>
<code>char **buffer</code>
</li>
<li>
<b>Param removed. </b>
<code>int *buflen</code>
</li>
<li>
<b>Param reordered. </b>
<code>buffer, buflen, str, namelen</code> ➡️ <code>p, str, namelen</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>bool</code>
</li>
</ul>
</details>
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
