# Function: <code>posix_acl_fix_xattr_userns</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int posix_acl_fix_xattr_userns(struct user_namespace *to, struct user_namespace *from, void *value, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff8126dba0)
Location: fs/posix_acl.c:598
Inline: False
Direct callers:
  - fs/posix_acl.c:posix_acl_fix_xattr_from_user
  - fs/posix_acl.c:posix_acl_fix_xattr_to_user
```
**Symbols:**

```
ffffffff8126dba0-ffffffff8126dc57: posix_acl_fix_xattr_userns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int posix_acl_fix_xattr_userns(struct user_namespace *to, struct user_namespace *from, void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff81299410)
Location: fs/posix_acl.c:632
Inline: False
Direct callers:
  - fs/posix_acl.c:posix_acl_fix_xattr_to_user
  - fs/posix_acl.c:posix_acl_fix_xattr_from_user
  - fs/fuse/dir.c:fuse_getxattr
  - fs/fuse/dir.c:fuse_setxattr
```
**Symbols:**

```
ffffffff81299410-ffffffff81299517: posix_acl_fix_xattr_userns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int posix_acl_fix_xattr_userns(struct user_namespace *to, struct user_namespace *from, void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff812adf30)
Location: fs/posix_acl.c:664
Inline: False
Direct callers:
  - fs/posix_acl.c:posix_acl_fix_xattr_to_user
  - fs/posix_acl.c:posix_acl_fix_xattr_from_user
  - fs/fuse/xattr.c:fuse_getxattr
  - fs/fuse/xattr.c:fuse_setxattr
```
**Symbols:**

```
ffffffff812adf30-ffffffff812ae037: posix_acl_fix_xattr_userns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void posix_acl_fix_xattr_userns(struct user_namespace *to, struct user_namespace *from, void *value, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff812bb3a0)
Location: fs/posix_acl.c:665
Inline: False
Direct callers:
  - fs/posix_acl.c:posix_acl_fix_xattr_to_user
  - fs/posix_acl.c:posix_acl_fix_xattr_from_user
```
**Symbols:**

```
ffffffff812bb3a0-ffffffff812bb43e: posix_acl_fix_xattr_userns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void posix_acl_fix_xattr_userns(struct user_namespace *to, struct user_namespace *from, void *value, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff812dec90)
Location: fs/posix_acl.c:665
Inline: False
Direct callers:
  - fs/posix_acl.c:posix_acl_fix_xattr_to_user
  - fs/posix_acl.c:posix_acl_fix_xattr_from_user
```
**Symbols:**

```
ffffffff812dec90-ffffffff812ded2e: posix_acl_fix_xattr_userns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void posix_acl_fix_xattr_userns(struct user_namespace *to, struct user_namespace *from, void *value, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff8130ade0)
Location: fs/posix_acl.c:665
Inline: False
Direct callers:
  - fs/posix_acl.c:posix_acl_fix_xattr_to_user
  - fs/posix_acl.c:posix_acl_fix_xattr_from_user
```
**Symbols:**

```
ffffffff8130ade0-ffffffff8130ae7f: posix_acl_fix_xattr_userns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void posix_acl_fix_xattr_userns(struct user_namespace *to, struct user_namespace *from, void *value, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff81320620)
Location: fs/posix_acl.c:665
Inline: False
Direct callers:
  - fs/posix_acl.c:posix_acl_fix_xattr_to_user
  - fs/posix_acl.c:posix_acl_fix_xattr_from_user
```
**Symbols:**

```
ffffffff81320620-ffffffff813206bf: posix_acl_fix_xattr_userns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void posix_acl_fix_xattr_userns(struct user_namespace *to, struct user_namespace *from, void *value, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff81347ee0)
Location: fs/posix_acl.c:666
Inline: False
Direct callers:
  - fs/posix_acl.c:posix_acl_fix_xattr_to_user
  - fs/posix_acl.c:posix_acl_fix_xattr_from_user
```
**Symbols:**

```
ffffffff81347ee0-ffffffff81347f7f: posix_acl_fix_xattr_userns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void posix_acl_fix_xattr_userns(struct user_namespace *to, struct user_namespace *from, void *value, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff81360180)
Location: fs/posix_acl.c:666
Inline: False
Direct callers:
  - fs/posix_acl.c:posix_acl_fix_xattr_to_user
  - fs/posix_acl.c:posix_acl_fix_xattr_from_user
```
**Symbols:**

```
ffffffff81360180-ffffffff8136021f: posix_acl_fix_xattr_userns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void posix_acl_fix_xattr_userns(struct user_namespace *to, struct user_namespace *from, void *value, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff813a5bc0)
Location: fs/posix_acl.c:669
Inline: False
Direct callers:
  - fs/posix_acl.c:posix_acl_fix_xattr_to_user
  - fs/posix_acl.c:posix_acl_fix_xattr_from_user
```
**Symbols:**

```
ffffffff813a5bc0-ffffffff813a5c5f: posix_acl_fix_xattr_userns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void posix_acl_fix_xattr_userns(struct user_namespace *to, struct user_namespace *from, void *value, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff813b6900)
Location: fs/posix_acl.c:669
Inline: False
Direct callers:
  - fs/posix_acl.c:posix_acl_fix_xattr_to_user
  - fs/posix_acl.c:posix_acl_fix_xattr_from_user
```
**Symbols:**

```
ffffffff813b6900-ffffffff813b699f: posix_acl_fix_xattr_userns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void posix_acl_fix_xattr_userns(struct user_namespace *to, struct user_namespace *from, struct user_namespace *mnt_userns, void *value, size_t size, bool from_user);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff813bd800)
Location: fs/posix_acl.c:698
Inline: False
Direct callers:
  - fs/posix_acl.c:posix_acl_fix_xattr_to_user
  - fs/posix_acl.c:posix_acl_fix_xattr_from_user
```
**Symbols:**

```
ffffffff813bd800-ffffffff813bd8ee: posix_acl_fix_xattr_userns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void posix_acl_fix_xattr_userns(struct user_namespace *to, struct user_namespace *from, struct user_namespace *mnt_userns, void *value, size_t size, bool from_user);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff8140d5c0)
Location: fs/posix_acl.c:709
Inline: False
Direct callers:
  - fs/posix_acl.c:posix_acl_fix_xattr_to_user
  - fs/posix_acl.c:posix_acl_fix_xattr_from_user
```
**Symbols:**

```
ffffffff8140d5c0-ffffffff8140d6ae: posix_acl_fix_xattr_userns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void posix_acl_fix_xattr_userns(struct user_namespace *to, struct user_namespace *from, struct user_namespace *mnt_userns, void *value, size_t size, bool from_user);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff81482d80)
Location: fs/posix_acl.c:713
Inline: False
Direct callers:
  - fs/posix_acl.c:posix_acl_fix_xattr_to_user
  - fs/posix_acl.c:posix_acl_fix_xattr_from_user
```
**Symbols:**

```
ffffffff81482d80-ffffffff81482ed9: posix_acl_fix_xattr_userns (STB_LOCAL)
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
void posix_acl_fix_xattr_userns(struct user_namespace *to, struct user_namespace *from, void *value, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffff8000104263a8)
Location: fs/posix_acl.c:666
Inline: False
Direct callers:
  - fs/posix_acl.c:posix_acl_fix_xattr_to_user
  - fs/posix_acl.c:posix_acl_fix_xattr_from_user
```
**Symbols:**

```
ffff8000104263a8-ffff800010426478: posix_acl_fix_xattr_userns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void posix_acl_fix_xattr_userns(struct user_namespace *to, struct user_namespace *from, void *value, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (c05eefdc)
Location: fs/posix_acl.c:666
Inline: False
Direct callers:
  - fs/posix_acl.c:posix_acl_fix_xattr_to_user
  - fs/posix_acl.c:posix_acl_fix_xattr_from_user
```
**Symbols:**

```
c05eefdc-c05ef08c: posix_acl_fix_xattr_userns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void posix_acl_fix_xattr_userns(struct user_namespace *to, struct user_namespace *from, void *value, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (c000000000535700)
Location: fs/posix_acl.c:666
Inline: False
Direct callers:
  - fs/posix_acl.c:posix_acl_fix_xattr_to_user
  - fs/posix_acl.c:posix_acl_fix_xattr_from_user
```
**Symbols:**

```
c000000000535700-c000000000535814: posix_acl_fix_xattr_userns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void posix_acl_fix_xattr_userns(struct user_namespace *to, struct user_namespace *from, void *value, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffe0002c4fd8)
Location: fs/posix_acl.c:666
Inline: False
Direct callers:
  - fs/posix_acl.c:posix_acl_fix_xattr_to_user
  - fs/posix_acl.c:posix_acl_fix_xattr_from_user
```
**Symbols:**

```
ffffffe0002c4fd8-ffffffe0002c5088: posix_acl_fix_xattr_userns (STB_LOCAL)
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
void posix_acl_fix_xattr_userns(struct user_namespace *to, struct user_namespace *from, void *value, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff81358760)
Location: fs/posix_acl.c:666
Inline: False
Direct callers:
  - fs/posix_acl.c:posix_acl_fix_xattr_to_user
  - fs/posix_acl.c:posix_acl_fix_xattr_from_user
```
**Symbols:**

```
ffffffff81358760-ffffffff813587ff: posix_acl_fix_xattr_userns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void posix_acl_fix_xattr_userns(struct user_namespace *to, struct user_namespace *from, void *value, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff81349410)
Location: fs/posix_acl.c:666
Inline: False
Direct callers:
  - fs/posix_acl.c:posix_acl_fix_xattr_to_user
  - fs/posix_acl.c:posix_acl_fix_xattr_from_user
```
**Symbols:**

```
ffffffff81349410-ffffffff813494af: posix_acl_fix_xattr_userns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void posix_acl_fix_xattr_userns(struct user_namespace *to, struct user_namespace *from, void *value, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff81356230)
Location: fs/posix_acl.c:666
Inline: False
Direct callers:
  - fs/posix_acl.c:posix_acl_fix_xattr_to_user
  - fs/posix_acl.c:posix_acl_fix_xattr_from_user
```
**Symbols:**

```
ffffffff81356230-ffffffff813562cf: posix_acl_fix_xattr_userns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void posix_acl_fix_xattr_userns(struct user_namespace *to, struct user_namespace *from, void *value, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff81369900)
Location: fs/posix_acl.c:666
Inline: False
Direct callers:
  - fs/posix_acl.c:posix_acl_fix_xattr_to_user
  - fs/posix_acl.c:posix_acl_fix_xattr_from_user
```
**Symbols:**

```
ffffffff81369900-ffffffff8136999f: posix_acl_fix_xattr_userns (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
</details>
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
<b>Param added. </b>
<code>bool from_user</code>
</li>
<li>
<b>Param reordered. </b>
<code>to, from, value, size</code> ➡️ <code>to, from, mnt_userns, value, size, from_user</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
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
