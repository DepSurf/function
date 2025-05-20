# Function: <code>check_stable_address_space</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811f5ed1)
Location: include/linux/oom.h:81
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:finish_fault
```
```
In mm/huge_memory.c (ffffffff81232a2d)
Location: include/linux/oom.h:81
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
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
In mm/memory.c (ffffffff8120d9c5)
Location: include/linux/oom.h:91
Inline: True
Inline callers:
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:finish_fault
```
```
In mm/huge_memory.c (ffffffff812500d3)
Location: include/linux/oom.h:91
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
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
In mm/memory.c (ffffffff8122e56e)
Location: include/linux/oom.h:91
Inline: True
Inline callers:
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:finish_fault
```
```
In mm/huge_memory.c (ffffffff812746a2)
Location: include/linux/oom.h:91
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
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
In mm/memory.c (ffffffff812423cc)
Location: include/linux/oom.h:101
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:finish_fault
```
```
In mm/huge_memory.c (ffffffff812896d6)
Location: include/linux/oom.h:101
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
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
In mm/memory.c (ffffffff81253a0a)
Location: include/linux/oom.h:101
Inline: True
Inline callers:
  - mm/memory.c:finish_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
```
```
In mm/huge_memory.c (ffffffff812a3fee)
Location: include/linux/oom.h:101
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
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
In mm/memory.c (ffffffff81261f6a)
Location: include/linux/oom.h:101
Inline: True
Inline callers:
  - mm/memory.c:finish_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
```
```
In mm/huge_memory.c (ffffffff812b573f)
Location: include/linux/oom.h:101
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
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
In mm/memory.c (ffffffff81291d9a)
Location: include/linux/oom.h:101
Inline: True
Inline callers:
  - mm/memory.c:finish_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
```
```
In mm/migrate.c (ffffffff812e530b)
Location: include/linux/oom.h:101
Inline: True
```
```
In mm/huge_memory.c (ffffffff812eaa04)
Location: include/linux/oom.h:101
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
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
In mm/memory.c (ffffffff8129c65a)
Location: include/linux/oom.h:102
Inline: True
Inline callers:
  - mm/memory.c:finish_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
```
```
In mm/migrate.c (ffffffff812f06d3)
Location: include/linux/oom.h:102
Inline: True
```
```
In mm/huge_memory.c (ffffffff812f5e93)
Location: include/linux/oom.h:102
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
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
In mm/memory.c (ffffffff812a1ab6)
Location: include/linux/oom.h:102
Inline: True
Inline callers:
  - mm/memory.c:finish_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
```
```
In mm/migrate.c (ffffffff812f6a9c)
Location: include/linux/oom.h:102
Inline: True
```
```
In mm/huge_memory.c (ffffffff812fc276)
Location: include/linux/oom.h:102
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
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
In mm/memory.c (ffffffff812e2a86)
Location: include/linux/oom.h:102
Inline: True
Inline callers:
  - mm/memory.c:finish_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
```
```
In mm/migrate.c (ffffffff813410f8)
Location: include/linux/oom.h:102
Inline: True
```
```
In mm/huge_memory.c (ffffffff813460d5)
Location: include/linux/oom.h:102
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
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
In mm/memory.c (ffffffff813433d8)
Location: include/linux/oom.h:102
Inline: True
Inline callers:
  - mm/memory.c:finish_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
```
```
In mm/migrate_device.c (ffffffff813b7f0f)
Location: include/linux/oom.h:102
Inline: True
```
```
In mm/huge_memory.c (ffffffff813bc2a3)
Location: include/linux/oom.h:102
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
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
In mm/memory.c (ffffffff813bb418)
Location: include/linux/oom.h:93
Inline: True
Inline callers:
  - mm/memory.c:finish_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
```
```
In mm/migrate_device.c (ffffffff81439bef)
Location: include/linux/oom.h:93
Inline: True
```
```
In mm/huge_memory.c (ffffffff8143e84a)
Location: include/linux/oom.h:93
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
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
In mm/memory.c (ffffffff813eff48)
Location: include/linux/oom.h:93
Inline: True
Inline callers:
  - mm/memory.c:finish_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
```
```
In mm/migrate_device.c (ffffffff8146e891)
Location: include/linux/oom.h:93
Inline: True
```
```
In mm/huge_memory.c (ffffffff8147402d)
Location: include/linux/oom.h:93
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
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
In mm/memory.c (ffffffff8141b5a8)
Location: include/linux/oom.h:93
Inline: True
Inline callers:
  - mm/memory.c:finish_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
```
```
In mm/migrate_device.c (ffffffff8149d2fe)
Location: include/linux/oom.h:93
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_insert_page
```
```
In mm/huge_memory.c (ffffffff814a351f)
Location: include/linux/oom.h:93
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
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
In mm/memory.c (ffff8000102f9230)
Location: include/linux/oom.h:101
Inline: True
Inline callers:
  - mm/memory.c:finish_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
```
```
In mm/huge_memory.c (ffff800010356a5c)
Location: include/linux/oom.h:101
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
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
In mm/memory.c (c0517d9c)
Location: include/linux/oom.h:101
Inline: True
Inline callers:
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
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
In mm/memory.c (c0000000003c2d94)
Location: include/linux/oom.h:101
Inline: True
Inline callers:
  - mm/memory.c:finish_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
```
```
In mm/huge_memory.c (c00000000043e094)
Location: include/linux/oom.h:101
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
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
In mm/memory.c (ffffffe000207024)
Location: include/linux/oom.h:101
Inline: True
Inline callers:
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
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
In mm/memory.c (ffffffff8125a5ba)
Location: include/linux/oom.h:101
Inline: True
Inline callers:
  - mm/memory.c:finish_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
```
```
In mm/huge_memory.c (ffffffff812add1f)
Location: include/linux/oom.h:101
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
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
In mm/memory.c (ffffffff8124c9da)
Location: include/linux/oom.h:101
Inline: True
Inline callers:
  - mm/memory.c:finish_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
```
```
In mm/huge_memory.c (ffffffff8129f376)
Location: include/linux/oom.h:101
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
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
In mm/memory.c (ffffffff8125835a)
Location: include/linux/oom.h:101
Inline: True
Inline callers:
  - mm/memory.c:finish_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
```
```
In mm/huge_memory.c (ffffffff812abb2f)
Location: include/linux/oom.h:101
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
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
In mm/memory.c (ffffffff81267d3c)
Location: include/linux/oom.h:101
Inline: True
Inline callers:
  - mm/memory.c:finish_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
```
```
In mm/huge_memory.c (ffffffff812bbe9c)
Location: include/linux/oom.h:101
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
</details>
</li>
</ul>

## Differences
