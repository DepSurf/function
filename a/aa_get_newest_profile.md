# Function: <code>aa_get_newest_profile</code>

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
In security/apparmor/policy.c (ffffffff8138008b)
Location: security/apparmor/include/policy.h:190
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_lookupn_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_replace_profiles
```
```
In security/apparmor/label.c (ffffffff8138b54e)
Location: security/apparmor/include/policy.h:190
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:__aa_labelset_update_subtree
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
In security/apparmor/policy.c (ffffffff813bacea)
Location: security/apparmor/include/policy.h:207
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_fqlookupn_profile
```
```
In security/apparmor/label.c (ffffffff813c8c11)
Location: security/apparmor/include/policy.h:207
Inline: True
Inline callers:
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:aa_label_merge
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
In security/apparmor/policy.c (ffffffff813d20b2)
Location: security/apparmor/include/policy.h:207
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_fqlookupn_profile
```
```
In security/apparmor/label.c (ffffffff813e022d)
Location: security/apparmor/include/policy.h:207
Inline: True
Inline callers:
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:aa_label_merge
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
In security/apparmor/policy.c (ffffffff813e50dd)
Location: security/apparmor/include/policy.h:210
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_fqlookupn_profile
```
```
In security/apparmor/label.c (ffffffff813ef6aa)
Location: security/apparmor/include/policy.h:210
Inline: True
Inline callers:
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:aa_label_merge
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
In security/apparmor/policy.c (ffffffff8140c1dd)
Location: security/apparmor/include/policy.h:210
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_fqlookupn_profile
```
```
In security/apparmor/label.c (ffffffff814175cd)
Location: security/apparmor/include/policy.h:210
Inline: True
Inline callers:
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:aa_label_merge
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
In security/apparmor/policy.c (ffffffff8143daca)
Location: security/apparmor/include/policy.h:214
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_fqlookupn_profile
```
```
In security/apparmor/label.c (ffffffff81449a32)
Location: security/apparmor/include/policy.h:214
Inline: True
Inline callers:
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:aa_label_merge
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
In security/apparmor/policy.c (ffffffff8145a929)
Location: security/apparmor/include/policy.h:214
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_fqlookupn_profile
```
```
In security/apparmor/label.c (ffffffff814669c2)
Location: security/apparmor/include/policy.h:214
Inline: True
Inline callers:
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:aa_label_merge
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
In security/apparmor/policy.c (ffffffff81487f42)
Location: security/apparmor/include/policy.h:210
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_fqlookupn_profile
```
```
In security/apparmor/label.c (ffffffff814918b6)
Location: security/apparmor/include/policy.h:210
Inline: True
Inline callers:
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:aa_label_merge
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
In security/apparmor/domain.c (ffffffff8149c2b3)
Location: security/apparmor/include/policy.h:210
Inline: True
Inline callers:
  - security/apparmor/domain.c:find_attach
```
```
In security/apparmor/policy.c (ffffffff814a1df2)
Location: security/apparmor/include/policy.h:210
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_fqlookupn_profile
```
```
In security/apparmor/label.c (ffffffff814ab7e6)
Location: security/apparmor/include/policy.h:210
Inline: True
Inline callers:
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:aa_label_merge
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
struct aa_profile *aa_get_newest_profile(struct aa_profile *p);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff814f4cc3)
Location: security/apparmor/include/policy.h:213
Inline: True
Inline callers:
  - security/apparmor/domain.c:find_attach
```
```
In security/apparmor/policy.c (ffffffff814f9fd9)
Location: security/apparmor/include/policy.h:213
Inline: True
Inline callers:
  - security/apparmor/policy.c:update_to_newest_parent
Direct callers:
  - security/apparmor/policy.c:aa_fqlookupn_profile
```
```
In security/apparmor/label.c (ffffffff8150a45e)
Location: security/apparmor/include/policy.h:213
Inline: True
Inline callers:
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:label_merge_insert
```
**Symbols:**

```
ffffffff814f9e50-ffffffff814f9fba: aa_get_newest_profile (STB_LOCAL)
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
In security/apparmor/domain.c (ffffffff815120c8)
Location: security/apparmor/include/policy.h:213
Inline: True
Inline callers:
  - security/apparmor/domain.c:find_attach
```
```
In security/apparmor/policy.c (ffffffff81519087)
Location: security/apparmor/include/policy.h:213
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_fqlookupn_profile
```
```
In security/apparmor/label.c (ffffffff815272d2)
Location: security/apparmor/include/policy.h:213
Inline: True
Inline callers:
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:label_merge_insert
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
In security/apparmor/domain.c (ffffffff81518a00)
Location: security/apparmor/include/policy.h:213
Inline: True
Inline callers:
  - security/apparmor/domain.c:find_attach
```
```
In security/apparmor/policy.c (ffffffff8151f95c)
Location: security/apparmor/include/policy.h:213
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_fqlookupn_profile
```
```
In security/apparmor/label.c (ffffffff8152cc49)
Location: security/apparmor/include/policy.h:213
Inline: True
Inline callers:
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:label_merge_insert
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
In security/apparmor/domain.c (ffffffff81576a10)
Location: security/apparmor/include/policy.h:213
Inline: True
Inline callers:
  - security/apparmor/domain.c:find_attach
```
```
In security/apparmor/policy.c (ffffffff8157dafc)
Location: security/apparmor/include/policy.h:213
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_fqlookupn_profile
```
```
In security/apparmor/label.c (ffffffff8158b039)
Location: security/apparmor/include/policy.h:213
Inline: True
Inline callers:
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:label_merge_insert
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
struct aa_profile *aa_get_newest_profile(struct aa_profile *p);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff816148c3)
Location: security/apparmor/include/policy.h:271
Inline: True
Inline callers:
  - security/apparmor/domain.c:find_attach
```
```
In security/apparmor/policy.c (ffffffff8161c281)
Location: security/apparmor/include/policy.h:271
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
Direct callers:
  - security/apparmor/policy.c:aa_fqlookupn_profile
```
```
In security/apparmor/label.c (ffffffff8162c54e)
Location: security/apparmor/include/policy.h:271
Inline: True
Inline callers:
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:label_merge_insert
```
**Symbols:**

```
ffffffff81619d60-ffffffff81619ef3: aa_get_newest_profile (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline ⚠️</summary>

```c
struct aa_profile *aa_get_newest_profile(struct aa_profile *p);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff816c75e0)
Location: security/apparmor/include/policy.h:277
Inline: True
Inline callers:
  - security/apparmor/domain.c:find_attach
```
```
In security/apparmor/policy.c (ffffffff816cf43a)
Location: security/apparmor/include/policy.h:277
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
Direct callers:
  - security/apparmor/policy.c:aa_fqlookupn_profile
```
```
In security/apparmor/label.c (ffffffff816e0fee)
Location: security/apparmor/include/policy.h:277
Inline: True
Inline callers:
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:label_merge_insert
```
**Symbols:**

```
ffffffff816cccc0-ffffffff816cce53: aa_get_newest_profile (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline ⚠️</summary>

```c
struct aa_profile *aa_get_newest_profile(struct aa_profile *p);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff816ffbb3)
Location: security/apparmor/include/policy.h:308
Inline: True
Inline callers:
  - security/apparmor/domain.c:find_attach
```
```
In security/apparmor/policy.c (ffffffff8170803f)
Location: security/apparmor/include/policy.h:308
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
Direct callers:
  - security/apparmor/policy.c:aa_fqlookupn_profile
```
```
In security/apparmor/label.c (ffffffff8171a5ee)
Location: security/apparmor/include/policy.h:308
Inline: True
Inline callers:
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:label_merge_insert
```
**Symbols:**

```
ffffffff81705760-ffffffff817058df: aa_get_newest_profile (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
struct aa_profile *aa_get_newest_profile(struct aa_profile *p);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff8173d18f)
Location: security/apparmor/include/policy.h:305
Inline: True
Inline callers:
  - security/apparmor/domain.c:find_attach
```
```
In security/apparmor/policy.c (ffffffff81745acf)
Location: security/apparmor/include/policy.h:305
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
Direct callers:
  - security/apparmor/policy.c:aa_fqlookupn_profile
```
```
In security/apparmor/label.c (ffffffff817590a0)
Location: security/apparmor/include/policy.h:305
Inline: True
Inline callers:
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:label_merge_insert
```
**Symbols:**

```
ffffffff81743060-ffffffff817431df: aa_get_newest_profile (STB_LOCAL)
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
In security/apparmor/domain.c (ffff800010591dbc)
Location: security/apparmor/include/policy.h:210
Inline: True
Inline callers:
  - security/apparmor/domain.c:find_attach
```
```
In security/apparmor/policy.c (ffff8000105979e0)
Location: security/apparmor/include/policy.h:210
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_fqlookupn_profile
```
```
In security/apparmor/label.c (ffff8000105a2ba0)
Location: security/apparmor/include/policy.h:210
Inline: True
Inline callers:
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:aa_label_merge
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
In security/apparmor/domain.c (c07429ec)
Location: security/apparmor/include/policy.h:210
Inline: True
Inline callers:
  - security/apparmor/domain.c:find_attach
```
```
In security/apparmor/policy.c (c0748b8c)
Location: security/apparmor/include/policy.h:210
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_fqlookupn_profile
```
```
In security/apparmor/label.c (c0752e5c)
Location: security/apparmor/include/policy.h:210
Inline: True
Inline callers:
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:aa_label_merge
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
In security/apparmor/domain.c (c000000000706a50)
Location: security/apparmor/include/policy.h:210
Inline: True
Inline callers:
  - security/apparmor/domain.c:find_attach
```
```
In security/apparmor/policy.c (c00000000070dfc4)
Location: security/apparmor/include/policy.h:210
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_fqlookupn_profile
```
```
In security/apparmor/label.c (c00000000071dc0c)
Location: security/apparmor/include/policy.h:210
Inline: True
Inline callers:
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:aa_label_merge
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
In security/apparmor/domain.c (ffffffe0003dff1c)
Location: security/apparmor/include/policy.h:210
Inline: True
Inline callers:
  - security/apparmor/domain.c:find_attach
```
```
In security/apparmor/policy.c (ffffffe0003e43d8)
Location: security/apparmor/include/policy.h:210
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_fqlookupn_profile
```
```
In security/apparmor/label.c (ffffffe0003ed16e)
Location: security/apparmor/include/policy.h:210
Inline: True
Inline callers:
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:aa_label_merge
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
In security/apparmor/domain.c (ffffffff81494893)
Location: security/apparmor/include/policy.h:210
Inline: True
Inline callers:
  - security/apparmor/domain.c:find_attach
```
```
In security/apparmor/policy.c (ffffffff8149a3d2)
Location: security/apparmor/include/policy.h:210
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_fqlookupn_profile
```
```
In security/apparmor/label.c (ffffffff814a3dc6)
Location: security/apparmor/include/policy.h:210
Inline: True
Inline callers:
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:aa_label_merge
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
In security/apparmor/domain.c (ffffffff814852b3)
Location: security/apparmor/include/policy.h:210
Inline: True
Inline callers:
  - security/apparmor/domain.c:find_attach
```
```
In security/apparmor/policy.c (ffffffff8148adf2)
Location: security/apparmor/include/policy.h:210
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_fqlookupn_profile
```
```
In security/apparmor/label.c (ffffffff814947e6)
Location: security/apparmor/include/policy.h:210
Inline: True
Inline callers:
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:aa_label_merge
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
In security/apparmor/domain.c (ffffffff81490933)
Location: security/apparmor/include/policy.h:210
Inline: True
Inline callers:
  - security/apparmor/domain.c:find_attach
```
```
In security/apparmor/policy.c (ffffffff81496472)
Location: security/apparmor/include/policy.h:210
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_fqlookupn_profile
```
```
In security/apparmor/label.c (ffffffff8149fe66)
Location: security/apparmor/include/policy.h:210
Inline: True
Inline callers:
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:aa_label_merge
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
In security/apparmor/domain.c (ffffffff814a886e)
Location: security/apparmor/include/policy.h:210
Inline: True
Inline callers:
  - security/apparmor/domain.c:find_attach
```
```
In security/apparmor/policy.c (ffffffff814ae4f5)
Location: security/apparmor/include/policy.h:210
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_fqlookupn_profile
```
```
In security/apparmor/label.c (ffffffff814b8522)
Location: security/apparmor/include/policy.h:210
Inline: True
Inline callers:
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:aa_label_merge
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
