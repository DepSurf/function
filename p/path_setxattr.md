# Function: <code>path_setxattr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int path_setxattr(const char *pathname, const char *name, const void *value, size_t size, int flags, unsigned int lookup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff81232d00)
Location: fs/xattr.c:372
Inline: False
Direct callers:
  - fs/xattr.c:SyS_setxattr
  - fs/xattr.c:SyS_lsetxattr
```
**Symbols:**

```
ffffffff81232d00-ffffffff81232dd7: path_setxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int path_setxattr(const char *pathname, const char *name, const void *value, size_t size, int flags, unsigned int lookup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff8125b430)
Location: fs/xattr.c:375
Inline: False
Direct callers:
  - fs/xattr.c:SyS_lsetxattr
  - fs/xattr.c:SyS_setxattr
```
**Symbols:**

```
ffffffff8125b430-ffffffff8125b510: path_setxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int path_setxattr(const char *pathname, const char *name, const void *value, size_t size, int flags, unsigned int lookup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff8126e9e0)
Location: fs/xattr.c:480
Inline: False
Direct callers:
  - fs/xattr.c:SyS_lsetxattr
  - fs/xattr.c:SyS_setxattr
```
**Symbols:**

```
ffffffff8126e9e0-ffffffff8126eac0: path_setxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int path_setxattr(const char *pathname, const char *name, const void *value, size_t size, int flags, unsigned int lookup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff8127c200)
Location: fs/xattr.c:483
Inline: False
Direct callers:
  - fs/xattr.c:SyS_lsetxattr
  - fs/xattr.c:SyS_setxattr
```
**Symbols:**

```
ffffffff8127c200-ffffffff8127c2d0: path_setxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int path_setxattr(const char *pathname, const char *name, const void *value, size_t size, int flags, unsigned int lookup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff8129eca0)
Location: fs/xattr.c:484
Inline: False
Direct callers:
  - fs/xattr.c:SyS_lsetxattr
  - fs/xattr.c:SyS_setxattr
```
**Symbols:**

```
ffffffff8129eca0-ffffffff8129ed70: path_setxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int path_setxattr(const char *pathname, const char *name, const void *value, size_t size, int flags, unsigned int lookup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff812c5950)
Location: fs/xattr.c:482
Inline: False
Direct callers:
  - fs/xattr.c:__ia32_sys_lsetxattr
  - fs/xattr.c:__x64_sys_lsetxattr
  - fs/xattr.c:__ia32_sys_setxattr
  - fs/xattr.c:__x64_sys_setxattr
```
**Symbols:**

```
ffffffff812c5950-ffffffff812c5a20: path_setxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int path_setxattr(const char *pathname, const char *name, const void *value, size_t size, int flags, unsigned int lookup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff812dab50)
Location: fs/xattr.c:481
Inline: False
Direct callers:
  - fs/xattr.c:__ia32_sys_lsetxattr
  - fs/xattr.c:__x64_sys_lsetxattr
  - fs/xattr.c:__ia32_sys_setxattr
  - fs/xattr.c:__x64_sys_setxattr
```
**Symbols:**

```
ffffffff812dab50-ffffffff812dac20: path_setxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int path_setxattr(const char *pathname, const char *name, const void *value, size_t size, int flags, unsigned int lookup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff812f91d0)
Location: fs/xattr.c:482
Inline: False
Direct callers:
  - fs/xattr.c:__ia32_sys_lsetxattr
  - fs/xattr.c:__x64_sys_lsetxattr
  - fs/xattr.c:__ia32_sys_setxattr
  - fs/xattr.c:__x64_sys_setxattr
```
**Symbols:**

```
ffffffff812f91d0-ffffffff812f929a: path_setxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int path_setxattr(const char *pathname, const char *name, const void *value, size_t size, int flags, unsigned int lookup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff8130ae00)
Location: fs/xattr.c:482
Inline: False
Direct callers:
  - fs/xattr.c:__ia32_sys_lsetxattr
  - fs/xattr.c:__x64_sys_lsetxattr
  - fs/xattr.c:__ia32_sys_setxattr
  - fs/xattr.c:__x64_sys_setxattr
```
**Symbols:**

```
ffffffff8130ae00-ffffffff8130aeca: path_setxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int path_setxattr(const char *pathname, const char *name, const void *value, size_t size, int flags, unsigned int lookup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff813445d0)
Location: fs/xattr.c:552
Inline: False
Direct callers:
  - fs/xattr.c:__ia32_sys_lsetxattr
  - fs/xattr.c:__x64_sys_lsetxattr
  - fs/xattr.c:__ia32_sys_setxattr
  - fs/xattr.c:__x64_sys_setxattr
```
**Symbols:**

```
ffffffff813445d0-ffffffff8134469a: path_setxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int path_setxattr(const char *pathname, const char *name, const void *value, size_t size, int flags, unsigned int lookup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff813508c0)
Location: fs/xattr.c:584
Inline: False
Direct callers:
  - fs/xattr.c:__ia32_sys_lsetxattr
  - fs/xattr.c:__x64_sys_lsetxattr
  - fs/xattr.c:__ia32_sys_setxattr
  - fs/xattr.c:__x64_sys_setxattr
```
**Symbols:**

```
ffffffff813508c0-ffffffff8135098a: path_setxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int path_setxattr(const char *pathname, const char *name, const void *value, size_t size, int flags, unsigned int lookup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff81357460)
Location: fs/xattr.c:606
Inline: False
Direct callers:
  - fs/xattr.c:__ia32_sys_lsetxattr
  - fs/xattr.c:__x64_sys_lsetxattr
  - fs/xattr.c:__ia32_sys_setxattr
  - fs/xattr.c:__x64_sys_setxattr
```
**Symbols:**

```
ffffffff81357460-ffffffff81357532: path_setxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int path_setxattr(const char *pathname, const char *name, const void *value, size_t size, int flags, unsigned int lookup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff813a5050)
Location: fs/xattr.c:607
Inline: False
Direct callers:
  - fs/xattr.c:__ia32_sys_lsetxattr
  - fs/xattr.c:__x64_sys_lsetxattr
  - fs/xattr.c:__ia32_sys_setxattr
  - fs/xattr.c:__x64_sys_setxattr
```
**Symbols:**

```
ffffffff813a5050-ffffffff813a5122: path_setxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int path_setxattr(const char *pathname, const char *name, const void *value, size_t size, int flags, unsigned int lookup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff81429670)
Location: fs/xattr.c:641
Inline: False
Direct callers:
  - fs/xattr.c:__ia32_sys_lsetxattr
  - fs/xattr.c:__x64_sys_lsetxattr
  - fs/xattr.c:__ia32_sys_setxattr
  - fs/xattr.c:__x64_sys_setxattr
```
**Symbols:**

```
ffffffff81429670-ffffffff81429764: path_setxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int path_setxattr(const char *pathname, const char *name, const void *value, size_t size, int flags, unsigned int lookup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff814b6640)
Location: fs/xattr.c:661
Inline: False
Direct callers:
  - fs/xattr.c:__ia32_sys_lsetxattr
  - fs/xattr.c:__x64_sys_lsetxattr
  - fs/xattr.c:__ia32_sys_setxattr
  - fs/xattr.c:__x64_sys_setxattr
```
**Symbols:**

```
ffffffff814b6640-ffffffff814b6734: path_setxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int path_setxattr(const char *pathname, const char *name, const void *value, size_t size, int flags, unsigned int lookup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff814eb350)
Location: fs/xattr.c:659
Inline: False
Direct callers:
  - fs/xattr.c:__ia32_sys_lsetxattr
  - fs/xattr.c:__x64_sys_lsetxattr
  - fs/xattr.c:__ia32_sys_setxattr
  - fs/xattr.c:__x64_sys_setxattr
```
**Symbols:**

```
ffffffff814eb350-ffffffff814eb444: path_setxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int path_setxattr(const char *pathname, const char *name, const void *value, size_t size, int flags, unsigned int lookup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff8151f1f0)
Location: fs/xattr.c:659
Inline: False
Direct callers:
  - fs/xattr.c:__ia32_sys_lsetxattr
  - fs/xattr.c:__x64_sys_lsetxattr
  - fs/xattr.c:__ia32_sys_setxattr
  - fs/xattr.c:__x64_sys_setxattr
```
**Symbols:**

```
ffffffff8151f1f0-ffffffff8151f2e7: path_setxattr (STB_LOCAL)
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
int path_setxattr(const char *pathname, const char *name, const void *value, size_t size, int flags, unsigned int lookup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffff8000103bf230)
Location: fs/xattr.c:482
Inline: False
Direct callers:
  - fs/xattr.c:__arm64_sys_lsetxattr
  - fs/xattr.c:__arm64_sys_setxattr
```
**Symbols:**

```
ffff8000103bf230-ffff8000103bf320: path_setxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int path_setxattr(const char *pathname, const char *name, const void *value, size_t size, int flags, unsigned int lookup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (c059be5c)
Location: fs/xattr.c:482
Inline: False
Direct callers:
  - fs/xattr.c:__se_sys_lsetxattr
  - fs/xattr.c:__se_sys_setxattr
```
**Symbols:**

```
c059be5c-c059bf44: path_setxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int path_setxattr(const char *pathname, const char *name, const void *value, size_t size, int flags, unsigned int lookup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (c0000000004bd690)
Location: fs/xattr.c:482
Inline: False
Direct callers:
  - fs/xattr.c:__se_sys_lsetxattr
  - fs/xattr.c:__se_sys_setxattr
```
**Symbols:**

```
c0000000004bd690-c0000000004bd7d8: path_setxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int path_setxattr(const char *pathname, const char *name, const void *value, size_t size, int flags, unsigned int lookup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffe00027f93e)
Location: fs/xattr.c:482
Inline: False
Direct callers:
  - fs/xattr.c:__se_sys_lsetxattr
  - fs/xattr.c:__se_sys_setxattr
```
**Symbols:**

```
ffffffe00027f93e-ffffffe00027f9f6: path_setxattr (STB_LOCAL)
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
int path_setxattr(const char *pathname, const char *name, const void *value, size_t size, int flags, unsigned int lookup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff813033e0)
Location: fs/xattr.c:482
Inline: False
Direct callers:
  - fs/xattr.c:__ia32_sys_lsetxattr
  - fs/xattr.c:__x64_sys_lsetxattr
  - fs/xattr.c:__ia32_sys_setxattr
  - fs/xattr.c:__x64_sys_setxattr
```
**Symbols:**

```
ffffffff813033e0-ffffffff813034aa: path_setxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int path_setxattr(const char *pathname, const char *name, const void *value, size_t size, int flags, unsigned int lookup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff812f4000)
Location: fs/xattr.c:482
Inline: False
Direct callers:
  - fs/xattr.c:__ia32_sys_lsetxattr
  - fs/xattr.c:__x64_sys_lsetxattr
  - fs/xattr.c:__ia32_sys_setxattr
  - fs/xattr.c:__x64_sys_setxattr
```
**Symbols:**

```
ffffffff812f4000-ffffffff812f40ca: path_setxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int path_setxattr(const char *pathname, const char *name, const void *value, size_t size, int flags, unsigned int lookup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff813011d0)
Location: fs/xattr.c:482
Inline: False
Direct callers:
  - fs/xattr.c:__ia32_sys_lsetxattr
  - fs/xattr.c:__x64_sys_lsetxattr
  - fs/xattr.c:__ia32_sys_setxattr
  - fs/xattr.c:__x64_sys_setxattr
```
**Symbols:**

```
ffffffff813011d0-ffffffff8130129a: path_setxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int path_setxattr(const char *pathname, const char *name, const void *value, size_t size, int flags, unsigned int lookup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff81312510)
Location: fs/xattr.c:482
Inline: False
Direct callers:
  - fs/xattr.c:__ia32_sys_lsetxattr
  - fs/xattr.c:__x64_sys_lsetxattr
  - fs/xattr.c:__ia32_sys_setxattr
  - fs/xattr.c:__x64_sys_setxattr
```
**Symbols:**

```
ffffffff81312510-ffffffff813125da: path_setxattr (STB_LOCAL)
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
