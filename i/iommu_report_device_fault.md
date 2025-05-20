# Function: <code>iommu_report_device_fault</code>

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
int iommu_report_device_fault(struct device *dev, struct iommu_fault_event *evt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816b6520)
Location: drivers/iommu/iommu.c:982
Inline: False
```
**Symbols:**

```
ffffffff816b6520-ffffffff816b667c: iommu_report_device_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int iommu_report_device_fault(struct device *dev, struct iommu_fault_event *evt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816d9220)
Location: drivers/iommu/iommu.c:1038
Inline: False
```
**Symbols:**

```
ffffffff816d9220-ffffffff816d937c: iommu_report_device_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int iommu_report_device_fault(struct device *dev, struct iommu_fault_event *evt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8178d760)
Location: drivers/iommu/iommu.c:1141
Inline: False
```
**Symbols:**

```
ffffffff8178d760-ffffffff8178d8bc: iommu_report_device_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int iommu_report_device_fault(struct device *dev, struct iommu_fault_event *evt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff817b91f0)
Location: drivers/iommu/iommu.c:1162
Inline: False
Direct callers:
  - drivers/iommu/intel/svm.c:intel_svm_prq_report
```
**Symbols:**

```
ffffffff817b91f0-ffffffff817b934c: iommu_report_device_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int iommu_report_device_fault(struct device *dev, struct iommu_fault_event *evt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8179c400)
Location: drivers/iommu/iommu.c:1191
Inline: False
Direct callers:
  - drivers/iommu/intel/svm.c:intel_svm_prq_report
```
**Symbols:**

```
ffffffff8179c400-ffffffff8179c553: iommu_report_device_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int iommu_report_device_fault(struct device *dev, struct iommu_fault_event *evt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff818250f0)
Location: drivers/iommu/iommu.c:1206
Inline: False
Direct callers:
  - drivers/iommu/intel/svm.c:prq_event_thread
```
**Symbols:**

```
ffffffff818250f0-ffffffff81825243: iommu_report_device_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int iommu_report_device_fault(struct device *dev, struct iommu_fault_event *evt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81964f80)
Location: drivers/iommu/iommu.c:1180
Inline: False
Direct callers:
  - drivers/iommu/intel/svm.c:prq_event_thread
```
**Symbols:**

```
ffffffff81964f80-ffffffff819650e7: iommu_report_device_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int iommu_report_device_fault(struct device *dev, struct iommu_fault_event *evt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81ace370)
Location: drivers/iommu/iommu.c:1301
Inline: False
Direct callers:
  - drivers/iommu/intel/svm.c:prq_event_thread
```
**Symbols:**

```
ffffffff81ace370-ffffffff81ace4d7: iommu_report_device_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int iommu_report_device_fault(struct device *dev, struct iommu_fault_event *evt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81b1cef0)
Location: drivers/iommu/iommu.c:1292
Inline: False
Direct callers:
  - drivers/iommu/intel/svm.c:prq_event_thread
```
**Symbols:**

```
ffffffff81b1cef0-ffffffff81b1d057: iommu_report_device_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int iommu_report_device_fault(struct device *dev, struct iommu_fault_event *evt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81b73470)
Location: drivers/iommu/iommu.c:1436
Inline: False
Direct callers:
  - drivers/iommu/intel/svm.c:prq_event_thread
```
**Symbols:**

```
ffffffff81b73470-ffffffff81b735d7: iommu_report_device_fault (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int iommu_report_device_fault(struct device *dev, struct iommu_fault_event *evt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffff8000108c4a50)
Location: drivers/iommu/iommu.c:1038
Inline: False
```
**Symbols:**

```
ffff8000108c4a50-ffff8000108c4b90: iommu_report_device_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int iommu_report_device_fault(struct device *dev, struct iommu_fault_event *evt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (c09bbe54)
Location: drivers/iommu/iommu.c:1038
Inline: False
```
**Symbols:**

```
c09bbe54-c09bbf80: iommu_report_device_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int iommu_report_device_fault(struct device *dev, struct iommu_fault_event *evt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (c00000000096a890)
Location: drivers/iommu/iommu.c:1038
Inline: False
```
**Symbols:**

```
c00000000096a890-c00000000096aa7c: iommu_report_device_fault (STB_GLOBAL)
```
</details>
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
int iommu_report_device_fault(struct device *dev, struct iommu_fault_event *evt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8169ec70)
Location: drivers/iommu/iommu.c:1038
Inline: False
```
**Symbols:**

```
ffffffff8169ec70-ffffffff8169edcc: iommu_report_device_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int iommu_report_device_fault(struct device *dev, struct iommu_fault_event *evt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8167c660)
Location: drivers/iommu/iommu.c:1038
Inline: False
```
**Symbols:**

```
ffffffff8167c660-ffffffff8167c7bc: iommu_report_device_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int iommu_report_device_fault(struct device *dev, struct iommu_fault_event *evt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816ccee0)
Location: drivers/iommu/iommu.c:1038
Inline: False
```
**Symbols:**

```
ffffffff816ccee0-ffffffff816cd03c: iommu_report_device_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int iommu_report_device_fault(struct device *dev, struct iommu_fault_event *evt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816e73c0)
Location: drivers/iommu/iommu.c:1038
Inline: False
```
**Symbols:**

```
ffffffff816e73c0-ffffffff816e751c: iommu_report_device_fault (STB_GLOBAL)
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
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
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
