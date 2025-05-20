# Function: <code>smack_privileged</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int smack_privileged(int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff81362d30)
Location: security/smack/smack_access.c:637
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_file_open
  - security/smack/smack_lsm.c:smack_syslog
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_unix_may_send
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_access.c:smk_tskacc
  - security/smack/smackfs.c:smk_write_ptrace
  - security/smack/smackfs.c:smk_write_logging
  - security/smack/smackfs.c:smk_write_mapped
  - security/smack/smackfs.c:smk_write_direct
  - security/smack/smackfs.c:smk_write_doi
  - security/smack/smackfs.c:smk_write_change_rule
  - security/smack/smackfs.c:smk_write_load2
  - security/smack/smackfs.c:smk_write_load
  - security/smack/smackfs.c:smk_write_syslog
  - security/smack/smackfs.c:smk_write_ambient
  - security/smack/smackfs.c:smk_write_onlycap
  - security/smack/smackfs.c:smk_write_relabel_self
  - security/smack/smackfs.c:smk_write_revoke_subj
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net4addr
```
**Symbols:**

```
ffffffff81362d30-ffffffff81362daa: smack_privileged (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int smack_privileged(int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff81398f00)
Location: security/smack/smack_access.c:637
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_unix_may_send
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smack_lsm.c:smack_file_open
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_syslog
  - security/smack/smack_access.c:smk_tskacc
  - security/smack/smackfs.c:smk_write_ptrace
  - security/smack/smackfs.c:smk_write_relabel_self
  - security/smack/smackfs.c:smk_write_syslog
  - security/smack/smackfs.c:smk_write_change_rule
  - security/smack/smackfs.c:smk_write_revoke_subj
  - security/smack/smackfs.c:smk_write_load2
  - security/smack/smackfs.c:smk_write_logging
  - security/smack/smackfs.c:smk_write_onlycap
  - security/smack/smackfs.c:smk_write_ambient
  - security/smack/smackfs.c:smk_write_mapped
  - security/smack/smackfs.c:smk_write_direct
  - security/smack/smackfs.c:smk_write_doi
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_write_load
```
**Symbols:**

```
ffffffff81398f00-ffffffff81398f7e: smack_privileged (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int smack_privileged(int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff813afae0)
Location: security/smack/smack_access.c:632
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_unix_may_send
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smack_lsm.c:smack_file_open
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_syslog
  - security/smack/smack_access.c:smk_tskacc
  - security/smack/smackfs.c:smk_write_ptrace
  - security/smack/smackfs.c:smk_write_relabel_self
  - security/smack/smackfs.c:smk_write_syslog
  - security/smack/smackfs.c:smk_write_change_rule
  - security/smack/smackfs.c:smk_write_revoke_subj
  - security/smack/smackfs.c:smk_write_load2
  - security/smack/smackfs.c:smk_write_logging
  - security/smack/smackfs.c:smk_write_onlycap
  - security/smack/smackfs.c:smk_write_ambient
  - security/smack/smackfs.c:smk_write_mapped
  - security/smack/smackfs.c:smk_write_direct
  - security/smack/smackfs.c:smk_write_doi
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_write_load
```
**Symbols:**

```
ffffffff813afae0-ffffffff813afb5e: smack_privileged (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool smack_privileged(int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff813c6680)
Location: security/smack/smack_access.c:632
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_unix_may_send
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_syslog
  - security/smack/smack_access.c:smk_tskacc
  - security/smack/smackfs.c:smk_write_ptrace
  - security/smack/smackfs.c:smk_write_relabel_self
  - security/smack/smackfs.c:smk_write_syslog
  - security/smack/smackfs.c:smk_write_change_rule
  - security/smack/smackfs.c:smk_write_revoke_subj
  - security/smack/smackfs.c:smk_write_load2
  - security/smack/smackfs.c:smk_write_logging
  - security/smack/smackfs.c:smk_write_onlycap
  - security/smack/smackfs.c:smk_write_ambient
  - security/smack/smackfs.c:smk_write_mapped
  - security/smack/smackfs.c:smk_write_direct
  - security/smack/smackfs.c:smk_write_doi
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_write_load
```
**Symbols:**

```
ffffffff813c6680-ffffffff813c6712: smack_privileged (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool smack_privileged(int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff813ec970)
Location: security/smack/smack_access.c:632
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_unix_may_send
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_syslog
  - security/smack/smack_access.c:smk_tskacc
  - security/smack/smackfs.c:smk_write_ptrace
  - security/smack/smackfs.c:smk_write_relabel_self
  - security/smack/smackfs.c:smk_write_syslog
  - security/smack/smackfs.c:smk_write_change_rule
  - security/smack/smackfs.c:smk_write_revoke_subj
  - security/smack/smackfs.c:smk_write_load2
  - security/smack/smackfs.c:smk_write_logging
  - security/smack/smackfs.c:smk_write_onlycap
  - security/smack/smackfs.c:smk_write_ambient
  - security/smack/smackfs.c:smk_write_mapped
  - security/smack/smackfs.c:smk_write_direct
  - security/smack/smackfs.c:smk_write_doi
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_write_load
```
**Symbols:**

```
ffffffff813ec970-ffffffff813eca02: smack_privileged (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool smack_privileged(int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff8141d820)
Location: security/smack/smack_access.c:673
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_unix_may_send
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_syslog
  - security/smack/smack_access.c:smk_tskacc
  - security/smack/smackfs.c:smk_write_ptrace
  - security/smack/smackfs.c:smk_write_relabel_self
  - security/smack/smackfs.c:smk_write_syslog
  - security/smack/smackfs.c:smk_write_change_rule
  - security/smack/smackfs.c:smk_write_revoke_subj
  - security/smack/smackfs.c:smk_write_load2
  - security/smack/smackfs.c:smk_write_logging
  - security/smack/smackfs.c:smk_write_onlycap
  - security/smack/smackfs.c:smk_write_ambient
  - security/smack/smackfs.c:smk_write_mapped
  - security/smack/smackfs.c:smk_write_direct
  - security/smack/smackfs.c:smk_write_doi
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_write_load
```
**Symbols:**

```
ffffffff8141d820-ffffffff8141d84d: smack_privileged (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool smack_privileged(int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff81439e10)
Location: security/smack/smack_access.c:673
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_unix_may_send
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_syslog
  - security/smack/smack_access.c:smk_tskacc
  - security/smack/smackfs.c:smk_write_ptrace
  - security/smack/smackfs.c:smk_write_relabel_self
  - security/smack/smackfs.c:smk_write_syslog
  - security/smack/smackfs.c:smk_write_change_rule
  - security/smack/smackfs.c:smk_write_revoke_subj
  - security/smack/smackfs.c:smk_write_load2
  - security/smack/smackfs.c:smk_write_logging
  - security/smack/smackfs.c:smk_write_onlycap
  - security/smack/smackfs.c:smk_write_ambient
  - security/smack/smackfs.c:smk_write_mapped
  - security/smack/smackfs.c:smk_write_direct
  - security/smack/smackfs.c:smk_write_doi
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_write_load
```
**Symbols:**

```
ffffffff81439e10-ffffffff81439e3d: smack_privileged (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool smack_privileged(int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff814679d0)
Location: security/smack/smack_access.c:669
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_unix_may_send
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_syslog
  - security/smack/smack_access.c:smk_tskacc
  - security/smack/smackfs.c:smk_write_ptrace
  - security/smack/smackfs.c:smk_write_relabel_self
  - security/smack/smackfs.c:smk_write_syslog
  - security/smack/smackfs.c:smk_write_change_rule
  - security/smack/smackfs.c:smk_write_revoke_subj
  - security/smack/smackfs.c:smk_write_load2
  - security/smack/smackfs.c:smk_write_logging
  - security/smack/smackfs.c:smk_write_onlycap
  - security/smack/smackfs.c:smk_write_ambient
  - security/smack/smackfs.c:smk_write_mapped
  - security/smack/smackfs.c:smk_write_direct
  - security/smack/smackfs.c:smk_write_doi
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_write_load
```
**Symbols:**

```
ffffffff814679d0-ffffffff814679fc: smack_privileged (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool smack_privileged(int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff814817b0)
Location: security/smack/smack_access.c:669
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_unix_may_send
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_syslog
  - security/smack/smack_access.c:smk_tskacc
  - security/smack/smackfs.c:smk_write_ptrace
  - security/smack/smackfs.c:smk_write_relabel_self
  - security/smack/smackfs.c:smk_write_syslog
  - security/smack/smackfs.c:smk_write_change_rule
  - security/smack/smackfs.c:smk_write_revoke_subj
  - security/smack/smackfs.c:smk_write_load2
  - security/smack/smackfs.c:smk_write_logging
  - security/smack/smackfs.c:smk_write_onlycap
  - security/smack/smackfs.c:smk_write_ambient
  - security/smack/smackfs.c:smk_write_mapped
  - security/smack/smackfs.c:smk_write_direct
  - security/smack/smackfs.c:smk_write_doi
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_write_load
```
**Symbols:**

```
ffffffff814817b0-ffffffff814817dc: smack_privileged (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool smack_privileged(int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff814d7837)
Location: security/smack/smack_access.c:669
Inline: True
Inline callers:
  - security/smack/smack_access.c:smk_tskacc
Direct callers:
  - security/smack/smack_lsm.c:smack_key_permission
  - security/smack/smack_lsm.c:smack_unix_may_send
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_syslog
  - security/smack/smackfs.c:smk_write_ptrace
  - security/smack/smackfs.c:smk_write_relabel_self
  - security/smack/smackfs.c:smk_write_syslog
  - security/smack/smackfs.c:smk_write_change_rule
  - security/smack/smackfs.c:smk_write_revoke_subj
  - security/smack/smackfs.c:smk_write_load2
  - security/smack/smackfs.c:smk_write_logging
  - security/smack/smackfs.c:smk_write_onlycap
  - security/smack/smackfs.c:smk_write_ambient
  - security/smack/smackfs.c:smk_write_mapped
  - security/smack/smackfs.c:smk_write_direct
  - security/smack/smackfs.c:smk_write_doi
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_write_load
```
**Symbols:**

```
ffffffff814d78e0-ffffffff814d790c: smack_privileged (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool smack_privileged(int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff814f4da7)
Location: security/smack/smack_access.c:691
Inline: True
Inline callers:
  - security/smack/smack_access.c:smk_tskacc
  - security/smack/smack_access.c:smk_tskacc
Direct callers:
  - security/smack/smack_lsm.c:smack_key_permission
  - security/smack/smack_lsm.c:smack_unix_may_send
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_syslog
  - security/smack/smackfs.c:smk_write_ptrace
  - security/smack/smackfs.c:smk_write_relabel_self
  - security/smack/smackfs.c:smk_write_syslog
  - security/smack/smackfs.c:smk_write_change_rule
  - security/smack/smackfs.c:smk_write_revoke_subj
  - security/smack/smackfs.c:smk_write_load2
  - security/smack/smackfs.c:smk_write_logging
  - security/smack/smackfs.c:smk_write_onlycap
  - security/smack/smackfs.c:smk_write_ambient
  - security/smack/smackfs.c:smk_write_mapped
  - security/smack/smackfs.c:smk_write_direct
  - security/smack/smackfs.c:smk_write_doi
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_write_load
```
**Symbols:**

```
ffffffff814f4e50-ffffffff814f4e89: smack_privileged (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool smack_privileged(int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff814fbd17)
Location: security/smack/smack_access.c:691
Inline: True
Inline callers:
  - security/smack/smack_access.c:smk_tskacc
  - security/smack/smack_access.c:smk_tskacc
Direct callers:
  - security/smack/smack_lsm.c:smack_key_permission
  - security/smack/smack_lsm.c:smack_unix_may_send
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_syslog
  - security/smack/smackfs.c:smk_write_ptrace
  - security/smack/smackfs.c:smk_write_relabel_self
  - security/smack/smackfs.c:smk_write_syslog
  - security/smack/smackfs.c:smk_write_change_rule
  - security/smack/smackfs.c:smk_write_revoke_subj
  - security/smack/smackfs.c:smk_write_load2
  - security/smack/smackfs.c:smk_write_logging
  - security/smack/smackfs.c:smk_write_onlycap
  - security/smack/smackfs.c:smk_write_ambient
  - security/smack/smackfs.c:smk_write_mapped
  - security/smack/smackfs.c:smk_write_direct
  - security/smack/smackfs.c:smk_write_doi
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_write_load
```
**Symbols:**

```
ffffffff814fbdc0-ffffffff814fbdf7: smack_privileged (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool smack_privileged(int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff8155698d)
Location: security/smack/smack_access.c:693
Inline: True
Inline callers:
  - security/smack/smack_access.c:smk_tskacc
Direct callers:
  - security/smack/smack_lsm.c:smack_key_permission
  - security/smack/smack_lsm.c:smack_unix_may_send
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_syslog
  - security/smack/smackfs.c:smk_write_ptrace
  - security/smack/smackfs.c:smk_write_relabel_self
  - security/smack/smackfs.c:smk_write_syslog
  - security/smack/smackfs.c:smk_write_change_rule
  - security/smack/smackfs.c:smk_write_revoke_subj
  - security/smack/smackfs.c:smk_write_load2
  - security/smack/smackfs.c:smk_write_logging
  - security/smack/smackfs.c:smk_write_onlycap
  - security/smack/smackfs.c:smk_write_ambient
  - security/smack/smackfs.c:smk_write_mapped
  - security/smack/smackfs.c:smk_write_direct
  - security/smack/smackfs.c:smk_write_doi
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_write_load
```
**Symbols:**

```
ffffffff81556a30-ffffffff81556a5c: smack_privileged (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool smack_privileged(int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff815f0dab)
Location: security/smack/smack_access.c:690
Inline: True
Inline callers:
  - security/smack/smack_access.c:smk_tskacc
Direct callers:
  - security/smack/smack_lsm.c:smack_key_permission
  - security/smack/smack_lsm.c:smack_unix_may_send
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_syslog
  - security/smack/smackfs.c:smk_write_ptrace
  - security/smack/smackfs.c:smk_write_relabel_self
  - security/smack/smackfs.c:smk_write_syslog
  - security/smack/smackfs.c:smk_write_change_rule
  - security/smack/smackfs.c:smk_write_revoke_subj
  - security/smack/smackfs.c:smk_write_load2
  - security/smack/smackfs.c:smk_write_logging
  - security/smack/smackfs.c:smk_write_onlycap
  - security/smack/smackfs.c:smk_write_ambient
  - security/smack/smackfs.c:smk_write_mapped
  - security/smack/smackfs.c:smk_write_direct
  - security/smack/smackfs.c:smk_write_doi
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_write_load
```
**Symbols:**

```
ffffffff815f0e60-ffffffff815f0e9c: smack_privileged (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool smack_privileged(int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff816a121b)
Location: security/smack/smack_access.c:687
Inline: True
Inline callers:
  - security/smack/smack_access.c:smk_tskacc
Direct callers:
  - security/smack/smack_lsm.c:smack_key_permission
  - security/smack/smack_lsm.c:smack_unix_may_send
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_syslog
  - security/smack/smackfs.c:smk_write_ptrace
  - security/smack/smackfs.c:smk_write_relabel_self
  - security/smack/smackfs.c:smk_write_syslog
  - security/smack/smackfs.c:smk_write_change_rule
  - security/smack/smackfs.c:smk_write_revoke_subj
  - security/smack/smackfs.c:smk_write_load2
  - security/smack/smackfs.c:smk_write_logging
  - security/smack/smackfs.c:smk_write_onlycap
  - security/smack/smackfs.c:smk_write_ambient
  - security/smack/smackfs.c:smk_write_mapped
  - security/smack/smackfs.c:smk_write_direct
  - security/smack/smackfs.c:smk_write_doi
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_write_load
```
**Symbols:**

```
ffffffff816a12f0-ffffffff816a132c: smack_privileged (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool smack_privileged(int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff816d9b5c)
Location: security/smack/smack_access.c:687
Inline: True
Inline callers:
  - security/smack/smack_access.c:smk_tskacc
Direct callers:
  - security/smack/smack_lsm.c:smack_key_permission
  - security/smack/smack_lsm.c:smack_unix_may_send
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_syslog
  - security/smack/smackfs.c:smk_write_ptrace
  - security/smack/smackfs.c:smk_write_relabel_self
  - security/smack/smackfs.c:smk_write_syslog
  - security/smack/smackfs.c:smk_write_change_rule
  - security/smack/smackfs.c:smk_write_revoke_subj
  - security/smack/smackfs.c:smk_write_load2
  - security/smack/smackfs.c:smk_write_logging
  - security/smack/smackfs.c:smk_write_onlycap
  - security/smack/smackfs.c:smk_write_ambient
  - security/smack/smackfs.c:smk_write_mapped
  - security/smack/smackfs.c:smk_write_direct
  - security/smack/smackfs.c:smk_write_doi
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_write_load
```
**Symbols:**

```
ffffffff816d9c40-ffffffff816d9c7c: smack_privileged (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool smack_privileged(int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff817165fc)
Location: security/smack/smack_access.c:687
Inline: True
Inline callers:
  - security/smack/smack_access.c:smk_tskacc
Direct callers:
  - security/smack/smack_lsm.c:smack_key_permission
  - security/smack/smack_lsm.c:smack_unix_may_send
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:do_setattr
  - security/smack/smack_lsm.c:do_setattr
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_syslog
  - security/smack/smackfs.c:smk_write_ptrace
  - security/smack/smackfs.c:smk_write_relabel_self
  - security/smack/smackfs.c:smk_write_syslog
  - security/smack/smackfs.c:smk_write_change_rule
  - security/smack/smackfs.c:smk_write_revoke_subj
  - security/smack/smackfs.c:smk_write_load2
  - security/smack/smackfs.c:smk_write_logging
  - security/smack/smackfs.c:smk_write_onlycap
  - security/smack/smackfs.c:smk_write_ambient
  - security/smack/smackfs.c:smk_write_mapped
  - security/smack/smackfs.c:smk_write_direct
  - security/smack/smackfs.c:smk_write_doi
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_write_load
```
**Symbols:**

```
ffffffff817166e0-ffffffff8171671c: smack_privileged (STB_GLOBAL)
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
bool smack_privileged(int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffff8000105731e0)
Location: security/smack/smack_access.c:669
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_unix_may_send
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_syslog
  - security/smack/smack_access.c:smk_tskacc
  - security/smack/smackfs.c:smk_write_ptrace
  - security/smack/smackfs.c:smk_write_relabel_self
  - security/smack/smackfs.c:smk_write_syslog
  - security/smack/smackfs.c:smk_write_change_rule
  - security/smack/smackfs.c:smk_write_revoke_subj
  - security/smack/smackfs.c:smk_write_load2
  - security/smack/smackfs.c:smk_write_logging
  - security/smack/smackfs.c:smk_write_onlycap
  - security/smack/smackfs.c:smk_write_ambient
  - security/smack/smackfs.c:smk_write_mapped
  - security/smack/smackfs.c:smk_write_direct
  - security/smack/smackfs.c:smk_write_doi
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_write_load
```
**Symbols:**

```
ffff8000105731e0-ffff800010573230: smack_privileged (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool smack_privileged(int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (c072633c)
Location: security/smack/smack_access.c:669
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_unix_may_send
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_syslog
  - security/smack/smack_access.c:smk_tskacc
  - security/smack/smackfs.c:smk_write_ptrace
  - security/smack/smackfs.c:smk_write_relabel_self
  - security/smack/smackfs.c:smk_write_syslog
  - security/smack/smackfs.c:smk_write_change_rule
  - security/smack/smackfs.c:smk_write_revoke_subj
  - security/smack/smackfs.c:smk_write_load2
  - security/smack/smackfs.c:smk_write_logging
  - security/smack/smackfs.c:smk_write_onlycap
  - security/smack/smackfs.c:smk_write_ambient
  - security/smack/smackfs.c:smk_write_mapped
  - security/smack/smackfs.c:smk_write_direct
  - security/smack/smackfs.c:smk_write_doi
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_write_load
```
**Symbols:**

```
c072633c-c0726380: smack_privileged (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool smack_privileged(int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (c0000000006db4b0)
Location: security/smack/smack_access.c:669
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_unix_may_send
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_syslog
  - security/smack/smack_access.c:smk_tskacc
  - security/smack/smackfs.c:smk_write_ptrace
  - security/smack/smackfs.c:smk_write_relabel_self
  - security/smack/smackfs.c:smk_write_syslog
  - security/smack/smackfs.c:smk_write_change_rule
  - security/smack/smackfs.c:smk_write_revoke_subj
  - security/smack/smackfs.c:smk_write_load2
  - security/smack/smackfs.c:smk_write_logging
  - security/smack/smackfs.c:smk_write_onlycap
  - security/smack/smackfs.c:smk_write_ambient
  - security/smack/smackfs.c:smk_write_mapped
  - security/smack/smackfs.c:smk_write_direct
  - security/smack/smackfs.c:smk_write_doi
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_write_load
```
**Symbols:**

```
c0000000006db4b0-c0000000006db4e8: smack_privileged (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool smack_privileged(int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffe0003c66b8)
Location: security/smack/smack_access.c:669
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_unix_may_send
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_syslog
  - security/smack/smack_access.c:smk_tskacc
  - security/smack/smackfs.c:smk_write_ptrace
  - security/smack/smackfs.c:smk_write_relabel_self
  - security/smack/smackfs.c:smk_write_syslog
  - security/smack/smackfs.c:smk_write_change_rule
  - security/smack/smackfs.c:smk_write_revoke_subj
  - security/smack/smackfs.c:smk_write_load2
  - security/smack/smackfs.c:smk_write_logging
  - security/smack/smackfs.c:smk_write_onlycap
  - security/smack/smackfs.c:smk_write_ambient
  - security/smack/smackfs.c:smk_write_mapped
  - security/smack/smackfs.c:smk_write_direct
  - security/smack/smackfs.c:smk_write_doi
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_write_load
```
**Symbols:**

```
ffffffe0003c66b8-ffffffe0003c66fe: smack_privileged (STB_GLOBAL)
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
bool smack_privileged(int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff81479d90)
Location: security/smack/smack_access.c:669
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_unix_may_send
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_syslog
  - security/smack/smack_access.c:smk_tskacc
  - security/smack/smackfs.c:smk_write_ptrace
  - security/smack/smackfs.c:smk_write_relabel_self
  - security/smack/smackfs.c:smk_write_syslog
  - security/smack/smackfs.c:smk_write_change_rule
  - security/smack/smackfs.c:smk_write_revoke_subj
  - security/smack/smackfs.c:smk_write_load2
  - security/smack/smackfs.c:smk_write_logging
  - security/smack/smackfs.c:smk_write_onlycap
  - security/smack/smackfs.c:smk_write_ambient
  - security/smack/smackfs.c:smk_write_mapped
  - security/smack/smackfs.c:smk_write_direct
  - security/smack/smackfs.c:smk_write_doi
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_write_load
```
**Symbols:**

```
ffffffff81479d90-ffffffff81479dbc: smack_privileged (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool smack_privileged(int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff8146a7b0)
Location: security/smack/smack_access.c:669
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_unix_may_send
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_syslog
  - security/smack/smack_access.c:smk_tskacc
  - security/smack/smackfs.c:smk_write_ptrace
  - security/smack/smackfs.c:smk_write_relabel_self
  - security/smack/smackfs.c:smk_write_syslog
  - security/smack/smackfs.c:smk_write_change_rule
  - security/smack/smackfs.c:smk_write_revoke_subj
  - security/smack/smackfs.c:smk_write_load2
  - security/smack/smackfs.c:smk_write_logging
  - security/smack/smackfs.c:smk_write_onlycap
  - security/smack/smackfs.c:smk_write_ambient
  - security/smack/smackfs.c:smk_write_mapped
  - security/smack/smackfs.c:smk_write_direct
  - security/smack/smackfs.c:smk_write_doi
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_write_load
```
**Symbols:**

```
ffffffff8146a7b0-ffffffff8146a7dc: smack_privileged (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool smack_privileged(int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff81475e30)
Location: security/smack/smack_access.c:669
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_unix_may_send
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_syslog
  - security/smack/smack_access.c:smk_tskacc
  - security/smack/smackfs.c:smk_write_ptrace
  - security/smack/smackfs.c:smk_write_relabel_self
  - security/smack/smackfs.c:smk_write_syslog
  - security/smack/smackfs.c:smk_write_change_rule
  - security/smack/smackfs.c:smk_write_revoke_subj
  - security/smack/smackfs.c:smk_write_load2
  - security/smack/smackfs.c:smk_write_logging
  - security/smack/smackfs.c:smk_write_onlycap
  - security/smack/smackfs.c:smk_write_ambient
  - security/smack/smackfs.c:smk_write_mapped
  - security/smack/smackfs.c:smk_write_direct
  - security/smack/smackfs.c:smk_write_doi
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_write_load
```
**Symbols:**

```
ffffffff81475e30-ffffffff81475e5c: smack_privileged (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool smack_privileged(int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff8148d8b0)
Location: security/smack/smack_access.c:669
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_unix_may_send
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_syslog
  - security/smack/smack_access.c:smk_tskacc
  - security/smack/smackfs.c:smk_write_ptrace
  - security/smack/smackfs.c:smk_write_relabel_self
  - security/smack/smackfs.c:smk_write_syslog
  - security/smack/smackfs.c:smk_write_change_rule
  - security/smack/smackfs.c:smk_write_revoke_subj
  - security/smack/smackfs.c:smk_write_load2
  - security/smack/smackfs.c:smk_write_logging
  - security/smack/smackfs.c:smk_write_onlycap
  - security/smack/smackfs.c:smk_write_ambient
  - security/smack/smackfs.c:smk_write_mapped
  - security/smack/smackfs.c:smk_write_direct
  - security/smack/smackfs.c:smk_write_doi
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_write_load
```
**Symbols:**

```
ffffffff8148d8b0-ffffffff8148d8dc: smack_privileged (STB_GLOBAL)
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
<code>int</code> ➡️ <code>bool</code>
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
