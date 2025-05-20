# Function: <code>cacheinfo_amd_init_llc_id</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void cacheinfo_amd_init_llc_id(struct cpuinfo_x86 *c, int cpu, u8 node_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81041060)
Location: arch/x86/kernel/cpu/cacheinfo.c:642
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
**Symbols:**

```
ffffffff81041060-ffffffff810411bb: cacheinfo_amd_init_llc_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void cacheinfo_amd_init_llc_id(struct cpuinfo_x86 *c, int cpu, u8 node_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81042670)
Location: arch/x86/kernel/cpu/cacheinfo.c:648
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
**Symbols:**

```
ffffffff81042670-ffffffff810427cb: cacheinfo_amd_init_llc_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void cacheinfo_amd_init_llc_id(struct cpuinfo_x86 *c, int cpu, u8 node_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81044ae0)
Location: arch/x86/kernel/cpu/cacheinfo.c:649
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
**Symbols:**

```
ffffffff81044ae0-ffffffff81044c36: cacheinfo_amd_init_llc_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void cacheinfo_amd_init_llc_id(struct cpuinfo_x86 *c, int cpu, u8 node_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81045230)
Location: arch/x86/kernel/cpu/cacheinfo.c:649
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
**Symbols:**

```
ffffffff81045230-ffffffff81045386: cacheinfo_amd_init_llc_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void cacheinfo_amd_init_llc_id(struct cpuinfo_x86 *c, int cpu, u8 node_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81049050)
Location: arch/x86/kernel/cpu/cacheinfo.c:649
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/amd.c:amd_get_topology
```
**Symbols:**

```
ffffffff81049050-ffffffff810491a6: cacheinfo_amd_init_llc_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void cacheinfo_amd_init_llc_id(struct cpuinfo_x86 *c, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81048510)
Location: arch/x86/kernel/cpu/cacheinfo.c:649
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/amd.c:amd_get_topology
```
**Symbols:**

```
ffffffff81048510-ffffffff8104865f: cacheinfo_amd_init_llc_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void cacheinfo_amd_init_llc_id(struct cpuinfo_x86 *c, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81049de0)
Location: arch/x86/kernel/cpu/cacheinfo.c:649
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
**Symbols:**

```
ffffffff81049de0-ffffffff81049f2f: cacheinfo_amd_init_llc_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void cacheinfo_amd_init_llc_id(struct cpuinfo_x86 *c, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (0)
Location: arch/x86/kernel/cpu/cacheinfo.c:649
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
**Symbols:**

```
ffffffff81c9a90b-ffffffff81c9a929: cacheinfo_amd_init_llc_id.cold (STB_LOCAL)
ffffffff81050830-ffffffff810509e9: cacheinfo_amd_init_llc_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void cacheinfo_amd_init_llc_id(struct cpuinfo_x86 *c, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (0)
Location: arch/x86/kernel/cpu/cacheinfo.c:649
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/amd.c:amd_get_topology
```
**Symbols:**

```
ffffffff81e49d92-ffffffff81e49db0: cacheinfo_amd_init_llc_id.cold (STB_LOCAL)
ffffffff8105bc90-ffffffff8105be8b: cacheinfo_amd_init_llc_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void cacheinfo_amd_init_llc_id(struct cpuinfo_x86 *c, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (0)
Location: arch/x86/kernel/cpu/cacheinfo.c:662
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/amd.c:amd_get_topology
```
**Symbols:**

```
ffffffff820527bf-ffffffff820527dd: cacheinfo_amd_init_llc_id.cold (STB_LOCAL)
ffffffff81069c50-ffffffff81069e4b: cacheinfo_amd_init_llc_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void cacheinfo_amd_init_llc_id(struct cpuinfo_x86 *c, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (0)
Location: arch/x86/kernel/cpu/cacheinfo.c:664
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/amd.c:amd_get_topology
```
**Symbols:**

```
ffffffff820d0c7a-ffffffff820d0c98: cacheinfo_amd_init_llc_id.cold (STB_LOCAL)
ffffffff8106b570-ffffffff8106b76b: cacheinfo_amd_init_llc_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void cacheinfo_amd_init_llc_id(struct cpuinfo_x86 *c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (0)
Location: arch/x86/kernel/cpu/cacheinfo.c:673
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/amd.c:amd_get_topology
```
**Symbols:**

```
ffffffff821ab7a1-ffffffff821ab7c0: cacheinfo_amd_init_llc_id.cold (STB_LOCAL)
ffffffff81072a40-ffffffff81072bac: cacheinfo_amd_init_llc_id (STB_GLOBAL)
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
void cacheinfo_amd_init_llc_id(struct cpuinfo_x86 *c, int cpu, u8 node_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff810453b0)
Location: arch/x86/kernel/cpu/cacheinfo.c:649
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
**Symbols:**

```
ffffffff810453b0-ffffffff81045506: cacheinfo_amd_init_llc_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void cacheinfo_amd_init_llc_id(struct cpuinfo_x86 *c, int cpu, u8 node_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff810348c0)
Location: arch/x86/kernel/cpu/cacheinfo.c:649
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
**Symbols:**

```
ffffffff810348c0-ffffffff810349c4: cacheinfo_amd_init_llc_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void cacheinfo_amd_init_llc_id(struct cpuinfo_x86 *c, int cpu, u8 node_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff810451f0)
Location: arch/x86/kernel/cpu/cacheinfo.c:649
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
**Symbols:**

```
ffffffff810451f0-ffffffff81045346: cacheinfo_amd_init_llc_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void cacheinfo_amd_init_llc_id(struct cpuinfo_x86 *c, int cpu, u8 node_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff810465f0)
Location: arch/x86/kernel/cpu/cacheinfo.c:649
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
**Symbols:**

```
ffffffff810465f0-ffffffff81046746: cacheinfo_amd_init_llc_id (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>u8 node_id</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int cpu</code>
</li>
</ul>
</details>
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
