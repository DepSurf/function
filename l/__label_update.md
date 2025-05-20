# Function: <code>__label_update</code>

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
In security/apparmor/label.c (ffffffff8138dd7d)
Location: security/apparmor/label.c:1973
Inline: True
Inline callers:
  - security/apparmor/label.c:__aa_labelset_update_subtree
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
In security/apparmor/label.c (ffffffff813c8b7d)
Location: security/apparmor/label.c:1993
Inline: True
Inline callers:
  - security/apparmor/label.c:__aa_labelset_update_subtree
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
In security/apparmor/label.c (ffffffff813e0195)
Location: security/apparmor/label.c:2031
Inline: True
Inline callers:
  - security/apparmor/label.c:__aa_labelset_update_subtree
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
In security/apparmor/label.c (ffffffff813ef64f)
Location: security/apparmor/label.c:2010
Inline: True
Inline callers:
  - security/apparmor/label.c:__aa_labelset_update_subtree
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
In security/apparmor/label.c (ffffffff81417562)
Location: security/apparmor/label.c:2010
Inline: True
Inline callers:
  - security/apparmor/label.c:__aa_labelset_update_subtree
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
In security/apparmor/label.c (ffffffff814499ca)
Location: security/apparmor/label.c:2023
Inline: True
Inline callers:
  - security/apparmor/label.c:__aa_labelset_update_subtree
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
In security/apparmor/label.c (ffffffff8146695a)
Location: security/apparmor/label.c:2024
Inline: True
Inline callers:
  - security/apparmor/label.c:__aa_labelset_update_subtree
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
In security/apparmor/label.c (ffffffff8149184b)
Location: security/apparmor/label.c:2020
Inline: True
Inline callers:
  - security/apparmor/label.c:__labelset_update
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
In security/apparmor/label.c (ffffffff814ab77b)
Location: security/apparmor/label.c:2049
Inline: True
Inline callers:
  - security/apparmor/label.c:__labelset_update
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct aa_label *__label_update(struct aa_label *label);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff8150a330)
Location: security/apparmor/label.c:2046
Inline: False
Direct callers:
  - security/apparmor/label.c:__aa_labelset_update_subtree
```
**Symbols:**

```
ffffffff8150a330-ffffffff8150a77f: __label_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct aa_label *__label_update(struct aa_label *label);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff815271a0)
Location: security/apparmor/label.c:2046
Inline: False
Direct callers:
  - security/apparmor/label.c:__aa_labelset_update_subtree
```
**Symbols:**

```
ffffffff815271a0-ffffffff815275f7: __label_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct aa_label *__label_update(struct aa_label *label);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff8152cb20)
Location: security/apparmor/label.c:2046
Inline: False
Direct callers:
  - security/apparmor/label.c:__labelset_update
```
**Symbols:**

```
ffffffff8152cb20-ffffffff8152cf64: __label_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct aa_label *__label_update(struct aa_label *label);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff8158af10)
Location: security/apparmor/label.c:2046
Inline: False
Direct callers:
  - security/apparmor/label.c:__labelset_update
```
**Symbols:**

```
ffffffff8158af10-ffffffff8158b354: __label_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct aa_label *__label_update(struct aa_label *label);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff8162c430)
Location: security/apparmor/label.c:2056
Inline: False
Direct callers:
  - security/apparmor/label.c:__labelset_update
```
**Symbols:**

```
ffffffff8162c430-ffffffff8162c8bf: __label_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct aa_label *__label_update(struct aa_label *label);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff816e0ed0)
Location: security/apparmor/label.c:2050
Inline: False
Direct callers:
  - security/apparmor/label.c:__labelset_update
```
**Symbols:**

```
ffffffff816e0ed0-ffffffff816e135f: __label_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct aa_label *__label_update(struct aa_label *label);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff8171a4d0)
Location: security/apparmor/label.c:2050
Inline: False
Direct callers:
  - security/apparmor/label.c:__labelset_update
```
**Symbols:**

```
ffffffff8171a4d0-ffffffff8171a957: __label_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct aa_label *__label_update(struct aa_label *label);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81758f80)
Location: security/apparmor/label.c:2056
Inline: False
Direct callers:
  - security/apparmor/label.c:__labelset_update
```
**Symbols:**

```
ffffffff81758f80-ffffffff81759409: __label_update (STB_LOCAL)
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
In security/apparmor/label.c (ffff8000105a2b0c)
Location: security/apparmor/label.c:2049
Inline: True
Inline callers:
  - security/apparmor/label.c:__labelset_update
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
In security/apparmor/label.c (c0752dec)
Location: security/apparmor/label.c:2049
Inline: True
Inline callers:
  - security/apparmor/label.c:__labelset_update
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
In security/apparmor/label.c (c00000000071db1c)
Location: security/apparmor/label.c:2049
Inline: True
Inline callers:
  - security/apparmor/label.c:__labelset_update
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
In security/apparmor/label.c (ffffffe0003ed128)
Location: security/apparmor/label.c:2049
Inline: True
Inline callers:
  - security/apparmor/label.c:__labelset_update
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
In security/apparmor/label.c (ffffffff814a3d5b)
Location: security/apparmor/label.c:2049
Inline: True
Inline callers:
  - security/apparmor/label.c:__labelset_update
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
In security/apparmor/label.c (ffffffff8149477b)
Location: security/apparmor/label.c:2049
Inline: True
Inline callers:
  - security/apparmor/label.c:__labelset_update
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
In security/apparmor/label.c (ffffffff8149fdfb)
Location: security/apparmor/label.c:2049
Inline: True
Inline callers:
  - security/apparmor/label.c:__labelset_update
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
In security/apparmor/label.c (ffffffff814b842c)
Location: security/apparmor/label.c:2049
Inline: True
Inline callers:
  - security/apparmor/label.c:__labelset_update
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
