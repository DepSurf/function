# Function: <code>label_merge_insert</code>

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
In security/apparmor/label.c (ffffffff8138b4a7)
Location: security/apparmor/label.c:1044
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_merge
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
In security/apparmor/label.c (ffffffff813c6197)
Location: security/apparmor/label.c:1044
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_merge
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
In security/apparmor/label.c (ffffffff813dd7d8)
Location: security/apparmor/label.c:1060
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_merge
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
In security/apparmor/label.c (ffffffff813edb8f)
Location: security/apparmor/label.c:1024
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_merge
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
In security/apparmor/label.c (ffffffff814156f2)
Location: security/apparmor/label.c:1024
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_merge
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
In security/apparmor/label.c (ffffffff81447b0f)
Location: security/apparmor/label.c:1023
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_merge
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
In security/apparmor/label.c (ffffffff81464a3f)
Location: security/apparmor/label.c:1024
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_merge
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
In security/apparmor/label.c (ffffffff81492010)
Location: security/apparmor/label.c:1020
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_merge
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
In security/apparmor/label.c (ffffffff814abf40)
Location: security/apparmor/label.c:1047
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_merge
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct aa_label *label_merge_insert(struct aa_label *new, struct aa_label *a, struct aa_label *b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff8150a850)
Location: security/apparmor/label.c:1047
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_merge
```
**Symbols:**

```
ffffffff8150a850-ffffffff8150ac7f: label_merge_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct aa_label *label_merge_insert(struct aa_label *new, struct aa_label *a, struct aa_label *b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff815276d0)
Location: security/apparmor/label.c:1047
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_merge
```
**Symbols:**

```
ffffffff815276d0-ffffffff81527b1c: label_merge_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct aa_label *label_merge_insert(struct aa_label *new, struct aa_label *a, struct aa_label *b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff8152d210)
Location: security/apparmor/label.c:1047
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_merge
```
**Symbols:**

```
ffffffff8152d210-ffffffff8152d605: label_merge_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct aa_label *label_merge_insert(struct aa_label *new, struct aa_label *a, struct aa_label *b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff8158b600)
Location: security/apparmor/label.c:1047
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_merge
```
**Symbols:**

```
ffffffff8158b600-ffffffff8158b9f5: label_merge_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct aa_label *label_merge_insert(struct aa_label *new, struct aa_label *a, struct aa_label *b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff8162cba0)
Location: security/apparmor/label.c:1049
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_merge
```
**Symbols:**

```
ffffffff8162cba0-ffffffff8162d001: label_merge_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct aa_label *label_merge_insert(struct aa_label *new, struct aa_label *a, struct aa_label *b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff816e1670)
Location: security/apparmor/label.c:1049
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_merge
```
**Symbols:**

```
ffffffff816e1670-ffffffff816e1ad1: label_merge_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct aa_label *label_merge_insert(struct aa_label *new, struct aa_label *a, struct aa_label *b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff8171ac70)
Location: security/apparmor/label.c:1049
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_merge
```
**Symbols:**

```
ffffffff8171ac70-ffffffff8171b0cb: label_merge_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct aa_label *label_merge_insert(struct aa_label *new, struct aa_label *a, struct aa_label *b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81759720)
Location: security/apparmor/label.c:1056
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_merge
```
**Symbols:**

```
ffffffff81759720-ffffffff81759b20: label_merge_insert (STB_LOCAL)
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
In security/apparmor/label.c (ffff8000105a3364)
Location: security/apparmor/label.c:1047
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_merge
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
In security/apparmor/label.c (c07534fc)
Location: security/apparmor/label.c:1047
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_merge
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
In security/apparmor/label.c (c00000000071e708)
Location: security/apparmor/label.c:1047
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_merge
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
In security/apparmor/label.c (ffffffe0003ed732)
Location: security/apparmor/label.c:1047
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_merge
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
In security/apparmor/label.c (ffffffff814a4520)
Location: security/apparmor/label.c:1047
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_merge
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
In security/apparmor/label.c (ffffffff81494f40)
Location: security/apparmor/label.c:1047
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_merge
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
In security/apparmor/label.c (ffffffff814a05c0)
Location: security/apparmor/label.c:1047
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_merge
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
In security/apparmor/label.c (ffffffff814b8bf7)
Location: security/apparmor/label.c:1047
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_merge
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
