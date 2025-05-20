# Function: <code>memory_block_size_bytes</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long unsigned int memory_block_size_bytes();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81069b10)
Location: arch/x86/mm/init_64.c:1222
Inline: False
Direct callers:
  - drivers/base/memory.c:get_memory_block_size
```
**Symbols:**

```
ffffffff81069b10-ffffffff81069ba7: memory_block_size_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long unsigned int memory_block_size_bytes();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81069890)
Location: arch/x86/mm/init_64.c:1154
Inline: False
Direct callers:
  - drivers/base/memory.c:get_memory_block_size
```
**Symbols:**

```
ffffffff81069890-ffffffff810698ee: memory_block_size_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long unsigned int memory_block_size_bytes();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8106d470)
Location: arch/x86/mm/init_64.c:1144
Inline: False
Direct callers:
  - drivers/base/memory.c:get_memory_block_size
```
**Symbols:**

```
ffffffff8106d470-ffffffff8106d4ce: memory_block_size_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long unsigned int memory_block_size_bytes();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8106ca90)
Location: arch/x86/mm/init_64.c:1322
Inline: False
```
**Symbols:**

```
ffffffff8106ca90-ffffffff8106caee: memory_block_size_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long unsigned int memory_block_size_bytes();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81071730)
Location: arch/x86/mm/init_64.c:1336
Inline: False
```
**Symbols:**

```
ffffffff81071730-ffffffff8107178e: memory_block_size_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
long unsigned int memory_block_size_bytes();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8169d770)
Location: arch/x86/mm/init_64.c:1390
Inline: False
Direct callers:
  - mm/memory_hotplug.c:check_hotplug_memory_range
```
**Symbols:**

```
ffffffff810749e4-ffffffff81074a08: memory_block_size_bytes.cold.21 (STB_LOCAL)
ffffffff810743e0-ffffffff8107444e: memory_block_size_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
long unsigned int memory_block_size_bytes();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff816bdf10)
Location: arch/x86/mm/init_64.c:1378
Inline: False
Direct callers:
  - mm/memory_hotplug.c:check_hotplug_memory_range
```
**Symbols:**

```
ffffffff8107a8f2-ffffffff8107a916: memory_block_size_bytes.cold.25 (STB_LOCAL)
ffffffff8107a2d0-ffffffff8107a33e: memory_block_size_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
long unsigned int memory_block_size_bytes();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff816f8310)
Location: arch/x86/mm/init_64.c:1435
Inline: False
Direct callers:
  - drivers/base/memory.c:remove_memory_block_devices
  - drivers/base/memory.c:remove_memory_block_devices
  - drivers/base/memory.c:create_memory_block_devices
  - drivers/base/memory.c:create_memory_block_devices
```
**Symbols:**

```
ffffffff8107e661-ffffffff8107e686: memory_block_size_bytes.cold (STB_LOCAL)
ffffffff8107e000-ffffffff8107e072: memory_block_size_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
long unsigned int memory_block_size_bytes();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8171c710)
Location: arch/x86/mm/init_64.c:1433
Inline: False
Direct callers:
  - drivers/base/node.c:register_mem_sect_under_node
  - drivers/base/memory.c:memory_dev_init
  - drivers/base/memory.c:remove_memory_block_devices
  - drivers/base/memory.c:remove_memory_block_devices
  - drivers/base/memory.c:create_memory_block_devices
  - drivers/base/memory.c:create_memory_block_devices
  - drivers/base/memory.c:block_size_bytes_show
```
**Symbols:**

```
ffffffff8107f6f1-ffffffff8107f716: memory_block_size_bytes.cold (STB_LOCAL)
ffffffff8107f090-ffffffff8107f102: memory_block_size_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
long unsigned int memory_block_size_bytes();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff817d8800)
Location: arch/x86/mm/init_64.c:1421
Inline: False
Direct callers:
  - mm/memory_hotplug.c:offline_and_remove_memory
  - mm/memory_hotplug.c:offline_and_remove_memory
  - drivers/base/node.c:register_mem_block_under_node_early
  - drivers/base/memory.c:memory_dev_init
  - drivers/base/memory.c:remove_memory_block_devices
  - drivers/base/memory.c:remove_memory_block_devices
  - drivers/base/memory.c:create_memory_block_devices
  - drivers/base/memory.c:create_memory_block_devices
  - drivers/base/memory.c:block_size_bytes_show
```
**Symbols:**

```
ffffffff81086639-ffffffff8108665e: memory_block_size_bytes.cold (STB_LOCAL)
ffffffff81085940-ffffffff810859b7: memory_block_size_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
long unsigned int memory_block_size_bytes();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff817ed200)
Location: arch/x86/mm/init_64.c:1476
Inline: False
Direct callers:
  - mm/memory_hotplug.c:offline_and_remove_memory
  - mm/memory_hotplug.c:offline_and_remove_memory
  - mm/memory_hotplug.c:offline_and_remove_memory
  - drivers/base/node.c:register_mem_block_under_node_early
  - drivers/base/memory.c:memory_dev_init
  - drivers/base/memory.c:remove_memory_block_devices
  - drivers/base/memory.c:remove_memory_block_devices
  - drivers/base/memory.c:create_memory_block_devices
  - drivers/base/memory.c:create_memory_block_devices
  - drivers/base/memory.c:block_size_bytes_show
```
**Symbols:**

```
ffffffff81bd92b3-ffffffff81bd92e0: memory_block_size_bytes.cold (STB_LOCAL)
ffffffff810869f0-ffffffff81086a79: memory_block_size_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
long unsigned int memory_block_size_bytes();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff817d19d0)
Location: arch/x86/mm/init_64.c:1519
Inline: False
Direct callers:
  - mm/memory_hotplug.c:offline_and_remove_memory
  - mm/memory_hotplug.c:offline_and_remove_memory
  - mm/memory_hotplug.c:offline_and_remove_memory
  - mm/memory_hotplug.c:try_remove_memory
  - mm/memory_hotplug.c:add_memory_resource
  - drivers/base/node.c:register_mem_block_under_node_early
  - drivers/base/memory.c:memory_dev_init
  - drivers/base/memory.c:remove_memory_block_devices
  - drivers/base/memory.c:remove_memory_block_devices
  - drivers/base/memory.c:create_memory_block_devices
  - drivers/base/memory.c:create_memory_block_devices
  - drivers/base/memory.c:block_size_bytes_show
```
**Symbols:**

```
ffffffff81bcb238-ffffffff81bcb265: memory_block_size_bytes.cold (STB_LOCAL)
ffffffff810876e0-ffffffff81087763: memory_block_size_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
long unsigned int memory_block_size_bytes();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8185c770)
Location: arch/x86/mm/init_64.c:1519
Inline: False
Direct callers:
  - mm/memory_hotplug.c:offline_and_remove_memory
  - mm/memory_hotplug.c:offline_and_remove_memory
  - mm/memory_hotplug.c:offline_and_remove_memory
  - mm/memory_hotplug.c:try_remove_memory
  - mm/memory_hotplug.c:mhp_supports_memmap_on_memory
  - drivers/base/node.c:register_mem_block_under_node_early
  - drivers/base/memory.c:memory_group_register_dynamic
  - drivers/base/memory.c:memory_dev_init
  - drivers/base/memory.c:remove_memory_block_devices
  - drivers/base/memory.c:remove_memory_block_devices
  - drivers/base/memory.c:create_memory_block_devices
  - drivers/base/memory.c:create_memory_block_devices
  - drivers/base/memory.c:block_size_bytes_show
```
**Symbols:**

```
ffffffff81ca08b1-ffffffff81ca08de: memory_block_size_bytes.cold (STB_LOCAL)
ffffffff81096a40-ffffffff81096ac3: memory_block_size_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
long unsigned int memory_block_size_bytes();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff819a38f0)
Location: arch/x86/mm/init_64.c:1519
Inline: False
Direct callers:
  - mm/memory_hotplug.c:offline_and_remove_memory
  - mm/memory_hotplug.c:offline_and_remove_memory
  - mm/memory_hotplug.c:offline_and_remove_memory
  - mm/memory_hotplug.c:try_remove_memory
  - mm/memory_hotplug.c:mhp_supports_memmap_on_memory
  - drivers/base/node.c:register_mem_block_under_node_early
  - drivers/base/memory.c:memory_group_register_dynamic
  - drivers/base/memory.c:memory_dev_init
  - drivers/base/memory.c:remove_memory_block_devices
  - drivers/base/memory.c:remove_memory_block_devices
  - drivers/base/memory.c:create_memory_block_devices
  - drivers/base/memory.c:create_memory_block_devices
  - drivers/base/memory.c:block_size_bytes_show
```
**Symbols:**

```
ffffffff81e4fdda-ffffffff81e4fe0c: memory_block_size_bytes.cold (STB_LOCAL)
ffffffff810a94f0-ffffffff810a9587: memory_block_size_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long unsigned int memory_block_size_bytes();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff810c28b0)
Location: arch/x86/mm/init_64.c:1479
Inline: False
Direct callers:
  - mm/memory_hotplug.c:offline_and_remove_memory
  - mm/memory_hotplug.c:offline_and_remove_memory
  - mm/memory_hotplug.c:offline_and_remove_memory
  - mm/memory_hotplug.c:try_remove_memory
  - mm/memory_hotplug.c:mhp_supports_memmap_on_memory
  - drivers/base/node.c:register_mem_block_under_node_early
  - drivers/base/memory.c:memory_group_register_dynamic
  - drivers/base/memory.c:memory_dev_init
  - drivers/base/memory.c:remove_memory_block_devices
  - drivers/base/memory.c:remove_memory_block_devices
  - drivers/base/memory.c:create_memory_block_devices
  - drivers/base/memory.c:create_memory_block_devices
  - drivers/base/memory.c:block_size_bytes_show
```
**Symbols:**

```
ffffffff810c28b0-ffffffff810c297a: memory_block_size_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long unsigned int memory_block_size_bytes();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff810c5f90)
Location: arch/x86/mm/init_64.c:1479
Inline: False
Direct callers:
  - mm/memory_hotplug.c:offline_and_remove_memory
  - mm/memory_hotplug.c:offline_and_remove_memory
  - mm/memory_hotplug.c:offline_and_remove_memory
  - mm/memory_hotplug.c:try_remove_memory
  - mm/memory_hotplug.c:mhp_supports_memmap_on_memory
  - drivers/base/node.c:register_mem_block_under_node_early
  - drivers/base/memory.c:memory_group_register_dynamic
  - drivers/base/memory.c:memory_dev_init
  - drivers/base/memory.c:remove_memory_block_devices
  - drivers/base/memory.c:remove_memory_block_devices
  - drivers/base/memory.c:create_memory_block_devices
  - drivers/base/memory.c:create_memory_block_devices
  - drivers/base/memory.c:block_size_bytes_show
```
**Symbols:**

```
ffffffff810c5f90-ffffffff810c605a: memory_block_size_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long unsigned int memory_block_size_bytes();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff810ce3e0)
Location: arch/x86/mm/init_64.c:1479
Inline: False
Direct callers:
  - mm/memory_hotplug.c:offline_and_remove_memory
  - mm/memory_hotplug.c:offline_and_remove_memory
  - mm/memory_hotplug.c:offline_and_remove_memory
  - mm/memory_hotplug.c:try_remove_memory
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:create_altmaps_and_memory_blocks
  - mm/memory_hotplug.c:create_altmaps_and_memory_blocks
  - mm/memory_hotplug.c:remove_memory_blocks_and_altmaps
  - mm/memory_hotplug.c:set_memmap_mode
  - mm/memory_hotplug.c:set_memmap_mode
  - drivers/base/node.c:register_mem_block_under_node_early
  - drivers/base/memory.c:memory_group_register_dynamic
  - drivers/base/memory.c:memory_dev_init
  - drivers/base/memory.c:remove_memory_block_devices
  - drivers/base/memory.c:remove_memory_block_devices
  - drivers/base/memory.c:create_memory_block_devices
  - drivers/base/memory.c:create_memory_block_devices
  - drivers/base/memory.c:block_size_bytes_show
```
**Symbols:**

```
ffffffff810ce3e0-ffffffff810ce4aa: memory_block_size_bytes (STB_GLOBAL)
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
long unsigned int memory_block_size_bytes();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffff800010910360)
Location: drivers/base/memory.c:97
Inline: False
Direct callers:
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:add_memory_resource
  - drivers/base/node.c:register_mem_sect_under_node
  - drivers/base/memory.c:memory_dev_init
  - drivers/base/memory.c:remove_memory_block_devices
  - drivers/base/memory.c:remove_memory_block_devices
  - drivers/base/memory.c:create_memory_block_devices
  - drivers/base/memory.c:create_memory_block_devices
  - drivers/base/memory.c:block_size_bytes_show
```
**Symbols:**

```
ffff800010910360-ffff80001091037c: memory_block_size_bytes (STB_WEAK)
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
long unsigned int memory_block_size_bytes();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/setup_64.c (c0000000000312a0)
Location: arch/powerpc/kernel/setup_64.c:796
Inline: False
Direct callers:
  - arch/powerpc/platforms/powernv/memtrace.c:memtrace_init_regions_runtime
  - drivers/base/node.c:register_mem_sect_under_node
  - drivers/base/memory.c:memory_dev_init
  - drivers/base/memory.c:remove_memory_block_devices
  - drivers/base/memory.c:remove_memory_block_devices
  - drivers/base/memory.c:create_memory_block_devices
  - drivers/base/memory.c:create_memory_block_devices
  - drivers/base/memory.c:block_size_bytes_show
```
**Symbols:**

```
c0000000000312a0-c0000000000312f8: memory_block_size_bytes (STB_GLOBAL)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
long unsigned int memory_block_size_bytes();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff816e2a40)
Location: arch/x86/mm/init_64.c:1433
Inline: False
Direct callers:
  - drivers/base/node.c:register_mem_sect_under_node
  - drivers/base/memory.c:memory_dev_init
  - drivers/base/memory.c:remove_memory_block_devices
  - drivers/base/memory.c:remove_memory_block_devices
  - drivers/base/memory.c:create_memory_block_devices
  - drivers/base/memory.c:create_memory_block_devices
  - drivers/base/memory.c:block_size_bytes_show
```
**Symbols:**

```
ffffffff8107e6f1-ffffffff8107e716: memory_block_size_bytes.cold (STB_LOCAL)
ffffffff8107e090-ffffffff8107e102: memory_block_size_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
long unsigned int memory_block_size_bytes();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff816bd080)
Location: arch/x86/mm/init_64.c:1433
Inline: False
Direct callers:
  - drivers/base/node.c:register_mem_sect_under_node
  - drivers/base/memory.c:memory_dev_init
  - drivers/base/memory.c:remove_memory_block_devices
  - drivers/base/memory.c:remove_memory_block_devices
  - drivers/base/memory.c:create_memory_block_devices
  - drivers/base/memory.c:create_memory_block_devices
  - drivers/base/memory.c:block_size_bytes_show
```
**Symbols:**

```
ffffffff8106d7e7-ffffffff8106d80c: memory_block_size_bytes.cold (STB_LOCAL)
ffffffff8106d2b0-ffffffff8106d322: memory_block_size_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
long unsigned int memory_block_size_bytes();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8170fbd0)
Location: arch/x86/mm/init_64.c:1433
Inline: False
Direct callers:
  - drivers/base/node.c:register_mem_sect_under_node
  - drivers/base/memory.c:memory_dev_init
  - drivers/base/memory.c:remove_memory_block_devices
  - drivers/base/memory.c:remove_memory_block_devices
  - drivers/base/memory.c:create_memory_block_devices
  - drivers/base/memory.c:create_memory_block_devices
  - drivers/base/memory.c:block_size_bytes_show
```
**Symbols:**

```
ffffffff8107e6a1-ffffffff8107e6c6: memory_block_size_bytes.cold (STB_LOCAL)
ffffffff8107e040-ffffffff8107e0b2: memory_block_size_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
long unsigned int memory_block_size_bytes();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8172ad30)
Location: arch/x86/mm/init_64.c:1433
Inline: False
Direct callers:
  - drivers/base/node.c:register_mem_sect_under_node
  - drivers/base/memory.c:memory_dev_init
  - drivers/base/memory.c:remove_memory_block_devices
  - drivers/base/memory.c:remove_memory_block_devices
  - drivers/base/memory.c:create_memory_block_devices
  - drivers/base/memory.c:create_memory_block_devices
  - drivers/base/memory.c:block_size_bytes_show
```
**Symbols:**

```
ffffffff81080791-ffffffff810807b6: memory_block_size_bytes.cold (STB_LOCAL)
ffffffff81080130-ffffffff810801a2: memory_block_size_bytes (STB_GLOBAL)
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
