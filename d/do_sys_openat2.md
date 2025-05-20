# Function: <code>do_sys_openat2</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int do_sys_openat2(int dfd, const char *filename, struct open_how *how);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8130f9b0)
Location: fs/open.c:1164
Inline: False
Direct callers:
  - fs/open.c:__ia32_sys_creat
  - fs/open.c:__x64_sys_creat
  - fs/open.c:__x32_compat_sys_openat
  - fs/open.c:__ia32_compat_sys_openat
  - fs/open.c:__x32_compat_sys_open
  - fs/open.c:__ia32_compat_sys_open
  - fs/open.c:__ia32_sys_openat2
  - fs/open.c:__x64_sys_openat2
  - fs/open.c:__ia32_sys_openat
  - fs/open.c:__x64_sys_openat
  - fs/open.c:__ia32_sys_open
  - fs/open.c:__x64_sys_open
```
**Symbols:**

```
ffffffff8130f9b0-ffffffff8130faf9: do_sys_openat2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int do_sys_openat2(int dfd, const char *filename, struct open_how *how);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8131bc70)
Location: fs/open.c:1157
Inline: False
Direct callers:
  - fs/open.c:__ia32_sys_creat
  - fs/open.c:__x64_sys_creat
  - fs/open.c:__x32_compat_sys_openat
  - fs/open.c:__ia32_compat_sys_openat
  - fs/open.c:__x32_compat_sys_open
  - fs/open.c:__ia32_compat_sys_open
  - fs/open.c:__ia32_sys_openat2
  - fs/open.c:__x64_sys_openat2
  - fs/open.c:__ia32_sys_openat
  - fs/open.c:__x64_sys_openat
  - fs/open.c:__ia32_sys_open
  - fs/open.c:__x64_sys_open
```
**Symbols:**

```
ffffffff8131bc70-ffffffff8131bdb9: do_sys_openat2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int do_sys_openat2(int dfd, const char *filename, struct open_how *how);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff81321de0)
Location: fs/open.c:1179
Inline: False
Direct callers:
  - fs/open.c:__ia32_sys_creat
  - fs/open.c:__x64_sys_creat
  - fs/open.c:__x32_compat_sys_openat
  - fs/open.c:__ia32_compat_sys_openat
  - fs/open.c:__x32_compat_sys_open
  - fs/open.c:__ia32_compat_sys_open
  - fs/open.c:__ia32_sys_openat2
  - fs/open.c:__x64_sys_openat2
  - fs/open.c:__ia32_sys_openat
  - fs/open.c:__x64_sys_openat
  - fs/open.c:__ia32_sys_open
  - fs/open.c:__x64_sys_open
```
**Symbols:**

```
ffffffff81321de0-ffffffff81321f29: do_sys_openat2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int do_sys_openat2(int dfd, const char *filename, struct open_how *how);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8136f2c0)
Location: fs/open.c:1197
Inline: False
Direct callers:
  - fs/open.c:__ia32_sys_creat
  - fs/open.c:__x64_sys_creat
  - fs/open.c:__x64_compat_sys_openat
  - fs/open.c:__ia32_compat_sys_openat
  - fs/open.c:__x64_compat_sys_open
  - fs/open.c:__ia32_compat_sys_open
  - fs/open.c:__ia32_sys_openat2
  - fs/open.c:__x64_sys_openat2
  - fs/open.c:__ia32_sys_openat
  - fs/open.c:__x64_sys_openat
  - fs/open.c:__ia32_sys_open
  - fs/open.c:__x64_sys_open
```
**Symbols:**

```
ffffffff8136f2c0-ffffffff8136f419: do_sys_openat2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int do_sys_openat2(int dfd, const char *filename, struct open_how *how);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff813edcd0)
Location: fs/open.c:1262
Inline: False
Direct callers:
  - fs/open.c:__ia32_sys_creat
  - fs/open.c:__x64_sys_creat
  - fs/open.c:__ia32_compat_sys_openat
  - fs/open.c:__ia32_compat_sys_open
  - fs/open.c:__do_sys_openat2
  - fs/open.c:__ia32_sys_openat
  - fs/open.c:__x64_sys_openat
  - fs/open.c:__ia32_sys_open
  - fs/open.c:__x64_sys_open
```
**Symbols:**

```
ffffffff813edcd0-ffffffff813ede48: do_sys_openat2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int do_sys_openat2(int dfd, const char *filename, struct open_how *how);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff81476450)
Location: fs/open.c:1294
Inline: False
Direct callers:
  - fs/open.c:__ia32_sys_creat
  - fs/open.c:__x64_sys_creat
  - fs/open.c:__ia32_compat_sys_openat
  - fs/open.c:__ia32_compat_sys_open
  - fs/open.c:__do_sys_openat2
  - fs/open.c:__ia32_sys_openat
  - fs/open.c:__x64_sys_openat
  - fs/open.c:__ia32_sys_open
  - fs/open.c:__x64_sys_open
```
**Symbols:**

```
ffffffff81476450-ffffffff814765c8: do_sys_openat2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int do_sys_openat2(int dfd, const char *filename, struct open_how *how);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff814aad90)
Location: fs/open.c:1391
Inline: False
Direct callers:
  - fs/open.c:__ia32_sys_creat
  - fs/open.c:__x64_sys_creat
  - fs/open.c:__ia32_compat_sys_openat
  - fs/open.c:__ia32_compat_sys_open
  - fs/open.c:__ia32_sys_openat2
  - fs/open.c:__x64_sys_openat2
  - fs/open.c:__ia32_sys_openat
  - fs/open.c:__x64_sys_openat
  - fs/open.c:__ia32_sys_open
  - fs/open.c:__x64_sys_open
```
**Symbols:**

```
ffffffff814aad90-ffffffff814aae6f: do_sys_openat2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int do_sys_openat2(int dfd, const char *filename, struct open_how *how);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff814dc230)
Location: fs/open.c:1388
Inline: False
Direct callers:
  - fs/open.c:__ia32_sys_creat
  - fs/open.c:__x64_sys_creat
  - fs/open.c:__ia32_compat_sys_openat
  - fs/open.c:__ia32_compat_sys_open
  - fs/open.c:__ia32_sys_openat2
  - fs/open.c:__x64_sys_openat2
  - fs/open.c:__ia32_sys_openat
  - fs/open.c:__x64_sys_openat
  - fs/open.c:__ia32_sys_open
  - fs/open.c:__x64_sys_open
```
**Symbols:**

```
ffffffff814dc230-ffffffff814dc30f: do_sys_openat2 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
