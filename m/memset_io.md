# Function: <code>memset_io</code>

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
In drivers/cpufreq/pcc-cpufreq.c (ffffffff816b8f29)
Location: arch/x86/include/asm/io.h:211
Inline: True
Inline callers:
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_cpu_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_cpu_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
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
In drivers/cpufreq/pcc-cpufreq.c (ffffffff8171abf7)
Location: arch/x86/include/asm/io.h:211
Inline: True
Inline callers:
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_cpu_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_cpu_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
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
In drivers/cpufreq/pcc-cpufreq.c (ffffffff8174c9e7)
Location: arch/x86/include/asm/io.h:211
Inline: True
Inline callers:
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_cpu_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_cpu_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
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
In drivers/cpufreq/pcc-cpufreq.c (ffffffff8176b26c)
Location: arch/x86/include/asm/io.h:219
Inline: True
Inline callers:
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_cpu_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_cpu_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
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
In drivers/cpufreq/pcc-cpufreq.c (ffffffff817e114c)
Location: include/asm-generic/io.h:970
Inline: True
Inline callers:
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_cpu_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_cpu_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
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
In drivers/cpufreq/pcc-cpufreq.c (ffffffff81829c1c)
Location: include/asm-generic/io.h:1095
Inline: True
Inline callers:
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_cpu_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_cpu_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void memset_io(volatile void *a, int b, size_t c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/iomem.c (ffffffff8150e640)
Location: arch/x86/lib/iomem.c:61
Inline: False
Direct callers:
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_cpu_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_cpu_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
```
**Symbols:**

```
ffffffff8150e640-ffffffff8150e650: memset_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void memset_io(volatile void *a, int b, size_t c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/iomem.c (ffffffff8153ccb0)
Location: arch/x86/lib/iomem.c:61
Inline: False
Direct callers:
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_cpu_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_cpu_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
```
**Symbols:**

```
ffffffff8153ccb0-ffffffff8153ccc0: memset_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void memset_io(volatile void *a, int b, size_t c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/iomem.c (ffffffff8155dac0)
Location: arch/x86/lib/iomem.c:61
Inline: False
Direct callers:
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_cpu_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_cpu_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
```
**Symbols:**

```
ffffffff8155dac0-ffffffff8155dad0: memset_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void memset_io(volatile void *a, int b, size_t c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/iomem.c (ffffffff815e7530)
Location: arch/x86/lib/iomem.c:61
Inline: False
Direct callers:
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_offset
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_offset
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
```
**Symbols:**

```
ffffffff815e7530-ffffffff815e7540: memset_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void memset_io(volatile void *a, int b, size_t c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/iomem.c (ffffffff8160c730)
Location: arch/x86/lib/iomem.c:61
Inline: False
Direct callers:
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_offset
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_offset
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
```
**Symbols:**

```
ffffffff8160c730-ffffffff8160c740: memset_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void memset_io(volatile void *a, int b, size_t c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/iomem.c (ffffffff815ef9d0)
Location: arch/x86/lib/iomem.c:61
Inline: False
Direct callers:
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_offset
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_offset
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
  - drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_load_segments
```
**Symbols:**

```
ffffffff815ef9d0-ffffffff815ef9e0: memset_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void memset_io(volatile void *a, int b, size_t c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/iomem.c (ffffffff8165cae0)
Location: arch/x86/lib/iomem.c:61
Inline: False
Direct callers:
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_offset
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_offset
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
  - drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_load_segments
```
**Symbols:**

```
ffffffff8165cae0-ffffffff8165caf0: memset_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void memset_io(volatile void *a, int b, size_t c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/iomem.c (ffffffff81775c50)
Location: arch/x86/lib/iomem.c:106
Inline: False
Direct callers:
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_offset
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_offset
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
  - drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_load_segments
```
**Symbols:**

```
ffffffff81775c50-ffffffff81775cc7: memset_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void memset_io(volatile void *a, int b, size_t c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/iomem.c (ffffffff818a6980)
Location: arch/x86/lib/iomem.c:111
Inline: False
Direct callers:
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_offset
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_offset
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
  - drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_load_segments
```
**Symbols:**

```
ffffffff818a6980-ffffffff818a69f7: memset_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void memset_io(volatile void *a, int b, size_t c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/iomem.c (ffffffff818e97f0)
Location: arch/x86/lib/iomem.c:111
Inline: False
Direct callers:
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_offset
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_offset
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
  - drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_load_segments
```
**Symbols:**

```
ffffffff818e97f0-ffffffff818e9867: memset_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void memset_io(volatile void *a, int b, size_t c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/iomem.c (ffffffff81930c90)
Location: arch/x86/lib/iomem.c:111
Inline: False
Direct callers:
  - drivers/gpu/drm/tiny/simpledrm.c:simpledrm_primary_plane_helper_atomic_disable
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_offset
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_offset
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
  - drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_load_segments
```
**Symbols:**

```
ffffffff81930c90-ffffffff81930d07: memset_io (STB_GLOBAL)
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
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm/plat-omap/sram.c (c151b5f4)
Location: arch/arm/include/asm/io.h:318
Inline: True
Inline callers:
  - arch/arm/plat-omap/sram.c:omap_map_sram
```
</details>
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
<summary>In <code>aws</code>: ✅</summary>

```c
void memset_io(volatile void *a, int b, size_t c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/iomem.c (ffffffff815560b0)
Location: arch/x86/lib/iomem.c:61
Inline: False
```
**Symbols:**

```
ffffffff815560b0-ffffffff815560c0: memset_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void memset_io(volatile void *a, int b, size_t c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/iomem.c (ffffffff81546570)
Location: arch/x86/lib/iomem.c:61
Inline: False
Direct callers:
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_cpu_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_cpu_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
```
**Symbols:**

```
ffffffff81546570-ffffffff81546580: memset_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void memset_io(volatile void *a, int b, size_t c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/iomem.c (ffffffff81551df0)
Location: arch/x86/lib/iomem.c:61
Inline: False
Direct callers:
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_cpu_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_cpu_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
```
**Symbols:**

```
ffffffff81551df0-ffffffff81551e00: memset_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void memset_io(volatile void *a, int b, size_t c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/iomem.c (ffffffff8156bc80)
Location: arch/x86/lib/iomem.c:61
Inline: False
Direct callers:
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_cpu_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_cpu_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
```
**Symbols:**

```
ffffffff8156bc80-ffffffff8156bc90: memset_io (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
