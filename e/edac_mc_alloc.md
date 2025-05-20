# Function: <code>edac_mc_alloc</code>

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
struct mem_ctl_info *edac_mc_alloc(unsigned int mc_num, unsigned int n_layers, struct edac_mc_layer *layers, unsigned int sz_pvt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_mc.c (ffffffff8175d0b0)
Location: drivers/edac/edac_mc.c:306
Inline: False
```
**Symbols:**

```
ffffffff8175d0b0-ffffffff8175d6f4: edac_mc_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct mem_ctl_info *edac_mc_alloc(unsigned int mc_num, unsigned int n_layers, struct edac_mc_layer *layers, unsigned int sz_pvt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_mc.c (ffffffff817cf120)
Location: drivers/edac/edac_mc.c:306
Inline: False
Direct callers:
  - drivers/edac/ghes_edac.c:ghes_edac_register
```
**Symbols:**

```
ffffffff817cf120-ffffffff817cf764: edac_mc_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct mem_ctl_info *edac_mc_alloc(unsigned int mc_num, unsigned int n_layers, struct edac_mc_layer *layers, unsigned int sz_pvt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_mc.c (ffffffff81817ca0)
Location: drivers/edac/edac_mc.c:308
Inline: False
Direct callers:
  - drivers/edac/ghes_edac.c:ghes_edac_register
```
**Symbols:**

```
ffffffff81817ca0-ffffffff818182ac: edac_mc_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct mem_ctl_info *edac_mc_alloc(unsigned int mc_num, unsigned int n_layers, struct edac_mc_layer *layers, unsigned int sz_pvt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_mc.c (ffffffff81843540)
Location: drivers/edac/edac_mc.c:306
Inline: False
Direct callers:
  - drivers/edac/ghes_edac.c:ghes_edac_register
```
**Symbols:**

```
ffffffff81843540-ffffffff81843b55: edac_mc_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct mem_ctl_info *edac_mc_alloc(unsigned int mc_num, unsigned int n_layers, struct edac_mc_layer *layers, unsigned int sz_pvt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/edac/edac_mc.c (0)
Location: drivers/edac/edac_mc.c:306
Inline: False
Direct callers:
  - drivers/edac/ghes_edac.c:ghes_edac_register
```
**Symbols:**

```
ffffffff81886d08-ffffffff81886d28: edac_mc_alloc.cold (STB_LOCAL)
ffffffff81886380-ffffffff8188691c: edac_mc_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct mem_ctl_info *edac_mc_alloc(unsigned int mc_num, unsigned int n_layers, struct edac_mc_layer *layers, unsigned int sz_pvt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/edac/edac_mc.c (0)
Location: drivers/edac/edac_mc.c:305
Inline: False
Direct callers:
  - drivers/edac/ghes_edac.c:ghes_edac_register
```
**Symbols:**

```
ffffffff818b8cc8-ffffffff818b8ce8: edac_mc_alloc.cold (STB_LOCAL)
ffffffff818b8340-ffffffff818b88dc: edac_mc_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct mem_ctl_info *edac_mc_alloc(unsigned int mc_num, unsigned int n_layers, struct edac_mc_layer *layers, unsigned int sz_pvt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/edac/edac_mc.c (ffffffff81988fa0)
Location: drivers/edac/edac_mc.c:386
Inline: True
Direct callers:
  - drivers/edac/ghes_edac.c:ghes_edac_register
```
**Symbols:**

```
ffffffff81988fa0-ffffffff81989140: edac_mc_alloc.part.0 (STB_LOCAL)
ffffffff81989140-ffffffff8198915d: edac_mc_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct mem_ctl_info *edac_mc_alloc(unsigned int mc_num, unsigned int n_layers, struct edac_mc_layer *layers, unsigned int sz_pvt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/edac/edac_mc.c (ffffffff8198cf40)
Location: drivers/edac/edac_mc.c:390
Inline: True
Direct callers:
  - drivers/edac/ghes_edac.c:ghes_edac_register
```
**Symbols:**

```
ffffffff8198cf40-ffffffff8198d0e0: edac_mc_alloc.part.0 (STB_LOCAL)
ffffffff8198d0e0-ffffffff8198d0fd: edac_mc_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct mem_ctl_info *edac_mc_alloc(unsigned int mc_num, unsigned int n_layers, struct edac_mc_layer *layers, unsigned int sz_pvt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/edac/edac_mc.c (ffffffff81971510)
Location: drivers/edac/edac_mc.c:390
Inline: True
Direct callers:
  - drivers/edac/ghes_edac.c:ghes_edac_register
```
**Symbols:**

```
ffffffff81971510-ffffffff81971799: edac_mc_alloc.part.0 (STB_LOCAL)
ffffffff819717a0-ffffffff819717bd: edac_mc_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct mem_ctl_info *edac_mc_alloc(unsigned int mc_num, unsigned int n_layers, struct edac_mc_layer *layers, unsigned int sz_pvt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/edac/edac_mc.c (0)
Location: drivers/edac/edac_mc.c:393
Inline: False
Direct callers:
  - drivers/edac/ghes_edac.c:ghes_edac_register
```
**Symbols:**

```
ffffffff81d2a9fe-ffffffff81d2aa40: edac_mc_alloc.cold (STB_LOCAL)
ffffffff81a1a100-ffffffff81a1a44e: edac_mc_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct mem_ctl_info *edac_mc_alloc(unsigned int mc_num, unsigned int n_layers, struct edac_mc_layer *layers, unsigned int sz_pvt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/edac/edac_mc.c (0)
Location: drivers/edac/edac_mc.c:335
Inline: False
Direct callers:
  - drivers/edac/ghes_edac.c:ghes_edac_register
```
**Symbols:**

```
ffffffff81ef6bb8-ffffffff81ef6bed: edac_mc_alloc.cold (STB_LOCAL)
ffffffff81b82f40-ffffffff81b83234: edac_mc_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct mem_ctl_info *edac_mc_alloc(unsigned int mc_num, unsigned int n_layers, struct edac_mc_layer *layers, unsigned int sz_pvt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/edac/edac_mc.c (0)
Location: drivers/edac/edac_mc.c:334
Inline: False
```
**Symbols:**

```
ffffffff820a892e-ffffffff820a8963: edac_mc_alloc.cold (STB_LOCAL)
ffffffff81d218a0-ffffffff81d21b94: edac_mc_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct mem_ctl_info *edac_mc_alloc(unsigned int mc_num, unsigned int n_layers, struct edac_mc_layer *layers, unsigned int sz_pvt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/edac/edac_mc.c (0)
Location: drivers/edac/edac_mc.c:334
Inline: False
```
**Symbols:**

```
ffffffff82129b1e-ffffffff82129b5c: edac_mc_alloc.cold (STB_LOCAL)
ffffffff81d8aaa0-ffffffff81d8ada0: edac_mc_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct mem_ctl_info *edac_mc_alloc(unsigned int mc_num, unsigned int n_layers, struct edac_mc_layer *layers, unsigned int sz_pvt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/edac/edac_mc.c (0)
Location: drivers/edac/edac_mc.c:335
Inline: False
```
**Symbols:**

```
ffffffff8220b872-ffffffff8220b8a5: edac_mc_alloc.cold (STB_LOCAL)
ffffffff81e423f0-ffffffff81e4261f: edac_mc_alloc (STB_GLOBAL)
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
struct mem_ctl_info *edac_mc_alloc(unsigned int mc_num, unsigned int n_layers, struct edac_mc_layer *layers, unsigned int sz_pvt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_mc.c (ffff800010b10548)
Location: drivers/edac/edac_mc.c:305
Inline: False
Direct callers:
  - drivers/edac/ghes_edac.c:ghes_edac_register
  - drivers/edac/altera_edac.c:altr_sdram_probe
```
**Symbols:**

```
ffff800010b10548-ffff800010b10a9c: edac_mc_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct mem_ctl_info *edac_mc_alloc(unsigned int mc_num, unsigned int n_layers, struct edac_mc_layer *layers, unsigned int sz_pvt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_mc.c (c0bee964)
Location: drivers/edac/edac_mc.c:305
Inline: False
Direct callers:
  - drivers/edac/armada_xp_edac.c:axp_mc_probe
```
**Symbols:**

```
c0bee964-c0beef38: edac_mc_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct mem_ctl_info *edac_mc_alloc(unsigned int mc_num, unsigned int n_layers, struct edac_mc_layer *layers, unsigned int sz_pvt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_mc.c (c000000000c04070)
Location: drivers/edac/edac_mc.c:305
Inline: False
```
**Symbols:**

```
c000000000c04070-c000000000c04770: edac_mc_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct mem_ctl_info *edac_mc_alloc(unsigned int mc_num, unsigned int n_layers, struct edac_mc_layer *layers, unsigned int sz_pvt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_mc.c (ffffffe0006fd5da)
Location: drivers/edac/edac_mc.c:305
Inline: False
```
**Symbols:**

```
ffffffe0006fd5da-ffffffe0006fda76: edac_mc_alloc (STB_GLOBAL)
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
struct mem_ctl_info *edac_mc_alloc(unsigned int mc_num, unsigned int n_layers, struct edac_mc_layer *layers, unsigned int sz_pvt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/edac/edac_mc.c (0)
Location: drivers/edac/edac_mc.c:305
Inline: False
```
**Symbols:**

```
ffffffff8185eb48-ffffffff8185eb68: edac_mc_alloc.cold (STB_LOCAL)
ffffffff8185e1c0-ffffffff8185e75c: edac_mc_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
struct mem_ctl_info *edac_mc_alloc(unsigned int mc_num, unsigned int n_layers, struct edac_mc_layer *layers, unsigned int sz_pvt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/edac/edac_mc.c (0)
Location: drivers/edac/edac_mc.c:305
Inline: False
```
**Symbols:**

```
ffffffff81826118-ffffffff81826138: edac_mc_alloc.cold (STB_LOCAL)
ffffffff81825790-ffffffff81825d2c: edac_mc_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
struct mem_ctl_info *edac_mc_alloc(unsigned int mc_num, unsigned int n_layers, struct edac_mc_layer *layers, unsigned int sz_pvt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/edac/edac_mc.c (0)
Location: drivers/edac/edac_mc.c:305
Inline: False
Direct callers:
  - drivers/edac/ghes_edac.c:ghes_edac_register
```
**Symbols:**

```
ffffffff818ae178-ffffffff818ae198: edac_mc_alloc.cold (STB_LOCAL)
ffffffff818ad7f0-ffffffff818add8c: edac_mc_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct mem_ctl_info *edac_mc_alloc(unsigned int mc_num, unsigned int n_layers, struct edac_mc_layer *layers, unsigned int sz_pvt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/edac/edac_mc.c (0)
Location: drivers/edac/edac_mc.c:305
Inline: False
Direct callers:
  - drivers/edac/ghes_edac.c:ghes_edac_register
```
**Symbols:**

```
ffffffff818ca408-ffffffff818ca428: edac_mc_alloc.cold (STB_LOCAL)
ffffffff818c9a80-ffffffff818ca01c: edac_mc_alloc (STB_GLOBAL)
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
