# Function: <code>evm_protected_xattr_common</code>

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
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int evm_protected_xattr_common(const char *req_xattr_name, bool all_xattrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/evm/evm_main.c (0)
Location: security/integrity/evm/evm_main.c:286
Inline: False
Direct callers:
  - security/integrity/evm/evm_main.c:evm_protect_xattr
  - security/integrity/evm/evm_main.c:evm_protected_xattr_if_enabled
```
**Symbols:**

```
ffffffff815a2720-ffffffff815a27d1: evm_protected_xattr_common (STB_LOCAL)
ffffffff81cd74c7-ffffffff81cd74db: evm_protected_xattr_common.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int evm_protected_xattr_common(const char *req_xattr_name, bool all_xattrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/evm/evm_main.c (0)
Location: security/integrity/evm/evm_main.c:286
Inline: False
Direct callers:
  - security/integrity/evm/evm_main.c:evm_inode_init_security
  - security/integrity/evm/evm_main.c:evm_protect_xattr
  - security/integrity/evm/evm_main.c:evm_verifyxattr
  - security/integrity/evm/evm_main.c:evm_protected_xattr_if_enabled
```
**Symbols:**

```
ffffffff81648dc0-ffffffff81648e91: evm_protected_xattr_common (STB_LOCAL)
ffffffff81e8a7aa-ffffffff81e8a7be: evm_protected_xattr_common.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int evm_protected_xattr_common(const char *req_xattr_name, bool all_xattrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/evm/evm_main.c (0)
Location: security/integrity/evm/evm_main.c:280
Inline: False
Direct callers:
  - security/integrity/evm/evm_main.c:evm_inode_init_security
  - security/integrity/evm/evm_main.c:evm_verifyxattr
  - security/integrity/evm/evm_main.c:evm_protected_xattr_if_enabled
```
**Symbols:**

```
ffffffff81701bb0-ffffffff81701c81: evm_protected_xattr_common (STB_LOCAL)
ffffffff82075650-ffffffff82075664: evm_protected_xattr_common.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int evm_protected_xattr_common(const char *req_xattr_name, bool all_xattrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/evm/evm_main.c (0)
Location: security/integrity/evm/evm_main.c:280
Inline: False
Direct callers:
  - security/integrity/evm/evm_main.c:evm_inode_init_security
  - security/integrity/evm/evm_main.c:evm_verifyxattr
  - security/integrity/evm/evm_main.c:evm_protected_xattr_if_enabled
```
**Symbols:**

```
ffffffff8173bc40-ffffffff8173bd11: evm_protected_xattr_common (STB_LOCAL)
ffffffff820f51b2-ffffffff820f51c6: evm_protected_xattr_common.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int evm_protected_xattr_common(const char *req_xattr_name, bool all_xattrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/evm/evm_main.c (0)
Location: security/integrity/evm/evm_main.c:294
Inline: False
Direct callers:
  - security/integrity/evm/evm_main.c:evm_inode_init_security
  - security/integrity/evm/evm_main.c:evm_verifyxattr
  - security/integrity/evm/evm_main.c:evm_protected_xattr_if_enabled
```
**Symbols:**

```
ffffffff8177c460-ffffffff8177c531: evm_protected_xattr_common (STB_LOCAL)
ffffffff821d235c-ffffffff821d2370: evm_protected_xattr_common.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
