# Function: <code>__seed</code>

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
In lib/random32.c (ffffffff813f89c4)
Location: include/linux/random.h:75
Inline: True
Inline callers:
  - lib/random32.c:prandom_seed
  - lib/random32.c:prandom_init
  - lib/random32.c:prandom_init
  - lib/random32.c:prandom_init
  - lib/random32.c:prandom_init
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_seed_full_state
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
In arch/x86/mm/kaslr.c (ffffffff81fa1e65)
Location: include/linux/random.h:75
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
```
```
In mm/slab_common.c (ffffffff811cdc94)
Location: include/linux/random.h:75
Inline: True
Inline callers:
  - mm/slab_common.c:cache_random_seq_create
  - mm/slab_common.c:cache_random_seq_create
  - mm/slab_common.c:cache_random_seq_create
  - mm/slab_common.c:cache_random_seq_create
```
```
In lib/random32.c (ffffffff8143f8c7)
Location: include/linux/random.h:75
Inline: True
Inline callers:
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_init
  - lib/random32.c:prandom_init
  - lib/random32.c:prandom_init
  - lib/random32.c:prandom_init
  - lib/random32.c:prandom_seed
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
In arch/x86/mm/kaslr.c (ffffffff81fdd4d4)
Location: include/linux/random.h:86
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
```
```
In mm/slab_common.c (ffffffff811ddde4)
Location: include/linux/random.h:86
Inline: True
Inline callers:
  - mm/slab_common.c:cache_random_seq_create
  - mm/slab_common.c:cache_random_seq_create
  - mm/slab_common.c:cache_random_seq_create
  - mm/slab_common.c:cache_random_seq_create
```
```
In lib/random32.c (ffffffff8145c9c7)
Location: include/linux/random.h:86
Inline: True
Inline callers:
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_init
  - lib/random32.c:prandom_init
  - lib/random32.c:prandom_init
  - lib/random32.c:prandom_init
  - lib/random32.c:prandom_seed
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
In arch/x86/mm/kaslr.c (ffffffff820be4d0)
Location: include/linux/random.h:145
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
```
```
In mm/slab_common.c (ffffffff811e7abc)
Location: include/linux/random.h:145
Inline: True
Inline callers:
  - mm/slab_common.c:cache_random_seq_create
  - mm/slab_common.c:cache_random_seq_create
  - mm/slab_common.c:cache_random_seq_create
  - mm/slab_common.c:cache_random_seq_create
```
```
In lib/random32.c (ffffffff81461bd7)
Location: include/linux/random.h:145
Inline: True
Inline callers:
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_init
  - lib/random32.c:prandom_init
  - lib/random32.c:prandom_init
  - lib/random32.c:prandom_init
  - lib/random32.c:prandom_seed
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
In arch/x86/mm/kaslr.c (ffffffff826c5310)
Location: include/linux/random.h:146
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
```
```
In mm/slab_common.c (ffffffff811fdcfc)
Location: include/linux/random.h:146
Inline: True
Inline callers:
  - mm/slab_common.c:cache_random_seq_create
  - mm/slab_common.c:cache_random_seq_create
  - mm/slab_common.c:cache_random_seq_create
  - mm/slab_common.c:cache_random_seq_create
```
```
In lib/random32.c (ffffffff8148dac9)
Location: include/linux/random.h:146
Inline: True
Inline callers:
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_init
  - lib/random32.c:prandom_init
  - lib/random32.c:prandom_init
  - lib/random32.c:prandom_init
  - lib/random32.c:prandom_seed
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
In arch/x86/mm/kaslr.c (ffffffff826ef5ae)
Location: include/linux/random.h:144
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
```
```
In mm/slab_common.c (ffffffff8121f032)
Location: include/linux/random.h:144
Inline: True
Inline callers:
  - mm/slab_common.c:cache_random_seq_create
  - mm/slab_common.c:cache_random_seq_create
  - mm/slab_common.c:cache_random_seq_create
  - mm/slab_common.c:cache_random_seq_create
```
```
In lib/random32.c (ffffffff814c2856)
Location: include/linux/random.h:144
Inline: True
Inline callers:
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_init
  - lib/random32.c:prandom_init
  - lib/random32.c:prandom_init
  - lib/random32.c:prandom_init
  - lib/random32.c:prandom_seed
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
In arch/x86/mm/kaslr.c (ffffffff828a629c)
Location: include/linux/random.h:145
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
```
```
In mm/slab_common.c (ffffffff81232022)
Location: include/linux/random.h:145
Inline: True
Inline callers:
  - mm/slab_common.c:cache_random_seq_create
  - mm/slab_common.c:cache_random_seq_create
  - mm/slab_common.c:cache_random_seq_create
  - mm/slab_common.c:cache_random_seq_create
```
```
In lib/random32.c (ffffffff814d6f06)
Location: include/linux/random.h:145
Inline: True
Inline callers:
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_init
  - lib/random32.c:prandom_init
  - lib/random32.c:prandom_init
  - lib/random32.c:prandom_init
  - lib/random32.c:prandom_seed
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
In arch/x86/mm/kaslr.c (ffffffff828be8b7)
Location: include/linux/random.h:146
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
```
```
In mm/slab_common.c (ffffffff812424f3)
Location: include/linux/random.h:146
Inline: True
Inline callers:
  - mm/slab_common.c:cache_random_seq_create
  - mm/slab_common.c:cache_random_seq_create
  - mm/slab_common.c:cache_random_seq_create
  - mm/slab_common.c:cache_random_seq_create
```
```
In lib/random32.c (ffffffff81502d66)
Location: include/linux/random.h:146
Inline: True
Inline callers:
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_init
  - lib/random32.c:prandom_init
  - lib/random32.c:prandom_init
  - lib/random32.c:prandom_init
  - lib/random32.c:prandom_seed
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
In arch/x86/mm/kaslr.c (ffffffff828c4d59)
Location: include/linux/random.h:147
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
```
```
In mm/slab_common.c (ffffffff81250a13)
Location: include/linux/random.h:147
Inline: True
Inline callers:
  - mm/slab_common.c:cache_random_seq_create
  - mm/slab_common.c:cache_random_seq_create
  - mm/slab_common.c:cache_random_seq_create
  - mm/slab_common.c:cache_random_seq_create
```
```
In lib/random32.c (ffffffff81520d06)
Location: include/linux/random.h:147
Inline: True
Inline callers:
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_init
  - lib/random32.c:prandom_init
  - lib/random32.c:prandom_init
  - lib/random32.c:prandom_init
  - lib/random32.c:prandom_seed
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
In arch/x86/mm/kaslr.c (ffffffff82ce7fa4)
Location: include/linux/prandom.h:52
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
```
```
In mm/slab_common.c (ffffffff8127f08c)
Location: include/linux/prandom.h:52
Inline: True
Inline callers:
  - mm/slab_common.c:cache_random_seq_create
  - mm/slab_common.c:cache_random_seq_create
  - mm/slab_common.c:cache_random_seq_create
  - mm/slab_common.c:cache_random_seq_create
```
```
In lib/random32.c (ffffffff81583d76)
Location: include/linux/prandom.h:52
Inline: True
Inline callers:
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_init
  - lib/random32.c:prandom_init
  - lib/random32.c:prandom_init
  - lib/random32.c:prandom_init
  - lib/random32.c:prandom_seed
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
In arch/x86/mm/kaslr.c (ffffffff82fd599b)
Location: include/linux/prandom.h:102
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
```
```
In mm/slab_common.c (ffffffff81288e24)
Location: include/linux/prandom.h:102
Inline: True
Inline callers:
  - mm/slab_common.c:cache_random_seq_create
  - mm/slab_common.c:cache_random_seq_create
  - mm/slab_common.c:cache_random_seq_create
  - mm/slab_common.c:cache_random_seq_create
```
```
In lib/random32.c (ffffffff815a0b59)
Location: include/linux/prandom.h:102
Inline: True
Inline callers:
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_seed_full_state
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
In arch/x86/mm/kaslr.c (ffffffff831e0437)
Location: include/linux/prandom.h:102
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
```
```
In mm/slab_common.c (ffffffff8128e4e4)
Location: include/linux/prandom.h:102
Inline: True
Inline callers:
  - mm/slab_common.c:cache_random_seq_create
  - mm/slab_common.c:cache_random_seq_create
  - mm/slab_common.c:cache_random_seq_create
  - mm/slab_common.c:cache_random_seq_create
```
```
In lib/random32.c (ffffffff815a79e9)
Location: include/linux/prandom.h:102
Inline: True
Inline callers:
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_seed_full_state
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
In arch/x86/mm/kaslr.c (ffffffff832c3ad0)
Location: include/linux/prandom.h:102
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
```
```
In mm/slab_common.c (ffffffff812ce424)
Location: include/linux/prandom.h:102
Inline: True
Inline callers:
  - mm/slab_common.c:cache_random_seq_create
  - mm/slab_common.c:cache_random_seq_create
  - mm/slab_common.c:cache_random_seq_create
  - mm/slab_common.c:cache_random_seq_create
```
```
In lib/random32.c (ffffffff81610939)
Location: include/linux/prandom.h:102
Inline: True
Inline callers:
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_seed_full_state
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
In arch/x86/mm/kaslr.c (ffffffff834763c5)
Location: include/linux/prandom.h:56
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
```
```
In mm/slab_common.c (ffffffff8132c4e4)
Location: include/linux/prandom.h:56
Inline: True
Inline callers:
  - mm/slab_common.c:cache_random_seq_create
  - mm/slab_common.c:cache_random_seq_create
  - mm/slab_common.c:cache_random_seq_create
  - mm/slab_common.c:cache_random_seq_create
```
```
In lib/random32.c (ffffffff816dce49)
Location: include/linux/prandom.h:56
Inline: True
Inline callers:
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_seed_full_state
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
In arch/x86/mm/kaslr.c (ffffffff83e9f2fa)
Location: include/linux/prandom.h:30
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
```
```
In mm/slab_common.c (ffffffff813a2884)
Location: include/linux/prandom.h:30
Inline: True
Inline callers:
  - mm/slab_common.c:cache_random_seq_create
  - mm/slab_common.c:cache_random_seq_create
  - mm/slab_common.c:cache_random_seq_create
  - mm/slab_common.c:cache_random_seq_create
```
```
In lib/random32.c (ffffffff817ccc65)
Location: include/linux/prandom.h:30
Inline: True
Inline callers:
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_seed_full_state
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
In arch/x86/mm/kaslr.c (ffffffff836c347a)
Location: include/linux/prandom.h:30
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
```
```
In lib/random32.c (ffffffff8180b075)
Location: include/linux/prandom.h:30
Inline: True
Inline callers:
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_seed_full_state
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
In arch/x86/mm/kaslr.c (ffffffff838f405a)
Location: include/linux/prandom.h:29
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
```
```
In lib/random32.c (ffffffff81851855)
Location: include/linux/prandom.h:29
Inline: True
Inline callers:
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_seed_full_state
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
In mm/slab_common.c (ffff8000102e7b44)
Location: include/linux/random.h:147
Inline: True
Inline callers:
  - mm/slab_common.c:cache_random_seq_create
  - mm/slab_common.c:cache_random_seq_create
  - mm/slab_common.c:cache_random_seq_create
  - mm/slab_common.c:cache_random_seq_create
```
```
In lib/random32.c (ffff80001062a284)
Location: include/linux/random.h:147
Inline: True
Inline callers:
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_init
  - lib/random32.c:prandom_init
  - lib/random32.c:prandom_init
  - lib/random32.c:prandom_init
  - lib/random32.c:prandom_seed
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
In mm/slab_common.c (c050bc40)
Location: include/linux/random.h:147
Inline: True
Inline callers:
  - mm/slab_common.c:cache_random_seq_create
  - mm/slab_common.c:cache_random_seq_create
  - mm/slab_common.c:cache_random_seq_create
  - mm/slab_common.c:cache_random_seq_create
```
```
In lib/random32.c (c07d157c)
Location: include/linux/random.h:147
Inline: True
Inline callers:
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_init
  - lib/random32.c:prandom_init
  - lib/random32.c:prandom_init
  - lib/random32.c:prandom_init
  - lib/random32.c:prandom_seed
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
In mm/slab_common.c (c0000000003a99d4)
Location: include/linux/random.h:147
Inline: True
Inline callers:
  - mm/slab_common.c:cache_random_seq_create
  - mm/slab_common.c:cache_random_seq_create
  - mm/slab_common.c:cache_random_seq_create
  - mm/slab_common.c:cache_random_seq_create
```
```
In lib/random32.c (c0000000007cc21c)
Location: include/linux/random.h:147
Inline: True
Inline callers:
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_init
  - lib/random32.c:prandom_init
  - lib/random32.c:prandom_init
  - lib/random32.c:prandom_init
  - lib/random32.c:prandom_seed
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
In mm/slab_common.c (ffffffe0001fd656)
Location: include/linux/random.h:147
Inline: True
Inline callers:
  - mm/slab_common.c:cache_random_seq_create
  - mm/slab_common.c:cache_random_seq_create
  - mm/slab_common.c:cache_random_seq_create
  - mm/slab_common.c:cache_random_seq_create
```
```
In lib/random32.c (ffffffe00045ad86)
Location: include/linux/random.h:147
Inline: True
Inline callers:
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_init
  - lib/random32.c:prandom_init
  - lib/random32.c:prandom_init
  - lib/random32.c:prandom_init
  - lib/random32.c:prandom_seed
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
In arch/x86/mm/kaslr.c (ffffffff828afcf1)
Location: include/linux/random.h:147
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
```
```
In mm/slab_common.c (ffffffff81249063)
Location: include/linux/random.h:147
Inline: True
Inline callers:
  - mm/slab_common.c:cache_random_seq_create
  - mm/slab_common.c:cache_random_seq_create
  - mm/slab_common.c:cache_random_seq_create
  - mm/slab_common.c:cache_random_seq_create
```
```
In lib/random32.c (ffffffff815192e6)
Location: include/linux/random.h:147
Inline: True
Inline callers:
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_init
  - lib/random32.c:prandom_init
  - lib/random32.c:prandom_init
  - lib/random32.c:prandom_init
  - lib/random32.c:prandom_seed
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
In arch/x86/mm/kaslr.c (ffffffff828a7ee3)
Location: include/linux/random.h:147
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
```
```
In mm/slab_common.c (ffffffff8123c013)
Location: include/linux/random.h:147
Inline: True
Inline callers:
  - mm/slab_common.c:cache_random_seq_create
  - mm/slab_common.c:cache_random_seq_create
  - mm/slab_common.c:cache_random_seq_create
  - mm/slab_common.c:cache_random_seq_create
```
```
In lib/random32.c (ffffffff815095e6)
Location: include/linux/random.h:147
Inline: True
Inline callers:
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_init
  - lib/random32.c:prandom_init
  - lib/random32.c:prandom_init
  - lib/random32.c:prandom_init
  - lib/random32.c:prandom_seed
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
In arch/x86/mm/kaslr.c (ffffffff828c2bf0)
Location: include/linux/random.h:147
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
```
```
In mm/slab_common.c (ffffffff81246e03)
Location: include/linux/random.h:147
Inline: True
Inline callers:
  - mm/slab_common.c:cache_random_seq_create
  - mm/slab_common.c:cache_random_seq_create
  - mm/slab_common.c:cache_random_seq_create
  - mm/slab_common.c:cache_random_seq_create
```
```
In lib/random32.c (ffffffff81515376)
Location: include/linux/random.h:147
Inline: True
Inline callers:
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_init
  - lib/random32.c:prandom_init
  - lib/random32.c:prandom_init
  - lib/random32.c:prandom_init
  - lib/random32.c:prandom_seed
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
In arch/x86/mm/kaslr.c (ffffffff828c5d79)
Location: include/linux/random.h:147
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
```
```
In mm/slab_common.c (ffffffff81256633)
Location: include/linux/random.h:147
Inline: True
Inline callers:
  - mm/slab_common.c:cache_random_seq_create
  - mm/slab_common.c:cache_random_seq_create
  - mm/slab_common.c:cache_random_seq_create
  - mm/slab_common.c:cache_random_seq_create
```
```
In lib/random32.c (ffffffff8152eb16)
Location: include/linux/random.h:147
Inline: True
Inline callers:
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_init
  - lib/random32.c:prandom_init
  - lib/random32.c:prandom_init
  - lib/random32.c:prandom_init
  - lib/random32.c:prandom_seed
```
</details>
</li>
</ul>

## Differences
