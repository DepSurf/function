# Function: <code>aa_ns_visible</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
bool aa_ns_visible(struct aa_ns *curr, struct aa_ns *view, bool subns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_ns.c (ffffffff813947a0)
Location: security/apparmor/policy_ns.c:41
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_ns_name
Direct callers:
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/label.c:label_modename
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_snxprint
  - security/apparmor/label.c:aa_label_snxprint
  - security/apparmor/label.c:aa_label_xaudit
  - security/apparmor/label.c:aa_label_seq_xprint
  - security/apparmor/label.c:aa_label_xprintk
```
**Symbols:**

```
ffffffff813947a0-ffffffff813947dd: aa_ns_visible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
bool aa_ns_visible(struct aa_ns *curr, struct aa_ns *view, bool subns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_ns.c (ffffffff813cffd1)
Location: security/apparmor/policy_ns.c:41
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_ns_name
Direct callers:
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/label.c:aa_label_xprintk
  - security/apparmor/label.c:aa_label_seq_xprint
  - security/apparmor/label.c:aa_label_xaudit
  - security/apparmor/label.c:aa_label_snxprint
  - security/apparmor/label.c:aa_label_snxprint
  - security/apparmor/label.c:label_modename
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
```
**Symbols:**

```
ffffffff813cff80-ffffffff813cffbd: aa_ns_visible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
bool aa_ns_visible(struct aa_ns *curr, struct aa_ns *view, bool subns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_ns.c (ffffffff813e76d1)
Location: security/apparmor/policy_ns.c:41
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_ns_name
Direct callers:
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/label.c:aa_label_xprintk
  - security/apparmor/label.c:aa_label_seq_xprint
  - security/apparmor/label.c:aa_label_xaudit
  - security/apparmor/label.c:aa_label_snxprint
  - security/apparmor/label.c:aa_label_snxprint
  - security/apparmor/label.c:label_modename
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
```
**Symbols:**

```
ffffffff813e7680-ffffffff813e76bd: aa_ns_visible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
bool aa_ns_visible(struct aa_ns *curr, struct aa_ns *view, bool subns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_ns.c (ffffffff813ec201)
Location: security/apparmor/policy_ns.c:41
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_ns_name
Direct callers:
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/label.c:aa_label_xprintk
  - security/apparmor/label.c:aa_label_seq_xprint
  - security/apparmor/label.c:aa_label_xaudit
  - security/apparmor/label.c:aa_label_snxprint
  - security/apparmor/label.c:aa_label_snxprint
  - security/apparmor/label.c:label_modename
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
```
**Symbols:**

```
ffffffff813ec1b0-ffffffff813ec1eb: aa_ns_visible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool aa_ns_visible(struct aa_ns *curr, struct aa_ns *view, bool subns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_ns.c (ffffffff81413b91)
Location: security/apparmor/policy_ns.c:41
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_ns_name
Direct callers:
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/label.c:aa_label_xprintk
  - security/apparmor/label.c:aa_label_seq_xprint
  - security/apparmor/label.c:aa_label_xaudit
  - security/apparmor/label.c:aa_label_snxprint
  - security/apparmor/label.c:aa_label_snxprint
  - security/apparmor/label.c:label_modename
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
```
**Symbols:**

```
ffffffff81413b40-ffffffff81413b7b: aa_ns_visible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool aa_ns_visible(struct aa_ns *curr, struct aa_ns *view, bool subns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_ns.c (ffffffff81445d61)
Location: security/apparmor/policy_ns.c:41
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_ns_name
Direct callers:
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/label.c:aa_label_xprintk
  - security/apparmor/label.c:aa_label_seq_xprint
  - security/apparmor/label.c:aa_label_xaudit
  - security/apparmor/label.c:aa_label_snxprint
  - security/apparmor/label.c:aa_label_snxprint
  - security/apparmor/label.c:label_modename
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
```
**Symbols:**

```
ffffffff81445d10-ffffffff81445d4d: aa_ns_visible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool aa_ns_visible(struct aa_ns *curr, struct aa_ns *view, bool subns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_ns.c (ffffffff81462c81)
Location: security/apparmor/policy_ns.c:41
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_ns_name
  - security/apparmor/policy_ns.c:aa_ns_name
Direct callers:
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/label.c:aa_label_xprintk
  - security/apparmor/label.c:aa_label_seq_xprint
  - security/apparmor/label.c:aa_label_xaudit
  - security/apparmor/label.c:aa_label_snxprint
  - security/apparmor/label.c:aa_label_snxprint
  - security/apparmor/label.c:label_modename
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
```
**Symbols:**

```
ffffffff81462c30-ffffffff81462c6d: aa_ns_visible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool aa_ns_visible(struct aa_ns *curr, struct aa_ns *view, bool subns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_ns.c (ffffffff814900d5)
Location: security/apparmor/policy_ns.c:37
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_ns_name
  - security/apparmor/policy_ns.c:aa_ns_name
Direct callers:
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/label.c:aa_label_xprintk
  - security/apparmor/label.c:aa_label_seq_xprint
  - security/apparmor/label.c:aa_label_xaudit
  - security/apparmor/label.c:aa_label_snxprint
  - security/apparmor/label.c:aa_label_snxprint
  - security/apparmor/label.c:label_modename
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
```
**Symbols:**

```
ffffffff81490090-ffffffff814900bf: aa_ns_visible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool aa_ns_visible(struct aa_ns *curr, struct aa_ns *view, bool subns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_ns.c (ffffffff814a9f95)
Location: security/apparmor/policy_ns.c:37
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_ns_name
  - security/apparmor/policy_ns.c:aa_ns_name
Direct callers:
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/label.c:aa_label_xprintk
  - security/apparmor/label.c:aa_label_seq_xprint
  - security/apparmor/label.c:aa_label_xaudit
  - security/apparmor/label.c:aa_label_snxprint
  - security/apparmor/label.c:aa_label_snxprint
  - security/apparmor/label.c:label_modename
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
```
**Symbols:**

```
ffffffff814a9f50-ffffffff814a9f7f: aa_ns_visible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool aa_ns_visible(struct aa_ns *curr, struct aa_ns *view, bool subns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_ns.c (ffffffff81507a65)
Location: security/apparmor/policy_ns.c:37
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_ns_name
  - security/apparmor/policy_ns.c:aa_ns_name
Direct callers:
  - security/apparmor/domain.c:label_components_match
  - security/apparmor/domain.c:label_components_match
  - security/apparmor/domain.c:label_compound_match
  - security/apparmor/domain.c:label_compound_match
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/label.c:aa_label_seq_xprint
  - security/apparmor/label.c:aa_label_xaudit
  - security/apparmor/label.c:aa_label_snxprint
  - security/apparmor/label.c:aa_label_snxprint
  - security/apparmor/label.c:label_modename
  - security/apparmor/label.c:label_components_match
  - security/apparmor/label.c:label_components_match
  - security/apparmor/label.c:label_compound_match
  - security/apparmor/label.c:label_compound_match
```
**Symbols:**

```
ffffffff81507a20-ffffffff81507a4f: aa_ns_visible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool aa_ns_visible(struct aa_ns *curr, struct aa_ns *view, bool subns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_ns.c (ffffffff81524b05)
Location: security/apparmor/policy_ns.c:37
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_ns_name
  - security/apparmor/policy_ns.c:aa_ns_name
Direct callers:
  - security/apparmor/domain.c:label_components_match
  - security/apparmor/domain.c:label_components_match
  - security/apparmor/domain.c:label_compound_match
  - security/apparmor/domain.c:label_compound_match
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/label.c:aa_label_seq_xprint
  - security/apparmor/label.c:aa_label_xaudit
  - security/apparmor/label.c:aa_label_snxprint
  - security/apparmor/label.c:aa_label_snxprint
  - security/apparmor/label.c:label_modename
  - security/apparmor/label.c:label_components_match
  - security/apparmor/label.c:label_components_match
  - security/apparmor/label.c:label_compound_match
  - security/apparmor/label.c:label_compound_match
```
**Symbols:**

```
ffffffff81524ac0-ffffffff81524aef: aa_ns_visible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool aa_ns_visible(struct aa_ns *curr, struct aa_ns *view, bool subns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_ns.c (ffffffff8152acb5)
Location: security/apparmor/policy_ns.c:37
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_ns_name
  - security/apparmor/policy_ns.c:aa_ns_name
Direct callers:
  - security/apparmor/domain.c:label_components_match
  - security/apparmor/domain.c:label_components_match
  - security/apparmor/domain.c:label_compound_match
  - security/apparmor/domain.c:label_compound_match
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/label.c:aa_label_seq_xprint
  - security/apparmor/label.c:aa_label_xaudit
  - security/apparmor/label.c:aa_label_snxprint
  - security/apparmor/label.c:aa_label_snxprint
  - security/apparmor/label.c:label_modename
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
```
**Symbols:**

```
ffffffff8152ac70-ffffffff8152ac9f: aa_ns_visible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool aa_ns_visible(struct aa_ns *curr, struct aa_ns *view, bool subns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_ns.c (ffffffff81589055)
Location: security/apparmor/policy_ns.c:37
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_ns_name
  - security/apparmor/policy_ns.c:aa_ns_name
Direct callers:
  - security/apparmor/domain.c:label_components_match
  - security/apparmor/domain.c:label_components_match
  - security/apparmor/domain.c:label_compound_match
  - security/apparmor/domain.c:label_compound_match
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/label.c:aa_label_seq_xprint
  - security/apparmor/label.c:aa_label_xaudit
  - security/apparmor/label.c:aa_label_snxprint
  - security/apparmor/label.c:aa_label_snxprint
  - security/apparmor/label.c:label_modename
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
```
**Symbols:**

```
ffffffff81589010-ffffffff8158903f: aa_ns_visible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool aa_ns_visible(struct aa_ns *curr, struct aa_ns *view, bool subns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_ns.c (ffffffff816298a5)
Location: security/apparmor/policy_ns.c:40
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_ns_name
  - security/apparmor/policy_ns.c:aa_ns_name
Direct callers:
  - security/apparmor/domain.c:label_components_match
  - security/apparmor/domain.c:label_components_match
  - security/apparmor/domain.c:label_compound_match
  - security/apparmor/domain.c:label_compound_match
  - security/apparmor/policy.c:aa_policy_view_capable
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/label.c:aa_label_seq_xprint
  - security/apparmor/label.c:aa_label_xaudit
  - security/apparmor/label.c:aa_label_snxprint
  - security/apparmor/label.c:aa_label_snxprint
  - security/apparmor/label.c:label_modename
  - security/apparmor/label.c:label_components_match
  - security/apparmor/label.c:label_components_match
  - security/apparmor/label.c:label_compound_match
  - security/apparmor/label.c:label_compound_match
```
**Symbols:**

```
ffffffff81629840-ffffffff81629883: aa_ns_visible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool aa_ns_visible(struct aa_ns *curr, struct aa_ns *view, bool subns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_ns.c (ffffffff816ddfc5)
Location: security/apparmor/policy_ns.c:41
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_ns_name
  - security/apparmor/policy_ns.c:aa_ns_name
Direct callers:
  - security/apparmor/domain.c:label_components_match
  - security/apparmor/domain.c:label_components_match
  - security/apparmor/domain.c:label_compound_match
  - security/apparmor/domain.c:label_compound_match
  - security/apparmor/policy.c:aa_policy_view_capable
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/label.c:aa_label_xprintk
  - security/apparmor/label.c:aa_label_seq_xprint
  - security/apparmor/label.c:aa_label_xaudit
  - security/apparmor/label.c:aa_label_snxprint
  - security/apparmor/label.c:aa_label_snxprint
  - security/apparmor/label.c:label_modename
  - security/apparmor/label.c:label_components_match
  - security/apparmor/label.c:label_components_match
  - security/apparmor/label.c:label_compound_match
  - security/apparmor/label.c:label_compound_match
```
**Symbols:**

```
ffffffff816ddf50-ffffffff816ddf93: aa_ns_visible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool aa_ns_visible(struct aa_ns *curr, struct aa_ns *view, bool subns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_ns.c (ffffffff817175c5)
Location: security/apparmor/policy_ns.c:41
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_ns_name
  - security/apparmor/policy_ns.c:aa_ns_name
Direct callers:
  - security/apparmor/domain.c:label_components_match
  - security/apparmor/domain.c:label_components_match
  - security/apparmor/domain.c:label_compound_match
  - security/apparmor/domain.c:label_compound_match
  - security/apparmor/policy.c:aa_policy_view_capable
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/label.c:aa_label_xprintk
  - security/apparmor/label.c:aa_label_seq_xprint
  - security/apparmor/label.c:aa_label_xaudit
  - security/apparmor/label.c:aa_label_snxprint
  - security/apparmor/label.c:aa_label_snxprint
  - security/apparmor/label.c:label_modename
  - security/apparmor/label.c:label_components_match
  - security/apparmor/label.c:label_components_match
  - security/apparmor/label.c:label_compound_match
  - security/apparmor/label.c:label_compound_match
  - security/apparmor/notify.c:notification_match
```
**Symbols:**

```
ffffffff81717550-ffffffff81717593: aa_ns_visible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool aa_ns_visible(struct aa_ns *curr, struct aa_ns *view, bool subns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_ns.c (ffffffff81756155)
Location: security/apparmor/policy_ns.c:41
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_ns_name
  - security/apparmor/policy_ns.c:aa_ns_name
Direct callers:
  - security/apparmor/domain.c:label_components_match
  - security/apparmor/domain.c:label_components_match
  - security/apparmor/domain.c:label_compound_match
  - security/apparmor/domain.c:label_compound_match
  - security/apparmor/policy.c:aa_policy_view_capable
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/label.c:aa_label_xprintk
  - security/apparmor/label.c:aa_label_seq_xprint
  - security/apparmor/label.c:aa_label_xaudit
  - security/apparmor/label.c:aa_label_snxprint
  - security/apparmor/label.c:aa_label_snxprint
  - security/apparmor/label.c:label_modename
  - security/apparmor/label.c:label_components_match
  - security/apparmor/label.c:label_components_match
  - security/apparmor/label.c:label_compound_match
  - security/apparmor/label.c:label_compound_match
  - security/apparmor/notify.c:notification_match
```
**Symbols:**

```
ffffffff817560e0-ffffffff81756123: aa_ns_visible (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
bool aa_ns_visible(struct aa_ns *curr, struct aa_ns *view, bool subns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_ns.c (ffff8000105a0a64)
Location: security/apparmor/policy_ns.c:37
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_ns_name
  - security/apparmor/policy_ns.c:aa_ns_name
Direct callers:
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/label.c:aa_label_xprintk
  - security/apparmor/label.c:aa_label_seq_xprint
  - security/apparmor/label.c:aa_label_xaudit
  - security/apparmor/label.c:aa_label_snxprint
  - security/apparmor/label.c:aa_label_snxprint
  - security/apparmor/label.c:label_modename
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
```
**Symbols:**

```
ffff8000105a09b0-ffff8000105a0a34: aa_ns_visible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool aa_ns_visible(struct aa_ns *curr, struct aa_ns *view, bool subns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_ns.c (c07515e8)
Location: security/apparmor/policy_ns.c:37
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_ns_name
  - security/apparmor/policy_ns.c:aa_ns_name
Direct callers:
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/label.c:aa_label_xprintk
  - security/apparmor/label.c:aa_label_seq_xprint
  - security/apparmor/label.c:aa_label_xaudit
  - security/apparmor/label.c:aa_label_snxprint
  - security/apparmor/label.c:aa_label_snxprint
  - security/apparmor/label.c:label_modename
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
```
**Symbols:**

```
c0751574-c07515c8: aa_ns_visible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool aa_ns_visible(struct aa_ns *curr, struct aa_ns *view, bool subns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_ns.c (c00000000071afa8)
Location: security/apparmor/policy_ns.c:37
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_ns_name
  - security/apparmor/policy_ns.c:aa_ns_name
Direct callers:
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/label.c:aa_label_xprintk
  - security/apparmor/label.c:aa_label_seq_xprint
  - security/apparmor/label.c:aa_label_xaudit
  - security/apparmor/label.c:aa_label_snxprint
  - security/apparmor/label.c:aa_label_snxprint
  - security/apparmor/label.c:label_modename
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
```
**Symbols:**

```
c00000000071af20-c00000000071af78: aa_ns_visible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
bool aa_ns_visible(struct aa_ns *curr, struct aa_ns *view, bool subns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_ns.c (ffffffe0003eb926)
Location: security/apparmor/policy_ns.c:37
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_ns_name
  - security/apparmor/policy_ns.c:aa_ns_name
Direct callers:
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/label.c:aa_label_xprintk
  - security/apparmor/label.c:aa_label_seq_xprint
  - security/apparmor/label.c:aa_label_xaudit
  - security/apparmor/label.c:aa_label_snxprint
  - security/apparmor/label.c:aa_label_snxprint
  - security/apparmor/label.c:label_modename
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
```
**Symbols:**

```
ffffffe0003eb8a2-ffffffe0003eb904: aa_ns_visible (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
bool aa_ns_visible(struct aa_ns *curr, struct aa_ns *view, bool subns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_ns.c (ffffffff814a2575)
Location: security/apparmor/policy_ns.c:37
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_ns_name
  - security/apparmor/policy_ns.c:aa_ns_name
Direct callers:
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/label.c:aa_label_xprintk
  - security/apparmor/label.c:aa_label_seq_xprint
  - security/apparmor/label.c:aa_label_xaudit
  - security/apparmor/label.c:aa_label_snxprint
  - security/apparmor/label.c:aa_label_snxprint
  - security/apparmor/label.c:label_modename
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
```
**Symbols:**

```
ffffffff814a2530-ffffffff814a255f: aa_ns_visible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool aa_ns_visible(struct aa_ns *curr, struct aa_ns *view, bool subns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_ns.c (ffffffff81492f95)
Location: security/apparmor/policy_ns.c:37
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_ns_name
  - security/apparmor/policy_ns.c:aa_ns_name
Direct callers:
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/label.c:aa_label_xprintk
  - security/apparmor/label.c:aa_label_seq_xprint
  - security/apparmor/label.c:aa_label_xaudit
  - security/apparmor/label.c:aa_label_snxprint
  - security/apparmor/label.c:aa_label_snxprint
  - security/apparmor/label.c:label_modename
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
```
**Symbols:**

```
ffffffff81492f50-ffffffff81492f7f: aa_ns_visible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool aa_ns_visible(struct aa_ns *curr, struct aa_ns *view, bool subns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_ns.c (ffffffff8149e615)
Location: security/apparmor/policy_ns.c:37
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_ns_name
  - security/apparmor/policy_ns.c:aa_ns_name
Direct callers:
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/label.c:aa_label_xprintk
  - security/apparmor/label.c:aa_label_seq_xprint
  - security/apparmor/label.c:aa_label_xaudit
  - security/apparmor/label.c:aa_label_snxprint
  - security/apparmor/label.c:aa_label_snxprint
  - security/apparmor/label.c:label_modename
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
```
**Symbols:**

```
ffffffff8149e5d0-ffffffff8149e5ff: aa_ns_visible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool aa_ns_visible(struct aa_ns *curr, struct aa_ns *view, bool subns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_ns.c (ffffffff814b6c05)
Location: security/apparmor/policy_ns.c:37
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_ns_name
  - security/apparmor/policy_ns.c:aa_ns_name
Direct callers:
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/label.c:aa_label_xprintk
  - security/apparmor/label.c:aa_label_seq_xprint
  - security/apparmor/label.c:aa_label_xaudit
  - security/apparmor/label.c:aa_label_snxprint
  - security/apparmor/label.c:aa_label_snxprint
  - security/apparmor/label.c:label_modename
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
```
**Symbols:**

```
ffffffff814b6bc0-ffffffff814b6bef: aa_ns_visible (STB_GLOBAL)
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
