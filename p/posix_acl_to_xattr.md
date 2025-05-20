# Function: <code>posix_acl_to_xattr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int posix_acl_to_xattr(struct user_namespace *user_ns, const struct posix_acl *acl, void *buffer, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff8126dc60)
Location: fs/posix_acl.c:744
Inline: False
Direct callers:
  - fs/posix_acl.c:posix_acl_xattr_get
```
**Symbols:**

```
ffffffff8126dc60-ffffffff8126dd30: posix_acl_to_xattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int posix_acl_to_xattr(struct user_namespace *user_ns, const struct posix_acl *acl, void *buffer, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff812992f0)
Location: fs/posix_acl.c:770
Inline: False
Direct callers:
  - fs/posix_acl.c:posix_acl_xattr_get
```
**Symbols:**

```
ffffffff812992f0-ffffffff812993c3: posix_acl_to_xattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int posix_acl_to_xattr(struct user_namespace *user_ns, const struct posix_acl *acl, void *buffer, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff812add60)
Location: fs/posix_acl.c:802
Inline: False
Direct callers:
  - fs/posix_acl.c:posix_acl_xattr_get
  - fs/fuse/acl.c:fuse_set_acl
```
**Symbols:**

```
ffffffff812add60-ffffffff812ade33: posix_acl_to_xattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int posix_acl_to_xattr(struct user_namespace *user_ns, const struct posix_acl *acl, void *buffer, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff812bb1e0)
Location: fs/posix_acl.c:793
Inline: False
Direct callers:
  - fs/posix_acl.c:posix_acl_xattr_get
  - fs/fuse/acl.c:fuse_set_acl
```
**Symbols:**

```
ffffffff812bb1e0-ffffffff812bb2b3: posix_acl_to_xattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int posix_acl_to_xattr(struct user_namespace *user_ns, const struct posix_acl *acl, void *buffer, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff812dead0)
Location: fs/posix_acl.c:793
Inline: False
Direct callers:
  - fs/posix_acl.c:posix_acl_xattr_get
  - fs/fuse/acl.c:fuse_set_acl
```
**Symbols:**

```
ffffffff812dead0-ffffffff812deba3: posix_acl_to_xattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int posix_acl_to_xattr(struct user_namespace *user_ns, const struct posix_acl *acl, void *buffer, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff8130ac20)
Location: fs/posix_acl.c:793
Inline: False
Direct callers:
  - fs/posix_acl.c:posix_acl_xattr_get
  - fs/fuse/acl.c:fuse_set_acl
```
**Symbols:**

```
ffffffff8130ac20-ffffffff8130acf6: posix_acl_to_xattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int posix_acl_to_xattr(struct user_namespace *user_ns, const struct posix_acl *acl, void *buffer, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff81320460)
Location: fs/posix_acl.c:793
Inline: False
Direct callers:
  - fs/posix_acl.c:posix_acl_xattr_get
  - fs/fuse/acl.c:fuse_set_acl
```
**Symbols:**

```
ffffffff81320460-ffffffff81320536: posix_acl_to_xattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int posix_acl_to_xattr(struct user_namespace *user_ns, const struct posix_acl *acl, void *buffer, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff81347d20)
Location: fs/posix_acl.c:794
Inline: False
Direct callers:
  - fs/posix_acl.c:posix_acl_xattr_get
  - fs/fuse/acl.c:fuse_set_acl
```
**Symbols:**

```
ffffffff81347d20-ffffffff81347df6: posix_acl_to_xattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int posix_acl_to_xattr(struct user_namespace *user_ns, const struct posix_acl *acl, void *buffer, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff8135ffc0)
Location: fs/posix_acl.c:794
Inline: False
Direct callers:
  - fs/posix_acl.c:posix_acl_xattr_get
  - fs/fuse/acl.c:fuse_set_acl
```
**Symbols:**

```
ffffffff8135ffc0-ffffffff81360096: posix_acl_to_xattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int posix_acl_to_xattr(struct user_namespace *user_ns, const struct posix_acl *acl, void *buffer, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff813a5a00)
Location: fs/posix_acl.c:797
Inline: False
Direct callers:
  - fs/posix_acl.c:posix_acl_xattr_get
  - fs/fuse/acl.c:fuse_set_acl
```
**Symbols:**

```
ffffffff813a5a00-ffffffff813a5ad3: posix_acl_to_xattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int posix_acl_to_xattr(struct user_namespace *user_ns, const struct posix_acl *acl, void *buffer, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff813b6740)
Location: fs/posix_acl.c:797
Inline: False
Direct callers:
  - fs/posix_acl.c:posix_acl_xattr_get
  - fs/fuse/acl.c:fuse_set_acl
```
**Symbols:**

```
ffffffff813b6740-ffffffff813b6813: posix_acl_to_xattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int posix_acl_to_xattr(struct user_namespace *user_ns, const struct posix_acl *acl, void *buffer, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff813bd720)
Location: fs/posix_acl.c:839
Inline: False
Direct callers:
  - fs/posix_acl.c:posix_acl_xattr_get
  - fs/fuse/acl.c:fuse_set_acl
```
**Symbols:**

```
ffffffff813bd720-ffffffff813bd7f2: posix_acl_to_xattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int posix_acl_to_xattr(struct user_namespace *user_ns, const struct posix_acl *acl, void *buffer, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff8140d4e0)
Location: fs/posix_acl.c:850
Inline: False
Direct callers:
  - fs/posix_acl.c:posix_acl_xattr_get
  - fs/fuse/acl.c:fuse_set_acl
```
**Symbols:**

```
ffffffff8140d4e0-ffffffff8140d5b2: posix_acl_to_xattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int posix_acl_to_xattr(struct user_namespace *user_ns, const struct posix_acl *acl, void *buffer, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff81482920)
Location: fs/posix_acl.c:864
Inline: False
Direct callers:
  - fs/posix_acl.c:posix_acl_xattr_get
  - fs/fuse/acl.c:fuse_set_acl
```
**Symbols:**

```
ffffffff81482920-ffffffff814829fe: posix_acl_to_xattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int posix_acl_to_xattr(struct user_namespace *user_ns, const struct posix_acl *acl, void *buffer, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff81515700)
Location: fs/posix_acl.c:834
Inline: False
Direct callers:
  - fs/fuse/acl.c:fuse_set_acl
```
**Symbols:**

```
ffffffff81515700-ffffffff815157de: posix_acl_to_xattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int posix_acl_to_xattr(struct user_namespace *user_ns, const struct posix_acl *acl, void *buffer, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff8154d100)
Location: fs/posix_acl.c:835
Inline: False
Direct callers:
  - fs/fuse/acl.c:fuse_set_acl
```
**Symbols:**

```
ffffffff8154d100-ffffffff8154d1e0: posix_acl_to_xattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int posix_acl_to_xattr(struct user_namespace *user_ns, const struct posix_acl *acl, void *buffer, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff81582f30)
Location: fs/posix_acl.c:835
Inline: False
Direct callers:
  - fs/fuse/acl.c:fuse_set_acl
```
**Symbols:**

```
ffffffff81582f30-ffffffff81583010: posix_acl_to_xattr (STB_GLOBAL)
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
int posix_acl_to_xattr(struct user_namespace *user_ns, const struct posix_acl *acl, void *buffer, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffff800010426188)
Location: fs/posix_acl.c:794
Inline: False
Direct callers:
  - fs/posix_acl.c:posix_acl_xattr_get
  - fs/fuse/acl.c:fuse_set_acl
```
**Symbols:**

```
ffff800010426188-ffff800010426288: posix_acl_to_xattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int posix_acl_to_xattr(struct user_namespace *user_ns, const struct posix_acl *acl, void *buffer, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (c05eee04)
Location: fs/posix_acl.c:794
Inline: False
Direct callers:
  - fs/posix_acl.c:posix_acl_xattr_get
  - fs/fuse/acl.c:fuse_set_acl
```
**Symbols:**

```
c05eee04-c05eeedc: posix_acl_to_xattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int posix_acl_to_xattr(struct user_namespace *user_ns, const struct posix_acl *acl, void *buffer, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (c000000000535430)
Location: fs/posix_acl.c:794
Inline: False
Direct callers:
  - fs/posix_acl.c:posix_acl_xattr_get
  - fs/fuse/acl.c:fuse_set_acl
```
**Symbols:**

```
c000000000535430-c000000000535594: posix_acl_to_xattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int posix_acl_to_xattr(struct user_namespace *user_ns, const struct posix_acl *acl, void *buffer, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffe0002c4c7e)
Location: fs/posix_acl.c:794
Inline: False
Direct callers:
  - fs/posix_acl.c:posix_acl_xattr_get
  - fs/fuse/acl.c:fuse_set_acl
```
**Symbols:**

```
ffffffe0002c4c7e-ffffffe0002c4d52: posix_acl_to_xattr (STB_GLOBAL)
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
int posix_acl_to_xattr(struct user_namespace *user_ns, const struct posix_acl *acl, void *buffer, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff813585a0)
Location: fs/posix_acl.c:794
Inline: False
Direct callers:
  - fs/posix_acl.c:posix_acl_xattr_get
  - fs/fuse/acl.c:fuse_set_acl
```
**Symbols:**

```
ffffffff813585a0-ffffffff81358676: posix_acl_to_xattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int posix_acl_to_xattr(struct user_namespace *user_ns, const struct posix_acl *acl, void *buffer, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff81349250)
Location: fs/posix_acl.c:794
Inline: False
Direct callers:
  - fs/posix_acl.c:posix_acl_xattr_get
  - fs/fuse/acl.c:fuse_set_acl
```
**Symbols:**

```
ffffffff81349250-ffffffff81349326: posix_acl_to_xattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int posix_acl_to_xattr(struct user_namespace *user_ns, const struct posix_acl *acl, void *buffer, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff81356070)
Location: fs/posix_acl.c:794
Inline: False
Direct callers:
  - fs/posix_acl.c:posix_acl_xattr_get
  - fs/fuse/acl.c:fuse_set_acl
```
**Symbols:**

```
ffffffff81356070-ffffffff81356146: posix_acl_to_xattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int posix_acl_to_xattr(struct user_namespace *user_ns, const struct posix_acl *acl, void *buffer, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff81369740)
Location: fs/posix_acl.c:794
Inline: False
Direct callers:
  - fs/posix_acl.c:posix_acl_xattr_get
  - fs/fuse/acl.c:fuse_set_acl
```
**Symbols:**

```
ffffffff81369740-ffffffff81369816: posix_acl_to_xattr (STB_GLOBAL)
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
