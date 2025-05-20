# Function: <code>xlvbd_flush</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void xlvbd_flush(struct blkfront_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff81573040)
Location: drivers/block/xen-blkfront.c:852
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/block/xen-blkfront.c:blkif_interrupt
```
**Symbols:**

```
ffffffff81573040-ffffffff815730e8: xlvbd_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void xlvbd_flush(struct blkfront_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff815c9d20)
Location: drivers/block/xen-blkfront.c:1004
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
```
**Symbols:**

```
ffffffff815c9d20-ffffffff815c9dc9: xlvbd_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void xlvbd_flush(struct blkfront_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff815f6a40)
Location: drivers/block/xen-blkfront.c:1003
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
```
**Symbols:**

```
ffffffff815f6a40-ffffffff815f6adf: xlvbd_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void xlvbd_flush(struct blkfront_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff8160a060)
Location: drivers/block/xen-blkfront.c:1013
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
```
**Symbols:**

```
ffffffff8160a060-ffffffff8160a0f8: xlvbd_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void xlvbd_flush(struct blkfront_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff81672930)
Location: drivers/block/xen-blkfront.c:1013
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
```
**Symbols:**

```
ffffffff81672930-ffffffff816729c8: xlvbd_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void xlvbd_flush(struct blkfront_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff816ae420)
Location: drivers/block/xen-blkfront.c:1013
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
```
**Symbols:**

```
ffffffff816ae420-ffffffff816ae4b7: xlvbd_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void xlvbd_flush(struct blkfront_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff816cf360)
Location: drivers/block/xen-blkfront.c:1012
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
```
**Symbols:**

```
ffffffff816cf360-ffffffff816cf3f7: xlvbd_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void xlvbd_flush(struct blkfront_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/xen-blkfront.c (0)
Location: drivers/block/xen-blkfront.c:1012
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
```
**Symbols:**

```
ffffffff8170a4b0-ffffffff8170a50b: xlvbd_flush (STB_LOCAL)
ffffffff8170fb28-ffffffff8170fb6f: xlvbd_flush.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void xlvbd_flush(struct blkfront_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/xen-blkfront.c (0)
Location: drivers/block/xen-blkfront.c:1012
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
```
**Symbols:**

```
ffffffff8172e7b0-ffffffff8172e80b: xlvbd_flush (STB_LOCAL)
ffffffff81733e28-ffffffff81733e6f: xlvbd_flush.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void xlvbd_flush(struct blkfront_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/xen-blkfront.c (0)
Location: drivers/block/xen-blkfront.c:1022
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
```
**Symbols:**

```
ffffffff817ec090-ffffffff817ec0eb: xlvbd_flush (STB_LOCAL)
ffffffff817f1445-ffffffff817f148c: xlvbd_flush.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void xlvbd_flush(struct blkfront_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/xen-blkfront.c (0)
Location: drivers/block/xen-blkfront.c:1023
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
```
**Symbols:**

```
ffffffff818009c0-ffffffff81800a1b: xlvbd_flush (STB_LOCAL)
ffffffff81c0fb38-ffffffff81c0fb7f: xlvbd_flush.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void xlvbd_flush(struct blkfront_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/xen-blkfront.c (0)
Location: drivers/block/xen-blkfront.c:1023
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
```
**Symbols:**

```
ffffffff817e5590-ffffffff817e55eb: xlvbd_flush (STB_LOCAL)
ffffffff81c01ccf-ffffffff81c01d16: xlvbd_flush.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void xlvbd_flush(struct blkfront_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/xen-blkfront.c (0)
Location: drivers/block/xen-blkfront.c:980
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
```
**Symbols:**

```
ffffffff81871c80-ffffffff81871cdb: xlvbd_flush (STB_LOCAL)
ffffffff81d05a6b-ffffffff81d05ab2: xlvbd_flush.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void xlvbd_flush(struct blkfront_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/xen-blkfront.c (0)
Location: drivers/block/xen-blkfront.c:985
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
```
**Symbols:**

```
ffffffff819b9cd0-ffffffff819b9d38: xlvbd_flush (STB_LOCAL)
ffffffff81ece37c-ffffffff81ece3e3: xlvbd_flush.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void xlvbd_flush(struct blkfront_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff81b2f120)
Location: drivers/block/xen-blkfront.c:988
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
```
**Symbols:**

```
ffffffff81b2f120-ffffffff81b2f1e2: xlvbd_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void xlvbd_flush(struct blkfront_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff81b82580)
Location: drivers/block/xen-blkfront.c:989
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
```
**Symbols:**

```
ffffffff81b82580-ffffffff81b82640: xlvbd_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void xlvbd_flush(struct blkfront_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff81bd6440)
Location: drivers/block/xen-blkfront.c:989
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
```
**Symbols:**

```
ffffffff81bd6440-ffffffff81bd6500: xlvbd_flush (STB_LOCAL)
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
void xlvbd_flush(struct blkfront_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffff8000109256d8)
Location: drivers/block/xen-blkfront.c:1012
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
```
**Symbols:**

```
ffff8000109256d8-ffff80001092578c: xlvbd_flush (STB_LOCAL)
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
void xlvbd_flush(struct blkfront_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/xen-blkfront.c (0)
Location: drivers/block/xen-blkfront.c:1028
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkfront_restore
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
```
**Symbols:**

```
ffffffff816f4210-ffffffff816f426b: xlvbd_flush (STB_LOCAL)
ffffffff816f9ebc-ffffffff816f9f03: xlvbd_flush.cold (STB_LOCAL)
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
void xlvbd_flush(struct blkfront_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/xen-blkfront.c (0)
Location: drivers/block/xen-blkfront.c:1012
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
```
**Symbols:**

```
ffffffff81721c70-ffffffff81721ccb: xlvbd_flush (STB_LOCAL)
ffffffff817272e8-ffffffff8172732f: xlvbd_flush.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void xlvbd_flush(struct blkfront_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/xen-blkfront.c (0)
Location: drivers/block/xen-blkfront.c:1012
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
```
**Symbols:**

```
ffffffff8173d060-ffffffff8173d0bb: xlvbd_flush (STB_LOCAL)
ffffffff81742738-ffffffff8174277f: xlvbd_flush.cold (STB_LOCAL)
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
