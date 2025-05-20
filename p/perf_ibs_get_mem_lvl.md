# Function: <code>perf_ibs_get_mem_lvl</code>

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
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void perf_ibs_get_mem_lvl(union ibs_op_data2 *op_data2, union ibs_op_data3 *op_data3, struct perf_sample_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/ibs.c (ffffffff8100e6c0)
Location: arch/x86/events/amd/ibs.c:706
Inline: False
Direct callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_parse_ld_st_data
```
**Symbols:**

```
ffffffff8100e6c0-ffffffff8100e9b3: perf_ibs_get_mem_lvl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void perf_ibs_get_mem_lvl(union ibs_op_data2 *op_data2, union ibs_op_data3 *op_data3, struct perf_sample_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/ibs.c (ffffffff8100dc90)
Location: arch/x86/events/amd/ibs.c:705
Inline: False
Direct callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_parse_ld_st_data
```
**Symbols:**

```
ffffffff8100dc90-ffffffff8100df83: perf_ibs_get_mem_lvl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
__u64 perf_ibs_get_mem_lvl(union ibs_op_data2 *op_data2, union ibs_op_data3 *op_data3, struct perf_sample_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/ibs.c (ffffffff81013550)
Location: arch/x86/events/amd/ibs.c:764
Inline: False
Direct callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_parse_ld_st_data
```
**Symbols:**

```
ffffffff81013550-ffffffff810136de: perf_ibs_get_mem_lvl (STB_LOCAL)
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>__u64</code>
</li>
</ul>
</details>
</li>
</ul>
