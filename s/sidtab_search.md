# Function: <code>sidtab_search</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct context *sidtab_search(struct sidtab *s, u32 sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/sidtab.c (ffffffff8134ea90)
Location: security/selinux/ss/sidtab.c:115
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_validate_transition
  - security/selinux/ss/services.c:security_validate_transition
  - security/selinux/ss/services.c:security_validate_transition
  - security/selinux/ss/services.c:security_bounded_transition
  - security/selinux/ss/services.c:security_bounded_transition
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_av
  - security/selinux/ss/services.c:security_compute_av
  - security/selinux/ss/services.c:security_compute_av_user
  - security/selinux/ss/services.c:security_compute_av_user
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_net_peersid_resolve
  - security/selinux/ss/services.c:security_net_peersid_resolve
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
  - security/selinux/ss/services.c:security_netlbl_sid_to_secattr
```
**Symbols:**

```
ffffffff8134ea90-ffffffff8134eaa2: sidtab_search (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct context *sidtab_search(struct sidtab *s, u32 sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/sidtab.c (ffffffff81384a80)
Location: security/selinux/ss/sidtab.c:115
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_netlbl_sid_to_secattr
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:security_net_peersid_resolve
  - security/selinux/ss/services.c:security_net_peersid_resolve
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_compute_av_user
  - security/selinux/ss/services.c:security_compute_av_user
  - security/selinux/ss/services.c:security_compute_av
  - security/selinux/ss/services.c:security_compute_av
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_bounded_transition
  - security/selinux/ss/services.c:security_bounded_transition
```
**Symbols:**

```
ffffffff81384a80-ffffffff81384a92: sidtab_search (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct context *sidtab_search(struct sidtab *s, u32 sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/sidtab.c (ffffffff8139b510)
Location: security/selinux/ss/sidtab.c:115
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_netlbl_sid_to_secattr
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:security_net_peersid_resolve
  - security/selinux/ss/services.c:security_net_peersid_resolve
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_compute_av_user
  - security/selinux/ss/services.c:security_compute_av_user
  - security/selinux/ss/services.c:security_compute_av
  - security/selinux/ss/services.c:security_compute_av
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_bounded_transition
  - security/selinux/ss/services.c:security_bounded_transition
```
**Symbols:**

```
ffffffff8139b510-ffffffff8139b522: sidtab_search (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct context *sidtab_search(struct sidtab *s, u32 sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/sidtab.c (ffffffff813b1c30)
Location: security/selinux/ss/sidtab.c:108
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_netlbl_sid_to_secattr
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:security_net_peersid_resolve
  - security/selinux/ss/services.c:security_net_peersid_resolve
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_sid_to_context_core
  - security/selinux/ss/services.c:security_compute_av_user
  - security/selinux/ss/services.c:security_compute_av_user
  - security/selinux/ss/services.c:security_compute_av
  - security/selinux/ss/services.c:security_compute_av
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_bounded_transition
  - security/selinux/ss/services.c:security_bounded_transition
  - security/selinux/ss/mls.c:mls_context_to_sid
```
**Symbols:**

```
ffffffff813b1c30-ffffffff813b1c42: sidtab_search (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct context *sidtab_search(struct sidtab *s, u32 sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/sidtab.c (ffffffff813d7d70)
Location: security/selinux/ss/sidtab.c:109
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_netlbl_sid_to_secattr
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:security_net_peersid_resolve
  - security/selinux/ss/services.c:security_net_peersid_resolve
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_sid_to_context_core
  - security/selinux/ss/services.c:security_compute_av_user
  - security/selinux/ss/services.c:security_compute_av_user
  - security/selinux/ss/services.c:security_compute_av
  - security/selinux/ss/services.c:security_compute_av
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_bounded_transition
  - security/selinux/ss/services.c:security_bounded_transition
  - security/selinux/ss/mls.c:mls_context_to_sid
```
**Symbols:**

```
ffffffff813d7d70-ffffffff813d7d82: sidtab_search (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct context *sidtab_search(struct sidtab *s, u32 sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/sidtab.c (ffffffff814083a0)
Location: security/selinux/ss/sidtab.c:109
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_netlbl_sid_to_secattr
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:security_net_peersid_resolve
  - security/selinux/ss/services.c:security_net_peersid_resolve
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_compute_av_user
  - security/selinux/ss/services.c:security_compute_av_user
  - security/selinux/ss/services.c:security_compute_av
  - security/selinux/ss/services.c:security_compute_av
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_bounded_transition
  - security/selinux/ss/services.c:security_bounded_transition
  - security/selinux/ss/mls.c:mls_context_to_sid
```
**Symbols:**

```
ffffffff814083a0-ffffffff814083b2: sidtab_search (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct context *sidtab_search(struct sidtab *s, u32 sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/sidtab.c (ffffffff81424470)
Location: security/selinux/ss/sidtab.c:165
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_netlbl_sid_to_secattr
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:security_net_peersid_resolve
  - security/selinux/ss/services.c:security_net_peersid_resolve
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_compute_av_user
  - security/selinux/ss/services.c:security_compute_av_user
  - security/selinux/ss/services.c:security_compute_av
  - security/selinux/ss/services.c:security_compute_av
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_bounded_transition
  - security/selinux/ss/services.c:security_bounded_transition
```
**Symbols:**

```
ffffffff81424470-ffffffff81424482: sidtab_search (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct context *sidtab_search(struct sidtab *s, u32 sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/sidtab.c (ffffffff81451fe0)
Location: security/selinux/ss/sidtab.c:165
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_netlbl_sid_to_secattr
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:security_net_peersid_resolve
  - security/selinux/ss/services.c:security_net_peersid_resolve
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_compute_av_user
  - security/selinux/ss/services.c:security_compute_av_user
  - security/selinux/ss/services.c:security_compute_av
  - security/selinux/ss/services.c:security_compute_av
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_bounded_transition
  - security/selinux/ss/services.c:security_bounded_transition
  - security/selinux/ss/mls.c:mls_context_to_sid
```
**Symbols:**

```
ffffffff81451fe0-ffffffff81451ff2: sidtab_search (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct context *sidtab_search(struct sidtab *s, u32 sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/sidtab.c (ffffffff8146bdb0)
Location: security/selinux/ss/sidtab.c:163
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_netlbl_sid_to_secattr
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:security_net_peersid_resolve
  - security/selinux/ss/services.c:security_net_peersid_resolve
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_compute_av_user
  - security/selinux/ss/services.c:security_compute_av_user
  - security/selinux/ss/services.c:security_compute_av
  - security/selinux/ss/services.c:security_compute_av
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_bounded_transition
  - security/selinux/ss/services.c:security_bounded_transition
  - security/selinux/ss/mls.c:mls_context_to_sid
```
**Symbols:**

```
ffffffff8146bdb0-ffffffff8146bdc2: sidtab_search (STB_GLOBAL)
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
In security/selinux/ss/services.c (ffffffff814cdae4)
Location: security/selinux/ss/sidtab.h:110
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_netlbl_sid_to_secattr
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:security_net_peersid_resolve
  - security/selinux/ss/services.c:security_net_peersid_resolve
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_compute_av_user
  - security/selinux/ss/services.c:security_compute_av_user
  - security/selinux/ss/services.c:security_compute_av
  - security/selinux/ss/services.c:security_compute_av
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
```
```
In security/selinux/ss/mls.c (ffffffff814cefbb)
Location: security/selinux/ss/sidtab.h:110
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814eb125)
Location: security/selinux/ss/sidtab.h:110
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_netlbl_sid_to_secattr
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:security_net_peersid_resolve
  - security/selinux/ss/services.c:security_net_peersid_resolve
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_compute_av_user
  - security/selinux/ss/services.c:security_compute_av_user
  - security/selinux/ss/services.c:security_compute_av
  - security/selinux/ss/services.c:security_compute_av
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
```
```
In security/selinux/ss/mls.c (ffffffff814ec4fb)
Location: security/selinux/ss/sidtab.h:110
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814f1df5)
Location: security/selinux/ss/sidtab.h:111
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_netlbl_sid_to_secattr
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:security_net_peersid_resolve
  - security/selinux/ss/services.c:security_net_peersid_resolve
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_compute_av_user
  - security/selinux/ss/services.c:security_compute_av_user
  - security/selinux/ss/services.c:security_compute_av
  - security/selinux/ss/services.c:security_compute_av
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
```
```
In security/selinux/ss/mls.c (ffffffff814f327b)
Location: security/selinux/ss/sidtab.h:111
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8154c4e5)
Location: security/selinux/ss/sidtab.h:111
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_netlbl_sid_to_secattr
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:security_net_peersid_resolve
  - security/selinux/ss/services.c:security_net_peersid_resolve
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_compute_av_user
  - security/selinux/ss/services.c:security_compute_av_user
  - security/selinux/ss/services.c:security_compute_av
  - security/selinux/ss/services.c:security_compute_av
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
```
```
In security/selinux/ss/mls.c (ffffffff8154db7b)
Location: security/selinux/ss/sidtab.h:111
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff815e5395)
Location: security/selinux/ss/sidtab.h:111
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_netlbl_sid_to_secattr
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:security_net_peersid_resolve
  - security/selinux/ss/services.c:security_net_peersid_resolve
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_compute_av_user
  - security/selinux/ss/services.c:security_compute_av_user
  - security/selinux/ss/services.c:security_compute_av
  - security/selinux/ss/services.c:security_compute_av
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
```
```
In security/selinux/ss/mls.c (ffffffff815e7380)
Location: security/selinux/ss/sidtab.h:111
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_context_to_sid
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff816947f5)
Location: security/selinux/ss/sidtab.h:110
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_netlbl_sid_to_secattr
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:security_net_peersid_resolve
  - security/selinux/ss/services.c:security_net_peersid_resolve
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_compute_av_user
  - security/selinux/ss/services.c:security_compute_av_user
  - security/selinux/ss/services.c:security_compute_av
  - security/selinux/ss/services.c:security_compute_av
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
```
```
In security/selinux/ss/mls.c (ffffffff81696a30)
Location: security/selinux/ss/sidtab.h:110
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_context_to_sid
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff816cccf7)
Location: security/selinux/ss/sidtab.h:110
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_netlbl_sid_to_secattr
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:security_net_peersid_resolve
  - security/selinux/ss/services.c:security_net_peersid_resolve
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_compute_av_user
  - security/selinux/ss/services.c:security_compute_av_user
  - security/selinux/ss/services.c:security_compute_av
  - security/selinux/ss/services.c:security_compute_av
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
```
```
In security/selinux/ss/mls.c (ffffffff816cef30)
Location: security/selinux/ss/sidtab.h:110
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_context_to_sid
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff817092f7)
Location: security/selinux/ss/sidtab.h:110
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_netlbl_sid_to_secattr
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
  - security/selinux/ss/services.c:security_net_peersid_resolve
  - security/selinux/ss/services.c:security_net_peersid_resolve
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_compute_av_user
  - security/selinux/ss/services.c:security_compute_av_user
  - security/selinux/ss/services.c:security_compute_av
  - security/selinux/ss/services.c:security_compute_av
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
```
```
In security/selinux/ss/mls.c (ffffffff8170b550)
Location: security/selinux/ss/sidtab.h:110
Inline: True
Inline callers:
  - security/selinux/ss/mls.c:mls_context_to_sid
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
struct context *sidtab_search(struct sidtab *s, u32 sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/sidtab.c (ffff80001055ac08)
Location: security/selinux/ss/sidtab.c:163
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_netlbl_sid_to_secattr
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:security_net_peersid_resolve
  - security/selinux/ss/services.c:security_net_peersid_resolve
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_compute_av_user
  - security/selinux/ss/services.c:security_compute_av_user
  - security/selinux/ss/services.c:security_compute_av
  - security/selinux/ss/services.c:security_compute_av
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_bounded_transition
  - security/selinux/ss/services.c:security_bounded_transition
  - security/selinux/ss/mls.c:mls_context_to_sid
```
**Symbols:**

```
ffff80001055ac08-ffff80001055ac40: sidtab_search (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct context *sidtab_search(struct sidtab *s, u32 sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/sidtab.c (c070f404)
Location: security/selinux/ss/sidtab.c:163
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_netlbl_sid_to_secattr
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:security_net_peersid_resolve
  - security/selinux/ss/services.c:security_net_peersid_resolve
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_sid_to_context_core
  - security/selinux/ss/services.c:security_compute_av_user
  - security/selinux/ss/services.c:security_compute_av_user
  - security/selinux/ss/services.c:security_compute_av
  - security/selinux/ss/services.c:security_compute_av
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_bounded_transition
  - security/selinux/ss/services.c:security_bounded_transition
  - security/selinux/ss/mls.c:mls_context_to_sid
```
**Symbols:**

```
c070f404-c070f424: sidtab_search (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct context *sidtab_search(struct sidtab *s, u32 sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/sidtab.c (c0000000006b99c0)
Location: security/selinux/ss/sidtab.c:163
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_netlbl_sid_to_secattr
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:security_net_peersid_resolve
  - security/selinux/ss/services.c:security_net_peersid_resolve
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_compute_av_user
  - security/selinux/ss/services.c:security_compute_av_user
  - security/selinux/ss/services.c:security_compute_av
  - security/selinux/ss/services.c:security_compute_av
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_bounded_transition
  - security/selinux/ss/services.c:security_bounded_transition
  - security/selinux/ss/mls.c:mls_context_to_sid
```
**Symbols:**

```
c0000000006b99c0-c0000000006b99d8: sidtab_search (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct context *sidtab_search(struct sidtab *s, u32 sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/sidtab.c (ffffffe0003b1b30)
Location: security/selinux/ss/sidtab.c:163
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_netlbl_sid_to_secattr
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:security_net_peersid_resolve
  - security/selinux/ss/services.c:security_net_peersid_resolve
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_compute_av_user
  - security/selinux/ss/services.c:security_compute_av_user
  - security/selinux/ss/services.c:security_compute_av
  - security/selinux/ss/services.c:security_compute_av
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_bounded_transition
  - security/selinux/ss/services.c:security_bounded_transition
  - security/selinux/ss/mls.c:mls_context_to_sid
```
**Symbols:**

```
ffffffe0003b1b30-ffffffe0003b1b64: sidtab_search (STB_GLOBAL)
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
struct context *sidtab_search(struct sidtab *s, u32 sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/sidtab.c (ffffffff81464390)
Location: security/selinux/ss/sidtab.c:163
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_netlbl_sid_to_secattr
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:security_net_peersid_resolve
  - security/selinux/ss/services.c:security_net_peersid_resolve
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_compute_av_user
  - security/selinux/ss/services.c:security_compute_av_user
  - security/selinux/ss/services.c:security_compute_av
  - security/selinux/ss/services.c:security_compute_av
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_bounded_transition
  - security/selinux/ss/services.c:security_bounded_transition
  - security/selinux/ss/mls.c:mls_context_to_sid
```
**Symbols:**

```
ffffffff81464390-ffffffff814643a2: sidtab_search (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct context *sidtab_search(struct sidtab *s, u32 sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/sidtab.c (ffffffff81454dc0)
Location: security/selinux/ss/sidtab.c:163
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_netlbl_sid_to_secattr
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:security_net_peersid_resolve
  - security/selinux/ss/services.c:security_net_peersid_resolve
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_compute_av_user
  - security/selinux/ss/services.c:security_compute_av_user
  - security/selinux/ss/services.c:security_compute_av
  - security/selinux/ss/services.c:security_compute_av
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_bounded_transition
  - security/selinux/ss/services.c:security_bounded_transition
  - security/selinux/ss/mls.c:mls_context_to_sid
```
**Symbols:**

```
ffffffff81454dc0-ffffffff81454dd2: sidtab_search (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct context *sidtab_search(struct sidtab *s, u32 sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/sidtab.c (ffffffff81460430)
Location: security/selinux/ss/sidtab.c:163
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_netlbl_sid_to_secattr
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:security_net_peersid_resolve
  - security/selinux/ss/services.c:security_net_peersid_resolve
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_compute_av_user
  - security/selinux/ss/services.c:security_compute_av_user
  - security/selinux/ss/services.c:security_compute_av
  - security/selinux/ss/services.c:security_compute_av
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_bounded_transition
  - security/selinux/ss/services.c:security_bounded_transition
  - security/selinux/ss/mls.c:mls_context_to_sid
```
**Symbols:**

```
ffffffff81460430-ffffffff81460442: sidtab_search (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct context *sidtab_search(struct sidtab *s, u32 sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/sidtab.c (ffffffff81477c30)
Location: security/selinux/ss/sidtab.c:163
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_netlbl_sid_to_secattr
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:security_net_peersid_resolve
  - security/selinux/ss/services.c:security_net_peersid_resolve
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_compute_av_user
  - security/selinux/ss/services.c:security_compute_av_user
  - security/selinux/ss/services.c:security_compute_av
  - security/selinux/ss/services.c:security_compute_av
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_bounded_transition
  - security/selinux/ss/services.c:security_bounded_transition
  - security/selinux/ss/mls.c:mls_context_to_sid
```
**Symbols:**

```
ffffffff81477c30-ffffffff81477c42: sidtab_search (STB_GLOBAL)
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
