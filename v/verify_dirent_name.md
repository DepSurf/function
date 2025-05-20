# Function: <code>verify_dirent_name</code>

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
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int verify_dirent_name(const char *name, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/readdir.c (ffffffff812f3d50)
Location: fs/readdir.c:110
Inline: False
Direct callers:
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir
```
**Symbols:**

```
ffffffff812f3d50-ffffffff812f3d83: verify_dirent_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int verify_dirent_name(const char *name, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/readdir.c (ffffffff8132c2d0)
Location: fs/readdir.c:110
Inline: False
Direct callers:
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir
```
**Symbols:**

```
ffffffff8132c2d0-ffffffff8132c303: verify_dirent_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int verify_dirent_name(const char *name, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/readdir.c (ffffffff813378d0)
Location: fs/readdir.c:110
Inline: False
Direct callers:
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir
```
**Symbols:**

```
ffffffff813378d0-ffffffff81337903: verify_dirent_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int verify_dirent_name(const char *name, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/readdir.c (ffffffff8133df30)
Location: fs/readdir.c:110
Inline: False
Direct callers:
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir
  - fs/readdir.c:fillonedir
```
**Symbols:**

```
ffffffff8133df30-ffffffff8133df60: verify_dirent_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int verify_dirent_name(const char *name, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/readdir.c (ffffffff8138b8b0)
Location: fs/readdir.c:110
Inline: False
Direct callers:
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir
  - fs/readdir.c:fillonedir
```
**Symbols:**

```
ffffffff8138b8b0-ffffffff8138b8e0: verify_dirent_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int verify_dirent_name(const char *name, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/readdir.c (ffffffff8140cc30)
Location: fs/readdir.c:110
Inline: False
Direct callers:
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir
  - fs/readdir.c:fillonedir
```
**Symbols:**

```
ffffffff8140cc30-ffffffff8140cc74: verify_dirent_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int verify_dirent_name(const char *name, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/readdir.c (ffffffff814976f0)
Location: fs/readdir.c:110
Inline: False
Direct callers:
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir
  - fs/readdir.c:fillonedir
```
**Symbols:**

```
ffffffff814976f0-ffffffff81497734: verify_dirent_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int verify_dirent_name(const char *name, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/readdir.c (ffffffff814cc810)
Location: fs/readdir.c:146
Inline: False
Direct callers:
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir
  - fs/readdir.c:fillonedir
```
**Symbols:**

```
ffffffff814cc810-ffffffff814cc854: verify_dirent_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int verify_dirent_name(const char *name, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/readdir.c (ffffffff814ff0d0)
Location: fs/readdir.c:150
Inline: False
Direct callers:
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir
  - fs/readdir.c:fillonedir
```
**Symbols:**

```
ffffffff814ff0d0-ffffffff814ff114: verify_dirent_name (STB_LOCAL)
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
int verify_dirent_name(const char *name, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/readdir.c (ffff80001039f340)
Location: fs/readdir.c:110
Inline: False
Direct callers:
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir
```
**Symbols:**

```
ffff80001039f340-ffff80001039f398: verify_dirent_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int verify_dirent_name(const char *name, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/readdir.c (c0584190)
Location: fs/readdir.c:110
Inline: False
Direct callers:
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir
```
**Symbols:**

```
c0584190-c05841d8: verify_dirent_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int verify_dirent_name(const char *name, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/readdir.c (c000000000499af0)
Location: fs/readdir.c:110
Inline: False
Direct callers:
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir
```
**Symbols:**

```
c000000000499af0-c000000000499b58: verify_dirent_name (STB_LOCAL)
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
In fs/readdir.c (ffffffe00026a302)
Location: fs/readdir.c:110
Inline: True
Inline callers:
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir
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
int verify_dirent_name(const char *name, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/readdir.c (ffffffff812ec330)
Location: fs/readdir.c:110
Inline: False
Direct callers:
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir
```
**Symbols:**

```
ffffffff812ec330-ffffffff812ec363: verify_dirent_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int verify_dirent_name(const char *name, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/readdir.c (ffffffff812dcf60)
Location: fs/readdir.c:110
Inline: False
Direct callers:
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir
```
**Symbols:**

```
ffffffff812dcf60-ffffffff812dcf93: verify_dirent_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int verify_dirent_name(const char *name, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/readdir.c (ffffffff812ea140)
Location: fs/readdir.c:110
Inline: False
Direct callers:
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir
```
**Symbols:**

```
ffffffff812ea140-ffffffff812ea173: verify_dirent_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int verify_dirent_name(const char *name, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/readdir.c (ffffffff812fb130)
Location: fs/readdir.c:110
Inline: False
Direct callers:
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir
```
**Symbols:**

```
ffffffff812fb130-ffffffff812fb163: verify_dirent_name (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
