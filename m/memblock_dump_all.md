# Function: <code>memblock_dump_all</code>

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
In arch/x86/kernel/e820.c (ffffffff81f687d5)
Location: include/linux/memblock.h:328
Inline: True
Inline callers:
  - arch/x86/kernel/e820.c:memblock_x86_fill
```
```
In arch/x86/mm/numa.c (ffffffff81f78e93)
Location: include/linux/memblock.h:328
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
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
In arch/x86/kernel/e820.c (ffffffff81f906d5)
Location: include/linux/memblock.h:344
Inline: True
Inline callers:
  - arch/x86/kernel/e820.c:memblock_x86_fill
```
```
In arch/x86/mm/numa.c (ffffffff81fa15be)
Location: include/linux/memblock.h:344
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
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
In arch/x86/kernel/e820.c (ffffffff81fcba75)
Location: include/linux/memblock.h:345
Inline: True
Inline callers:
  - arch/x86/kernel/e820.c:memblock_x86_fill
```
```
In arch/x86/mm/numa.c (ffffffff81fdcb95)
Location: include/linux/memblock.h:345
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
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
In arch/x86/kernel/e820.c (ffffffff820ac2e3)
Location: include/linux/memblock.h:326
Inline: True
Inline callers:
  - arch/x86/kernel/e820.c:e820__memblock_setup
```
```
In arch/x86/mm/numa.c (ffffffff820bdb83)
Location: include/linux/memblock.h:326
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
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
In arch/x86/kernel/e820.c (ffffffff826b2abc)
Location: include/linux/memblock.h:341
Inline: True
Inline callers:
  - arch/x86/kernel/e820.c:e820__memblock_setup
```
```
In arch/x86/mm/numa.c (ffffffff826c49ba)
Location: include/linux/memblock.h:341
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
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
In arch/x86/kernel/e820.c (ffffffff826dc27a)
Location: include/linux/memblock.h:344
Inline: True
Inline callers:
  - arch/x86/kernel/e820.c:e820__memblock_setup
```
```
In arch/x86/mm/numa.c (ffffffff826eec5d)
Location: include/linux/memblock.h:344
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
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
In arch/x86/kernel/e820.c (ffffffff82892638)
Location: include/linux/memblock.h:472
Inline: True
Inline callers:
  - arch/x86/kernel/e820.c:e820__memblock_setup
```
```
In arch/x86/mm/numa.c (ffffffff828a594b)
Location: include/linux/memblock.h:472
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
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
In arch/x86/kernel/e820.c (ffffffff828a9b84)
Location: include/linux/memblock.h:455
Inline: True
Inline callers:
  - arch/x86/kernel/e820.c:e820__memblock_setup
```
```
In arch/x86/mm/numa.c (ffffffff828bdf20)
Location: include/linux/memblock.h:455
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
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
In arch/x86/kernel/e820.c (ffffffff828acbe7)
Location: include/linux/memblock.h:455
Inline: True
Inline callers:
  - arch/x86/kernel/e820.c:e820__memblock_setup
```
```
In arch/x86/mm/numa.c (ffffffff828c437a)
Location: include/linux/memblock.h:455
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
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
In arch/x86/kernel/e820.c (ffffffff82cd1fb0)
Location: include/linux/memblock.h:461
Inline: True
Inline callers:
  - arch/x86/kernel/e820.c:e820__memblock_setup
```
```
In arch/x86/mm/numa.c (ffffffff82ce7133)
Location: include/linux/memblock.h:461
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void memblock_dump_all();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81c40105)
Location: mm/memblock.c:1876
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__memblock_setup
```
**Symbols:**

```
ffffffff81c40105-ffffffff81c40153: memblock_dump_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void memblock_dump_all();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81c321c6)
Location: mm/memblock.c:1877
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__memblock_setup
```
**Symbols:**

```
ffffffff81c321c6-ffffffff81c32214: memblock_dump_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void memblock_dump_all();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81d50bc6)
Location: mm/memblock.c:1904
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__memblock_setup
```
**Symbols:**

```
ffffffff81d50bc6-ffffffff81d50c14: memblock_dump_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void memblock_dump_all();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81f20de5)
Location: mm/memblock.c:1911
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__memblock_setup
```
**Symbols:**

```
ffffffff81f20de5-ffffffff81f20e4b: memblock_dump_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void memblock_dump_all();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff820caa20)
Location: mm/memblock.c:1929
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__memblock_setup
```
**Symbols:**

```
ffffffff820caa20-ffffffff820caa87: memblock_dump_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void memblock_dump_all();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff8214ecb0)
Location: mm/memblock.c:1951
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__memblock_setup
```
**Symbols:**

```
ffffffff8214ecb0-ffffffff8214ed17: memblock_dump_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void memblock_dump_all();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff82231b20)
Location: mm/memblock.c:2009
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__memblock_setup
```
**Symbols:**

```
ffffffff82231b20-ffffffff82231b87: memblock_dump_all (STB_GLOBAL)
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
In arch/arm64/mm/init.c (ffff8000114377e8)
Location: include/linux/memblock.h:455
Inline: True
Inline callers:
  - arch/arm64/mm/init.c:bootmem_init
```
```
In drivers/firmware/efi/arm-init.c (ffff8000114a72bc)
Location: include/linux/memblock.h:455
Inline: True
Inline callers:
  - drivers/firmware/efi/arm-init.c:reserve_regions
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
In arch/arm/mm/init.c (c1507734)
Location: include/linux/memblock.h:455
Inline: True
Inline callers:
  - arch/arm/mm/init.c:arm_memblock_init
```
```
In drivers/firmware/efi/arm-init.c (c15a9a90)
Location: include/linux/memblock.h:455
Inline: True
Inline callers:
  - drivers/firmware/efi/arm-init.c:reserve_regions
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
In arch/powerpc/kernel/prom.c (c000000001349d0c)
Location: include/linux/memblock.h:455
Inline: True
Inline callers:
  - arch/powerpc/kernel/prom.c:early_init_devtree
```
```
In arch/powerpc/mm/drmem.c (c000000001354de4)
Location: include/linux/memblock.h:455
Inline: True
Inline callers:
  - arch/powerpc/mm/drmem.c:walk_drmem_lmbs_early
```
```
In arch/powerpc/mm/numa.c (c000000001357a2c)
Location: include/linux/memblock.h:455
Inline: True
Inline callers:
  - arch/powerpc/mm/numa.c:initmem_init
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
In arch/riscv/mm/init.c (ffffffe000003c36)
Location: include/linux/memblock.h:455
Inline: True
Inline callers:
  - arch/riscv/mm/init.c:setup_bootmem
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
In arch/x86/kernel/e820.c (ffffffff8289abf9)
Location: include/linux/memblock.h:455
Inline: True
Inline callers:
  - arch/x86/kernel/e820.c:e820__memblock_setup
```
```
In arch/x86/mm/numa.c (ffffffff828af350)
Location: include/linux/memblock.h:455
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
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
In arch/x86/kernel/e820.c (ffffffff82892eb7)
Location: include/linux/memblock.h:455
Inline: True
Inline callers:
  - arch/x86/kernel/e820.c:e820__memblock_setup
```
```
In arch/x86/mm/numa.c (ffffffff828a7542)
Location: include/linux/memblock.h:455
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
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
In arch/x86/kernel/e820.c (ffffffff828adbd9)
Location: include/linux/memblock.h:455
Inline: True
Inline callers:
  - arch/x86/kernel/e820.c:e820__memblock_setup
```
```
In arch/x86/mm/numa.c (ffffffff828c224f)
Location: include/linux/memblock.h:455
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
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
In arch/x86/kernel/e820.c (ffffffff828adbf7)
Location: include/linux/memblock.h:455
Inline: True
Inline callers:
  - arch/x86/kernel/e820.c:e820__memblock_setup
```
```
In arch/x86/mm/numa.c (ffffffff828c539a)
Location: include/linux/memblock.h:455
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
