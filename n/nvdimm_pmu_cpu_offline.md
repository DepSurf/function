# Function: <code>nvdimm_pmu_cpu_offline</code>

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
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int nvdimm_pmu_cpu_offline(unsigned int cpu, struct hlist_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/nd_perf.c (ffffffff819d9090)
Location: drivers/nvdimm/nd_perf.c:129
Inline: False
```
**Symbols:**

```
ffffffff819d9090-ffffffff819d91ac: nvdimm_pmu_cpu_offline (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int nvdimm_pmu_cpu_offline(unsigned int cpu, struct hlist_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/nd_perf.c (ffffffff81b540d0)
Location: drivers/nvdimm/nd_perf.c:129
Inline: False
```
**Symbols:**

```
ffffffff81b540d0-ffffffff81b54207: nvdimm_pmu_cpu_offline (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int nvdimm_pmu_cpu_offline(unsigned int cpu, struct hlist_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/nd_perf.c (ffffffff81ba7620)
Location: drivers/nvdimm/nd_perf.c:129
Inline: False
```
**Symbols:**

```
ffffffff81ba7620-ffffffff81ba7757: nvdimm_pmu_cpu_offline (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int nvdimm_pmu_cpu_offline(unsigned int cpu, struct hlist_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/nd_perf.c (ffffffff81bfb8d0)
Location: drivers/nvdimm/nd_perf.c:129
Inline: False
```
**Symbols:**

```
ffffffff81bfb8d0-ffffffff81bfba07: nvdimm_pmu_cpu_offline (STB_LOCAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
