# Function: <code>aa_ns_name</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
const char *aa_ns_name(struct aa_ns *curr, struct aa_ns *view, bool subns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_ns.c (ffffffff813947e0)
Location: security/apparmor/policy_ns.c:65
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_profile_snxprint
```
**Symbols:**

```
ffffffff813947e0-ffffffff81394838: aa_ns_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
const char *aa_ns_name(struct aa_ns *curr, struct aa_ns *view, bool subns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_ns.c (ffffffff813cffc0)
Location: security/apparmor/policy_ns.c:65
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_profile_snxprint
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
```
**Symbols:**

```
ffffffff813cffc0-ffffffff813d0017: aa_ns_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
const char *aa_ns_name(struct aa_ns *curr, struct aa_ns *view, bool subns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_ns.c (ffffffff813e76c0)
Location: security/apparmor/policy_ns.c:65
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_profile_snxprint
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
```
**Symbols:**

```
ffffffff813e76c0-ffffffff813e7717: aa_ns_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
const char *aa_ns_name(struct aa_ns *curr, struct aa_ns *view, bool subns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_ns.c (ffffffff813ec1f0)
Location: security/apparmor/policy_ns.c:65
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:seq_ns_name_show
  - security/apparmor/label.c:aa_label_snxprint
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
```
**Symbols:**

```
ffffffff813ec1f0-ffffffff813ec252: aa_ns_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
const char *aa_ns_name(struct aa_ns *curr, struct aa_ns *view, bool subns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_ns.c (ffffffff81413b80)
Location: security/apparmor/policy_ns.c:65
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_snxprint
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
```
**Symbols:**

```
ffffffff81413b80-ffffffff81413be2: aa_ns_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
const char *aa_ns_name(struct aa_ns *curr, struct aa_ns *view, bool subns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_ns.c (ffffffff81445d50)
Location: security/apparmor/policy_ns.c:65
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_snxprint
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
```
**Symbols:**

```
ffffffff81445d50-ffffffff81445da7: aa_ns_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
const char *aa_ns_name(struct aa_ns *curr, struct aa_ns *view, bool subns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_ns.c (ffffffff81462c70)
Location: security/apparmor/policy_ns.c:65
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_snxprint
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
```
**Symbols:**

```
ffffffff81462c70-ffffffff81462cc7: aa_ns_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
const char *aa_ns_name(struct aa_ns *curr, struct aa_ns *view, bool subns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_ns.c (ffffffff814900c0)
Location: security/apparmor/policy_ns.c:61
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_snxprint
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
```
**Symbols:**

```
ffffffff814900c0-ffffffff81490110: aa_ns_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
const char *aa_ns_name(struct aa_ns *curr, struct aa_ns *view, bool subns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_ns.c (ffffffff814a9f80)
Location: security/apparmor/policy_ns.c:61
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_snxprint
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
```
**Symbols:**

```
ffffffff814a9f80-ffffffff814a9fd0: aa_ns_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
const char *aa_ns_name(struct aa_ns *curr, struct aa_ns *view, bool subns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_ns.c (ffffffff81507a50)
Location: security/apparmor/policy_ns.c:61
Inline: False
Direct callers:
  - security/apparmor/domain.c:label_components_match
  - security/apparmor/domain.c:label_components_match
  - security/apparmor/domain.c:label_compound_match
  - security/apparmor/domain.c:label_compound_match
  - security/apparmor/label.c:aa_label_snxprint
  - security/apparmor/label.c:label_components_match
  - security/apparmor/label.c:label_components_match
  - security/apparmor/label.c:label_compound_match
  - security/apparmor/label.c:label_compound_match
```
**Symbols:**

```
ffffffff81507a50-ffffffff81507aa6: aa_ns_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
const char *aa_ns_name(struct aa_ns *curr, struct aa_ns *view, bool subns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_ns.c (ffffffff81524af0)
Location: security/apparmor/policy_ns.c:61
Inline: False
Direct callers:
  - security/apparmor/domain.c:label_components_match
  - security/apparmor/domain.c:label_components_match
  - security/apparmor/domain.c:label_compound_match
  - security/apparmor/domain.c:label_compound_match
  - security/apparmor/label.c:aa_label_snxprint
  - security/apparmor/label.c:label_components_match
  - security/apparmor/label.c:label_components_match
  - security/apparmor/label.c:label_compound_match
  - security/apparmor/label.c:label_compound_match
```
**Symbols:**

```
ffffffff81524af0-ffffffff81524b46: aa_ns_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
const char *aa_ns_name(struct aa_ns *curr, struct aa_ns *view, bool subns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_ns.c (ffffffff8152aca0)
Location: security/apparmor/policy_ns.c:61
Inline: False
Direct callers:
  - security/apparmor/domain.c:label_components_match
  - security/apparmor/domain.c:label_components_match
  - security/apparmor/domain.c:label_compound_match
  - security/apparmor/domain.c:label_compound_match
  - security/apparmor/label.c:aa_label_snxprint
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
```
**Symbols:**

```
ffffffff8152aca0-ffffffff8152acf6: aa_ns_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
const char *aa_ns_name(struct aa_ns *curr, struct aa_ns *view, bool subns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_ns.c (ffffffff81589040)
Location: security/apparmor/policy_ns.c:61
Inline: False
Direct callers:
  - security/apparmor/domain.c:label_components_match
  - security/apparmor/domain.c:label_components_match
  - security/apparmor/domain.c:label_compound_match
  - security/apparmor/domain.c:label_compound_match
  - security/apparmor/label.c:aa_label_snxprint
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
```
**Symbols:**

```
ffffffff81589040-ffffffff81589096: aa_ns_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
const char *aa_ns_name(struct aa_ns *curr, struct aa_ns *view, bool subns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_ns.c (ffffffff81629890)
Location: security/apparmor/policy_ns.c:64
Inline: False
Direct callers:
  - security/apparmor/domain.c:label_components_match
  - security/apparmor/domain.c:label_components_match
  - security/apparmor/domain.c:label_compound_match
  - security/apparmor/domain.c:label_compound_match
  - security/apparmor/label.c:aa_label_snxprint
  - security/apparmor/label.c:label_components_match
  - security/apparmor/label.c:label_components_match
  - security/apparmor/label.c:label_compound_match
  - security/apparmor/label.c:label_compound_match
```
**Symbols:**

```
ffffffff81629890-ffffffff81629904: aa_ns_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
const char *aa_ns_name(struct aa_ns *curr, struct aa_ns *view, bool subns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_ns.c (ffffffff816ddfb0)
Location: security/apparmor/policy_ns.c:65
Inline: False
Direct callers:
  - security/apparmor/domain.c:label_components_match
  - security/apparmor/domain.c:label_components_match
  - security/apparmor/domain.c:label_compound_match
  - security/apparmor/domain.c:label_compound_match
  - security/apparmor/label.c:aa_label_snxprint
  - security/apparmor/label.c:label_components_match
  - security/apparmor/label.c:label_components_match
  - security/apparmor/label.c:label_compound_match
  - security/apparmor/label.c:label_compound_match
```
**Symbols:**

```
ffffffff816ddfb0-ffffffff816de024: aa_ns_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
const char *aa_ns_name(struct aa_ns *curr, struct aa_ns *view, bool subns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_ns.c (ffffffff817175b0)
Location: security/apparmor/policy_ns.c:65
Inline: False
Direct callers:
  - security/apparmor/domain.c:label_components_match
  - security/apparmor/domain.c:label_components_match
  - security/apparmor/domain.c:label_compound_match
  - security/apparmor/domain.c:label_compound_match
  - security/apparmor/label.c:aa_label_snxprint
  - security/apparmor/label.c:label_components_match
  - security/apparmor/label.c:label_components_match
  - security/apparmor/label.c:label_compound_match
  - security/apparmor/label.c:label_compound_match
```
**Symbols:**

```
ffffffff817175b0-ffffffff81717624: aa_ns_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
const char *aa_ns_name(struct aa_ns *curr, struct aa_ns *view, bool subns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_ns.c (ffffffff81756140)
Location: security/apparmor/policy_ns.c:65
Inline: False
Direct callers:
  - security/apparmor/domain.c:label_components_match
  - security/apparmor/domain.c:label_components_match
  - security/apparmor/domain.c:label_compound_match
  - security/apparmor/domain.c:label_compound_match
  - security/apparmor/label.c:aa_label_snxprint
  - security/apparmor/label.c:label_components_match
  - security/apparmor/label.c:label_components_match
  - security/apparmor/label.c:label_compound_match
  - security/apparmor/label.c:label_compound_match
```
**Symbols:**

```
ffffffff81756140-ffffffff817561b4: aa_ns_name (STB_GLOBAL)
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
const char *aa_ns_name(struct aa_ns *curr, struct aa_ns *view, bool subns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_ns.c (ffff8000105a0a38)
Location: security/apparmor/policy_ns.c:61
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_snxprint
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
```
**Symbols:**

```
ffff8000105a0a38-ffff8000105a0ad4: aa_ns_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
const char *aa_ns_name(struct aa_ns *curr, struct aa_ns *view, bool subns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_ns.c (c07515c8)
Location: security/apparmor/policy_ns.c:61
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_snxprint
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
```
**Symbols:**

```
c07515c8-c0751640: aa_ns_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
const char *aa_ns_name(struct aa_ns *curr, struct aa_ns *view, bool subns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_ns.c (c00000000071af80)
Location: security/apparmor/policy_ns.c:61
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_snxprint
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
```
**Symbols:**

```
c00000000071af80-c00000000071b02c: aa_ns_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
const char *aa_ns_name(struct aa_ns *curr, struct aa_ns *view, bool subns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_ns.c (ffffffe0003eb904)
Location: security/apparmor/policy_ns.c:61
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_snxprint
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
```
**Symbols:**

```
ffffffe0003eb904-ffffffe0003eb980: aa_ns_name (STB_GLOBAL)
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
const char *aa_ns_name(struct aa_ns *curr, struct aa_ns *view, bool subns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_ns.c (ffffffff814a2560)
Location: security/apparmor/policy_ns.c:61
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_snxprint
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
```
**Symbols:**

```
ffffffff814a2560-ffffffff814a25b0: aa_ns_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
const char *aa_ns_name(struct aa_ns *curr, struct aa_ns *view, bool subns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_ns.c (ffffffff81492f80)
Location: security/apparmor/policy_ns.c:61
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_snxprint
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
```
**Symbols:**

```
ffffffff81492f80-ffffffff81492fd0: aa_ns_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
const char *aa_ns_name(struct aa_ns *curr, struct aa_ns *view, bool subns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_ns.c (ffffffff8149e600)
Location: security/apparmor/policy_ns.c:61
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_snxprint
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
```
**Symbols:**

```
ffffffff8149e600-ffffffff8149e650: aa_ns_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
const char *aa_ns_name(struct aa_ns *curr, struct aa_ns *view, bool subns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_ns.c (ffffffff814b6bf0)
Location: security/apparmor/policy_ns.c:61
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_snxprint
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
```
**Symbols:**

```
ffffffff814b6bf0-ffffffff814b6c40: aa_ns_name (STB_GLOBAL)
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
