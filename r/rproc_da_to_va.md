# Function: <code>rproc_da_to_va</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *rproc_da_to_va(struct rproc *rproc, u64 da, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff818f3580)
Location: drivers/remoteproc/remoteproc_core.c:190
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_trigger_recovery
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_trace_read
  - drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_find_loaded_rsc_table
  - drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_load_segments
```
**Symbols:**

```
ffffffff818f3580-ffffffff818f3606: rproc_da_to_va (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *rproc_da_to_va(struct rproc *rproc, u64 da, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff819c8ec0)
Location: drivers/remoteproc/remoteproc_core.c:193
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_coredump
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_trace_read
  - drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_find_loaded_rsc_table
  - drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_load_segments
```
**Symbols:**

```
ffffffff819c8ec0-ffffffff819c8f46: rproc_da_to_va (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *rproc_da_to_va(struct rproc *rproc, u64 da, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff819c8a80)
Location: drivers/remoteproc/remoteproc_core.c:192
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_trace_read
  - drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_find_loaded_rsc_table
  - drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_load_segments
```
**Symbols:**

```
ffffffff819c8a80-ffffffff819c8b06: rproc_da_to_va (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void *rproc_da_to_va(struct rproc *rproc, u64 da, size_t len, bool *is_iomem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff819aded0)
Location: drivers/remoteproc/remoteproc_core.c:192
Inline: True
Direct callers:
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_trace_read
  - drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_find_loaded_rsc_table
  - drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_load_segments
```
**Symbols:**

```
ffffffff819aded0-ffffffff819adf6d: rproc_da_to_va (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void *rproc_da_to_va(struct rproc *rproc, u64 da, size_t len, bool *is_iomem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff81a5c574)
Location: drivers/remoteproc/remoteproc_core.c:194
Inline: True
Direct callers:
  - drivers/remoteproc/remoteproc_coredump.c:rproc_copy_segment
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_trace_read
  - drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_find_loaded_rsc_table
  - drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_load_segments
```
**Symbols:**

```
ffffffff81d31d5f-ffffffff81d31d7b: rproc_da_to_va.cold (STB_LOCAL)
ffffffff81a5c530-ffffffff81a5c5e5: rproc_da_to_va (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void *rproc_da_to_va(struct rproc *rproc, u64 da, size_t len, bool *is_iomem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff81bcc590)
Location: drivers/remoteproc/remoteproc_core.c:194
Inline: True
Direct callers:
  - drivers/remoteproc/remoteproc_coredump.c:rproc_copy_segment
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_trace_read
  - drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_find_loaded_rsc_table
  - drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_load_segments
```
**Symbols:**

```
ffffffff81efe25c-ffffffff81efe280: rproc_da_to_va.cold (STB_LOCAL)
ffffffff81bcc540-ffffffff81bcc60f: rproc_da_to_va (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void *rproc_da_to_va(struct rproc *rproc, u64 da, size_t len, bool *is_iomem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff81d768c0)
Location: drivers/remoteproc/remoteproc_core.c:193
Inline: True
Direct callers:
  - drivers/remoteproc/remoteproc_coredump.c:rproc_copy_segment
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_trace_read
  - drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_find_loaded_rsc_table
  - drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_load_segments
```
**Symbols:**

```
ffffffff820aa28d-ffffffff820aa2b1: rproc_da_to_va.cold (STB_LOCAL)
ffffffff81d76870-ffffffff81d7693f: rproc_da_to_va (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void *rproc_da_to_va(struct rproc *rproc, u64 da, size_t len, bool *is_iomem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff81de4800)
Location: drivers/remoteproc/remoteproc_core.c:193
Inline: True
Direct callers:
  - drivers/remoteproc/remoteproc_coredump.c:rproc_copy_segment
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_trace_read
  - drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_find_loaded_rsc_table
  - drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_load_segments
```
**Symbols:**

```
ffffffff8212b78c-ffffffff8212b7b0: rproc_da_to_va.cold (STB_LOCAL)
ffffffff81de47b0-ffffffff81de487f: rproc_da_to_va (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void *rproc_da_to_va(struct rproc *rproc, u64 da, size_t len, bool *is_iomem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff81e9a8f0)
Location: drivers/remoteproc/remoteproc_core.c:193
Inline: True
Direct callers:
  - drivers/remoteproc/remoteproc_coredump.c:rproc_copy_segment
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_trace_read
  - drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_find_loaded_rsc_table
  - drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_load_segments
```
**Symbols:**

```
ffffffff8220d3b3-ffffffff8220d3d7: rproc_da_to_va.cold (STB_LOCAL)
ffffffff81e9a8a0-ffffffff81e9a96f: rproc_da_to_va (STB_GLOBAL)
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
void *rproc_da_to_va(struct rproc *rproc, u64 da, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffff800010b7f1b8)
Location: drivers/remoteproc/remoteproc_core.c:190
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_trigger_recovery
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_trace_read
  - drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_find_loaded_rsc_table
  - drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_load_segments
```
**Symbols:**

```
ffff800010b7f1b8-ffff800010b7f274: rproc_da_to_va (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *rproc_da_to_va(struct rproc *rproc, u64 da, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (c0c62970)
Location: drivers/remoteproc/remoteproc_core.c:190
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_trigger_recovery
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_trace_read
  - drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_find_loaded_rsc_table
  - drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_load_segments
```
**Symbols:**

```
c0c62970-c0c62a20: rproc_da_to_va (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *rproc_da_to_va(struct rproc *rproc, u64 da, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (c000000000c5b340)
Location: drivers/remoteproc/remoteproc_core.c:190
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_trigger_recovery
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_trace_read
  - drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_find_loaded_rsc_table
  - drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_load_segments
```
**Symbols:**

```
c000000000c5b340-c000000000c5b438: rproc_da_to_va (STB_GLOBAL)
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
void *rproc_da_to_va(struct rproc *rproc, u64 da, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff818948b0)
Location: drivers/remoteproc/remoteproc_core.c:190
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_trigger_recovery
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_trace_read
  - drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_find_loaded_rsc_table
  - drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_load_segments
```
**Symbols:**

```
ffffffff818948b0-ffffffff81894936: rproc_da_to_va (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *rproc_da_to_va(struct rproc *rproc, u64 da, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff81905010)
Location: drivers/remoteproc/remoteproc_core.c:190
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_trigger_recovery
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_trace_read
  - drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_find_loaded_rsc_table
  - drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_load_segments
```
**Symbols:**

```
ffffffff81905010-ffffffff81905096: rproc_da_to_va (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int len</code> ➡️ <code>size_t len</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool *is_iomem</code>
</li>
</ul>
</details>
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
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
