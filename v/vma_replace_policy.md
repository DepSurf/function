# Function: <code>vma_replace_policy</code>

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
In mm/mempolicy.c (ffffffff811e27c6)
Location: mm/mempolicy.c:659
Inline: True
Inline callers:
  - mm/mempolicy.c:do_mbind
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
In mm/mempolicy.c (ffffffff812011e8)
Location: mm/mempolicy.c:691
Inline: True
Inline callers:
  - mm/mempolicy.c:do_mbind
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
In mm/mempolicy.c (ffffffff81212d2a)
Location: mm/mempolicy.c:693
Inline: True
Inline callers:
  - mm/mempolicy.c:SYSC_mbind
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
In mm/mempolicy.c (ffffffff8121e09b)
Location: mm/mempolicy.c:627
Inline: True
Inline callers:
  - mm/mempolicy.c:SYSC_mbind
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
In mm/mempolicy.c (ffffffff812392eb)
Location: mm/mempolicy.c:669
Inline: True
Inline callers:
  - mm/mempolicy.c:SYSC_mbind
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
In mm/mempolicy.c (ffffffff8125c75a)
Location: mm/mempolicy.c:644
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_mbind
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
In mm/mempolicy.c (ffffffff8127103a)
Location: mm/mempolicy.c:670
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_mbind
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
In mm/mempolicy.c (ffffffff8128c550)
Location: mm/mempolicy.c:697
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_mbind
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
In mm/mempolicy.c (ffffffff8129c14e)
Location: mm/mempolicy.c:698
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_mbind
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int vma_replace_policy(struct vm_area_struct *vma, struct mempolicy *pol);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812cf920)
Location: mm/mempolicy.c:769
Inline: False
Direct callers:
  - mm/mempolicy.c:mbind_range
```
**Symbols:**

```
ffffffff812cf920-ffffffff812cfa0c: vma_replace_policy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int vma_replace_policy(struct vm_area_struct *vma, struct mempolicy *pol);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812db3f0)
Location: mm/mempolicy.c:769
Inline: False
Direct callers:
  - mm/mempolicy.c:mbind_range
```
**Symbols:**

```
ffffffff812db3f0-ffffffff812db4dc: vma_replace_policy (STB_LOCAL)
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
In mm/mempolicy.c (ffffffff812e2dee)
Location: mm/mempolicy.c:769
Inline: True
Inline callers:
  - mm/mempolicy.c:mbind_range
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
In mm/mempolicy.c (ffffffff8132a14e)
Location: mm/mempolicy.c:750
Inline: True
Inline callers:
  - mm/mempolicy.c:mbind_range
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
In mm/mempolicy.c (ffffffff813998dd)
Location: mm/mempolicy.c:754
Inline: True
Inline callers:
  - mm/mempolicy.c:mbind_range
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
In mm/mempolicy.c (ffffffff81419802)
Location: mm/mempolicy.c:755
Inline: True
Inline callers:
  - mm/mempolicy.c:mbind_range
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int vma_replace_policy(struct vm_area_struct *vma, struct mempolicy *pol);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8144ca00)
Location: mm/mempolicy.c:776
Inline: False
Direct callers:
  - mm/mempolicy.c:mbind_range
  - mm/mempolicy.c:mbind_range
```
**Symbols:**

```
ffffffff8144ca00-ffffffff8144cb02: vma_replace_policy (STB_LOCAL)
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
In mm/mempolicy.c (ffffffff81486636)
Location: mm/mempolicy.c:755
Inline: True
Inline callers:
  - mm/mempolicy.c:mbind_range
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
In mm/mempolicy.c (ffff80001033b1d8)
Location: mm/mempolicy.c:698
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_mbind
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (c000000000415c2c)
Location: mm/mempolicy.c:698
Inline: True
Inline callers:
  - mm/mempolicy.c:do_mbind
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
In mm/mempolicy.c (ffffffff8129472e)
Location: mm/mempolicy.c:698
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_mbind
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
In mm/mempolicy.c (ffffffff8128633e)
Location: mm/mempolicy.c:698
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_mbind
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
In mm/mempolicy.c (ffffffff8129253e)
Location: mm/mempolicy.c:698
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_mbind
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
In mm/mempolicy.c (ffffffff812a239f)
Location: mm/mempolicy.c:698
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_mbind
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
