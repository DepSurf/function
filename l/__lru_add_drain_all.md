# Function: <code>__lru_add_drain_all</code>

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
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void __lru_add_drain_all(bool force_all_cpus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/swap.c (0)
Location: mm/swap.c:752
Inline: False
Direct callers:
  - mm/swap.c:lru_cache_disable
  - mm/swap.c:lru_add_drain_all
```
**Symbols:**

```
ffffffff81bd8bf7-ffffffff81bd8c03: __lru_add_drain_all.cold (STB_LOCAL)
ffffffff8126f7d0-ffffffff8126f9ca: __lru_add_drain_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void __lru_add_drain_all(bool force_all_cpus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/swap.c (0)
Location: mm/swap.c:743
Inline: False
Direct callers:
  - mm/swap.c:lru_cache_disable
  - mm/swap.c:lru_add_drain_all
```
**Symbols:**

```
ffffffff81cba597-ffffffff81cba5a3: __lru_add_drain_all.cold (STB_LOCAL)
ffffffff812ac920-ffffffff812acca9: __lru_add_drain_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void __lru_add_drain_all(bool force_all_cpus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/swap.c (0)
Location: mm/swap.c:751
Inline: False
Direct callers:
  - mm/swap.c:lru_cache_disable
  - mm/swap.c:lru_add_drain_all
```
**Symbols:**

```
ffffffff81302da0-ffffffff81303116: __lru_add_drain_all (STB_LOCAL)
ffffffff81e6bdda-ffffffff81e6bde6: __lru_add_drain_all.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __lru_add_drain_all(bool force_all_cpus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff8136dd70)
Location: mm/swap.c:846
Inline: False
Direct callers:
  - mm/swap.c:lru_cache_disable
  - mm/swap.c:lru_add_drain_all
```
**Symbols:**

```
ffffffff8136dd70-ffffffff8136e041: __lru_add_drain_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __lru_add_drain_all(bool force_all_cpus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff8139ff90)
Location: mm/swap.c:812
Inline: False
Direct callers:
  - mm/swap.c:lru_cache_disable
  - mm/swap.c:lru_add_drain_all
```
**Symbols:**

```
ffffffff8139ff90-ffffffff813a0261: __lru_add_drain_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __lru_add_drain_all(bool force_all_cpus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff813c9c10)
Location: mm/swap.c:812
Inline: False
Direct callers:
  - mm/swap.c:lru_cache_disable
  - mm/swap.c:lru_add_drain_all
```
**Symbols:**

```
ffffffff813c9c10-ffffffff813c9ee1: __lru_add_drain_all (STB_LOCAL)
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
