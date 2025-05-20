# Function: <code>posix_acl_fix_xattr_to_user</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int posix_acl_fix_xattr_to_user(struct user_namespace *source_ns, void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff8126e960)
Location: fs/posix_acl.c:662
Inline: False
Direct callers:
  - fs/xattr.c:getxattr
```
**Symbols:**

```
ffffffff8126e960-ffffffff8126e99b: posix_acl_fix_xattr_to_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void posix_acl_fix_xattr_to_user(void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff8129a0c0)
Location: fs/posix_acl.c:691
Inline: False
Direct callers:
  - fs/xattr.c:getxattr
```
**Symbols:**

```
ffffffff8129a0c0-ffffffff8129a0f4: posix_acl_fix_xattr_to_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void posix_acl_fix_xattr_to_user(void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff812aebe0)
Location: fs/posix_acl.c:723
Inline: False
Direct callers:
  - fs/xattr.c:getxattr
```
**Symbols:**

```
ffffffff812aebe0-ffffffff812aec14: posix_acl_fix_xattr_to_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void posix_acl_fix_xattr_to_user(void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff812bc000)
Location: fs/posix_acl.c:712
Inline: False
Direct callers:
  - fs/xattr.c:getxattr
```
**Symbols:**

```
ffffffff812bc000-ffffffff812bc03f: posix_acl_fix_xattr_to_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void posix_acl_fix_xattr_to_user(void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff812df900)
Location: fs/posix_acl.c:712
Inline: False
Direct callers:
  - fs/xattr.c:getxattr
```
**Symbols:**

```
ffffffff812df900-ffffffff812df93d: posix_acl_fix_xattr_to_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void posix_acl_fix_xattr_to_user(void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff8130bb30)
Location: fs/posix_acl.c:712
Inline: False
Direct callers:
  - fs/xattr.c:getxattr
```
**Symbols:**

```
ffffffff8130bb30-ffffffff8130bb6d: posix_acl_fix_xattr_to_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void posix_acl_fix_xattr_to_user(void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff81321390)
Location: fs/posix_acl.c:712
Inline: False
Direct callers:
  - fs/xattr.c:getxattr
```
**Symbols:**

```
ffffffff81321390-ffffffff813213cd: posix_acl_fix_xattr_to_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void posix_acl_fix_xattr_to_user(void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff81348c30)
Location: fs/posix_acl.c:713
Inline: False
Direct callers:
  - fs/xattr.c:getxattr
```
**Symbols:**

```
ffffffff81348c30-ffffffff81348c6e: posix_acl_fix_xattr_to_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void posix_acl_fix_xattr_to_user(void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff81360ed0)
Location: fs/posix_acl.c:713
Inline: False
Direct callers:
  - fs/xattr.c:getxattr
```
**Symbols:**

```
ffffffff81360ed0-ffffffff81360f0e: posix_acl_fix_xattr_to_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void posix_acl_fix_xattr_to_user(void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff813a6c80)
Location: fs/posix_acl.c:716
Inline: False
Direct callers:
  - fs/xattr.c:getxattr
```
**Symbols:**

```
ffffffff813a6c80-ffffffff813a6cbe: posix_acl_fix_xattr_to_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void posix_acl_fix_xattr_to_user(void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff813b7a40)
Location: fs/posix_acl.c:716
Inline: False
Direct callers:
  - fs/xattr.c:getxattr
```
**Symbols:**

```
ffffffff813b7a40-ffffffff813b7a7e: posix_acl_fix_xattr_to_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void posix_acl_fix_xattr_to_user(struct user_namespace *mnt_userns, void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff813beab0)
Location: fs/posix_acl.c:756
Inline: False
Direct callers:
  - fs/xattr.c:getxattr
```
**Symbols:**

```
ffffffff813beab0-ffffffff813beb00: posix_acl_fix_xattr_to_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void posix_acl_fix_xattr_to_user(struct user_namespace *mnt_userns, void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff8140e8e0)
Location: fs/posix_acl.c:767
Inline: False
Direct callers:
  - fs/xattr.c:getxattr
```
**Symbols:**

```
ffffffff8140e8e0-ffffffff8140e930: posix_acl_fix_xattr_to_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void posix_acl_fix_xattr_to_user(struct user_namespace *mnt_userns, struct inode *inode, void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff81484020)
Location: fs/posix_acl.c:776
Inline: False
Direct callers:
  - fs/xattr.c:do_getxattr
```
**Symbols:**

```
ffffffff81484020-ffffffff814840ad: posix_acl_fix_xattr_to_user (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void posix_acl_fix_xattr_to_user(void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffff8000104273b8)
Location: fs/posix_acl.c:713
Inline: False
Direct callers:
  - fs/xattr.c:getxattr
```
**Symbols:**

```
ffff8000104273b8-ffff800010427408: posix_acl_fix_xattr_to_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void posix_acl_fix_xattr_to_user(void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (c05eff20)
Location: fs/posix_acl.c:713
Inline: False
Direct callers:
  - fs/xattr.c:getxattr
```
**Symbols:**

```
c05eff20-c05eff70: posix_acl_fix_xattr_to_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void posix_acl_fix_xattr_to_user(void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (c000000000537010)
Location: fs/posix_acl.c:713
Inline: False
Direct callers:
  - fs/xattr.c:getxattr
```
**Symbols:**

```
c000000000537010-c00000000053704c: posix_acl_fix_xattr_to_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void posix_acl_fix_xattr_to_user(void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffe0002c59e8)
Location: fs/posix_acl.c:713
Inline: False
Direct callers:
  - fs/xattr.c:getxattr
```
**Symbols:**

```
ffffffe0002c59e8-ffffffe0002c5a2c: posix_acl_fix_xattr_to_user (STB_GLOBAL)
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
void posix_acl_fix_xattr_to_user(void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff813594b0)
Location: fs/posix_acl.c:713
Inline: False
Direct callers:
  - fs/xattr.c:getxattr
```
**Symbols:**

```
ffffffff813594b0-ffffffff813594ee: posix_acl_fix_xattr_to_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void posix_acl_fix_xattr_to_user(void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff8134a160)
Location: fs/posix_acl.c:713
Inline: False
Direct callers:
  - fs/xattr.c:getxattr
```
**Symbols:**

```
ffffffff8134a160-ffffffff8134a19e: posix_acl_fix_xattr_to_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void posix_acl_fix_xattr_to_user(void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff81356f80)
Location: fs/posix_acl.c:713
Inline: False
Direct callers:
  - fs/xattr.c:getxattr
```
**Symbols:**

```
ffffffff81356f80-ffffffff81356fbe: posix_acl_fix_xattr_to_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void posix_acl_fix_xattr_to_user(void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff8136a660)
Location: fs/posix_acl.c:713
Inline: False
Direct callers:
  - fs/xattr.c:getxattr
```
**Symbols:**

```
ffffffff8136a660-ffffffff8136a69e: posix_acl_fix_xattr_to_user (STB_GLOBAL)
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
<b>Param removed. </b>
<code>struct user_namespace *source_ns</code>
</li>
<li>
<b>Param reordered. </b>
<code>source_ns, value, size</code> ➡️ <code>value, size</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
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
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct user_namespace *mnt_userns</code>
</li>
<li>
<b>Param reordered. </b>
<code>value, size</code> ➡️ <code>mnt_userns, value, size</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct inode *inode</code>
</li>
<li>
<b>Param reordered. </b>
<code>mnt_userns, value, size</code> ➡️ <code>mnt_userns, inode, value, size</code>
</li>
</ul>
</details>
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
