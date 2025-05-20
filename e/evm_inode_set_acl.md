# Function: <code>evm_inode_set_acl</code>

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
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int evm_inode_set_acl(struct user_namespace *mnt_userns, struct dentry *dentry, const char *acl_name, struct posix_acl *kacl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_main.c (ffffffff817024c0)
Location: security/integrity/evm/evm_main.c:652
Inline: False
Direct callers:
  - security/security.c:security_inode_remove_acl
  - security/security.c:security_inode_set_acl
```
**Symbols:**

```
ffffffff817024c0-ffffffff817025dd: evm_inode_set_acl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int evm_inode_set_acl(struct mnt_idmap *idmap, struct dentry *dentry, const char *acl_name, struct posix_acl *kacl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_main.c (ffffffff8173c430)
Location: security/integrity/evm/evm_main.c:652
Inline: False
Direct callers:
  - security/security.c:security_inode_remove_acl
  - security/security.c:security_inode_set_acl
```
**Symbols:**

```
ffffffff8173c430-ffffffff8173c54d: evm_inode_set_acl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int evm_inode_set_acl(struct mnt_idmap *idmap, struct dentry *dentry, const char *acl_name, struct posix_acl *kacl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_main.c (ffffffff8177d200)
Location: security/integrity/evm/evm_main.c:675
Inline: False
Direct callers:
  - security/security.c:security_inode_remove_acl
  - security/security.c:security_inode_set_acl
```
**Symbols:**

```
ffffffff8177d200-ffffffff8177d31d: evm_inode_set_acl (STB_GLOBAL)
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct mnt_idmap *idmap</code>
</li>
<li>
<b>Param removed. </b>
<code>struct user_namespace *mnt_userns</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
