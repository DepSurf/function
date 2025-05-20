# Function: <code>tpm_tis_reenable_interrupts</code>

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
In drivers/char/tpm/tpm_tis.c (ffffffff815283a0)
Location: drivers/char/tpm/tpm_tis.c:818
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_resume
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
In drivers/char/tpm/tpm_tis_core.c (ffffffff8157bcee)
Location: drivers/char/tpm/tpm_tis_core.c:785
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_resume
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
In drivers/char/tpm/tpm_tis_core.c (ffffffff815a818e)
Location: drivers/char/tpm/tpm_tis_core.c:813
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_resume
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
In drivers/char/tpm/tpm_tis_core.c (ffffffff815be3cb)
Location: drivers/char/tpm/tpm_tis_core.c:801
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_resume
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
In drivers/char/tpm/tpm_tis_core.c (ffffffff81624ad1)
Location: drivers/char/tpm/tpm_tis_core.c:902
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_resume
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
In drivers/char/tpm/tpm_tis_core.c (ffffffff8165ede7)
Location: drivers/char/tpm/tpm_tis_core.c:1012
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_resume
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
In drivers/char/tpm/tpm_tis_core.c (ffffffff8167d297)
Location: drivers/char/tpm/tpm_tis_core.c:1010
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_resume
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
In drivers/char/tpm/tpm_tis_core.c (ffffffff816b3018)
Location: drivers/char/tpm/tpm_tis_core.c:1013
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_resume
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
In drivers/char/tpm/tpm_tis_core.c (ffffffff816d5cf8)
Location: drivers/char/tpm/tpm_tis_core.c:1013
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_resume
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void tpm_tis_reenable_interrupts(struct tpm_chip *chip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff81789b40)
Location: drivers/char/tpm/tpm_tis_core.c:1098
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_resume
```
**Symbols:**

```
ffffffff81789b40-ffffffff81789c36: tpm_tis_reenable_interrupts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void tpm_tis_reenable_interrupts(struct tpm_chip *chip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff817a0a30)
Location: drivers/char/tpm/tpm_tis_core.c:1085
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_resume
```
**Symbols:**

```
ffffffff817a0a30-ffffffff817a0b26: tpm_tis_reenable_interrupts (STB_LOCAL)
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
In drivers/char/tpm/tpm_tis_core.c (ffffffff817844a6)
Location: drivers/char/tpm/tpm_tis_core.c:1094
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_resume
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
In drivers/char/tpm/tpm_tis_core.c (ffffffff8180aef6)
Location: drivers/char/tpm/tpm_tis_core.c:1112
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_resume
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
In drivers/char/tpm/tpm_tis_core.c (ffffffff8194b29c)
Location: drivers/char/tpm/tpm_tis_core.c:1112
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_resume
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
In drivers/char/tpm/tpm_tis_core.c (ffffffff81aaed7c)
Location: drivers/char/tpm/tpm_tis_core.c:1130
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_resume
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
In drivers/char/tpm/tpm_tis_core.c (ffffffff81af9c5b)
Location: drivers/char/tpm/tpm_tis_core.c:1284
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_resume
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
In drivers/char/tpm/tpm_tis_core.c (ffffffff81b4d27b)
Location: drivers/char/tpm/tpm_tis_core.c:1312
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_resume
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
In drivers/char/tpm/tpm_tis_core.c (ffff8000108c0d7c)
Location: drivers/char/tpm/tpm_tis_core.c:1013
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_resume
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
In drivers/char/tpm/tpm_tis_core.c (c09ba4bc)
Location: drivers/char/tpm/tpm_tis_core.c:1013
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_resume
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
In drivers/char/tpm/tpm_tis_core.c (c000000000964294)
Location: drivers/char/tpm/tpm_tis_core.c:1013
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_resume
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
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
In drivers/char/tpm/tpm_tis_core.c (ffffffff8169b748)
Location: drivers/char/tpm/tpm_tis_core.c:1013
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_resume
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
In drivers/char/tpm/tpm_tis_core.c (ffffffff81679138)
Location: drivers/char/tpm/tpm_tis_core.c:1013
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_resume
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
In drivers/char/tpm/tpm_tis_core.c (ffffffff816c99b8)
Location: drivers/char/tpm/tpm_tis_core.c:1013
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_resume
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
In drivers/char/tpm/tpm_tis_core.c (ffffffff816e3e98)
Location: drivers/char/tpm/tpm_tis_core.c:1013
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_resume
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
