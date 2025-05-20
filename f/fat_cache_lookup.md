# Function: <code>fat_cache_lookup</code>

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
In fs/fat/cache.c (ffffffff812f560a)
Location: fs/fat/cache.c:79
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_get_cluster
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
In fs/fat/cache.c (ffffffff81329028)
Location: fs/fat/cache.c:79
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_get_cluster
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
In fs/fat/cache.c (ffffffff8133ed68)
Location: fs/fat/cache.c:79
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_get_cluster
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
In fs/fat/cache.c (ffffffff81353928)
Location: fs/fat/cache.c:79
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_get_cluster
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
In fs/fat/cache.c (ffffffff81378548)
Location: fs/fat/cache.c:80
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_get_cluster
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
In fs/fat/cache.c (ffffffff813a6ffe)
Location: fs/fat/cache.c:80
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_get_cluster
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
In fs/fat/cache.c (ffffffff813bfdee)
Location: fs/fat/cache.c:80
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_get_cluster
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
In fs/fat/cache.c (ffffffff813ea5f0)
Location: fs/fat/cache.c:80
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_get_cluster
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
In fs/fat/cache.c (ffffffff81404690)
Location: fs/fat/cache.c:80
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_get_cluster
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int fat_cache_lookup(struct inode *inode, int fclus, struct fat_cache_id *cid, int *cached_fclus, int *cached_dclus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/cache.c (ffffffff81452230)
Location: fs/fat/cache.c:80
Inline: False
Direct callers:
  - fs/fat/cache.c:fat_get_cluster
```
**Symbols:**

```
ffffffff81452230-ffffffff81452338: fat_cache_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int fat_cache_lookup(struct inode *inode, int fclus, struct fat_cache_id *cid, int *cached_fclus, int *cached_dclus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/cache.c (ffffffff8146e710)
Location: fs/fat/cache.c:80
Inline: False
Direct callers:
  - fs/fat/cache.c:fat_get_cluster
```
**Symbols:**

```
ffffffff8146e710-ffffffff8146e818: fat_cache_lookup (STB_LOCAL)
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
In fs/fat/cache.c (ffffffff81473ff0)
Location: fs/fat/cache.c:80
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_get_cluster
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
In fs/fat/cache.c (ffffffff814cac9b)
Location: fs/fat/cache.c:80
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_get_cluster
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
In fs/fat/cache.c (ffffffff81556d0f)
Location: fs/fat/cache.c:80
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_get_cluster
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
In fs/fat/cache.c (ffffffff815f88b5)
Location: fs/fat/cache.c:80
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_get_cluster
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
In fs/fat/cache.c (ffffffff81630835)
Location: fs/fat/cache.c:80
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_get_cluster
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
In fs/fat/cache.c (ffffffff81669ce5)
Location: fs/fat/cache.c:80
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_get_cluster
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
In fs/fat/cache.c (ffff8000104e3264)
Location: fs/fat/cache.c:80
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_get_cluster
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
In fs/fat/cache.c (c06a2388)
Location: fs/fat/cache.c:80
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_get_cluster
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
In fs/fat/cache.c (c0000000006203e0)
Location: fs/fat/cache.c:80
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_get_cluster
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
In fs/fat/cache.c (ffffffe000356a72)
Location: fs/fat/cache.c:80
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_get_cluster
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
In fs/fat/cache.c (ffffffff813fcc70)
Location: fs/fat/cache.c:80
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_get_cluster
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
In fs/fat/cache.c (ffffffff813ed6f0)
Location: fs/fat/cache.c:80
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_get_cluster
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
In fs/fat/cache.c (ffffffff813f9ff0)
Location: fs/fat/cache.c:80
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_get_cluster
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
In fs/fat/cache.c (ffffffff8140fc27)
Location: fs/fat/cache.c:80
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_get_cluster
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
