# Function: <code>arm_ccn_for_each_valid_region</code>

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
int arm_ccn_for_each_valid_region(struct arm_ccn *ccn, int (*callback)(struct arm_ccn *, int, void *, u32, u32));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/perf/arm-ccn.c (ffff800010b92e68)
Location: drivers/perf/arm-ccn.c:1342
Inline: False
Direct callers:
  - drivers/perf/arm-ccn.c:arm_ccn_probe
  - drivers/perf/arm-ccn.c:arm_ccn_probe
```
**Symbols:**

```
ffff800010b92e68-ffff800010b92f44: arm_ccn_for_each_valid_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int arm_ccn_for_each_valid_region(struct arm_ccn *ccn, int (*callback)(struct arm_ccn *, int, void *, u32, u32));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/perf/arm-ccn.c (c0c7bc00)
Location: drivers/perf/arm-ccn.c:1342
Inline: False
Direct callers:
  - drivers/perf/arm-ccn.c:arm_ccn_probe
  - drivers/perf/arm-ccn.c:arm_ccn_probe
```
**Symbols:**

```
c0c7bc00-c0c7bca8: arm_ccn_for_each_valid_region (STB_LOCAL)
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
