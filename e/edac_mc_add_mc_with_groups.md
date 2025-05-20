# Function: <code>edac_mc_add_mc_with_groups</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int edac_mc_add_mc_with_groups(struct mem_ctl_info *mci, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_mc.c (ffffffff8175bd50)
Location: drivers/edac/edac_mc.c:706
Inline: False
```
**Symbols:**

```
ffffffff8175bd50-ffffffff8175c08d: edac_mc_add_mc_with_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int edac_mc_add_mc_with_groups(struct mem_ctl_info *mci, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_mc.c (ffffffff817cdfa0)
Location: drivers/edac/edac_mc.c:711
Inline: False
Direct callers:
  - drivers/edac/ghes_edac.c:ghes_edac_register
```
**Symbols:**

```
ffffffff817cdfa0-ffffffff817ce2ce: edac_mc_add_mc_with_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int edac_mc_add_mc_with_groups(struct mem_ctl_info *mci, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/edac/edac_mc.c (0)
Location: drivers/edac/edac_mc.c:713
Inline: False
Direct callers:
  - drivers/edac/ghes_edac.c:ghes_edac_register
```
**Symbols:**

```
ffffffff81818431-ffffffff81818516: edac_mc_add_mc_with_groups.cold.13 (STB_LOCAL)
ffffffff81816d90-ffffffff81816ff2: edac_mc_add_mc_with_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int edac_mc_add_mc_with_groups(struct mem_ctl_info *mci, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/edac/edac_mc.c (0)
Location: drivers/edac/edac_mc.c:711
Inline: False
Direct callers:
  - drivers/edac/ghes_edac.c:ghes_edac_register
```
**Symbols:**

```
ffffffff81843ce1-ffffffff81843daf: edac_mc_add_mc_with_groups.cold.14 (STB_LOCAL)
ffffffff81842670-ffffffff81842899: edac_mc_add_mc_with_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int edac_mc_add_mc_with_groups(struct mem_ctl_info *mci, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/edac/edac_mc.c (0)
Location: drivers/edac/edac_mc.c:707
Inline: False
Direct callers:
  - drivers/edac/ghes_edac.c:ghes_edac_register
```
**Symbols:**

```
ffffffff81886aa1-ffffffff81886b5d: edac_mc_add_mc_with_groups.cold (STB_LOCAL)
ffffffff818854d0-ffffffff818856ac: edac_mc_add_mc_with_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int edac_mc_add_mc_with_groups(struct mem_ctl_info *mci, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/edac/edac_mc.c (0)
Location: drivers/edac/edac_mc.c:700
Inline: False
Direct callers:
  - drivers/edac/ghes_edac.c:ghes_edac_register
```
**Symbols:**

```
ffffffff818b8a61-ffffffff818b8b1d: edac_mc_add_mc_with_groups.cold (STB_LOCAL)
ffffffff818b7470-ffffffff818b764c: edac_mc_add_mc_with_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int edac_mc_add_mc_with_groups(struct mem_ctl_info *mci, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/edac/edac_mc.c (0)
Location: drivers/edac/edac_mc.c:669
Inline: False
Direct callers:
  - drivers/edac/ghes_edac.c:ghes_edac_register
```
**Symbols:**

```
ffffffff8198933e-ffffffff81989365: edac_mc_add_mc_with_groups.cold (STB_LOCAL)
ffffffff81988090-ffffffff8198821e: edac_mc_add_mc_with_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int edac_mc_add_mc_with_groups(struct mem_ctl_info *mci, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/edac/edac_mc.c (0)
Location: drivers/edac/edac_mc.c:673
Inline: False
Direct callers:
  - drivers/edac/ghes_edac.c:ghes_edac_register
```
**Symbols:**

```
ffffffff81c28773-ffffffff81c2879a: edac_mc_add_mc_with_groups.cold (STB_LOCAL)
ffffffff8198bfc0-ffffffff8198c14e: edac_mc_add_mc_with_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int edac_mc_add_mc_with_groups(struct mem_ctl_info *mci, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/edac/edac_mc.c (0)
Location: drivers/edac/edac_mc.c:673
Inline: False
Direct callers:
  - drivers/edac/ghes_edac.c:ghes_edac_register
```
**Symbols:**

```
ffffffff81c1a8f5-ffffffff81c1a97c: edac_mc_add_mc_with_groups.cold (STB_LOCAL)
ffffffff819705d0-ffffffff819707c7: edac_mc_add_mc_with_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int edac_mc_add_mc_with_groups(struct mem_ctl_info *mci, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/edac/edac_mc.c (0)
Location: drivers/edac/edac_mc.c:676
Inline: False
Direct callers:
  - drivers/edac/ghes_edac.c:ghes_edac_register
```
**Symbols:**

```
ffffffff81d2a7f1-ffffffff81d2a878: edac_mc_add_mc_with_groups.cold (STB_LOCAL)
ffffffff81a18ef0-ffffffff81a190e7: edac_mc_add_mc_with_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int edac_mc_add_mc_with_groups(struct mem_ctl_info *mci, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/edac/edac_mc.c (0)
Location: drivers/edac/edac_mc.c:601
Inline: False
Direct callers:
  - drivers/edac/ghes_edac.c:ghes_edac_register
```
**Symbols:**

```
ffffffff81ef69d6-ffffffff81ef6a48: edac_mc_add_mc_with_groups.cold (STB_LOCAL)
ffffffff81b81cb0-ffffffff81b81e9a: edac_mc_add_mc_with_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int edac_mc_add_mc_with_groups(struct mem_ctl_info *mci, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_mc.c (ffffffff81d20400)
Location: drivers/edac/edac_mc.c:600
Inline: False
```
**Symbols:**

```
ffffffff81d20400-ffffffff81d206bb: edac_mc_add_mc_with_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int edac_mc_add_mc_with_groups(struct mem_ctl_info *mci, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_mc.c (ffffffff81d895e0)
Location: drivers/edac/edac_mc.c:600
Inline: False
```
**Symbols:**

```
ffffffff81d895e0-ffffffff81d8989b: edac_mc_add_mc_with_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int edac_mc_add_mc_with_groups(struct mem_ctl_info *mci, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_mc.c (ffffffff81e40d20)
Location: drivers/edac/edac_mc.c:601
Inline: False
```
**Symbols:**

```
ffffffff81e40d20-ffffffff81e40fdb: edac_mc_add_mc_with_groups (STB_GLOBAL)
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
int edac_mc_add_mc_with_groups(struct mem_ctl_info *mci, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_mc.c (ffff800010b0f558)
Location: drivers/edac/edac_mc.c:700
Inline: False
Direct callers:
  - drivers/edac/ghes_edac.c:ghes_edac_register
  - drivers/edac/altera_edac.c:altr_sdram_probe
```
**Symbols:**

```
ffff800010b0f558-ffff800010b0f7d4: edac_mc_add_mc_with_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int edac_mc_add_mc_with_groups(struct mem_ctl_info *mci, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_mc.c (c0bed844)
Location: drivers/edac/edac_mc.c:700
Inline: False
Direct callers:
  - drivers/edac/armada_xp_edac.c:axp_mc_probe
```
**Symbols:**

```
c0bed844-c0bedaac: edac_mc_add_mc_with_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int edac_mc_add_mc_with_groups(struct mem_ctl_info *mci, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_mc.c (c000000000c02b20)
Location: drivers/edac/edac_mc.c:700
Inline: False
```
**Symbols:**

```
c000000000c02b20-c000000000c02e3c: edac_mc_add_mc_with_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int edac_mc_add_mc_with_groups(struct mem_ctl_info *mci, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_mc.c (ffffffe0006fc696)
Location: drivers/edac/edac_mc.c:700
Inline: False
```
**Symbols:**

```
ffffffe0006fc696-ffffffe0006fc8de: edac_mc_add_mc_with_groups (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int edac_mc_add_mc_with_groups(struct mem_ctl_info *mci, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/edac/edac_mc.c (0)
Location: drivers/edac/edac_mc.c:700
Inline: False
```
**Symbols:**

```
ffffffff8185e8e1-ffffffff8185e99d: edac_mc_add_mc_with_groups.cold (STB_LOCAL)
ffffffff8185d2f0-ffffffff8185d4cc: edac_mc_add_mc_with_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int edac_mc_add_mc_with_groups(struct mem_ctl_info *mci, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/edac/edac_mc.c (0)
Location: drivers/edac/edac_mc.c:700
Inline: False
```
**Symbols:**

```
ffffffff81825eb1-ffffffff81825f6d: edac_mc_add_mc_with_groups.cold (STB_LOCAL)
ffffffff818248c0-ffffffff81824a9c: edac_mc_add_mc_with_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int edac_mc_add_mc_with_groups(struct mem_ctl_info *mci, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/edac/edac_mc.c (0)
Location: drivers/edac/edac_mc.c:700
Inline: False
Direct callers:
  - drivers/edac/ghes_edac.c:ghes_edac_register
```
**Symbols:**

```
ffffffff818adf11-ffffffff818adfcd: edac_mc_add_mc_with_groups.cold (STB_LOCAL)
ffffffff818ac920-ffffffff818acafc: edac_mc_add_mc_with_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int edac_mc_add_mc_with_groups(struct mem_ctl_info *mci, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/edac/edac_mc.c (0)
Location: drivers/edac/edac_mc.c:700
Inline: False
Direct callers:
  - drivers/edac/ghes_edac.c:ghes_edac_register
```
**Symbols:**

```
ffffffff818ca1a1-ffffffff818ca25d: edac_mc_add_mc_with_groups.cold (STB_LOCAL)
ffffffff818c8b70-ffffffff818c8d4c: edac_mc_add_mc_with_groups (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
