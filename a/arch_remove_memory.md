# Function: <code>arch_remove_memory</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int arch_remove_memory(u64 start, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81818d00)
Location: arch/x86/mm/init_64.c:1017
Inline: False
Direct callers:
  - kernel/memremap.c:devm_memremap_pages_release
  - mm/memory_hotplug.c:remove_memory
```
**Symbols:**

```
ffffffff81818d00-ffffffff81818dbf: arch_remove_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int arch_remove_memory(u64 start, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff818927e0)
Location: arch/x86/mm/init_64.c:959
Inline: False
Direct callers:
  - kernel/memremap.c:devm_memremap_pages_release
  - mm/memory_hotplug.c:remove_memory
```
**Symbols:**

```
ffffffff818927e0-ffffffff818928b9: arch_remove_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int arch_remove_memory(u64 start, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff818c7130)
Location: arch/x86/mm/init_64.c:949
Inline: False
Direct callers:
  - kernel/memremap.c:devm_memremap_pages_release
  - mm/memory_hotplug.c:remove_memory
```
**Symbols:**

```
ffffffff818c7130-ffffffff818c7203: arch_remove_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int arch_remove_memory(u64 start, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff818fe8a0)
Location: arch/x86/mm/init_64.c:1127
Inline: False
Direct callers:
  - kernel/memremap.c:devm_memremap_pages_release
  - mm/memory_hotplug.c:remove_memory
```
**Symbols:**

```
ffffffff818fe8a0-ffffffff818fe954: arch_remove_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int arch_remove_memory(u64 start, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff819889d0)
Location: arch/x86/mm/init_64.c:1135
Inline: False
Direct callers:
  - kernel/memremap.c:devm_memremap_pages_release
  - mm/memory_hotplug.c:remove_memory
  - mm/hmm.c:hmm_devmem_release
```
**Symbols:**

```
ffffffff819889d0-ffffffff81988a84: arch_remove_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int arch_remove_memory(u64 start, u64 size, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff819e5320)
Location: arch/x86/mm/init_64.c:1151
Inline: False
Direct callers:
  - kernel/memremap.c:devm_memremap_pages_release
  - mm/memory_hotplug.c:remove_memory
  - mm/hmm.c:hmm_devmem_release
```
**Symbols:**

```
ffffffff819e5320-ffffffff819e53dd: arch_remove_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int arch_remove_memory(int nid, u64 start, u64 size, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81a20540)
Location: arch/x86/mm/init_64.c:1144
Inline: False
Direct callers:
  - kernel/memremap.c:devm_memremap_pages_release
  - mm/memory_hotplug.c:__remove_memory
```
**Symbols:**

```
ffffffff81a20540-ffffffff81a205fa: arch_remove_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void arch_remove_memory(int nid, u64 start, u64 size, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81a90aef)
Location: arch/x86/mm/init_64.c:1210
Inline: False
Direct callers:
  - mm/memory_hotplug.c:try_remove_memory
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memremap.c:devm_memremap_pages_release
```
**Symbols:**

```
ffffffff81a90aef-ffffffff81a90b7d: arch_remove_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void arch_remove_memory(int nid, u64 start, u64 size, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81ac7e6f)
Location: arch/x86/mm/init_64.c:1210
Inline: False
Direct callers:
  - mm/memory_hotplug.c:try_remove_memory
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memremap.c:memunmap_pages
```
**Symbols:**

```
ffffffff81ac7e6f-ffffffff81ac7eb9: arch_remove_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void arch_remove_memory(int nid, u64 start, u64 size, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81bc0963)
Location: arch/x86/mm/init_64.c:1218
Inline: False
Direct callers:
  - mm/memory_hotplug.c:try_remove_memory
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memremap.c:memunmap_pages
```
**Symbols:**

```
ffffffff81bc0963-ffffffff81bc09b3: arch_remove_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void arch_remove_memory(int nid, u64 start, u64 size, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81c399f5)
Location: arch/x86/mm/init_64.c:1212
Inline: False
Direct callers:
  - mm/memory_hotplug.c:try_remove_memory
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memremap.c:pageunmap_range
```
**Symbols:**

```
ffffffff81c399f5-ffffffff81c39a45: arch_remove_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void arch_remove_memory(int nid, u64 start, u64 size, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81c2be85)
Location: arch/x86/mm/init_64.c:1257
Inline: False
Direct callers:
  - mm/memory_hotplug.c:try_remove_memory
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memremap.c:memunmap_pages
```
**Symbols:**

```
ffffffff81c2be85-ffffffff81c2bed5: arch_remove_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void arch_remove_memory(u64 start, u64 size, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81d4a612)
Location: arch/x86/mm/init_64.c:1258
Inline: False
Direct callers:
  - mm/memory_hotplug.c:try_remove_memory
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memremap.c:memunmap_pages
```
**Symbols:**

```
ffffffff81d4a612-ffffffff81d4a659: arch_remove_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void arch_remove_memory(u64 start, u64 size, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81f19c8a)
Location: arch/x86/mm/init_64.c:1258
Inline: False
Direct callers:
  - mm/memory_hotplug.c:try_remove_memory
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memremap.c:memunmap_pages
```
**Symbols:**

```
ffffffff81f19c8a-ffffffff81f19cda: arch_remove_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void arch_remove_memory(u64 start, u64 size, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff820c18f0)
Location: arch/x86/mm/init_64.c:1259
Inline: False
Direct callers:
  - mm/memory_hotplug.c:try_remove_memory
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memremap.c:memunmap_pages
```
**Symbols:**

```
ffffffff820c18f0-ffffffff820c1940: arch_remove_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void arch_remove_memory(u64 start, u64 size, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff821455c0)
Location: arch/x86/mm/init_64.c:1259
Inline: False
Direct callers:
  - mm/memory_hotplug.c:try_remove_memory
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memremap.c:memunmap_pages
```
**Symbols:**

```
ffffffff821455c0-ffffffff82145610: arch_remove_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void arch_remove_memory(u64 start, u64 size, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff82227ce0)
Location: arch/x86/mm/init_64.c:1259
Inline: False
Direct callers:
  - mm/memory_hotplug.c:try_remove_memory
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:create_altmaps_and_memory_blocks
  - mm/memory_hotplug.c:remove_memory_blocks_and_altmaps
  - mm/memremap.c:memunmap_pages
```
**Symbols:**

```
ffffffff82227ce0-ffffffff82227d30: arch_remove_memory (STB_GLOBAL)
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
void arch_remove_memory(int nid, u64 start, u64 size, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm64/mm/mmu.c (ffff8000100af6e0)
Location: arch/arm64/mm/mmu.c:1067
Inline: False
Direct callers:
  - mm/memory_hotplug.c:add_memory_resource
```
**Symbols:**

```
ffff8000100af6e0-ffff8000100af724: arch_remove_memory (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void arch_remove_memory(int nid, u64 start, u64 size, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/powerpc/mm/mem.c (c000000000087740)
Location: arch/powerpc/mm/mem.c:150
Inline: False
Direct callers:
  - mm/memory_hotplug.c:try_remove_memory
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memremap.c:memunmap_pages
```
**Symbols:**

```
c000000000087740-c00000000008780c: arch_remove_memory (STB_GLOBAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
void arch_remove_memory(int nid, u64 start, u64 size, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81a66cdf)
Location: arch/x86/mm/init_64.c:1210
Inline: False
Direct callers:
  - mm/memory_hotplug.c:try_remove_memory
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memremap.c:memunmap_pages
```
**Symbols:**

```
ffffffff81a66cdf-ffffffff81a66d29: arch_remove_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void arch_remove_memory(int nid, u64 start, u64 size, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81a2379f)
Location: arch/x86/mm/init_64.c:1210
Inline: False
Direct callers:
  - mm/memory_hotplug.c:try_remove_memory
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memremap.c:memunmap_pages
```
**Symbols:**

```
ffffffff81a2379f-ffffffff81a237e9: arch_remove_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void arch_remove_memory(int nid, u64 start, u64 size, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81ad30ef)
Location: arch/x86/mm/init_64.c:1210
Inline: False
Direct callers:
  - mm/memory_hotplug.c:try_remove_memory
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memremap.c:memunmap_pages
```
**Symbols:**

```
ffffffff81ad30ef-ffffffff81ad3139: arch_remove_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void arch_remove_memory(int nid, u64 start, u64 size, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81adf5ef)
Location: arch/x86/mm/init_64.c:1210
Inline: False
Direct callers:
  - mm/memory_hotplug.c:try_remove_memory
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memremap.c:memunmap_pages
```
**Symbols:**

```
ffffffff81adf5ef-ffffffff81adf639: arch_remove_memory (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct vmem_altmap *altmap</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int nid</code>
</li>
<li>
<b>Param reordered. </b>
<code>start, size, altmap</code> ➡️ <code>nid, start, size, altmap</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int nid</code>
</li>
<li>
<b>Param reordered. </b>
<code>nid, start, size, altmap</code> ➡️ <code>start, size, altmap</code>
</li>
</ul>
</details>
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
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
