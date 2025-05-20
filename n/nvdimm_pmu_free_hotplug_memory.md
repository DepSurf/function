# Function: <code>nvdimm_pmu_free_hotplug_memory</code>

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
void nvdimm_pmu_free_hotplug_memory(struct nvdimm_pmu *nd_pmu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/nd_perf.c (ffffffff819d8ff0)
Location: drivers/nvdimm/nd_perf.c:263
Inline: False
Direct callers:
  - drivers/nvdimm/nd_perf.c:unregister_nvdimm_pmu
  - drivers/nvdimm/nd_perf.c:register_nvdimm_pmu
```
**Symbols:**

```
ffffffff819d8ff0-ffffffff819d9053: nvdimm_pmu_free_hotplug_memory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void nvdimm_pmu_free_hotplug_memory(struct nvdimm_pmu *nd_pmu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/nd_perf.c (ffffffff81b54010)
Location: drivers/nvdimm/nd_perf.c:263
Inline: False
Direct callers:
  - drivers/nvdimm/nd_perf.c:unregister_nvdimm_pmu
  - drivers/nvdimm/nd_perf.c:register_nvdimm_pmu
```
**Symbols:**

```
ffffffff81b54010-ffffffff81b54073: nvdimm_pmu_free_hotplug_memory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void nvdimm_pmu_free_hotplug_memory(struct nvdimm_pmu *nd_pmu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/nd_perf.c (ffffffff81ba7550)
Location: drivers/nvdimm/nd_perf.c:263
Inline: False
Direct callers:
  - drivers/nvdimm/nd_perf.c:unregister_nvdimm_pmu
  - drivers/nvdimm/nd_perf.c:register_nvdimm_pmu
```
**Symbols:**

```
ffffffff81ba7550-ffffffff81ba75b3: nvdimm_pmu_free_hotplug_memory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void nvdimm_pmu_free_hotplug_memory(struct nvdimm_pmu *nd_pmu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/nd_perf.c (ffffffff81bfb800)
Location: drivers/nvdimm/nd_perf.c:263
Inline: False
Direct callers:
  - drivers/nvdimm/nd_perf.c:unregister_nvdimm_pmu
  - drivers/nvdimm/nd_perf.c:register_nvdimm_pmu
```
**Symbols:**

```
ffffffff81bfb800-ffffffff81bfb863: nvdimm_pmu_free_hotplug_memory (STB_LOCAL)
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
