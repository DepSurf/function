# Function: <code>snr_uncore_mmio_disable_event</code>

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
void snr_uncore_mmio_disable_event(struct intel_uncore_box *box, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101abd0)
Location: arch/x86/events/intel/uncore_snbep.c:4468
Inline: False
```
**Symbols:**

```
ffffffff8101abd0-ffffffff8101abf7: snr_uncore_mmio_disable_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void snr_uncore_mmio_disable_event(struct intel_uncore_box *box, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101b550)
Location: arch/x86/events/intel/uncore_snbep.c:4444
Inline: False
```
**Symbols:**

```
ffffffff8101b550-ffffffff8101b577: snr_uncore_mmio_disable_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void snr_uncore_mmio_disable_event(struct intel_uncore_box *box, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101cc40)
Location: arch/x86/events/intel/uncore_snbep.c:4487
Inline: False
```
**Symbols:**

```
ffffffff8101cc40-ffffffff8101cc67: snr_uncore_mmio_disable_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void snr_uncore_mmio_disable_event(struct intel_uncore_box *box, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101ef31)
Location: arch/x86/events/intel/uncore_snbep.c:4740
Inline: True
```
**Symbols:**

```
ffffffff8101eef0-ffffffff8101ef3f: snr_uncore_mmio_disable_event (STB_LOCAL)
ffffffff81bd266d-ffffffff81bd268b: snr_uncore_mmio_disable_event.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void snr_uncore_mmio_disable_event(struct intel_uncore_box *box, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/uncore_snbep.c (ffffffff810203ad)
Location: arch/x86/events/intel/uncore_snbep.c:4765
Inline: True
```
**Symbols:**

```
ffffffff81020370-ffffffff810203b9: snr_uncore_mmio_disable_event (STB_LOCAL)
ffffffff81bc4860-ffffffff81bc487f: snr_uncore_mmio_disable_event.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void snr_uncore_mmio_disable_event(struct intel_uncore_box *box, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/uncore_snbep.c (ffffffff81023c04)
Location: arch/x86/events/intel/uncore_snbep.c:4923
Inline: True
```
**Symbols:**

```
ffffffff81023ba0-ffffffff81023c1b: snr_uncore_mmio_disable_event (STB_LOCAL)
ffffffff81c96d66-ffffffff81c96da2: snr_uncore_mmio_disable_event.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void snr_uncore_mmio_disable_event(struct intel_uncore_box *box, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/uncore_snbep.c (ffffffff81027b49)
Location: arch/x86/events/intel/uncore_snbep.c:4923
Inline: True
```
**Symbols:**

```
ffffffff81027ae0-ffffffff81027b74: snr_uncore_mmio_disable_event (STB_LOCAL)
ffffffff81e461b7-ffffffff81e461f8: snr_uncore_mmio_disable_event.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void snr_uncore_mmio_disable_event(struct intel_uncore_box *box, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8102dab5)
Location: arch/x86/events/intel/uncore_snbep.c:5179
Inline: True
```
**Symbols:**

```
ffffffff8102da50-ffffffff8102db09: snr_uncore_mmio_disable_event (STB_LOCAL)
ffffffff8205171b-ffffffff82051730: snr_uncore_mmio_disable_event.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void snr_uncore_mmio_disable_event(struct intel_uncore_box *box, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8102de35)
Location: arch/x86/events/intel/uncore_snbep.c:5169
Inline: True
```
**Symbols:**

```
ffffffff8102ddd0-ffffffff8102de89: snr_uncore_mmio_disable_event (STB_LOCAL)
ffffffff820cfc01-ffffffff820cfc16: snr_uncore_mmio_disable_event.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void snr_uncore_mmio_disable_event(struct intel_uncore_box *box, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/uncore_snbep.c (ffffffff81033e65)
Location: arch/x86/events/intel/uncore_snbep.c:5177
Inline: True
```
**Symbols:**

```
ffffffff81033e00-ffffffff81033eb9: snr_uncore_mmio_disable_event (STB_LOCAL)
ffffffff821aa56f-ffffffff821aa584: snr_uncore_mmio_disable_event.cold (STB_LOCAL)
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
void snr_uncore_mmio_disable_event(struct intel_uncore_box *box, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101b550)
Location: arch/x86/events/intel/uncore_snbep.c:4444
Inline: False
```
**Symbols:**

```
ffffffff8101b550-ffffffff8101b577: snr_uncore_mmio_disable_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void snr_uncore_mmio_disable_event(struct intel_uncore_box *box, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101aba0)
Location: arch/x86/events/intel/uncore_snbep.c:4444
Inline: False
```
**Symbols:**

```
ffffffff8101aba0-ffffffff8101abc7: snr_uncore_mmio_disable_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void snr_uncore_mmio_disable_event(struct intel_uncore_box *box, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101b510)
Location: arch/x86/events/intel/uncore_snbep.c:4444
Inline: False
```
**Symbols:**

```
ffffffff8101b510-ffffffff8101b537: snr_uncore_mmio_disable_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void snr_uncore_mmio_disable_event(struct intel_uncore_box *box, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101b750)
Location: arch/x86/events/intel/uncore_snbep.c:4444
Inline: False
```
**Symbols:**

```
ffffffff8101b750-ffffffff8101b777: snr_uncore_mmio_disable_event (STB_LOCAL)
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
