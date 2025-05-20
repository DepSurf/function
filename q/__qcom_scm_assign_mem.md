# Function: <code>__qcom_scm_assign_mem</code>

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
int __qcom_scm_assign_mem(struct device *dev, phys_addr_t mem_region, size_t mem_sz, phys_addr_t src, size_t src_sz, phys_addr_t dest, size_t dest_sz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/qcom_scm-64.c (ffff800010b50208)
Location: drivers/firmware/qcom_scm-64.c:377
Inline: False
Direct callers:
  - drivers/firmware/qcom_scm.c:qcom_scm_assign_mem
```
**Symbols:**

```
ffff800010b50208-ffff800010b502cc: __qcom_scm_assign_mem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __qcom_scm_assign_mem(struct device *dev, phys_addr_t mem_region, size_t mem_sz, phys_addr_t src, size_t src_sz, phys_addr_t dest, size_t dest_sz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/qcom_scm-32.c (c0c36cb4)
Location: drivers/firmware/qcom_scm-32.c:575
Inline: False
Direct callers:
  - drivers/firmware/qcom_scm.c:qcom_scm_assign_mem
```
**Symbols:**

```
c0c36cb4-c0c36cd0: __qcom_scm_assign_mem (STB_GLOBAL)
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
