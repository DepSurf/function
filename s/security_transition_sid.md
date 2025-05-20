# Function: <code>security_transition_sid</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int security_transition_sid(u32 ssid, u32 tsid, u16 tclass, const struct qstr *qstr, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff813584f0)
Location: security/selinux/ss/services.c:1753
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_determine_inode_label
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_socket_create
  - security/selinux/hooks.c:selinux_socket_post_create
```
**Symbols:**

```
ffffffff813584f0-ffffffff81358524: security_transition_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int security_transition_sid(u32 ssid, u32 tsid, u16 tclass, const struct qstr *qstr, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8138e440)
Location: security/selinux/ss/services.c:1747
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_socket_post_create
  - security/selinux/hooks.c:selinux_socket_create
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_determine_inode_label
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:selinux_set_mnt_opts
```
**Symbols:**

```
ffffffff8138e440-ffffffff8138e474: security_transition_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int security_transition_sid(u32 ssid, u32 tsid, u16 tclass, const struct qstr *qstr, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff813a5060)
Location: security/selinux/ss/services.c:1747
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_socket_post_create
  - security/selinux/hooks.c:selinux_socket_create
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:selinux_set_mnt_opts
```
**Symbols:**

```
ffffffff813a5060-ffffffff813a5094: security_transition_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int security_transition_sid(u32 ssid, u32 tsid, u16 tclass, const struct qstr *qstr, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff813bba10)
Location: security/selinux/ss/services.c:1759
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_socket_post_create
  - security/selinux/hooks.c:selinux_socket_create
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:selinux_set_mnt_opts
```
**Symbols:**

```
ffffffff813bba10-ffffffff813bba3b: security_transition_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int security_transition_sid(u32 ssid, u32 tsid, u16 tclass, const struct qstr *qstr, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff813e1b80)
Location: security/selinux/ss/services.c:1762
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_socket_post_create
  - security/selinux/hooks.c:selinux_socket_create
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:selinux_set_mnt_opts
```
**Symbols:**

```
ffffffff813e1b80-ffffffff813e1bab: security_transition_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int security_transition_sid(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, const struct qstr *qstr, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814121f0)
Location: security/selinux/ss/services.c:1823
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_socket_post_create
  - security/selinux/hooks.c:selinux_socket_create
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:selinux_set_mnt_opts
```
**Symbols:**

```
ffffffff814121f0-ffffffff81412236: security_transition_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int security_transition_sid(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, const struct qstr *qstr, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8142e710)
Location: security/selinux/ss/services.c:1816
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_socket_post_create
  - security/selinux/hooks.c:selinux_socket_create
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:selinux_set_mnt_opts
```
**Symbols:**

```
ffffffff8142e710-ffffffff8142e753: security_transition_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int security_transition_sid(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, const struct qstr *qstr, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8145c090)
Location: security/selinux/ss/services.c:1829
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_socket_post_create
  - security/selinux/hooks.c:selinux_socket_create
  - security/selinux/hooks.c:selinux_kernfs_init_security
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:selinux_set_mnt_opts
```
**Symbols:**

```
ffffffff8145c090-ffffffff8145c0d3: security_transition_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int security_transition_sid(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, const struct qstr *qstr, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81475e40)
Location: security/selinux/ss/services.c:1829
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_socket_post_create
  - security/selinux/hooks.c:selinux_socket_create
  - security/selinux/hooks.c:selinux_kernfs_init_security
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:selinux_set_mnt_opts
```
**Symbols:**

```
ffffffff81475e40-ffffffff81475e83: security_transition_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int security_transition_sid(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, const struct qstr *qstr, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814cb5f0)
Location: security/selinux/ss/services.c:1878
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_socket_post_create
  - security/selinux/hooks.c:selinux_socket_create
  - security/selinux/hooks.c:selinux_kernfs_init_security
  - security/selinux/hooks.c:selinux_bprm_creds_for_exec
  - security/selinux/hooks.c:selinux_determine_inode_label
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:selinux_set_mnt_opts
```
**Symbols:**

```
ffffffff814cb5f0-ffffffff814cb635: security_transition_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int security_transition_sid(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, const struct qstr *qstr, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814e8e00)
Location: security/selinux/ss/services.c:1902
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_socket_post_create
  - security/selinux/hooks.c:selinux_socket_create
  - security/selinux/hooks.c:selinux_kernfs_init_security
  - security/selinux/hooks.c:selinux_bprm_creds_for_exec
  - security/selinux/hooks.c:selinux_determine_inode_label
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:selinux_set_mnt_opts
```
**Symbols:**

```
ffffffff814e8e00-ffffffff814e8e45: security_transition_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int security_transition_sid(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, const struct qstr *qstr, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814ef730)
Location: security/selinux/ss/services.c:1921
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_socket_post_create
  - security/selinux/hooks.c:selinux_socket_create
  - security/selinux/hooks.c:selinux_kernfs_init_security
  - security/selinux/hooks.c:selinux_inode_init_security_anon
  - security/selinux/hooks.c:selinux_bprm_creds_for_exec
  - security/selinux/hooks.c:selinux_determine_inode_label
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:selinux_set_mnt_opts
```
**Symbols:**

```
ffffffff814ef730-ffffffff814ef775: security_transition_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int security_transition_sid(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, const struct qstr *qstr, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:1930
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_socket_post_create
  - security/selinux/hooks.c:selinux_socket_create
  - security/selinux/hooks.c:selinux_kernfs_init_security
  - security/selinux/hooks.c:selinux_inode_init_security_anon
  - security/selinux/hooks.c:selinux_bprm_creds_for_exec
  - security/selinux/hooks.c:selinux_determine_inode_label
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:selinux_set_mnt_opts
```
**Symbols:**

```
ffffffff81cd4f3e-ffffffff81cd4f6e: security_transition_sid.cold (STB_LOCAL)
ffffffff81549a60-ffffffff81549ae3: security_transition_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int security_transition_sid(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, const struct qstr *qstr, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff815e27d0)
Location: security/selinux/ss/services.c:1930
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_socket_post_create
  - security/selinux/hooks.c:selinux_socket_create
  - security/selinux/hooks.c:selinux_kernfs_init_security
  - security/selinux/hooks.c:selinux_inode_init_security_anon
  - security/selinux/hooks.c:selinux_bprm_creds_for_exec
  - security/selinux/hooks.c:selinux_determine_inode_label
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:selinux_set_mnt_opts
```
**Symbols:**

```
ffffffff815e27d0-ffffffff815e280b: security_transition_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int security_transition_sid(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, const struct qstr *qstr, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff816915a0)
Location: security/selinux/ss/services.c:1924
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_socket_post_create
  - security/selinux/hooks.c:selinux_socket_create
  - security/selinux/hooks.c:selinux_kernfs_init_security
  - security/selinux/hooks.c:selinux_inode_init_security_anon
  - security/selinux/hooks.c:selinux_bprm_creds_for_exec
  - security/selinux/hooks.c:selinux_determine_inode_label
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:selinux_set_mnt_opts
```
**Symbols:**

```
ffffffff816915a0-ffffffff816915db: security_transition_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int security_transition_sid(u32 ssid, u32 tsid, u16 tclass, const struct qstr *qstr, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff816c9b30)
Location: security/selinux/ss/services.c:1899
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_socket_post_create
  - security/selinux/hooks.c:selinux_socket_create
  - security/selinux/hooks.c:selinux_kernfs_init_security
  - security/selinux/hooks.c:selinux_inode_init_security_anon
  - security/selinux/hooks.c:selinux_bprm_creds_for_exec
  - security/selinux/hooks.c:selinux_determine_inode_label
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:selinux_set_mnt_opts
```
**Symbols:**

```
ffffffff816c9b30-ffffffff816c9b6b: security_transition_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int security_transition_sid(u32 ssid, u32 tsid, u16 tclass, const struct qstr *qstr, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81706740)
Location: security/selinux/ss/services.c:1909
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_socket_post_create
  - security/selinux/hooks.c:selinux_socket_create
  - security/selinux/hooks.c:selinux_kernfs_init_security
  - security/selinux/hooks.c:selinux_inode_init_security_anon
  - security/selinux/hooks.c:selinux_bprm_creds_for_exec
  - security/selinux/hooks.c:selinux_determine_inode_label
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:selinux_set_mnt_opts
```
**Symbols:**

```
ffffffff81706740-ffffffff8170677b: security_transition_sid (STB_GLOBAL)
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
int security_transition_sid(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, const struct qstr *qstr, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffff8000105656c0)
Location: security/selinux/ss/services.c:1829
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_socket_post_create
  - security/selinux/hooks.c:selinux_socket_create
  - security/selinux/hooks.c:selinux_kernfs_init_security
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:selinux_set_mnt_opts
```
**Symbols:**

```
ffff8000105656c0-ffff800010565778: security_transition_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int security_transition_sid(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, const struct qstr *qstr, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (c0719f78)
Location: security/selinux/ss/services.c:1829
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_socket_post_create
  - security/selinux/hooks.c:selinux_socket_create
  - security/selinux/hooks.c:selinux_kernfs_init_security
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:selinux_set_mnt_opts
```
**Symbols:**

```
c0719f78-c0719fec: security_transition_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int security_transition_sid(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, const struct qstr *qstr, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (c0000000006c7f40)
Location: security/selinux/ss/services.c:1829
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_socket_post_create
  - security/selinux/hooks.c:selinux_socket_create
  - security/selinux/hooks.c:selinux_kernfs_init_security
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:selinux_set_mnt_opts
```
**Symbols:**

```
c0000000006c7f40-c0000000006c7fac: security_transition_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int security_transition_sid(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, const struct qstr *qstr, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffe0003bbb90)
Location: security/selinux/ss/services.c:1829
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_socket_post_create
  - security/selinux/hooks.c:selinux_socket_create
  - security/selinux/hooks.c:selinux_kernfs_init_security
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:selinux_set_mnt_opts
```
**Symbols:**

```
ffffffe0003bbb90-ffffffe0003bbc06: security_transition_sid (STB_GLOBAL)
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
int security_transition_sid(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, const struct qstr *qstr, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8146e420)
Location: security/selinux/ss/services.c:1829
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_socket_post_create
  - security/selinux/hooks.c:selinux_socket_create
  - security/selinux/hooks.c:selinux_kernfs_init_security
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:selinux_set_mnt_opts
```
**Symbols:**

```
ffffffff8146e420-ffffffff8146e463: security_transition_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int security_transition_sid(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, const struct qstr *qstr, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8145ee50)
Location: security/selinux/ss/services.c:1829
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_socket_post_create
  - security/selinux/hooks.c:selinux_socket_create
  - security/selinux/hooks.c:selinux_kernfs_init_security
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:selinux_set_mnt_opts
```
**Symbols:**

```
ffffffff8145ee50-ffffffff8145ee93: security_transition_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int security_transition_sid(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, const struct qstr *qstr, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8146a4c0)
Location: security/selinux/ss/services.c:1829
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_socket_post_create
  - security/selinux/hooks.c:selinux_socket_create
  - security/selinux/hooks.c:selinux_kernfs_init_security
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:selinux_set_mnt_opts
```
**Symbols:**

```
ffffffff8146a4c0-ffffffff8146a503: security_transition_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int security_transition_sid(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, const struct qstr *qstr, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81481c60)
Location: security/selinux/ss/services.c:1829
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_socket_post_create
  - security/selinux/hooks.c:selinux_socket_create
  - security/selinux/hooks.c:selinux_kernfs_init_security
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:selinux_set_mnt_opts
```
**Symbols:**

```
ffffffff81481c60-ffffffff81481ca3: security_transition_sid (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct selinux_state *state</code>
</li>
<li>
<b>Param reordered. </b>
<code>ssid, tsid, tclass, qstr, out_sid</code> ➡️ <code>state, ssid, tsid, tclass, qstr, out_sid</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct selinux_state *state</code>
</li>
<li>
<b>Param reordered. </b>
<code>state, ssid, tsid, tclass, qstr, out_sid</code> ➡️ <code>ssid, tsid, tclass, qstr, out_sid</code>
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
