# Function: <code>invalidate_bh_lrus_cpu</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void invalidate_bh_lrus_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81371f80)
Location: fs/buffer.c:1453
Inline: False
Direct callers:
  - mm/swap.c:lru_add_drain_cpu
```
**Symbols:**

```
ffffffff81371f80-ffffffff81371ffb: invalidate_bh_lrus_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void invalidate_bh_lrus_cpu();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff813c0fb0)
Location: fs/buffer.c:1432
Inline: False
Direct callers:
  - mm/swap.c:lru_add_drain_per_cpu
```
**Symbols:**

```
ffffffff813c0fb0-ffffffff813c1028: invalidate_bh_lrus_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void invalidate_bh_lrus_cpu();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81447c70)
Location: fs/buffer.c:1431
Inline: False
Direct callers:
  - mm/swap.c:lru_add_drain_per_cpu
  - mm/swap.c:lru_add_drain_per_cpu
```
**Symbols:**

```
ffffffff81447c70-ffffffff81447cf0: invalidate_bh_lrus_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void invalidate_bh_lrus_cpu();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff814d6800)
Location: fs/buffer.c:1420
Inline: False
Direct callers:
  - mm/swap.c:lru_add_drain_per_cpu
  - mm/swap.c:lru_add_drain_per_cpu
```
**Symbols:**

```
ffffffff814d6800-ffffffff814d6884: invalidate_bh_lrus_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void invalidate_bh_lrus_cpu();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8150cdf0)
Location: fs/buffer.c:1532
Inline: False
Direct callers:
  - mm/swap.c:lru_add_drain_per_cpu
  - mm/swap.c:lru_add_drain_per_cpu
```
**Symbols:**

```
ffffffff8150cdf0-ffffffff8150ce9b: invalidate_bh_lrus_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void invalidate_bh_lrus_cpu();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff815419f0)
Location: fs/buffer.c:1527
Inline: False
Direct callers:
  - mm/swap.c:lru_add_drain_per_cpu
  - mm/swap.c:lru_add_drain_per_cpu
```
**Symbols:**

```
ffffffff815419f0-ffffffff81541a9b: invalidate_bh_lrus_cpu (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int cpu</code>
</li>
</ul>
</details>
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
