# Function: <code>skx_iio_topology_cb</code>

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
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int skx_iio_topology_cb(struct intel_uncore_type *type, int segment, int die, u64 cpu_bus_msr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/uncore_snbep.c (0)
Location: arch/x86/events/intel/uncore_snbep.c:3883
Inline: False
```
**Symbols:**

```
ffffffff8102bb80-ffffffff8102bc2d: skx_iio_topology_cb (STB_LOCAL)
ffffffff820516c5-ffffffff820516e7: skx_iio_topology_cb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int skx_iio_topology_cb(struct intel_uncore_type *type, int segment, int die, u64 cpu_bus_msr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/uncore_snbep.c (0)
Location: arch/x86/events/intel/uncore_snbep.c:3873
Inline: False
```
**Symbols:**

```
ffffffff8102bbb0-ffffffff8102bc5e: skx_iio_topology_cb (STB_LOCAL)
ffffffff820cfbab-ffffffff820cfbcd: skx_iio_topology_cb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int skx_iio_topology_cb(struct intel_uncore_type *type, int segment, int die, u64 cpu_bus_msr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/uncore_snbep.c (0)
Location: arch/x86/events/intel/uncore_snbep.c:3881
Inline: False
```
**Symbols:**

```
ffffffff81031d10-ffffffff81031dbe: skx_iio_topology_cb (STB_LOCAL)
ffffffff821aa519-ffffffff821aa53b: skx_iio_topology_cb.cold (STB_LOCAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
