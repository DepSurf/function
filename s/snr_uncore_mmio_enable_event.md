# Function: <code>snr_uncore_mmio_enable_event</code>

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
void snr_uncore_mmio_enable_event(struct intel_uncore_box *box, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101aba0)
Location: arch/x86/events/intel/uncore_snbep.c:4456
Inline: False
```
**Symbols:**

```
ffffffff8101aba0-ffffffff8101abcd: snr_uncore_mmio_enable_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void snr_uncore_mmio_enable_event(struct intel_uncore_box *box, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101b520)
Location: arch/x86/events/intel/uncore_snbep.c:4432
Inline: False
```
**Symbols:**

```
ffffffff8101b520-ffffffff8101b54d: snr_uncore_mmio_enable_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void snr_uncore_mmio_enable_event(struct intel_uncore_box *box, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101cc10)
Location: arch/x86/events/intel/uncore_snbep.c:4475
Inline: False
```
**Symbols:**

```
ffffffff8101cc10-ffffffff8101cc3d: snr_uncore_mmio_enable_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void snr_uncore_mmio_enable_event(struct intel_uncore_box *box, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101ec91)
Location: arch/x86/events/intel/uncore_snbep.c:4725
Inline: True
```
**Symbols:**

```
ffffffff8101ec50-ffffffff8101eca5: snr_uncore_mmio_enable_event (STB_LOCAL)
ffffffff81bd264f-ffffffff81bd266d: snr_uncore_mmio_enable_event.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void snr_uncore_mmio_enable_event(struct intel_uncore_box *box, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8102011d)
Location: arch/x86/events/intel/uncore_snbep.c:4750
Inline: True
```
**Symbols:**

```
ffffffff810200e0-ffffffff81020130: snr_uncore_mmio_enable_event (STB_LOCAL)
ffffffff81bc4841-ffffffff81bc4860: snr_uncore_mmio_enable_event.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void snr_uncore_mmio_enable_event(struct intel_uncore_box *box, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/uncore_snbep.c (ffffffff810237f4)
Location: arch/x86/events/intel/uncore_snbep.c:4908
Inline: True
```
**Symbols:**

```
ffffffff81023790-ffffffff81023811: snr_uncore_mmio_enable_event (STB_LOCAL)
ffffffff81c96ca8-ffffffff81c96ce4: snr_uncore_mmio_enable_event.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void snr_uncore_mmio_enable_event(struct intel_uncore_box *box, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/uncore_snbep.c (ffffffff81027899)
Location: arch/x86/events/intel/uncore_snbep.c:4908
Inline: True
```
**Symbols:**

```
ffffffff81027830-ffffffff810278cb: snr_uncore_mmio_enable_event (STB_LOCAL)
ffffffff81e4611f-ffffffff81e46160: snr_uncore_mmio_enable_event.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void snr_uncore_mmio_enable_event(struct intel_uncore_box *box, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8102d975)
Location: arch/x86/events/intel/uncore_snbep.c:5164
Inline: True
```
**Symbols:**

```
ffffffff8102d910-ffffffff8102d9d0: snr_uncore_mmio_enable_event (STB_LOCAL)
ffffffff82051706-ffffffff8205171b: snr_uncore_mmio_enable_event.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void snr_uncore_mmio_enable_event(struct intel_uncore_box *box, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8102dcf5)
Location: arch/x86/events/intel/uncore_snbep.c:5154
Inline: True
```
**Symbols:**

```
ffffffff8102dc90-ffffffff8102dd50: snr_uncore_mmio_enable_event (STB_LOCAL)
ffffffff820cfbec-ffffffff820cfc01: snr_uncore_mmio_enable_event.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void snr_uncore_mmio_enable_event(struct intel_uncore_box *box, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/uncore_snbep.c (ffffffff81033d25)
Location: arch/x86/events/intel/uncore_snbep.c:5162
Inline: True
```
**Symbols:**

```
ffffffff81033cc0-ffffffff81033d80: snr_uncore_mmio_enable_event (STB_LOCAL)
ffffffff821aa55a-ffffffff821aa56f: snr_uncore_mmio_enable_event.cold (STB_LOCAL)
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
void snr_uncore_mmio_enable_event(struct intel_uncore_box *box, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101b520)
Location: arch/x86/events/intel/uncore_snbep.c:4432
Inline: False
```
**Symbols:**

```
ffffffff8101b520-ffffffff8101b54d: snr_uncore_mmio_enable_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void snr_uncore_mmio_enable_event(struct intel_uncore_box *box, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101ab70)
Location: arch/x86/events/intel/uncore_snbep.c:4432
Inline: False
```
**Symbols:**

```
ffffffff8101ab70-ffffffff8101ab9d: snr_uncore_mmio_enable_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void snr_uncore_mmio_enable_event(struct intel_uncore_box *box, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101b4e0)
Location: arch/x86/events/intel/uncore_snbep.c:4432
Inline: False
```
**Symbols:**

```
ffffffff8101b4e0-ffffffff8101b50d: snr_uncore_mmio_enable_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void snr_uncore_mmio_enable_event(struct intel_uncore_box *box, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101b720)
Location: arch/x86/events/intel/uncore_snbep.c:4432
Inline: False
```
**Symbols:**

```
ffffffff8101b720-ffffffff8101b74d: snr_uncore_mmio_enable_event (STB_LOCAL)
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
