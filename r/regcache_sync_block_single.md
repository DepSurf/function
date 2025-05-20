# Function: <code>regcache_sync_block_single</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (ffffffff815682b0)
Location: drivers/base/regmap/regcache.c:621
Inline: True
Inline callers:
  - drivers/base/regmap/regcache.c:regcache_sync_block
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
In drivers/base/regmap/regcache.c (ffffffff815bce40)
Location: drivers/base/regmap/regcache.c:670
Inline: True
Inline callers:
  - drivers/base/regmap/regcache.c:regcache_sync_block
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
In drivers/base/regmap/regcache.c (ffffffff815ec250)
Location: drivers/base/regmap/regcache.c:670
Inline: True
Inline callers:
  - drivers/base/regmap/regcache.c:regcache_sync_block
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
In drivers/base/regmap/regcache.c (ffffffff81600b4e)
Location: drivers/base/regmap/regcache.c:672
Inline: True
Inline callers:
  - drivers/base/regmap/regcache.c:regcache_sync_block
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
In drivers/base/regmap/regcache.c (ffffffff81668ebe)
Location: drivers/base/regmap/regcache.c:672
Inline: True
Inline callers:
  - drivers/base/regmap/regcache.c:regcache_sync_block
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
In drivers/base/regmap/regcache.c (0)
Location: drivers/base/regmap/regcache.c:672
Inline: True
Inline callers:
  - drivers/base/regmap/regcache.c:regcache_sync_block
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
In drivers/base/regmap/regcache.c (0)
Location: drivers/base/regmap/regcache.c:672
Inline: True
Inline callers:
  - drivers/base/regmap/regcache.c:regcache_sync_block
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
In drivers/base/regmap/regcache.c (0)
Location: drivers/base/regmap/regcache.c:668
Inline: True
Inline callers:
  - drivers/base/regmap/regcache.c:regcache_sync_block
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
In drivers/base/regmap/regcache.c (0)
Location: drivers/base/regmap/regcache.c:668
Inline: True
Inline callers:
  - drivers/base/regmap/regcache.c:regcache_sync_block
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int regcache_sync_block_single(struct regmap *map, void *block, long unsigned int *cache_present, unsigned int block_base, unsigned int start, unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regcache.c (0)
Location: drivers/base/regmap/regcache.c:668
Inline: False
Direct callers:
  - drivers/base/regmap/regcache.c:regcache_sync_block
```
**Symbols:**

```
ffffffff817e0970-ffffffff817e0ae8: regcache_sync_block_single (STB_LOCAL)
ffffffff817e0d48-ffffffff817e0d68: regcache_sync_block_single.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int regcache_sync_block_single(struct regmap *map, void *block, long unsigned int *cache_present, unsigned int block_base, unsigned int start, unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regcache.c (0)
Location: drivers/base/regmap/regcache.c:668
Inline: False
Direct callers:
  - drivers/base/regmap/regcache.c:regcache_sync_block
```
**Symbols:**

```
ffffffff817f5860-ffffffff817f59d8: regcache_sync_block_single (STB_LOCAL)
ffffffff81c0f61d-ffffffff81c0f63d: regcache_sync_block_single.cold (STB_LOCAL)
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
In drivers/base/regmap/regcache.c (0)
Location: drivers/base/regmap/regcache.c:668
Inline: True
Inline callers:
  - drivers/base/regmap/regcache.c:regcache_sync_block
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
In drivers/base/regmap/regcache.c (0)
Location: drivers/base/regmap/regcache.c:668
Inline: True
Inline callers:
  - drivers/base/regmap/regcache.c:regcache_sync_block
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
In drivers/base/regmap/regcache.c (0)
Location: drivers/base/regmap/regcache.c:668
Inline: True
Inline callers:
  - drivers/base/regmap/regcache.c:regcache_sync_block
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
In drivers/base/regmap/regcache.c (0)
Location: drivers/base/regmap/regcache.c:675
Inline: True
Inline callers:
  - drivers/base/regmap/regcache.c:regcache_sync_block
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
In drivers/base/regmap/regcache.c (ffffffff81b70aae)
Location: drivers/base/regmap/regcache.c:701
Inline: True
Inline callers:
  - drivers/base/regmap/regcache.c:regcache_sync_block
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
In drivers/base/regmap/regcache.c (ffffffff81bc47ae)
Location: drivers/base/regmap/regcache.c:738
Inline: True
Inline callers:
  - drivers/base/regmap/regcache.c:regcache_sync_block
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
In drivers/base/regmap/regcache.c (0)
Location: drivers/base/regmap/regcache.c:668
Inline: True
Inline callers:
  - drivers/base/regmap/regcache.c:regcache_sync_block
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
In drivers/base/regmap/regcache.c (0)
Location: drivers/base/regmap/regcache.c:668
Inline: True
Inline callers:
  - drivers/base/regmap/regcache.c:regcache_sync_block
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
In drivers/base/regmap/regcache.c (0)
Location: drivers/base/regmap/regcache.c:668
Inline: True
Inline callers:
  - drivers/base/regmap/regcache.c:regcache_sync_block
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
In drivers/base/regmap/regcache.c (ffffffe0005995f6)
Location: drivers/base/regmap/regcache.c:668
Inline: True
Inline callers:
  - drivers/base/regmap/regcache.c:regcache_sync_block
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
In drivers/base/regmap/regcache.c (0)
Location: drivers/base/regmap/regcache.c:668
Inline: True
Inline callers:
  - drivers/base/regmap/regcache.c:regcache_sync_block
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
In drivers/base/regmap/regcache.c (0)
Location: drivers/base/regmap/regcache.c:668
Inline: True
Inline callers:
  - drivers/base/regmap/regcache.c:regcache_sync_block
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
In drivers/base/regmap/regcache.c (0)
Location: drivers/base/regmap/regcache.c:668
Inline: True
Inline callers:
  - drivers/base/regmap/regcache.c:regcache_sync_block
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
In drivers/base/regmap/regcache.c (0)
Location: drivers/base/regmap/regcache.c:668
Inline: True
Inline callers:
  - drivers/base/regmap/regcache.c:regcache_sync_block
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
