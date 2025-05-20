# Function: <code>path_listxattr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
ssize_t path_listxattr(const char *pathname, char *list, size_t size, unsigned int lookup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff812324f0)
Location: fs/xattr.c:564
Inline: False
Direct callers:
  - fs/xattr.c:SyS_listxattr
  - fs/xattr.c:SyS_llistxattr
```
**Symbols:**

```
ffffffff812324f0-ffffffff81232592: path_listxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
ssize_t path_listxattr(const char *pathname, char *list, size_t size, unsigned int lookup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff8125aaa0)
Location: fs/xattr.c:556
Inline: False
Direct callers:
  - fs/xattr.c:SyS_llistxattr
  - fs/xattr.c:SyS_listxattr
```
**Symbols:**

```
ffffffff8125aaa0-ffffffff8125ab45: path_listxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
ssize_t path_listxattr(const char *pathname, char *list, size_t size, unsigned int lookup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff8126de80)
Location: fs/xattr.c:661
Inline: False
Direct callers:
  - fs/xattr.c:SyS_llistxattr
  - fs/xattr.c:SyS_listxattr
```
**Symbols:**

```
ffffffff8126de80-ffffffff8126df25: path_listxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ssize_t path_listxattr(const char *pathname, char *list, size_t size, unsigned int lookup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff8127b690)
Location: fs/xattr.c:658
Inline: False
Direct callers:
  - fs/xattr.c:SyS_llistxattr
  - fs/xattr.c:SyS_listxattr
```
**Symbols:**

```
ffffffff8127b690-ffffffff8127b735: path_listxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t path_listxattr(const char *pathname, char *list, size_t size, unsigned int lookup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff8129e130)
Location: fs/xattr.c:659
Inline: False
Direct callers:
  - fs/xattr.c:SyS_llistxattr
  - fs/xattr.c:SyS_listxattr
```
**Symbols:**

```
ffffffff8129e130-ffffffff8129e1d5: path_listxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
ssize_t path_listxattr(const char *pathname, char *list, size_t size, unsigned int lookup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff812c47f0)
Location: fs/xattr.c:657
Inline: False
Direct callers:
  - fs/xattr.c:__ia32_sys_llistxattr
  - fs/xattr.c:__x64_sys_llistxattr
  - fs/xattr.c:__ia32_sys_listxattr
  - fs/xattr.c:__x64_sys_listxattr
```
**Symbols:**

```
ffffffff812c47f0-ffffffff812c4895: path_listxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ssize_t path_listxattr(const char *pathname, char *list, size_t size, unsigned int lookup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff812d99f0)
Location: fs/xattr.c:656
Inline: False
Direct callers:
  - fs/xattr.c:__ia32_sys_llistxattr
  - fs/xattr.c:__x64_sys_llistxattr
  - fs/xattr.c:__ia32_sys_listxattr
  - fs/xattr.c:__x64_sys_listxattr
```
**Symbols:**

```
ffffffff812d99f0-ffffffff812d9a95: path_listxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
ssize_t path_listxattr(const char *pathname, char *list, size_t size, unsigned int lookup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff812f7f70)
Location: fs/xattr.c:657
Inline: False
Direct callers:
  - fs/xattr.c:__ia32_sys_llistxattr
  - fs/xattr.c:__x64_sys_llistxattr
  - fs/xattr.c:__ia32_sys_listxattr
  - fs/xattr.c:__x64_sys_listxattr
```
**Symbols:**

```
ffffffff812f7f70-ffffffff812f800f: path_listxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ssize_t path_listxattr(const char *pathname, char *list, size_t size, unsigned int lookup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff81309b90)
Location: fs/xattr.c:657
Inline: False
Direct callers:
  - fs/xattr.c:__ia32_sys_llistxattr
  - fs/xattr.c:__x64_sys_llistxattr
  - fs/xattr.c:__ia32_sys_listxattr
  - fs/xattr.c:__x64_sys_listxattr
```
**Symbols:**

```
ffffffff81309b90-ffffffff81309c2f: path_listxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t path_listxattr(const char *pathname, char *list, size_t size, unsigned int lookup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff81342f60)
Location: fs/xattr.c:727
Inline: False
Direct callers:
  - fs/xattr.c:__ia32_sys_llistxattr
  - fs/xattr.c:__x64_sys_llistxattr
  - fs/xattr.c:__ia32_sys_listxattr
  - fs/xattr.c:__x64_sys_listxattr
```
**Symbols:**

```
ffffffff81342f60-ffffffff81342fff: path_listxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t path_listxattr(const char *pathname, char *list, size_t size, unsigned int lookup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff8134f410)
Location: fs/xattr.c:759
Inline: False
Direct callers:
  - fs/xattr.c:__ia32_sys_llistxattr
  - fs/xattr.c:__x64_sys_llistxattr
  - fs/xattr.c:__ia32_sys_listxattr
  - fs/xattr.c:__x64_sys_listxattr
```
**Symbols:**

```
ffffffff8134f410-ffffffff8134f4af: path_listxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t path_listxattr(const char *pathname, char *list, size_t size, unsigned int lookup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff81355f00)
Location: fs/xattr.c:786
Inline: False
Direct callers:
  - fs/xattr.c:__ia32_sys_llistxattr
  - fs/xattr.c:__x64_sys_llistxattr
  - fs/xattr.c:__ia32_sys_listxattr
  - fs/xattr.c:__x64_sys_listxattr
```
**Symbols:**

```
ffffffff81355f00-ffffffff81355f9f: path_listxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
ssize_t path_listxattr(const char *pathname, char *list, size_t size, unsigned int lookup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff813a4420)
Location: fs/xattr.c:787
Inline: False
Direct callers:
  - fs/xattr.c:__ia32_sys_llistxattr
  - fs/xattr.c:__x64_sys_llistxattr
  - fs/xattr.c:__ia32_sys_listxattr
  - fs/xattr.c:__x64_sys_listxattr
```
**Symbols:**

```
ffffffff813a4420-ffffffff813a44bf: path_listxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ssize_t path_listxattr(const char *pathname, char *list, size_t size, unsigned int lookup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff81428260)
Location: fs/xattr.c:839
Inline: False
Direct callers:
  - fs/xattr.c:__ia32_sys_llistxattr
  - fs/xattr.c:__x64_sys_llistxattr
  - fs/xattr.c:__ia32_sys_listxattr
  - fs/xattr.c:__x64_sys_listxattr
```
**Symbols:**

```
ffffffff81428260-ffffffff81428322: path_listxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t path_listxattr(const char *pathname, char *list, size_t size, unsigned int lookup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff814b4880)
Location: fs/xattr.c:859
Inline: False
Direct callers:
  - fs/xattr.c:__ia32_sys_llistxattr
  - fs/xattr.c:__x64_sys_llistxattr
  - fs/xattr.c:__ia32_sys_listxattr
  - fs/xattr.c:__x64_sys_listxattr
```
**Symbols:**

```
ffffffff814b4880-ffffffff814b4942: path_listxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t path_listxattr(const char *pathname, char *list, size_t size, unsigned int lookup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff814e9890)
Location: fs/xattr.c:856
Inline: False
Direct callers:
  - fs/xattr.c:__ia32_sys_llistxattr
  - fs/xattr.c:__x64_sys_llistxattr
  - fs/xattr.c:__ia32_sys_listxattr
  - fs/xattr.c:__x64_sys_listxattr
```
**Symbols:**

```
ffffffff814e9890-ffffffff814e9952: path_listxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t path_listxattr(const char *pathname, char *list, size_t size, unsigned int lookup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff8151d730)
Location: fs/xattr.c:856
Inline: False
Direct callers:
  - fs/xattr.c:__ia32_sys_llistxattr
  - fs/xattr.c:__x64_sys_llistxattr
  - fs/xattr.c:__ia32_sys_listxattr
  - fs/xattr.c:__x64_sys_listxattr
```
**Symbols:**

```
ffffffff8151d730-ffffffff8151d7f2: path_listxattr (STB_LOCAL)
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
ssize_t path_listxattr(const char *pathname, char *list, size_t size, unsigned int lookup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffff8000103bea00)
Location: fs/xattr.c:657
Inline: False
Direct callers:
  - fs/xattr.c:__arm64_sys_llistxattr
  - fs/xattr.c:__arm64_sys_listxattr
```
**Symbols:**

```
ffff8000103bea00-ffff8000103beac0: path_listxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t path_listxattr(const char *pathname, char *list, size_t size, unsigned int lookup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (c059b6cc)
Location: fs/xattr.c:657
Inline: False
Direct callers:
  - fs/xattr.c:__se_sys_llistxattr
  - fs/xattr.c:__se_sys_listxattr
```
**Symbols:**

```
c059b6cc-c059b788: path_listxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t path_listxattr(const char *pathname, char *list, size_t size, unsigned int lookup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (c0000000004bbe90)
Location: fs/xattr.c:657
Inline: False
Direct callers:
  - fs/xattr.c:__se_sys_llistxattr
  - fs/xattr.c:__se_sys_listxattr
```
**Symbols:**

```
c0000000004bbe90-c0000000004bbf8c: path_listxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ssize_t path_listxattr(const char *pathname, char *list, size_t size, unsigned int lookup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffe00027ef62)
Location: fs/xattr.c:657
Inline: False
Direct callers:
  - fs/xattr.c:__se_sys_llistxattr
  - fs/xattr.c:__se_sys_listxattr
```
**Symbols:**

```
ffffffe00027ef62-ffffffe00027efea: path_listxattr (STB_LOCAL)
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
ssize_t path_listxattr(const char *pathname, char *list, size_t size, unsigned int lookup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff81302170)
Location: fs/xattr.c:657
Inline: False
Direct callers:
  - fs/xattr.c:__ia32_sys_llistxattr
  - fs/xattr.c:__x64_sys_llistxattr
  - fs/xattr.c:__ia32_sys_listxattr
  - fs/xattr.c:__x64_sys_listxattr
```
**Symbols:**

```
ffffffff81302170-ffffffff8130220f: path_listxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ssize_t path_listxattr(const char *pathname, char *list, size_t size, unsigned int lookup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff812f2d90)
Location: fs/xattr.c:657
Inline: False
Direct callers:
  - fs/xattr.c:__ia32_sys_llistxattr
  - fs/xattr.c:__x64_sys_llistxattr
  - fs/xattr.c:__ia32_sys_listxattr
  - fs/xattr.c:__x64_sys_listxattr
```
**Symbols:**

```
ffffffff812f2d90-ffffffff812f2e2f: path_listxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ssize_t path_listxattr(const char *pathname, char *list, size_t size, unsigned int lookup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff812fff60)
Location: fs/xattr.c:657
Inline: False
Direct callers:
  - fs/xattr.c:__ia32_sys_llistxattr
  - fs/xattr.c:__x64_sys_llistxattr
  - fs/xattr.c:__ia32_sys_listxattr
  - fs/xattr.c:__x64_sys_listxattr
```
**Symbols:**

```
ffffffff812fff60-ffffffff812fffff: path_listxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ssize_t path_listxattr(const char *pathname, char *list, size_t size, unsigned int lookup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff813112a0)
Location: fs/xattr.c:657
Inline: False
Direct callers:
  - fs/xattr.c:__ia32_sys_llistxattr
  - fs/xattr.c:__x64_sys_llistxattr
  - fs/xattr.c:__ia32_sys_listxattr
  - fs/xattr.c:__x64_sys_listxattr
```
**Symbols:**

```
ffffffff813112a0-ffffffff8131133f: path_listxattr (STB_LOCAL)
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
