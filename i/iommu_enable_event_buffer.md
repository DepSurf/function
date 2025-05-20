# Function: <code>iommu_enable_event_buffer</code>

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
In drivers/iommu/amd_iommu_init.c (ffffffff81532a40)
Location: drivers/iommu/amd_iommu_init.c:560
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
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
In drivers/iommu/amd_iommu_init.c (ffffffff8158733e)
Location: drivers/iommu/amd_iommu_init.c:614
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
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
In drivers/iommu/amd_iommu_init.c (ffffffff815b49dd)
Location: drivers/iommu/amd_iommu_init.c:623
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
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
In drivers/iommu/amd_iommu_init.c (ffffffff815ca82d)
Location: drivers/iommu/amd_iommu_init.c:632
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void iommu_enable_event_buffer(struct amd_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff81631120)
Location: drivers/iommu/amd_iommu_init.c:669
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
```
**Symbols:**

```
ffffffff81631120-ffffffff8163119d: iommu_enable_event_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void iommu_enable_event_buffer(struct amd_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff8166bf00)
Location: drivers/iommu/amd_iommu_init.c:669
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
```
**Symbols:**

```
ffffffff8166bf00-ffffffff8166bf7d: iommu_enable_event_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void iommu_enable_event_buffer(struct amd_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff8168a720)
Location: drivers/iommu/amd_iommu_init.c:672
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
```
**Symbols:**

```
ffffffff8168a720-ffffffff8168a7ea: iommu_enable_event_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void iommu_enable_event_buffer(struct amd_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff816c2150)
Location: drivers/iommu/amd_iommu_init.c:660
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
```
**Symbols:**

```
ffffffff816c2150-ffffffff816c221a: iommu_enable_event_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void iommu_enable_event_buffer(struct amd_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff816e5070)
Location: drivers/iommu/amd_iommu_init.c:661
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
```
**Symbols:**

```
ffffffff816e5070-ffffffff816e513a: iommu_enable_event_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void iommu_enable_event_buffer(struct amd_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff8179adc0)
Location: drivers/iommu/amd/init.c:661
Inline: False
Direct callers:
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
```
**Symbols:**

```
ffffffff8179adc0-ffffffff8179ae87: iommu_enable_event_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void iommu_enable_event_buffer(struct amd_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff817a90e0)
Location: drivers/iommu/amd/init.c:718
Inline: False
Direct callers:
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
```
**Symbols:**

```
ffffffff817a90e0-ffffffff817a91a7: iommu_enable_event_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void iommu_enable_event_buffer(struct amd_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff8178add0)
Location: drivers/iommu/amd/init.c:714
Inline: False
Direct callers:
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
```
**Symbols:**

```
ffffffff8178add0-ffffffff8178aea0: iommu_enable_event_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void iommu_enable_event_buffer(struct amd_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff81812610)
Location: drivers/iommu/amd/init.c:741
Inline: False
Direct callers:
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
```
**Symbols:**

```
ffffffff81812610-ffffffff818126e0: iommu_enable_event_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void iommu_enable_event_buffer(struct amd_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff81953570)
Location: drivers/iommu/amd/init.c:745
Inline: False
Direct callers:
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
```
**Symbols:**

```
ffffffff81953570-ffffffff8195364c: iommu_enable_event_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void iommu_enable_event_buffer(struct amd_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff81ab8e00)
Location: drivers/iommu/amd/init.c:827
Inline: False
Direct callers:
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
```
**Symbols:**

```
ffffffff81ab8e00-ffffffff81ab8edf: iommu_enable_event_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void iommu_enable_event_buffer(struct amd_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff81b04fe0)
Location: drivers/iommu/amd/init.c:862
Inline: False
Direct callers:
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
```
**Symbols:**

```
ffffffff81b04fe0-ffffffff81b050bf: iommu_enable_event_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void iommu_enable_event_buffer(struct amd_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff81b58b90)
Location: drivers/iommu/amd/init.c:875
Inline: False
Direct callers:
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
```
**Symbols:**

```
ffffffff81b58b90-ffffffff81b58c6f: iommu_enable_event_buffer (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void iommu_enable_event_buffer(struct amd_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff816aab50)
Location: drivers/iommu/amd_iommu_init.c:661
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
```
**Symbols:**

```
ffffffff816aab50-ffffffff816aac1a: iommu_enable_event_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void iommu_enable_event_buffer(struct amd_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff816881a0)
Location: drivers/iommu/amd_iommu_init.c:661
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
```
**Symbols:**

```
ffffffff816881a0-ffffffff8168826a: iommu_enable_event_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void iommu_enable_event_buffer(struct amd_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff816d8d30)
Location: drivers/iommu/amd_iommu_init.c:661
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
```
**Symbols:**

```
ffffffff816d8d30-ffffffff816d8dfa: iommu_enable_event_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void iommu_enable_event_buffer(struct amd_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff816f32e0)
Location: drivers/iommu/amd_iommu_init.c:661
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
```
**Symbols:**

```
ffffffff816f32e0-ffffffff816f33aa: iommu_enable_event_buffer (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
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
