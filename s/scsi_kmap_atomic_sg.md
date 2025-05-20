# Function: <code>scsi_kmap_atomic_sg</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void *scsi_kmap_atomic_sg(struct scatterlist *sgl, int sg_count, size_t *offset, size_t *len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff815ae260)
Location: drivers/scsi/scsi_lib.c:3093
Inline: False
```
**Symbols:**

```
ffffffff815ae260-ffffffff815ae3d5: scsi_kmap_atomic_sg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void *scsi_kmap_atomic_sg(struct scatterlist *sgl, int sg_count, size_t *offset, size_t *len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81606130)
Location: drivers/scsi/scsi_lib.c:2967
Inline: False
```
**Symbols:**

```
ffffffff81606130-ffffffff81606298: scsi_kmap_atomic_sg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void *scsi_kmap_atomic_sg(struct scatterlist *sgl, int sg_count, size_t *offset, size_t *len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81635650)
Location: drivers/scsi/scsi_lib.c:3051
Inline: False
```
**Symbols:**

```
ffffffff81635650-ffffffff816357b3: scsi_kmap_atomic_sg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void *scsi_kmap_atomic_sg(struct scatterlist *sgl, int sg_count, size_t *offset, size_t *len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff8164a830)
Location: drivers/scsi/scsi_lib.c:3182
Inline: False
```
**Symbols:**

```
ffffffff8164a830-ffffffff8164a95a: scsi_kmap_atomic_sg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void *scsi_kmap_atomic_sg(struct scatterlist *sgl, int sg_count, size_t *offset, size_t *len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff816b3ba0)
Location: drivers/scsi/scsi_lib.c:3287
Inline: False
```
**Symbols:**

```
ffffffff816b3ba0-ffffffff816b3cca: scsi_kmap_atomic_sg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void *scsi_kmap_atomic_sg(struct scatterlist *sgl, int sg_count, size_t *offset, size_t *len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_lib.c (0)
Location: drivers/scsi/scsi_lib.c:3303
Inline: False
```
**Symbols:**

```
ffffffff816f2fed-ffffffff816f3011: scsi_kmap_atomic_sg.cold.46 (STB_LOCAL)
ffffffff816efc70-ffffffff816efd6f: scsi_kmap_atomic_sg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void *scsi_kmap_atomic_sg(struct scatterlist *sgl, int sg_count, size_t *offset, size_t *len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_lib.c (0)
Location: drivers/scsi/scsi_lib.c:2847
Inline: False
```
**Symbols:**

```
ffffffff81715de4-ffffffff81715e08: scsi_kmap_atomic_sg.cold.45 (STB_LOCAL)
ffffffff817134d0-ffffffff817135cf: scsi_kmap_atomic_sg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void *scsi_kmap_atomic_sg(struct scatterlist *sgl, int sg_count, size_t *offset, size_t *len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_lib.c (0)
Location: drivers/scsi/scsi_lib.c:2796
Inline: False
```
**Symbols:**

```
ffffffff81751594-ffffffff817515d8: scsi_kmap_atomic_sg.cold (STB_LOCAL)
ffffffff8174edb0-ffffffff8174eebe: scsi_kmap_atomic_sg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void *scsi_kmap_atomic_sg(struct scatterlist *sgl, int sg_count, size_t *offset, size_t *len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_lib.c (0)
Location: drivers/scsi/scsi_lib.c:2856
Inline: False
```
**Symbols:**

```
ffffffff81775824-ffffffff81775849: scsi_kmap_atomic_sg.cold (STB_LOCAL)
ffffffff81772fa0-ffffffff8177309d: scsi_kmap_atomic_sg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void *scsi_kmap_atomic_sg(struct scatterlist *sgl, int sg_count, size_t *offset, size_t *len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_lib.c (0)
Location: drivers/scsi/scsi_lib.c:2889
Inline: False
```
**Symbols:**

```
ffffffff81838744-ffffffff81838769: scsi_kmap_atomic_sg.cold (STB_LOCAL)
ffffffff81834c30-ffffffff81834d2e: scsi_kmap_atomic_sg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void *scsi_kmap_atomic_sg(struct scatterlist *sgl, int sg_count, size_t *offset, size_t *len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_lib.c (0)
Location: drivers/scsi/scsi_lib.c:2895
Inline: False
```
**Symbols:**

```
ffffffff81c168ed-ffffffff81c16912: scsi_kmap_atomic_sg.cold (STB_LOCAL)
ffffffff81845d00-ffffffff81845dfe: scsi_kmap_atomic_sg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void *scsi_kmap_atomic_sg(struct scatterlist *sgl, int sg_count, size_t *offset, size_t *len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_lib.c (0)
Location: drivers/scsi/scsi_lib.c:2912
Inline: False
```
**Symbols:**

```
ffffffff81c085c8-ffffffff81c085ed: scsi_kmap_atomic_sg.cold (STB_LOCAL)
ffffffff81828fa0-ffffffff8182909e: scsi_kmap_atomic_sg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void *scsi_kmap_atomic_sg(struct scatterlist *sgl, int sg_count, size_t *offset, size_t *len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_lib.c (0)
Location: drivers/scsi/scsi_lib.c:2905
Inline: False
```
**Symbols:**

```
ffffffff81d0c482-ffffffff81d0c4a7: scsi_kmap_atomic_sg.cold (STB_LOCAL)
ffffffff818b4980-ffffffff818b4a69: scsi_kmap_atomic_sg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void *scsi_kmap_atomic_sg(struct scatterlist *sgl, int sg_count, size_t *offset, size_t *len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_lib.c (0)
Location: drivers/scsi/scsi_lib.c:2989
Inline: False
```
**Symbols:**

```
ffffffff81ed53e0-ffffffff81ed5406: scsi_kmap_atomic_sg.cold (STB_LOCAL)
ffffffff819ff910-ffffffff819ffa1c: scsi_kmap_atomic_sg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *scsi_kmap_atomic_sg(struct scatterlist *sgl, int sg_count, size_t *offset, size_t *len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81b7df60)
Location: drivers/scsi/scsi_lib.c:2994
Inline: False
```
**Symbols:**

```
ffffffff81b7df60-ffffffff81b7e0b1: scsi_kmap_atomic_sg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *scsi_kmap_atomic_sg(struct scatterlist *sgl, int sg_count, size_t *offset, size_t *len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81bd1d40)
Location: drivers/scsi/scsi_lib.c:3013
Inline: False
```
**Symbols:**

```
ffffffff81bd1d40-ffffffff81bd1e91: scsi_kmap_atomic_sg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *scsi_kmap_atomic_sg(struct scatterlist *sgl, int sg_count, size_t *offset, size_t *len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81c269b0)
Location: drivers/scsi/scsi_lib.c:3010
Inline: False
```
**Symbols:**

```
ffffffff81c269b0-ffffffff81c26b01: scsi_kmap_atomic_sg (STB_GLOBAL)
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
void *scsi_kmap_atomic_sg(struct scatterlist *sgl, int sg_count, size_t *offset, size_t *len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffff800010976560)
Location: drivers/scsi/scsi_lib.c:2856
Inline: False
```
**Symbols:**

```
ffff800010976560-ffff8000109766b8: scsi_kmap_atomic_sg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *scsi_kmap_atomic_sg(struct scatterlist *sgl, int sg_count, size_t *offset, size_t *len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (c0a4af04)
Location: drivers/scsi/scsi_lib.c:2856
Inline: False
```
**Symbols:**

```
c0a4af04-c0a4b054: scsi_kmap_atomic_sg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *scsi_kmap_atomic_sg(struct scatterlist *sgl, int sg_count, size_t *offset, size_t *len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (c000000000a30d90)
Location: drivers/scsi/scsi_lib.c:2856
Inline: False
```
**Symbols:**

```
c000000000a30d90-c000000000a30f48: scsi_kmap_atomic_sg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *scsi_kmap_atomic_sg(struct scatterlist *sgl, int sg_count, size_t *offset, size_t *len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffe0005dec4a)
Location: drivers/scsi/scsi_lib.c:2856
Inline: False
```
**Symbols:**

```
ffffffe0005dec4a-ffffffe0005ded46: scsi_kmap_atomic_sg (STB_GLOBAL)
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
void *scsi_kmap_atomic_sg(struct scatterlist *sgl, int sg_count, size_t *offset, size_t *len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_lib.c (0)
Location: drivers/scsi/scsi_lib.c:2856
Inline: False
```
**Symbols:**

```
ffffffff81729f14-ffffffff81729f39: scsi_kmap_atomic_sg.cold (STB_LOCAL)
ffffffff81727690-ffffffff8172778d: scsi_kmap_atomic_sg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void *scsi_kmap_atomic_sg(struct scatterlist *sgl, int sg_count, size_t *offset, size_t *len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_lib.c (0)
Location: drivers/scsi/scsi_lib.c:2856
Inline: False
```
**Symbols:**

```
ffffffff81703334-ffffffff81703359: scsi_kmap_atomic_sg.cold (STB_LOCAL)
ffffffff81700ac0-ffffffff81700bb8: scsi_kmap_atomic_sg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void *scsi_kmap_atomic_sg(struct scatterlist *sgl, int sg_count, size_t *offset, size_t *len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_lib.c (0)
Location: drivers/scsi/scsi_lib.c:2856
Inline: False
```
**Symbols:**

```
ffffffff81768ce4-ffffffff81768d09: scsi_kmap_atomic_sg.cold (STB_LOCAL)
ffffffff81766460-ffffffff8176655d: scsi_kmap_atomic_sg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void *scsi_kmap_atomic_sg(struct scatterlist *sgl, int sg_count, size_t *offset, size_t *len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_lib.c (0)
Location: drivers/scsi/scsi_lib.c:2856
Inline: False
```
**Symbols:**

```
ffffffff81784464-ffffffff81784489: scsi_kmap_atomic_sg.cold (STB_LOCAL)
ffffffff81781b10-ffffffff81781c14: scsi_kmap_atomic_sg (STB_GLOBAL)
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
