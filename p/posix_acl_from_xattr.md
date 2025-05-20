# Function: <code>posix_acl_from_xattr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct posix_acl *posix_acl_from_xattr(struct user_namespace *user_ns, const void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff8126e3e0)
Location: fs/posix_acl.c:675
Inline: False
Direct callers:
  - fs/posix_acl.c:posix_acl_xattr_set
```
**Symbols:**

```
ffffffff8126e3e0-ffffffff8126e549: posix_acl_from_xattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct posix_acl *posix_acl_from_xattr(struct user_namespace *user_ns, const void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff81299970)
Location: fs/posix_acl.c:701
Inline: False
Direct callers:
  - fs/posix_acl.c:posix_acl_xattr_set
```
**Symbols:**

```
ffffffff81299970-ffffffff81299acf: posix_acl_from_xattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct posix_acl *posix_acl_from_xattr(struct user_namespace *user_ns, const void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff812ae490)
Location: fs/posix_acl.c:733
Inline: False
Direct callers:
  - fs/posix_acl.c:posix_acl_xattr_set
  - fs/fuse/acl.c:fuse_get_acl
```
**Symbols:**

```
ffffffff812ae490-ffffffff812ae5ef: posix_acl_from_xattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct posix_acl *posix_acl_from_xattr(struct user_namespace *user_ns, const void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff812bb440)
Location: fs/posix_acl.c:724
Inline: False
Direct callers:
  - fs/posix_acl.c:posix_acl_xattr_set
  - fs/fuse/acl.c:fuse_get_acl
```
**Symbols:**

```
ffffffff812bb440-ffffffff812bb5a3: posix_acl_from_xattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct posix_acl *posix_acl_from_xattr(struct user_namespace *user_ns, const void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff812ded30)
Location: fs/posix_acl.c:724
Inline: False
Direct callers:
  - fs/posix_acl.c:posix_acl_xattr_set
  - fs/fuse/acl.c:fuse_get_acl
```
**Symbols:**

```
ffffffff812ded30-ffffffff812dee93: posix_acl_from_xattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct posix_acl *posix_acl_from_xattr(struct user_namespace *user_ns, const void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff8130b620)
Location: fs/posix_acl.c:724
Inline: False
Direct callers:
  - fs/posix_acl.c:posix_acl_xattr_set
  - fs/fuse/acl.c:fuse_get_acl
```
**Symbols:**

```
ffffffff8130b620-ffffffff8130b782: posix_acl_from_xattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct posix_acl *posix_acl_from_xattr(struct user_namespace *user_ns, const void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff81320b90)
Location: fs/posix_acl.c:724
Inline: False
Direct callers:
  - fs/posix_acl.c:posix_acl_xattr_set
  - fs/fuse/acl.c:fuse_get_acl
```
**Symbols:**

```
ffffffff81320b90-ffffffff81320cf2: posix_acl_from_xattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct posix_acl *posix_acl_from_xattr(struct user_namespace *user_ns, const void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff81348440)
Location: fs/posix_acl.c:725
Inline: False
Direct callers:
  - fs/posix_acl.c:posix_acl_xattr_set
  - fs/fuse/acl.c:fuse_get_acl
```
**Symbols:**

```
ffffffff81348440-ffffffff81348597: posix_acl_from_xattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct posix_acl *posix_acl_from_xattr(struct user_namespace *user_ns, const void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff813606e0)
Location: fs/posix_acl.c:725
Inline: False
Direct callers:
  - fs/posix_acl.c:posix_acl_xattr_set
  - fs/fuse/acl.c:fuse_get_acl
```
**Symbols:**

```
ffffffff813606e0-ffffffff81360837: posix_acl_from_xattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct posix_acl *posix_acl_from_xattr(struct user_namespace *user_ns, const void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff813a6670)
Location: fs/posix_acl.c:728
Inline: False
Direct callers:
  - fs/posix_acl.c:posix_acl_xattr_set
  - fs/fuse/acl.c:fuse_get_acl
```
**Symbols:**

```
ffffffff813a6670-ffffffff813a67fd: posix_acl_from_xattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct posix_acl *posix_acl_from_xattr(struct user_namespace *user_ns, const void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff813b7400)
Location: fs/posix_acl.c:728
Inline: False
Direct callers:
  - fs/posix_acl.c:posix_acl_xattr_set
  - fs/fuse/acl.c:fuse_get_acl
```
**Symbols:**

```
ffffffff813b7400-ffffffff813b758d: posix_acl_from_xattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct posix_acl *posix_acl_from_xattr(struct user_namespace *user_ns, const void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff813be0a0)
Location: fs/posix_acl.c:770
Inline: False
Direct callers:
  - fs/posix_acl.c:posix_acl_xattr_set
  - fs/fuse/acl.c:fuse_get_acl
```
**Symbols:**

```
ffffffff813be0a0-ffffffff813be21f: posix_acl_from_xattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct posix_acl *posix_acl_from_xattr(struct user_namespace *user_ns, const void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff8140ded0)
Location: fs/posix_acl.c:781
Inline: False
Direct callers:
  - fs/posix_acl.c:posix_acl_xattr_set
  - fs/fuse/acl.c:fuse_get_acl
  - security/integrity/evm/evm_main.c:evm_xattr_change
```
**Symbols:**

```
ffffffff8140ded0-ffffffff8140e04f: posix_acl_from_xattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct posix_acl *posix_acl_from_xattr(struct user_namespace *user_ns, const void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff81483490)
Location: fs/posix_acl.c:795
Inline: False
Direct callers:
  - fs/posix_acl.c:posix_acl_xattr_set
  - fs/fuse/acl.c:fuse_get_acl
  - security/integrity/evm/evm_main.c:evm_xattr_change
```
**Symbols:**

```
ffffffff81483490-ffffffff81483611: posix_acl_from_xattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct posix_acl *posix_acl_from_xattr(struct user_namespace *userns, const void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff815164b0)
Location: fs/posix_acl.c:774
Inline: False
Direct callers:
  - fs/posix_acl.c:do_set_acl
```
**Symbols:**

```
ffffffff815164b0-ffffffff8151662d: posix_acl_from_xattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct posix_acl *posix_acl_from_xattr(struct user_namespace *userns, const void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff8154de30)
Location: fs/posix_acl.c:775
Inline: False
Direct callers:
  - fs/posix_acl.c:do_set_acl
```
**Symbols:**

```
ffffffff8154de30-ffffffff8154df86: posix_acl_from_xattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct posix_acl *posix_acl_from_xattr(struct user_namespace *userns, const void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff81583c80)
Location: fs/posix_acl.c:775
Inline: False
Direct callers:
  - fs/posix_acl.c:do_set_acl
```
**Symbols:**

```
ffffffff81583c80-ffffffff81583dd6: posix_acl_from_xattr (STB_GLOBAL)
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
struct posix_acl *posix_acl_from_xattr(struct user_namespace *user_ns, const void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffff800010426da8)
Location: fs/posix_acl.c:725
Inline: False
Direct callers:
  - fs/posix_acl.c:posix_acl_xattr_set
  - fs/fuse/acl.c:fuse_get_acl
```
**Symbols:**

```
ffff800010426da8-ffff800010426f24: posix_acl_from_xattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct posix_acl *posix_acl_from_xattr(struct user_namespace *user_ns, const void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (c05ef630)
Location: fs/posix_acl.c:725
Inline: False
Direct callers:
  - fs/posix_acl.c:posix_acl_xattr_set
  - fs/fuse/acl.c:fuse_get_acl
```
**Symbols:**

```
c05ef630-c05ef7bc: posix_acl_from_xattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct posix_acl *posix_acl_from_xattr(struct user_namespace *user_ns, const void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (c000000000536900)
Location: fs/posix_acl.c:725
Inline: False
Direct callers:
  - fs/posix_acl.c:posix_acl_xattr_set
  - fs/fuse/acl.c:fuse_get_acl
```
**Symbols:**

```
c000000000536900-c000000000536ba8: posix_acl_from_xattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct posix_acl *posix_acl_from_xattr(struct user_namespace *user_ns, const void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffe0002c5088)
Location: fs/posix_acl.c:725
Inline: False
Direct callers:
  - fs/posix_acl.c:posix_acl_xattr_set
  - fs/fuse/acl.c:fuse_get_acl
```
**Symbols:**

```
ffffffe0002c5088-ffffffe0002c51a2: posix_acl_from_xattr (STB_GLOBAL)
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
struct posix_acl *posix_acl_from_xattr(struct user_namespace *user_ns, const void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff81358cc0)
Location: fs/posix_acl.c:725
Inline: False
Direct callers:
  - fs/posix_acl.c:posix_acl_xattr_set
  - fs/fuse/acl.c:fuse_get_acl
```
**Symbols:**

```
ffffffff81358cc0-ffffffff81358e17: posix_acl_from_xattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct posix_acl *posix_acl_from_xattr(struct user_namespace *user_ns, const void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff81349970)
Location: fs/posix_acl.c:725
Inline: False
Direct callers:
  - fs/posix_acl.c:posix_acl_xattr_set
  - fs/fuse/acl.c:fuse_get_acl
```
**Symbols:**

```
ffffffff81349970-ffffffff81349ac7: posix_acl_from_xattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct posix_acl *posix_acl_from_xattr(struct user_namespace *user_ns, const void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff81356790)
Location: fs/posix_acl.c:725
Inline: False
Direct callers:
  - fs/posix_acl.c:posix_acl_xattr_set
  - fs/fuse/acl.c:fuse_get_acl
```
**Symbols:**

```
ffffffff81356790-ffffffff813568e7: posix_acl_from_xattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct posix_acl *posix_acl_from_xattr(struct user_namespace *user_ns, const void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff81369e70)
Location: fs/posix_acl.c:725
Inline: False
Direct callers:
  - fs/posix_acl.c:posix_acl_xattr_set
  - fs/fuse/acl.c:fuse_get_acl
```
**Symbols:**

```
ffffffff81369e70-ffffffff81369fc7: posix_acl_from_xattr (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct user_namespace *userns</code>
</li>
<li>
<b>Param removed. </b>
<code>struct user_namespace *user_ns</code>
</li>
</ul>
</details>
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
