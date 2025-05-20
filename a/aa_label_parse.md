# Function: <code>aa_label_parse</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct aa_label *aa_label_parse(struct aa_label *base, const char *str, gfp_t gfp, bool create, bool force_stack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff8138d790)
Location: security/apparmor/label.c:1834
Inline: False
Direct callers:
  - security/apparmor/domain.c:x_table_lookup
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
```
**Symbols:**

```
ffffffff8138d790-ffffffff8138dba2: aa_label_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct aa_label *aa_label_parse(struct aa_label *base, const char *str, gfp_t gfp, bool create, bool force_stack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff813c8560)
Location: security/apparmor/label.c:1849
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:x_table_lookup
```
**Symbols:**

```
ffffffff813c8560-ffffffff813c89a1: aa_label_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct aa_label *aa_label_parse(struct aa_label *base, const char *str, gfp_t gfp, bool create, bool force_stack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff813dfb40)
Location: security/apparmor/label.c:1881
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:x_table_lookup
```
**Symbols:**

```
ffffffff813dfb40-ffffffff813dffbe: aa_label_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct aa_label *aa_label_parse(struct aa_label *base, const char *str, gfp_t gfp, bool create, bool force_stack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff813ef1a0)
Location: security/apparmor/label.c:1856
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:x_table_lookup
```
**Symbols:**

```
ffffffff813ef1a0-ffffffff813ef504: aa_label_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct aa_label *aa_label_parse(struct aa_label *base, const char *str, gfp_t gfp, bool create, bool force_stack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81416fc0)
Location: security/apparmor/label.c:1856
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:x_table_lookup
```
**Symbols:**

```
ffffffff81416fc0-ffffffff8141732d: aa_label_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct aa_label *aa_label_parse(struct aa_label *base, const char *str, gfp_t gfp, bool create, bool force_stack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81449750)
Location: security/apparmor/label.c:1940
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/audit.c:aa_audit_rule_init
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:x_table_lookup
```
**Symbols:**

```
ffffffff81449750-ffffffff8144979d: aa_label_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct aa_label *aa_label_parse(struct aa_label *base, const char *str, gfp_t gfp, bool create, bool force_stack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff814666e0)
Location: security/apparmor/label.c:1941
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:x_table_lookup
```
**Symbols:**

```
ffffffff814666e0-ffffffff8146672d: aa_label_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct aa_label *aa_label_parse(struct aa_label *base, const char *str, gfp_t gfp, bool create, bool force_stack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81493c20)
Location: security/apparmor/label.c:1937
Inline: False
Direct callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:x_table_lookup
```
**Symbols:**

```
ffffffff81493c20-ffffffff81493c6c: aa_label_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct aa_label *aa_label_parse(struct aa_label *base, const char *str, gfp_t gfp, bool create, bool force_stack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff814adb50)
Location: security/apparmor/label.c:1966
Inline: False
Direct callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:x_table_lookup
```
**Symbols:**

```
ffffffff814adb50-ffffffff814adb9c: aa_label_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct aa_label *aa_label_parse(struct aa_label *base, const char *str, gfp_t gfp, bool create, bool force_stack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff8150ca60)
Location: security/apparmor/label.c:1963
Inline: False
Direct callers:
  - security/apparmor/audit.c:aa_audit_rule_init
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:x_table_lookup
```
**Symbols:**

```
ffffffff8150ca60-ffffffff8150caac: aa_label_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct aa_label *aa_label_parse(struct aa_label *base, const char *str, gfp_t gfp, bool create, bool force_stack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81529920)
Location: security/apparmor/label.c:1963
Inline: False
Direct callers:
  - security/apparmor/audit.c:aa_audit_rule_init
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:x_table_lookup
```
**Symbols:**

```
ffffffff81529920-ffffffff8152996c: aa_label_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct aa_label *aa_label_parse(struct aa_label *base, const char *str, gfp_t gfp, bool create, bool force_stack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff8152fad0)
Location: security/apparmor/label.c:1963
Inline: False
Direct callers:
  - security/apparmor/audit.c:aa_audit_rule_init
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:x_table_lookup
```
**Symbols:**

```
ffffffff8152fad0-ffffffff8152fb1c: aa_label_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct aa_label *aa_label_parse(struct aa_label *base, const char *str, gfp_t gfp, bool create, bool force_stack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff8158def0)
Location: security/apparmor/label.c:1963
Inline: False
Direct callers:
  - security/apparmor/audit.c:aa_audit_rule_init
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:x_table_lookup
```
**Symbols:**

```
ffffffff8158def0-ffffffff8158df3c: aa_label_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct aa_label *aa_label_parse(struct aa_label *base, const char *str, gfp_t gfp, bool create, bool force_stack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff8162ec90)
Location: security/apparmor/label.c:1973
Inline: False
Direct callers:
  - security/apparmor/audit.c:aa_audit_rule_init
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:x_table_lookup
```
**Symbols:**

```
ffffffff8162ec90-ffffffff8162ecef: aa_label_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct aa_label *aa_label_parse(struct aa_label *base, const char *str, gfp_t gfp, bool create, bool force_stack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff816e3870)
Location: security/apparmor/label.c:1967
Inline: False
Direct callers:
  - security/apparmor/audit.c:aa_audit_rule_init
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:x_table_lookup
```
**Symbols:**

```
ffffffff816e3870-ffffffff816e38cf: aa_label_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct aa_label *aa_label_parse(struct aa_label *base, const char *str, gfp_t gfp, bool create, bool force_stack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff8171cdd0)
Location: security/apparmor/label.c:1967
Inline: False
Direct callers:
  - security/apparmor/audit.c:aa_audit_rule_init
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:x_table_lookup
```
**Symbols:**

```
ffffffff8171cdd0-ffffffff8171ce2f: aa_label_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct aa_label *aa_label_parse(struct aa_label *base, const char *str, gfp_t gfp, bool create, bool force_stack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff8175b820)
Location: security/apparmor/label.c:1973
Inline: False
Direct callers:
  - security/apparmor/task.c:aa_profile_ns_perm
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:x_table_lookup
```
**Symbols:**

```
ffffffff8175b820-ffffffff8175b87f: aa_label_parse (STB_GLOBAL)
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
struct aa_label *aa_label_parse(struct aa_label *base, const char *str, gfp_t gfp, bool create, bool force_stack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffff8000105a4fd8)
Location: security/apparmor/label.c:1966
Inline: False
Direct callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:x_table_lookup
```
**Symbols:**

```
ffff8000105a4fd8-ffff8000105a5040: aa_label_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct aa_label *aa_label_parse(struct aa_label *base, const char *str, gfp_t gfp, bool create, bool force_stack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (c0755270)
Location: security/apparmor/label.c:1966
Inline: False
Direct callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:x_table_lookup
```
**Symbols:**

```
c0755270-c07552c4: aa_label_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct aa_label *aa_label_parse(struct aa_label *base, const char *str, gfp_t gfp, bool create, bool force_stack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (c000000000720f90)
Location: security/apparmor/label.c:1966
Inline: False
Direct callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:x_table_lookup
```
**Symbols:**

```
c000000000720f90-c00000000072100c: aa_label_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct aa_label *aa_label_parse(struct aa_label *base, const char *str, gfp_t gfp, bool create, bool force_stack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffe0003eee1e)
Location: security/apparmor/label.c:1966
Inline: False
Direct callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:x_table_lookup
```
**Symbols:**

```
ffffffe0003eee1e-ffffffe0003eee74: aa_label_parse (STB_GLOBAL)
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
struct aa_label *aa_label_parse(struct aa_label *base, const char *str, gfp_t gfp, bool create, bool force_stack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff814a6130)
Location: security/apparmor/label.c:1966
Inline: False
Direct callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:x_table_lookup
```
**Symbols:**

```
ffffffff814a6130-ffffffff814a617c: aa_label_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct aa_label *aa_label_parse(struct aa_label *base, const char *str, gfp_t gfp, bool create, bool force_stack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81496b50)
Location: security/apparmor/label.c:1966
Inline: False
Direct callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:x_table_lookup
```
**Symbols:**

```
ffffffff81496b50-ffffffff81496b9c: aa_label_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct aa_label *aa_label_parse(struct aa_label *base, const char *str, gfp_t gfp, bool create, bool force_stack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff814a21d0)
Location: security/apparmor/label.c:1966
Inline: False
Direct callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:x_table_lookup
```
**Symbols:**

```
ffffffff814a21d0-ffffffff814a221c: aa_label_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct aa_label *aa_label_parse(struct aa_label *base, const char *str, gfp_t gfp, bool create, bool force_stack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff814ba990)
Location: security/apparmor/label.c:1966
Inline: False
Direct callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:x_table_lookup
```
**Symbols:**

```
ffffffff814ba990-ffffffff814ba9dc: aa_label_parse (STB_GLOBAL)
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
