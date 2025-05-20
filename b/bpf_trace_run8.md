# Function: <code>bpf_trace_run8</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void bpf_trace_run8(struct bpf_prog *prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4, u64 arg5, u64 arg6, u64 arg7);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811a4a00)
Location: kernel/trace/bpf_trace.c:1140
Inline: False
Direct callers:
  - mm/vmscan.c:__bpf_trace_mm_vmscan_inactive_list_is_low
  - mm/vmscan.c:__bpf_trace_mm_vmscan_lru_isolate
  - fs/jbd2/journal.c:__bpf_trace_jbd2_handle_stats
```
**Symbols:**

```
ffffffff811a4a00-ffffffff811a4a6a: bpf_trace_run8 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void bpf_trace_run8(struct bpf_prog *prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4, u64 arg5, u64 arg6, u64 arg7);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811b2ad0)
Location: kernel/trace/bpf_trace.c:1185
Inline: False
Direct callers:
  - mm/vmscan.c:__bpf_trace_mm_vmscan_inactive_list_is_low
  - mm/vmscan.c:__bpf_trace_mm_vmscan_lru_isolate
  - fs/jbd2/journal.c:__bpf_trace_jbd2_handle_stats
```
**Symbols:**

```
ffffffff811b2ad0-ffffffff811b2b3a: bpf_trace_run8 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void bpf_trace_run8(struct bpf_prog *prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4, u64 arg5, u64 arg6, u64 arg7);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811c1650)
Location: kernel/trace/bpf_trace.c:1354
Inline: False
Direct callers:
  - mm/vmscan.c:__bpf_trace_mm_vmscan_inactive_list_is_low
  - mm/vmscan.c:__bpf_trace_mm_vmscan_lru_isolate
  - fs/jbd2/journal.c:__bpf_trace_jbd2_handle_stats
  - drivers/i2c/i2c-core-smbus.c:__bpf_trace_smbus_reply
```
**Symbols:**

```
ffffffff811c1650-ffffffff811c170a: bpf_trace_run8 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void bpf_trace_run8(struct bpf_prog *prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4, u64 arg5, u64 arg6, u64 arg7);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811cce00)
Location: kernel/trace/bpf_trace.c:1378
Inline: False
Direct callers:
  - mm/vmscan.c:__bpf_trace_mm_vmscan_inactive_list_is_low
  - mm/vmscan.c:__bpf_trace_mm_vmscan_lru_isolate
  - fs/jbd2/journal.c:__bpf_trace_jbd2_handle_stats
  - drivers/i2c/i2c-core-smbus.c:__bpf_trace_smbus_reply
```
**Symbols:**

```
ffffffff811cce00-ffffffff811cceba: bpf_trace_run8 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void bpf_trace_run8(struct bpf_prog *prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4, u64 arg5, u64 arg6, u64 arg7);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811e8790)
Location: kernel/trace/bpf_trace.c:1872
Inline: False
Direct callers:
  - mm/vmscan.c:__bpf_trace_mm_vmscan_inactive_list_is_low
  - mm/vmscan.c:__bpf_trace_mm_vmscan_lru_isolate
  - fs/jbd2/journal.c:__bpf_trace_jbd2_handle_stats
  - drivers/i2c/i2c-core-smbus.c:__bpf_trace_smbus_reply
```
**Symbols:**

```
ffffffff811e8790-ffffffff811e884a: bpf_trace_run8 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void bpf_trace_run8(struct bpf_prog *prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4, u64 arg5, u64 arg6, u64 arg7);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811e7d20)
Location: kernel/trace/bpf_trace.c:2128
Inline: False
Direct callers:
  - mm/vmscan.c:__bpf_trace_mm_vmscan_inactive_list_is_low
  - mm/vmscan.c:__bpf_trace_mm_vmscan_lru_isolate
  - fs/jbd2/journal.c:__bpf_trace_jbd2_handle_stats
  - block/blk-iocost.c:__bpf_trace_iocost_iocg_forgive_debt
  - drivers/i2c/i2c-core-smbus.c:__bpf_trace_smbus_reply
```
**Symbols:**

```
ffffffff811e7d20-ffffffff811e7ddf: bpf_trace_run8 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void bpf_trace_run8(struct bpf_prog *prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4, u64 arg5, u64 arg6, u64 arg7);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811e8b40)
Location: kernel/trace/bpf_trace.c:1824
Inline: False
Direct callers:
  - mm/vmscan.c:__bpf_trace_mm_vmscan_inactive_list_is_low
  - mm/vmscan.c:__bpf_trace_mm_vmscan_lru_isolate
  - fs/jbd2/journal.c:__bpf_trace_jbd2_handle_stats
  - block/blk-iocost.c:__bpf_trace_iocost_iocg_forgive_debt
  - drivers/i2c/i2c-core-smbus.c:__bpf_trace_smbus_reply
```
**Symbols:**

```
ffffffff811e8b40-ffffffff811e8bf8: bpf_trace_run8 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void bpf_trace_run8(struct bpf_prog *prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4, u64 arg5, u64 arg6, u64 arg7);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff812197b0)
Location: kernel/trace/bpf_trace.c:1908
Inline: False
Direct callers:
  - mm/vmscan.c:__bpf_trace_mm_vmscan_lru_isolate
  - fs/jbd2/journal.c:__bpf_trace_jbd2_handle_stats
  - block/blk-iocost.c:__bpf_trace_iocost_iocg_forgive_debt
  - drivers/i2c/i2c-core-smbus.c:__bpf_trace_smbus_reply
```
**Symbols:**

```
ffffffff812197b0-ffffffff81219864: bpf_trace_run8 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void bpf_trace_run8(struct bpf_prog *prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4, u64 arg5, u64 arg6, u64 arg7);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff81256360)
Location: kernel/trace/bpf_trace.c:2089
Inline: False
Direct callers:
  - mm/vmscan.c:__bpf_trace_mm_vmscan_lru_isolate
  - fs/jbd2/journal.c:__bpf_trace_jbd2_handle_stats
  - block/blk-iocost.c:__bpf_trace_iocost_iocg_forgive_debt
  - drivers/i2c/i2c-core-smbus.c:__bpf_trace_smbus_reply
```
**Symbols:**

```
ffffffff81256360-ffffffff8125642d: bpf_trace_run8 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void bpf_trace_run8(struct bpf_prog *prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4, u64 arg5, u64 arg6, u64 arg7);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff812a78a0)
Location: kernel/trace/bpf_trace.c:2312
Inline: False
Direct callers:
  - mm/vmscan.c:__bpf_trace_mm_vmscan_lru_isolate
  - mm/khugepaged.c:__bpf_trace_mm_khugepaged_collapse_file
  - fs/jbd2/journal.c:__bpf_trace_jbd2_handle_stats
  - block/blk-iocost.c:__bpf_trace_iocost_iocg_forgive_debt
  - drivers/i2c/i2c-core-smbus.c:__bpf_trace_smbus_reply
```
**Symbols:**

```
ffffffff812a78a0-ffffffff812a7996: bpf_trace_run8 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void bpf_trace_run8(struct bpf_prog *prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4, u64 arg5, u64 arg6, u64 arg7);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff812c9b30)
Location: kernel/trace/bpf_trace.c:2321
Inline: False
Direct callers:
  - mm/vmscan.c:__bpf_trace_mm_vmscan_lru_isolate
  - mm/khugepaged.c:__bpf_trace_mm_khugepaged_collapse_file
  - fs/jbd2/journal.c:__bpf_trace_jbd2_handle_stats
  - block/blk-iocost.c:__bpf_trace_iocost_iocg_forgive_debt
  - drivers/i2c/i2c-core-smbus.c:__bpf_trace_smbus_reply
```
**Symbols:**

```
ffffffff812c9b30-ffffffff812c9c26: bpf_trace_run8 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void bpf_trace_run8(struct bpf_prog *prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4, u64 arg5, u64 arg6, u64 arg7);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff812e68a0)
Location: kernel/trace/bpf_trace.c:2426
Inline: False
Direct callers:
  - mm/rmap.c:__bpf_trace_mm_migrate_pages
  - mm/khugepaged.c:__bpf_trace_mm_khugepaged_collapse_file
  - fs/jbd2/journal.c:__bpf_trace_jbd2_handle_stats
  - block/blk-iocost.c:__bpf_trace_iocost_iocg_forgive_debt
  - drivers/i2c/i2c-core-smbus.c:__bpf_trace_smbus_reply
  - drivers/thermal/gov_power_allocator.c:__bpf_trace_thermal_power_allocator
```
**Symbols:**

```
ffffffff812e68a0-ffffffff812e6996: bpf_trace_run8 (STB_GLOBAL)
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
void bpf_trace_run8(struct bpf_prog *prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4, u64 arg5, u64 arg6, u64 arg7);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffff80001024e250)
Location: kernel/trace/bpf_trace.c:1378
Inline: False
Direct callers:
  - mm/vmscan.c:__bpf_trace_mm_vmscan_inactive_list_is_low
  - mm/vmscan.c:__bpf_trace_mm_vmscan_lru_isolate
  - fs/jbd2/journal.c:__bpf_trace_jbd2_handle_stats
  - drivers/i2c/i2c-core-smbus.c:__bpf_trace_smbus_reply
```
**Symbols:**

```
ffff80001024e250-ffff80001024e314: bpf_trace_run8 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void bpf_trace_run8(struct bpf_prog *prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4, u64 arg5, u64 arg6, u64 arg7);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (c047f41c)
Location: kernel/trace/bpf_trace.c:1378
Inline: False
Direct callers:
  - mm/vmscan.c:__bpf_trace_mm_vmscan_inactive_list_is_low
  - mm/vmscan.c:__bpf_trace_mm_vmscan_lru_isolate
  - fs/jbd2/journal.c:__bpf_trace_jbd2_handle_stats
  - drivers/i2c/i2c-core-smbus.c:__bpf_trace_smbus_reply
```
**Symbols:**

```
c047f41c-c047f558: bpf_trace_run8 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void bpf_trace_run8(struct bpf_prog *prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4, u64 arg5, u64 arg6, u64 arg7);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (c0000000002e8180)
Location: kernel/trace/bpf_trace.c:1378
Inline: False
Direct callers:
  - mm/vmscan.c:__bpf_trace_mm_vmscan_inactive_list_is_low
  - mm/vmscan.c:__bpf_trace_mm_vmscan_lru_isolate
  - fs/jbd2/journal.c:__bpf_trace_jbd2_handle_stats
  - drivers/i2c/i2c-core-smbus.c:__bpf_trace_smbus_reply
```
**Symbols:**

```
c0000000002e8180-c0000000002e8290: bpf_trace_run8 (STB_GLOBAL)
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
void bpf_trace_run8(struct bpf_prog *prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4, u64 arg5, u64 arg6, u64 arg7);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811c5420)
Location: kernel/trace/bpf_trace.c:1378
Inline: False
Direct callers:
  - mm/vmscan.c:__bpf_trace_mm_vmscan_inactive_list_is_low
  - mm/vmscan.c:__bpf_trace_mm_vmscan_lru_isolate
  - fs/jbd2/journal.c:__bpf_trace_jbd2_handle_stats
```
**Symbols:**

```
ffffffff811c5420-ffffffff811c54da: bpf_trace_run8 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void bpf_trace_run8(struct bpf_prog *prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4, u64 arg5, u64 arg6, u64 arg7);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811b8200)
Location: kernel/trace/bpf_trace.c:1378
Inline: False
Direct callers:
  - mm/vmscan.c:__bpf_trace_mm_vmscan_inactive_list_is_low
  - mm/vmscan.c:__bpf_trace_mm_vmscan_lru_isolate
  - fs/jbd2/journal.c:__bpf_trace_jbd2_handle_stats
```
**Symbols:**

```
ffffffff811b8200-ffffffff811b82ba: bpf_trace_run8 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void bpf_trace_run8(struct bpf_prog *prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4, u64 arg5, u64 arg6, u64 arg7);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811c31f0)
Location: kernel/trace/bpf_trace.c:1378
Inline: False
Direct callers:
  - mm/vmscan.c:__bpf_trace_mm_vmscan_inactive_list_is_low
  - mm/vmscan.c:__bpf_trace_mm_vmscan_lru_isolate
  - fs/jbd2/journal.c:__bpf_trace_jbd2_handle_stats
  - drivers/i2c/i2c-core-smbus.c:__bpf_trace_smbus_reply
```
**Symbols:**

```
ffffffff811c31f0-ffffffff811c32aa: bpf_trace_run8 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void bpf_trace_run8(struct bpf_prog *prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4, u64 arg5, u64 arg6, u64 arg7);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811d26a0)
Location: kernel/trace/bpf_trace.c:1378
Inline: False
Direct callers:
  - mm/vmscan.c:__bpf_trace_mm_vmscan_inactive_list_is_low
  - mm/vmscan.c:__bpf_trace_mm_vmscan_lru_isolate
  - fs/jbd2/journal.c:__bpf_trace_jbd2_handle_stats
  - drivers/i2c/i2c-core-smbus.c:__bpf_trace_smbus_reply
```
**Symbols:**

```
ffffffff811d26a0-ffffffff811d277b: bpf_trace_run8 (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
