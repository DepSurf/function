# Function: <code>ebitmap_get_bit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ebitmap_get_bit(struct ebitmap *e, long unsigned int bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/ebitmap.c (ffffffff8134db10)
Location: security/selinux/ss/ebitmap.c:239
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:policydb_context_isvalid
  - security/selinux/ss/policydb.c:policydb_context_isvalid
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:security_compute_av
  - security/selinux/ss/services.c:security_compute_av_user
  - security/selinux/ss/services.c:security_policycap_supported
```
**Symbols:**

```
ffffffff8134db10-ffffffff8134db6d: ebitmap_get_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ebitmap_get_bit(struct ebitmap *e, long unsigned int bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/ebitmap.c (ffffffff81383b20)
Location: security/selinux/ss/ebitmap.c:239
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:policydb_context_isvalid
  - security/selinux/ss/policydb.c:policydb_context_isvalid
  - security/selinux/ss/services.c:security_policycap_supported
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_compute_av_user
  - security/selinux/ss/services.c:security_compute_av
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
```
**Symbols:**

```
ffffffff81383b20-ffffffff81383b7d: ebitmap_get_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ebitmap_get_bit(struct ebitmap *e, long unsigned int bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/ebitmap.c (ffffffff8139a5a0)
Location: security/selinux/ss/ebitmap.c:239
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:policydb_context_isvalid
  - security/selinux/ss/policydb.c:policydb_context_isvalid
  - security/selinux/ss/services.c:security_policycap_supported
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_compute_av_user
  - security/selinux/ss/services.c:security_compute_av
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
```
**Symbols:**

```
ffffffff8139a5a0-ffffffff8139a5fd: ebitmap_get_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ebitmap_get_bit(struct ebitmap *e, long unsigned int bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/ebitmap.c (ffffffff813b0a40)
Location: security/selinux/ss/ebitmap.c:241
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:policydb_context_isvalid
  - security/selinux/ss/policydb.c:policydb_context_isvalid
  - security/selinux/ss/services.c:security_policycap_supported
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_compute_av_user
  - security/selinux/ss/services.c:security_compute_av
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
```
**Symbols:**

```
ffffffff813b0a40-ffffffff813b0ab3: ebitmap_get_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ebitmap_get_bit(struct ebitmap *e, long unsigned int bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/ebitmap.c (ffffffff813d6b30)
Location: security/selinux/ss/ebitmap.c:242
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:policydb_context_isvalid
  - security/selinux/ss/policydb.c:policydb_context_isvalid
  - security/selinux/ss/services.c:security_policycap_supported
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_compute_av_user
  - security/selinux/ss/services.c:security_compute_av
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
```
**Symbols:**

```
ffffffff813d6b30-ffffffff813d6ba1: ebitmap_get_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ebitmap_get_bit(struct ebitmap *e, long unsigned int bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/ebitmap.c (ffffffff81407140)
Location: security/selinux/ss/ebitmap.c:242
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:policydb_context_isvalid
  - security/selinux/ss/policydb.c:policydb_context_isvalid
  - security/selinux/ss/services.c:security_policycap_supported
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_compute_av_user
  - security/selinux/ss/services.c:security_compute_av
```
**Symbols:**

```
ffffffff81407140-ffffffff814071b4: ebitmap_get_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ebitmap_get_bit(struct ebitmap *e, long unsigned int bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/ebitmap.c (ffffffff81422c90)
Location: security/selinux/ss/ebitmap.c:242
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:policydb_context_isvalid
  - security/selinux/ss/policydb.c:policydb_context_isvalid
  - security/selinux/ss/services.c:security_policycap_supported
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_compute_av_user
  - security/selinux/ss/services.c:security_compute_av
```
**Symbols:**

```
ffffffff81422c90-ffffffff81422d04: ebitmap_get_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ebitmap_get_bit(struct ebitmap *e, long unsigned int bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/ebitmap.c (ffffffff814508c0)
Location: security/selinux/ss/ebitmap.c:242
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:policydb_context_isvalid
  - security/selinux/ss/policydb.c:policydb_context_isvalid
  - security/selinux/ss/services.c:security_policycap_supported
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_compute_av_user
  - security/selinux/ss/services.c:security_compute_av
```
**Symbols:**

```
ffffffff814508c0-ffffffff81450920: ebitmap_get_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ebitmap_get_bit(struct ebitmap *e, long unsigned int bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/ebitmap.c (ffffffff8146a6a0)
Location: security/selinux/ss/ebitmap.c:242
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:policydb_context_isvalid
  - security/selinux/ss/policydb.c:policydb_context_isvalid
  - security/selinux/ss/services.c:security_policycap_supported
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_compute_av_user
  - security/selinux/ss/services.c:security_compute_av
```
**Symbols:**

```
ffffffff8146a6a0-ffffffff8146a700: ebitmap_get_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ebitmap_get_bit(struct ebitmap *e, long unsigned int bit);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/ebitmap.c (ffffffff814bee7a)
Location: security/selinux/ss/ebitmap.c:261
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_and
Direct callers:
  - security/selinux/ss/ebitmap.c:ebitmap_and
  - security/selinux/ss/policydb.c:filename_trans_read_helper_compat
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:policydb_context_isvalid
  - security/selinux/ss/policydb.c:policydb_context_isvalid
  - security/selinux/ss/services.c:security_policycap_supported
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_compute_av_user
  - security/selinux/ss/services.c:security_compute_av
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
```
**Symbols:**

```
ffffffff814be720-ffffffff814be775: ebitmap_get_bit.part.0.isra.0 (STB_LOCAL)
ffffffff814bec10-ffffffff814bec2e: ebitmap_get_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ebitmap_get_bit(struct ebitmap *e, long unsigned int bit);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/ebitmap.c (ffffffff814dc89a)
Location: security/selinux/ss/ebitmap.c:261
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_and
Direct callers:
  - security/selinux/ss/ebitmap.c:ebitmap_and
  - security/selinux/ss/policydb.c:filename_trans_read_helper_compat
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:policydb_context_isvalid
  - security/selinux/ss/policydb.c:policydb_context_isvalid
  - security/selinux/ss/services.c:security_policycap_supported
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_compute_av_user
  - security/selinux/ss/services.c:security_compute_av
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
```
**Symbols:**

```
ffffffff814dc140-ffffffff814dc195: ebitmap_get_bit.part.0.isra.0 (STB_LOCAL)
ffffffff814dc630-ffffffff814dc64e: ebitmap_get_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ebitmap_get_bit(struct ebitmap *e, long unsigned int bit);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/ebitmap.c (ffffffff814e31ca)
Location: security/selinux/ss/ebitmap.c:261
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_and
Direct callers:
  - security/selinux/ss/ebitmap.c:ebitmap_and
  - security/selinux/ss/policydb.c:filename_trans_read_helper_compat
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:policydb_context_isvalid
  - security/selinux/ss/policydb.c:policydb_context_isvalid
  - security/selinux/ss/services.c:security_policycap_supported
  - security/selinux/ss/services.c:selinux_policy_commit
  - security/selinux/ss/services.c:selinux_policy_commit
  - security/selinux/ss/services.c:security_compute_av_user
  - security/selinux/ss/services.c:security_compute_av
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
```
**Symbols:**

```
ffffffff814e2a80-ffffffff814e2ad5: ebitmap_get_bit.part.0.isra.0 (STB_LOCAL)
ffffffff814e2f60-ffffffff814e2f7e: ebitmap_get_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ebitmap_get_bit(struct ebitmap *e, long unsigned int bit);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/ebitmap.c (ffffffff8153c58a)
Location: security/selinux/ss/ebitmap.c:261
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_and
Direct callers:
  - security/selinux/ss/ebitmap.c:ebitmap_and
  - security/selinux/ss/policydb.c:filename_trans_read_helper_compat
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:policydb_context_isvalid
  - security/selinux/ss/policydb.c:policydb_context_isvalid
  - security/selinux/ss/services.c:security_policycap_supported
  - security/selinux/ss/services.c:selinux_policy_commit
  - security/selinux/ss/services.c:selinux_policy_commit
  - security/selinux/ss/services.c:security_compute_av_user
  - security/selinux/ss/services.c:security_compute_av
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
```
**Symbols:**

```
ffffffff8153bc40-ffffffff8153bccf: ebitmap_get_bit.part.0.isra.0 (STB_LOCAL)
ffffffff8153c270-ffffffff8153c28e: ebitmap_get_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ebitmap_get_bit(struct ebitmap *e, long unsigned int bit);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/ebitmap.c (ffffffff815d3edb)
Location: security/selinux/ss/ebitmap.c:261
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_and
Direct callers:
  - security/selinux/ss/ebitmap.c:ebitmap_and
  - security/selinux/ss/policydb.c:filename_trans_read_helper_compat
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:policydb_context_isvalid
  - security/selinux/ss/policydb.c:policydb_context_isvalid
  - security/selinux/ss/services.c:security_policycap_supported
  - security/selinux/ss/services.c:selinux_policy_commit
  - security/selinux/ss/services.c:selinux_policy_commit
  - security/selinux/ss/services.c:security_compute_sid
  - security/selinux/ss/services.c:security_compute_sid
  - security/selinux/ss/services.c:security_compute_av_user
  - security/selinux/ss/services.c:security_compute_av
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
```
**Symbols:**

```
ffffffff815d34b0-ffffffff815d3567: ebitmap_get_bit.part.0.isra.0 (STB_LOCAL)
ffffffff815d3ba0-ffffffff815d3bd2: ebitmap_get_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ebitmap_get_bit(const struct ebitmap *e, long unsigned int bit);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/ebitmap.c (ffffffff81681fab)
Location: security/selinux/ss/ebitmap.c:262
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_and
Direct callers:
  - security/selinux/ss/ebitmap.c:ebitmap_and
  - security/selinux/ss/policydb.c:filename_trans_read_helper_compat
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:policydb_context_isvalid
  - security/selinux/ss/policydb.c:policydb_context_isvalid
  - security/selinux/ss/services.c:security_policycap_supported
  - security/selinux/ss/services.c:selinux_policy_commit
  - security/selinux/ss/services.c:selinux_policy_commit
  - security/selinux/ss/services.c:security_compute_sid
  - security/selinux/ss/services.c:security_compute_sid
  - security/selinux/ss/services.c:security_compute_av_user
  - security/selinux/ss/services.c:security_compute_av
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
```
**Symbols:**

```
ffffffff81681500-ffffffff816815b7: ebitmap_get_bit.part.0.isra.0 (STB_LOCAL)
ffffffff81681c50-ffffffff81681c82: ebitmap_get_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ebitmap_get_bit(const struct ebitmap *e, long unsigned int bit);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/ebitmap.c (ffffffff816ba12b)
Location: security/selinux/ss/ebitmap.c:262
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_and
Direct callers:
  - security/selinux/ss/ebitmap.c:ebitmap_and
  - security/selinux/ss/policydb.c:filename_trans_read_helper_compat
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:policydb_context_isvalid
  - security/selinux/ss/policydb.c:policydb_context_isvalid
  - security/selinux/ss/services.c:security_policycap_supported
  - security/selinux/ss/services.c:selinux_policy_commit
  - security/selinux/ss/services.c:selinux_policy_commit
  - security/selinux/ss/services.c:security_compute_sid
  - security/selinux/ss/services.c:security_compute_sid
  - security/selinux/ss/services.c:security_compute_av_user
  - security/selinux/ss/services.c:security_compute_av
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
```
**Symbols:**

```
ffffffff816b96b0-ffffffff816b9767: ebitmap_get_bit.part.0.isra.0 (STB_LOCAL)
ffffffff816b9e00-ffffffff816b9e32: ebitmap_get_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ebitmap_get_bit(const struct ebitmap *e, long unsigned int bit);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/ebitmap.c (ffffffff816f6bbb)
Location: security/selinux/ss/ebitmap.c:262
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_and
Direct callers:
  - security/selinux/ss/ebitmap.c:ebitmap_and
  - security/selinux/ss/policydb.c:filename_trans_read_helper_compat
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:policydb_context_isvalid
  - security/selinux/ss/policydb.c:policydb_context_isvalid
  - security/selinux/ss/policydb.c:policydb_load_isids
  - security/selinux/ss/services.c:security_policycap_supported
  - security/selinux/ss/services.c:selinux_policy_commit
  - security/selinux/ss/services.c:selinux_policy_commit
  - security/selinux/ss/services.c:security_compute_sid
  - security/selinux/ss/services.c:security_compute_sid
  - security/selinux/ss/services.c:security_compute_av_user
  - security/selinux/ss/services.c:security_compute_av
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
```
**Symbols:**

```
ffffffff816f6140-ffffffff816f61f7: ebitmap_get_bit.part.0.isra.0 (STB_LOCAL)
ffffffff816f6890-ffffffff816f68c2: ebitmap_get_bit (STB_GLOBAL)
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
int ebitmap_get_bit(struct ebitmap *e, long unsigned int bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/ebitmap.c (ffff800010559310)
Location: security/selinux/ss/ebitmap.c:242
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:policydb_context_isvalid
  - security/selinux/ss/policydb.c:policydb_context_isvalid
  - security/selinux/ss/services.c:security_policycap_supported
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_compute_av_user
  - security/selinux/ss/services.c:security_compute_av
```
**Symbols:**

```
ffff800010559310-ffff8000105593b0: ebitmap_get_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ebitmap_get_bit(struct ebitmap *e, long unsigned int bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/ebitmap.c (c070db80)
Location: security/selinux/ss/ebitmap.c:242
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:policydb_context_isvalid
  - security/selinux/ss/policydb.c:policydb_context_isvalid
  - security/selinux/ss/services.c:security_policycap_supported
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_compute_av_user
  - security/selinux/ss/services.c:security_compute_av
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
```
**Symbols:**

```
c070db80-c070dbfc: ebitmap_get_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ebitmap_get_bit(struct ebitmap *e, long unsigned int bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/ebitmap.c (c0000000006b7330)
Location: security/selinux/ss/ebitmap.c:242
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:policydb_context_isvalid
  - security/selinux/ss/policydb.c:policydb_context_isvalid
  - security/selinux/ss/services.c:security_policycap_supported
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_compute_av_user
  - security/selinux/ss/services.c:security_compute_av
```
**Symbols:**

```
c0000000006b7330-c0000000006b73c0: ebitmap_get_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ebitmap_get_bit(struct ebitmap *e, long unsigned int bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/ebitmap.c (ffffffe0003b0428)
Location: security/selinux/ss/ebitmap.c:242
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:policydb_context_isvalid
  - security/selinux/ss/policydb.c:policydb_context_isvalid
  - security/selinux/ss/services.c:security_policycap_supported
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_compute_av_user
  - security/selinux/ss/services.c:security_compute_av
```
**Symbols:**

```
ffffffe0003b0428-ffffffe0003b04ac: ebitmap_get_bit (STB_GLOBAL)
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
int ebitmap_get_bit(struct ebitmap *e, long unsigned int bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/ebitmap.c (ffffffff81462c80)
Location: security/selinux/ss/ebitmap.c:242
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:policydb_context_isvalid
  - security/selinux/ss/policydb.c:policydb_context_isvalid
  - security/selinux/ss/services.c:security_policycap_supported
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_compute_av_user
  - security/selinux/ss/services.c:security_compute_av
```
**Symbols:**

```
ffffffff81462c80-ffffffff81462ce0: ebitmap_get_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ebitmap_get_bit(struct ebitmap *e, long unsigned int bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/ebitmap.c (ffffffff814536b0)
Location: security/selinux/ss/ebitmap.c:242
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:policydb_context_isvalid
  - security/selinux/ss/policydb.c:policydb_context_isvalid
  - security/selinux/ss/services.c:security_policycap_supported
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_compute_av_user
  - security/selinux/ss/services.c:security_compute_av
```
**Symbols:**

```
ffffffff814536b0-ffffffff81453710: ebitmap_get_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ebitmap_get_bit(struct ebitmap *e, long unsigned int bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/ebitmap.c (ffffffff8145ed20)
Location: security/selinux/ss/ebitmap.c:242
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:policydb_context_isvalid
  - security/selinux/ss/policydb.c:policydb_context_isvalid
  - security/selinux/ss/services.c:security_policycap_supported
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_compute_av_user
  - security/selinux/ss/services.c:security_compute_av
```
**Symbols:**

```
ffffffff8145ed20-ffffffff8145ed80: ebitmap_get_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ebitmap_get_bit(struct ebitmap *e, long unsigned int bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/ebitmap.c (ffffffff81476530)
Location: security/selinux/ss/ebitmap.c:242
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/policydb.c:policydb_context_isvalid
  - security/selinux/ss/policydb.c:policydb_context_isvalid
  - security/selinux/ss/services.c:security_policycap_supported
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_load_policycaps
  - security/selinux/ss/services.c:security_compute_av_user
  - security/selinux/ss/services.c:security_compute_av
```
**Symbols:**

```
ffffffff81476530-ffffffff81476590: ebitmap_get_bit (STB_GLOBAL)
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
<code>struct ebitmap *e</code> ➡️ <code>const struct ebitmap *e</code>
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
