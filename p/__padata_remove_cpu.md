# Function: <code>__padata_remove_cpu</code>

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
In kernel/padata.c (ffffffff8118a9a0)
Location: kernel/padata.c:733
Inline: True
Inline callers:
  - kernel/padata.c:padata_cpu_callback
  - kernel/padata.c:padata_remove_cpu
Direct callers:
  - kernel/padata.c:padata_cpu_callback
  - kernel/padata.c:padata_remove_cpu
```
**Symbols:**

```
ffffffff8118a9a0-ffffffff8118aa39: __padata_remove_cpu.part.8 (STB_LOCAL)
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
In kernel/padata.c (ffffffff8119cf37)
Location: kernel/padata.c:707
Inline: True
Inline callers:
  - kernel/padata.c:padata_cpu_callback
  - kernel/padata.c:padata_remove_cpu
Direct callers:
  - kernel/padata.c:padata_cpu_callback
  - kernel/padata.c:padata_remove_cpu
```
**Symbols:**

```
ffffffff8119cdc0-ffffffff8119ce8d: __padata_remove_cpu.part.7 (STB_LOCAL)
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
In kernel/padata.c (ffffffff811ac930)
Location: kernel/padata.c:704
Inline: True
Inline callers:
  - kernel/padata.c:padata_cpu_prep_down
  - kernel/padata.c:padata_remove_cpu
Direct callers:
  - kernel/padata.c:padata_cpu_prep_down
  - kernel/padata.c:padata_remove_cpu
```
**Symbols:**

```
ffffffff811ac7b0-ffffffff811ac843: __padata_remove_cpu.part.9 (STB_LOCAL)
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
In kernel/padata.c (ffffffff811b4004)
Location: kernel/padata.c:700
Inline: True
Inline callers:
  - kernel/padata.c:padata_cpu_prep_down
  - kernel/padata.c:padata_remove_cpu
Direct callers:
  - kernel/padata.c:padata_cpu_prep_down
  - kernel/padata.c:padata_remove_cpu
```
**Symbols:**

```
ffffffff811b3e80-ffffffff811b3f13: __padata_remove_cpu.part.9 (STB_LOCAL)
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
In kernel/padata.c (ffffffff811c7c94)
Location: kernel/padata.c:765
Inline: True
Inline callers:
  - kernel/padata.c:padata_cpu_prep_down
  - kernel/padata.c:padata_remove_cpu
Direct callers:
  - kernel/padata.c:padata_cpu_prep_down
  - kernel/padata.c:padata_remove_cpu
```
**Symbols:**

```
ffffffff811c7b10-ffffffff811c7ba3: __padata_remove_cpu.part.9 (STB_LOCAL)
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
In kernel/padata.c (ffffffff811e7ed4)
Location: kernel/padata.c:766
Inline: True
Inline callers:
  - kernel/padata.c:padata_cpu_prep_down
  - kernel/padata.c:padata_remove_cpu
Direct callers:
  - kernel/padata.c:padata_cpu_prep_down
  - kernel/padata.c:padata_remove_cpu
```
**Symbols:**

```
ffffffff811e7d50-ffffffff811e7de3: __padata_remove_cpu.part.13 (STB_LOCAL)
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
In kernel/padata.c (ffffffff811f8d84)
Location: kernel/padata.c:766
Inline: True
Inline callers:
  - kernel/padata.c:padata_cpu_prep_down
  - kernel/padata.c:padata_remove_cpu
Direct callers:
  - kernel/padata.c:padata_cpu_prep_down
  - kernel/padata.c:padata_remove_cpu
```
**Symbols:**

```
ffffffff811f8ca0-ffffffff811f8d33: __padata_remove_cpu.part.14 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __padata_remove_cpu(struct padata_instance *pinst, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff812109e0)
Location: kernel/padata.c:778
Inline: False
Direct callers:
  - kernel/padata.c:padata_cpu_prep_down
  - kernel/padata.c:padata_remove_cpu
```
**Symbols:**

```
ffffffff812109e0-ffffffff81210a91: __padata_remove_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int __padata_remove_cpu(struct padata_instance *pinst, int cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff8121de10)
Location: kernel/padata.c:724
Inline: True
Direct callers:
  - kernel/padata.c:padata_cpu_dead
  - kernel/padata.c:padata_remove_cpu
```
**Symbols:**

```
ffffffff8121de10-ffffffff8121de92: __padata_remove_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff81249c1b)
Location: kernel/padata.c:847
Inline: True
Inline callers:
  - kernel/padata.c:padata_cpu_dead
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff81253fcb)
Location: kernel/padata.c:779
Inline: True
Inline callers:
  - kernel/padata.c:padata_cpu_dead
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff8125850b)
Location: kernel/padata.c:779
Inline: True
Inline callers:
  - kernel/padata.c:padata_cpu_dead
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff8129412b)
Location: kernel/padata.c:766
Inline: True
Inline callers:
  - kernel/padata.c:padata_cpu_dead
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff812ea162)
Location: kernel/padata.c:766
Inline: True
Inline callers:
  - kernel/padata.c:padata_cpu_dead
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff81354032)
Location: kernel/padata.c:779
Inline: True
Inline callers:
  - kernel/padata.c:padata_cpu_dead
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff81385232)
Location: kernel/padata.c:779
Inline: True
Inline callers:
  - kernel/padata.c:padata_cpu_dead
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff813ae5a2)
Location: kernel/padata.c:779
Inline: True
Inline callers:
  - kernel/padata.c:padata_cpu_dead
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
int __padata_remove_cpu(struct padata_instance *pinst, int cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffff8000102a9650)
Location: kernel/padata.c:724
Inline: True
Direct callers:
  - kernel/padata.c:padata_cpu_dead
  - kernel/padata.c:padata_remove_cpu
```
**Symbols:**

```
ffff8000102a9650-ffff8000102a9724: __padata_remove_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int __padata_remove_cpu(struct padata_instance *pinst, int cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/padata.c (c04d88e0)
Location: kernel/padata.c:724
Inline: True
Direct callers:
  - kernel/padata.c:padata_cpu_dead
  - kernel/padata.c:padata_remove_cpu
```
**Symbols:**

```
c04d88e0-c04d898c: __padata_remove_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int __padata_remove_cpu(struct padata_instance *pinst, int cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/padata.c (c00000000035dc70)
Location: kernel/padata.c:724
Inline: True
Direct callers:
  - kernel/padata.c:padata_cpu_dead
  - kernel/padata.c:padata_remove_cpu
```
**Symbols:**

```
c00000000035dc70-c00000000035dd74: __padata_remove_cpu (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int __padata_remove_cpu(struct padata_instance *pinst, int cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff81216460)
Location: kernel/padata.c:724
Inline: True
Direct callers:
  - kernel/padata.c:padata_cpu_dead
  - kernel/padata.c:padata_remove_cpu
```
**Symbols:**

```
ffffffff81216460-ffffffff812164e2: __padata_remove_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int __padata_remove_cpu(struct padata_instance *pinst, int cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff812091c0)
Location: kernel/padata.c:724
Inline: True
Direct callers:
  - kernel/padata.c:padata_cpu_dead
  - kernel/padata.c:padata_remove_cpu
```
**Symbols:**

```
ffffffff812091c0-ffffffff81209242: __padata_remove_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int __padata_remove_cpu(struct padata_instance *pinst, int cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff81214200)
Location: kernel/padata.c:724
Inline: True
Direct callers:
  - kernel/padata.c:padata_cpu_dead
  - kernel/padata.c:padata_remove_cpu
```
**Symbols:**

```
ffffffff81214200-ffffffff81214282: __padata_remove_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int __padata_remove_cpu(struct padata_instance *pinst, int cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff81223440)
Location: kernel/padata.c:724
Inline: True
Direct callers:
  - kernel/padata.c:padata_cpu_dead
  - kernel/padata.c:padata_remove_cpu
```
**Symbols:**

```
ffffffff81223440-ffffffff812234c2: __padata_remove_cpu (STB_LOCAL)
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
