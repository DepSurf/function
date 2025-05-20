# Function: <code>intel_generic_uncore_mmio_enable_event</code>

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
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void intel_generic_uncore_mmio_enable_event(struct intel_uncore_box *box, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_discovery.c (ffffffff810215b0)
Location: arch/x86/events/intel/uncore_discovery.c:497
Inline: False
```
**Symbols:**

```
ffffffff810215b0-ffffffff810215d6: intel_generic_uncore_mmio_enable_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void intel_generic_uncore_mmio_enable_event(struct intel_uncore_box *box, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_discovery.c (ffffffff81025310)
Location: arch/x86/events/intel/uncore_discovery.c:497
Inline: False
```
**Symbols:**

```
ffffffff81025310-ffffffff81025336: intel_generic_uncore_mmio_enable_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void intel_generic_uncore_mmio_enable_event(struct intel_uncore_box *box, struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_discovery.c (ffffffff810291c0)
Location: arch/x86/events/intel/uncore_discovery.c:505
Inline: False
```
**Symbols:**

```
ffffffff810291c0-ffffffff810291f2: intel_generic_uncore_mmio_enable_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void intel_generic_uncore_mmio_enable_event(struct intel_uncore_box *box, struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_discovery.c (ffffffff8102fac0)
Location: arch/x86/events/intel/uncore_discovery.c:505
Inline: False
```
**Symbols:**

```
ffffffff8102fac0-ffffffff8102faf2: intel_generic_uncore_mmio_enable_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void intel_generic_uncore_mmio_enable_event(struct intel_uncore_box *box, struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_discovery.c (ffffffff8102fbb0)
Location: arch/x86/events/intel/uncore_discovery.c:525
Inline: False
```
**Symbols:**

```
ffffffff8102fbb0-ffffffff8102fbe2: intel_generic_uncore_mmio_enable_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void intel_generic_uncore_mmio_enable_event(struct intel_uncore_box *box, struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_discovery.c (ffffffff81035e50)
Location: arch/x86/events/intel/uncore_discovery.c:526
Inline: False
```
**Symbols:**

```
ffffffff81035e50-ffffffff81035e82: intel_generic_uncore_mmio_enable_event (STB_GLOBAL)
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
