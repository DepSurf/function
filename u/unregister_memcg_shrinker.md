# Function: <code>unregister_memcg_shrinker</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/vmscan.c (ffffffff81218e50)
Location: mm/vmscan.c:220
Inline: True
Direct callers:
  - mm/vmscan.c:unregister_shrinker
  - mm/vmscan.c:free_prealloced_shrinker
```
**Symbols:**

```
ffffffff81218e50-ffffffff81218e8c: unregister_memcg_shrinker.isra.45 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/vmscan.c (ffffffff81228860)
Location: mm/vmscan.c:220
Inline: True
Direct callers:
  - mm/vmscan.c:unregister_shrinker
  - mm/vmscan.c:free_prealloced_shrinker
```
**Symbols:**

```
ffffffff81228860-ffffffff8122889c: unregister_memcg_shrinker.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/vmscan.c (ffffffff81236700)
Location: mm/vmscan.c:231
Inline: True
Direct callers:
  - mm/vmscan.c:unregister_shrinker
  - mm/vmscan.c:free_prealloced_shrinker
```
**Symbols:**

```
ffffffff81236700-ffffffff8123673c: unregister_memcg_shrinker.isra.0 (STB_LOCAL)
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
In mm/vmscan.c (ffffffff81263a50)
Location: mm/vmscan.c:236
Inline: True
Direct callers:
  - mm/vmscan.c:unregister_shrinker
  - mm/vmscan.c:free_prealloced_shrinker
```
**Symbols:**

```
ffffffff81263a50-ffffffff81263a8f: unregister_memcg_shrinker.isra.0 (STB_LOCAL)
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
In mm/vmscan.c (ffffffff8126e3e0)
Location: mm/vmscan.c:229
Inline: True
Direct callers:
  - mm/vmscan.c:unregister_shrinker
  - mm/vmscan.c:free_prealloced_shrinker
```
**Symbols:**

```
ffffffff8126e3e0-ffffffff8126e41f: unregister_memcg_shrinker.isra.0 (STB_LOCAL)
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
In mm/vmscan.c (ffffffff8127710a)
Location: mm/vmscan.c:374
Inline: True
Inline callers:
  - mm/vmscan.c:free_prealloced_shrinker
  - mm/vmscan.c:free_prealloced_shrinker
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
In mm/vmscan.c (ffffffff812b4a4a)
Location: mm/vmscan.c:378
Inline: True
Inline callers:
  - mm/vmscan.c:free_prealloced_shrinker
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
In mm/vmscan.c (ffffffff81310a24)
Location: mm/vmscan.c:380
Inline: True
Inline callers:
  - mm/vmscan.c:free_prealloced_shrinker
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
In mm/vmscan.c (ffffffff81383eb4)
Location: mm/vmscan.c:394
Inline: True
Inline callers:
  - mm/vmscan.c:free_prealloced_shrinker
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
In mm/vmscan.c (ffffffff813b5964)
Location: mm/vmscan.c:379
Inline: True
Inline callers:
  - mm/vmscan.c:free_prealloced_shrinker
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/vmscan.c (ffff8000102c6308)
Location: mm/vmscan.c:231
Inline: True
Direct callers:
  - mm/vmscan.c:unregister_shrinker
  - mm/vmscan.c:free_prealloced_shrinker
```
**Symbols:**

```
ffff8000102c6308-ffff8000102c6358: unregister_memcg_shrinker.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void unregister_memcg_shrinker(struct shrinker *shrinker);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (c04f1444)
Location: mm/vmscan.c:231
Inline: True
Direct callers:
  - mm/vmscan.c:unregister_shrinker
  - mm/vmscan.c:free_prealloced_shrinker
```
**Symbols:**

```
c04f1444-c04f1494: unregister_memcg_shrinker (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/vmscan.c (c000000000382580)
Location: mm/vmscan.c:231
Inline: True
Direct callers:
  - mm/vmscan.c:unregister_shrinker
  - mm/vmscan.c:free_prealloced_shrinker
```
**Symbols:**

```
c000000000382580-c0000000003825f8: unregister_memcg_shrinker.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/vmscan.c (ffffffe0001e6c4e)
Location: mm/vmscan.c:231
Inline: True
Direct callers:
  - mm/vmscan.c:unregister_shrinker
  - mm/vmscan.c:free_prealloced_shrinker
```
**Symbols:**

```
ffffffe0001e6c4e-ffffffe0001e6ca6: unregister_memcg_shrinker.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/vmscan.c (ffffffff8122ed50)
Location: mm/vmscan.c:231
Inline: True
Direct callers:
  - mm/vmscan.c:unregister_shrinker
  - mm/vmscan.c:free_prealloced_shrinker
```
**Symbols:**

```
ffffffff8122ed50-ffffffff8122ed8c: unregister_memcg_shrinker.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/vmscan.c (ffffffff81221e10)
Location: mm/vmscan.c:231
Inline: True
Direct callers:
  - mm/vmscan.c:unregister_shrinker
  - mm/vmscan.c:free_prealloced_shrinker
```
**Symbols:**

```
ffffffff81221e10-ffffffff81221e4c: unregister_memcg_shrinker.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/vmscan.c (ffffffff8122caf0)
Location: mm/vmscan.c:231
Inline: True
Direct callers:
  - mm/vmscan.c:unregister_shrinker
  - mm/vmscan.c:free_prealloced_shrinker
```
**Symbols:**

```
ffffffff8122caf0-ffffffff8122cb2c: unregister_memcg_shrinker.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/vmscan.c (ffffffff8123bf20)
Location: mm/vmscan.c:231
Inline: True
Direct callers:
  - mm/vmscan.c:unregister_shrinker
  - mm/vmscan.c:free_prealloced_shrinker
```
**Symbols:**

```
ffffffff8123bf20-ffffffff8123bf5c: unregister_memcg_shrinker.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
