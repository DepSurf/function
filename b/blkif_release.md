# Function: <code>blkif_release</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void blkif_release(struct gendisk *disk, fmode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff81573440)
Location: drivers/block/xen-blkfront.c:2209
Inline: False
```
**Symbols:**

```
ffffffff81573440-ffffffff81573550: blkif_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void blkif_release(struct gendisk *disk, fmode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff815ca4a0)
Location: drivers/block/xen-blkfront.c:2604
Inline: False
```
**Symbols:**

```
ffffffff815ca4a0-ffffffff815ca5a8: blkif_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void blkif_release(struct gendisk *disk, fmode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff815f7100)
Location: drivers/block/xen-blkfront.c:2578
Inline: False
```
**Symbols:**

```
ffffffff815f7100-ffffffff815f7208: blkif_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void blkif_release(struct gendisk *disk, fmode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff8160c8b0)
Location: drivers/block/xen-blkfront.c:2551
Inline: False
```
**Symbols:**

```
ffffffff8160c8b0-ffffffff8160c9af: blkif_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void blkif_release(struct gendisk *disk, fmode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff81675180)
Location: drivers/block/xen-blkfront.c:2551
Inline: False
```
**Symbols:**

```
ffffffff81675180-ffffffff81675282: blkif_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void blkif_release(struct gendisk *disk, fmode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff816b1750)
Location: drivers/block/xen-blkfront.c:2554
Inline: False
```
**Symbols:**

```
ffffffff816b1750-ffffffff816b184e: blkif_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void blkif_release(struct gendisk *disk, fmode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff816d1b40)
Location: drivers/block/xen-blkfront.c:2580
Inline: False
```
**Symbols:**

```
ffffffff816d1b40-ffffffff816d1c75: blkif_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void blkif_release(struct gendisk *disk, fmode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/xen-blkfront.c (0)
Location: drivers/block/xen-blkfront.c:2580
Inline: False
```
**Symbols:**

```
ffffffff8170d3f0-ffffffff8170d488: blkif_release (STB_LOCAL)
ffffffff8170fd04-ffffffff8170fda3: blkif_release.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void blkif_release(struct gendisk *disk, fmode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/xen-blkfront.c (0)
Location: drivers/block/xen-blkfront.c:2580
Inline: False
```
**Symbols:**

```
ffffffff817316f0-ffffffff81731788: blkif_release (STB_LOCAL)
ffffffff81733fee-ffffffff8173408d: blkif_release.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void blkif_release(struct gendisk *disk, fmode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/xen-blkfront.c (0)
Location: drivers/block/xen-blkfront.c:2585
Inline: False
```
**Symbols:**

```
ffffffff817ee000-ffffffff817ee098: blkif_release (STB_LOCAL)
ffffffff817f14a4-ffffffff817f1518: blkif_release.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void blkif_release(struct gendisk *disk, fmode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/xen-blkfront.c (0)
Location: drivers/block/xen-blkfront.c:2590
Inline: False
```
**Symbols:**

```
ffffffff81802930-ffffffff81802998: blkif_release (STB_LOCAL)
ffffffff81c0fb97-ffffffff81c0fbfb: blkif_release.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void blkif_release(struct gendisk *disk, fmode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/xen-blkfront.c (0)
Location: drivers/block/xen-blkfront.c:2590
Inline: False
```
**Symbols:**

```
ffffffff817e8bd0-ffffffff817e8c38: blkif_release (STB_LOCAL)
ffffffff81c01e97-ffffffff81c01efb: blkif_release.cold (STB_LOCAL)
```
</details>
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
void blkif_release(struct gendisk *disk, fmode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffff800010928e98)
Location: drivers/block/xen-blkfront.c:2580
Inline: False
```
**Symbols:**

```
ffff800010928e98-ffff800010928fc0: blkif_release (STB_LOCAL)
```
</details>
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void blkif_release(struct gendisk *disk, fmode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/xen-blkfront.c (0)
Location: drivers/block/xen-blkfront.c:2635
Inline: False
```
**Symbols:**

```
ffffffff816f7660-ffffffff816f76f8: blkif_release (STB_LOCAL)
ffffffff816fa082-ffffffff816fa121: blkif_release.cold (STB_LOCAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void blkif_release(struct gendisk *disk, fmode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/xen-blkfront.c (0)
Location: drivers/block/xen-blkfront.c:2580
Inline: False
```
**Symbols:**

```
ffffffff81724bb0-ffffffff81724c48: blkif_release (STB_LOCAL)
ffffffff817274ae-ffffffff8172754d: blkif_release.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void blkif_release(struct gendisk *disk, fmode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/xen-blkfront.c (0)
Location: drivers/block/xen-blkfront.c:2580
Inline: False
```
**Symbols:**

```
ffffffff8173f8e0-ffffffff8173f978: blkif_release (STB_LOCAL)
ffffffff817428e6-ffffffff81742985: blkif_release.cold (STB_LOCAL)
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
