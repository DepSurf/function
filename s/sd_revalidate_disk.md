# Function: <code>sd_revalidate_disk</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int sd_revalidate_disk(struct gendisk *disk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff815bda60)
Location: drivers/scsi/sd.c:2825
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_probe_async
  - drivers/scsi/sd.c:sd_probe_async
```
**Symbols:**

```
ffffffff815bda60-ffffffff815beda2: sd_revalidate_disk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int sd_revalidate_disk(struct gendisk *disk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81616870)
Location: drivers/scsi/sd.c:2806
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_probe_async
  - drivers/scsi/sd.c:sd_probe_async
```
**Symbols:**

```
ffffffff81616870-ffffffff81617bab: sd_revalidate_disk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int sd_revalidate_disk(struct gendisk *disk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81646300)
Location: drivers/scsi/sd.c:2889
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_probe_async
  - drivers/scsi/sd.c:sd_probe_async
```
**Symbols:**

```
ffffffff81646300-ffffffff81647744: sd_revalidate_disk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int sd_revalidate_disk(struct gendisk *disk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff8165ae80)
Location: drivers/scsi/sd.c:3053
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_probe_async
  - drivers/scsi/sd.c:sd_probe_async
```
**Symbols:**

```
ffffffff8165ae80-ffffffff8165c2a8: sd_revalidate_disk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int sd_revalidate_disk(struct gendisk *disk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff816c44d0)
Location: drivers/scsi/sd.c:3089
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_probe_async
  - drivers/scsi/sd.c:sd_probe_async
```
**Symbols:**

```
ffffffff816c44d0-ffffffff816c5911: sd_revalidate_disk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int sd_revalidate_disk(struct gendisk *disk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/sd.c (0)
Location: drivers/scsi/sd.c:3063
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_probe_async
  - drivers/scsi/sd.c:sd_probe_async
```
**Symbols:**

```
ffffffff81700a30-ffffffff81701e76: sd_revalidate_disk (STB_LOCAL)
ffffffff817020a7-ffffffff817020d6: sd_revalidate_disk.cold.38 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int sd_revalidate_disk(struct gendisk *disk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/sd.c (0)
Location: drivers/scsi/sd.c:3102
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_probe_async
  - drivers/scsi/sd.c:sd_probe_async
```
**Symbols:**

```
ffffffff817237d0-ffffffff81724e3c: sd_revalidate_disk (STB_LOCAL)
ffffffff81725069-ffffffff81725098: sd_revalidate_disk.cold.38 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int sd_revalidate_disk(struct gendisk *disk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff8175edb0)
Location: drivers/scsi/sd.c:3088
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
```
**Symbols:**

```
ffffffff8175edb0-ffffffff8175fdfd: sd_revalidate_disk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int sd_revalidate_disk(struct gendisk *disk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81782d10)
Location: drivers/scsi/sd.c:3098
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
```
**Symbols:**

```
ffffffff81782d10-ffffffff81783d5b: sd_revalidate_disk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int sd_revalidate_disk(struct gendisk *disk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff818478b0)
Location: drivers/scsi/sd.c:3128
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
```
**Symbols:**

```
ffffffff818478b0-ffffffff81847ccf: sd_revalidate_disk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/sd.c (ffffffff818572c0)
Location: drivers/scsi/sd.c:3170
Inline: True
Direct callers:
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_rescan
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sd.c:cache_type_store
```
**Symbols:**

```
ffffffff818572c0-ffffffff81857722: sd_revalidate_disk.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/sd.c (ffffffff8183a030)
Location: drivers/scsi/sd.c:3185
Inline: True
Direct callers:
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_rescan
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sd.c:cache_type_store
```
**Symbols:**

```
ffffffff8183a030-ffffffff8183a674: sd_revalidate_disk.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/sd.c (0)
Location: drivers/scsi/sd.c:3155
Inline: True
Direct callers:
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_rescan
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sd.c:cache_type_store
```
**Symbols:**

```
ffffffff818c66b0-ffffffff818c6d2e: sd_revalidate_disk.isra.0 (STB_LOCAL)
ffffffff81d0cf49-ffffffff81d0cfda: sd_revalidate_disk.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/sd.c (0)
Location: drivers/scsi/sd.c:3209
Inline: True
Direct callers:
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_rescan
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sd.c:cache_type_store
```
**Symbols:**

```
ffffffff81a131c0-ffffffff81a13a6e: sd_revalidate_disk.isra.0 (STB_LOCAL)
ffffffff81ed5d6e-ffffffff81ed5df0: sd_revalidate_disk.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/sd.c (0)
Location: drivers/scsi/sd.c:3250
Inline: True
Direct callers:
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_rescan
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sd.c:cache_type_store
```
**Symbols:**

```
ffffffff81b93550-ffffffff81b93e24: sd_revalidate_disk.isra.0 (STB_LOCAL)
ffffffff8209beeb-ffffffff8209bf65: sd_revalidate_disk.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/sd.c (0)
Location: drivers/scsi/sd.c:3368
Inline: True
Direct callers:
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_rescan
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sd.c:cache_type_store
```
**Symbols:**

```
ffffffff81be9a80-ffffffff81bea38a: sd_revalidate_disk.isra.0 (STB_LOCAL)
ffffffff8211ce52-ffffffff8211cec6: sd_revalidate_disk.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/sd.c (0)
Location: drivers/scsi/sd.c:3433
Inline: True
Direct callers:
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_rescan
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sd.c:cache_type_store
```
**Symbols:**

```
ffffffff81c3efe0-ffffffff81c3f9ac: sd_revalidate_disk.isra.0 (STB_LOCAL)
ffffffff821fad55-ffffffff821fadc9: sd_revalidate_disk.isra.0.cold (STB_LOCAL)
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
int sd_revalidate_disk(struct gendisk *disk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffff8000109898f0)
Location: drivers/scsi/sd.c:3098
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
```
**Symbols:**

```
ffff8000109898f0-ffff80001098a54c: sd_revalidate_disk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int sd_revalidate_disk(struct gendisk *disk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (c0a5ba48)
Location: drivers/scsi/sd.c:3098
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
```
**Symbols:**

```
c0a5ba48-c0a5c788: sd_revalidate_disk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int sd_revalidate_disk(struct gendisk *disk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (c000000000a49c00)
Location: drivers/scsi/sd.c:3098
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
```
**Symbols:**

```
c000000000a49c00-c000000000a4acdc: sd_revalidate_disk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int sd_revalidate_disk(struct gendisk *disk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffe0005edb4c)
Location: drivers/scsi/sd.c:3098
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
```
**Symbols:**

```
ffffffe0005edb4c-ffffffe0005ee924: sd_revalidate_disk (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int sd_revalidate_disk(struct gendisk *disk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81737400)
Location: drivers/scsi/sd.c:3098
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
```
**Symbols:**

```
ffffffff81737400-ffffffff8173844b: sd_revalidate_disk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int sd_revalidate_disk(struct gendisk *disk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff817190a0)
Location: drivers/scsi/sd.c:3098
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
```
**Symbols:**

```
ffffffff817190a0-ffffffff8171a0eb: sd_revalidate_disk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int sd_revalidate_disk(struct gendisk *disk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81777b90)
Location: drivers/scsi/sd.c:3098
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
```
**Symbols:**

```
ffffffff81777b90-ffffffff81778bdb: sd_revalidate_disk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int sd_revalidate_disk(struct gendisk *disk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff817919b0)
Location: drivers/scsi/sd.c:3098
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
```
**Symbols:**

```
ffffffff817919b0-ffffffff817929fb: sd_revalidate_disk (STB_LOCAL)
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
