# Function: <code>label_components_match</code>

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
In security/apparmor/domain.c (ffffffff8137a00e)
Location: security/apparmor/domain.c:199
Inline: True
```
```
In security/apparmor/label.c (ffffffff8138bece)
Location: security/apparmor/label.c:1346
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
In security/apparmor/domain.c (ffffffff813b2c75)
Location: security/apparmor/domain.c:199
Inline: True
```
```
In security/apparmor/label.c (ffffffff813c6ec9)
Location: security/apparmor/label.c:1355
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
In security/apparmor/domain.c (ffffffff813c9e35)
Location: security/apparmor/domain.c:199
Inline: True
```
```
In security/apparmor/label.c (ffffffff813de4a9)
Location: security/apparmor/label.c:1370
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
In security/apparmor/domain.c (ffffffff813df60a)
Location: security/apparmor/domain.c:195
Inline: True
```
```
In security/apparmor/label.c (ffffffff813ee161)
Location: security/apparmor/label.c:1336
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
In security/apparmor/domain.c (ffffffff81405e8a)
Location: security/apparmor/domain.c:195
Inline: True
```
```
In security/apparmor/label.c (ffffffff81415e11)
Location: security/apparmor/label.c:1336
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
In security/apparmor/domain.c (ffffffff8143769f)
Location: security/apparmor/domain.c:196
Inline: True
```
```
In security/apparmor/label.c (ffffffff8144821e)
Location: security/apparmor/label.c:1335
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
In security/apparmor/domain.c (ffffffff8145425f)
Location: security/apparmor/domain.c:196
Inline: True
```
```
In security/apparmor/label.c (ffffffff8146514e)
Location: security/apparmor/label.c:1336
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
In security/apparmor/domain.c (ffffffff81481c10)
Location: security/apparmor/domain.c:192
Inline: True
```
```
In security/apparmor/label.c (ffffffff81492710)
Location: security/apparmor/label.c:1332
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
In security/apparmor/domain.c (ffffffff8149b940)
Location: security/apparmor/domain.c:192
Inline: True
```
```
In security/apparmor/label.c (ffffffff814ac640)
Location: security/apparmor/label.c:1359
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
int label_components_match(struct aa_profile *profile, struct aa_label *label, bool stack, unsigned int start, bool subns, u32 request, struct aa_perms *perms);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff814f3ed0)
Location: security/apparmor/domain.c:192
Inline: False
```
```
In security/apparmor/label.c (ffffffff81508710)
Location: security/apparmor/label.c:1359
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_match
```
**Symbols:**

```
ffffffff814f3ed0-ffffffff814f42e8: label_components_match (STB_LOCAL)
ffffffff81508710-ffffffff815089e0: label_components_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision ⚠️</summary>

```c
int label_components_match(struct aa_profile *profile, struct aa_label *label, bool stack, unsigned int start, bool subns, u32 request, struct aa_perms *perms);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff81511010)
Location: security/apparmor/domain.c:192
Inline: False
```
```
In security/apparmor/label.c (ffffffff815256d0)
Location: security/apparmor/label.c:1359
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_match
```
**Symbols:**

```
ffffffff81511010-ffffffff81511428: label_components_match (STB_LOCAL)
ffffffff815256d0-ffffffff815259a0: label_components_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Selective Inline ⚠️</summary>

```c
int label_components_match(struct aa_profile *profile, struct aa_label *label, bool stack, unsigned int start, bool subns, u32 request, struct aa_perms *perms);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff81517990)
Location: security/apparmor/domain.c:194
Inline: False
```
```
In security/apparmor/label.c (ffffffff8152e0d8)
Location: security/apparmor/label.c:1359
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_match
```
**Symbols:**

```
ffffffff81517990-ffffffff81517d9a: label_components_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Selective Inline ⚠️</summary>

```c
int label_components_match(struct aa_profile *profile, struct aa_label *label, bool stack, unsigned int start, bool subns, u32 request, struct aa_perms *perms);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff81575990)
Location: security/apparmor/domain.c:194
Inline: False
```
```
In security/apparmor/label.c (ffffffff8158c4c8)
Location: security/apparmor/label.c:1359
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_match
```
**Symbols:**

```
ffffffff81575990-ffffffff81575d9a: label_components_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision ⚠️</summary>

```c
int label_components_match(struct aa_profile *profile, struct aa_label *label, bool stack, unsigned int start, bool subns, u32 request, struct aa_perms *perms);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff81613900)
Location: security/apparmor/domain.c:179
Inline: False
```
```
In security/apparmor/label.c (ffffffff8162a2d0)
Location: security/apparmor/label.c:1363
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_match
```
**Symbols:**

```
ffffffff81613900-ffffffff81613ea4: label_components_match (STB_LOCAL)
ffffffff8162a2d0-ffffffff8162a7b4: label_components_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision ⚠️</summary>

```c
int label_components_match(struct aa_profile *profile, struct aa_label *label, bool stack, unsigned int start, bool subns, u32 request, struct aa_perms *perms);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff816c65f0)
Location: security/apparmor/domain.c:186
Inline: False
```
```
In security/apparmor/label.c (ffffffff816deae0)
Location: security/apparmor/label.c:1357
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_match
```
**Symbols:**

```
ffffffff816c65f0-ffffffff816c6b94: label_components_match (STB_LOCAL)
ffffffff816deae0-ffffffff816defc4: label_components_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision ⚠️</summary>

```c
int label_components_match(struct aa_profile *profile, struct aa_label *label, bool stack, unsigned int start, bool subns, u32 request, struct aa_perms *perms);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff816ff3e0)
Location: security/apparmor/domain.c:186
Inline: False
```
```
In security/apparmor/label.c (ffffffff817180e0)
Location: security/apparmor/label.c:1357
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_match
```
**Symbols:**

```
ffffffff816ff3e0-ffffffff816ff989: label_components_match (STB_LOCAL)
ffffffff817180e0-ffffffff817185f0: label_components_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision ⚠️</summary>

```c
int label_components_match(struct aa_profile *profile, struct aa_label *label, bool stack, unsigned int start, bool subns, u32 request, struct aa_perms *perms);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff8173c970)
Location: security/apparmor/domain.c:187
Inline: False
```
```
In security/apparmor/label.c (ffffffff81756b50)
Location: security/apparmor/label.c:1363
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_match
```
**Symbols:**

```
ffffffff8173c970-ffffffff8173cf50: label_components_match (STB_LOCAL)
ffffffff81756b50-ffffffff81757060: label_components_match (STB_LOCAL)
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
In security/apparmor/domain.c (ffff800010592228)
Location: security/apparmor/domain.c:192
Inline: True
```
```
In security/apparmor/label.c (ffff8000105a3964)
Location: security/apparmor/label.c:1359
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
In security/apparmor/domain.c (c0742dd8)
Location: security/apparmor/domain.c:192
Inline: True
```
```
In security/apparmor/label.c (c0753b08)
Location: security/apparmor/label.c:1359
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
In security/apparmor/domain.c (c000000000705fb0)
Location: security/apparmor/domain.c:192
Inline: True
```
```
In security/apparmor/label.c (c00000000071f054)
Location: security/apparmor/label.c:1359
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
In security/apparmor/domain.c (ffffffe0003df542)
Location: security/apparmor/domain.c:192
Inline: True
```
```
In security/apparmor/label.c (ffffffe0003edb2e)
Location: security/apparmor/label.c:1359
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
In security/apparmor/domain.c (ffffffff81493f20)
Location: security/apparmor/domain.c:192
Inline: True
```
```
In security/apparmor/label.c (ffffffff814a4c20)
Location: security/apparmor/label.c:1359
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
In security/apparmor/domain.c (ffffffff81484940)
Location: security/apparmor/domain.c:192
Inline: True
```
```
In security/apparmor/label.c (ffffffff81495640)
Location: security/apparmor/label.c:1359
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
In security/apparmor/domain.c (ffffffff8148ffc0)
Location: security/apparmor/domain.c:192
Inline: True
```
```
In security/apparmor/label.c (ffffffff814a0cc0)
Location: security/apparmor/label.c:1359
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
In security/apparmor/domain.c (ffffffff814a7ed0)
Location: security/apparmor/domain.c:192
Inline: True
```
```
In security/apparmor/label.c (ffffffff814b93e0)
Location: security/apparmor/label.c:1359
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
