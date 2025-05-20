# Function: <code>blkif_recover</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int blkif_recover(struct blkfront_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff81577b00)
Location: drivers/block/xen-blkfront.c:1650
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkback_changed
```
**Symbols:**

```
ffffffff81577b00-ffffffff815788c3: blkif_recover (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff815cd9fc)
Location: drivers/block/xen-blkfront.c:2007
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkback_changed
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff815fa2bd)
Location: drivers/block/xen-blkfront.c:1998
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_connect
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff8160e52f)
Location: drivers/block/xen-blkfront.c:1998
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkback_changed
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff81676daf)
Location: drivers/block/xen-blkfront.c:1998
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkback_changed
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff816b2fec)
Location: drivers/block/xen-blkfront.c:2002
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkback_changed
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff816d424e)
Location: drivers/block/xen-blkfront.c:2015
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkback_changed
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff8170e3da)
Location: drivers/block/xen-blkfront.c:2015
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_connect
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff817326da)
Location: drivers/block/xen-blkfront.c:2015
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_connect
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff817edc80)
Location: drivers/block/xen-blkfront.c:2021
Inline: True
Direct callers:
  - drivers/block/xen-blkfront.c:blkfront_connect
```
**Symbols:**

```
ffffffff817edc80-ffffffff817ede5b: blkif_recover.isra.0 (STB_LOCAL)
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
In drivers/block/xen-blkfront.c (ffffffff818025b0)
Location: drivers/block/xen-blkfront.c:2031
Inline: True
Direct callers:
  - drivers/block/xen-blkfront.c:blkfront_connect
```
**Symbols:**

```
ffffffff818025b0-ffffffff8180278b: blkif_recover.isra.0 (STB_LOCAL)
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
In drivers/block/xen-blkfront.c (ffffffff817e6fe0)
Location: drivers/block/xen-blkfront.c:2031
Inline: True
Direct callers:
  - drivers/block/xen-blkfront.c:blkfront_connect
```
**Symbols:**

```
ffffffff817e6fe0-ffffffff817e71bb: blkif_recover.isra.0 (STB_LOCAL)
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
In drivers/block/xen-blkfront.c (ffffffff81876c8c)
Location: drivers/block/xen-blkfront.c:2020
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_connect
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
In drivers/block/xen-blkfront.c (ffffffff819bee92)
Location: drivers/block/xen-blkfront.c:2002
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_connect
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
In drivers/block/xen-blkfront.c (ffffffff81b347b8)
Location: drivers/block/xen-blkfront.c:2006
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_connect
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
In drivers/block/xen-blkfront.c (ffffffff81b87c35)
Location: drivers/block/xen-blkfront.c:2007
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_connect
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
In drivers/block/xen-blkfront.c (ffffffff81bdbae5)
Location: drivers/block/xen-blkfront.c:2007
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_connect
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffff800010929b28)
Location: drivers/block/xen-blkfront.c:2015
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_connect
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff816f8684)
Location: drivers/block/xen-blkfront.c:2040
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_connect
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff81725b9a)
Location: drivers/block/xen-blkfront.c:2015
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_connect
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff81740fea)
Location: drivers/block/xen-blkfront.c:2015
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_connect
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
