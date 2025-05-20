# Function: <code>perf_iommu_enable_event</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/iommu.c (ffffffff8100a17e)
Location: arch/x86/events/amd/iommu.c:250
Inline: True
Inline callers:
  - arch/x86/events/amd/iommu.c:perf_iommu_start
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/iommu.c (ffffffff8100a31a)
Location: arch/x86/events/amd/iommu.c:255
Inline: True
Inline callers:
  - arch/x86/events/amd/iommu.c:perf_iommu_start
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/iommu.c (ffffffff8100a35a)
Location: arch/x86/events/amd/iommu.c:255
Inline: True
Inline callers:
  - arch/x86/events/amd/iommu.c:perf_iommu_start
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/iommu.c (ffffffff81009ec3)
Location: arch/x86/events/amd/iommu.c:246
Inline: True
Inline callers:
  - arch/x86/events/amd/iommu.c:perf_iommu_start
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/iommu.c (ffffffff8100a3a3)
Location: arch/x86/events/amd/iommu.c:246
Inline: True
Inline callers:
  - arch/x86/events/amd/iommu.c:perf_iommu_start
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/iommu.c (ffffffff8100aab6)
Location: arch/x86/events/amd/iommu.c:246
Inline: True
Inline callers:
  - arch/x86/events/amd/iommu.c:perf_iommu_start
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/iommu.c (ffffffff8100a9e6)
Location: arch/x86/events/amd/iommu.c:246
Inline: True
Inline callers:
  - arch/x86/events/amd/iommu.c:perf_iommu_start
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/iommu.c (ffffffff8100ae9c)
Location: arch/x86/events/amd/iommu.c:238
Inline: True
Inline callers:
  - arch/x86/events/amd/iommu.c:perf_iommu_start
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/iommu.c (ffffffff8100b2ac)
Location: arch/x86/events/amd/iommu.c:238
Inline: True
Inline callers:
  - arch/x86/events/amd/iommu.c:perf_iommu_start
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void perf_iommu_enable_event(struct perf_event *ev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/iommu.c (ffffffff8100c510)
Location: arch/x86/events/amd/iommu.c:238
Inline: False
Direct callers:
  - arch/x86/events/amd/iommu.c:perf_iommu_start
```
**Symbols:**

```
ffffffff8100c510-ffffffff8100c68f: perf_iommu_enable_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void perf_iommu_enable_event(struct perf_event *ev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/iommu.c (ffffffff8100b470)
Location: arch/x86/events/amd/iommu.c:238
Inline: False
Direct callers:
  - arch/x86/events/amd/iommu.c:perf_iommu_start
```
**Symbols:**

```
ffffffff8100b470-ffffffff8100b5ef: perf_iommu_enable_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/iommu.c (ffffffff8100be47)
Location: arch/x86/events/amd/iommu.c:237
Inline: True
Inline callers:
  - arch/x86/events/amd/iommu.c:perf_iommu_start
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/iommu.c (ffffffff8100c347)
Location: arch/x86/events/amd/iommu.c:237
Inline: True
Inline callers:
  - arch/x86/events/amd/iommu.c:perf_iommu_start
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/iommu.c (ffffffff8100d0ac)
Location: arch/x86/events/amd/iommu.c:237
Inline: True
Inline callers:
  - arch/x86/events/amd/iommu.c:perf_iommu_start
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/iommu.c (ffffffff810101ec)
Location: arch/x86/events/amd/iommu.c:237
Inline: True
Inline callers:
  - arch/x86/events/amd/iommu.c:perf_iommu_start
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/iommu.c (ffffffff8100f8ac)
Location: arch/x86/events/amd/iommu.c:237
Inline: True
Inline callers:
  - arch/x86/events/amd/iommu.c:perf_iommu_start
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/iommu.c (ffffffff81014fec)
Location: arch/x86/events/amd/iommu.c:237
Inline: True
Inline callers:
  - arch/x86/events/amd/iommu.c:perf_iommu_start
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/iommu.c (ffffffff8100b2ac)
Location: arch/x86/events/amd/iommu.c:238
Inline: True
Inline callers:
  - arch/x86/events/amd/iommu.c:perf_iommu_start
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/iommu.c (ffffffff81009c3c)
Location: arch/x86/events/amd/iommu.c:238
Inline: True
Inline callers:
  - arch/x86/events/amd/iommu.c:perf_iommu_start
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/iommu.c (ffffffff8100b26c)
Location: arch/x86/events/amd/iommu.c:238
Inline: True
Inline callers:
  - arch/x86/events/amd/iommu.c:perf_iommu_start
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/iommu.c (ffffffff8100b44c)
Location: arch/x86/events/amd/iommu.c:238
Inline: True
Inline callers:
  - arch/x86/events/amd/iommu.c:perf_iommu_start
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
