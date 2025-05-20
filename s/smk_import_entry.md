# Function: <code>smk_import_entry</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct smack_known *smk_import_entry(const char *string, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff81362bb0)
Location: security/smack/smack_access.c:531
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_audit_rule_init
  - security/smack/smack_lsm.c:smack_inode_post_setxattr
  - security/smack/smack_lsm.c:smack_inode_post_setxattr
  - security/smack/smack_lsm.c:smack_inode_post_setxattr
  - security/smack/smack_lsm.c:smack_inode_setsecurity
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smackfs.c:smk_fill_rule
  - security/smack/smackfs.c:smk_fill_rule
  - security/smack/smackfs.c:smk_parse_label_list
  - security/smack/smackfs.c:smk_write_syslog
  - security/smack/smackfs.c:smk_write_ambient
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net4addr
```
**Symbols:**

```
ffffffff81362bb0-ffffffff81362cda: smk_import_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct smack_known *smk_import_entry(const char *string, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff81398d70)
Location: security/smack/smack_access.c:531
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_audit_rule_init
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smack_lsm.c:smack_inode_setsecurity
  - security/smack/smack_lsm.c:smack_inode_post_setxattr
  - security/smack/smack_lsm.c:smack_inode_post_setxattr
  - security/smack/smack_lsm.c:smack_inode_post_setxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smk_fetch
  - security/smack/smackfs.c:smk_write_syslog
  - security/smack/smackfs.c:smk_parse_label_list
  - security/smack/smackfs.c:smk_write_ambient
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_fill_rule
  - security/smack/smackfs.c:smk_fill_rule
```
**Symbols:**

```
ffffffff81398d70-ffffffff81398ead: smk_import_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct smack_known *smk_import_entry(const char *string, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff813af950)
Location: security/smack/smack_access.c:526
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_audit_rule_init
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smack_lsm.c:smack_inode_setsecurity
  - security/smack/smack_lsm.c:smack_inode_post_setxattr
  - security/smack/smack_lsm.c:smack_inode_post_setxattr
  - security/smack/smack_lsm.c:smack_inode_post_setxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smackfs.c:smk_write_syslog
  - security/smack/smackfs.c:smk_parse_label_list
  - security/smack/smackfs.c:smk_write_ambient
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_fill_rule
  - security/smack/smackfs.c:smk_fill_rule
```
**Symbols:**

```
ffffffff813af950-ffffffff813afa8d: smk_import_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct smack_known *smk_import_entry(const char *string, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff813c6500)
Location: security/smack/smack_access.c:526
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_audit_rule_init
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smack_lsm.c:smack_inode_setsecurity
  - security/smack/smack_lsm.c:smack_inode_post_setxattr
  - security/smack/smack_lsm.c:smack_inode_post_setxattr
  - security/smack/smack_lsm.c:smack_inode_post_setxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smackfs.c:smk_write_syslog
  - security/smack/smackfs.c:smk_parse_label_list
  - security/smack/smackfs.c:smk_write_ambient
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_fill_rule
  - security/smack/smackfs.c:smk_fill_rule
```
**Symbols:**

```
ffffffff813c6500-ffffffff813c6639: smk_import_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct smack_known *smk_import_entry(const char *string, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff813ec7f0)
Location: security/smack/smack_access.c:526
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_audit_rule_init
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smack_lsm.c:smack_inode_setsecurity
  - security/smack/smack_lsm.c:smack_inode_post_setxattr
  - security/smack/smack_lsm.c:smack_inode_post_setxattr
  - security/smack/smack_lsm.c:smack_inode_post_setxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smackfs.c:smk_write_syslog
  - security/smack/smackfs.c:smk_parse_label_list
  - security/smack/smackfs.c:smk_write_ambient
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_fill_rule
  - security/smack/smackfs.c:smk_fill_rule
```
**Symbols:**

```
ffffffff813ec7f0-ffffffff813ec929: smk_import_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct smack_known *smk_import_entry(const char *string, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff8141d620)
Location: security/smack/smack_access.c:526
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_audit_rule_init
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smack_lsm.c:smack_inode_setsecurity
  - security/smack/smack_lsm.c:smack_inode_post_setxattr
  - security/smack/smack_lsm.c:smack_inode_post_setxattr
  - security/smack/smack_lsm.c:smack_inode_post_setxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smackfs.c:smk_write_syslog
  - security/smack/smackfs.c:smk_parse_label_list
  - security/smack/smackfs.c:smk_write_ambient
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_fill_rule
  - security/smack/smackfs.c:smk_fill_rule
```
**Symbols:**

```
ffffffff8141d620-ffffffff8141d758: smk_import_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct smack_known *smk_import_entry(const char *string, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff81439c10)
Location: security/smack/smack_access.c:526
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_audit_rule_init
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smack_lsm.c:smack_inode_setsecurity
  - security/smack/smack_lsm.c:smack_inode_post_setxattr
  - security/smack/smack_lsm.c:smack_inode_post_setxattr
  - security/smack/smack_lsm.c:smack_inode_post_setxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smackfs.c:smk_write_syslog
  - security/smack/smackfs.c:smk_parse_label_list
  - security/smack/smackfs.c:smk_write_ambient
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_fill_rule
  - security/smack/smackfs.c:smk_fill_rule
```
**Symbols:**

```
ffffffff81439c10-ffffffff81439d48: smk_import_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct smack_known *smk_import_entry(const char *string, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff814677c0)
Location: security/smack/smack_access.c:522
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_audit_rule_init
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smack_lsm.c:smack_inode_setsecurity
  - security/smack/smack_lsm.c:smack_inode_post_setxattr
  - security/smack/smack_lsm.c:smack_inode_post_setxattr
  - security/smack/smack_lsm.c:smack_inode_post_setxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smackfs.c:smk_write_syslog
  - security/smack/smackfs.c:smk_parse_label_list
  - security/smack/smackfs.c:smk_write_ambient
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_fill_rule
  - security/smack/smackfs.c:smk_fill_rule
```
**Symbols:**

```
ffffffff814677c0-ffffffff81467904: smk_import_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct smack_known *smk_import_entry(const char *string, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff814815a0)
Location: security/smack/smack_access.c:522
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_audit_rule_init
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smack_lsm.c:smack_inode_setsecurity
  - security/smack/smack_lsm.c:smack_inode_post_setxattr
  - security/smack/smack_lsm.c:smack_inode_post_setxattr
  - security/smack/smack_lsm.c:smack_inode_post_setxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smackfs.c:smk_write_syslog
  - security/smack/smackfs.c:smk_parse_label_list
  - security/smack/smackfs.c:smk_write_ambient
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_fill_rule
  - security/smack/smackfs.c:smk_fill_rule
```
**Symbols:**

```
ffffffff814815a0-ffffffff814816e4: smk_import_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct smack_known *smk_import_entry(const char *string, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff814d7510)
Location: security/smack/smack_access.c:522
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_audit_rule_init
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smack_lsm.c:smack_inode_setsecurity
  - security/smack/smack_lsm.c:smack_inode_post_setxattr
  - security/smack/smack_lsm.c:smack_inode_post_setxattr
  - security/smack/smack_lsm.c:smack_inode_post_setxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smackfs.c:smk_write_syslog
  - security/smack/smackfs.c:smk_parse_label_list
  - security/smack/smackfs.c:smk_write_ambient
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net4addr
```
**Symbols:**

```
ffffffff814d7510-ffffffff814d76ec: smk_import_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct smack_known *smk_import_entry(const char *string, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff814f4b30)
Location: security/smack/smack_access.c:561
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_audit_rule_init
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smack_lsm.c:smack_inode_setsecurity
  - security/smack/smack_lsm.c:smack_inode_post_setxattr
  - security/smack/smack_lsm.c:smack_inode_post_setxattr
  - security/smack/smack_lsm.c:smack_inode_post_setxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smackfs.c:smk_write_syslog
  - security/smack/smackfs.c:smk_parse_label_list
  - security/smack/smackfs.c:smk_write_ambient
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net4addr
```
**Symbols:**

```
ffffffff814f4b30-ffffffff814f4c27: smk_import_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct smack_known *smk_import_entry(const char *string, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff814fbaa0)
Location: security/smack/smack_access.c:561
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_audit_rule_init
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smack_lsm.c:smack_inode_setsecurity
  - security/smack/smack_lsm.c:smack_inode_post_setxattr
  - security/smack/smack_lsm.c:smack_inode_post_setxattr
  - security/smack/smack_lsm.c:smack_inode_post_setxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smackfs.c:smk_write_syslog
  - security/smack/smackfs.c:smk_parse_label_list
  - security/smack/smackfs.c:smk_write_ambient
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net4addr
```
**Symbols:**

```
ffffffff814fbaa0-ffffffff814fbb97: smk_import_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct smack_known *smk_import_entry(const char *string, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff81556710)
Location: security/smack/smack_access.c:563
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_audit_rule_init
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smack_lsm.c:smack_inode_setsecurity
  - security/smack/smack_lsm.c:smack_inode_post_setxattr
  - security/smack/smack_lsm.c:smack_inode_post_setxattr
  - security/smack/smack_lsm.c:smack_inode_post_setxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smackfs.c:smk_write_syslog
  - security/smack/smackfs.c:smk_parse_label_list
  - security/smack/smackfs.c:smk_write_ambient
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net4addr
```
**Symbols:**

```
ffffffff81556710-ffffffff81556807: smk_import_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct smack_known *smk_import_entry(const char *string, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff815f0b00)
Location: security/smack/smack_access.c:560
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_audit_rule_init
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smack_lsm.c:smack_inode_setsecurity
  - security/smack/smack_lsm.c:smack_inode_post_setxattr
  - security/smack/smack_lsm.c:smack_inode_post_setxattr
  - security/smack/smack_lsm.c:smack_inode_post_setxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smackfs.c:smk_write_syslog
  - security/smack/smackfs.c:smk_parse_label_list
  - security/smack/smackfs.c:smk_write_ambient
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net4addr
```
**Symbols:**

```
ffffffff815f0b00-ffffffff815f0c09: smk_import_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct smack_known *smk_import_entry(const char *string, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff816a0f40)
Location: security/smack/smack_access.c:557
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_audit_rule_init
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smack_lsm.c:smack_inode_setsecurity
  - security/smack/smack_lsm.c:smack_inode_post_setxattr
  - security/smack/smack_lsm.c:smack_inode_post_setxattr
  - security/smack/smack_lsm.c:smack_inode_post_setxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smackfs.c:smk_write_syslog
  - security/smack/smackfs.c:smk_parse_label_list
  - security/smack/smackfs.c:smk_write_ambient
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net4addr
```
**Symbols:**

```
ffffffff816a0f40-ffffffff816a1049: smk_import_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct smack_known *smk_import_entry(const char *string, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff816d9880)
Location: security/smack/smack_access.c:557
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_audit_rule_init
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smack_lsm.c:smack_inode_setsecurity
  - security/smack/smack_lsm.c:smack_inode_post_setxattr
  - security/smack/smack_lsm.c:smack_inode_post_setxattr
  - security/smack/smack_lsm.c:smack_inode_post_setxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_add_opt
  - security/smack/smackfs.c:smk_write_syslog
  - security/smack/smackfs.c:smk_parse_label_list
  - security/smack/smackfs.c:smk_write_ambient
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net4addr
```
**Symbols:**

```
ffffffff816d9880-ffffffff816d9989: smk_import_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct smack_known *smk_import_entry(const char *string, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff817162f0)
Location: security/smack/smack_access.c:557
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:do_setattr
  - security/smack/smack_lsm.c:smack_inode_setsecurity
  - security/smack/smack_lsm.c:smack_inode_post_setxattr
  - security/smack/smack_lsm.c:smack_inode_post_setxattr
  - security/smack/smack_lsm.c:smack_inode_post_setxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_add_opt
  - security/smack/smackfs.c:smk_write_syslog
  - security/smack/smackfs.c:smk_parse_label_list
  - security/smack/smackfs.c:smk_write_ambient
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net4addr
```
**Symbols:**

```
ffffffff817162f0-ffffffff8171642b: smk_import_entry (STB_GLOBAL)
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
struct smack_known *smk_import_entry(const char *string, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffff800010572f48)
Location: security/smack/smack_access.c:522
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_audit_rule_init
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smack_lsm.c:smack_inode_setsecurity
  - security/smack/smack_lsm.c:smack_inode_post_setxattr
  - security/smack/smack_lsm.c:smack_inode_post_setxattr
  - security/smack/smack_lsm.c:smack_inode_post_setxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smackfs.c:smk_write_syslog
  - security/smack/smackfs.c:smk_parse_label_list
  - security/smack/smackfs.c:smk_write_ambient
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_fill_rule
  - security/smack/smackfs.c:smk_fill_rule
```
**Symbols:**

```
ffff800010572f48-ffff8000105730b4: smk_import_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct smack_known *smk_import_entry(const char *string, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (c07260ec)
Location: security/smack/smack_access.c:522
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_audit_rule_init
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smack_lsm.c:smack_inode_setsecurity
  - security/smack/smack_lsm.c:smack_inode_post_setxattr
  - security/smack/smack_lsm.c:smack_inode_post_setxattr
  - security/smack/smack_lsm.c:smack_inode_post_setxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smackfs.c:smk_write_syslog
  - security/smack/smackfs.c:smk_parse_label_list
  - security/smack/smackfs.c:smk_write_ambient
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_fill_rule
  - security/smack/smackfs.c:smk_fill_rule
```
**Symbols:**

```
c07260ec-c0726244: smk_import_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct smack_known *smk_import_entry(const char *string, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (c0000000006db150)
Location: security/smack/smack_access.c:522
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_audit_rule_init
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smack_lsm.c:smack_inode_setsecurity
  - security/smack/smack_lsm.c:smack_inode_post_setxattr
  - security/smack/smack_lsm.c:smack_inode_post_setxattr
  - security/smack/smack_lsm.c:smack_inode_post_setxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smackfs.c:smk_write_syslog
  - security/smack/smackfs.c:smk_parse_label_list
  - security/smack/smackfs.c:smk_write_ambient
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_fill_rule
  - security/smack/smackfs.c:smk_fill_rule
```
**Symbols:**

```
c0000000006db150-c0000000006db338: smk_import_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct smack_known *smk_import_entry(const char *string, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffe0003c6478)
Location: security/smack/smack_access.c:522
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_audit_rule_init
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smack_lsm.c:smack_inode_setsecurity
  - security/smack/smack_lsm.c:smack_inode_post_setxattr
  - security/smack/smack_lsm.c:smack_inode_post_setxattr
  - security/smack/smack_lsm.c:smack_inode_post_setxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smackfs.c:smk_write_syslog
  - security/smack/smackfs.c:smk_parse_label_list
  - security/smack/smackfs.c:smk_write_ambient
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_fill_rule
  - security/smack/smackfs.c:smk_fill_rule
```
**Symbols:**

```
ffffffe0003c6478-ffffffe0003c65cc: smk_import_entry (STB_GLOBAL)
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
struct smack_known *smk_import_entry(const char *string, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff81479b80)
Location: security/smack/smack_access.c:522
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_audit_rule_init
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smack_lsm.c:smack_inode_setsecurity
  - security/smack/smack_lsm.c:smack_inode_post_setxattr
  - security/smack/smack_lsm.c:smack_inode_post_setxattr
  - security/smack/smack_lsm.c:smack_inode_post_setxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smackfs.c:smk_write_syslog
  - security/smack/smackfs.c:smk_parse_label_list
  - security/smack/smackfs.c:smk_write_ambient
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_fill_rule
  - security/smack/smackfs.c:smk_fill_rule
```
**Symbols:**

```
ffffffff81479b80-ffffffff81479cc4: smk_import_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct smack_known *smk_import_entry(const char *string, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff8146a5a0)
Location: security/smack/smack_access.c:522
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_audit_rule_init
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smack_lsm.c:smack_inode_setsecurity
  - security/smack/smack_lsm.c:smack_inode_post_setxattr
  - security/smack/smack_lsm.c:smack_inode_post_setxattr
  - security/smack/smack_lsm.c:smack_inode_post_setxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smackfs.c:smk_write_syslog
  - security/smack/smackfs.c:smk_parse_label_list
  - security/smack/smackfs.c:smk_write_ambient
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_fill_rule
  - security/smack/smackfs.c:smk_fill_rule
```
**Symbols:**

```
ffffffff8146a5a0-ffffffff8146a6e4: smk_import_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct smack_known *smk_import_entry(const char *string, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff81475c20)
Location: security/smack/smack_access.c:522
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_audit_rule_init
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smack_lsm.c:smack_inode_setsecurity
  - security/smack/smack_lsm.c:smack_inode_post_setxattr
  - security/smack/smack_lsm.c:smack_inode_post_setxattr
  - security/smack/smack_lsm.c:smack_inode_post_setxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smackfs.c:smk_write_syslog
  - security/smack/smackfs.c:smk_parse_label_list
  - security/smack/smackfs.c:smk_write_ambient
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_fill_rule
  - security/smack/smackfs.c:smk_fill_rule
```
**Symbols:**

```
ffffffff81475c20-ffffffff81475d64: smk_import_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct smack_known *smk_import_entry(const char *string, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff8148d670)
Location: security/smack/smack_access.c:522
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_audit_rule_init
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smack_lsm.c:smack_inode_setsecurity
  - security/smack/smack_lsm.c:smack_inode_post_setxattr
  - security/smack/smack_lsm.c:smack_inode_post_setxattr
  - security/smack/smack_lsm.c:smack_inode_post_setxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smackfs.c:smk_write_syslog
  - security/smack/smackfs.c:smk_parse_label_list
  - security/smack/smackfs.c:smk_write_ambient
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_fill_rule
  - security/smack/smackfs.c:smk_fill_rule
```
**Symbols:**

```
ffffffff8148d670-ffffffff8148d7b4: smk_import_entry (STB_GLOBAL)
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
