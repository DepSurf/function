# Function: <code>path_getxattr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
ssize_t path_getxattr(const char *pathname, const char *name, void *value, size_t size, unsigned int lookup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff812327f0)
Location: fs/xattr.c:481
Inline: False
Direct callers:
  - fs/xattr.c:SyS_getxattr
  - fs/xattr.c:SyS_lgetxattr
```
**Symbols:**

```
ffffffff812327f0-ffffffff81232897: path_getxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
ssize_t path_getxattr(const char *pathname, const char *name, void *value, size_t size, unsigned int lookup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff8125ad20)
Location: fs/xattr.c:476
Inline: False
Direct callers:
  - fs/xattr.c:SyS_lgetxattr
  - fs/xattr.c:SyS_getxattr
```
**Symbols:**

```
ffffffff8125ad20-ffffffff8125adce: path_getxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
ssize_t path_getxattr(const char *pathname, const char *name, void *value, size_t size, unsigned int lookup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff8126e2e0)
Location: fs/xattr.c:581
Inline: False
Direct callers:
  - fs/xattr.c:SyS_lgetxattr
  - fs/xattr.c:SyS_getxattr
```
**Symbols:**

```
ffffffff8126e2e0-ffffffff8126e38e: path_getxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ssize_t path_getxattr(const char *pathname, const char *name, void *value, size_t size, unsigned int lookup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff8127b900)
Location: fs/xattr.c:581
Inline: False
Direct callers:
  - fs/xattr.c:SyS_lgetxattr
  - fs/xattr.c:SyS_getxattr
```
**Symbols:**

```
ffffffff8127b900-ffffffff8127b9ae: path_getxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t path_getxattr(const char *pathname, const char *name, void *value, size_t size, unsigned int lookup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff8129e3a0)
Location: fs/xattr.c:582
Inline: False
Direct callers:
  - fs/xattr.c:SyS_lgetxattr
  - fs/xattr.c:SyS_getxattr
```
**Symbols:**

```
ffffffff8129e3a0-ffffffff8129e44e: path_getxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
ssize_t path_getxattr(const char *pathname, const char *name, void *value, size_t size, unsigned int lookup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff812c4af0)
Location: fs/xattr.c:580
Inline: False
Direct callers:
  - fs/xattr.c:__ia32_sys_lgetxattr
  - fs/xattr.c:__x64_sys_lgetxattr
  - fs/xattr.c:__ia32_sys_getxattr
  - fs/xattr.c:__x64_sys_getxattr
```
**Symbols:**

```
ffffffff812c4af0-ffffffff812c4b9e: path_getxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ssize_t path_getxattr(const char *pathname, const char *name, void *value, size_t size, unsigned int lookup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff812d9cf0)
Location: fs/xattr.c:579
Inline: False
Direct callers:
  - fs/xattr.c:__ia32_sys_lgetxattr
  - fs/xattr.c:__x64_sys_lgetxattr
  - fs/xattr.c:__ia32_sys_getxattr
  - fs/xattr.c:__x64_sys_getxattr
```
**Symbols:**

```
ffffffff812d9cf0-ffffffff812d9d9e: path_getxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
ssize_t path_getxattr(const char *pathname, const char *name, void *value, size_t size, unsigned int lookup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff812f82e0)
Location: fs/xattr.c:580
Inline: False
Direct callers:
  - fs/xattr.c:__ia32_sys_lgetxattr
  - fs/xattr.c:__x64_sys_lgetxattr
  - fs/xattr.c:__ia32_sys_getxattr
  - fs/xattr.c:__x64_sys_getxattr
```
**Symbols:**

```
ffffffff812f82e0-ffffffff812f8387: path_getxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ssize_t path_getxattr(const char *pathname, const char *name, void *value, size_t size, unsigned int lookup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff81309f10)
Location: fs/xattr.c:580
Inline: False
Direct callers:
  - fs/xattr.c:__ia32_sys_lgetxattr
  - fs/xattr.c:__x64_sys_lgetxattr
  - fs/xattr.c:__ia32_sys_getxattr
  - fs/xattr.c:__x64_sys_getxattr
```
**Symbols:**

```
ffffffff81309f10-ffffffff81309fb7: path_getxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t path_getxattr(const char *pathname, const char *name, void *value, size_t size, unsigned int lookup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff813440a0)
Location: fs/xattr.c:650
Inline: False
Direct callers:
  - fs/xattr.c:__ia32_sys_lgetxattr
  - fs/xattr.c:__x64_sys_lgetxattr
  - fs/xattr.c:__ia32_sys_getxattr
  - fs/xattr.c:__x64_sys_getxattr
```
**Symbols:**

```
ffffffff813440a0-ffffffff81344147: path_getxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t path_getxattr(const char *pathname, const char *name, void *value, size_t size, unsigned int lookup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff81350410)
Location: fs/xattr.c:682
Inline: False
Direct callers:
  - fs/xattr.c:__ia32_sys_lgetxattr
  - fs/xattr.c:__x64_sys_lgetxattr
  - fs/xattr.c:__ia32_sys_getxattr
  - fs/xattr.c:__x64_sys_getxattr
```
**Symbols:**

```
ffffffff81350410-ffffffff813504b7: path_getxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t path_getxattr(const char *pathname, const char *name, void *value, size_t size, unsigned int lookup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff81356f70)
Location: fs/xattr.c:708
Inline: False
Direct callers:
  - fs/xattr.c:__ia32_sys_lgetxattr
  - fs/xattr.c:__x64_sys_lgetxattr
  - fs/xattr.c:__ia32_sys_getxattr
  - fs/xattr.c:__x64_sys_getxattr
```
**Symbols:**

```
ffffffff81356f70-ffffffff8135701f: path_getxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
ssize_t path_getxattr(const char *pathname, const char *name, void *value, size_t size, unsigned int lookup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff813a5a30)
Location: fs/xattr.c:709
Inline: False
Direct callers:
  - fs/xattr.c:__ia32_sys_lgetxattr
  - fs/xattr.c:__x64_sys_lgetxattr
  - fs/xattr.c:__ia32_sys_getxattr
  - fs/xattr.c:__x64_sys_getxattr
```
**Symbols:**

```
ffffffff813a5a30-ffffffff813a5adf: path_getxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ssize_t path_getxattr(const char *pathname, const char *name, void *value, size_t size, unsigned int lookup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff81429d00)
Location: fs/xattr.c:761
Inline: False
Direct callers:
  - fs/xattr.c:__ia32_sys_lgetxattr
  - fs/xattr.c:__x64_sys_lgetxattr
  - fs/xattr.c:__ia32_sys_getxattr
  - fs/xattr.c:__x64_sys_getxattr
```
**Symbols:**

```
ffffffff81429d00-ffffffff81429dd1: path_getxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t path_getxattr(const char *pathname, const char *name, void *value, size_t size, unsigned int lookup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff814b6d60)
Location: fs/xattr.c:781
Inline: False
Direct callers:
  - fs/xattr.c:__ia32_sys_lgetxattr
  - fs/xattr.c:__x64_sys_lgetxattr
  - fs/xattr.c:__ia32_sys_getxattr
  - fs/xattr.c:__x64_sys_getxattr
```
**Symbols:**

```
ffffffff814b6d60-ffffffff814b6e31: path_getxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t path_getxattr(const char *pathname, const char *name, void *value, size_t size, unsigned int lookup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff814eba70)
Location: fs/xattr.c:778
Inline: False
Direct callers:
  - fs/xattr.c:__ia32_sys_lgetxattr
  - fs/xattr.c:__x64_sys_lgetxattr
  - fs/xattr.c:__ia32_sys_getxattr
  - fs/xattr.c:__x64_sys_getxattr
```
**Symbols:**

```
ffffffff814eba70-ffffffff814ebb41: path_getxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t path_getxattr(const char *pathname, const char *name, void *value, size_t size, unsigned int lookup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff8151f910)
Location: fs/xattr.c:778
Inline: False
Direct callers:
  - fs/xattr.c:__ia32_sys_lgetxattr
  - fs/xattr.c:__x64_sys_lgetxattr
  - fs/xattr.c:__ia32_sys_getxattr
  - fs/xattr.c:__x64_sys_getxattr
```
**Symbols:**

```
ffffffff8151f910-ffffffff8151f9e1: path_getxattr (STB_LOCAL)
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
ssize_t path_getxattr(const char *pathname, const char *name, void *value, size_t size, unsigned int lookup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffff8000103be6a0)
Location: fs/xattr.c:580
Inline: False
Direct callers:
  - fs/xattr.c:__arm64_sys_lgetxattr
  - fs/xattr.c:__arm64_sys_getxattr
```
**Symbols:**

```
ffff8000103be6a0-ffff8000103be770: path_getxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t path_getxattr(const char *pathname, const char *name, void *value, size_t size, unsigned int lookup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (c059b31c)
Location: fs/xattr.c:580
Inline: False
Direct callers:
  - fs/xattr.c:__se_sys_lgetxattr
  - fs/xattr.c:__se_sys_getxattr
```
**Symbols:**

```
c059b31c-c059b3e0: path_getxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t path_getxattr(const char *pathname, const char *name, void *value, size_t size, unsigned int lookup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (c0000000004bc2b0)
Location: fs/xattr.c:580
Inline: False
Direct callers:
  - fs/xattr.c:__se_sys_lgetxattr
  - fs/xattr.c:__se_sys_getxattr
```
**Symbols:**

```
c0000000004bc2b0-c0000000004bc3bc: path_getxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ssize_t path_getxattr(const char *pathname, const char *name, void *value, size_t size, unsigned int lookup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffe00027f146)
Location: fs/xattr.c:580
Inline: False
Direct callers:
  - fs/xattr.c:__se_sys_lgetxattr
  - fs/xattr.c:__se_sys_getxattr
```
**Symbols:**

```
ffffffe00027f146-ffffffe00027f1d6: path_getxattr (STB_LOCAL)
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
ssize_t path_getxattr(const char *pathname, const char *name, void *value, size_t size, unsigned int lookup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff813024f0)
Location: fs/xattr.c:580
Inline: False
Direct callers:
  - fs/xattr.c:__ia32_sys_lgetxattr
  - fs/xattr.c:__x64_sys_lgetxattr
  - fs/xattr.c:__ia32_sys_getxattr
  - fs/xattr.c:__x64_sys_getxattr
```
**Symbols:**

```
ffffffff813024f0-ffffffff81302597: path_getxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ssize_t path_getxattr(const char *pathname, const char *name, void *value, size_t size, unsigned int lookup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff812f3110)
Location: fs/xattr.c:580
Inline: False
Direct callers:
  - fs/xattr.c:__ia32_sys_lgetxattr
  - fs/xattr.c:__x64_sys_lgetxattr
  - fs/xattr.c:__ia32_sys_getxattr
  - fs/xattr.c:__x64_sys_getxattr
```
**Symbols:**

```
ffffffff812f3110-ffffffff812f31b7: path_getxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ssize_t path_getxattr(const char *pathname, const char *name, void *value, size_t size, unsigned int lookup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff813002e0)
Location: fs/xattr.c:580
Inline: False
Direct callers:
  - fs/xattr.c:__ia32_sys_lgetxattr
  - fs/xattr.c:__x64_sys_lgetxattr
  - fs/xattr.c:__ia32_sys_getxattr
  - fs/xattr.c:__x64_sys_getxattr
```
**Symbols:**

```
ffffffff813002e0-ffffffff81300387: path_getxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ssize_t path_getxattr(const char *pathname, const char *name, void *value, size_t size, unsigned int lookup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff81311620)
Location: fs/xattr.c:580
Inline: False
Direct callers:
  - fs/xattr.c:__ia32_sys_lgetxattr
  - fs/xattr.c:__x64_sys_lgetxattr
  - fs/xattr.c:__ia32_sys_getxattr
  - fs/xattr.c:__x64_sys_getxattr
```
**Symbols:**

```
ffffffff81311620-ffffffff813116c7: path_getxattr (STB_LOCAL)
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
