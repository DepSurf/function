# Function: <code>do_sendfile</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
ssize_t do_sendfile(int out_fd, int in_fd, loff_t *ppos, size_t count, loff_t max);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff8120d0d0)
Location: fs/read_write.c:1179
Inline: False
Direct callers:
  - fs/read_write.c:SyS_sendfile
  - fs/read_write.c:SyS_sendfile
  - fs/read_write.c:SyS_sendfile64
  - fs/read_write.c:SyS_sendfile64
  - fs/read_write.c:compat_SyS_sendfile
  - fs/read_write.c:compat_SyS_sendfile
  - fs/read_write.c:compat_SyS_sendfile64
  - fs/read_write.c:compat_SyS_sendfile64
```
**Symbols:**

```
ffffffff8120d0d0-ffffffff8120d470: do_sendfile (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
ssize_t do_sendfile(int out_fd, int in_fd, loff_t *ppos, size_t count, loff_t max);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81233a20)
Location: fs/read_write.c:1324
Inline: False
Direct callers:
  - fs/read_write.c:compat_SyS_sendfile64
  - fs/read_write.c:compat_SyS_sendfile64
  - fs/read_write.c:compat_SyS_sendfile
  - fs/read_write.c:compat_SyS_sendfile
  - fs/read_write.c:SyS_sendfile64
  - fs/read_write.c:SyS_sendfile64
  - fs/read_write.c:SyS_sendfile
  - fs/read_write.c:SyS_sendfile
```
**Symbols:**

```
ffffffff81233a20-ffffffff81233dbf: do_sendfile (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
ssize_t do_sendfile(int out_fd, int in_fd, loff_t *ppos, size_t count, loff_t max);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812465b0)
Location: fs/read_write.c:1353
Inline: False
Direct callers:
  - fs/read_write.c:compat_SyS_sendfile64
  - fs/read_write.c:compat_SyS_sendfile64
  - fs/read_write.c:compat_SyS_sendfile
  - fs/read_write.c:compat_SyS_sendfile
  - fs/read_write.c:SyS_sendfile64
  - fs/read_write.c:SyS_sendfile64
  - fs/read_write.c:SyS_sendfile
  - fs/read_write.c:SyS_sendfile
```
**Symbols:**

```
ffffffff812465b0-ffffffff8124694f: do_sendfile (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ssize_t do_sendfile(int out_fd, int in_fd, loff_t *ppos, size_t count, loff_t max);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81251bd0)
Location: fs/read_write.c:1364
Inline: False
Direct callers:
  - fs/read_write.c:compat_SyS_sendfile64
  - fs/read_write.c:compat_SyS_sendfile64
  - fs/read_write.c:compat_SyS_sendfile
  - fs/read_write.c:compat_SyS_sendfile
  - fs/read_write.c:SyS_sendfile64
  - fs/read_write.c:SyS_sendfile64
  - fs/read_write.c:SyS_sendfile
  - fs/read_write.c:SyS_sendfile
```
**Symbols:**

```
ffffffff81251bd0-ffffffff81251f6f: do_sendfile (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t do_sendfile(int out_fd, int in_fd, loff_t *ppos, size_t count, loff_t max);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81273540)
Location: fs/read_write.c:1367
Inline: False
Direct callers:
  - fs/read_write.c:compat_SyS_sendfile64
  - fs/read_write.c:compat_SyS_sendfile64
  - fs/read_write.c:compat_SyS_sendfile
  - fs/read_write.c:compat_SyS_sendfile
  - fs/read_write.c:SyS_sendfile64
  - fs/read_write.c:SyS_sendfile64
  - fs/read_write.c:SyS_sendfile
  - fs/read_write.c:SyS_sendfile
```
**Symbols:**

```
ffffffff81273540-ffffffff812738df: do_sendfile (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
ssize_t do_sendfile(int out_fd, int in_fd, loff_t *ppos, size_t count, loff_t max);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812998c0)
Location: fs/read_write.c:1394
Inline: False
Direct callers:
  - fs/read_write.c:__x32_compat_sys_sendfile64
  - fs/read_write.c:__x32_compat_sys_sendfile64
  - fs/read_write.c:__ia32_compat_sys_sendfile64
  - fs/read_write.c:__ia32_compat_sys_sendfile64
  - fs/read_write.c:__x32_compat_sys_sendfile
  - fs/read_write.c:__x32_compat_sys_sendfile
  - fs/read_write.c:__ia32_compat_sys_sendfile
  - fs/read_write.c:__ia32_compat_sys_sendfile
  - fs/read_write.c:__ia32_sys_sendfile64
  - fs/read_write.c:__ia32_sys_sendfile64
  - fs/read_write.c:__x64_sys_sendfile64
  - fs/read_write.c:__x64_sys_sendfile64
  - fs/read_write.c:__ia32_sys_sendfile
  - fs/read_write.c:__ia32_sys_sendfile
  - fs/read_write.c:__x64_sys_sendfile
  - fs/read_write.c:__x64_sys_sendfile
```
**Symbols:**

```
ffffffff812998c0-ffffffff81299c71: do_sendfile (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ssize_t do_sendfile(int out_fd, int in_fd, loff_t *ppos, size_t count, loff_t max);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812ae740)
Location: fs/read_write.c:1391
Inline: False
Direct callers:
  - fs/read_write.c:__x32_compat_sys_sendfile64
  - fs/read_write.c:__x32_compat_sys_sendfile64
  - fs/read_write.c:__ia32_compat_sys_sendfile64
  - fs/read_write.c:__ia32_compat_sys_sendfile64
  - fs/read_write.c:__x32_compat_sys_sendfile
  - fs/read_write.c:__x32_compat_sys_sendfile
  - fs/read_write.c:__ia32_compat_sys_sendfile
  - fs/read_write.c:__ia32_compat_sys_sendfile
  - fs/read_write.c:__ia32_sys_sendfile64
  - fs/read_write.c:__ia32_sys_sendfile64
  - fs/read_write.c:__x64_sys_sendfile64
  - fs/read_write.c:__x64_sys_sendfile64
  - fs/read_write.c:__ia32_sys_sendfile
  - fs/read_write.c:__ia32_sys_sendfile
  - fs/read_write.c:__x64_sys_sendfile
  - fs/read_write.c:__x64_sys_sendfile
```
**Symbols:**

```
ffffffff812ae740-ffffffff812aeb0b: do_sendfile (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
ssize_t do_sendfile(int out_fd, int in_fd, loff_t *ppos, size_t count, loff_t max);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812cb3e0)
Location: fs/read_write.c:1419
Inline: False
Direct callers:
  - fs/read_write.c:__x32_compat_sys_sendfile64
  - fs/read_write.c:__x32_compat_sys_sendfile64
  - fs/read_write.c:__ia32_compat_sys_sendfile64
  - fs/read_write.c:__ia32_compat_sys_sendfile64
  - fs/read_write.c:__x32_compat_sys_sendfile
  - fs/read_write.c:__x32_compat_sys_sendfile
  - fs/read_write.c:__ia32_compat_sys_sendfile
  - fs/read_write.c:__ia32_compat_sys_sendfile
  - fs/read_write.c:__ia32_sys_sendfile64
  - fs/read_write.c:__ia32_sys_sendfile64
  - fs/read_write.c:__x64_sys_sendfile64
  - fs/read_write.c:__x64_sys_sendfile64
  - fs/read_write.c:__ia32_sys_sendfile
  - fs/read_write.c:__ia32_sys_sendfile
  - fs/read_write.c:__x64_sys_sendfile
  - fs/read_write.c:__x64_sys_sendfile
```
**Symbols:**

```
ffffffff812cb3e0-ffffffff812cb7c0: do_sendfile (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ssize_t do_sendfile(int out_fd, int in_fd, loff_t *ppos, size_t count, loff_t max);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812dce00)
Location: fs/read_write.c:1419
Inline: False
Direct callers:
  - fs/read_write.c:__x32_compat_sys_sendfile64
  - fs/read_write.c:__x32_compat_sys_sendfile64
  - fs/read_write.c:__ia32_compat_sys_sendfile64
  - fs/read_write.c:__ia32_compat_sys_sendfile64
  - fs/read_write.c:__x32_compat_sys_sendfile
  - fs/read_write.c:__x32_compat_sys_sendfile
  - fs/read_write.c:__ia32_compat_sys_sendfile
  - fs/read_write.c:__ia32_compat_sys_sendfile
  - fs/read_write.c:__ia32_sys_sendfile64
  - fs/read_write.c:__ia32_sys_sendfile64
  - fs/read_write.c:__x64_sys_sendfile64
  - fs/read_write.c:__x64_sys_sendfile64
  - fs/read_write.c:__ia32_sys_sendfile
  - fs/read_write.c:__ia32_sys_sendfile
  - fs/read_write.c:__x64_sys_sendfile
  - fs/read_write.c:__x64_sys_sendfile
```
**Symbols:**

```
ffffffff812dce00-ffffffff812dd1e0: do_sendfile (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t do_sendfile(int out_fd, int in_fd, loff_t *ppos, size_t count, loff_t max);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81313df0)
Location: fs/read_write.c:1503
Inline: False
Direct callers:
  - fs/read_write.c:__x32_compat_sys_sendfile64
  - fs/read_write.c:__x32_compat_sys_sendfile64
  - fs/read_write.c:__ia32_compat_sys_sendfile64
  - fs/read_write.c:__ia32_compat_sys_sendfile64
  - fs/read_write.c:__x32_compat_sys_sendfile
  - fs/read_write.c:__x32_compat_sys_sendfile
  - fs/read_write.c:__ia32_compat_sys_sendfile
  - fs/read_write.c:__ia32_compat_sys_sendfile
  - fs/read_write.c:__ia32_sys_sendfile64
  - fs/read_write.c:__ia32_sys_sendfile64
  - fs/read_write.c:__x64_sys_sendfile64
  - fs/read_write.c:__x64_sys_sendfile64
  - fs/read_write.c:__ia32_sys_sendfile
  - fs/read_write.c:__ia32_sys_sendfile
  - fs/read_write.c:__x64_sys_sendfile
  - fs/read_write.c:__x64_sys_sendfile
```
**Symbols:**

```
ffffffff81313df0-ffffffff813141b8: do_sendfile (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t do_sendfile(int out_fd, int in_fd, loff_t *ppos, size_t count, loff_t max);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff8131f4e0)
Location: fs/read_write.c:1188
Inline: False
Direct callers:
  - fs/read_write.c:__x32_compat_sys_sendfile64
  - fs/read_write.c:__x32_compat_sys_sendfile64
  - fs/read_write.c:__ia32_compat_sys_sendfile64
  - fs/read_write.c:__ia32_compat_sys_sendfile64
  - fs/read_write.c:__x32_compat_sys_sendfile
  - fs/read_write.c:__x32_compat_sys_sendfile
  - fs/read_write.c:__ia32_compat_sys_sendfile
  - fs/read_write.c:__ia32_compat_sys_sendfile
  - fs/read_write.c:__ia32_sys_sendfile64
  - fs/read_write.c:__ia32_sys_sendfile64
  - fs/read_write.c:__x64_sys_sendfile64
  - fs/read_write.c:__x64_sys_sendfile64
  - fs/read_write.c:__ia32_sys_sendfile
  - fs/read_write.c:__ia32_sys_sendfile
  - fs/read_write.c:__x64_sys_sendfile
  - fs/read_write.c:__x64_sys_sendfile
```
**Symbols:**

```
ffffffff8131f4e0-ffffffff8131f94c: do_sendfile (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t do_sendfile(int out_fd, int in_fd, loff_t *ppos, size_t count, loff_t max);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81324f10)
Location: fs/read_write.c:1186
Inline: False
Direct callers:
  - fs/read_write.c:__x32_compat_sys_sendfile64
  - fs/read_write.c:__x32_compat_sys_sendfile64
  - fs/read_write.c:__ia32_compat_sys_sendfile64
  - fs/read_write.c:__ia32_compat_sys_sendfile64
  - fs/read_write.c:__x32_compat_sys_sendfile
  - fs/read_write.c:__x32_compat_sys_sendfile
  - fs/read_write.c:__ia32_compat_sys_sendfile
  - fs/read_write.c:__ia32_compat_sys_sendfile
  - fs/read_write.c:__ia32_sys_sendfile64
  - fs/read_write.c:__ia32_sys_sendfile64
  - fs/read_write.c:__x64_sys_sendfile64
  - fs/read_write.c:__x64_sys_sendfile64
  - fs/read_write.c:__ia32_sys_sendfile
  - fs/read_write.c:__ia32_sys_sendfile
  - fs/read_write.c:__x64_sys_sendfile
  - fs/read_write.c:__x64_sys_sendfile
```
**Symbols:**

```
ffffffff81324f10-ffffffff8132534f: do_sendfile (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
ssize_t do_sendfile(int out_fd, int in_fd, loff_t *ppos, size_t count, loff_t max);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81372b50)
Location: fs/read_write.c:1177
Inline: False
Direct callers:
  - fs/read_write.c:__x64_compat_sys_sendfile64
  - fs/read_write.c:__x64_compat_sys_sendfile64
  - fs/read_write.c:__ia32_compat_sys_sendfile64
  - fs/read_write.c:__ia32_compat_sys_sendfile64
  - fs/read_write.c:__x64_compat_sys_sendfile
  - fs/read_write.c:__x64_compat_sys_sendfile
  - fs/read_write.c:__ia32_compat_sys_sendfile
  - fs/read_write.c:__ia32_compat_sys_sendfile
  - fs/read_write.c:__ia32_sys_sendfile64
  - fs/read_write.c:__ia32_sys_sendfile64
  - fs/read_write.c:__x64_sys_sendfile64
  - fs/read_write.c:__x64_sys_sendfile64
  - fs/read_write.c:__ia32_sys_sendfile
  - fs/read_write.c:__ia32_sys_sendfile
  - fs/read_write.c:__x64_sys_sendfile
  - fs/read_write.c:__x64_sys_sendfile
```
**Symbols:**

```
ffffffff81372b50-ffffffff81372fb3: do_sendfile (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ssize_t do_sendfile(int out_fd, int in_fd, loff_t *ppos, size_t count, loff_t max);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff813f1160)
Location: fs/read_write.c:1188
Inline: False
Direct callers:
  - fs/read_write.c:__ia32_compat_sys_sendfile64
  - fs/read_write.c:__ia32_compat_sys_sendfile64
  - fs/read_write.c:__ia32_compat_sys_sendfile
  - fs/read_write.c:__ia32_compat_sys_sendfile
  - fs/read_write.c:__ia32_sys_sendfile64
  - fs/read_write.c:__ia32_sys_sendfile64
  - fs/read_write.c:__x64_sys_sendfile64
  - fs/read_write.c:__x64_sys_sendfile64
  - fs/read_write.c:__ia32_sys_sendfile
  - fs/read_write.c:__ia32_sys_sendfile
  - fs/read_write.c:__x64_sys_sendfile
  - fs/read_write.c:__x64_sys_sendfile
```
**Symbols:**

```
ffffffff813f1160-ffffffff813f1669: do_sendfile (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t do_sendfile(int out_fd, int in_fd, loff_t *ppos, size_t count, loff_t max);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81479470)
Location: fs/read_write.c:1181
Inline: False
Direct callers:
  - fs/read_write.c:__ia32_compat_sys_sendfile64
  - fs/read_write.c:__ia32_compat_sys_sendfile64
  - fs/read_write.c:__ia32_compat_sys_sendfile
  - fs/read_write.c:__ia32_compat_sys_sendfile
  - fs/read_write.c:__ia32_sys_sendfile64
  - fs/read_write.c:__ia32_sys_sendfile64
  - fs/read_write.c:__x64_sys_sendfile64
  - fs/read_write.c:__x64_sys_sendfile64
  - fs/read_write.c:__ia32_sys_sendfile
  - fs/read_write.c:__ia32_sys_sendfile
  - fs/read_write.c:__x64_sys_sendfile
  - fs/read_write.c:__x64_sys_sendfile
```
**Symbols:**

```
ffffffff81479470-ffffffff81479979: do_sendfile (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t do_sendfile(int out_fd, int in_fd, loff_t *ppos, size_t count, loff_t max);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff814aded0)
Location: fs/read_write.c:1180
Inline: False
Direct callers:
  - fs/read_write.c:__ia32_compat_sys_sendfile64
  - fs/read_write.c:__ia32_compat_sys_sendfile64
  - fs/read_write.c:__ia32_compat_sys_sendfile
  - fs/read_write.c:__ia32_compat_sys_sendfile
  - fs/read_write.c:__ia32_sys_sendfile64
  - fs/read_write.c:__ia32_sys_sendfile64
  - fs/read_write.c:__x64_sys_sendfile64
  - fs/read_write.c:__x64_sys_sendfile64
  - fs/read_write.c:__ia32_sys_sendfile
  - fs/read_write.c:__ia32_sys_sendfile
  - fs/read_write.c:__x64_sys_sendfile
  - fs/read_write.c:__x64_sys_sendfile
```
**Symbols:**

```
ffffffff814aded0-ffffffff814ae44e: do_sendfile (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t do_sendfile(int out_fd, int in_fd, loff_t *ppos, size_t count, loff_t max);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff814df750)
Location: fs/read_write.c:1222
Inline: False
Direct callers:
  - fs/read_write.c:__ia32_compat_sys_sendfile64
  - fs/read_write.c:__ia32_compat_sys_sendfile64
  - fs/read_write.c:__ia32_compat_sys_sendfile
  - fs/read_write.c:__ia32_compat_sys_sendfile
  - fs/read_write.c:__ia32_sys_sendfile64
  - fs/read_write.c:__ia32_sys_sendfile64
  - fs/read_write.c:__x64_sys_sendfile64
  - fs/read_write.c:__x64_sys_sendfile64
  - fs/read_write.c:__ia32_sys_sendfile
  - fs/read_write.c:__ia32_sys_sendfile
  - fs/read_write.c:__x64_sys_sendfile
  - fs/read_write.c:__x64_sys_sendfile
```
**Symbols:**

```
ffffffff814df750-ffffffff814dfb6d: do_sendfile (STB_LOCAL)
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
ssize_t do_sendfile(int out_fd, int in_fd, loff_t *ppos, size_t count, loff_t max);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffff800010382750)
Location: fs/read_write.c:1419
Inline: False
Direct callers:
  - fs/read_write.c:__arm64_compat_sys_sendfile64
  - fs/read_write.c:__arm64_compat_sys_sendfile64
  - fs/read_write.c:__arm64_compat_sys_sendfile
  - fs/read_write.c:__arm64_compat_sys_sendfile
  - fs/read_write.c:__arm64_sys_sendfile64
  - fs/read_write.c:__arm64_sys_sendfile64
  - fs/read_write.c:__arm64_sys_sendfile
  - fs/read_write.c:__arm64_sys_sendfile
```
**Symbols:**

```
ffff800010382750-ffff800010382ab8: do_sendfile (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t do_sendfile(int out_fd, int in_fd, loff_t *ppos, size_t count, loff_t max);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (c056c708)
Location: fs/read_write.c:1419
Inline: False
Direct callers:
  - fs/read_write.c:__se_sys_sendfile64
  - fs/read_write.c:__se_sys_sendfile64
  - fs/read_write.c:__se_sys_sendfile
  - fs/read_write.c:__se_sys_sendfile
```
**Symbols:**

```
c056c708-c056cb04: do_sendfile (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t do_sendfile(int out_fd, int in_fd, loff_t *ppos, size_t count, loff_t max);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (c000000000478ec0)
Location: fs/read_write.c:1419
Inline: False
Direct callers:
  - fs/read_write.c:__se_compat_sys_sendfile64
  - fs/read_write.c:__se_compat_sys_sendfile64
  - fs/read_write.c:__se_compat_sys_sendfile
  - fs/read_write.c:__se_compat_sys_sendfile
  - fs/read_write.c:__se_sys_sendfile64
  - fs/read_write.c:__se_sys_sendfile64
  - fs/read_write.c:__se_sys_sendfile
  - fs/read_write.c:__se_sys_sendfile
```
**Symbols:**

```
c000000000478ec0-c00000000047935c: do_sendfile (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ssize_t do_sendfile(int out_fd, int in_fd, loff_t *ppos, size_t count, loff_t max);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffe000256d44)
Location: fs/read_write.c:1419
Inline: False
Direct callers:
  - fs/read_write.c:__se_sys_sendfile64
  - fs/read_write.c:__se_sys_sendfile64
  - fs/read_write.c:__se_sys_sendfile
  - fs/read_write.c:__se_sys_sendfile
```
**Symbols:**

```
ffffffe000256d44-ffffffe000257004: do_sendfile (STB_LOCAL)
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
ssize_t do_sendfile(int out_fd, int in_fd, loff_t *ppos, size_t count, loff_t max);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812d53e0)
Location: fs/read_write.c:1419
Inline: False
Direct callers:
  - fs/read_write.c:__x32_compat_sys_sendfile64
  - fs/read_write.c:__x32_compat_sys_sendfile64
  - fs/read_write.c:__ia32_compat_sys_sendfile64
  - fs/read_write.c:__ia32_compat_sys_sendfile64
  - fs/read_write.c:__x32_compat_sys_sendfile
  - fs/read_write.c:__x32_compat_sys_sendfile
  - fs/read_write.c:__ia32_compat_sys_sendfile
  - fs/read_write.c:__ia32_compat_sys_sendfile
  - fs/read_write.c:__ia32_sys_sendfile64
  - fs/read_write.c:__ia32_sys_sendfile64
  - fs/read_write.c:__x64_sys_sendfile64
  - fs/read_write.c:__x64_sys_sendfile64
  - fs/read_write.c:__ia32_sys_sendfile
  - fs/read_write.c:__ia32_sys_sendfile
  - fs/read_write.c:__x64_sys_sendfile
  - fs/read_write.c:__x64_sys_sendfile
```
**Symbols:**

```
ffffffff812d53e0-ffffffff812d57c0: do_sendfile (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ssize_t do_sendfile(int out_fd, int in_fd, loff_t *ppos, size_t count, loff_t max);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812c6060)
Location: fs/read_write.c:1419
Inline: False
Direct callers:
  - fs/read_write.c:__x32_compat_sys_sendfile64
  - fs/read_write.c:__x32_compat_sys_sendfile64
  - fs/read_write.c:__ia32_compat_sys_sendfile64
  - fs/read_write.c:__ia32_compat_sys_sendfile64
  - fs/read_write.c:__x32_compat_sys_sendfile
  - fs/read_write.c:__x32_compat_sys_sendfile
  - fs/read_write.c:__ia32_compat_sys_sendfile
  - fs/read_write.c:__ia32_compat_sys_sendfile
  - fs/read_write.c:__ia32_sys_sendfile64
  - fs/read_write.c:__ia32_sys_sendfile64
  - fs/read_write.c:__x64_sys_sendfile64
  - fs/read_write.c:__x64_sys_sendfile64
  - fs/read_write.c:__ia32_sys_sendfile
  - fs/read_write.c:__ia32_sys_sendfile
  - fs/read_write.c:__x64_sys_sendfile
  - fs/read_write.c:__x64_sys_sendfile
```
**Symbols:**

```
ffffffff812c6060-ffffffff812c6440: do_sendfile (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ssize_t do_sendfile(int out_fd, int in_fd, loff_t *ppos, size_t count, loff_t max);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812d31f0)
Location: fs/read_write.c:1419
Inline: False
Direct callers:
  - fs/read_write.c:__x32_compat_sys_sendfile64
  - fs/read_write.c:__x32_compat_sys_sendfile64
  - fs/read_write.c:__ia32_compat_sys_sendfile64
  - fs/read_write.c:__ia32_compat_sys_sendfile64
  - fs/read_write.c:__x32_compat_sys_sendfile
  - fs/read_write.c:__x32_compat_sys_sendfile
  - fs/read_write.c:__ia32_compat_sys_sendfile
  - fs/read_write.c:__ia32_compat_sys_sendfile
  - fs/read_write.c:__ia32_sys_sendfile64
  - fs/read_write.c:__ia32_sys_sendfile64
  - fs/read_write.c:__x64_sys_sendfile64
  - fs/read_write.c:__x64_sys_sendfile64
  - fs/read_write.c:__ia32_sys_sendfile
  - fs/read_write.c:__ia32_sys_sendfile
  - fs/read_write.c:__x64_sys_sendfile
  - fs/read_write.c:__x64_sys_sendfile
```
**Symbols:**

```
ffffffff812d31f0-ffffffff812d35d0: do_sendfile (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ssize_t do_sendfile(int out_fd, int in_fd, loff_t *ppos, size_t count, loff_t max);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812e4050)
Location: fs/read_write.c:1419
Inline: False
Direct callers:
  - fs/read_write.c:__x32_compat_sys_sendfile64
  - fs/read_write.c:__x32_compat_sys_sendfile64
  - fs/read_write.c:__ia32_compat_sys_sendfile64
  - fs/read_write.c:__ia32_compat_sys_sendfile64
  - fs/read_write.c:__x32_compat_sys_sendfile
  - fs/read_write.c:__x32_compat_sys_sendfile
  - fs/read_write.c:__ia32_compat_sys_sendfile
  - fs/read_write.c:__ia32_compat_sys_sendfile
  - fs/read_write.c:__ia32_sys_sendfile64
  - fs/read_write.c:__ia32_sys_sendfile64
  - fs/read_write.c:__x64_sys_sendfile64
  - fs/read_write.c:__x64_sys_sendfile64
  - fs/read_write.c:__ia32_sys_sendfile
  - fs/read_write.c:__ia32_sys_sendfile
  - fs/read_write.c:__x64_sys_sendfile
  - fs/read_write.c:__x64_sys_sendfile
```
**Symbols:**

```
ffffffff812e4050-ffffffff812e4430: do_sendfile (STB_LOCAL)
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
