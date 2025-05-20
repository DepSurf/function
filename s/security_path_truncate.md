# Function: <code>security_path_truncate</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int security_path_truncate(struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8133c1d0)
Location: security/security.c:484
Inline: False
Direct callers:
  - fs/open.c:vfs_truncate
  - fs/namei.c:path_openat
```
**Symbols:**

```
ffffffff8133c1d0-ffffffff8133c224: security_path_truncate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int security_path_truncate(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813717a0)
Location: security/security.c:485
Inline: False
Direct callers:
  - fs/open.c:vfs_truncate
  - fs/namei.c:path_openat
```
**Symbols:**

```
ffffffff813717a0-ffffffff813717f4: security_path_truncate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int security_path_truncate(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813880d0)
Location: security/security.c:494
Inline: False
Direct callers:
  - fs/open.c:vfs_truncate
  - fs/namei.c:path_openat
```
**Symbols:**

```
ffffffff813880d0-ffffffff81388124: security_path_truncate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int security_path_truncate(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8139d0d0)
Location: security/security.c:1099
Inline: False
Direct callers:
  - fs/open.c:vfs_truncate
  - fs/namei.c:path_openat
```
**Symbols:**

```
ffffffff8139d0d0-ffffffff8139d124: security_path_truncate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int security_path_truncate(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813c2960)
Location: security/security.c:1048
Inline: False
Direct callers:
  - fs/open.c:vfs_truncate
  - fs/namei.c:path_openat
```
**Symbols:**

```
ffffffff813c2960-ffffffff813c29ba: security_path_truncate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int security_path_truncate(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813f2a10)
Location: security/security.c:590
Inline: False
Direct callers:
  - fs/open.c:do_sys_ftruncate
  - fs/open.c:vfs_truncate
  - fs/namei.c:path_openat
```
**Symbols:**

```
ffffffff813f2a10-ffffffff813f2a5b: security_path_truncate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int security_path_truncate(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8140deb0)
Location: security/security.c:1111
Inline: False
Direct callers:
  - fs/open.c:do_sys_ftruncate
  - fs/open.c:vfs_truncate
  - fs/namei.c:path_openat
```
**Symbols:**

```
ffffffff8140deb0-ffffffff8140defb: security_path_truncate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int security_path_truncate(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8143bd90)
Location: security/security.c:1125
Inline: False
Direct callers:
  - fs/open.c:do_sys_ftruncate
  - fs/open.c:vfs_truncate
  - fs/namei.c:do_last
```
**Symbols:**

```
ffffffff8143bd90-ffffffff8143bde2: security_path_truncate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int security_path_truncate(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81455aa0)
Location: security/security.c:1165
Inline: False
Direct callers:
  - fs/open.c:do_sys_ftruncate
  - fs/open.c:vfs_truncate
  - fs/namei.c:do_last
```
**Symbols:**

```
ffffffff81455aa0-ffffffff81455aeb: security_path_truncate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int security_path_truncate(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814a82d0)
Location: security/security.c:1313
Inline: False
Direct callers:
  - fs/open.c:do_sys_ftruncate
  - fs/open.c:vfs_truncate
  - fs/namei.c:handle_truncate
```
**Symbols:**

```
ffffffff814a82d0-ffffffff814a831b: security_path_truncate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int security_path_truncate(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814c5860)
Location: security/security.c:1315
Inline: False
Direct callers:
  - fs/open.c:do_sys_ftruncate
  - fs/open.c:vfs_truncate
  - fs/namei.c:handle_truncate
```
**Symbols:**

```
ffffffff814c5860-ffffffff814c58ab: security_path_truncate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int security_path_truncate(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814cd350)
Location: security/security.c:1365
Inline: False
Direct callers:
  - fs/open.c:do_sys_ftruncate
  - fs/open.c:vfs_truncate
  - fs/namei.c:do_open
```
**Symbols:**

```
ffffffff814cd350-ffffffff814cd39b: security_path_truncate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int security_path_truncate(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81524a50)
Location: security/security.c:1368
Inline: False
Direct callers:
  - fs/open.c:do_sys_ftruncate
  - fs/open.c:vfs_truncate
  - fs/namei.c:do_open
```
**Symbols:**

```
ffffffff81524a50-ffffffff81524a9b: security_path_truncate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int security_path_truncate(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff815ba9e0)
Location: security/security.c:1378
Inline: False
Direct callers:
  - fs/open.c:do_sys_ftruncate
  - fs/open.c:vfs_truncate
  - fs/namei.c:do_open
```
**Symbols:**

```
ffffffff815ba9e0-ffffffff815baa44: security_path_truncate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int security_path_truncate(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81666400)
Location: security/security.c:1376
Inline: False
Direct callers:
  - fs/open.c:vfs_truncate
```
**Symbols:**

```
ffffffff81666400-ffffffff81666464: security_path_truncate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int security_path_truncate(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8169e9f0)
Location: security/security.c:1957
Inline: False
Direct callers:
  - fs/open.c:vfs_truncate
```
**Symbols:**

```
ffffffff8169e9f0-ffffffff8169ea54: security_path_truncate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int security_path_truncate(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816db340)
Location: security/security.c:2030
Inline: False
Direct callers:
  - fs/open.c:vfs_truncate
```
**Symbols:**

```
ffffffff816db340-ffffffff816db3a4: security_path_truncate (STB_GLOBAL)
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
int security_path_truncate(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffff800010541080)
Location: security/security.c:1165
Inline: False
Direct callers:
  - fs/open.c:do_sys_ftruncate
  - fs/open.c:vfs_truncate
  - fs/namei.c:do_last
```
**Symbols:**

```
ffff800010541080-ffff8000105410e0: security_path_truncate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int security_path_truncate(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c06f70bc)
Location: security/security.c:1165
Inline: False
Direct callers:
  - fs/open.c:do_sys_ftruncate
  - fs/open.c:vfs_truncate
  - fs/namei.c:do_last
```
**Symbols:**

```
c06f70bc-c06f7124: security_path_truncate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int security_path_truncate(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c000000000693480)
Location: security/security.c:1165
Inline: False
Direct callers:
  - fs/open.c:do_sys_ftruncate
  - fs/open.c:vfs_truncate
  - fs/namei.c:do_last
```
**Symbols:**

```
c000000000693480-c000000000693528: security_path_truncate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int security_path_truncate(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffe00039de98)
Location: security/security.c:1165
Inline: False
Direct callers:
  - fs/open.c:do_sys_ftruncate
  - fs/open.c:vfs_truncate
  - fs/namei.c:do_last
```
**Symbols:**

```
ffffffe00039de98-ffffffe00039dee2: security_path_truncate (STB_GLOBAL)
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
int security_path_truncate(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144e080)
Location: security/security.c:1165
Inline: False
Direct callers:
  - fs/open.c:do_sys_ftruncate
  - fs/open.c:vfs_truncate
  - fs/namei.c:do_last
```
**Symbols:**

```
ffffffff8144e080-ffffffff8144e0cb: security_path_truncate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int security_path_truncate(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8143ead0)
Location: security/security.c:1165
Inline: False
Direct callers:
  - fs/open.c:do_sys_ftruncate
  - fs/open.c:vfs_truncate
  - fs/namei.c:do_last
```
**Symbols:**

```
ffffffff8143ead0-ffffffff8143eb1b: security_path_truncate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int security_path_truncate(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144a120)
Location: security/security.c:1165
Inline: False
Direct callers:
  - fs/open.c:do_sys_ftruncate
  - fs/open.c:vfs_truncate
  - fs/namei.c:do_last
```
**Symbols:**

```
ffffffff8144a120-ffffffff8144a16b: security_path_truncate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int security_path_truncate(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814614f0)
Location: security/security.c:1165
Inline: False
Direct callers:
  - fs/open.c:do_sys_ftruncate
  - fs/open.c:vfs_truncate
  - fs/namei.c:do_last
```
**Symbols:**

```
ffffffff814614f0-ffffffff8146153b: security_path_truncate (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct path *path</code> ➡️ <code>const struct path *path</code>
</li>
</ul>
</details>
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
