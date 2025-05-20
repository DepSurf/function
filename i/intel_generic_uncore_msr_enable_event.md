# Function: <code>intel_generic_uncore_msr_enable_event</code>

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
void intel_generic_uncore_msr_enable_event(struct intel_uncore_box *box, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_discovery.c (ffffffff81021970)
Location: arch/x86/events/intel/uncore_discovery.c:355
Inline: False
```
**Symbols:**

```
ffffffff81021970-ffffffff81021995: intel_generic_uncore_msr_enable_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void intel_generic_uncore_msr_enable_event(struct intel_uncore_box *box, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_discovery.c (ffffffff810256d0)
Location: arch/x86/events/intel/uncore_discovery.c:355
Inline: False
```
**Symbols:**

```
ffffffff810256d0-ffffffff810256f5: intel_generic_uncore_msr_enable_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void intel_generic_uncore_msr_enable_event(struct intel_uncore_box *box, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_discovery.c (ffffffff81029650)
Location: arch/x86/events/intel/uncore_discovery.c:363
Inline: False
```
**Symbols:**

```
ffffffff81029650-ffffffff8102968e: intel_generic_uncore_msr_enable_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void intel_generic_uncore_msr_enable_event(struct intel_uncore_box *box, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_discovery.c (ffffffff81030090)
Location: arch/x86/events/intel/uncore_discovery.c:363
Inline: False
```
**Symbols:**

```
ffffffff81030090-ffffffff810300ce: intel_generic_uncore_msr_enable_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void intel_generic_uncore_msr_enable_event(struct intel_uncore_box *box, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_discovery.c (ffffffff81030180)
Location: arch/x86/events/intel/uncore_discovery.c:383
Inline: False
```
**Symbols:**

```
ffffffff81030180-ffffffff810301be: intel_generic_uncore_msr_enable_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void intel_generic_uncore_msr_enable_event(struct intel_uncore_box *box, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_discovery.c (ffffffff81036420)
Location: arch/x86/events/intel/uncore_discovery.c:384
Inline: False
```
**Symbols:**

```
ffffffff81036420-ffffffff8103645e: intel_generic_uncore_msr_enable_event (STB_LOCAL)
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
