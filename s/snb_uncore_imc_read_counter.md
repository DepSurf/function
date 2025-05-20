# Function: <code>snb_uncore_imc_read_counter</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
u64 snb_uncore_imc_read_counter(struct intel_uncore_box *box, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_snb.c (ffffffff81018bd0)
Location: arch/x86/events/intel/uncore_snb.c:245
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_event_start
```
**Symbols:**

```
ffffffff81018bd0-ffffffff81018bec: snb_uncore_imc_read_counter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
u64 snb_uncore_imc_read_counter(struct intel_uncore_box *box, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_snb.c (ffffffff81018268)
Location: arch/x86/events/intel/uncore_snb.c:331
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_event_start
```
**Symbols:**

```
ffffffff81017f40-ffffffff81017f5c: snb_uncore_imc_read_counter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
u64 snb_uncore_imc_read_counter(struct intel_uncore_box *box, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_snb.c (ffffffff8101843b)
Location: arch/x86/events/intel/uncore_snb.c:335
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_event_start
```
**Symbols:**

```
ffffffff81018150-ffffffff8101816c: snb_uncore_imc_read_counter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
u64 snb_uncore_imc_read_counter(struct intel_uncore_box *box, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_snb.c (ffffffff81016917)
Location: arch/x86/events/intel/uncore_snb.c:335
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_event_start
```
**Symbols:**

```
ffffffff81016650-ffffffff8101666c: snb_uncore_imc_read_counter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
u64 snb_uncore_imc_read_counter(struct intel_uncore_box *box, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_snb.c (ffffffff8101719b)
Location: arch/x86/events/intel/uncore_snb.c:336
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_event_start
```
**Symbols:**

```
ffffffff81016ed0-ffffffff81016eec: snb_uncore_imc_read_counter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
u64 snb_uncore_imc_read_counter(struct intel_uncore_box *box, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_snb.c (ffffffff81017a30)
Location: arch/x86/events/intel/uncore_snb.c:345
Inline: False
```
**Symbols:**

```
ffffffff81017a30-ffffffff81017a4c: snb_uncore_imc_read_counter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
u64 snb_uncore_imc_read_counter(struct intel_uncore_box *box, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_snb.c (ffffffff81018220)
Location: arch/x86/events/intel/uncore_snb.c:368
Inline: False
```
**Symbols:**

```
ffffffff81018220-ffffffff8101823c: snb_uncore_imc_read_counter (STB_LOCAL)
```
</details>
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
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u64 snb_uncore_imc_read_counter(struct intel_uncore_box *box, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_snb.c (ffffffff81023430)
Location: arch/x86/events/intel/uncore_snb.c:844
Inline: False
```
**Symbols:**

```
ffffffff81023430-ffffffff81023455: snb_uncore_imc_read_counter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u64 snb_uncore_imc_read_counter(struct intel_uncore_box *box, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_snb.c (ffffffff81028140)
Location: arch/x86/events/intel/uncore_snb.c:992
Inline: False
```
**Symbols:**

```
ffffffff81028140-ffffffff81028165: snb_uncore_imc_read_counter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u64 snb_uncore_imc_read_counter(struct intel_uncore_box *box, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_snb.c (ffffffff81028170)
Location: arch/x86/events/intel/uncore_snb.c:992
Inline: False
```
**Symbols:**

```
ffffffff81028170-ffffffff81028195: snb_uncore_imc_read_counter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u64 snb_uncore_imc_read_counter(struct intel_uncore_box *box, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_snb.c (ffffffff8102e2d0)
Location: arch/x86/events/intel/uncore_snb.c:992
Inline: False
```
**Symbols:**

```
ffffffff8102e2d0-ffffffff8102e2f5: snb_uncore_imc_read_counter (STB_LOCAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
