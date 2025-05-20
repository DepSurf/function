# Function: <code>xlbd_release_minors</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void xlbd_release_minors(unsigned int minor, unsigned int nr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff81573360)
Location: drivers/block/xen-blkfront.c:394
Inline: True
Direct callers:
  - drivers/block/xen-blkfront.c:xlvbd_release_gendisk
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
```
**Symbols:**

```
ffffffff81573360-ffffffff815733ae: xlbd_release_minors (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void xlbd_release_minors(unsigned int minor, unsigned int nr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff815ca270)
Location: drivers/block/xen-blkfront.c:456
Inline: True
Direct callers:
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
```
**Symbols:**

```
ffffffff815ca270-ffffffff815ca2be: xlbd_release_minors (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void xlbd_release_minors(unsigned int minor, unsigned int nr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff815f6ed0)
Location: drivers/block/xen-blkfront.c:456
Inline: True
Direct callers:
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
```
**Symbols:**

```
ffffffff815f6ed0-ffffffff815f6f1e: xlbd_release_minors (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void xlbd_release_minors(unsigned int minor, unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff8160ae00)
Location: drivers/block/xen-blkfront.c:460
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
```
**Symbols:**

```
ffffffff8160ae00-ffffffff8160ae4e: xlbd_release_minors (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void xlbd_release_minors(unsigned int minor, unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff816736d0)
Location: drivers/block/xen-blkfront.c:460
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
```
**Symbols:**

```
ffffffff816736d0-ffffffff8167371e: xlbd_release_minors (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void xlbd_release_minors(unsigned int minor, unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff816b1520)
Location: drivers/block/xen-blkfront.c:460
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
```
**Symbols:**

```
ffffffff816b1520-ffffffff816b156e: xlbd_release_minors (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void xlbd_release_minors(unsigned int minor, unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff816d1860)
Location: drivers/block/xen-blkfront.c:459
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
```
**Symbols:**

```
ffffffff816d1860-ffffffff816d18ae: xlbd_release_minors (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void xlbd_release_minors(unsigned int minor, unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff8170d2e0)
Location: drivers/block/xen-blkfront.c:459
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
```
**Symbols:**

```
ffffffff8170d2e0-ffffffff8170d332: xlbd_release_minors (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void xlbd_release_minors(unsigned int minor, unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff817315e0)
Location: drivers/block/xen-blkfront.c:459
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
```
**Symbols:**

```
ffffffff817315e0-ffffffff81731632: xlbd_release_minors (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void xlbd_release_minors(unsigned int minor, unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff817edee0)
Location: drivers/block/xen-blkfront.c:470
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
```
**Symbols:**

```
ffffffff817edee0-ffffffff817edf32: xlbd_release_minors (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void xlbd_release_minors(unsigned int minor, unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff81802810)
Location: drivers/block/xen-blkfront.c:470
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
```
**Symbols:**

```
ffffffff81802810-ffffffff81802862: xlbd_release_minors (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void xlbd_release_minors(unsigned int minor, unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff817e8ab0)
Location: drivers/block/xen-blkfront.c:470
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
```
**Symbols:**

```
ffffffff817e8ab0-ffffffff817e8b02: xlbd_release_minors (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void xlbd_release_minors(unsigned int minor, unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff81874f60)
Location: drivers/block/xen-blkfront.c:473
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkfront_remove
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
```
**Symbols:**

```
ffffffff81874f60-ffffffff81874fb2: xlbd_release_minors (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void xlbd_release_minors(unsigned int minor, unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff819b9d40)
Location: drivers/block/xen-blkfront.c:477
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkfront_remove
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
```
**Symbols:**

```
ffffffff819b9d40-ffffffff819b9d98: xlbd_release_minors (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void xlbd_release_minors(unsigned int minor, unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff81b2f200)
Location: drivers/block/xen-blkfront.c:480
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkfront_remove
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
```
**Symbols:**

```
ffffffff81b2f200-ffffffff81b2f258: xlbd_release_minors (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void xlbd_release_minors(unsigned int minor, unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff81b82650)
Location: drivers/block/xen-blkfront.c:480
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkfront_remove
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
```
**Symbols:**

```
ffffffff81b82650-ffffffff81b826a8: xlbd_release_minors (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void xlbd_release_minors(unsigned int minor, unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff81bd6510)
Location: drivers/block/xen-blkfront.c:480
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkfront_remove
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
```
**Symbols:**

```
ffffffff81bd6510-ffffffff81bd6568: xlbd_release_minors (STB_LOCAL)
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
void xlbd_release_minors(unsigned int minor, unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffff800010928ba0)
Location: drivers/block/xen-blkfront.c:459
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
```
**Symbols:**

```
ffff800010928ba0-ffff800010928c50: xlbd_release_minors (STB_LOCAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
void xlbd_release_minors(unsigned int minor, unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff816f7550)
Location: drivers/block/xen-blkfront.c:474
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
```
**Symbols:**

```
ffffffff816f7550-ffffffff816f75a2: xlbd_release_minors (STB_LOCAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void xlbd_release_minors(unsigned int minor, unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff81724aa0)
Location: drivers/block/xen-blkfront.c:459
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
```
**Symbols:**

```
ffffffff81724aa0-ffffffff81724af2: xlbd_release_minors (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void xlbd_release_minors(unsigned int minor, unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff8173d0c0)
Location: drivers/block/xen-blkfront.c:459
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
```
**Symbols:**

```
ffffffff8173d0c0-ffffffff8173d110: xlbd_release_minors (STB_LOCAL)
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
