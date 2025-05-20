# Function: <code>__list_lookup_parent</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff81380f39)
Location: security/apparmor/policy.c:685
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff813ba7f9)
Location: security/apparmor/policy.c:715
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff813d1bb9)
Location: security/apparmor/policy.c:716
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff813e4b16)
Location: security/apparmor/policy.c:701
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff8140bd5b)
Location: security/apparmor/policy.c:702
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff8143d5cf)
Location: security/apparmor/policy.c:707
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff8145a59b)
Location: security/apparmor/policy.c:707
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff814879af)
Location: security/apparmor/policy.c:702
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff814a185f)
Location: security/apparmor/policy.c:702
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct aa_profile *__list_lookup_parent(struct list_head *lh, struct aa_profile *profile);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff814f9b10)
Location: security/apparmor/policy.c:706
Inline: False
Direct callers:
  - security/apparmor/policy.c:aa_replace_profiles
```
**Symbols:**

```
ffffffff814f9b10-ffffffff814f9bce: __list_lookup_parent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct aa_profile *__list_lookup_parent(struct list_head *lh, struct aa_profile *profile);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff81516c40)
Location: security/apparmor/policy.c:706
Inline: False
Direct callers:
  - security/apparmor/policy.c:aa_replace_profiles
```
**Symbols:**

```
ffffffff81516c40-ffffffff81516cfe: __list_lookup_parent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff8151f361)
Location: security/apparmor/policy.c:706
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff8157d501)
Location: security/apparmor/policy.c:706
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff8161bb98)
Location: security/apparmor/policy.c:792
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff816cec5f)
Location: security/apparmor/policy.c:874
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff8170786b)
Location: security/apparmor/policy.c:909
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff817452fb)
Location: security/apparmor/policy.c:941
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffff800010597548)
Location: security/apparmor/policy.c:702
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (c07485dc)
Location: security/apparmor/policy.c:702
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (c00000000070dc04)
Location: security/apparmor/policy.c:702
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffe0003e41f6)
Location: security/apparmor/policy.c:702
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff81499e3f)
Location: security/apparmor/policy.c:702
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff8148a85f)
Location: security/apparmor/policy.c:702
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff81495edf)
Location: security/apparmor/policy.c:702
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff814adf6f)
Location: security/apparmor/policy.c:702
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
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
</ul>
