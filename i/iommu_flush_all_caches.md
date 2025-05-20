# Function: <code>iommu_flush_all_caches</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void iommu_flush_all_caches(struct amd_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff815323c0)
Location: drivers/iommu/amd_iommu.c:981
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:state_next
```
**Symbols:**

```
ffffffff815323c0-ffffffff815324ca: iommu_flush_all_caches (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void iommu_flush_all_caches(struct amd_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff81586b90)
Location: drivers/iommu/amd_iommu.c:1077
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
```
**Symbols:**

```
ffffffff81586b90-ffffffff81586ca6: iommu_flush_all_caches (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void iommu_flush_all_caches(struct amd_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff815b4150)
Location: drivers/iommu/amd_iommu.c:1166
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci
```
**Symbols:**

```
ffffffff815b4150-ffffffff815b4297: iommu_flush_all_caches (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void iommu_flush_all_caches(struct amd_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff815c9ee0)
Location: drivers/iommu/amd_iommu.c:1225
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci
```
**Symbols:**

```
ffffffff815c9ee0-ffffffff815ca030: iommu_flush_all_caches (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void iommu_flush_all_caches(struct amd_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816308b0)
Location: drivers/iommu/amd_iommu.c:1166
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci
```
**Symbols:**

```
ffffffff816308b0-ffffffff81630a00: iommu_flush_all_caches (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void iommu_flush_all_caches(struct amd_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff8166b300)
Location: drivers/iommu/amd_iommu.c:1172
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu_init.c:amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:iommu_go_to_state
```
**Symbols:**

```
ffffffff8166b300-ffffffff8166b458: iommu_flush_all_caches (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void iommu_flush_all_caches(struct amd_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff81689a10)
Location: drivers/iommu/amd_iommu.c:1187
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu_init.c:amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:iommu_go_to_state
```
**Symbols:**

```
ffffffff81689a10-ffffffff81689b68: iommu_flush_all_caches (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void iommu_flush_all_caches(struct amd_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816c0ff0)
Location: drivers/iommu/amd_iommu.c:1186
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
```
**Symbols:**

```
ffffffff816c0ff0-ffffffff816c1142: iommu_flush_all_caches (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void iommu_flush_all_caches(struct amd_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816e4060)
Location: drivers/iommu/amd_iommu.c:1193
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
```
**Symbols:**

```
ffffffff816e4060-ffffffff816e41a7: iommu_flush_all_caches (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void iommu_flush_all_caches(struct amd_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff8179a280)
Location: drivers/iommu/amd/iommu.c:1137
Inline: False
Direct callers:
  - drivers/iommu/amd/init.c:state_next
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:amd_iommu_init_pci
```
**Symbols:**

```
ffffffff8179a280-ffffffff8179a455: iommu_flush_all_caches (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void iommu_flush_all_caches(struct amd_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff817a8990)
Location: drivers/iommu/amd/iommu.c:1227
Inline: False
Direct callers:
  - drivers/iommu/amd/init.c:state_next
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:amd_iommu_init_pci
```
**Symbols:**

```
ffffffff817a8990-ffffffff817a8b5e: iommu_flush_all_caches (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void iommu_flush_all_caches(struct amd_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81789600)
Location: drivers/iommu/amd/iommu.c:1159
Inline: False
Direct callers:
  - drivers/iommu/amd/init.c:state_next
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:amd_iommu_init_pci
```
**Symbols:**

```
ffffffff81789600-ffffffff81789839: iommu_flush_all_caches (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void iommu_flush_all_caches(struct amd_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/iommu.c (0)
Location: drivers/iommu/amd/iommu.c:1171
Inline: False
Direct callers:
  - drivers/iommu/amd/init.c:state_next
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:amd_iommu_init_pci
```
**Symbols:**

```
ffffffff81cfe2cf-ffffffff81cfe31f: iommu_flush_all_caches.cold (STB_LOCAL)
ffffffff818107f0-ffffffff81810a50: iommu_flush_all_caches (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void iommu_flush_all_caches(struct amd_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81952540)
Location: drivers/iommu/amd/iommu.c:1193
Inline: False
Direct callers:
  - drivers/iommu/amd/init.c:state_next
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:amd_iommu_init_pci
```
**Symbols:**

```
ffffffff81952540-ffffffff81952758: iommu_flush_all_caches (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void iommu_flush_all_caches(struct amd_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81ab7730)
Location: drivers/iommu/amd/iommu.c:1265
Inline: False
Direct callers:
  - drivers/iommu/amd/init.c:state_next
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:amd_iommu_init_pci
```
**Symbols:**

```
ffffffff81ab7730-ffffffff81ab795c: iommu_flush_all_caches (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void iommu_flush_all_caches(struct amd_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/iommu.c (0)
Location: drivers/iommu/amd/iommu.c:1285
Inline: False
Direct callers:
  - drivers/iommu/amd/init.c:state_next
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:amd_iommu_init_pci
```
**Symbols:**

```
ffffffff82117ef8-ffffffff82117f0c: iommu_flush_all_caches.cold (STB_LOCAL)
ffffffff81b03990-ffffffff81b03b73: iommu_flush_all_caches (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
<summary>In <code>aws</code>: ✅</summary>

```c
void iommu_flush_all_caches(struct amd_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816a9b40)
Location: drivers/iommu/amd_iommu.c:1193
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
```
**Symbols:**

```
ffffffff816a9b40-ffffffff816a9c87: iommu_flush_all_caches (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void iommu_flush_all_caches(struct amd_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816874a0)
Location: drivers/iommu/amd_iommu.c:1193
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
```
**Symbols:**

```
ffffffff816874a0-ffffffff816875e7: iommu_flush_all_caches (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void iommu_flush_all_caches(struct amd_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816d7d20)
Location: drivers/iommu/amd_iommu.c:1193
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
```
**Symbols:**

```
ffffffff816d7d20-ffffffff816d7e67: iommu_flush_all_caches (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void iommu_flush_all_caches(struct amd_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816f22d0)
Location: drivers/iommu/amd_iommu.c:1193
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
```
**Symbols:**

```
ffffffff816f22d0-ffffffff816f2417: iommu_flush_all_caches (STB_GLOBAL)
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
