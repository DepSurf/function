# Function: <code>arch_get_random_seed_long</code>

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
In drivers/char/random.c (ffffffff81513de7)
Location: arch/x86/include/asm/archrandom.h:104
Inline: True
Inline callers:
  - drivers/char/random.c:init_std_data
  - drivers/char/random.c:add_interrupt_randomness
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
In drivers/char/random.c (ffffffff8156610e)
Location: arch/x86/include/asm/archrandom.h:110
Inline: True
Inline callers:
  - drivers/char/random.c:init_std_data
  - drivers/char/random.c:add_interrupt_randomness
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:crng_initialize
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
In drivers/char/random.c (ffffffff8159286e)
Location: arch/x86/include/asm/archrandom.h:110
Inline: True
Inline callers:
  - drivers/char/random.c:init_std_data
  - drivers/char/random.c:add_interrupt_randomness
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:crng_initialize
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
In drivers/char/random.c (ffffffff815a6b0f)
Location: arch/x86/include/asm/archrandom.h:110
Inline: True
Inline callers:
  - drivers/char/random.c:init_std_data
  - drivers/char/random.c:add_interrupt_randomness
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:crng_initialize
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
In drivers/char/random.c (ffffffff8160d40f)
Location: arch/x86/include/asm/archrandom.h:110
Inline: True
Inline callers:
  - drivers/char/random.c:init_std_data
  - drivers/char/random.c:add_interrupt_randomness
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:crng_initialize
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
In drivers/char/random.c (ffffffff8164648e)
Location: arch/x86/include/asm/archrandom.h:110
Inline: True
Inline callers:
  - drivers/char/random.c:init_std_data
  - drivers/char/random.c:add_interrupt_randomness
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:crng_initialize
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
In drivers/char/random.c (ffffffff816650de)
Location: arch/x86/include/asm/archrandom.h:110
Inline: True
Inline callers:
  - drivers/char/random.c:init_std_data
  - drivers/char/random.c:init_std_data
  - drivers/char/random.c:add_interrupt_randomness
  - drivers/char/random.c:add_interrupt_randomness
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:crng_initialize
  - drivers/char/random.c:crng_initialize
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool arch_get_random_seed_long(long unsigned int *v);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff8169bffe)
Location: arch/x86/include/asm/archrandom.h:97
Inline: True
Inline callers:
  - drivers/char/random.c:add_interrupt_randomness
  - drivers/char/random.c:add_interrupt_randomness
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:crng_initialize
  - drivers/char/random.c:crng_initialize
Direct callers:
  - drivers/char/random.c:init_std_data
```
**Symbols:**

```
ffffffff816999e0-ffffffff816999f6: arch_get_random_seed_long (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool arch_get_random_seed_long(long unsigned int *v);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff816bed2e)
Location: arch/x86/include/asm/archrandom.h:97
Inline: True
Inline callers:
  - drivers/char/random.c:add_interrupt_randomness
  - drivers/char/random.c:add_interrupt_randomness
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:crng_initialize
  - drivers/char/random.c:crng_initialize
Direct callers:
  - drivers/char/random.c:init_std_data
```
**Symbols:**

```
ffffffff816bc5f0-ffffffff816bc606: arch_get_random_seed_long (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool arch_get_random_seed_long(long unsigned int *v);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff817739b9)
Location: arch/x86/include/asm/archrandom.h:83
Inline: True
Inline callers:
  - drivers/char/random.c:add_interrupt_randomness
  - drivers/char/random.c:add_interrupt_randomness
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:do_numa_crng_init
  - drivers/char/random.c:do_numa_crng_init
```
**Symbols:**

```
ffffffff81770970-ffffffff81770983: arch_get_random_seed_long (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool arch_get_random_seed_long(long unsigned int *v);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff8178e950)
Location: arch/x86/include/asm/archrandom.h:83
Inline: True
Inline callers:
  - drivers/char/random.c:add_interrupt_randomness
  - drivers/char/random.c:add_interrupt_randomness
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:do_numa_crng_init
  - drivers/char/random.c:do_numa_crng_init
```
**Symbols:**

```
ffffffff8178b9e0-ffffffff8178b9f3: arch_get_random_seed_long (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool arch_get_random_seed_long(long unsigned int *v);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff817702a3)
Location: arch/x86/include/asm/archrandom.h:83
Inline: True
Inline callers:
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:do_numa_crng_init
  - drivers/char/random.c:do_numa_crng_init
Direct callers:
  - drivers/char/random.c:rand_initialize
  - drivers/char/random.c:rand_initialize
```
**Symbols:**

```
ffffffff8176ebf0-ffffffff8176ec03: arch_get_random_seed_long (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool arch_get_random_seed_long(long unsigned int *v);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff817f5c8d)
Location: arch/x86/include/asm/archrandom.h:83
Inline: True
Inline callers:
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:do_numa_crng_init
  - drivers/char/random.c:do_numa_crng_init
Direct callers:
  - drivers/char/random.c:rand_initialize
  - drivers/char/random.c:rand_initialize
```
**Symbols:**

```
ffffffff817f43c0-ffffffff817f43d3: arch_get_random_seed_long (STB_LOCAL)
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
In drivers/char/random.c (ffffffff834b400c)
Location: arch/x86/include/asm/archrandom.h:83
Inline: True
Inline callers:
  - drivers/char/random.c:random_init
```
</details>
</li>
<li>
In <code>6.2</code>: Absent ⚠️
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
In drivers/char/random.c (0)
Location: include/linux/random.h:182
Inline: True
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
In drivers/char/random.c (0)
Location: include/linux/random.h:182
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
In lib/random32.c (c0000000013a0168)
Location: arch/powerpc/include/asm/archrandom.h:19
Inline: True
Inline callers:
  - lib/random32.c:prandom_init
  - lib/random32.c:prandom_init
  - lib/random32.c:prandom_init
  - lib/random32.c:prandom_init
```
```
In drivers/char/random.c (c0000000013a8390)
Location: arch/powerpc/include/asm/archrandom.h:19
Inline: True
Inline callers:
  - drivers/char/random.c:init_std_data
  - drivers/char/random.c:add_interrupt_randomness
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:crng_initialize
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
In drivers/char/random.c (0)
Location: include/linux/random.h:182
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
bool arch_get_random_seed_long(long unsigned int *v);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff8168479e)
Location: arch/x86/include/asm/archrandom.h:97
Inline: True
Inline callers:
  - drivers/char/random.c:add_interrupt_randomness
  - drivers/char/random.c:add_interrupt_randomness
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:crng_initialize
  - drivers/char/random.c:crng_initialize
Direct callers:
  - drivers/char/random.c:init_std_data
```
**Symbols:**

```
ffffffff81682050-ffffffff81682066: arch_get_random_seed_long (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool arch_get_random_seed_long(long unsigned int *v);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff8166241e)
Location: arch/x86/include/asm/archrandom.h:97
Inline: True
Inline callers:
  - drivers/char/random.c:add_interrupt_randomness
  - drivers/char/random.c:add_interrupt_randomness
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:crng_initialize
  - drivers/char/random.c:crng_initialize
Direct callers:
  - drivers/char/random.c:init_std_data
```
**Symbols:**

```
ffffffff8165fed0-ffffffff8165fee6: arch_get_random_seed_long (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool arch_get_random_seed_long(long unsigned int *v);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff816b2b6e)
Location: arch/x86/include/asm/archrandom.h:97
Inline: True
Inline callers:
  - drivers/char/random.c:add_interrupt_randomness
  - drivers/char/random.c:add_interrupt_randomness
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:crng_initialize
  - drivers/char/random.c:crng_initialize
Direct callers:
  - drivers/char/random.c:init_std_data
```
**Symbols:**

```
ffffffff816b0430-ffffffff816b0446: arch_get_random_seed_long (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool arch_get_random_seed_long(long unsigned int *v);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff816cd0be)
Location: arch/x86/include/asm/archrandom.h:97
Inline: True
Inline callers:
  - drivers/char/random.c:add_interrupt_randomness
  - drivers/char/random.c:add_interrupt_randomness
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:crng_initialize
  - drivers/char/random.c:crng_initialize
Direct callers:
  - drivers/char/random.c:init_std_data
```
**Symbols:**

```
ffffffff816cab80-ffffffff816cab96: arch_get_random_seed_long (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
