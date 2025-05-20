# Function: <code>memblock_remove</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int memblock_remove(phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff8181ea21)
Location: mm/memblock.c:724
Inline: False
Direct callers:
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:remove_memory
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
```
**Symbols:**

```
ffffffff8181ea21-ffffffff8181ea39: memblock_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int memblock_remove(phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81898ed2)
Location: mm/memblock.c:713
Inline: False
Direct callers:
  - mm/memory_hotplug.c:remove_memory
  - mm/memory_hotplug.c:add_memory_resource
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
```
**Symbols:**

```
ffffffff81898ed2-ffffffff81898eea: memblock_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int memblock_remove(phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff818cd57a)
Location: mm/memblock.c:713
Inline: False
Direct callers:
  - mm/memory_hotplug.c:remove_memory
  - mm/memory_hotplug.c:add_memory_resource
```
**Symbols:**

```
ffffffff818cd57a-ffffffff818cd592: memblock_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int memblock_remove(phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81904987)
Location: mm/memblock.c:697
Inline: False
Direct callers:
  - mm/memory_hotplug.c:remove_memory
  - mm/memory_hotplug.c:add_memory_resource
```
**Symbols:**

```
ffffffff81904987-ffffffff8190499f: memblock_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int memblock_remove(phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff8198e990)
Location: mm/memblock.c:697
Inline: False
Direct callers:
  - mm/memory_hotplug.c:remove_memory
  - mm/memory_hotplug.c:add_memory_resource
```
**Symbols:**

```
ffffffff8198e990-ffffffff8198e9a8: memblock_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int memblock_remove(phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff819eb213)
Location: mm/memblock.c:700
Inline: False
Direct callers:
  - mm/memory_hotplug.c:remove_memory
  - mm/memory_hotplug.c:add_memory_resource
```
**Symbols:**

```
ffffffff819eb213-ffffffff819eb28a: memblock_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int memblock_remove(phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81a26493)
Location: mm/memblock.c:801
Inline: False
Direct callers:
  - mm/memory_hotplug.c:__remove_memory
  - mm/memory_hotplug.c:add_memory_resource
```
**Symbols:**

```
ffffffff81a26493-ffffffff81a2650a: memblock_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int memblock_remove(phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81a96c40)
Location: mm/memblock.c:798
Inline: False
Direct callers:
  - mm/memory_hotplug.c:try_remove_memory
  - mm/memory_hotplug.c:add_memory_resource
```
**Symbols:**

```
ffffffff81a96c40-ffffffff81a96cb9: memblock_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int memblock_remove(phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81ace4b0)
Location: mm/memblock.c:798
Inline: False
Direct callers:
  - mm/memory_hotplug.c:try_remove_memory
  - mm/memory_hotplug.c:add_memory_resource
```
**Symbols:**

```
ffffffff81ace4b0-ffffffff81ace529: memblock_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int memblock_remove(phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81bc6bc7)
Location: mm/memblock.c:794
Inline: False
```
**Symbols:**

```
ffffffff81bc6bc7-ffffffff81bc6c47: memblock_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int memblock_remove(phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81c3f8e9)
Location: mm/memblock.c:781
Inline: False
```
**Symbols:**

```
ffffffff81c3f8e9-ffffffff81c3f969: memblock_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int memblock_remove(phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81c319a9)
Location: mm/memblock.c:781
Inline: False
```
**Symbols:**

```
ffffffff81c319a9-ffffffff81c31a29: memblock_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int memblock_remove(phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81d5030d)
Location: mm/memblock.c:794
Inline: False
```
**Symbols:**

```
ffffffff81d5030d-ffffffff81d5038d: memblock_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int memblock_remove(phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81f20739)
Location: mm/memblock.c:795
Inline: False
```
**Symbols:**

```
ffffffff81f20739-ffffffff81f207c6: memblock_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int memblock_remove(phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff820ca080)
Location: mm/memblock.c:810
Inline: False
```
**Symbols:**

```
ffffffff820ca080-ffffffff820ca15d: memblock_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int memblock_remove(phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff8214e310)
Location: mm/memblock.c:823
Inline: False
```
**Symbols:**

```
ffffffff8214e310-ffffffff8214e3ed: memblock_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int memblock_remove(phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff82231080)
Location: mm/memblock.c:863
Inline: False
```
**Symbols:**

```
ffffffff82231080-ffffffff8223115d: memblock_remove (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int memblock_remove(phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffff80001031ca10)
Location: mm/memblock.c:798
Inline: False
Direct callers:
  - arch/arm64/mm/init.c:arm64_memblock_init
  - arch/arm64/mm/init.c:arm64_memblock_init
  - arch/arm64/mm/init.c:arm64_memblock_init
  - arch/arm64/mm/init.c:arm64_memblock_init
  - mm/memory_hotplug.c:add_memory_resource
  - drivers/firmware/efi/arm-init.c:reserve_regions
  - drivers/of/fdt.c:early_init_dt_reserve_memory_arch
  - drivers/of/of_reserved_mem.c:early_init_dt_alloc_reserved_memory_arch
```
**Symbols:**

```
ffff80001031ca10-ffff80001031cabc: memblock_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int memblock_remove(phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (c0536918)
Location: mm/memblock.c:798
Inline: False
Direct callers:
  - arch/arm/kernel/setup.c:early_mem
  - arch/arm/mm/init.c:arm_memblock_steal
  - drivers/firmware/efi/arm-init.c:reserve_regions
  - drivers/of/fdt.c:early_init_dt_reserve_memory_arch
  - drivers/of/of_reserved_mem.c:early_init_dt_alloc_reserved_memory_arch
```
**Symbols:**

```
c0536918-c05369c8: memblock_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int memblock_remove(phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (c0000000003f0880)
Location: mm/memblock.c:798
Inline: False
Direct callers:
  - arch/powerpc/platforms/pseries/hotplug-memory.c:pseries_remove_memblock
  - arch/powerpc/platforms/pseries/hotplug-memory.c:pseries_remove_memblock
  - mm/memory_hotplug.c:try_remove_memory
  - mm/memory_hotplug.c:add_memory_resource
  - drivers/of/fdt.c:early_init_dt_reserve_memory_arch
  - drivers/of/of_reserved_mem.c:early_init_dt_alloc_reserved_memory_arch
```
**Symbols:**

```
c0000000003f0880-c0000000003f0938: memblock_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int memblock_remove(phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffe00004868c)
Location: mm/memblock.c:798
Inline: False
Direct callers:
  - arch/riscv/mm/init.c:setup_bootmem
  - drivers/of/fdt.c:early_init_dt_reserve_memory_arch
  - drivers/of/of_reserved_mem.c:early_init_dt_alloc_reserved_memory_arch
```
**Symbols:**

```
ffffffe00004868c-ffffffe0000486ea: memblock_remove (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int memblock_remove(phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81a6d320)
Location: mm/memblock.c:798
Inline: False
Direct callers:
  - mm/memory_hotplug.c:try_remove_memory
  - mm/memory_hotplug.c:add_memory_resource
```
**Symbols:**

```
ffffffff81a6d320-ffffffff81a6d399: memblock_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int memblock_remove(phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81a29867)
Location: mm/memblock.c:798
Inline: False
Direct callers:
  - mm/memory_hotplug.c:try_remove_memory
  - mm/memory_hotplug.c:add_memory_resource
```
**Symbols:**

```
ffffffff81a29867-ffffffff81a298e0: memblock_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int memblock_remove(phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81ad9730)
Location: mm/memblock.c:798
Inline: False
Direct callers:
  - mm/memory_hotplug.c:try_remove_memory
  - mm/memory_hotplug.c:add_memory_resource
```
**Symbols:**

```
ffffffff81ad9730-ffffffff81ad97a9: memblock_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int memblock_remove(phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81ae5be6)
Location: mm/memblock.c:798
Inline: False
Direct callers:
  - mm/memory_hotplug.c:try_remove_memory
  - mm/memory_hotplug.c:add_memory_resource
```
**Symbols:**

```
ffffffff81ae5be6-ffffffff81ae5c5f: memblock_remove (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
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
