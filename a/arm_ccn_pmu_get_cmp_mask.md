# Function: <code>arm_ccn_pmu_get_cmp_mask</code>

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
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
u64 *arm_ccn_pmu_get_cmp_mask(struct arm_ccn *ccn, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/perf/arm-ccn.c (ffff800010b92338)
Location: drivers/perf/arm-ccn.c:455
Inline: False
Direct callers:
  - drivers/perf/arm-ccn.c:arm_ccn_pmu_cmp_mask_store
  - drivers/perf/arm-ccn.c:arm_ccn_pmu_cmp_mask_show
```
**Symbols:**

```
ffff800010b92338-ffff800010b923f4: arm_ccn_pmu_get_cmp_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u64 *arm_ccn_pmu_get_cmp_mask(struct arm_ccn *ccn, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/perf/arm-ccn.c (c0c7c488)
Location: drivers/perf/arm-ccn.c:455
Inline: False
Direct callers:
  - drivers/perf/arm-ccn.c:arm_ccn_pmu_cmp_mask_store
  - drivers/perf/arm-ccn.c:arm_ccn_pmu_cmp_mask_show
```
**Symbols:**

```
c0c7c488-c0c7c53c: arm_ccn_pmu_get_cmp_mask (STB_LOCAL)
```
</details>
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
<b>Arch</b>
<ul>
</ul>
