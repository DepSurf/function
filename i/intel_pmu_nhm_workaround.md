# Function: <code>intel_pmu_nhm_workaround</code>

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
In arch/x86/events/intel/core.c (ffffffff8100c13e)
Location: arch/x86/events/intel/core.c:1567
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
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
In arch/x86/events/intel/core.c (ffffffff8100c374)
Location: arch/x86/events/intel/core.c:1796
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
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
In arch/x86/events/intel/core.c (ffffffff8100c434)
Location: arch/x86/events/intel/core.c:1796
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
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
In arch/x86/events/intel/core.c (ffffffff8100c184)
Location: arch/x86/events/intel/core.c:1931
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
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
In arch/x86/events/intel/core.c (ffffffff8100c454)
Location: arch/x86/events/intel/core.c:1931
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
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
In arch/x86/events/intel/core.c (ffffffff8100cba4)
Location: arch/x86/events/intel/core.c:1931
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
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
In arch/x86/events/intel/core.c (ffffffff8100ccb4)
Location: arch/x86/events/intel/core.c:1935
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
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
In arch/x86/events/intel/core.c (ffffffff8100d4f4)
Location: arch/x86/events/intel/core.c:2005
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
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
In arch/x86/events/intel/core.c (ffffffff8100da30)
Location: arch/x86/events/intel/core.c:2006
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void intel_pmu_nhm_workaround();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100eb70)
Location: arch/x86/events/intel/core.c:2013
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
```
**Symbols:**

```
ffffffff8100eb70-ffffffff8100ed26: intel_pmu_nhm_workaround (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void intel_pmu_nhm_workaround();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100df40)
Location: arch/x86/events/intel/core.c:2037
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
```
**Symbols:**

```
ffffffff8100df40-ffffffff8100e0f6: intel_pmu_nhm_workaround (STB_LOCAL)
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
In arch/x86/events/intel/core.c (ffffffff8100e7b5)
Location: arch/x86/events/intel/core.c:2203
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
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
In arch/x86/events/intel/core.c (ffffffff8100f1c5)
Location: arch/x86/events/intel/core.c:2205
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
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
In arch/x86/events/intel/core.c (ffffffff810106ff)
Location: arch/x86/events/intel/core.c:2267
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
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
In arch/x86/events/intel/core.c (ffffffff8101447f)
Location: arch/x86/events/intel/core.c:2283
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
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
In arch/x86/events/intel/core.c (ffffffff81013cdf)
Location: arch/x86/events/intel/core.c:2303
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
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
In arch/x86/events/intel/core.c (ffffffff8101931f)
Location: arch/x86/events/intel/core.c:2323
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
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
In arch/x86/events/intel/core.c (ffffffff8100da30)
Location: arch/x86/events/intel/core.c:2006
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
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
In arch/x86/events/intel/core.c (ffffffff8100c300)
Location: arch/x86/events/intel/core.c:2006
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
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
In arch/x86/events/intel/core.c (ffffffff8100d9f0)
Location: arch/x86/events/intel/core.c:2006
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
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
In arch/x86/events/intel/core.c (ffffffff8100dbc0)
Location: arch/x86/events/intel/core.c:2006
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
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
