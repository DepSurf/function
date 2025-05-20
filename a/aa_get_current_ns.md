# Function: <code>aa_get_current_ns</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff81375c46)
Location: security/apparmor/include/context.h:184
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_start
```
```
In security/apparmor/policy.c (ffffffff81380732)
Location: security/apparmor/include/context.h:184
Inline: True
Inline callers:
  - security/apparmor/policy.c:policy_admin_capable
  - security/apparmor/policy.c:aa_may_open_profiles
```
```
In security/apparmor/procattr.c (ffffffff81382c9b)
Location: security/apparmor/include/context.h:184
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff81386b46)
Location: security/apparmor/include/context.h:184
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_post_create
```
```
In security/apparmor/label.c (ffffffff8138d116)
Location: security/apparmor/include/context.h:184
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_printk
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff813acb96)
Location: security/apparmor/include/context.h:184
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_start
```
```
In security/apparmor/policy.c (ffffffff813ba128)
Location: security/apparmor/include/context.h:184
Inline: True
Inline callers:
  - security/apparmor/policy.c:policy_view_capable
```
```
In security/apparmor/procattr.c (ffffffff813bcf1f)
Location: security/apparmor/include/context.h:184
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff813c14c6)
Location: security/apparmor/include/context.h:184
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_post_create
```
```
In security/apparmor/label.c (ffffffff813c8356)
Location: security/apparmor/include/context.h:184
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff813c39a6)
Location: security/apparmor/include/context.h:184
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:ns_revision_open
```
```
In security/apparmor/policy.c (ffffffff813d14e8)
Location: security/apparmor/include/context.h:184
Inline: True
Inline callers:
  - security/apparmor/policy.c:policy_view_capable
```
```
In security/apparmor/procattr.c (ffffffff813d434f)
Location: security/apparmor/include/context.h:184
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff813d8966)
Location: security/apparmor/include/context.h:184
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_post_create
```
```
In security/apparmor/label.c (ffffffff813df936)
Location: security/apparmor/include/context.h:184
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff813d9e6c)
Location: security/apparmor/include/context.h:223
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:policy_readlink
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:ns_revision_open
```
```
In security/apparmor/policy.c (ffffffff813e4485)
Location: security/apparmor/include/context.h:223
Inline: True
Inline callers:
  - security/apparmor/policy.c:policy_view_capable
```
```
In security/apparmor/procattr.c (ffffffff813e7267)
Location: security/apparmor/include/context.h:223
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff813e984d)
Location: security/apparmor/include/context.h:223
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_post_create
```
```
In security/apparmor/label.c (ffffffff813ef048)
Location: security/apparmor/include/context.h:223
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff81400d2c)
Location: security/apparmor/include/context.h:223
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:policy_readlink
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:ns_revision_open
```
```
In security/apparmor/policy.c (ffffffff8140b3e5)
Location: security/apparmor/include/context.h:223
Inline: True
Inline callers:
  - security/apparmor/policy.c:policy_view_capable
```
```
In security/apparmor/procattr.c (ffffffff8140e467)
Location: security/apparmor/include/context.h:223
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff81411831)
Location: security/apparmor/include/context.h:223
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_post_create
```
```
In security/apparmor/label.c (ffffffff81416df6)
Location: security/apparmor/include/context.h:223
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff81432055)
Location: security/apparmor/include/cred.h:164
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:ns_revision_open
```
```
In security/apparmor/policy.c (ffffffff8143cd20)
Location: security/apparmor/include/cred.h:164
Inline: True
Inline callers:
  - security/apparmor/policy.c:policy_view_capable
```
```
In security/apparmor/procattr.c (ffffffff8143fff7)
Location: security/apparmor/include/cred.h:164
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff81443a9a)
Location: security/apparmor/include/cred.h:164
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_post_create
```
```
In security/apparmor/label.c (ffffffff81449145)
Location: security/apparmor/include/cred.h:164
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff8144de05)
Location: security/apparmor/include/cred.h:180
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:ns_revision_open
```
```
In security/apparmor/policy.c (ffffffff81459b83)
Location: security/apparmor/include/cred.h:180
Inline: True
Inline callers:
  - security/apparmor/policy.c:policy_view_capable
```
```
In security/apparmor/procattr.c (ffffffff8145cec7)
Location: security/apparmor/include/cred.h:180
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff814603a1)
Location: security/apparmor/include/cred.h:180
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_post_create
```
```
In security/apparmor/label.c (ffffffff814660b5)
Location: security/apparmor/include/cred.h:180
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff8147b775)
Location: security/apparmor/include/cred.h:176
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:ns_revision_open
```
```
In security/apparmor/policy.c (ffffffff81487213)
Location: security/apparmor/include/cred.h:176
Inline: True
Inline callers:
  - security/apparmor/policy.c:policy_view_capable
```
```
In security/apparmor/procattr.c (ffffffff8148a477)
Location: security/apparmor/include/cred.h:176
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff8148d2a5)
Location: security/apparmor/include/cred.h:176
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_post_create
```
```
In security/apparmor/label.c (ffffffff81493625)
Location: security/apparmor/include/cred.h:176
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff81495445)
Location: security/apparmor/include/cred.h:176
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:ns_revision_open
```
```
In security/apparmor/policy.c (ffffffff814a10c3)
Location: security/apparmor/include/cred.h:176
Inline: True
Inline callers:
  - security/apparmor/policy.c:policy_view_capable
```
```
In security/apparmor/procattr.c (ffffffff814a4337)
Location: security/apparmor/include/cred.h:176
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff814a7165)
Location: security/apparmor/include/cred.h:176
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_post_create
```
```
In security/apparmor/label.c (ffffffff814ad555)
Location: security/apparmor/include/cred.h:176
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff814ed4c5)
Location: security/apparmor/include/cred.h:176
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:ns_revision_open
```
```
In security/apparmor/policy.c (ffffffff814fb1a7)
Location: security/apparmor/include/cred.h:176
Inline: True
Inline callers:
  - security/apparmor/policy.c:policy_view_capable
```
```
In security/apparmor/procattr.c (ffffffff814ff190)
Location: security/apparmor/include/cred.h:176
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff81504c1b)
Location: security/apparmor/include/cred.h:176
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_post_create
```
```
In security/apparmor/label.c (ffffffff8150c1a5)
Location: security/apparmor/include/cred.h:176
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
struct aa_ns *aa_get_current_ns();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff8150ab68)
Location: security/apparmor/include/cred.h:176
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_start
Direct callers:
  - security/apparmor/apparmorfs.c:ns_revision_open
```
```
In security/apparmor/policy.c (ffffffff815181f7)
Location: security/apparmor/include/cred.h:176
Inline: True
Inline callers:
  - security/apparmor/policy.c:policy_view_capable
```
```
In security/apparmor/procattr.c (ffffffff8151c3d0)
Location: security/apparmor/include/cred.h:176
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff81521abb)
Location: security/apparmor/include/cred.h:176
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_post_create
```
```
In security/apparmor/label.c (ffffffff81529055)
Location: security/apparmor/include/cred.h:176
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
```
**Symbols:**

```
ffffffff8150a670-ffffffff8150a802: aa_get_current_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
struct aa_ns *aa_get_current_ns();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff815112e8)
Location: security/apparmor/include/cred.h:176
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_start
Direct callers:
  - security/apparmor/apparmorfs.c:ns_revision_open
```
```
In security/apparmor/policy.c (ffffffff8151ea57)
Location: security/apparmor/include/cred.h:176
Inline: True
Inline callers:
  - security/apparmor/policy.c:policy_view_capable
```
```
In security/apparmor/procattr.c (ffffffff81522bb0)
Location: security/apparmor/include/cred.h:176
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff81527e9b)
Location: security/apparmor/include/cred.h:176
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_post_create
```
```
In security/apparmor/label.c (ffffffff8152f1c5)
Location: security/apparmor/include/cred.h:176
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
```
**Symbols:**

```
ffffffff81511080-ffffffff8151120a: aa_get_current_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
struct aa_ns *aa_get_current_ns();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff8156eee8)
Location: security/apparmor/include/cred.h:176
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_start
Direct callers:
  - security/apparmor/apparmorfs.c:ns_revision_open
```
```
In security/apparmor/policy.c (ffffffff8157cba7)
Location: security/apparmor/include/cred.h:176
Inline: True
Inline callers:
  - security/apparmor/policy.c:policy_view_capable
```
```
In security/apparmor/procattr.c (ffffffff81580e20)
Location: security/apparmor/include/cred.h:176
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff8158612b)
Location: security/apparmor/include/cred.h:176
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_post_create
```
```
In security/apparmor/label.c (ffffffff8158d5e5)
Location: security/apparmor/include/cred.h:176
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
```
**Symbols:**

```
ffffffff8156ec80-ffffffff8156ee0a: aa_get_current_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
struct aa_ns *aa_get_current_ns();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff8160d581)
Location: security/apparmor/include/cred.h:163
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:policy_get_link
  - security/apparmor/apparmorfs.c:p_start
Direct callers:
  - security/apparmor/apparmorfs.c:ns_revision_open
```
```
In security/apparmor/procattr.c (ffffffff8161ffc0)
Location: security/apparmor/include/cred.h:163
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/label.c (ffffffff8162b3d0)
Location: security/apparmor/include/cred.h:163
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
```
**Symbols:**

```
ffffffff8160ccd0-ffffffff8160ce6a: aa_get_current_ns (STB_LOCAL)
ffffffff8162b3d0-ffffffff8162b5ac: aa_get_current_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline ⚠️</summary>

```c
struct aa_ns *aa_get_current_ns();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff816bf501)
Location: security/apparmor/include/cred.h:163
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:policy_get_link
  - security/apparmor/apparmorfs.c:p_start
Direct callers:
  - security/apparmor/apparmorfs.c:ns_revision_open
```
```
In security/apparmor/procattr.c (ffffffff816d34bd)
Location: security/apparmor/include/cred.h:163
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/label.c (ffffffff816dfc70)
Location: security/apparmor/include/cred.h:163
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
```
```
In security/apparmor/notify.c (ffffffff816e9f20)
Location: security/apparmor/include/cred.h:163
Inline: False
Direct callers:
  - security/apparmor/notify.c:aa_new_listener
  - security/apparmor/notify.c:aa_register_listener_proxy
```
**Symbols:**

```
ffffffff816bf790-ffffffff816bf92a: aa_get_current_ns (STB_LOCAL)
ffffffff816dfc70-ffffffff816dfe4c: aa_get_current_ns (STB_LOCAL)
ffffffff816e9f20-ffffffff816ea0ba: aa_get_current_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline ⚠️</summary>

```c
struct aa_ns *aa_get_current_ns();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff816f8011)
Location: security/apparmor/include/cred.h:163
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:policy_get_link
  - security/apparmor/apparmorfs.c:p_start
Direct callers:
  - security/apparmor/apparmorfs.c:ns_revision_open
```
```
In security/apparmor/procattr.c (ffffffff8170c38d)
Location: security/apparmor/include/cred.h:163
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/label.c (ffffffff81719290)
Location: security/apparmor/include/cred.h:163
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
```
```
In security/apparmor/notify.c (ffffffff81724170)
Location: security/apparmor/include/cred.h:163
Inline: False
Direct callers:
  - security/apparmor/notify.c:knotif_update_from_uresp_name
  - security/apparmor/notify.c:aa_new_listener
  - security/apparmor/notify.c:aa_register_listener_proxy
```
**Symbols:**

```
ffffffff816f8290-ffffffff816f8426: aa_get_current_ns (STB_LOCAL)
ffffffff81719290-ffffffff81719468: aa_get_current_ns (STB_LOCAL)
ffffffff81724170-ffffffff81724306: aa_get_current_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
struct aa_ns *aa_get_current_ns();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff81734d81)
Location: security/apparmor/include/cred.h:163
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:policy_get_link
  - security/apparmor/apparmorfs.c:p_start
Direct callers:
  - security/apparmor/apparmorfs.c:ns_revision_open
```
```
In security/apparmor/procattr.c (ffffffff8174a0d0)
Location: security/apparmor/include/cred.h:163
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/label.c (ffffffff81757d30)
Location: security/apparmor/include/cred.h:163
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
```
```
In security/apparmor/notify.c (ffffffff81765470)
Location: security/apparmor/include/cred.h:163
Inline: False
Direct callers:
  - security/apparmor/notify.c:knotif_update_from_uresp_name
  - security/apparmor/notify.c:aa_new_listener
  - security/apparmor/notify.c:aa_register_listener_proxy
```
**Symbols:**

```
ffffffff81735010-ffffffff817351ac: aa_get_current_ns (STB_LOCAL)
ffffffff81757d30-ffffffff81757f0e: aa_get_current_ns (STB_LOCAL)
ffffffff81765470-ffffffff8176560c: aa_get_current_ns (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffff80001058b4fc)
Location: security/apparmor/include/cred.h:176
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:ns_revision_open
```
```
In security/apparmor/policy.c (ffff800010596dc8)
Location: security/apparmor/include/cred.h:176
Inline: True
Inline callers:
  - security/apparmor/policy.c:policy_view_capable
```
```
In security/apparmor/procattr.c (ffff80001059a134)
Location: security/apparmor/include/cred.h:176
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffff80001059e138)
Location: security/apparmor/include/cred.h:176
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_post_create
```
```
In security/apparmor/label.c (ffff8000105a4a14)
Location: security/apparmor/include/cred.h:176
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (c073c08c)
Location: security/apparmor/include/cred.h:176
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:ns_revision_open
```
```
In security/apparmor/policy.c (c0747e88)
Location: security/apparmor/include/cred.h:176
Inline: True
Inline callers:
  - security/apparmor/policy.c:policy_view_capable
```
```
In security/apparmor/procattr.c (c074b238)
Location: security/apparmor/include/cred.h:176
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (c074ed30)
Location: security/apparmor/include/cred.h:176
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_post_create
```
```
In security/apparmor/label.c (c0754be8)
Location: security/apparmor/include/cred.h:176
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (c0000000006fc8d0)
Location: security/apparmor/include/cred.h:176
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:ns_revision_open
```
```
In security/apparmor/policy.c (c00000000070ce94)
Location: security/apparmor/include/cred.h:176
Inline: True
Inline callers:
  - security/apparmor/policy.c:policy_view_capable
```
```
In security/apparmor/procattr.c (c000000000711668)
Location: security/apparmor/include/cred.h:176
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (c0000000007163e4)
Location: security/apparmor/include/cred.h:176
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_post_create
```
```
In security/apparmor/label.c (c000000000720764)
Location: security/apparmor/include/cred.h:176
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffe0003d9b92)
Location: security/apparmor/include/cred.h:176
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:ns_revision_open
```
```
In security/apparmor/policy.c (ffffffe0003e3aea)
Location: security/apparmor/include/cred.h:176
Inline: True
Inline callers:
  - security/apparmor/policy.c:policy_view_capable
```
```
In security/apparmor/procattr.c (ffffffe0003e6726)
Location: security/apparmor/include/cred.h:176
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffe0003e920c)
Location: security/apparmor/include/cred.h:176
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_post_create
```
```
In security/apparmor/label.c (ffffffe0003ee9ca)
Location: security/apparmor/include/cred.h:176
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff8148da25)
Location: security/apparmor/include/cred.h:176
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:ns_revision_open
```
```
In security/apparmor/policy.c (ffffffff814996a3)
Location: security/apparmor/include/cred.h:176
Inline: True
Inline callers:
  - security/apparmor/policy.c:policy_view_capable
```
```
In security/apparmor/procattr.c (ffffffff8149c917)
Location: security/apparmor/include/cred.h:176
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff8149f745)
Location: security/apparmor/include/cred.h:176
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_post_create
```
```
In security/apparmor/label.c (ffffffff814a5b35)
Location: security/apparmor/include/cred.h:176
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff8147e445)
Location: security/apparmor/include/cred.h:176
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:ns_revision_open
```
```
In security/apparmor/policy.c (ffffffff8148a0c3)
Location: security/apparmor/include/cred.h:176
Inline: True
Inline callers:
  - security/apparmor/policy.c:policy_view_capable
```
```
In security/apparmor/procattr.c (ffffffff8148d337)
Location: security/apparmor/include/cred.h:176
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff81490165)
Location: security/apparmor/include/cred.h:176
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_post_create
```
```
In security/apparmor/label.c (ffffffff81496555)
Location: security/apparmor/include/cred.h:176
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff81489ac5)
Location: security/apparmor/include/cred.h:176
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:ns_revision_open
```
```
In security/apparmor/policy.c (ffffffff81495743)
Location: security/apparmor/include/cred.h:176
Inline: True
Inline callers:
  - security/apparmor/policy.c:policy_view_capable
```
```
In security/apparmor/procattr.c (ffffffff814989b7)
Location: security/apparmor/include/cred.h:176
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff8149b7e5)
Location: security/apparmor/include/cred.h:176
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_post_create
```
```
In security/apparmor/label.c (ffffffff814a1bd5)
Location: security/apparmor/include/cred.h:176
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff814a1745)
Location: security/apparmor/include/cred.h:176
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:ns_revision_open
```
```
In security/apparmor/policy.c (ffffffff814ad7a7)
Location: security/apparmor/include/cred.h:176
Inline: True
Inline callers:
  - security/apparmor/policy.c:policy_view_capable
```
```
In security/apparmor/procattr.c (ffffffff814b0b09)
Location: security/apparmor/include/cred.h:176
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff814b3b5b)
Location: security/apparmor/include/cred.h:176
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_post_create
```
```
In security/apparmor/label.c (ffffffff814ba375)
Location: security/apparmor/include/cred.h:176
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
