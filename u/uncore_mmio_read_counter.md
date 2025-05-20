# Function: <code>uncore_mmio_read_counter</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
u64 uncore_mmio_read_counter(struct intel_uncore_box *box, struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff81017170)
Location: arch/x86/events/intel/uncore.c:129
Inline: False
```
**Symbols:**

```
ffffffff81017170-ffffffff81017195: uncore_mmio_read_counter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u64 uncore_mmio_read_counter(struct intel_uncore_box *box, struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff81017b20)
Location: arch/x86/events/intel/uncore.c:129
Inline: False
```
**Symbols:**

```
ffffffff81017b20-ffffffff81017b45: uncore_mmio_read_counter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u64 uncore_mmio_read_counter(struct intel_uncore_box *box, struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff810196d0)
Location: arch/x86/events/intel/uncore.c:129
Inline: False
```
**Symbols:**

```
ffffffff810196d0-ffffffff810196f5: uncore_mmio_read_counter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
u64 uncore_mmio_read_counter(struct intel_uncore_box *box, struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/uncore.c (0)
Location: arch/x86/events/intel/uncore.c:131
Inline: False
```
**Symbols:**

```
ffffffff81bd25d2-ffffffff81bd25ed: uncore_mmio_read_counter.cold (STB_LOCAL)
ffffffff81019d10-ffffffff81019d6c: uncore_mmio_read_counter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
u64 uncore_mmio_read_counter(struct intel_uncore_box *box, struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/uncore.c (0)
Location: arch/x86/events/intel/uncore.c:148
Inline: False
```
**Symbols:**

```
ffffffff81bc47c4-ffffffff81bc47df: uncore_mmio_read_counter.cold (STB_LOCAL)
ffffffff8101b090-ffffffff8101b0ec: uncore_mmio_read_counter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
u64 uncore_mmio_read_counter(struct intel_uncore_box *box, struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/uncore.c (0)
Location: arch/x86/events/intel/uncore.c:148
Inline: False
```
**Symbols:**

```
ffffffff81c96846-ffffffff81c96889: uncore_mmio_read_counter.cold (STB_LOCAL)
ffffffff8101d9c0-ffffffff8101da2f: uncore_mmio_read_counter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
u64 uncore_mmio_read_counter(struct intel_uncore_box *box, struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/uncore.c (0)
Location: arch/x86/events/intel/uncore.c:148
Inline: False
```
**Symbols:**

```
ffffffff81e45cfd-ffffffff81e45d12: uncore_mmio_read_counter.cold (STB_LOCAL)
ffffffff810203e0-ffffffff81020489: uncore_mmio_read_counter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
u64 uncore_mmio_read_counter(struct intel_uncore_box *box, struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/uncore.c (0)
Location: arch/x86/events/intel/uncore.c:148
Inline: False
```
**Symbols:**

```
ffffffff82051340-ffffffff82051355: uncore_mmio_read_counter.cold (STB_LOCAL)
ffffffff81024ce0-ffffffff81024d89: uncore_mmio_read_counter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
u64 uncore_mmio_read_counter(struct intel_uncore_box *box, struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/uncore.c (0)
Location: arch/x86/events/intel/uncore.c:163
Inline: False
```
**Symbols:**

```
ffffffff820cf772-ffffffff820cf787: uncore_mmio_read_counter.cold (STB_LOCAL)
ffffffff81024be0-ffffffff81024c89: uncore_mmio_read_counter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
u64 uncore_mmio_read_counter(struct intel_uncore_box *box, struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/uncore.c (0)
Location: arch/x86/events/intel/uncore.c:163
Inline: False
```
**Symbols:**

```
ffffffff821aa0e0-ffffffff821aa0f5: uncore_mmio_read_counter.cold (STB_LOCAL)
ffffffff8102ad40-ffffffff8102ade9: uncore_mmio_read_counter (STB_GLOBAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
u64 uncore_mmio_read_counter(struct intel_uncore_box *box, struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff81017b20)
Location: arch/x86/events/intel/uncore.c:129
Inline: False
```
**Symbols:**

```
ffffffff81017b20-ffffffff81017b45: uncore_mmio_read_counter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u64 uncore_mmio_read_counter(struct intel_uncore_box *box, struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff81016f70)
Location: arch/x86/events/intel/uncore.c:129
Inline: False
```
**Symbols:**

```
ffffffff81016f70-ffffffff81016f95: uncore_mmio_read_counter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u64 uncore_mmio_read_counter(struct intel_uncore_box *box, struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff81017ae0)
Location: arch/x86/events/intel/uncore.c:129
Inline: False
```
**Symbols:**

```
ffffffff81017ae0-ffffffff81017b05: uncore_mmio_read_counter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u64 uncore_mmio_read_counter(struct intel_uncore_box *box, struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff81017d20)
Location: arch/x86/events/intel/uncore.c:129
Inline: False
```
**Symbols:**

```
ffffffff81017d20-ffffffff81017d45: uncore_mmio_read_counter (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
