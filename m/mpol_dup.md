# Function: <code>mpol_dup</code>

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
In kernel/fork.c (ffffffff8107eb87)
Location: include/linux/mempolicy.h:86
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In mm/mempolicy.c (ffffffff811e2404)
Location: include/linux/mempolicy.h:86
Inline: True
Inline callers:
  - mm/mempolicy.c:vma_dup_policy
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:mpol_set_shared_policy
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
In kernel/fork.c (ffffffff8108084b)
Location: include/linux/mempolicy.h:86
Inline: True
```
```
In mm/mempolicy.c (ffffffff81201897)
Location: include/linux/mempolicy.h:86
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:vma_dup_policy
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
In kernel/fork.c (ffffffff81085116)
Location: include/linux/mempolicy.h:87
Inline: True
```
```
In mm/mempolicy.c (ffffffff81213387)
Location: include/linux/mempolicy.h:87
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:vma_dup_policy
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
In kernel/fork.c (ffffffff81082048)
Location: include/linux/mempolicy.h:87
Inline: True
```
```
In mm/mempolicy.c (ffffffff8121e6a8)
Location: include/linux/mempolicy.h:87
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:vma_dup_policy
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
In kernel/fork.c (ffffffff810888b3)
Location: include/linux/mempolicy.h:88
Inline: True
```
```
In mm/mempolicy.c (ffffffff812398c8)
Location: include/linux/mempolicy.h:88
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:vma_dup_policy
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
In kernel/fork.c (ffffffff8108c61c)
Location: include/linux/mempolicy.h:88
Inline: True
```
```
In mm/mempolicy.c (ffffffff8125ce84)
Location: include/linux/mempolicy.h:88
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:vma_dup_policy
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
In kernel/fork.c (ffffffff81094036)
Location: include/linux/mempolicy.h:88
Inline: True
```
```
In mm/mempolicy.c (ffffffff8127175c)
Location: include/linux/mempolicy.h:88
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:vma_dup_policy
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
In kernel/fork.c (ffffffff810987d0)
Location: include/linux/mempolicy.h:88
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In mm/mempolicy.c (ffffffff8128cd78)
Location: include/linux/mempolicy.h:88
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:vma_dup_policy
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
In kernel/fork.c (ffffffff8109ed8b)
Location: include/linux/mempolicy.h:88
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In mm/mempolicy.c (ffffffff8129c9a8)
Location: include/linux/mempolicy.h:88
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:vma_dup_policy
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
In kernel/fork.c (ffffffff810a63b8)
Location: include/linux/mempolicy.h:88
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In mm/mempolicy.c (ffffffff812d0669)
Location: include/linux/mempolicy.h:88
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:vma_dup_policy
  - mm/mempolicy.c:vma_replace_policy
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
In kernel/fork.c (ffffffff810a1cd1)
Location: include/linux/mempolicy.h:88
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In mm/mempolicy.c (ffffffff812dc189)
Location: include/linux/mempolicy.h:88
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:vma_dup_policy
  - mm/mempolicy.c:vma_replace_policy
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
In kernel/fork.c (ffffffff810a2b2a)
Location: include/linux/mempolicy.h:88
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In mm/mempolicy.c (ffffffff812e3a29)
Location: include/linux/mempolicy.h:88
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:vma_dup_policy
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
In kernel/fork.c (ffffffff810b424f)
Location: include/linux/mempolicy.h:85
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In mm/mempolicy.c (ffffffff8132ad09)
Location: include/linux/mempolicy.h:85
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:vma_dup_policy
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
In kernel/fork.c (ffffffff810ca5bf)
Location: include/linux/mempolicy.h:85
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In mm/mempolicy.c (ffffffff8139a6d6)
Location: include/linux/mempolicy.h:85
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:vma_dup_policy
  - mm/mempolicy.c:__do_sys_set_mempolicy_home_node
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
In kernel/fork.c (ffffffff810e7c28)
Location: include/linux/mempolicy.h:85
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In mm/mempolicy.c (ffffffff8141a713)
Location: include/linux/mempolicy.h:85
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:vma_dup_policy
  - mm/mempolicy.c:__do_sys_set_mempolicy_home_node
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
In kernel/fork.c (ffffffff810f3846)
Location: include/linux/mempolicy.h:85
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In mm/mempolicy.c (ffffffff8144dc86)
Location: include/linux/mempolicy.h:85
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:vma_dup_policy
  - mm/mempolicy.c:__do_sys_set_mempolicy_home_node
  - mm/mempolicy.c:vma_replace_policy
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
In kernel/fork.c (ffffffff810fcc17)
Location: include/linux/mempolicy.h:87
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In mm/mempolicy.c (ffffffff81486407)
Location: include/linux/mempolicy.h:87
Inline: True
Inline callers:
  - mm/mempolicy.c:sp_alloc
  - mm/mempolicy.c:vma_dup_policy
  - mm/mempolicy.c:__do_sys_set_mempolicy_home_node
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
In kernel/fork.c (ffff8000100f38ac)
Location: include/linux/mempolicy.h:88
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In mm/mempolicy.c (ffff80001033b96c)
Location: include/linux/mempolicy.h:88
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:vma_dup_policy
  - mm/mempolicy.c:kernel_mbind
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (c00000000013967c)
Location: include/linux/mempolicy.h:88
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In mm/mempolicy.c (c0000000004167bc)
Location: include/linux/mempolicy.h:88
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:vma_dup_policy
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
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810986ab)
Location: include/linux/mempolicy.h:88
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In mm/mempolicy.c (ffffffff81294f88)
Location: include/linux/mempolicy.h:88
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:vma_dup_policy
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
In kernel/fork.c (ffffffff81087115)
Location: include/linux/mempolicy.h:88
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In mm/mempolicy.c (ffffffff81286b98)
Location: include/linux/mempolicy.h:88
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:vma_dup_policy
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
In kernel/fork.c (ffffffff8109865b)
Location: include/linux/mempolicy.h:88
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In mm/mempolicy.c (ffffffff81292d98)
Location: include/linux/mempolicy.h:88
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:vma_dup_policy
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
In kernel/fork.c (ffffffff810a0282)
Location: include/linux/mempolicy.h:88
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In mm/mempolicy.c (ffffffff812a2b88)
Location: include/linux/mempolicy.h:88
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:vma_dup_policy
  - mm/mempolicy.c:kernel_mbind
```
</details>
</li>
</ul>

## Differences
