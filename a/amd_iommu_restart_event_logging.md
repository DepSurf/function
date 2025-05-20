# Function: <code>amd_iommu_restart_event_logging</code>

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
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void amd_iommu_restart_event_logging(struct amd_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff81813020)
Location: drivers/iommu/amd/init.c:662
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_int_thread
```
**Symbols:**

```
ffffffff81813020-ffffffff81813059: amd_iommu_restart_event_logging (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void amd_iommu_restart_event_logging(struct amd_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff81953fd0)
Location: drivers/iommu/amd/init.c:666
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_int_thread
```
**Symbols:**

```
ffffffff81953fd0-ffffffff81954015: amd_iommu_restart_event_logging (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void amd_iommu_restart_event_logging(struct amd_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff81ab9c30)
Location: drivers/iommu/amd/init.c:748
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_int_thread
```
**Symbols:**

```
ffffffff81ab9c30-ffffffff81ab9c75: amd_iommu_restart_event_logging (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void amd_iommu_restart_event_logging(struct amd_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff81b060e0)
Location: drivers/iommu/amd/init.c:759
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_int_thread
```
**Symbols:**

```
ffffffff81b060e0-ffffffff81b06125: amd_iommu_restart_event_logging (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void amd_iommu_restart_event_logging(struct amd_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff81b59e80)
Location: drivers/iommu/amd/init.c:773
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_int_thread
```
**Symbols:**

```
ffffffff81b59e80-ffffffff81b59eda: amd_iommu_restart_event_logging (STB_GLOBAL)
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
