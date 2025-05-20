# Function: <code>arch_get_random_long</code>

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
In arch/x86/kernel/espfix_64.c (ffffffff81f6731e)
Location: arch/x86/include/asm/archrandom.h:101
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In drivers/char/random.c (ffffffff815122b9)
Location: arch/x86/include/asm/archrandom.h:101
Inline: True
Inline callers:
  - drivers/char/random.c:extract_buf
  - drivers/char/random.c:get_random_bytes_arch
  - drivers/char/random.c:init_std_data
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
In arch/x86/kernel/espfix_64.c (ffffffff81f8f1b4)
Location: arch/x86/include/asm/archrandom.h:100
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In drivers/char/random.c (ffffffff81566445)
Location: arch/x86/include/asm/archrandom.h:100
Inline: True
Inline callers:
  - drivers/char/random.c:get_random_long
  - drivers/char/random.c:init_std_data
  - drivers/char/random.c:get_random_bytes_arch
  - drivers/char/random.c:extract_buf
  - drivers/char/random.c:_extract_crng
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:crng_initialize
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
In arch/x86/kernel/espfix_64.c (ffffffff81fca543)
Location: arch/x86/include/asm/archrandom.h:100
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In drivers/char/random.c (ffffffff81592ba5)
Location: arch/x86/include/asm/archrandom.h:100
Inline: True
Inline callers:
  - drivers/char/random.c:get_random_long
  - drivers/char/random.c:init_std_data
  - drivers/char/random.c:get_random_bytes_arch
  - drivers/char/random.c:extract_buf
  - drivers/char/random.c:_extract_crng
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:crng_initialize
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
In arch/x86/kernel/espfix_64.c (ffffffff820aace9)
Location: arch/x86/include/asm/archrandom.h:100
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In drivers/char/random.c (ffffffff815a8875)
Location: arch/x86/include/asm/archrandom.h:100
Inline: True
Inline callers:
  - drivers/char/random.c:get_random_u64
  - drivers/char/random.c:init_std_data
  - drivers/char/random.c:get_random_bytes_arch
  - drivers/char/random.c:extract_buf
  - drivers/char/random.c:_extract_crng
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:crng_initialize
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
In arch/x86/kernel/espfix_64.c (ffffffff826b146b)
Location: arch/x86/include/asm/archrandom.h:100
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In drivers/char/random.c (ffffffff8160f180)
Location: arch/x86/include/asm/archrandom.h:100
Inline: True
Inline callers:
  - drivers/char/random.c:get_random_u64
  - drivers/char/random.c:init_std_data
  - drivers/char/random.c:get_random_bytes_arch
  - drivers/char/random.c:extract_buf
  - drivers/char/random.c:_extract_crng
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:crng_initialize
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
In arch/x86/kernel/espfix_64.c (ffffffff826dab24)
Location: arch/x86/include/asm/archrandom.h:100
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In drivers/char/random.c (ffffffff81648855)
Location: arch/x86/include/asm/archrandom.h:100
Inline: True
Inline callers:
  - drivers/char/random.c:get_random_u64
  - drivers/char/random.c:init_std_data
  - drivers/char/random.c:get_random_bytes_arch
  - drivers/char/random.c:extract_buf
  - drivers/char/random.c:_extract_crng
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:crng_initialize
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
In arch/x86/kernel/espfix_64.c (ffffffff82890f06)
Location: arch/x86/include/asm/archrandom.h:100
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In drivers/char/random.c (ffffffff816672f5)
Location: arch/x86/include/asm/archrandom.h:100
Inline: True
Inline callers:
  - drivers/char/random.c:get_random_u64
  - drivers/char/random.c:get_random_u64
  - drivers/char/random.c:init_std_data
  - drivers/char/random.c:init_std_data
  - drivers/char/random.c:get_random_bytes_arch
  - drivers/char/random.c:get_random_bytes_arch
  - drivers/char/random.c:extract_buf
  - drivers/char/random.c:extract_buf
  - drivers/char/random.c:_extract_crng
  - drivers/char/random.c:_extract_crng
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:crng_initialize
  - drivers/char/random.c:crng_initialize
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool arch_get_random_long(long unsigned int *v);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/espfix_64.c (ffffffff828a8471)
Location: arch/x86/include/asm/archrandom.h:87
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In drivers/char/random.c (ffffffff8169c845)
Location: arch/x86/include/asm/archrandom.h:87
Inline: True
Inline callers:
  - drivers/char/random.c:get_random_u64
  - drivers/char/random.c:get_random_u64
  - drivers/char/random.c:get_random_bytes_arch
  - drivers/char/random.c:get_random_bytes_arch
  - drivers/char/random.c:extract_buf
  - drivers/char/random.c:extract_buf
  - drivers/char/random.c:_extract_crng
  - drivers/char/random.c:_extract_crng
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:crng_initialize
  - drivers/char/random.c:crng_initialize
Direct callers:
  - drivers/char/random.c:init_std_data
```
**Symbols:**

```
ffffffff816999a0-ffffffff816999d1: arch_get_random_long (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool arch_get_random_long(long unsigned int *v);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/espfix_64.c (ffffffff828ab4d1)
Location: arch/x86/include/asm/archrandom.h:87
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In drivers/char/random.c (ffffffff816bf5b5)
Location: arch/x86/include/asm/archrandom.h:87
Inline: True
Inline callers:
  - drivers/char/random.c:get_random_u64
  - drivers/char/random.c:get_random_u64
  - drivers/char/random.c:get_random_bytes_arch
  - drivers/char/random.c:get_random_bytes_arch
  - drivers/char/random.c:extract_buf
  - drivers/char/random.c:extract_buf
  - drivers/char/random.c:_extract_crng
  - drivers/char/random.c:_extract_crng
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:crng_initialize
  - drivers/char/random.c:crng_initialize
Direct callers:
  - drivers/char/random.c:init_std_data
```
**Symbols:**

```
ffffffff816bc5b0-ffffffff816bc5e1: arch_get_random_long (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool arch_get_random_long(long unsigned int *v);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/espfix_64.c (ffffffff8103b3bf)
Location: arch/x86/include/asm/archrandom.h:73
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_random
```
```
In drivers/char/random.c (ffffffff817715f4)
Location: arch/x86/include/asm/archrandom.h:73
Inline: True
Inline callers:
  - drivers/char/random.c:get_random_bytes_arch
  - drivers/char/random.c:get_random_bytes_arch
  - drivers/char/random.c:extract_buf
  - drivers/char/random.c:extract_buf
  - drivers/char/random.c:_extract_crng
  - drivers/char/random.c:_extract_crng
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:do_numa_crng_init
  - drivers/char/random.c:do_numa_crng_init
```
**Symbols:**

```
ffffffff81770930-ffffffff81770961: arch_get_random_long (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool arch_get_random_long(long unsigned int *v);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/espfix_64.c (ffffffff81bd3b7b)
Location: arch/x86/include/asm/archrandom.h:73
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_random
```
```
In lib/random32.c (ffffffff81bf3f41)
Location: arch/x86/include/asm/archrandom.h:73
Inline: True
Direct callers:
  - lib/random32.c:prandom_init_early
  - lib/random32.c:prandom_init_early
```
```
In drivers/char/random.c (ffffffff8178c604)
Location: arch/x86/include/asm/archrandom.h:73
Inline: True
Inline callers:
  - drivers/char/random.c:get_random_bytes_arch
  - drivers/char/random.c:get_random_bytes_arch
  - drivers/char/random.c:extract_buf
  - drivers/char/random.c:extract_buf
  - drivers/char/random.c:_extract_crng
  - drivers/char/random.c:_extract_crng
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:do_numa_crng_init
  - drivers/char/random.c:do_numa_crng_init
```
**Symbols:**

```
ffffffff81bf3f41-ffffffff81bf3f6f: arch_get_random_long (STB_LOCAL)
ffffffff8178b9a0-ffffffff8178b9d1: arch_get_random_long (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool arch_get_random_long(long unsigned int *v);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/espfix_64.c (ffffffff831c6d14)
Location: arch/x86/include/asm/archrandom.h:73
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In lib/random32.c (ffffffff81be5d9c)
Location: arch/x86/include/asm/archrandom.h:73
Inline: True
Direct callers:
  - lib/random32.c:prandom_init_early
  - lib/random32.c:prandom_init_early
```
```
In drivers/char/random.c (ffffffff8176fd1d)
Location: arch/x86/include/asm/archrandom.h:73
Inline: True
Inline callers:
  - drivers/char/random.c:get_random_bytes_arch
  - drivers/char/random.c:get_random_bytes_arch
  - drivers/char/random.c:extract_buf
  - drivers/char/random.c:extract_buf
  - drivers/char/random.c:_extract_crng
  - drivers/char/random.c:_extract_crng
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
ffffffff81be5d9c-ffffffff81be5dca: arch_get_random_long (STB_LOCAL)
ffffffff8176ebb0-ffffffff8176ebe1: arch_get_random_long (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool arch_get_random_long(long unsigned int *v);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/espfix_64.c (ffffffff832a7bd8)
Location: arch/x86/include/asm/archrandom.h:73
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In lib/random32.c (ffffffff81cda730)
Location: arch/x86/include/asm/archrandom.h:73
Inline: True
Direct callers:
  - lib/random32.c:prandom_init_early
  - lib/random32.c:prandom_init_early
```
```
In drivers/char/random.c (ffffffff817f56dd)
Location: arch/x86/include/asm/archrandom.h:73
Inline: True
Inline callers:
  - drivers/char/random.c:get_random_bytes_arch
  - drivers/char/random.c:get_random_bytes_arch
  - drivers/char/random.c:extract_buf
  - drivers/char/random.c:extract_buf
  - drivers/char/random.c:_extract_crng
  - drivers/char/random.c:_extract_crng
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
ffffffff81cda730-ffffffff81cda75e: arch_get_random_long (STB_LOCAL)
ffffffff817f4380-ffffffff817f43b1: arch_get_random_long (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool arch_get_random_long(long unsigned int *v);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/espfix_64.c (ffffffff83456f79)
Location: arch/x86/include/asm/archrandom.h:73
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In drivers/char/random.c (ffffffff81933a40)
Location: arch/x86/include/asm/archrandom.h:73
Inline: True
Direct callers:
  - drivers/char/random.c:random_init
```
**Symbols:**

```
ffffffff81933a40-ffffffff81933a80: arch_get_random_long (STB_LOCAL)
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
Location: include/linux/random.h:170
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
Location: include/linux/random.h:170
Inline: True
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
In drivers/char/random.c (0)
Location: arch/powerpc/include/asm/archrandom.h:9
Inline: True
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
Location: include/linux/random.h:170
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool arch_get_random_long(long unsigned int *v);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/espfix_64.c (ffffffff828994e3)
Location: arch/x86/include/asm/archrandom.h:87
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In drivers/char/random.c (ffffffff81685005)
Location: arch/x86/include/asm/archrandom.h:87
Inline: True
Inline callers:
  - drivers/char/random.c:get_random_u64
  - drivers/char/random.c:get_random_u64
  - drivers/char/random.c:get_random_bytes_arch
  - drivers/char/random.c:get_random_bytes_arch
  - drivers/char/random.c:extract_buf
  - drivers/char/random.c:extract_buf
  - drivers/char/random.c:_extract_crng
  - drivers/char/random.c:_extract_crng
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:crng_initialize
  - drivers/char/random.c:crng_initialize
Direct callers:
  - drivers/char/random.c:init_std_data
```
**Symbols:**

```
ffffffff81682010-ffffffff81682041: arch_get_random_long (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool arch_get_random_long(long unsigned int *v);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/espfix_64.c (ffffffff828917a4)
Location: arch/x86/include/asm/archrandom.h:87
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In drivers/char/random.c (ffffffff81662ca5)
Location: arch/x86/include/asm/archrandom.h:87
Inline: True
Inline callers:
  - drivers/char/random.c:get_random_u64
  - drivers/char/random.c:get_random_u64
  - drivers/char/random.c:get_random_bytes_arch
  - drivers/char/random.c:get_random_bytes_arch
  - drivers/char/random.c:extract_buf
  - drivers/char/random.c:extract_buf
  - drivers/char/random.c:_extract_crng
  - drivers/char/random.c:_extract_crng
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:crng_initialize
  - drivers/char/random.c:crng_initialize
Direct callers:
  - drivers/char/random.c:init_std_data
```
**Symbols:**

```
ffffffff8165fe90-ffffffff8165fec1: arch_get_random_long (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool arch_get_random_long(long unsigned int *v);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/espfix_64.c (ffffffff828ac4c3)
Location: arch/x86/include/asm/archrandom.h:87
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In drivers/char/random.c (ffffffff816b33f5)
Location: arch/x86/include/asm/archrandom.h:87
Inline: True
Inline callers:
  - drivers/char/random.c:get_random_u64
  - drivers/char/random.c:get_random_u64
  - drivers/char/random.c:get_random_bytes_arch
  - drivers/char/random.c:get_random_bytes_arch
  - drivers/char/random.c:extract_buf
  - drivers/char/random.c:extract_buf
  - drivers/char/random.c:_extract_crng
  - drivers/char/random.c:_extract_crng
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:crng_initialize
  - drivers/char/random.c:crng_initialize
Direct callers:
  - drivers/char/random.c:init_std_data
```
**Symbols:**

```
ffffffff816b03f0-ffffffff816b0421: arch_get_random_long (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool arch_get_random_long(long unsigned int *v);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/espfix_64.c (ffffffff828ac4e1)
Location: arch/x86/include/asm/archrandom.h:87
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In drivers/char/random.c (ffffffff816cd975)
Location: arch/x86/include/asm/archrandom.h:87
Inline: True
Inline callers:
  - drivers/char/random.c:get_random_u64
  - drivers/char/random.c:get_random_u64
  - drivers/char/random.c:get_random_bytes_arch
  - drivers/char/random.c:get_random_bytes_arch
  - drivers/char/random.c:extract_buf
  - drivers/char/random.c:extract_buf
  - drivers/char/random.c:_extract_crng
  - drivers/char/random.c:_extract_crng
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:crng_initialize
  - drivers/char/random.c:crng_initialize
Direct callers:
  - drivers/char/random.c:init_std_data
```
**Symbols:**

```
ffffffff816cab40-ffffffff816cab71: arch_get_random_long (STB_LOCAL)
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
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
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
