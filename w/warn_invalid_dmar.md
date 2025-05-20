# Function: <code>warn_invalid_dmar</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void warn_invalid_dmar(u64 addr, const char *message);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff81533140)
Location: drivers/iommu/dmar.c:821
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:dmar_validate_one_drhd
  - drivers/iommu/dmar.c:dmar_validate_one_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
```
**Symbols:**

```
ffffffff81533140-ffffffff815331cd: warn_invalid_dmar (STB_LOCAL)
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
In drivers/iommu/dmar.c (ffffffff8189579c)
Location: drivers/iommu/dmar.c:833
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_validate_one_drhd
  - drivers/iommu/dmar.c:dmar_validate_one_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
Direct callers:
  - drivers/iommu/dmar.c:dmar_validate_one_drhd
  - drivers/iommu/dmar.c:dmar_validate_one_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
```
**Symbols:**

```
ffffffff81587c80-ffffffff81587d03: warn_invalid_dmar.part.8 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff818c9fec)
Location: drivers/iommu/dmar.c:832
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_validate_one_drhd
  - drivers/iommu/dmar.c:dmar_validate_one_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
Direct callers:
  - drivers/iommu/dmar.c:dmar_validate_one_drhd
  - drivers/iommu/dmar.c:dmar_validate_one_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
```
**Symbols:**

```
ffffffff815b5340-ffffffff815b53c3: warn_invalid_dmar.part.10 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff8190156c)
Location: drivers/iommu/dmar.c:836
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_validate_one_drhd
  - drivers/iommu/dmar.c:dmar_validate_one_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
Direct callers:
  - drivers/iommu/dmar.c:dmar_validate_one_drhd
  - drivers/iommu/dmar.c:dmar_validate_one_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
```
**Symbols:**

```
ffffffff815cb1e0-ffffffff815cb247: warn_invalid_dmar.part.12 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff8198b59c)
Location: drivers/iommu/dmar.c:839
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_validate_one_drhd
  - drivers/iommu/dmar.c:dmar_validate_one_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
Direct callers:
  - drivers/iommu/dmar.c:dmar_validate_one_drhd
  - drivers/iommu/dmar.c:dmar_validate_one_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
```
**Symbols:**

```
ffffffff81631fb0-ffffffff81632017: warn_invalid_dmar.part.11 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff819e7f28)
Location: drivers/iommu/dmar.c:839
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_validate_one_drhd
  - drivers/iommu/dmar.c:dmar_validate_one_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
Direct callers:
  - drivers/iommu/dmar.c:dmar_validate_one_drhd
  - drivers/iommu/dmar.c:dmar_validate_one_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
```
**Symbols:**

```
ffffffff8166d380-ffffffff8166d3e7: warn_invalid_dmar.part.12 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff81a23398)
Location: drivers/iommu/dmar.c:839
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_validate_one_drhd
  - drivers/iommu/dmar.c:dmar_validate_one_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
Direct callers:
  - drivers/iommu/dmar.c:dmar_validate_one_drhd
  - drivers/iommu/dmar.c:dmar_validate_one_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
```
**Symbols:**

```
ffffffff8168b790-ffffffff8168b7f7: warn_invalid_dmar.part.11 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff816c3acc)
Location: drivers/iommu/dmar.c:828
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/iommu/dmar.c:dmar_validate_one_drhd
  - drivers/iommu/dmar.c:dmar_validate_one_drhd
Direct callers:
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/iommu/dmar.c:dmar_validate_one_drhd
  - drivers/iommu/dmar.c:dmar_validate_one_drhd
```
**Symbols:**

```
ffffffff816c3180-ffffffff816c31e7: warn_invalid_dmar.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void warn_invalid_dmar(u64 addr, const char *message);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff816e5ba0)
Location: drivers/iommu/dmar.c:838
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/iommu/dmar.c:dmar_validate_one_drhd
  - drivers/iommu/dmar.c:dmar_validate_one_drhd
```
**Symbols:**

```
ffffffff816e5ba0-ffffffff816e5c25: warn_invalid_dmar (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void warn_invalid_dmar(u64 addr, const char *message);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/dmar.c (ffffffff8179c1a0)
Location: drivers/iommu/intel/dmar.c:838
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:alloc_iommu
  - drivers/iommu/intel/dmar.c:map_iommu
  - drivers/iommu/intel/dmar.c:dmar_validate_one_drhd
  - drivers/iommu/intel/dmar.c:dmar_validate_one_drhd
```
**Symbols:**

```
ffffffff8179c1a0-ffffffff8179c225: warn_invalid_dmar (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void warn_invalid_dmar(u64 addr, const char *message);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/dmar.c (ffffffff817a9e70)
Location: drivers/iommu/intel/dmar.c:860
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:alloc_iommu
  - drivers/iommu/intel/dmar.c:map_iommu
  - drivers/iommu/intel/dmar.c:dmar_validate_one_drhd
  - drivers/iommu/intel/dmar.c:dmar_validate_one_drhd
```
**Symbols:**

```
ffffffff817a9e70-ffffffff817a9ef5: warn_invalid_dmar (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void warn_invalid_dmar(u64 addr, const char *message);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/dmar.c (ffffffff8178cb30)
Location: drivers/iommu/intel/dmar.c:867
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:alloc_iommu
  - drivers/iommu/intel/dmar.c:map_iommu
  - drivers/iommu/intel/dmar.c:dmar_validate_one_drhd
  - drivers/iommu/intel/dmar.c:dmar_validate_one_drhd
```
**Symbols:**

```
ffffffff8178cb30-ffffffff8178cbb2: warn_invalid_dmar (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void warn_invalid_dmar(u64 addr, const char *message);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/dmar.c (0)
Location: drivers/iommu/intel/dmar.c:866
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:alloc_iommu
  - drivers/iommu/intel/dmar.c:map_iommu
  - drivers/iommu/intel/dmar.c:dmar_validate_one_drhd
  - drivers/iommu/intel/dmar.c:dmar_validate_one_drhd
```
**Symbols:**

```
ffffffff818145d0-ffffffff81814658: warn_invalid_dmar (STB_LOCAL)
ffffffff81cfecf1-ffffffff81cfed05: warn_invalid_dmar.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void warn_invalid_dmar(u64 addr, const char *message);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/dmar.c (0)
Location: drivers/iommu/intel/dmar.c:864
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:alloc_iommu
  - drivers/iommu/intel/dmar.c:map_iommu
  - drivers/iommu/intel/dmar.c:dmar_validate_one_drhd
  - drivers/iommu/intel/dmar.c:dmar_validate_one_drhd
```
**Symbols:**

```
ffffffff81955440-ffffffff819554dc: warn_invalid_dmar (STB_LOCAL)
ffffffff81ec74fe-ffffffff81ec7512: warn_invalid_dmar.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void warn_invalid_dmar(u64 addr, const char *message);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/dmar.c (0)
Location: drivers/iommu/intel/dmar.c:865
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:alloc_iommu
  - drivers/iommu/intel/dmar.c:map_iommu
  - drivers/iommu/intel/dmar.c:dmar_validate_one_drhd
  - drivers/iommu/intel/dmar.c:dmar_validate_one_drhd
```
**Symbols:**

```
ffffffff81abba60-ffffffff81abbafc: warn_invalid_dmar (STB_LOCAL)
ffffffff82097320-ffffffff82097334: warn_invalid_dmar.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void warn_invalid_dmar(u64 addr, const char *message);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/dmar.c (0)
Location: drivers/iommu/intel/dmar.c:867
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:alloc_iommu
  - drivers/iommu/intel/dmar.c:map_iommu
  - drivers/iommu/intel/dmar.c:dmar_validate_one_drhd
  - drivers/iommu/intel/dmar.c:dmar_validate_one_drhd
```
**Symbols:**

```
ffffffff81b08340-ffffffff81b083dc: warn_invalid_dmar (STB_LOCAL)
ffffffff82118362-ffffffff82118376: warn_invalid_dmar.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void warn_invalid_dmar(u64 addr, const char *message);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/dmar.c (0)
Location: drivers/iommu/intel/dmar.c:867
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:alloc_iommu
  - drivers/iommu/intel/dmar.c:map_iommu
  - drivers/iommu/intel/dmar.c:dmar_validate_one_drhd
  - drivers/iommu/intel/dmar.c:dmar_validate_one_drhd
```
**Symbols:**

```
ffffffff81b5c360-ffffffff81b5c3fc: warn_invalid_dmar (STB_LOCAL)
ffffffff821f6076-ffffffff821f608a: warn_invalid_dmar.cold (STB_LOCAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
void warn_invalid_dmar(u64 addr, const char *message);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff816ab680)
Location: drivers/iommu/dmar.c:838
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/iommu/dmar.c:dmar_validate_one_drhd
  - drivers/iommu/dmar.c:dmar_validate_one_drhd
```
**Symbols:**

```
ffffffff816ab680-ffffffff816ab705: warn_invalid_dmar (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void warn_invalid_dmar(u64 addr, const char *message);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff81688fe0)
Location: drivers/iommu/dmar.c:838
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/iommu/dmar.c:dmar_validate_one_drhd
  - drivers/iommu/dmar.c:dmar_validate_one_drhd
```
**Symbols:**

```
ffffffff81688fe0-ffffffff81689065: warn_invalid_dmar (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void warn_invalid_dmar(u64 addr, const char *message);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff816d9860)
Location: drivers/iommu/dmar.c:838
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/iommu/dmar.c:dmar_validate_one_drhd
  - drivers/iommu/dmar.c:dmar_validate_one_drhd
```
**Symbols:**

```
ffffffff816d9860-ffffffff816d98e5: warn_invalid_dmar (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void warn_invalid_dmar(u64 addr, const char *message);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff816f3e10)
Location: drivers/iommu/dmar.c:838
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/iommu/dmar.c:dmar_validate_one_drhd
  - drivers/iommu/dmar.c:dmar_validate_one_drhd
```
**Symbols:**

```
ffffffff816f3e10-ffffffff816f3e95: warn_invalid_dmar (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
