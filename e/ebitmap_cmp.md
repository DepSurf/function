# Function: <code>ebitmap_cmp</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ebitmap_cmp(struct ebitmap *e1, struct ebitmap *e2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/ebitmap.c (ffffffff8134d660)
Location: security/selinux/ss/ebitmap.c:27
Inline: False
Direct callers:
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/policydb.c:mls_write_range_helper
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:security_net_peersid_resolve
  - security/selinux/ss/services.c:security_net_peersid_resolve
  - security/selinux/ss/mls.c:mls_compute_context_len
  - security/selinux/ss/mls.c:mls_sid_to_context
```
**Symbols:**

```
ffffffff8134d660-ffffffff8134d6f2: ebitmap_cmp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ebitmap_cmp(struct ebitmap *e1, struct ebitmap *e2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/ebitmap.c (ffffffff81383640)
Location: security/selinux/ss/ebitmap.c:27
Inline: False
Direct callers:
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/policydb.c:mls_write_range_helper
  - security/selinux/ss/services.c:security_net_peersid_resolve
  - security/selinux/ss/services.c:security_net_peersid_resolve
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
```
**Symbols:**

```
ffffffff81383640-ffffffff813836d2: ebitmap_cmp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ebitmap_cmp(struct ebitmap *e1, struct ebitmap *e2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/ebitmap.c (ffffffff8139a0c0)
Location: security/selinux/ss/ebitmap.c:27
Inline: False
Direct callers:
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/policydb.c:mls_write_range_helper
  - security/selinux/ss/services.c:security_net_peersid_resolve
  - security/selinux/ss/services.c:security_net_peersid_resolve
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
```
**Symbols:**

```
ffffffff8139a0c0-ffffffff8139a152: ebitmap_cmp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ebitmap_cmp(struct ebitmap *e1, struct ebitmap *e2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/ebitmap.c (ffffffff813b0810)
Location: security/selinux/ss/ebitmap.c:29
Inline: False
Direct callers:
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:security_net_peersid_resolve
  - security/selinux/ss/services.c:security_net_peersid_resolve
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
```
**Symbols:**

```
ffffffff813b0810-ffffffff813b08a1: ebitmap_cmp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ebitmap_cmp(struct ebitmap *e1, struct ebitmap *e2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/ebitmap.c (ffffffff813d68b0)
Location: security/selinux/ss/ebitmap.c:30
Inline: False
Direct callers:
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:security_net_peersid_resolve
  - security/selinux/ss/services.c:security_net_peersid_resolve
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
```
**Symbols:**

```
ffffffff813d68b0-ffffffff813d6941: ebitmap_cmp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ebitmap_cmp(struct ebitmap *e1, struct ebitmap *e2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/ebitmap.c (ffffffff81406ec0)
Location: security/selinux/ss/ebitmap.c:30
Inline: False
Direct callers:
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/policydb.c:mls_write_range_helper
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:security_net_peersid_resolve
  - security/selinux/ss/services.c:security_net_peersid_resolve
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
```
**Symbols:**

```
ffffffff81406ec0-ffffffff81406f55: ebitmap_cmp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ebitmap_cmp(struct ebitmap *e1, struct ebitmap *e2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/ebitmap.c (ffffffff81422a10)
Location: security/selinux/ss/ebitmap.c:30
Inline: False
Direct callers:
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_find_context
  - security/selinux/ss/sidtab.c:sidtab_find_context
  - security/selinux/ss/policydb.c:mls_write_range_helper
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:security_net_peersid_resolve
  - security/selinux/ss/services.c:security_net_peersid_resolve
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
```
**Symbols:**

```
ffffffff81422a10-ffffffff81422aa5: ebitmap_cmp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ebitmap_cmp(struct ebitmap *e1, struct ebitmap *e2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/ebitmap.c (ffffffff814506d0)
Location: security/selinux/ss/ebitmap.c:30
Inline: False
Direct callers:
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_find_context
  - security/selinux/ss/sidtab.c:sidtab_find_context
  - security/selinux/ss/policydb.c:mls_write_range_helper
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:security_net_peersid_resolve
  - security/selinux/ss/services.c:security_net_peersid_resolve
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
```
**Symbols:**

```
ffffffff814506d0-ffffffff8145073f: ebitmap_cmp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ebitmap_cmp(struct ebitmap *e1, struct ebitmap *e2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/ebitmap.c (ffffffff8146a4b0)
Location: security/selinux/ss/ebitmap.c:30
Inline: False
Direct callers:
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_find_context
  - security/selinux/ss/sidtab.c:sidtab_find_context
  - security/selinux/ss/policydb.c:mls_write_range_helper
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:security_net_peersid_resolve
  - security/selinux/ss/services.c:security_net_peersid_resolve
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
```
**Symbols:**

```
ffffffff8146a4b0-ffffffff8146a51f: ebitmap_cmp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ebitmap_cmp(struct ebitmap *e1, struct ebitmap *e2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/ebitmap.c (ffffffff814be780)
Location: security/selinux/ss/ebitmap.c:31
Inline: False
Direct callers:
  - security/selinux/ss/sidtab.c:context_to_sid
  - security/selinux/ss/sidtab.c:context_to_sid
  - security/selinux/ss/policydb.c:mls_write_range_helper
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:security_net_peersid_resolve
  - security/selinux/ss/services.c:security_net_peersid_resolve
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
```
**Symbols:**

```
ffffffff814be780-ffffffff814be7ef: ebitmap_cmp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ebitmap_cmp(struct ebitmap *e1, struct ebitmap *e2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/ebitmap.c (ffffffff814dc1a0)
Location: security/selinux/ss/ebitmap.c:31
Inline: False
Direct callers:
  - security/selinux/ss/sidtab.c:context_to_sid
  - security/selinux/ss/sidtab.c:context_to_sid
  - security/selinux/ss/policydb.c:mls_write_range_helper
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:security_net_peersid_resolve
  - security/selinux/ss/services.c:security_net_peersid_resolve
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
```
**Symbols:**

```
ffffffff814dc1a0-ffffffff814dc20f: ebitmap_cmp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ebitmap_cmp(struct ebitmap *e1, struct ebitmap *e2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/ebitmap.c (ffffffff814e2ae0)
Location: security/selinux/ss/ebitmap.c:31
Inline: False
Direct callers:
  - security/selinux/ss/sidtab.c:context_to_sid
  - security/selinux/ss/sidtab.c:context_to_sid
  - security/selinux/ss/policydb.c:mls_write_range_helper
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:security_net_peersid_resolve
  - security/selinux/ss/services.c:security_net_peersid_resolve
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
```
**Symbols:**

```
ffffffff814e2ae0-ffffffff814e2b4f: ebitmap_cmp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ebitmap_cmp(struct ebitmap *e1, struct ebitmap *e2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/ebitmap.c (ffffffff8153bcd0)
Location: security/selinux/ss/ebitmap.c:31
Inline: False
Direct callers:
  - security/selinux/ss/sidtab.c:context_to_sid
  - security/selinux/ss/sidtab.c:context_to_sid
  - security/selinux/ss/policydb.c:mls_write_range_helper
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:security_net_peersid_resolve
  - security/selinux/ss/services.c:security_net_peersid_resolve
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
```
**Symbols:**

```
ffffffff8153bcd0-ffffffff8153bd3f: ebitmap_cmp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ebitmap_cmp(struct ebitmap *e1, struct ebitmap *e2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/ebitmap.c (ffffffff815d3570)
Location: security/selinux/ss/ebitmap.c:31
Inline: False
Direct callers:
  - security/selinux/ss/sidtab.c:context_to_sid
  - security/selinux/ss/sidtab.c:context_to_sid
  - security/selinux/ss/policydb.c:mls_write_range_helper
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:security_net_peersid_resolve
  - security/selinux/ss/services.c:security_net_peersid_resolve
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
```
**Symbols:**

```
ffffffff815d3570-ffffffff815d35fc: ebitmap_cmp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ebitmap_cmp(const struct ebitmap *e1, const struct ebitmap *e2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/ebitmap.c (ffffffff816815d0)
Location: security/selinux/ss/ebitmap.c:31
Inline: False
Direct callers:
  - security/selinux/ss/sidtab.c:context_to_sid
  - security/selinux/ss/sidtab.c:context_to_sid
  - security/selinux/ss/policydb.c:mls_write_range_helper
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:security_net_peersid_resolve
  - security/selinux/ss/services.c:security_net_peersid_resolve
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
```
**Symbols:**

```
ffffffff816815d0-ffffffff8168165c: ebitmap_cmp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ebitmap_cmp(const struct ebitmap *e1, const struct ebitmap *e2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/ebitmap.c (ffffffff816b9780)
Location: security/selinux/ss/ebitmap.c:31
Inline: False
Direct callers:
  - security/selinux/ss/sidtab.c:context_to_sid
  - security/selinux/ss/sidtab.c:context_to_sid
  - security/selinux/ss/policydb.c:mls_write_range_helper
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:security_net_peersid_resolve
  - security/selinux/ss/services.c:security_net_peersid_resolve
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
```
**Symbols:**

```
ffffffff816b9780-ffffffff816b9813: ebitmap_cmp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ebitmap_cmp(const struct ebitmap *e1, const struct ebitmap *e2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/ebitmap.c (ffffffff816f6210)
Location: security/selinux/ss/ebitmap.c:31
Inline: False
Direct callers:
  - security/selinux/ss/sidtab.c:context_to_sid
  - security/selinux/ss/sidtab.c:context_to_sid
  - security/selinux/ss/policydb.c:mls_write_range_helper
  - security/selinux/ss/services.c:security_net_peersid_resolve
  - security/selinux/ss/services.c:security_net_peersid_resolve
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
```
**Symbols:**

```
ffffffff816f6210-ffffffff816f62a3: ebitmap_cmp (STB_GLOBAL)
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
int ebitmap_cmp(struct ebitmap *e1, struct ebitmap *e2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/ebitmap.c (ffff800010558ff8)
Location: security/selinux/ss/ebitmap.c:30
Inline: False
Direct callers:
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_find_context
  - security/selinux/ss/sidtab.c:sidtab_find_context
  - security/selinux/ss/policydb.c:mls_write_range_helper
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:security_net_peersid_resolve
  - security/selinux/ss/services.c:security_net_peersid_resolve
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
```
**Symbols:**

```
ffff800010558ff8-ffff800010559104: ebitmap_cmp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ebitmap_cmp(struct ebitmap *e1, struct ebitmap *e2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/ebitmap.c (c070d930)
Location: security/selinux/ss/ebitmap.c:30
Inline: False
Direct callers:
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_find_context
  - security/selinux/ss/sidtab.c:sidtab_find_context
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:security_net_peersid_resolve
  - security/selinux/ss/services.c:security_net_peersid_resolve
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
```
**Symbols:**

```
c070d930-c070d9bc: ebitmap_cmp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ebitmap_cmp(struct ebitmap *e1, struct ebitmap *e2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/ebitmap.c (c0000000006b6fb0)
Location: security/selinux/ss/ebitmap.c:30
Inline: False
Direct callers:
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_find_context
  - security/selinux/ss/sidtab.c:sidtab_find_context
  - security/selinux/ss/policydb.c:mls_write_range_helper
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:security_net_peersid_resolve
  - security/selinux/ss/services.c:security_net_peersid_resolve
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
```
**Symbols:**

```
c0000000006b6fb0-c0000000006b709c: ebitmap_cmp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ebitmap_cmp(struct ebitmap *e1, struct ebitmap *e2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/ebitmap.c (ffffffe0003b01ce)
Location: security/selinux/ss/ebitmap.c:30
Inline: False
Direct callers:
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_find_context
  - security/selinux/ss/sidtab.c:sidtab_find_context
  - security/selinux/ss/policydb.c:mls_write_range_helper
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:security_net_peersid_resolve
  - security/selinux/ss/services.c:security_net_peersid_resolve
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
```
**Symbols:**

```
ffffffe0003b01ce-ffffffe0003b024a: ebitmap_cmp (STB_GLOBAL)
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
int ebitmap_cmp(struct ebitmap *e1, struct ebitmap *e2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/ebitmap.c (ffffffff81462a90)
Location: security/selinux/ss/ebitmap.c:30
Inline: False
Direct callers:
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_find_context
  - security/selinux/ss/sidtab.c:sidtab_find_context
  - security/selinux/ss/policydb.c:mls_write_range_helper
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:security_net_peersid_resolve
  - security/selinux/ss/services.c:security_net_peersid_resolve
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
```
**Symbols:**

```
ffffffff81462a90-ffffffff81462aff: ebitmap_cmp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ebitmap_cmp(struct ebitmap *e1, struct ebitmap *e2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/ebitmap.c (ffffffff814534c0)
Location: security/selinux/ss/ebitmap.c:30
Inline: False
Direct callers:
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_find_context
  - security/selinux/ss/sidtab.c:sidtab_find_context
  - security/selinux/ss/policydb.c:mls_write_range_helper
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:security_net_peersid_resolve
  - security/selinux/ss/services.c:security_net_peersid_resolve
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
```
**Symbols:**

```
ffffffff814534c0-ffffffff8145352f: ebitmap_cmp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ebitmap_cmp(struct ebitmap *e1, struct ebitmap *e2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/ebitmap.c (ffffffff8145eb30)
Location: security/selinux/ss/ebitmap.c:30
Inline: False
Direct callers:
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_find_context
  - security/selinux/ss/sidtab.c:sidtab_find_context
  - security/selinux/ss/policydb.c:mls_write_range_helper
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:security_net_peersid_resolve
  - security/selinux/ss/services.c:security_net_peersid_resolve
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
```
**Symbols:**

```
ffffffff8145eb30-ffffffff8145eb9f: ebitmap_cmp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ebitmap_cmp(struct ebitmap *e1, struct ebitmap *e2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/ebitmap.c (ffffffff81476340)
Location: security/selinux/ss/ebitmap.c:30
Inline: False
Direct callers:
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_find_context
  - security/selinux/ss/sidtab.c:sidtab_find_context
  - security/selinux/ss/policydb.c:mls_write_range_helper
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:security_net_peersid_resolve
  - security/selinux/ss/services.c:security_net_peersid_resolve
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
```
**Symbols:**

```
ffffffff81476340-ffffffff814763af: ebitmap_cmp (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct ebitmap *e1</code> ➡️ <code>const struct ebitmap *e1</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct ebitmap *e2</code> ➡️ <code>const struct ebitmap *e2</code>
</li>
</ul>
</details>
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
