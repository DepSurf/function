# Function: <code>get_vfs_caps_from_disk</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int get_vfs_caps_from_disk(const struct dentry *dentry, struct cpu_vfs_cap_data *cpu_caps);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffff8133ab30)
Location: security/commoncap.c:387
Inline: False
Direct callers:
  - kernel/audit.c:audit_copy_inode
  - kernel/auditsc.c:__audit_log_bprm_fcaps
  - security/commoncap.c:cap_bprm_set_creds
```
**Symbols:**

```
ffffffff8133ab30-ffffffff8133ac32: get_vfs_caps_from_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int get_vfs_caps_from_disk(const struct dentry *dentry, struct cpu_vfs_cap_data *cpu_caps);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffff813700c0)
Location: security/commoncap.c:387
Inline: False
Direct callers:
  - kernel/audit.c:audit_copy_inode
  - kernel/auditsc.c:__audit_log_bprm_fcaps
  - security/commoncap.c:cap_bprm_set_creds
```
**Symbols:**

```
ffffffff813700c0-ffffffff813701c3: get_vfs_caps_from_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int get_vfs_caps_from_disk(const struct dentry *dentry, struct cpu_vfs_cap_data *cpu_caps);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffff813868e0)
Location: security/commoncap.c:382
Inline: False
Direct callers:
  - kernel/audit.c:audit_copy_inode
  - kernel/auditsc.c:__audit_log_bprm_fcaps
  - security/commoncap.c:cap_bprm_set_creds
```
**Symbols:**

```
ffffffff813868e0-ffffffff813869d2: get_vfs_caps_from_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int get_vfs_caps_from_disk(const struct dentry *dentry, struct cpu_vfs_cap_data *cpu_caps);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffff8139b540)
Location: security/commoncap.c:585
Inline: False
Direct callers:
  - kernel/audit.c:audit_copy_inode
  - kernel/auditsc.c:__audit_log_bprm_fcaps
  - security/commoncap.c:cap_bprm_set_creds
```
**Symbols:**

```
ffffffff8139b540-ffffffff8139b6aa: get_vfs_caps_from_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int get_vfs_caps_from_disk(const struct dentry *dentry, struct cpu_vfs_cap_data *cpu_caps);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffff813c0b50)
Location: security/commoncap.c:576
Inline: False
Direct callers:
  - kernel/audit.c:audit_copy_inode
  - kernel/auditsc.c:__audit_log_bprm_fcaps
  - security/commoncap.c:cap_bprm_set_creds
```
**Symbols:**

```
ffffffff813c0b50-ffffffff813c0cba: get_vfs_caps_from_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int get_vfs_caps_from_disk(const struct dentry *dentry, struct cpu_vfs_cap_data *cpu_caps);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffff813f1ab0)
Location: security/commoncap.c:578
Inline: False
Direct callers:
  - kernel/audit.c:audit_copy_inode
  - kernel/auditsc.c:__audit_log_bprm_fcaps
  - security/commoncap.c:cap_bprm_set_creds
```
**Symbols:**

```
ffffffff813f1ab0-ffffffff813f1c25: get_vfs_caps_from_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int get_vfs_caps_from_disk(const struct dentry *dentry, struct cpu_vfs_cap_data *cpu_caps);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffff8140cd80)
Location: security/commoncap.c:576
Inline: False
Direct callers:
  - kernel/audit.c:audit_copy_inode
  - kernel/auditsc.c:__audit_log_bprm_fcaps
  - security/commoncap.c:cap_bprm_set_creds
```
**Symbols:**

```
ffffffff8140cd80-ffffffff8140cef2: get_vfs_caps_from_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int get_vfs_caps_from_disk(const struct dentry *dentry, struct cpu_vfs_cap_data *cpu_caps);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffff81439f20)
Location: security/commoncap.c:571
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_log_bprm_fcaps
  - kernel/auditsc.c:audit_copy_inode
  - security/commoncap.c:cap_bprm_set_creds
```
**Symbols:**

```
ffffffff81439f20-ffffffff8143a0a8: get_vfs_caps_from_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int get_vfs_caps_from_disk(const struct dentry *dentry, struct cpu_vfs_cap_data *cpu_caps);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffff81453d90)
Location: security/commoncap.c:571
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_log_bprm_fcaps
  - kernel/auditsc.c:audit_copy_inode
  - security/commoncap.c:cap_bprm_set_creds
```
**Symbols:**

```
ffffffff81453d90-ffffffff81453f18: get_vfs_caps_from_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int get_vfs_caps_from_disk(const struct dentry *dentry, struct cpu_vfs_cap_data *cpu_caps);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffff814a66a0)
Location: security/commoncap.c:571
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_log_bprm_fcaps
```
**Symbols:**

```
ffffffff814a66a0-ffffffff814a6864: get_vfs_caps_from_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int get_vfs_caps_from_disk(const struct dentry *dentry, struct cpu_vfs_cap_data *cpu_caps);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffff814c3c50)
Location: security/commoncap.c:589
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_log_bprm_fcaps
```
**Symbols:**

```
ffffffff814c3c50-ffffffff814c3e14: get_vfs_caps_from_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int get_vfs_caps_from_disk(struct user_namespace *mnt_userns, const struct dentry *dentry, struct cpu_vfs_cap_data *cpu_caps);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffff814ca0f0)
Location: security/commoncap.c:644
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_log_bprm_fcaps
  - security/commoncap.c:cap_bprm_creds_from_file
```
**Symbols:**

```
ffffffff814ca0f0-ffffffff814ca2b9: get_vfs_caps_from_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int get_vfs_caps_from_disk(struct user_namespace *mnt_userns, const struct dentry *dentry, struct cpu_vfs_cap_data *cpu_caps);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffff81522d90)
Location: security/commoncap.c:644
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_log_bprm_fcaps
```
**Symbols:**

```
ffffffff81522d90-ffffffff81522f59: get_vfs_caps_from_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int get_vfs_caps_from_disk(struct user_namespace *mnt_userns, const struct dentry *dentry, struct cpu_vfs_cap_data *cpu_caps);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffff815b6ac0)
Location: security/commoncap.c:647
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_log_bprm_fcaps
  - security/commoncap.c:cap_bprm_creds_from_file
```
**Symbols:**

```
ffffffff815b6ac0-ffffffff815b6cf0: get_vfs_caps_from_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int get_vfs_caps_from_disk(struct user_namespace *mnt_userns, const struct dentry *dentry, struct cpu_vfs_cap_data *cpu_caps);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffff81661c80)
Location: security/commoncap.c:642
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_log_bprm_fcaps
```
**Symbols:**

```
ffffffff81661c80-ffffffff81661ea7: get_vfs_caps_from_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int get_vfs_caps_from_disk(struct mnt_idmap *idmap, const struct dentry *dentry, struct cpu_vfs_cap_data *cpu_caps);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffff8169a2c0)
Location: security/commoncap.c:636
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_log_bprm_fcaps
  - security/commoncap.c:cap_bprm_creds_from_file
```
**Symbols:**

```
ffffffff8169a2c0-ffffffff8169a4b1: get_vfs_caps_from_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int get_vfs_caps_from_disk(struct mnt_idmap *idmap, const struct dentry *dentry, struct cpu_vfs_cap_data *cpu_caps);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffff816d6a00)
Location: security/commoncap.c:636
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_log_bprm_fcaps
  - security/commoncap.c:cap_bprm_creds_from_file
```
**Symbols:**

```
ffffffff816d6a00-ffffffff816d6bf1: get_vfs_caps_from_disk (STB_GLOBAL)
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
int get_vfs_caps_from_disk(const struct dentry *dentry, struct cpu_vfs_cap_data *cpu_caps);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffff80001053eeb8)
Location: security/commoncap.c:571
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_log_bprm_fcaps
  - kernel/auditsc.c:audit_copy_inode
  - security/commoncap.c:cap_bprm_set_creds
```
**Symbols:**

```
ffff80001053eeb8-ffff80001053f060: get_vfs_caps_from_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int get_vfs_caps_from_disk(const struct dentry *dentry, struct cpu_vfs_cap_data *cpu_caps);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/commoncap.c (c06f4e88)
Location: security/commoncap.c:571
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_log_bprm_fcaps
  - kernel/auditsc.c:audit_copy_inode
  - security/commoncap.c:cap_bprm_set_creds
```
**Symbols:**

```
c06f4e88-c06f502c: get_vfs_caps_from_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int get_vfs_caps_from_disk(const struct dentry *dentry, struct cpu_vfs_cap_data *cpu_caps);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/commoncap.c (c00000000068f780)
Location: security/commoncap.c:571
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_log_bprm_fcaps
  - kernel/auditsc.c:audit_copy_inode
  - security/commoncap.c:cap_bprm_set_creds
```
**Symbols:**

```
c00000000068f780-c00000000068f9d0: get_vfs_caps_from_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int get_vfs_caps_from_disk(const struct dentry *dentry, struct cpu_vfs_cap_data *cpu_caps);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffe00039c4ce)
Location: security/commoncap.c:571
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_log_bprm_fcaps
  - kernel/auditsc.c:audit_copy_inode
  - security/commoncap.c:cap_bprm_set_creds
```
**Symbols:**

```
ffffffe00039c4ce-ffffffe00039c620: get_vfs_caps_from_disk (STB_GLOBAL)
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
int get_vfs_caps_from_disk(const struct dentry *dentry, struct cpu_vfs_cap_data *cpu_caps);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffff8144c370)
Location: security/commoncap.c:571
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_log_bprm_fcaps
  - kernel/auditsc.c:audit_copy_inode
  - security/commoncap.c:cap_bprm_set_creds
```
**Symbols:**

```
ffffffff8144c370-ffffffff8144c4f8: get_vfs_caps_from_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int get_vfs_caps_from_disk(const struct dentry *dentry, struct cpu_vfs_cap_data *cpu_caps);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffff8143cdc0)
Location: security/commoncap.c:571
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_log_bprm_fcaps
  - kernel/auditsc.c:audit_copy_inode
  - security/commoncap.c:cap_bprm_set_creds
```
**Symbols:**

```
ffffffff8143cdc0-ffffffff8143cf48: get_vfs_caps_from_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int get_vfs_caps_from_disk(const struct dentry *dentry, struct cpu_vfs_cap_data *cpu_caps);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffff81448410)
Location: security/commoncap.c:571
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_log_bprm_fcaps
  - kernel/auditsc.c:audit_copy_inode
  - security/commoncap.c:cap_bprm_set_creds
```
**Symbols:**

```
ffffffff81448410-ffffffff81448598: get_vfs_caps_from_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int get_vfs_caps_from_disk(const struct dentry *dentry, struct cpu_vfs_cap_data *cpu_caps);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffff8145f7e0)
Location: security/commoncap.c:571
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_log_bprm_fcaps
  - kernel/auditsc.c:audit_copy_inode
  - security/commoncap.c:cap_bprm_set_creds
```
**Symbols:**

```
ffffffff8145f7e0-ffffffff8145f968: get_vfs_caps_from_disk (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct user_namespace *mnt_userns</code>
</li>
<li>
<b>Param reordered. </b>
<code>dentry, cpu_caps</code> ➡️ <code>mnt_userns, dentry, cpu_caps</code>
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
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
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
