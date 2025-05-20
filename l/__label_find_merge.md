# Function: <code>__label_find_merge</code>

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
In security/apparmor/label.c (ffffffff8138af28)
Location: security/apparmor/label.c:1126
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_find_merge
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
In security/apparmor/label.c (ffffffff813c5c08)
Location: security/apparmor/label.c:1135
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_find_merge
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
In security/apparmor/label.c (ffffffff813dd248)
Location: security/apparmor/label.c:1150
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_find_merge
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
In security/apparmor/label.c (ffffffff813ed913)
Location: security/apparmor/label.c:1117
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_find_merge
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
In security/apparmor/label.c (ffffffff81415323)
Location: security/apparmor/label.c:1117
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_find_merge
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
In security/apparmor/label.c (ffffffff81447750)
Location: security/apparmor/label.c:1116
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_find_merge
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
In security/apparmor/label.c (ffffffff81464680)
Location: security/apparmor/label.c:1117
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_find_merge
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
In security/apparmor/label.c (ffffffff81491d11)
Location: security/apparmor/label.c:1113
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_find_merge
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
In security/apparmor/label.c (ffffffff814abc41)
Location: security/apparmor/label.c:1140
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_find_merge
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct aa_label *__label_find_merge(struct aa_labelset *ls, struct aa_label *a, struct aa_label *b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81508590)
Location: security/apparmor/label.c:1140
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_find_merge
```
**Symbols:**

```
ffffffff81508590-ffffffff8150870f: __label_find_merge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct aa_label *__label_find_merge(struct aa_labelset *ls, struct aa_label *a, struct aa_label *b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81525550)
Location: security/apparmor/label.c:1140
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_find_merge
```
**Symbols:**

```
ffffffff81525550-ffffffff815256cf: __label_find_merge (STB_LOCAL)
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
In security/apparmor/label.c (ffffffff8152d6cf)
Location: security/apparmor/label.c:1140
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_find_merge
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
In security/apparmor/label.c (ffffffff8158babf)
Location: security/apparmor/label.c:1140
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_find_merge
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
In security/apparmor/label.c (ffffffff8162d0d2)
Location: security/apparmor/label.c:1141
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_find_merge
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
In security/apparmor/label.c (ffffffff816e1bb2)
Location: security/apparmor/label.c:1141
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_find_merge
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
In security/apparmor/label.c (ffffffff8171b1a3)
Location: security/apparmor/label.c:1141
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_find_merge
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
In security/apparmor/label.c (ffffffff81759bf3)
Location: security/apparmor/label.c:1147
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_find_merge
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
In security/apparmor/label.c (ffff8000105a309c)
Location: security/apparmor/label.c:1140
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_find_merge
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
In security/apparmor/label.c (c0753254)
Location: security/apparmor/label.c:1140
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_find_merge
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
In security/apparmor/label.c (c00000000071e2fc)
Location: security/apparmor/label.c:1140
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_find_merge
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
In security/apparmor/label.c (ffffffe0003ed5a8)
Location: security/apparmor/label.c:1140
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_find_merge
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
In security/apparmor/label.c (ffffffff814a4221)
Location: security/apparmor/label.c:1140
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_find_merge
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
In security/apparmor/label.c (ffffffff81494c41)
Location: security/apparmor/label.c:1140
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_find_merge
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
In security/apparmor/label.c (ffffffff814a02c1)
Location: security/apparmor/label.c:1140
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_find_merge
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
In security/apparmor/label.c (ffffffff814b8941)
Location: security/apparmor/label.c:1140
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_find_merge
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
