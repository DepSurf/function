# Function: <code>mfill_zeropage_pte</code>

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
In mm/userfaultfd.c (ffffffff81207e95)
Location: mm/userfaultfd.c:100
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
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
In mm/userfaultfd.c (ffffffff8122d834)
Location: mm/userfaultfd.c:100
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
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
In mm/userfaultfd.c (ffffffff8123fd72)
Location: mm/userfaultfd.c:100
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
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
In mm/userfaultfd.c (ffffffff8124bc56)
Location: mm/userfaultfd.c:104
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
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
In mm/userfaultfd.c (ffffffff8126bfd3)
Location: mm/userfaultfd.c:104
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
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
In mm/userfaultfd.c (ffffffff81290a06)
Location: mm/userfaultfd.c:103
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
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
In mm/userfaultfd.c (ffffffff812a59d8)
Location: mm/userfaultfd.c:114
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
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
In mm/userfaultfd.c (ffffffff812c10cf)
Location: mm/userfaultfd.c:112
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
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
In mm/userfaultfd.c (ffffffff812d301f)
Location: mm/userfaultfd.c:112
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int mfill_zeropage_pte(struct mm_struct *dst_mm, pmd_t *dst_pmd, struct vm_area_struct *dst_vma, long unsigned int dst_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/userfaultfd.c (ffffffff81307e00)
Location: mm/userfaultfd.c:144
Inline: False
Direct callers:
  - mm/userfaultfd.c:mfill_zeropage
```
**Symbols:**

```
ffffffff81307e00-ffffffff81307fbd: mfill_zeropage_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/userfaultfd.c (ffffffff81313bb0)
Location: mm/userfaultfd.c:144
Inline: True
Direct callers:
  - mm/userfaultfd.c:mfill_zeropage
```
**Symbols:**

```
ffffffff81313bb0-ffffffff81313d5d: mfill_zeropage_pte.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/userfaultfd.c (ffffffff81319d50)
Location: mm/userfaultfd.c:144
Inline: True
Direct callers:
  - mm/userfaultfd.c:mfill_zeropage
```
**Symbols:**

```
ffffffff81319d50-ffffffff81319f08: mfill_zeropage_pte.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/userfaultfd.c (ffffffff81366b00)
Location: mm/userfaultfd.c:181
Inline: True
Direct callers:
  - mm/userfaultfd.c:mfill_zeropage
```
**Symbols:**

```
ffffffff81366b00-ffffffff81366cb8: mfill_zeropage_pte.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/userfaultfd.c (ffffffff813e3f50)
Location: mm/userfaultfd.c:202
Inline: True
Direct callers:
  - mm/userfaultfd.c:mfill_zeropage
```
**Symbols:**

```
ffffffff813e3f50-ffffffff813e412d: mfill_zeropage_pte.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/userfaultfd.c (ffffffff8146b9c0)
Location: mm/userfaultfd.c:221
Inline: True
Direct callers:
  - mm/userfaultfd.c:mfill_zeropage
```
**Symbols:**

```
ffffffff8146b9c0-ffffffff8146bb9e: mfill_zeropage_pte.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In mm/userfaultfd.c (ffff800010378c2c)
Location: mm/userfaultfd.c:112
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
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
In mm/userfaultfd.c (c0563ff4)
Location: mm/userfaultfd.c:112
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
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
In mm/userfaultfd.c (c00000000046b8e0)
Location: mm/userfaultfd.c:112
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
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
In mm/userfaultfd.c (ffffffe0002504b0)
Location: mm/userfaultfd.c:112
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
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
In mm/userfaultfd.c (ffffffff812cb5ff)
Location: mm/userfaultfd.c:112
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
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
In mm/userfaultfd.c (ffffffff812bc4ad)
Location: mm/userfaultfd.c:112
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
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
In mm/userfaultfd.c (ffffffff812c940f)
Location: mm/userfaultfd.c:112
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
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
In mm/userfaultfd.c (ffffffff812da0ef)
Location: mm/userfaultfd.c:112
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
