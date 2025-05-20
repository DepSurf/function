# Function: <code>prandom_seed_state</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/kaslr.c (ffffffff81fa1e4d)
Location: include/linux/random.h:85
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
```
```
In mm/slab_common.c (ffffffff811cdc84)
Location: include/linux/random.h:85
Inline: True
Inline callers:
  - mm/slab_common.c:cache_random_seq_create
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
In arch/x86/mm/kaslr.c (ffffffff81fdd48c)
Location: include/linux/random.h:96
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
```
```
In mm/slab_common.c (ffffffff811dddd4)
Location: include/linux/random.h:96
Inline: True
Inline callers:
  - mm/slab_common.c:cache_random_seq_create
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
In arch/x86/mm/kaslr.c (ffffffff820be4c0)
Location: include/linux/random.h:155
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
```
```
In mm/slab_common.c (ffffffff811e7aac)
Location: include/linux/random.h:155
Inline: True
Inline callers:
  - mm/slab_common.c:cache_random_seq_create
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
In arch/x86/mm/kaslr.c (ffffffff826c5300)
Location: include/linux/random.h:156
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
```
```
In mm/slab_common.c (ffffffff811fdcec)
Location: include/linux/random.h:156
Inline: True
Inline callers:
  - mm/slab_common.c:cache_random_seq_create
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
In arch/x86/mm/kaslr.c (ffffffff826ef59e)
Location: include/linux/random.h:154
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
```
```
In mm/slab_common.c (ffffffff8121f022)
Location: include/linux/random.h:154
Inline: True
Inline callers:
  - mm/slab_common.c:cache_random_seq_create
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
In arch/x86/mm/kaslr.c (ffffffff828a628c)
Location: include/linux/random.h:155
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
```
```
In mm/slab_common.c (ffffffff81232012)
Location: include/linux/random.h:155
Inline: True
Inline callers:
  - mm/slab_common.c:cache_random_seq_create
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
In arch/x86/mm/kaslr.c (ffffffff828be8ac)
Location: include/linux/random.h:156
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
```
```
In mm/slab_common.c (ffffffff812424e8)
Location: include/linux/random.h:156
Inline: True
Inline callers:
  - mm/slab_common.c:cache_random_seq_create
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
In arch/x86/mm/kaslr.c (ffffffff828c4d4e)
Location: include/linux/random.h:157
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
```
```
In mm/slab_common.c (ffffffff81250a08)
Location: include/linux/random.h:157
Inline: True
Inline callers:
  - mm/slab_common.c:cache_random_seq_create
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
In arch/x86/mm/kaslr.c (ffffffff82ce7f94)
Location: include/linux/prandom.h:62
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
```
```
In mm/slab_common.c (ffffffff8127f081)
Location: include/linux/prandom.h:62
Inline: True
Inline callers:
  - mm/slab_common.c:cache_random_seq_create
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
In arch/x86/mm/kaslr.c (ffffffff82fd598b)
Location: include/linux/prandom.h:112
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
```
```
In mm/slab_common.c (ffffffff81288e19)
Location: include/linux/prandom.h:112
Inline: True
Inline callers:
  - mm/slab_common.c:cache_random_seq_create
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
In arch/x86/mm/kaslr.c (ffffffff831e0427)
Location: include/linux/prandom.h:112
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
```
```
In mm/slab_common.c (ffffffff8128e4d9)
Location: include/linux/prandom.h:112
Inline: True
Inline callers:
  - mm/slab_common.c:cache_random_seq_create
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
In arch/x86/mm/kaslr.c (ffffffff832c3ac0)
Location: include/linux/prandom.h:112
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
```
```
In mm/slab_common.c (ffffffff812ce419)
Location: include/linux/prandom.h:112
Inline: True
Inline callers:
  - mm/slab_common.c:cache_random_seq_create
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
In arch/x86/mm/kaslr.c (ffffffff834763b5)
Location: include/linux/prandom.h:66
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
```
```
In mm/slab_common.c (ffffffff8132c4d9)
Location: include/linux/prandom.h:66
Inline: True
Inline callers:
  - mm/slab_common.c:cache_random_seq_create
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
In arch/x86/mm/kaslr.c (ffffffff83e9f2ef)
Location: include/linux/prandom.h:40
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
```
```
In mm/slab_common.c (ffffffff813a2879)
Location: include/linux/prandom.h:40
Inline: True
Inline callers:
  - mm/slab_common.c:cache_random_seq_create
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
In arch/x86/mm/kaslr.c (ffffffff836c346f)
Location: include/linux/prandom.h:40
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
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
In arch/x86/mm/kaslr.c (ffffffff838f404f)
Location: include/linux/prandom.h:39
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
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
In mm/slab_common.c (ffff8000102e7b38)
Location: include/linux/random.h:157
Inline: True
Inline callers:
  - mm/slab_common.c:cache_random_seq_create
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
In mm/slab_common.c (c050bc3c)
Location: include/linux/random.h:157
Inline: True
Inline callers:
  - mm/slab_common.c:cache_random_seq_create
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
In mm/slab_common.c (c0000000003a99bc)
Location: include/linux/random.h:157
Inline: True
Inline callers:
  - mm/slab_common.c:cache_random_seq_create
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
In mm/slab_common.c (ffffffe0001fd646)
Location: include/linux/random.h:157
Inline: True
Inline callers:
  - mm/slab_common.c:cache_random_seq_create
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
In arch/x86/mm/kaslr.c (ffffffff828afce6)
Location: include/linux/random.h:157
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
```
```
In mm/slab_common.c (ffffffff81249058)
Location: include/linux/random.h:157
Inline: True
Inline callers:
  - mm/slab_common.c:cache_random_seq_create
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
In arch/x86/mm/kaslr.c (ffffffff828a7ed8)
Location: include/linux/random.h:157
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
```
```
In mm/slab_common.c (ffffffff8123c008)
Location: include/linux/random.h:157
Inline: True
Inline callers:
  - mm/slab_common.c:cache_random_seq_create
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
In arch/x86/mm/kaslr.c (ffffffff828c2be5)
Location: include/linux/random.h:157
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
```
```
In mm/slab_common.c (ffffffff81246df8)
Location: include/linux/random.h:157
Inline: True
Inline callers:
  - mm/slab_common.c:cache_random_seq_create
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
In arch/x86/mm/kaslr.c (ffffffff828c5d6e)
Location: include/linux/random.h:157
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
```
```
In mm/slab_common.c (ffffffff81256628)
Location: include/linux/random.h:157
Inline: True
Inline callers:
  - mm/slab_common.c:cache_random_seq_create
```
</details>
</li>
</ul>

## Differences
