# Function: <code>early_enable_iommus</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void early_enable_iommus();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff81532a00)
Location: drivers/iommu/amd_iommu_init.c:1654
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu_init.c:amd_iommu_resume
  - drivers/iommu/amd_iommu_init.c:state_next
```
**Symbols:**

```
ffffffff81532a00-ffffffff81532c5a: early_enable_iommus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void early_enable_iommus();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff815871f0)
Location: drivers/iommu/amd_iommu_init.c:1869
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:amd_iommu_resume
```
**Symbols:**

```
ffffffff815871f0-ffffffff8158747a: early_enable_iommus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void early_enable_iommus();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff815b4890)
Location: drivers/iommu/amd_iommu_init.c:2009
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu_init.c:amd_iommu_resume
  - drivers/iommu/amd_iommu_init.c:iommu_go_to_state
```
**Symbols:**

```
ffffffff815b4890-ffffffff815b4b80: early_enable_iommus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void early_enable_iommus();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff815ca6e0)
Location: drivers/iommu/amd_iommu_init.c:2029
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu_init.c:amd_iommu_resume
  - drivers/iommu/amd_iommu_init.c:iommu_go_to_state
```
**Symbols:**

```
ffffffff815ca6e0-ffffffff815ca9d7: early_enable_iommus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void early_enable_iommus();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff81631270)
Location: drivers/iommu/amd_iommu_init.c:2182
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu_init.c:amd_iommu_resume
  - drivers/iommu/amd_iommu_init.c:iommu_go_to_state
```
**Symbols:**

```
ffffffff81631270-ffffffff81631795: early_enable_iommus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void early_enable_iommus();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (0)
Location: drivers/iommu/amd_iommu_init.c:2183
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu_init.c:amd_iommu_resume
  - drivers/iommu/amd_iommu_init.c:iommu_go_to_state
```
**Symbols:**

```
ffffffff8166c130-ffffffff8166c32b: early_enable_iommus (STB_LOCAL)
ffffffff8166cbe8-ffffffff8166ceaa: early_enable_iommus.cold.19 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void early_enable_iommus();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (0)
Location: drivers/iommu/amd_iommu_init.c:2217
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu_init.c:amd_iommu_resume
  - drivers/iommu/amd_iommu_init.c:iommu_go_to_state
```
**Symbols:**

```
ffffffff8168a990-ffffffff8168ac3d: early_enable_iommus (STB_LOCAL)
ffffffff8168af06-ffffffff8168b236: early_enable_iommus.cold.20 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void early_enable_iommus();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (0)
Location: drivers/iommu/amd_iommu_init.c:2293
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:amd_iommu_resume
```
**Symbols:**

```
ffffffff816c23d0-ffffffff816c267d: early_enable_iommus (STB_LOCAL)
ffffffff816c2970-ffffffff816c2c8a: early_enable_iommus.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void early_enable_iommus();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (0)
Location: drivers/iommu/amd_iommu_init.c:2313
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:amd_iommu_resume
```
**Symbols:**

```
ffffffff816e52f0-ffffffff816e559d: early_enable_iommus (STB_LOCAL)
ffffffff816e5878-ffffffff816e5b93: early_enable_iommus.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void early_enable_iommus();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/init.c (0)
Location: drivers/iommu/amd/init.c:2283
Inline: False
Direct callers:
  - drivers/iommu/amd/init.c:amd_iommu_reenable
  - drivers/iommu/amd/init.c:state_next
```
**Symbols:**

```
ffffffff8179b750-ffffffff8179b8f8: early_enable_iommus (STB_LOCAL)
ffffffff8179c0bd-ffffffff8179c172: early_enable_iommus.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void early_enable_iommus();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/init.c (0)
Location: drivers/iommu/amd/init.c:2487
Inline: False
Direct callers:
  - drivers/iommu/amd/init.c:amd_iommu_reenable
  - drivers/iommu/amd/init.c:state_next
```
**Symbols:**

```
ffffffff817a9b90-ffffffff817a9d3c: early_enable_iommus (STB_LOCAL)
ffffffff81c0be9c-ffffffff81c0bf5d: early_enable_iommus.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void early_enable_iommus();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/init.c (0)
Location: drivers/iommu/amd/init.c:2440
Inline: False
Direct callers:
  - drivers/iommu/amd/init.c:amd_iommu_reenable
  - drivers/iommu/amd/init.c:state_next
```
**Symbols:**

```
ffffffff8178b8c0-ffffffff8178ba72: early_enable_iommus (STB_LOCAL)
ffffffff81bfd548-ffffffff81bfd60f: early_enable_iommus.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void early_enable_iommus();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/init.c (0)
Location: drivers/iommu/amd/init.c:2464
Inline: False
Direct callers:
  - drivers/iommu/amd/init.c:amd_iommu_reenable
  - drivers/iommu/amd/init.c:state_next
```
**Symbols:**

```
ffffffff81812c10-ffffffff81812f82: early_enable_iommus (STB_LOCAL)
ffffffff81cfe870-ffffffff81cfe9b3: early_enable_iommus.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void early_enable_iommus();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/init.c (0)
Location: drivers/iommu/amd/init.c:2478
Inline: False
Direct callers:
  - drivers/iommu/amd/init.c:amd_iommu_reenable
  - drivers/iommu/amd/init.c:state_next
```
**Symbols:**

```
ffffffff81953bd0-ffffffff81953f3f: early_enable_iommus (STB_LOCAL)
ffffffff81ec70bc-ffffffff81ec720f: early_enable_iommus.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void early_enable_iommus();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/init.c (0)
Location: drivers/iommu/amd/init.c:2701
Inline: False
Direct callers:
  - drivers/iommu/amd/init.c:amd_iommu_reenable
  - drivers/iommu/amd/init.c:state_next
```
**Symbols:**

```
ffffffff81ab9670-ffffffff81ab9b5b: early_enable_iommus (STB_LOCAL)
ffffffff8209712d-ffffffff82097162: early_enable_iommus.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void early_enable_iommus();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/init.c (0)
Location: drivers/iommu/amd/init.c:2767
Inline: False
Direct callers:
  - drivers/iommu/amd/init.c:amd_iommu_reenable
  - drivers/iommu/amd/init.c:state_next
```
**Symbols:**

```
ffffffff81b05ae0-ffffffff81b06006: early_enable_iommus (STB_LOCAL)
ffffffff82118076-ffffffff821180ab: early_enable_iommus.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void early_enable_iommus();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/init.c (0)
Location: drivers/iommu/amd/init.c:2787
Inline: False
Direct callers:
  - drivers/iommu/amd/init.c:amd_iommu_reenable
  - drivers/iommu/amd/init.c:state_next
```
**Symbols:**

```
ffffffff81b59880-ffffffff81b59da6: early_enable_iommus (STB_LOCAL)
ffffffff821f5d16-ffffffff821f5d4b: early_enable_iommus.cold (STB_LOCAL)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void early_enable_iommus();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (0)
Location: drivers/iommu/amd_iommu_init.c:2313
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:amd_iommu_resume
```
**Symbols:**

```
ffffffff816aadd0-ffffffff816ab07d: early_enable_iommus (STB_LOCAL)
ffffffff816ab358-ffffffff816ab673: early_enable_iommus.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void early_enable_iommus();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (0)
Location: drivers/iommu/amd_iommu_init.c:2313
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:amd_iommu_resume
```
**Symbols:**

```
ffffffff81688730-ffffffff816889dd: early_enable_iommus (STB_LOCAL)
ffffffff81688cb8-ffffffff81688fd3: early_enable_iommus.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void early_enable_iommus();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (0)
Location: drivers/iommu/amd_iommu_init.c:2313
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:amd_iommu_resume
```
**Symbols:**

```
ffffffff816d8fb0-ffffffff816d925d: early_enable_iommus (STB_LOCAL)
ffffffff816d9538-ffffffff816d9853: early_enable_iommus.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void early_enable_iommus();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (0)
Location: drivers/iommu/amd_iommu_init.c:2313
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:amd_iommu_resume
```
**Symbols:**

```
ffffffff816f3560-ffffffff816f380d: early_enable_iommus (STB_LOCAL)
ffffffff816f3ae8-ffffffff816f3e03: early_enable_iommus.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
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
