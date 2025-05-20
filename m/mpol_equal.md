# Function: <code>mpol_equal</code>

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
In mm/mmap.c (ffffffff811c4092)
Location: include/linux/mempolicy.h:102
Inline: True
Inline callers:
  - mm/mmap.c:reusable_anon_vma
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
```
```
In mm/mempolicy.c (ffffffff811e26ec)
Location: include/linux/mempolicy.h:102
Inline: True
Inline callers:
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_mbind
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
In mm/mmap.c (ffffffff811dff52)
Location: include/linux/mempolicy.h:102
Inline: True
Inline callers:
  - mm/mmap.c:reusable_anon_vma
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
```
```
In mm/mempolicy.c (ffffffff81201111)
Location: include/linux/mempolicy.h:102
Inline: True
Inline callers:
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_mbind
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
In mm/mmap.c (ffffffff811efea2)
Location: include/linux/mempolicy.h:103
Inline: True
Inline callers:
  - mm/mmap.c:reusable_anon_vma
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
```
```
In mm/mempolicy.c (ffffffff81212c30)
Location: include/linux/mempolicy.h:103
Inline: True
Inline callers:
  - mm/mempolicy.c:SYSC_mbind
  - mm/mempolicy.c:SYSC_mbind
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
In mm/mmap.c (ffffffff811fae4c)
Location: include/linux/mempolicy.h:103
Inline: True
Inline callers:
  - mm/mmap.c:anon_vma_compatible
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
```
```
In mm/mempolicy.c (ffffffff8121dfd3)
Location: include/linux/mempolicy.h:103
Inline: True
Inline callers:
  - mm/mempolicy.c:SYSC_mbind
  - mm/mempolicy.c:SYSC_mbind
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
In mm/mmap.c (ffffffff8121336c)
Location: include/linux/mempolicy.h:104
Inline: True
Inline callers:
  - mm/mmap.c:anon_vma_compatible
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
```
```
In mm/mempolicy.c (ffffffff81239223)
Location: include/linux/mempolicy.h:104
Inline: True
Inline callers:
  - mm/mempolicy.c:SYSC_mbind
  - mm/mempolicy.c:SYSC_mbind
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
In mm/mmap.c (ffffffff8123430c)
Location: include/linux/mempolicy.h:104
Inline: True
Inline callers:
  - mm/mmap.c:anon_vma_compatible
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
```
```
In mm/mempolicy.c (ffffffff8125c742)
Location: include/linux/mempolicy.h:104
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:kernel_mbind
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
In mm/mmap.c (ffffffff81247abc)
Location: include/linux/mempolicy.h:104
Inline: True
Inline callers:
  - mm/mmap.c:anon_vma_compatible
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
```
```
In mm/mempolicy.c (ffffffff81271022)
Location: include/linux/mempolicy.h:104
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:kernel_mbind
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
In mm/mmap.c (ffffffff81259c05)
Location: include/linux/mempolicy.h:104
Inline: True
Inline callers:
  - mm/mmap.c:anon_vma_compatible
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
```
```
In mm/mempolicy.c (ffffffff8128c538)
Location: include/linux/mempolicy.h:104
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:kernel_mbind
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
In mm/mmap.c (ffffffff812680b5)
Location: include/linux/mempolicy.h:104
Inline: True
Inline callers:
  - mm/mmap.c:anon_vma_compatible
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
```
```
In mm/mempolicy.c (ffffffff8129c136)
Location: include/linux/mempolicy.h:104
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:kernel_mbind
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81298765)
Location: include/linux/mempolicy.h:104
Inline: True
Inline callers:
  - mm/mmap.c:anon_vma_compatible
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
```
```
In mm/mempolicy.c (ffffffff812cfb83)
Location: include/linux/mempolicy.h:104
Inline: True
Inline callers:
  - mm/mempolicy.c:mbind_range
  - mm/mempolicy.c:mbind_range
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
In mm/mmap.c (ffffffff812a38ec)
Location: include/linux/mempolicy.h:104
Inline: True
Inline callers:
  - mm/mmap.c:anon_vma_compatible
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
```
```
In mm/mempolicy.c (ffffffff812db653)
Location: include/linux/mempolicy.h:104
Inline: True
Inline callers:
  - mm/mempolicy.c:mbind_range
  - mm/mempolicy.c:mbind_range
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
In mm/mmap.c (ffffffff812a911c)
Location: include/linux/mempolicy.h:104
Inline: True
Inline callers:
  - mm/mmap.c:anon_vma_compatible
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
```
```
In mm/mempolicy.c (ffffffff812e2dd6)
Location: include/linux/mempolicy.h:104
Inline: True
Inline callers:
  - mm/mempolicy.c:mbind_range
  - mm/mempolicy.c:mbind_range
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
In mm/mmap.c (ffffffff812ea77c)
Location: include/linux/mempolicy.h:101
Inline: True
Inline callers:
  - mm/mmap.c:anon_vma_compatible
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
```
```
In mm/mempolicy.c (ffffffff8132a136)
Location: include/linux/mempolicy.h:101
Inline: True
Inline callers:
  - mm/mempolicy.c:mbind_range
  - mm/mempolicy.c:mbind_range
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8134d3f4)
Location: include/linux/mempolicy.h:101
Inline: True
Inline callers:
  - mm/mmap.c:anon_vma_compatible
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
```
```
In mm/mempolicy.c (ffffffff81399852)
Location: include/linux/mempolicy.h:101
Inline: True
Inline callers:
  - mm/mempolicy.c:mbind_range
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff813c866f)
Location: include/linux/mempolicy.h:101
Inline: True
Inline callers:
  - mm/mmap.c:find_mergeable_anon_vma
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
```
```
In mm/mempolicy.c (ffffffff81419897)
Location: include/linux/mempolicy.h:101
Inline: True
Inline callers:
  - mm/mempolicy.c:mbind_range
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff813fc853)
Location: include/linux/mempolicy.h:101
Inline: True
Inline callers:
  - mm/mmap.c:find_mergeable_anon_vma
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
```
```
In mm/mempolicy.c (ffffffff8144ccb0)
Location: include/linux/mempolicy.h:101
Inline: True
Inline callers:
  - mm/mempolicy.c:mbind_range
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8142922a)
Location: include/linux/mempolicy.h:101
Inline: True
Inline callers:
  - mm/mmap.c:find_mergeable_anon_vma
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
```
```
In mm/mempolicy.c (ffffffff814865b0)
Location: include/linux/mempolicy.h:101
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
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffff8000102ff360)
Location: include/linux/mempolicy.h:104
Inline: True
Inline callers:
  - mm/mmap.c:anon_vma_compatible
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
```
```
In mm/mempolicy.c (ffff80001033b138)
Location: include/linux/mempolicy.h:104
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:kernel_mbind
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
In mm/mmap.c (0)
Location: include/linux/mempolicy.h:212
Inline: True
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
In mm/mmap.c (c0000000003caf8c)
Location: include/linux/mempolicy.h:104
Inline: True
Inline callers:
  - mm/mmap.c:anon_vma_compatible
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
```
```
In mm/mempolicy.c (c000000000415b80)
Location: include/linux/mempolicy.h:104
Inline: True
Inline callers:
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_mbind
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
In mm/mmap.c (0)
Location: include/linux/mempolicy.h:212
Inline: True
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
In mm/mmap.c (ffffffff81260705)
Location: include/linux/mempolicy.h:104
Inline: True
Inline callers:
  - mm/mmap.c:anon_vma_compatible
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
```
```
In mm/mempolicy.c (ffffffff81294716)
Location: include/linux/mempolicy.h:104
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:kernel_mbind
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
In mm/mmap.c (ffffffff81252b25)
Location: include/linux/mempolicy.h:104
Inline: True
Inline callers:
  - mm/mmap.c:anon_vma_compatible
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
```
```
In mm/mempolicy.c (ffffffff81286326)
Location: include/linux/mempolicy.h:104
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:kernel_mbind
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
In mm/mmap.c (ffffffff8125e4a5)
Location: include/linux/mempolicy.h:104
Inline: True
Inline callers:
  - mm/mmap.c:anon_vma_compatible
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
```
```
In mm/mempolicy.c (ffffffff81292526)
Location: include/linux/mempolicy.h:104
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:kernel_mbind
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
In mm/mmap.c (ffffffff8126def5)
Location: include/linux/mempolicy.h:104
Inline: True
Inline callers:
  - mm/mmap.c:anon_vma_compatible
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
```
```
In mm/mempolicy.c (ffffffff812a2387)
Location: include/linux/mempolicy.h:104
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:kernel_mbind
```
</details>
</li>
</ul>

## Differences
