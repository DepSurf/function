# Function: <code>dax_add_host</code>

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
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff8163cc7b)
Location: drivers/dax/super.c:417
Inline: True
Inline callers:
  - drivers/dax/super.c:alloc_dax
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
In drivers/dax/super.c (ffffffff816a594b)
Location: drivers/dax/super.c:446
Inline: True
Inline callers:
  - drivers/dax/super.c:alloc_dax
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
In drivers/dax/super.c (ffffffff816e1d1b)
Location: drivers/dax/super.c:472
Inline: True
Inline callers:
  - drivers/dax/super.c:alloc_dax
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
In drivers/dax/super.c (ffffffff8170513b)
Location: drivers/dax/super.c:471
Inline: True
Inline callers:
  - drivers/dax/super.c:alloc_dax
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
In drivers/dax/super.c (ffffffff8173ef97)
Location: drivers/dax/super.c:527
Inline: True
Inline callers:
  - drivers/dax/super.c:alloc_dax
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
In drivers/dax/super.c (ffffffff81763177)
Location: drivers/dax/super.c:527
Inline: True
Inline callers:
  - drivers/dax/super.c:alloc_dax
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
In drivers/dax/super.c (ffffffff81822fd4)
Location: drivers/dax/super.c:548
Inline: True
Inline callers:
  - drivers/dax/super.c:alloc_dax
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
In drivers/dax/super.c (ffffffff81831d14)
Location: drivers/dax/super.c:556
Inline: True
Inline callers:
  - drivers/dax/super.c:alloc_dax
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
In drivers/dax/super.c (ffffffff81814f44)
Location: drivers/dax/super.c:556
Inline: True
Inline callers:
  - drivers/dax/super.c:alloc_dax
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
In drivers/dax/super.c (ffffffff8189f6b4)
Location: drivers/dax/super.c:543
Inline: True
Inline callers:
  - drivers/dax/super.c:alloc_dax
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int dax_add_host(struct dax_device *dax_dev, struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff819e9380)
Location: drivers/dax/super.c:58
Inline: False
Direct callers:
  - drivers/md/dm.c:alloc_dev
```
**Symbols:**

```
ffffffff819e9380-ffffffff819e93d6: dax_add_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int dax_add_host(struct dax_device *dax_dev, struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81b65a70)
Location: drivers/dax/super.c:62
Inline: False
Direct callers:
  - drivers/md/dm.c:alloc_dev
```
**Symbols:**

```
ffffffff81b65a70-ffffffff81b65acb: dax_add_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int dax_add_host(struct dax_device *dax_dev, struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81bb9090)
Location: drivers/dax/super.c:62
Inline: False
Direct callers:
  - drivers/md/dm.c:alloc_dev
```
**Symbols:**

```
ffffffff81bb9090-ffffffff81bb90eb: dax_add_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int dax_add_host(struct dax_device *dax_dev, struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81c0d6f0)
Location: drivers/dax/super.c:62
Inline: False
Direct callers:
  - drivers/md/dm.c:alloc_dev
```
**Symbols:**

```
ffffffff81c0d6f0-ffffffff81c0d74b: dax_add_host (STB_GLOBAL)
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
In drivers/dax/super.c (ffff800010963988)
Location: drivers/dax/super.c:527
Inline: True
Inline callers:
  - drivers/dax/super.c:alloc_dax
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (c0a39bcc)
Location: drivers/dax/super.c:527
Inline: True
Inline callers:
  - drivers/dax/super.c:alloc_dax
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (c000000000a18dc8)
Location: drivers/dax/super.c:527
Inline: True
Inline callers:
  - drivers/dax/super.c:alloc_dax
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffe0005d0516)
Location: drivers/dax/super.c:527
Inline: True
Inline callers:
  - drivers/dax/super.c:alloc_dax
```
</details>
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
In drivers/dax/super.c (ffffffff81717867)
Location: drivers/dax/super.c:527
Inline: True
Inline callers:
  - drivers/dax/super.c:alloc_dax
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff816efd97)
Location: drivers/dax/super.c:527
Inline: True
Inline callers:
  - drivers/dax/super.c:alloc_dax
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81756637)
Location: drivers/dax/super.c:527
Inline: True
Inline callers:
  - drivers/dax/super.c:alloc_dax
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
In drivers/dax/super.c (ffffffff81771898)
Location: drivers/dax/super.c:527
Inline: True
Inline callers:
  - drivers/dax/super.c:alloc_dax
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
