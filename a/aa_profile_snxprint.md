# Function: <code>aa_profile_snxprint</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int aa_profile_snxprint(char *str, size_t size, struct aa_ns *ns, struct aa_profile *profile, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff8138c3b0)
Location: security/apparmor/label.c:1492
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_snxprint
```
**Symbols:**

```
ffffffff8138c3b0-ffffffff8138c564: aa_profile_snxprint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int aa_profile_snxprint(char *str, size_t size, struct aa_ns *ns, struct aa_profile *profile, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff813c71a0)
Location: security/apparmor/label.c:1501
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_snxprint
```
**Symbols:**

```
ffffffff813c71a0-ffffffff813c7364: aa_profile_snxprint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int aa_profile_snxprint(char *str, size_t size, struct aa_ns *ns, struct aa_profile *profile, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff813de780)
Location: security/apparmor/label.c:1516
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_snxprint
```
**Symbols:**

```
ffffffff813de780-ffffffff813de944: aa_profile_snxprint (STB_GLOBAL)
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
In security/apparmor/label.c (ffffffff813ee4a0)
Location: security/apparmor/label.c:1487
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_snxprint
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
In security/apparmor/label.c (ffffffff81416150)
Location: security/apparmor/label.c:1487
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_snxprint
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
In security/apparmor/label.c (ffffffff814485e4)
Location: security/apparmor/label.c:1486
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_snxprint
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
In security/apparmor/label.c (ffffffff81465517)
Location: security/apparmor/label.c:1487
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_snxprint
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
In security/apparmor/label.c (ffffffff81492b1d)
Location: security/apparmor/label.c:1483
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_snxprint
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
In security/apparmor/label.c (ffffffff814aca4d)
Location: security/apparmor/label.c:1512
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_snxprint
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff8150b4b1)
Location: security/apparmor/label.c:1512
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_snxprint
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81528361)
Location: security/apparmor/label.c:1512
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_snxprint
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
In security/apparmor/label.c (ffffffff8152e4d4)
Location: security/apparmor/label.c:1512
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_snxprint
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
In security/apparmor/label.c (ffffffff8158c8c4)
Location: security/apparmor/label.c:1512
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_snxprint
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
In security/apparmor/label.c (ffffffff8162da7e)
Location: security/apparmor/label.c:1518
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_snxprint
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
In security/apparmor/label.c (ffffffff816e257f)
Location: security/apparmor/label.c:1512
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_snxprint
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
In security/apparmor/label.c (ffffffff8171bb62)
Location: security/apparmor/label.c:1512
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_snxprint
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
In security/apparmor/label.c (ffffffff8175a5b2)
Location: security/apparmor/label.c:1518
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_snxprint
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
In security/apparmor/label.c (ffff8000105a3c50)
Location: security/apparmor/label.c:1512
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_snxprint
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
In security/apparmor/label.c (c0753ec8)
Location: security/apparmor/label.c:1512
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_snxprint
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
In security/apparmor/label.c (c00000000071f448)
Location: security/apparmor/label.c:1512
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_snxprint
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
In security/apparmor/label.c (ffffffe0003edf70)
Location: security/apparmor/label.c:1512
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_snxprint
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
In security/apparmor/label.c (ffffffff814a502d)
Location: security/apparmor/label.c:1512
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_snxprint
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
In security/apparmor/label.c (ffffffff81495a4d)
Location: security/apparmor/label.c:1512
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_snxprint
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
In security/apparmor/label.c (ffffffff814a10cd)
Location: security/apparmor/label.c:1512
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_snxprint
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
In security/apparmor/label.c (ffffffff814b97ed)
Location: security/apparmor/label.c:1512
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_snxprint
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
</ul>
