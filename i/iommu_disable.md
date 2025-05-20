# Function: <code>iommu_disable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff81532850)
Location: drivers/iommu/amd_iommu_init.c:361
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:amd_iommu_disable
```
**Symbols:**

```
ffffffff81532850-ffffffff81532897: iommu_disable.isra.5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff81587030)
Location: drivers/iommu/amd_iommu_init.c:380
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu_init.c:amd_iommu_disable
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
```
**Symbols:**

```
ffffffff81587030-ffffffff81587077: iommu_disable.isra.5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void iommu_disable(struct amd_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff815b4300)
Location: drivers/iommu/amd_iommu_init.c:385
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
```
**Symbols:**

```
ffffffff815b4300-ffffffff815b4375: iommu_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void iommu_disable(struct amd_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff815ca0d0)
Location: drivers/iommu/amd_iommu_init.c:392
Inline: False
```
**Symbols:**

```
ffffffff815ca0d0-ffffffff815ca145: iommu_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void iommu_disable(struct amd_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff81630ac0)
Location: drivers/iommu/amd_iommu_init.c:421
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
```
**Symbols:**

```
ffffffff81630ac0-ffffffff81630b35: iommu_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void iommu_disable(struct amd_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff8166b970)
Location: drivers/iommu/amd_iommu_init.c:421
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
```
**Symbols:**

```
ffffffff8166b970-ffffffff8166b9e5: iommu_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void iommu_disable(struct amd_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff8168a0b0)
Location: drivers/iommu/amd_iommu_init.c:424
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
```
**Symbols:**

```
ffffffff8168a0b0-ffffffff8168a136: iommu_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void iommu_disable(struct amd_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff816c18e0)
Location: drivers/iommu/amd_iommu_init.c:409
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:init_iommu_all
```
**Symbols:**

```
ffffffff816c18e0-ffffffff816c196b: iommu_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void iommu_disable(struct amd_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff816e4800)
Location: drivers/iommu/amd_iommu_init.c:410
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:init_iommu_all
```
**Symbols:**

```
ffffffff816e4800-ffffffff816e488b: iommu_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void iommu_disable(struct amd_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff8179a8f0)
Location: drivers/iommu/amd/init.c:410
Inline: False
Direct callers:
  - drivers/iommu/amd/init.c:amd_iommu_disable
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:init_iommu_one
```
**Symbols:**

```
ffffffff8179a8f0-ffffffff8179a97b: iommu_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void iommu_disable(struct amd_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff817a8c20)
Location: drivers/iommu/amd/init.c:451
Inline: False
Direct callers:
  - drivers/iommu/amd/init.c:amd_iommu_disable
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:init_iommu_one
```
**Symbols:**

```
ffffffff817a8c20-ffffffff817a8cab: iommu_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void iommu_disable(struct amd_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff8178a9a0)
Location: drivers/iommu/amd/init.c:447
Inline: False
Direct callers:
  - drivers/iommu/amd/init.c:amd_iommu_disable
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:init_iommu_one
```
**Symbols:**

```
ffffffff8178a9a0-ffffffff8178aa30: iommu_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff8181311a)
Location: drivers/iommu/amd/init.c:464
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:amd_iommu_disable
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:init_iommu_one
Direct callers:
  - drivers/iommu/amd/init.c:amd_iommu_disable
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:init_iommu_one
```
**Symbols:**

```
ffffffff818124e0-ffffffff8181256b: iommu_disable.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff8195409a)
Location: drivers/iommu/amd/init.c:468
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:amd_iommu_disable
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:init_iommu_one
Direct callers:
  - drivers/iommu/amd/init.c:amd_iommu_disable
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:init_iommu_one
```
**Symbols:**

```
ffffffff81953410-ffffffff819534a9: iommu_disable.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff81ab9d3a)
Location: drivers/iommu/amd/init.c:462
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:amd_iommu_disable
  - drivers/iommu/amd/init.c:state_next
  - drivers/iommu/amd/init.c:early_amd_iommu_init
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:init_iommu_one_late
Direct callers:
  - drivers/iommu/amd/init.c:amd_iommu_disable
  - drivers/iommu/amd/init.c:state_next
  - drivers/iommu/amd/init.c:early_amd_iommu_init
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:init_iommu_one_late
```
**Symbols:**

```
ffffffff81ab8c70-ffffffff81ab8d09: iommu_disable.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff81b062da)
Location: drivers/iommu/amd/init.c:470
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:amd_iommu_disable
  - drivers/iommu/amd/init.c:state_next
  - drivers/iommu/amd/init.c:early_amd_iommu_init
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:init_iommu_one_late
Direct callers:
  - drivers/iommu/amd/init.c:amd_iommu_disable
  - drivers/iommu/amd/init.c:state_next
  - drivers/iommu/amd/init.c:early_amd_iommu_init
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:init_iommu_one_late
```
**Symbols:**

```
ffffffff81b050d0-ffffffff81b0517e: iommu_disable.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff81b5a07a)
Location: drivers/iommu/amd/init.c:455
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:amd_iommu_disable
  - drivers/iommu/amd/init.c:state_next
  - drivers/iommu/amd/init.c:early_amd_iommu_init
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:init_iommu_one_late
Direct callers:
  - drivers/iommu/amd/init.c:amd_iommu_disable
  - drivers/iommu/amd/init.c:state_next
  - drivers/iommu/amd/init.c:early_amd_iommu_init
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:init_iommu_one_late
```
**Symbols:**

```
ffffffff81b58d90-ffffffff81b58e64: iommu_disable.part.0 (STB_LOCAL)
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
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/omap-iommu.c (c09c3fb0)
Location: drivers/iommu/omap-iommu.c:215
Inline: True
Inline callers:
  - drivers/iommu/omap-iommu.c:omap_iommu_detach
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
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void iommu_disable(struct amd_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff816aa2e0)
Location: drivers/iommu/amd_iommu_init.c:410
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:init_iommu_all
```
**Symbols:**

```
ffffffff816aa2e0-ffffffff816aa36b: iommu_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void iommu_disable(struct amd_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff81687c40)
Location: drivers/iommu/amd_iommu_init.c:410
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:init_iommu_all
```
**Symbols:**

```
ffffffff81687c40-ffffffff81687ccb: iommu_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void iommu_disable(struct amd_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff816d84c0)
Location: drivers/iommu/amd_iommu_init.c:410
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:init_iommu_all
```
**Symbols:**

```
ffffffff816d84c0-ffffffff816d854b: iommu_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void iommu_disable(struct amd_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff816f2a70)
Location: drivers/iommu/amd_iommu_init.c:410
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:init_iommu_all
```
**Symbols:**

```
ffffffff816f2a70-ffffffff816f2afb: iommu_disable (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
