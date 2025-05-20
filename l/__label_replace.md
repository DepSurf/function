# Function: <code>__label_replace</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool __label_replace(struct aa_label *old, struct aa_label *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81389450)
Location: security/apparmor/label.c:586
Inline: False
Direct callers:
  - security/apparmor/label.c:__label_insert
  - security/apparmor/label.c:aa_label_replace
```
**Symbols:**

```
ffffffff81389450-ffffffff813895b3: __label_replace (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool __label_replace(struct aa_label *old, struct aa_label *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff813c4010)
Location: security/apparmor/label.c:586
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:__label_insert
```
**Symbols:**

```
ffffffff813c4010-ffffffff813c4173: __label_replace (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool __label_replace(struct aa_label *old, struct aa_label *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff813db5a0)
Location: security/apparmor/label.c:602
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:__label_insert
```
**Symbols:**

```
ffffffff813db5a0-ffffffff813db703: __label_replace (STB_LOCAL)
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
In security/apparmor/label.c (ffffffff813ed55f)
Location: security/apparmor/label.c:604
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_replace
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
In security/apparmor/label.c (ffffffff81414f73)
Location: security/apparmor/label.c:604
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_replace
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
In security/apparmor/label.c (ffffffff8144737b)
Location: security/apparmor/label.c:603
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_replace
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
In security/apparmor/label.c (ffffffff814642ab)
Location: security/apparmor/label.c:604
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_replace
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
In security/apparmor/label.c (ffffffff8149153d)
Location: security/apparmor/label.c:600
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_replace
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
In security/apparmor/label.c (ffffffff814ab46d)
Location: security/apparmor/label.c:627
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_replace
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
In security/apparmor/label.c (ffffffff81509efd)
Location: security/apparmor/label.c:627
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_replace
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
In security/apparmor/label.c (ffffffff81526d6d)
Location: security/apparmor/label.c:627
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_replace
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
In security/apparmor/label.c (ffffffff8152c6fd)
Location: security/apparmor/label.c:627
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_replace
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
In security/apparmor/label.c (ffffffff8158aaed)
Location: security/apparmor/label.c:627
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_replace
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
In security/apparmor/label.c (ffffffff8162bfc5)
Location: security/apparmor/label.c:629
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_replace
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
In security/apparmor/label.c (ffffffff816e0a25)
Location: security/apparmor/label.c:629
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_replace
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
In security/apparmor/label.c (ffffffff8171a04d)
Location: security/apparmor/label.c:629
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_replace
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
In security/apparmor/label.c (ffffffff81758aed)
Location: security/apparmor/label.c:635
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_replace
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
In security/apparmor/label.c (ffff8000105a2660)
Location: security/apparmor/label.c:627
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_replace
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
In security/apparmor/label.c (c0752b24)
Location: security/apparmor/label.c:627
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_replace
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
In security/apparmor/label.c (c00000000071d6c8)
Location: security/apparmor/label.c:627
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_replace
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
In security/apparmor/label.c (ffffffe0003ece50)
Location: security/apparmor/label.c:627
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_replace
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
In security/apparmor/label.c (ffffffff814a3a4d)
Location: security/apparmor/label.c:627
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_replace
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
In security/apparmor/label.c (ffffffff8149446d)
Location: security/apparmor/label.c:627
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_replace
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
In security/apparmor/label.c (ffffffff8149faed)
Location: security/apparmor/label.c:627
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_replace
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
In security/apparmor/label.c (ffffffff814b811d)
Location: security/apparmor/label.c:627
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_replace
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
