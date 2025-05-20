# Function: <code>nvdimm_revalidate_disk</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int nvdimm_revalidate_disk(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff815977c0)
Location: drivers/nvdimm/bus.c:236
Inline: False
```
**Symbols:**

```
ffffffff815977c0-ffffffff81597846: nvdimm_revalidate_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int nvdimm_revalidate_disk(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff815ec870)
Location: drivers/nvdimm/bus.c:499
Inline: False
```
**Symbols:**

```
ffffffff815ec870-ffffffff815ec8f3: nvdimm_revalidate_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int nvdimm_revalidate_disk(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff81619650)
Location: drivers/nvdimm/bus.c:501
Inline: False
```
**Symbols:**

```
ffffffff81619650-ffffffff816196d3: nvdimm_revalidate_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int nvdimm_revalidate_disk(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff8162d580)
Location: drivers/nvdimm/bus.c:564
Inline: False
```
**Symbols:**

```
ffffffff8162d580-ffffffff8162d603: nvdimm_revalidate_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int nvdimm_revalidate_disk(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff81695d30)
Location: drivers/nvdimm/bus.c:564
Inline: False
```
**Symbols:**

```
ffffffff81695d30-ffffffff81695db3: nvdimm_revalidate_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int nvdimm_revalidate_disk(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff816d1e10)
Location: drivers/nvdimm/bus.c:568
Inline: False
```
**Symbols:**

```
ffffffff816d1e10-ffffffff816d1e74: nvdimm_revalidate_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int nvdimm_revalidate_disk(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff816f34a0)
Location: drivers/nvdimm/bus.c:597
Inline: False
```
**Symbols:**

```
ffffffff816f34a0-ffffffff816f3504: nvdimm_revalidate_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int nvdimm_revalidate_disk(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/bus.c (0)
Location: drivers/nvdimm/bus.c:628
Inline: False
```
**Symbols:**

```
ffffffff8172e760-ffffffff8172e794: nvdimm_revalidate_disk.cold (STB_LOCAL)
ffffffff8172c9f0-ffffffff8172ca32: nvdimm_revalidate_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int nvdimm_revalidate_disk(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/bus.c (0)
Location: drivers/nvdimm/bus.c:626
Inline: False
```
**Symbols:**

```
ffffffff81752a00-ffffffff81752a34: nvdimm_revalidate_disk.cold (STB_LOCAL)
ffffffff81750c10-ffffffff81750c52: nvdimm_revalidate_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int nvdimm_revalidate_disk(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/bus.c (0)
Location: drivers/nvdimm/bus.c:631
Inline: False
```
**Symbols:**

```
ffffffff81811430-ffffffff81811464: nvdimm_revalidate_disk.cold (STB_LOCAL)
ffffffff8180f510-ffffffff8180f552: nvdimm_revalidate_disk (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int nvdimm_revalidate_disk(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffff800010950d20)
Location: drivers/nvdimm/bus.c:626
Inline: False
```
**Symbols:**

```
ffff800010950d20-ffff800010950d98: nvdimm_revalidate_disk (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int nvdimm_revalidate_disk(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (c0000000009fd7f0)
Location: drivers/nvdimm/bus.c:626
Inline: False
```
**Symbols:**

```
c0000000009fd7f0-c0000000009fd89c: nvdimm_revalidate_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int nvdimm_revalidate_disk(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffe0005c0dbc)
Location: drivers/nvdimm/bus.c:626
Inline: False
```
**Symbols:**

```
ffffffe0005c0dbc-ffffffe0005c0e2a: nvdimm_revalidate_disk (STB_GLOBAL)
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
int nvdimm_revalidate_disk(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/bus.c (0)
Location: drivers/nvdimm/bus.c:626
Inline: False
```
**Symbols:**

```
ffffffff817070f0-ffffffff81707124: nvdimm_revalidate_disk.cold (STB_LOCAL)
ffffffff81705300-ffffffff81705342: nvdimm_revalidate_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int nvdimm_revalidate_disk(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/bus.c (0)
Location: drivers/nvdimm/bus.c:626
Inline: False
```
**Symbols:**

```
ffffffff816dab70-ffffffff816daba4: nvdimm_revalidate_disk.cold (STB_LOCAL)
ffffffff816d8d80-ffffffff816d8dc2: nvdimm_revalidate_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int nvdimm_revalidate_disk(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/bus.c (0)
Location: drivers/nvdimm/bus.c:626
Inline: False
```
**Symbols:**

```
ffffffff81745ec0-ffffffff81745ef4: nvdimm_revalidate_disk.cold (STB_LOCAL)
ffffffff817440d0-ffffffff81744112: nvdimm_revalidate_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int nvdimm_revalidate_disk(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/bus.c (0)
Location: drivers/nvdimm/bus.c:626
Inline: False
```
**Symbols:**

```
ffffffff81761300-ffffffff81761334: nvdimm_revalidate_disk.cold (STB_LOCAL)
ffffffff8175f520-ffffffff8175f562: nvdimm_revalidate_disk (STB_GLOBAL)
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
