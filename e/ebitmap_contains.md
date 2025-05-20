# Function: <code>ebitmap_contains</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ebitmap_contains(struct ebitmap *e1, struct ebitmap *e2, u32 last_e2bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/ebitmap.c (ffffffff8134da50)
Location: security/selinux/ss/ebitmap.c:198
Inline: False
Direct callers:
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/mls.c:mls_level_isvalid
  - security/selinux/ss/mls.c:mls_range_isvalid
  - security/selinux/ss/mls.c:mls_context_isvalid
  - security/selinux/ss/mls.c:mls_context_isvalid
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
```
**Symbols:**

```
ffffffff8134da50-ffffffff8134db0e: ebitmap_contains (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ebitmap_contains(struct ebitmap *e1, struct ebitmap *e2, u32 last_e2bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/ebitmap.c (ffffffff81383a40)
Location: security/selinux/ss/ebitmap.c:198
Inline: False
Direct callers:
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_context_isvalid
  - security/selinux/ss/mls.c:mls_context_isvalid
  - security/selinux/ss/mls.c:mls_range_isvalid
  - security/selinux/ss/mls.c:mls_level_isvalid
```
**Symbols:**

```
ffffffff81383a40-ffffffff81383b12: ebitmap_contains (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ebitmap_contains(struct ebitmap *e1, struct ebitmap *e2, u32 last_e2bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/ebitmap.c (ffffffff8139a4c0)
Location: security/selinux/ss/ebitmap.c:198
Inline: False
Direct callers:
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_context_isvalid
  - security/selinux/ss/mls.c:mls_context_isvalid
  - security/selinux/ss/mls.c:mls_range_isvalid
  - security/selinux/ss/mls.c:mls_level_isvalid
```
**Symbols:**

```
ffffffff8139a4c0-ffffffff8139a592: ebitmap_contains (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ebitmap_contains(struct ebitmap *e1, struct ebitmap *e2, u32 last_e2bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/ebitmap.c (ffffffff813b0970)
Location: security/selinux/ss/ebitmap.c:200
Inline: False
Direct callers:
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_context_isvalid
  - security/selinux/ss/mls.c:mls_context_isvalid
  - security/selinux/ss/mls.c:mls_range_isvalid
  - security/selinux/ss/mls.c:mls_level_isvalid
```
**Symbols:**

```
ffffffff813b0970-ffffffff813b0a3d: ebitmap_contains (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ebitmap_contains(struct ebitmap *e1, struct ebitmap *e2, u32 last_e2bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/ebitmap.c (ffffffff813d6a10)
Location: security/selinux/ss/ebitmap.c:201
Inline: False
Direct callers:
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_context_isvalid
  - security/selinux/ss/mls.c:mls_context_isvalid
  - security/selinux/ss/mls.c:mls_range_isvalid
  - security/selinux/ss/mls.c:mls_level_isvalid
```
**Symbols:**

```
ffffffff813d6a10-ffffffff813d6b2a: ebitmap_contains (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ebitmap_contains(struct ebitmap *e1, struct ebitmap *e2, u32 last_e2bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/ebitmap.c (ffffffff81407030)
Location: security/selinux/ss/ebitmap.c:201
Inline: False
Direct callers:
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_context_isvalid
  - security/selinux/ss/mls.c:mls_context_isvalid
  - security/selinux/ss/mls.c:mls_range_isvalid
  - security/selinux/ss/mls.c:mls_level_isvalid
```
**Symbols:**

```
ffffffff81407030-ffffffff8140713f: ebitmap_contains (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ebitmap_contains(struct ebitmap *e1, struct ebitmap *e2, u32 last_e2bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/ebitmap.c (ffffffff81422b80)
Location: security/selinux/ss/ebitmap.c:201
Inline: False
Direct callers:
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_context_isvalid
  - security/selinux/ss/mls.c:mls_context_isvalid
  - security/selinux/ss/mls.c:mls_range_isvalid
  - security/selinux/ss/mls.c:mls_level_isvalid
```
**Symbols:**

```
ffffffff81422b80-ffffffff81422c8f: ebitmap_contains (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ebitmap_contains(struct ebitmap *e1, struct ebitmap *e2, u32 last_e2bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/ebitmap.c (ffffffff81450810)
Location: security/selinux/ss/ebitmap.c:201
Inline: False
Direct callers:
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_context_isvalid
  - security/selinux/ss/mls.c:mls_context_isvalid
  - security/selinux/ss/mls.c:mls_range_isvalid
  - security/selinux/ss/mls.c:mls_level_isvalid
```
**Symbols:**

```
ffffffff81450810-ffffffff814508ba: ebitmap_contains (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ebitmap_contains(struct ebitmap *e1, struct ebitmap *e2, u32 last_e2bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/ebitmap.c (ffffffff8146a5f0)
Location: security/selinux/ss/ebitmap.c:201
Inline: False
Direct callers:
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_context_isvalid
  - security/selinux/ss/mls.c:mls_context_isvalid
  - security/selinux/ss/mls.c:mls_range_isvalid
  - security/selinux/ss/mls.c:mls_level_isvalid
```
**Symbols:**

```
ffffffff8146a5f0-ffffffff8146a69a: ebitmap_contains (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ebitmap_contains(struct ebitmap *e1, struct ebitmap *e2, u32 last_e2bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/ebitmap.c (ffffffff814beb50)
Location: security/selinux/ss/ebitmap.c:220
Inline: False
Direct callers:
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_context_isvalid
  - security/selinux/ss/mls.c:mls_context_isvalid
  - security/selinux/ss/mls.c:mls_range_isvalid
  - security/selinux/ss/mls.c:mls_range_isvalid
```
**Symbols:**

```
ffffffff814beb50-ffffffff814bec0f: ebitmap_contains (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ebitmap_contains(struct ebitmap *e1, struct ebitmap *e2, u32 last_e2bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/ebitmap.c (ffffffff814dc570)
Location: security/selinux/ss/ebitmap.c:220
Inline: False
Direct callers:
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_context_isvalid
  - security/selinux/ss/mls.c:mls_context_isvalid
  - security/selinux/ss/mls.c:mls_range_isvalid
  - security/selinux/ss/mls.c:mls_range_isvalid
```
**Symbols:**

```
ffffffff814dc570-ffffffff814dc62f: ebitmap_contains (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ebitmap_contains(struct ebitmap *e1, struct ebitmap *e2, u32 last_e2bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/ebitmap.c (ffffffff814e2eb0)
Location: security/selinux/ss/ebitmap.c:220
Inline: False
Direct callers:
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_context_isvalid
  - security/selinux/ss/mls.c:mls_context_isvalid
  - security/selinux/ss/mls.c:mls_range_isvalid
  - security/selinux/ss/mls.c:mls_range_isvalid
```
**Symbols:**

```
ffffffff814e2eb0-ffffffff814e2f51: ebitmap_contains (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ebitmap_contains(struct ebitmap *e1, struct ebitmap *e2, u32 last_e2bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/ebitmap.c (ffffffff8153c0e0)
Location: security/selinux/ss/ebitmap.c:220
Inline: False
Direct callers:
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_context_isvalid
  - security/selinux/ss/mls.c:mls_context_isvalid
  - security/selinux/ss/mls.c:mls_range_isvalid
  - security/selinux/ss/mls.c:mls_range_isvalid
```
**Symbols:**

```
ffffffff8153c0e0-ffffffff8153c26d: ebitmap_contains (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ebitmap_contains(struct ebitmap *e1, struct ebitmap *e2, u32 last_e2bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/ebitmap.c (ffffffff815d39c0)
Location: security/selinux/ss/ebitmap.c:220
Inline: False
Direct callers:
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_context_isvalid
  - security/selinux/ss/mls.c:mls_context_isvalid
  - security/selinux/ss/mls.c:mls_context_isvalid
```
**Symbols:**

```
ffffffff815d39c0-ffffffff815d3b98: ebitmap_contains (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ebitmap_contains(const struct ebitmap *e1, const struct ebitmap *e2, u32 last_e2bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/ebitmap.c (ffffffff81681a60)
Location: security/selinux/ss/ebitmap.c:221
Inline: False
Direct callers:
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_context_isvalid
  - security/selinux/ss/mls.c:mls_context_isvalid
  - security/selinux/ss/mls.c:mls_context_isvalid
```
**Symbols:**

```
ffffffff81681a60-ffffffff81681c38: ebitmap_contains (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ebitmap_contains(const struct ebitmap *e1, const struct ebitmap *e2, u32 last_e2bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/ebitmap.c (ffffffff816b9c20)
Location: security/selinux/ss/ebitmap.c:221
Inline: False
Direct callers:
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_context_isvalid
  - security/selinux/ss/mls.c:mls_context_isvalid
  - security/selinux/ss/mls.c:mls_context_isvalid
```
**Symbols:**

```
ffffffff816b9c20-ffffffff816b9de1: ebitmap_contains (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ebitmap_contains(const struct ebitmap *e1, const struct ebitmap *e2, u32 last_e2bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/ebitmap.c (ffffffff816f66b0)
Location: security/selinux/ss/ebitmap.c:221
Inline: False
Direct callers:
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_context_isvalid
  - security/selinux/ss/mls.c:mls_context_isvalid
  - security/selinux/ss/mls.c:mls_context_isvalid
```
**Symbols:**

```
ffffffff816f66b0-ffffffff816f6871: ebitmap_contains (STB_GLOBAL)
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
int ebitmap_contains(struct ebitmap *e1, struct ebitmap *e2, u32 last_e2bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/ebitmap.c (ffff800010559208)
Location: security/selinux/ss/ebitmap.c:201
Inline: False
Direct callers:
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_context_isvalid
  - security/selinux/ss/mls.c:mls_context_isvalid
  - security/selinux/ss/mls.c:mls_range_isvalid
  - security/selinux/ss/mls.c:mls_level_isvalid
```
**Symbols:**

```
ffff800010559208-ffff800010559310: ebitmap_contains (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ebitmap_contains(struct ebitmap *e1, struct ebitmap *e2, u32 last_e2bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/ebitmap.c (c070da90)
Location: security/selinux/ss/ebitmap.c:201
Inline: False
Direct callers:
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/services.c:constraint_expr_eval
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_context_isvalid
  - security/selinux/ss/mls.c:mls_context_isvalid
  - security/selinux/ss/mls.c:mls_range_isvalid
  - security/selinux/ss/mls.c:mls_level_isvalid
```
**Symbols:**

```
c070da90-c070db80: ebitmap_contains (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ebitmap_contains(struct ebitmap *e1, struct ebitmap *e2, u32 last_e2bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/ebitmap.c (c0000000006b71f0)
Location: security/selinux/ss/ebitmap.c:201
Inline: False
Direct callers:
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_context_isvalid
  - security/selinux/ss/mls.c:mls_context_isvalid
  - security/selinux/ss/mls.c:mls_range_isvalid
  - security/selinux/ss/mls.c:mls_level_isvalid
```
**Symbols:**

```
c0000000006b71f0-c0000000006b7324: ebitmap_contains (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ebitmap_contains(struct ebitmap *e1, struct ebitmap *e2, u32 last_e2bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/ebitmap.c (ffffffe0003b02fe)
Location: security/selinux/ss/ebitmap.c:201
Inline: False
Direct callers:
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_context_isvalid
  - security/selinux/ss/mls.c:mls_context_isvalid
  - security/selinux/ss/mls.c:mls_range_isvalid
  - security/selinux/ss/mls.c:mls_level_isvalid
```
**Symbols:**

```
ffffffe0003b02fe-ffffffe0003b0428: ebitmap_contains (STB_GLOBAL)
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
int ebitmap_contains(struct ebitmap *e1, struct ebitmap *e2, u32 last_e2bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/ebitmap.c (ffffffff81462bd0)
Location: security/selinux/ss/ebitmap.c:201
Inline: False
Direct callers:
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_context_isvalid
  - security/selinux/ss/mls.c:mls_context_isvalid
  - security/selinux/ss/mls.c:mls_range_isvalid
  - security/selinux/ss/mls.c:mls_level_isvalid
```
**Symbols:**

```
ffffffff81462bd0-ffffffff81462c7a: ebitmap_contains (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ebitmap_contains(struct ebitmap *e1, struct ebitmap *e2, u32 last_e2bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/ebitmap.c (ffffffff81453600)
Location: security/selinux/ss/ebitmap.c:201
Inline: False
Direct callers:
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_context_isvalid
  - security/selinux/ss/mls.c:mls_context_isvalid
  - security/selinux/ss/mls.c:mls_range_isvalid
  - security/selinux/ss/mls.c:mls_level_isvalid
```
**Symbols:**

```
ffffffff81453600-ffffffff814536aa: ebitmap_contains (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ebitmap_contains(struct ebitmap *e1, struct ebitmap *e2, u32 last_e2bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/ebitmap.c (ffffffff8145ec70)
Location: security/selinux/ss/ebitmap.c:201
Inline: False
Direct callers:
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_context_isvalid
  - security/selinux/ss/mls.c:mls_context_isvalid
  - security/selinux/ss/mls.c:mls_range_isvalid
  - security/selinux/ss/mls.c:mls_level_isvalid
```
**Symbols:**

```
ffffffff8145ec70-ffffffff8145ed1a: ebitmap_contains (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ebitmap_contains(struct ebitmap *e1, struct ebitmap *e2, u32 last_e2bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/ebitmap.c (ffffffff81476480)
Location: security/selinux/ss/ebitmap.c:201
Inline: False
Direct callers:
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/services.c:selinux_audit_rule_match
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_setup_user_range
  - security/selinux/ss/mls.c:mls_context_isvalid
  - security/selinux/ss/mls.c:mls_context_isvalid
  - security/selinux/ss/mls.c:mls_range_isvalid
  - security/selinux/ss/mls.c:mls_level_isvalid
```
**Symbols:**

```
ffffffff81476480-ffffffff8147652a: ebitmap_contains (STB_GLOBAL)
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
