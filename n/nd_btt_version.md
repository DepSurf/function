# Function: <code>nd_btt_version</code>

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
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int nd_btt_version(struct nd_btt *nd_btt, struct nd_namespace_common *ndns, struct btt_sb *btt_sb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/btt_devs.c (ffffffff8163ac70)
Location: drivers/nvdimm/btt_devs.c:263
Inline: True
Direct callers:
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
```
**Symbols:**

```
ffffffff8163ac70-ffffffff8163ad2c: nd_btt_version (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int nd_btt_version(struct nd_btt *nd_btt, struct nd_namespace_common *ndns, struct btt_sb *btt_sb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/btt_devs.c (ffffffff816a3870)
Location: drivers/nvdimm/btt_devs.c:263
Inline: True
Direct callers:
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
```
**Symbols:**

```
ffffffff816a3870-ffffffff816a3931: nd_btt_version (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int nd_btt_version(struct nd_btt *nd_btt, struct nd_namespace_common *ndns, struct btt_sb *btt_sb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/btt_devs.c (ffffffff816df9e0)
Location: drivers/nvdimm/btt_devs.c:263
Inline: True
Direct callers:
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
```
**Symbols:**

```
ffffffff816df9e0-ffffffff816dfaa1: nd_btt_version (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int nd_btt_version(struct nd_btt *nd_btt, struct nd_namespace_common *ndns, struct btt_sb *btt_sb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/btt_devs.c (ffffffff81701d90)
Location: drivers/nvdimm/btt_devs.c:263
Inline: True
Direct callers:
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
```
**Symbols:**

```
ffffffff81701d90-ffffffff81701e51: nd_btt_version (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int nd_btt_version(struct nd_btt *nd_btt, struct nd_namespace_common *ndns, struct btt_sb *btt_sb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/btt_devs.c (ffffffff8173bbf0)
Location: drivers/nvdimm/btt_devs.c:271
Inline: True
Direct callers:
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
```
**Symbols:**

```
ffffffff8173bbf0-ffffffff8173bcb1: nd_btt_version (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int nd_btt_version(struct nd_btt *nd_btt, struct nd_namespace_common *ndns, struct btt_sb *btt_sb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/btt_devs.c (ffffffff8175f910)
Location: drivers/nvdimm/btt_devs.c:271
Inline: True
Direct callers:
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
```
**Symbols:**

```
ffffffff8175f910-ffffffff8175f9d1: nd_btt_version (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int nd_btt_version(struct nd_btt *nd_btt, struct nd_namespace_common *ndns, struct btt_sb *btt_sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/btt_devs.c (ffffffff8181eff0)
Location: drivers/nvdimm/btt_devs.c:271
Inline: False
Direct callers:
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
```
**Symbols:**

```
ffffffff8181eff0-ffffffff8181f0b1: nd_btt_version (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int nd_btt_version(struct nd_btt *nd_btt, struct nd_namespace_common *ndns, struct btt_sb *btt_sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/btt_devs.c (ffffffff8182df30)
Location: drivers/nvdimm/btt_devs.c:271
Inline: False
Direct callers:
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
```
**Symbols:**

```
ffffffff8182df30-ffffffff8182dff1: nd_btt_version (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int nd_btt_version(struct nd_btt *nd_btt, struct nd_namespace_common *ndns, struct btt_sb *btt_sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/btt_devs.c (ffffffff81811200)
Location: drivers/nvdimm/btt_devs.c:271
Inline: False
Direct callers:
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
```
**Symbols:**

```
ffffffff81811200-ffffffff818112c1: nd_btt_version (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int nd_btt_version(struct nd_btt *nd_btt, struct nd_namespace_common *ndns, struct btt_sb *btt_sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/btt_devs.c (ffffffff8189be40)
Location: drivers/nvdimm/btt_devs.c:271
Inline: False
Direct callers:
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
```
**Symbols:**

```
ffffffff8189be40-ffffffff8189bf01: nd_btt_version (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int nd_btt_version(struct nd_btt *nd_btt, struct nd_namespace_common *ndns, struct btt_sb *btt_sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/btt_devs.c (ffffffff819e5680)
Location: drivers/nvdimm/btt_devs.c:275
Inline: False
Direct callers:
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
```
**Symbols:**

```
ffffffff819e5680-ffffffff819e5753: nd_btt_version (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int nd_btt_version(struct nd_btt *nd_btt, struct nd_namespace_common *ndns, struct btt_sb *btt_sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/btt_devs.c (ffffffff81b61540)
Location: drivers/nvdimm/btt_devs.c:275
Inline: False
Direct callers:
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
```
**Symbols:**

```
ffffffff81b61540-ffffffff81b61613: nd_btt_version (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int nd_btt_version(struct nd_btt *nd_btt, struct nd_namespace_common *ndns, struct btt_sb *btt_sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/btt_devs.c (ffffffff81bb4b00)
Location: drivers/nvdimm/btt_devs.c:275
Inline: False
Direct callers:
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
```
**Symbols:**

```
ffffffff81bb4b00-ffffffff81bb4bd3: nd_btt_version (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int nd_btt_version(struct nd_btt *nd_btt, struct nd_namespace_common *ndns, struct btt_sb *btt_sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/btt_devs.c (ffffffff81c09080)
Location: drivers/nvdimm/btt_devs.c:275
Inline: False
Direct callers:
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
```
**Symbols:**

```
ffffffff81c09080-ffffffff81c09153: nd_btt_version (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int nd_btt_version(struct nd_btt *nd_btt, struct nd_namespace_common *ndns, struct btt_sb *btt_sb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/btt_devs.c (ffff8000109612e8)
Location: drivers/nvdimm/btt_devs.c:271
Inline: True
Direct callers:
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
```
**Symbols:**

```
ffff8000109612e8-ffff8000109613e8: nd_btt_version (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int nd_btt_version(struct nd_btt *nd_btt, struct nd_namespace_common *ndns, struct btt_sb *btt_sb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/btt_devs.c (c000000000a14710)
Location: drivers/nvdimm/btt_devs.c:271
Inline: True
Direct callers:
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
```
**Symbols:**

```
c000000000a14710-c000000000a14864: nd_btt_version (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int nd_btt_version(struct nd_btt *nd_btt, struct nd_namespace_common *ndns, struct btt_sb *btt_sb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/btt_devs.c (ffffffe0005ceac0)
Location: drivers/nvdimm/btt_devs.c:271
Inline: True
Direct callers:
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
```
**Symbols:**

```
ffffffe0005ceac0-ffffffe0005ceb78: nd_btt_version (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int nd_btt_version(struct nd_btt *nd_btt, struct nd_namespace_common *ndns, struct btt_sb *btt_sb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/btt_devs.c (ffffffff81714000)
Location: drivers/nvdimm/btt_devs.c:271
Inline: True
Direct callers:
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
```
**Symbols:**

```
ffffffff81714000-ffffffff817140c1: nd_btt_version (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int nd_btt_version(struct nd_btt *nd_btt, struct nd_namespace_common *ndns, struct btt_sb *btt_sb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/btt_devs.c (ffffffff816e7a80)
Location: drivers/nvdimm/btt_devs.c:271
Inline: True
Direct callers:
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt.c:nvdimm_namespace_attach_btt
```
**Symbols:**

```
ffffffff816e7a80-ffffffff816e7b41: nd_btt_version (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int nd_btt_version(struct nd_btt *nd_btt, struct nd_namespace_common *ndns, struct btt_sb *btt_sb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/btt_devs.c (ffffffff81752dd0)
Location: drivers/nvdimm/btt_devs.c:271
Inline: True
Direct callers:
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
```
**Symbols:**

```
ffffffff81752dd0-ffffffff81752e91: nd_btt_version (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int nd_btt_version(struct nd_btt *nd_btt, struct nd_namespace_common *ndns, struct btt_sb *btt_sb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/btt_devs.c (ffffffff8176e240)
Location: drivers/nvdimm/btt_devs.c:271
Inline: True
Direct callers:
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
```
**Symbols:**

```
ffffffff8176e240-ffffffff8176e301: nd_btt_version (STB_GLOBAL)
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
