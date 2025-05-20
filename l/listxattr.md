# Function: <code>listxattr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
ssize_t listxattr(struct dentry *d, char *list, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff812323c0)
Location: fs/xattr.c:530
Inline: False
Direct callers:
  - fs/xattr.c:path_listxattr
  - fs/xattr.c:SyS_flistxattr
```
**Symbols:**

```
ffffffff812323c0-ffffffff812324ed: listxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
ssize_t listxattr(struct dentry *d, char *list, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff8125a9a0)
Location: fs/xattr.c:525
Inline: False
Direct callers:
  - fs/xattr.c:SyS_flistxattr
  - fs/xattr.c:path_listxattr
```
**Symbols:**

```
ffffffff8125a9a0-ffffffff8125aaa0: listxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
ssize_t listxattr(struct dentry *d, char *list, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff8126dd80)
Location: fs/xattr.c:630
Inline: False
Direct callers:
  - fs/xattr.c:SyS_flistxattr
  - fs/xattr.c:path_listxattr
```
**Symbols:**

```
ffffffff8126dd80-ffffffff8126de80: listxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ssize_t listxattr(struct dentry *d, char *list, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff8127b5b0)
Location: fs/xattr.c:630
Inline: False
Direct callers:
  - fs/xattr.c:SyS_flistxattr
  - fs/xattr.c:path_listxattr
```
**Symbols:**

```
ffffffff8127b5b0-ffffffff8127b68e: listxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t listxattr(struct dentry *d, char *list, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff8129e050)
Location: fs/xattr.c:631
Inline: False
Direct callers:
  - fs/xattr.c:SyS_flistxattr
  - fs/xattr.c:path_listxattr
```
**Symbols:**

```
ffffffff8129e050-ffffffff8129e12e: listxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
ssize_t listxattr(struct dentry *d, char *list, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff812c4710)
Location: fs/xattr.c:629
Inline: False
Direct callers:
  - fs/xattr.c:__ia32_sys_flistxattr
  - fs/xattr.c:__x64_sys_flistxattr
  - fs/xattr.c:path_listxattr
```
**Symbols:**

```
ffffffff812c4710-ffffffff812c47ee: listxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ssize_t listxattr(struct dentry *d, char *list, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff812d9910)
Location: fs/xattr.c:628
Inline: False
Direct callers:
  - fs/xattr.c:__ia32_sys_flistxattr
  - fs/xattr.c:__x64_sys_flistxattr
  - fs/xattr.c:path_listxattr
```
**Symbols:**

```
ffffffff812d9910-ffffffff812d99ee: listxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
ssize_t listxattr(struct dentry *d, char *list, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff812f7e90)
Location: fs/xattr.c:629
Inline: False
Direct callers:
  - fs/xattr.c:__ia32_sys_flistxattr
  - fs/xattr.c:__x64_sys_flistxattr
  - fs/xattr.c:path_listxattr
```
**Symbols:**

```
ffffffff812f7e90-ffffffff812f7f6b: listxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ssize_t listxattr(struct dentry *d, char *list, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff81309a90)
Location: fs/xattr.c:629
Inline: False
Direct callers:
  - fs/xattr.c:__ia32_sys_flistxattr
  - fs/xattr.c:__x64_sys_flistxattr
  - fs/xattr.c:path_listxattr
```
**Symbols:**

```
ffffffff81309a90-ffffffff81309b83: listxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t listxattr(struct dentry *d, char *list, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff81342e60)
Location: fs/xattr.c:699
Inline: False
Direct callers:
  - fs/xattr.c:__ia32_sys_flistxattr
  - fs/xattr.c:__x64_sys_flistxattr
  - fs/xattr.c:path_listxattr
```
**Symbols:**

```
ffffffff81342e60-ffffffff81342f53: listxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t listxattr(struct dentry *d, char *list, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff8134f310)
Location: fs/xattr.c:731
Inline: False
Direct callers:
  - fs/xattr.c:__ia32_sys_flistxattr
  - fs/xattr.c:__x64_sys_flistxattr
  - fs/xattr.c:path_listxattr
```
**Symbols:**

```
ffffffff8134f310-ffffffff8134f403: listxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t listxattr(struct dentry *d, char *list, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff81355e00)
Location: fs/xattr.c:758
Inline: False
Direct callers:
  - fs/xattr.c:__ia32_sys_flistxattr
  - fs/xattr.c:__x64_sys_flistxattr
  - fs/xattr.c:path_listxattr
```
**Symbols:**

```
ffffffff81355e00-ffffffff81355ef1: listxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
ssize_t listxattr(struct dentry *d, char *list, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff813a4320)
Location: fs/xattr.c:759
Inline: False
Direct callers:
  - fs/xattr.c:__ia32_sys_flistxattr
  - fs/xattr.c:__x64_sys_flistxattr
  - fs/xattr.c:path_listxattr
```
**Symbols:**

```
ffffffff813a4320-ffffffff813a4411: listxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ssize_t listxattr(struct dentry *d, char *list, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff81428170)
Location: fs/xattr.c:811
Inline: False
Direct callers:
  - fs/xattr.c:__ia32_sys_flistxattr
  - fs/xattr.c:__x64_sys_flistxattr
  - fs/xattr.c:path_listxattr
```
**Symbols:**

```
ffffffff81428170-ffffffff8142825e: listxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t listxattr(struct dentry *d, char *list, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff814b4780)
Location: fs/xattr.c:831
Inline: False
Direct callers:
  - fs/xattr.c:__ia32_sys_flistxattr
  - fs/xattr.c:__x64_sys_flistxattr
  - fs/xattr.c:path_listxattr
```
**Symbols:**

```
ffffffff814b4780-ffffffff814b486e: listxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t listxattr(struct dentry *d, char *list, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff814e9790)
Location: fs/xattr.c:828
Inline: False
Direct callers:
  - fs/xattr.c:__ia32_sys_flistxattr
  - fs/xattr.c:__x64_sys_flistxattr
  - fs/xattr.c:path_listxattr
```
**Symbols:**

```
ffffffff814e9790-ffffffff814e987e: listxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t listxattr(struct dentry *d, char *list, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff8151d630)
Location: fs/xattr.c:828
Inline: False
Direct callers:
  - fs/xattr.c:__ia32_sys_flistxattr
  - fs/xattr.c:__x64_sys_flistxattr
  - fs/xattr.c:path_listxattr
```
**Symbols:**

```
ffffffff8151d630-ffffffff8151d71e: listxattr (STB_LOCAL)
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
ssize_t listxattr(struct dentry *d, char *list, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffff8000103be898)
Location: fs/xattr.c:629
Inline: False
Direct callers:
  - fs/xattr.c:__arm64_sys_flistxattr
  - fs/xattr.c:path_listxattr
```
**Symbols:**

```
ffff8000103be898-ffff8000103bea00: listxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t listxattr(struct dentry *d, char *list, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (c059b5c4)
Location: fs/xattr.c:629
Inline: False
Direct callers:
  - fs/xattr.c:__se_sys_flistxattr
  - fs/xattr.c:path_listxattr
```
**Symbols:**

```
c059b5c4-c059b6cc: listxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t listxattr(struct dentry *d, char *list, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (c0000000004bbcf0)
Location: fs/xattr.c:629
Inline: False
Direct callers:
  - fs/xattr.c:__se_sys_flistxattr
  - fs/xattr.c:path_listxattr
```
**Symbols:**

```
c0000000004bbcf0-c0000000004bbe84: listxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ssize_t listxattr(struct dentry *d, char *list, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffe00027ee76)
Location: fs/xattr.c:629
Inline: False
Direct callers:
  - fs/xattr.c:__se_sys_flistxattr
  - fs/xattr.c:path_listxattr
```
**Symbols:**

```
ffffffe00027ee76-ffffffe00027ef62: listxattr (STB_LOCAL)
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
ssize_t listxattr(struct dentry *d, char *list, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff81302070)
Location: fs/xattr.c:629
Inline: False
Direct callers:
  - fs/xattr.c:__ia32_sys_flistxattr
  - fs/xattr.c:__x64_sys_flistxattr
  - fs/xattr.c:path_listxattr
```
**Symbols:**

```
ffffffff81302070-ffffffff81302163: listxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ssize_t listxattr(struct dentry *d, char *list, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff812f2c90)
Location: fs/xattr.c:629
Inline: False
Direct callers:
  - fs/xattr.c:__ia32_sys_flistxattr
  - fs/xattr.c:__x64_sys_flistxattr
  - fs/xattr.c:path_listxattr
```
**Symbols:**

```
ffffffff812f2c90-ffffffff812f2d83: listxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ssize_t listxattr(struct dentry *d, char *list, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff812ffe60)
Location: fs/xattr.c:629
Inline: False
Direct callers:
  - fs/xattr.c:__ia32_sys_flistxattr
  - fs/xattr.c:__x64_sys_flistxattr
  - fs/xattr.c:path_listxattr
```
**Symbols:**

```
ffffffff812ffe60-ffffffff812fff53: listxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ssize_t listxattr(struct dentry *d, char *list, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff813111a0)
Location: fs/xattr.c:629
Inline: False
Direct callers:
  - fs/xattr.c:__ia32_sys_flistxattr
  - fs/xattr.c:__x64_sys_flistxattr
  - fs/xattr.c:path_listxattr
```
**Symbols:**

```
ffffffff813111a0-ffffffff81311293: listxattr (STB_LOCAL)
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
