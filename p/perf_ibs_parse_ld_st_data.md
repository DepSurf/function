# Function: <code>perf_ibs_parse_ld_st_data</code>

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
void perf_ibs_parse_ld_st_data(__u64 sample_type, struct perf_ibs_data *ibs_data, struct perf_sample_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/ibs.c (ffffffff8100e9d0)
Location: arch/x86/events/amd/ibs.c:952
Inline: False
Direct callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
```
**Symbols:**

```
ffffffff8100e9d0-ffffffff8100eccf: perf_ibs_parse_ld_st_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void perf_ibs_parse_ld_st_data(__u64 sample_type, struct perf_ibs_data *ibs_data, struct perf_sample_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/ibs.c (ffffffff8100dfa0)
Location: arch/x86/events/amd/ibs.c:951
Inline: False
Direct callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
```
**Symbols:**

```
ffffffff8100dfa0-ffffffff8100e2a2: perf_ibs_parse_ld_st_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void perf_ibs_parse_ld_st_data(__u64 sample_type, struct perf_ibs_data *ibs_data, struct perf_sample_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/ibs.c (ffffffff810136f0)
Location: arch/x86/events/amd/ibs.c:960
Inline: False
Direct callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
```
**Symbols:**

```
ffffffff810136f0-ffffffff810139f4: perf_ibs_parse_ld_st_data (STB_LOCAL)
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
