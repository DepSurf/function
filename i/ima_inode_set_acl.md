# Function: <code>ima_inode_set_acl</code>

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
int ima_inode_set_acl(struct user_namespace *mnt_userns, struct dentry *dentry, const char *acl_name, struct posix_acl *kacl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_appraise.c (ffffffff81700950)
Location: security/integrity/ima/ima_appraise.c:778
Inline: False
Direct callers:
  - security/security.c:security_inode_remove_acl
  - security/security.c:security_inode_set_acl
```
**Symbols:**

```
ffffffff81700950-ffffffff8170099e: ima_inode_set_acl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ima_inode_set_acl(struct mnt_idmap *idmap, struct dentry *dentry, const char *acl_name, struct posix_acl *kacl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_appraise.c (ffffffff8173a9f0)
Location: security/integrity/ima/ima_appraise.c:781
Inline: False
Direct callers:
  - security/security.c:security_inode_remove_acl
  - security/security.c:security_inode_set_acl
```
**Symbols:**

```
ffffffff8173a9f0-ffffffff8173aa3e: ima_inode_set_acl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ima_inode_set_acl(struct mnt_idmap *idmap, struct dentry *dentry, const char *acl_name, struct posix_acl *kacl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_appraise.c (ffffffff8177b550)
Location: security/integrity/ima/ima_appraise.c:782
Inline: False
Direct callers:
  - security/security.c:security_inode_remove_acl
  - security/security.c:security_inode_set_acl
```
**Symbols:**

```
ffffffff8177b550-ffffffff8177b59e: ima_inode_set_acl (STB_GLOBAL)
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
