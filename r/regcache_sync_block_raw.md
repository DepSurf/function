# Function: <code>regcache_sync_block_raw</code>

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
In drivers/base/regmap/regcache.c (ffffffff815683a4)
Location: drivers/base/regmap/regcache.c:685
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
In drivers/base/regmap/regcache.c (ffffffff815bcf45)
Location: drivers/base/regmap/regcache.c:734
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
In drivers/base/regmap/regcache.c (ffffffff815ec355)
Location: drivers/base/regmap/regcache.c:734
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
In drivers/base/regmap/regcache.c (ffffffff81600c3d)
Location: drivers/base/regmap/regcache.c:736
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
In drivers/base/regmap/regcache.c (ffffffff81668fad)
Location: drivers/base/regmap/regcache.c:736
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
In drivers/base/regmap/regcache.c (ffffffff816a4931)
Location: drivers/base/regmap/regcache.c:736
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
In drivers/base/regmap/regcache.c (ffffffff816c5471)
Location: drivers/base/regmap/regcache.c:736
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
In drivers/base/regmap/regcache.c (ffffffff817003d6)
Location: drivers/base/regmap/regcache.c:732
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
In drivers/base/regmap/regcache.c (ffffffff81724756)
Location: drivers/base/regmap/regcache.c:732
Inline: True
Inline callers:
  - drivers/base/regmap/regcache.c:regcache_sync_block
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int regcache_sync_block_raw(struct regmap *map, void *block, long unsigned int *cache_present, unsigned int block_base, unsigned int start, unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (ffffffff817e07c0)
Location: drivers/base/regmap/regcache.c:732
Inline: False
Direct callers:
  - drivers/base/regmap/regcache.c:regcache_sync_block
```
**Symbols:**

```
ffffffff817e07c0-ffffffff817e0961: regcache_sync_block_raw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int regcache_sync_block_raw(struct regmap *map, void *block, long unsigned int *cache_present, unsigned int block_base, unsigned int start, unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (ffffffff817f56b0)
Location: drivers/base/regmap/regcache.c:732
Inline: False
Direct callers:
  - drivers/base/regmap/regcache.c:regcache_sync_block
```
**Symbols:**

```
ffffffff817f56b0-ffffffff817f5851: regcache_sync_block_raw (STB_LOCAL)
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
In drivers/base/regmap/regcache.c (ffffffff817da18c)
Location: drivers/base/regmap/regcache.c:732
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
In drivers/base/regmap/regcache.c (ffffffff81865960)
Location: drivers/base/regmap/regcache.c:732
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
In drivers/base/regmap/regcache.c (ffffffff819ade82)
Location: drivers/base/regmap/regcache.c:732
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
In drivers/base/regmap/regcache.c (ffffffff81b218b8)
Location: drivers/base/regmap/regcache.c:739
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
In drivers/base/regmap/regcache.c (ffffffff81b70b65)
Location: drivers/base/regmap/regcache.c:753
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
In drivers/base/regmap/regcache.c (ffffffff81bc4865)
Location: drivers/base/regmap/regcache.c:790
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
In drivers/base/regmap/regcache.c (ffff8000109194f4)
Location: drivers/base/regmap/regcache.c:732
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
In drivers/base/regmap/regcache.c (c09ff12c)
Location: drivers/base/regmap/regcache.c:732
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
In drivers/base/regmap/regcache.c (c0000000009bd074)
Location: drivers/base/regmap/regcache.c:732
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
In drivers/base/regmap/regcache.c (ffffffe0005996c0)
Location: drivers/base/regmap/regcache.c:732
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
In drivers/base/regmap/regcache.c (ffffffff816eaa86)
Location: drivers/base/regmap/regcache.c:732
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
In drivers/base/regmap/regcache.c (ffffffff816c50c6)
Location: drivers/base/regmap/regcache.c:732
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
In drivers/base/regmap/regcache.c (ffffffff81717c16)
Location: drivers/base/regmap/regcache.c:732
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
In drivers/base/regmap/regcache.c (ffffffff81732f76)
Location: drivers/base/regmap/regcache.c:732
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
