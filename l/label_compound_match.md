# Function: <code>label_compound_match</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff81379d66)
Location: security/apparmor/domain.c:139
Inline: True
```
```
In security/apparmor/label.c (ffffffff8138be36)
Location: security/apparmor/label.c:1288
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_match
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff813b2a46)
Location: security/apparmor/domain.c:139
Inline: True
```
```
In security/apparmor/label.c (ffffffff813c6c26)
Location: security/apparmor/label.c:1297
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_match
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff813c9c06)
Location: security/apparmor/domain.c:139
Inline: True
```
```
In security/apparmor/label.c (ffffffff813de206)
Location: security/apparmor/label.c:1312
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_match
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff813df341)
Location: security/apparmor/domain.c:135
Inline: True
```
```
In security/apparmor/label.c (ffffffff813edea9)
Location: security/apparmor/label.c:1278
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_match
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff81405bc1)
Location: security/apparmor/domain.c:135
Inline: True
```
```
In security/apparmor/label.c (ffffffff81415b59)
Location: security/apparmor/label.c:1278
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_match
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff814373bd)
Location: security/apparmor/domain.c:136
Inline: True
```
```
In security/apparmor/label.c (ffffffff81447f29)
Location: security/apparmor/label.c:1277
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_match
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff81453f7d)
Location: security/apparmor/domain.c:136
Inline: True
```
```
In security/apparmor/label.c (ffffffff81464e59)
Location: security/apparmor/label.c:1278
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_match
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff81481919)
Location: security/apparmor/domain.c:132
Inline: True
```
```
In security/apparmor/label.c (ffffffff81492403)
Location: security/apparmor/label.c:1274
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_match
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff8149b649)
Location: security/apparmor/domain.c:132
Inline: True
```
```
In security/apparmor/label.c (ffffffff814ac333)
Location: security/apparmor/label.c:1301
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_match
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision ⚠️</summary>

```c
int label_compound_match(struct aa_profile *profile, struct aa_label *label, bool stack, unsigned int state, bool subns, u32 request, struct aa_perms *perms);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff814f43b0)
Location: security/apparmor/domain.c:132
Inline: False
```
```
In security/apparmor/label.c (ffffffff81508a50)
Location: security/apparmor/label.c:1301
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_match
```
**Symbols:**

```
ffffffff814f43b0-ffffffff814f4754: label_compound_match (STB_LOCAL)
ffffffff81508a50-ffffffff81508d52: label_compound_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision ⚠️</summary>

```c
int label_compound_match(struct aa_profile *profile, struct aa_label *label, bool stack, unsigned int state, bool subns, u32 request, struct aa_perms *perms);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff815114f0)
Location: security/apparmor/domain.c:132
Inline: False
```
```
In security/apparmor/label.c (ffffffff81525a10)
Location: security/apparmor/label.c:1301
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_match
```
**Symbols:**

```
ffffffff815114f0-ffffffff81511894: label_compound_match (STB_LOCAL)
ffffffff81525a10-ffffffff81525d12: label_compound_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Selective Inline ⚠️</summary>

```c
int label_compound_match(struct aa_profile *profile, struct aa_label *label, bool stack, unsigned int state, bool subns, u32 request, struct aa_perms *perms);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff81517e60)
Location: security/apparmor/domain.c:134
Inline: False
```
```
In security/apparmor/label.c (ffffffff8152ddf7)
Location: security/apparmor/label.c:1301
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_match
```
**Symbols:**

```
ffffffff81517e60-ffffffff815181fd: label_compound_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Selective Inline ⚠️</summary>

```c
int label_compound_match(struct aa_profile *profile, struct aa_label *label, bool stack, unsigned int state, bool subns, u32 request, struct aa_perms *perms);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff81575e60)
Location: security/apparmor/domain.c:134
Inline: False
```
```
In security/apparmor/label.c (ffffffff8158c1e7)
Location: security/apparmor/label.c:1301
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_match
```
**Symbols:**

```
ffffffff81575e60-ffffffff815761fd: label_compound_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision ⚠️</summary>

```c
int label_compound_match(struct aa_profile *profile, struct aa_label *label, bool stack, unsigned int state, bool subns, u32 request, struct aa_perms *perms);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff81613eb0)
Location: security/apparmor/domain.c:117
Inline: False
```
```
In security/apparmor/label.c (ffffffff8162a850)
Location: security/apparmor/label.c:1303
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_match
```
**Symbols:**

```
ffffffff81613eb0-ffffffff8161426f: label_compound_match (STB_LOCAL)
ffffffff8162a850-ffffffff8162ab94: label_compound_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision ⚠️</summary>

```c
int label_compound_match(struct aa_profile *profile, struct aa_label *label, bool stack, unsigned int state, bool subns, u32 request, struct aa_perms *perms);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff816c6bb0)
Location: security/apparmor/domain.c:124
Inline: False
```
```
In security/apparmor/label.c (ffffffff816df080)
Location: security/apparmor/label.c:1297
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_match
```
**Symbols:**

```
ffffffff816c6bb0-ffffffff816c6f6f: label_compound_match (STB_LOCAL)
ffffffff816df080-ffffffff816df3c4: label_compound_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision ⚠️</summary>

```c
int label_compound_match(struct aa_profile *profile, struct aa_label *label, bool stack, unsigned int state, bool subns, u32 request, struct aa_perms *perms);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff816fff80)
Location: security/apparmor/domain.c:124
Inline: False
```
```
In security/apparmor/label.c (ffffffff817186a0)
Location: security/apparmor/label.c:1297
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_match
```
**Symbols:**

```
ffffffff816fff80-ffffffff8170034c: label_compound_match (STB_LOCAL)
ffffffff817186a0-ffffffff81718a14: label_compound_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision ⚠️</summary>

```c
int label_compound_match(struct aa_profile *profile, struct aa_label *label, bool stack, unsigned int state, bool subns, u32 request, struct aa_perms *perms);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff8173d570)
Location: security/apparmor/domain.c:124
Inline: False
```
```
In security/apparmor/label.c (ffffffff81757110)
Location: security/apparmor/label.c:1303
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_match
```
**Symbols:**

```
ffffffff8173d570-ffffffff8173d952: label_compound_match (STB_LOCAL)
ffffffff81757110-ffffffff81757484: label_compound_match (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffff800010591f78)
Location: security/apparmor/domain.c:132
Inline: True
```
```
In security/apparmor/label.c (ffff8000105a371c)
Location: security/apparmor/label.c:1301
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_match
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (c0742b90)
Location: security/apparmor/domain.c:132
Inline: True
```
```
In security/apparmor/label.c (c0753888)
Location: security/apparmor/label.c:1301
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_match
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (c000000000705c94)
Location: security/apparmor/domain.c:132
Inline: True
```
```
In security/apparmor/label.c (c00000000071ec90)
Location: security/apparmor/label.c:1301
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_match
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffe0003df4e2)
Location: security/apparmor/domain.c:132
Inline: True
```
```
In security/apparmor/label.c (ffffffe0003eda5c)
Location: security/apparmor/label.c:1301
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_match
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff81493c29)
Location: security/apparmor/domain.c:132
Inline: True
```
```
In security/apparmor/label.c (ffffffff814a4913)
Location: security/apparmor/label.c:1301
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_match
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff81484649)
Location: security/apparmor/domain.c:132
Inline: True
```
```
In security/apparmor/label.c (ffffffff81495333)
Location: security/apparmor/label.c:1301
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_match
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff8148fcc9)
Location: security/apparmor/domain.c:132
Inline: True
```
```
In security/apparmor/label.c (ffffffff814a09b3)
Location: security/apparmor/label.c:1301
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_match
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff814a7bd9)
Location: security/apparmor/domain.c:132
Inline: True
```
```
In security/apparmor/label.c (ffffffff814b90d3)
Location: security/apparmor/label.c:1301
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_match
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
