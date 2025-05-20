# Function: <code>evm_revalidate_status</code>

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
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool evm_revalidate_status(const char *xattr_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_main.c (ffffffff815a3105)
Location: security/integrity/evm/evm_main.c:686
Inline: True
Inline callers:
  - security/integrity/evm/evm_main.c:evm_inode_post_setattr
Direct callers:
  - security/integrity/ima/ima_appraise.c:ima_inode_removexattr
  - security/integrity/ima/ima_appraise.c:ima_inode_setxattr
  - security/integrity/evm/evm_main.c:evm_inode_post_removexattr
  - security/integrity/evm/evm_main.c:evm_inode_post_setxattr
```
**Symbols:**

```
ffffffff815a2eb0-ffffffff815a2f07: evm_revalidate_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool evm_revalidate_status(const char *xattr_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_main.c (ffffffff81649915)
Location: security/integrity/evm/evm_main.c:686
Inline: True
Inline callers:
  - security/integrity/evm/evm_main.c:evm_inode_post_setattr
Direct callers:
  - security/integrity/ima/ima_appraise.c:ima_inode_removexattr
  - security/integrity/ima/ima_appraise.c:ima_inode_setxattr
  - security/integrity/evm/evm_main.c:evm_inode_post_removexattr
  - security/integrity/evm/evm_main.c:evm_inode_post_setxattr
```
**Symbols:**

```
ffffffff81649660-ffffffff816496c6: evm_revalidate_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool evm_revalidate_status(const char *xattr_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_main.c (ffffffff817028d5)
Location: security/integrity/evm/evm_main.c:710
Inline: True
Inline callers:
  - security/integrity/evm/evm_main.c:evm_inode_post_setattr
Direct callers:
  - security/integrity/ima/ima_appraise.c:ima_inode_removexattr
  - security/integrity/ima/ima_appraise.c:ima_inode_set_acl
  - security/integrity/ima/ima_appraise.c:ima_inode_setxattr
  - security/integrity/evm/evm_main.c:evm_inode_post_removexattr
  - security/integrity/evm/evm_main.c:evm_inode_post_setxattr
```
**Symbols:**

```
ffffffff817025f0-ffffffff81702656: evm_revalidate_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool evm_revalidate_status(const char *xattr_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_main.c (ffffffff8173c905)
Location: security/integrity/evm/evm_main.c:710
Inline: True
Inline callers:
  - security/integrity/evm/evm_main.c:evm_inode_post_setattr
Direct callers:
  - security/integrity/ima/ima_appraise.c:ima_inode_removexattr
  - security/integrity/ima/ima_appraise.c:ima_inode_set_acl
  - security/integrity/ima/ima_appraise.c:ima_inode_setxattr
  - security/integrity/evm/evm_main.c:evm_inode_post_removexattr
  - security/integrity/evm/evm_main.c:evm_inode_post_setxattr
```
**Symbols:**

```
ffffffff8173c560-ffffffff8173c5c6: evm_revalidate_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool evm_revalidate_status(const char *xattr_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_main.c (ffffffff8177d6c5)
Location: security/integrity/evm/evm_main.c:733
Inline: True
Inline callers:
  - security/integrity/evm/evm_main.c:evm_inode_post_setattr
Direct callers:
  - security/integrity/ima/ima_appraise.c:ima_inode_removexattr
  - security/integrity/ima/ima_appraise.c:ima_inode_set_acl
  - security/integrity/ima/ima_appraise.c:ima_inode_setxattr
  - security/integrity/evm/evm_main.c:evm_inode_post_removexattr
  - security/integrity/evm/evm_main.c:evm_inode_post_setxattr
```
**Symbols:**

```
ffffffff8177d330-ffffffff8177d396: evm_revalidate_status (STB_GLOBAL)
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
