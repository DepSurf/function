# Function: <code>rdrand_long</code>

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
In arch/x86/kernel/cpu/rdrand.c (ffffffff8104144b)
Location: arch/x86/include/asm/archrandom.h:46
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/rdrand.c:x86_init_rdrand
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
In arch/x86/kernel/espfix_64.c (ffffffff81f8f1c5)
Location: arch/x86/include/asm/archrandom.h:43
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/kernel/cpu/rdrand.c (ffffffff8104137a)
Location: arch/x86/include/asm/archrandom.h:43
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/rdrand.c:x86_init_rdrand
```
```
In arch/x86/lib/kaslr.c (ffffffff8143e080)
Location: arch/x86/include/asm/archrandom.h:43
Inline: True
Inline callers:
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
```
```
In drivers/char/random.c (ffffffff81566456)
Location: arch/x86/include/asm/archrandom.h:43
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
In arch/x86/kernel/espfix_64.c (ffffffff81fca554)
Location: arch/x86/include/asm/archrandom.h:43
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/kernel/cpu/rdrand.c (ffffffff81040dca)
Location: arch/x86/include/asm/archrandom.h:43
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/rdrand.c:x86_init_rdrand
```
```
In arch/x86/lib/kaslr.c (ffffffff8145b000)
Location: arch/x86/include/asm/archrandom.h:43
Inline: True
Inline callers:
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
```
```
In drivers/char/random.c (ffffffff81592bb6)
Location: arch/x86/include/asm/archrandom.h:43
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
In arch/x86/kernel/espfix_64.c (ffffffff820aacfa)
Location: arch/x86/include/asm/archrandom.h:43
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/kernel/cpu/rdrand.c (ffffffff8103ed6a)
Location: arch/x86/include/asm/archrandom.h:43
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/rdrand.c:x86_init_rdrand
```
```
In drivers/char/random.c (ffffffff815a8886)
Location: arch/x86/include/asm/archrandom.h:43
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
```
In arch/x86/lib/kaslr.c (ffffffff818fcd9e)
Location: arch/x86/include/asm/archrandom.h:43
Inline: True
Inline callers:
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
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
In arch/x86/kernel/espfix_64.c (ffffffff826b147c)
Location: arch/x86/include/asm/archrandom.h:43
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/kernel/cpu/rdrand.c (ffffffff81041b7e)
Location: arch/x86/include/asm/archrandom.h:43
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/rdrand.c:x86_init_rdrand
```
```
In drivers/char/random.c (ffffffff8160f191)
Location: arch/x86/include/asm/archrandom.h:43
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
```
In arch/x86/lib/kaslr.c (ffffffff8198484e)
Location: arch/x86/include/asm/archrandom.h:43
Inline: True
Inline callers:
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
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
In arch/x86/kernel/espfix_64.c (ffffffff826dab35)
Location: arch/x86/include/asm/archrandom.h:43
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/kernel/cpu/rdrand.c (ffffffff8104356e)
Location: arch/x86/include/asm/archrandom.h:43
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/rdrand.c:x86_init_rdrand
```
```
In drivers/char/random.c (ffffffff81648871)
Location: arch/x86/include/asm/archrandom.h:43
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
```
In arch/x86/lib/kaslr.c (ffffffff819e0d77)
Location: arch/x86/include/asm/archrandom.h:43
Inline: True
Inline callers:
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
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
In arch/x86/kernel/espfix_64.c (ffffffff82890f17)
Location: arch/x86/include/asm/archrandom.h:43
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/kernel/cpu/rdrand.c (ffffffff81044c0e)
Location: arch/x86/include/asm/archrandom.h:43
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/rdrand.c:x86_init_rdrand
```
```
In drivers/char/random.c (ffffffff81667311)
Location: arch/x86/include/asm/archrandom.h:43
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
```
In arch/x86/lib/kaslr.c (ffffffff81a1bd27)
Location: arch/x86/include/asm/archrandom.h:43
Inline: True
Inline callers:
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
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
In arch/x86/kernel/espfix_64.c (ffffffff828a8482)
Location: arch/x86/include/asm/archrandom.h:30
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/kernel/cpu/rdrand.c (ffffffff810471ba)
Location: arch/x86/include/asm/archrandom.h:30
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/rdrand.c:x86_init_rdrand
```
```
In drivers/char/random.c (ffffffff8169c860)
Location: arch/x86/include/asm/archrandom.h:30
Inline: True
Inline callers:
  - drivers/char/random.c:get_random_u64
  - drivers/char/random.c:get_random_bytes_arch
  - drivers/char/random.c:extract_buf
  - drivers/char/random.c:_extract_crng
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:crng_initialize
```
```
In arch/x86/lib/kaslr.c (ffffffff81a8baef)
Location: arch/x86/include/asm/archrandom.h:30
Inline: True
Inline callers:
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
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
In arch/x86/kernel/espfix_64.c (ffffffff828ab4e2)
Location: arch/x86/include/asm/archrandom.h:30
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/kernel/cpu/rdrand.c (ffffffff8104793a)
Location: arch/x86/include/asm/archrandom.h:30
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/rdrand.c:x86_init_rdrand
```
```
In drivers/char/random.c (ffffffff816bf5d0)
Location: arch/x86/include/asm/archrandom.h:30
Inline: True
Inline callers:
  - drivers/char/random.c:get_random_u64
  - drivers/char/random.c:get_random_bytes_arch
  - drivers/char/random.c:extract_buf
  - drivers/char/random.c:_extract_crng
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:crng_initialize
```
```
In arch/x86/lib/kaslr.c (ffffffff81ac2daf)
Location: arch/x86/include/asm/archrandom.h:30
Inline: True
Inline callers:
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
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
In arch/x86/kernel/espfix_64.c (ffffffff8103b3d4)
Location: arch/x86/include/asm/archrandom.h:20
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_random
```
```
In arch/x86/kernel/cpu/rdrand.c (ffffffff8104b69e)
Location: arch/x86/include/asm/archrandom.h:20
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/rdrand.c:x86_init_rdrand
  - arch/x86/kernel/cpu/rdrand.c:x86_init_rdrand
```
```
In arch/x86/lib/kaslr.c (ffffffff815ff43f)
Location: arch/x86/include/asm/archrandom.h:20
Inline: True
Inline callers:
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
```
```
In drivers/char/random.c (ffffffff817715fe)
Location: arch/x86/include/asm/archrandom.h:20
Inline: True
Inline callers:
  - drivers/char/random.c:get_random_bytes_arch
  - drivers/char/random.c:extract_buf
  - drivers/char/random.c:_extract_crng
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:do_numa_crng_init
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
In arch/x86/kernel/espfix_64.c (ffffffff81bd3b90)
Location: arch/x86/include/asm/archrandom.h:20
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_random
```
```
In arch/x86/kernel/cpu/rdrand.c (ffffffff8104ac0e)
Location: arch/x86/include/asm/archrandom.h:20
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/rdrand.c:x86_init_rdrand
  - arch/x86/kernel/cpu/rdrand.c:x86_init_rdrand
```
```
In lib/random32.c (ffffffff81bf3f52)
Location: arch/x86/include/asm/archrandom.h:20
Inline: True
```
```
In arch/x86/lib/kaslr.c (ffffffff8162440f)
Location: arch/x86/include/asm/archrandom.h:20
Inline: True
Inline callers:
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
```
```
In drivers/char/random.c (ffffffff8178c60e)
Location: arch/x86/include/asm/archrandom.h:20
Inline: True
Inline callers:
  - drivers/char/random.c:get_random_bytes_arch
  - drivers/char/random.c:extract_buf
  - drivers/char/random.c:_extract_crng
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:do_numa_crng_init
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
In arch/x86/kernel/espfix_64.c (ffffffff831c6d25)
Location: arch/x86/include/asm/archrandom.h:20
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/kernel/cpu/rdrand.c (ffffffff8104c4ee)
Location: arch/x86/include/asm/archrandom.h:20
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/rdrand.c:x86_init_rdrand
  - arch/x86/kernel/cpu/rdrand.c:x86_init_rdrand
```
```
In lib/random32.c (ffffffff81be5dad)
Location: arch/x86/include/asm/archrandom.h:20
Inline: True
```
```
In arch/x86/lib/kaslr.c (ffffffff81607dff)
Location: arch/x86/include/asm/archrandom.h:20
Inline: True
Inline callers:
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
```
```
In drivers/char/random.c (ffffffff8176fd27)
Location: arch/x86/include/asm/archrandom.h:20
Inline: True
Inline callers:
  - drivers/char/random.c:get_random_bytes_arch
  - drivers/char/random.c:extract_buf
  - drivers/char/random.c:_extract_crng
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:do_numa_crng_init
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
In arch/x86/kernel/espfix_64.c (ffffffff832a7be9)
Location: arch/x86/include/asm/archrandom.h:20
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/kernel/cpu/rdrand.c (ffffffff8105379f)
Location: arch/x86/include/asm/archrandom.h:20
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/rdrand.c:x86_init_rdrand
  - arch/x86/kernel/cpu/rdrand.c:x86_init_rdrand
```
```
In lib/random32.c (ffffffff81cda741)
Location: arch/x86/include/asm/archrandom.h:20
Inline: True
```
```
In arch/x86/lib/kaslr.c (ffffffff81676a3f)
Location: arch/x86/include/asm/archrandom.h:20
Inline: True
Inline callers:
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
```
```
In drivers/char/random.c (ffffffff817f56e7)
Location: arch/x86/include/asm/archrandom.h:20
Inline: True
Inline callers:
  - drivers/char/random.c:get_random_bytes_arch
  - drivers/char/random.c:extract_buf
  - drivers/char/random.c:_extract_crng
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:do_numa_crng_init
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
In arch/x86/kernel/espfix_64.c (ffffffff83456f8a)
Location: arch/x86/include/asm/archrandom.h:20
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/kernel/cpu/rdrand.c (ffffffff8105f143)
Location: arch/x86/include/asm/archrandom.h:20
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/rdrand.c:x86_init_rdrand
  - arch/x86/kernel/cpu/rdrand.c:x86_init_rdrand
```
```
In arch/x86/lib/kaslr.c (ffffffff8179187b)
Location: arch/x86/include/asm/archrandom.h:20
Inline: True
Inline callers:
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
```
```
In drivers/char/random.c (ffffffff81933a4a)
Location: arch/x86/include/asm/archrandom.h:20
Inline: True
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
In arch/x86/kernel/cpu/rdrand.c (0)
Location: arch/x86/include/asm/archrandom.h:20
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/rdrand.c:x86_init_rdrand
```
```
In drivers/char/random.c (ffffffff83eeef1d)
Location: arch/x86/include/asm/archrandom.h:20
Inline: True
Inline callers:
  - drivers/char/random.c:random_init_early
```
```
In arch/x86/lib/kaslr.c (ffffffff8204f55b)
Location: arch/x86/include/asm/archrandom.h:20
Inline: True
Inline callers:
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
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
In arch/x86/kernel/cpu/rdrand.c (ffffffff8106f1e8)
Location: arch/x86/include/asm/archrandom.h:20
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/rdrand.c:x86_init_rdrand
```
```
In drivers/char/random.c (ffffffff83714b75)
Location: arch/x86/include/asm/archrandom.h:20
Inline: True
Inline callers:
  - drivers/char/random.c:random_init_early
```
```
In arch/x86/lib/kaslr.c (ffffffff820cdddb)
Location: arch/x86/include/asm/archrandom.h:20
Inline: True
Inline callers:
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
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
In arch/x86/kernel/cpu/rdrand.c (ffffffff810765a8)
Location: arch/x86/include/asm/archrandom.h:20
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/rdrand.c:x86_init_rdrand
```
```
In drivers/char/random.c (ffffffff839485d5)
Location: arch/x86/include/asm/archrandom.h:20
Inline: True
Inline callers:
  - drivers/char/random.c:random_init_early
```
```
In arch/x86/lib/kaslr.c (ffffffff821a85fb)
Location: arch/x86/include/asm/archrandom.h:20
Inline: True
Inline callers:
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
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
In arch/x86/kernel/espfix_64.c (ffffffff828994f4)
Location: arch/x86/include/asm/archrandom.h:30
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/kernel/cpu/rdrand.c (ffffffff81047aaa)
Location: arch/x86/include/asm/archrandom.h:30
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/rdrand.c:x86_init_rdrand
```
```
In drivers/char/random.c (ffffffff81685020)
Location: arch/x86/include/asm/archrandom.h:30
Inline: True
Inline callers:
  - drivers/char/random.c:get_random_u64
  - drivers/char/random.c:get_random_bytes_arch
  - drivers/char/random.c:extract_buf
  - drivers/char/random.c:_extract_crng
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:crng_initialize
```
```
In arch/x86/lib/kaslr.c (ffffffff81a61bff)
Location: arch/x86/include/asm/archrandom.h:30
Inline: True
Inline callers:
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
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
In arch/x86/kernel/espfix_64.c (ffffffff828917b5)
Location: arch/x86/include/asm/archrandom.h:30
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/kernel/cpu/rdrand.c (ffffffff81036daa)
Location: arch/x86/include/asm/archrandom.h:30
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/rdrand.c:x86_init_rdrand
```
```
In drivers/char/random.c (ffffffff81662cc0)
Location: arch/x86/include/asm/archrandom.h:30
Inline: True
Inline callers:
  - drivers/char/random.c:get_random_u64
  - drivers/char/random.c:get_random_bytes_arch
  - drivers/char/random.c:extract_buf
  - drivers/char/random.c:_extract_crng
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:crng_initialize
```
```
In arch/x86/lib/kaslr.c (ffffffff81a1ec6f)
Location: arch/x86/include/asm/archrandom.h:30
Inline: True
Inline callers:
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
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
In arch/x86/kernel/espfix_64.c (ffffffff828ac4d4)
Location: arch/x86/include/asm/archrandom.h:30
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/kernel/cpu/rdrand.c (ffffffff810478ea)
Location: arch/x86/include/asm/archrandom.h:30
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/rdrand.c:x86_init_rdrand
```
```
In drivers/char/random.c (ffffffff816b3410)
Location: arch/x86/include/asm/archrandom.h:30
Inline: True
Inline callers:
  - drivers/char/random.c:get_random_u64
  - drivers/char/random.c:get_random_bytes_arch
  - drivers/char/random.c:extract_buf
  - drivers/char/random.c:_extract_crng
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:crng_initialize
```
```
In arch/x86/lib/kaslr.c (ffffffff81acdfef)
Location: arch/x86/include/asm/archrandom.h:30
Inline: True
Inline callers:
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
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
In arch/x86/kernel/espfix_64.c (ffffffff828ac4f2)
Location: arch/x86/include/asm/archrandom.h:30
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/kernel/cpu/rdrand.c (ffffffff81048cfa)
Location: arch/x86/include/asm/archrandom.h:30
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/rdrand.c:x86_init_rdrand
```
```
In drivers/char/random.c (ffffffff816cd990)
Location: arch/x86/include/asm/archrandom.h:30
Inline: True
Inline callers:
  - drivers/char/random.c:get_random_u64
  - drivers/char/random.c:get_random_bytes_arch
  - drivers/char/random.c:extract_buf
  - drivers/char/random.c:_extract_crng
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:crng_initialize
```
```
In arch/x86/lib/kaslr.c (ffffffff81ada4ff)
Location: arch/x86/include/asm/archrandom.h:30
Inline: True
Inline callers:
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
```
</details>
</li>
</ul>

## Differences
