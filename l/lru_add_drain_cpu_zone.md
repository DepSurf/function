# Function: <code>lru_add_drain_cpu_zone</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void lru_add_drain_cpu_zone(struct zone *zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff812605a0)
Location: mm/swap.c:738
Inline: False
Direct callers:
  - mm/compaction.c:compact_zone
```
**Symbols:**

```
ffffffff812605a0-ffffffff812605e2: lru_add_drain_cpu_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void lru_add_drain_cpu_zone(struct zone *zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff8126ac20)
Location: mm/swap.c:724
Inline: False
Direct callers:
  - mm/compaction.c:compact_zone
```
**Symbols:**

```
ffffffff8126ac20-ffffffff8126ac62: lru_add_drain_cpu_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void lru_add_drain_cpu_zone(struct zone *zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff8126fe00)
Location: mm/swap.c:728
Inline: False
Direct callers:
  - mm/compaction.c:compact_zone
```
**Symbols:**

```
ffffffff8126fe00-ffffffff8126fe42: lru_add_drain_cpu_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void lru_add_drain_cpu_zone(struct zone *zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff812ad1e0)
Location: mm/swap.c:719
Inline: False
Direct callers:
  - mm/compaction.c:compact_zone
```
**Symbols:**

```
ffffffff812ad1e0-ffffffff812ad222: lru_add_drain_cpu_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void lru_add_drain_cpu_zone(struct zone *zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81307250)
Location: mm/swap.c:726
Inline: False
Direct callers:
  - mm/compaction.c:compact_zone
```
**Symbols:**

```
ffffffff81307250-ffffffff813072a8: lru_add_drain_cpu_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void lru_add_drain_cpu_zone(struct zone *zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81371110)
Location: mm/swap.c:806
Inline: False
Direct callers:
  - mm/compaction.c:compact_zone
```
**Symbols:**

```
ffffffff81371110-ffffffff81371168: lru_add_drain_cpu_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void lru_add_drain_cpu_zone(struct zone *zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff813a32a0)
Location: mm/swap.c:772
Inline: False
Direct callers:
  - mm/compaction.c:compact_zone
```
**Symbols:**

```
ffffffff813a32a0-ffffffff813a32f8: lru_add_drain_cpu_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void lru_add_drain_cpu_zone(struct zone *zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff813ccf10)
Location: mm/swap.c:772
Inline: False
Direct callers:
  - mm/compaction.c:compact_zone
```
**Symbols:**

```
ffffffff813ccf10-ffffffff813ccf68: lru_add_drain_cpu_zone (STB_GLOBAL)
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
