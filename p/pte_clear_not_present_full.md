# Function: <code>pte_clear_not_present_full</code>

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
In mm/memory.c (ffffffff811bd8d8)
Location: include/asm-generic/pgtable.h:163
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
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
In mm/memory.c (ffffffff811d8fd2)
Location: include/asm-generic/pgtable.h:165
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
```
```
In mm/madvise.c (ffffffff811eef3b)
Location: include/asm-generic/pgtable.h:165
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
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
In mm/memory.c (ffffffff811e8466)
Location: include/asm-generic/pgtable.h:165
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
```
```
In mm/madvise.c (ffffffff811ff89d)
Location: include/asm-generic/pgtable.h:165
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
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
In mm/memory.c (ffffffff811f367a)
Location: include/asm-generic/pgtable.h:195
Inline: True
```
```
In mm/madvise.c (ffffffff8120a52a)
Location: include/asm-generic/pgtable.h:195
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
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
In mm/memory.c (ffffffff8120b299)
Location: include/asm-generic/pgtable.h:196
Inline: True
```
```
In mm/madvise.c (ffffffff81223781)
Location: include/asm-generic/pgtable.h:196
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
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
In mm/memory.c (ffffffff8122c07a)
Location: include/asm-generic/pgtable.h:196
Inline: True
```
```
In mm/madvise.c (ffffffff8124658c)
Location: include/asm-generic/pgtable.h:196
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
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
In mm/memory.c (ffffffff8123f489)
Location: include/asm-generic/pgtable.h:196
Inline: True
```
```
In mm/madvise.c (ffffffff8125a9af)
Location: include/asm-generic/pgtable.h:196
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
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
In mm/memory.c (ffffffff81250dca)
Location: include/asm-generic/pgtable.h:196
Inline: True
```
```
In mm/madvise.c (ffffffff81275af9)
Location: include/asm-generic/pgtable.h:196
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
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
In mm/memory.c (ffffffff8125f3e6)
Location: include/asm-generic/pgtable.h:196
Inline: True
```
```
In mm/madvise.c (ffffffff81284ac9)
Location: include/asm-generic/pgtable.h:196
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
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
In mm/memory.c (ffffffff8128f92e)
Location: include/linux/pgtable.h:339
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
```
```
In mm/madvise.c (ffffffff812b6cb8)
Location: include/linux/pgtable.h:339
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
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
In mm/memory.c (ffffffff8129a37d)
Location: include/linux/pgtable.h:394
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
```
```
In mm/madvise.c (ffffffff812c2e72)
Location: include/linux/pgtable.h:394
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
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
In mm/memory.c (ffffffff8129f5a0)
Location: include/linux/pgtable.h:394
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
```
```
In mm/madvise.c (ffffffff812c9cef)
Location: include/linux/pgtable.h:394
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
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
In mm/memory.c (ffffffff812e071e)
Location: include/linux/pgtable.h:413
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
```
```
In mm/madvise.c (ffffffff8130ed0f)
Location: include/linux/pgtable.h:413
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
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
In mm/memory.c (ffffffff81340e84)
Location: include/linux/pgtable.h:426
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
```
```
In mm/madvise.c (ffffffff81376a02)
Location: include/linux/pgtable.h:426
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
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
In mm/memory.c (ffffffff813b8d8a)
Location: include/linux/pgtable.h:486
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
```
```
In mm/madvise.c (ffffffff813f42f6)
Location: include/linux/pgtable.h:486
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
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
In mm/memory.c (ffffffff813ed982)
Location: include/linux/pgtable.h:494
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
```
```
In mm/madvise.c (ffffffff81427b0b)
Location: include/linux/pgtable.h:494
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
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
In mm/memory.c (ffffffff8141901f)
Location: include/linux/pgtable.h:606
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
```
```
In mm/madvise.c (ffffffff8146131b)
Location: include/linux/pgtable.h:606
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
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
In mm/memory.c (ffff8000102f6dcc)
Location: include/asm-generic/pgtable.h:196
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
```
```
In mm/madvise.c (ffff80001031edac)
Location: include/asm-generic/pgtable.h:196
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (c0518e50)
Location: include/asm-generic/pgtable.h:196
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
```
```
In mm/madvise.c (c053796c)
Location: include/asm-generic/pgtable.h:196
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
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
In mm/memory.c (c0000000003bed58)
Location: include/asm-generic/pgtable.h:196
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
```
```
In mm/madvise.c (c0000000003f32c0)
Location: include/asm-generic/pgtable.h:196
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffe00020766e)
Location: include/asm-generic/pgtable.h:196
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
```
```
In mm/madvise.c (ffffffe00022071e)
Location: include/asm-generic/pgtable.h:196
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
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
In mm/memory.c (ffffffff81257a36)
Location: include/asm-generic/pgtable.h:196
Inline: True
```
```
In mm/madvise.c (ffffffff8127d119)
Location: include/asm-generic/pgtable.h:196
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
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
In mm/memory.c (ffffffff8124a385)
Location: include/asm-generic/pgtable.h:196
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
```
```
In mm/madvise.c (ffffffff8126ee08)
Location: include/asm-generic/pgtable.h:196
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
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
In mm/memory.c (ffffffff812557d6)
Location: include/asm-generic/pgtable.h:196
Inline: True
```
```
In mm/madvise.c (ffffffff8127aeb9)
Location: include/asm-generic/pgtable.h:196
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
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
In mm/memory.c (ffffffff8126528d)
Location: include/asm-generic/pgtable.h:196
Inline: True
```
```
In mm/madvise.c (ffffffff8128aa85)
Location: include/asm-generic/pgtable.h:196
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
</details>
</li>
</ul>

## Differences
