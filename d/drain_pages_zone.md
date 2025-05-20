# Function: <code>drain_pages_zone</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void drain_pages_zone(unsigned int cpu, struct zone *zone);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81194a10)
Location: mm/page_alloc.c:1880
Inline: False
Direct callers:
  - mm/page_alloc.c:drain_pages
  - mm/page_alloc.c:drain_local_pages
```
**Symbols:**

```
ffffffff81194a10-ffffffff81194a66: drain_pages_zone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void drain_pages_zone(unsigned int cpu, struct zone *zone);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811a7e70)
Location: mm/page_alloc.c:2242
Inline: False
Direct callers:
  - mm/page_alloc.c:drain_local_pages
  - mm/page_alloc.c:drain_pages
```
**Symbols:**

```
ffffffff811a7e70-ffffffff811a7ec6: drain_pages_zone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void drain_pages_zone(unsigned int cpu, struct zone *zone);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811b8260)
Location: mm/page_alloc.c:2295
Inline: False
Direct callers:
  - mm/page_alloc.c:drain_local_pages
  - mm/page_alloc.c:drain_pages
```
**Symbols:**

```
ffffffff811b8260-ffffffff811b82b6: drain_pages_zone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void drain_pages_zone(unsigned int cpu, struct zone *zone);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811c00d0)
Location: mm/page_alloc.c:2393
Inline: False
Direct callers:
  - mm/page_alloc.c:drain_pages
```
**Symbols:**

```
ffffffff811c00d0-ffffffff811c0126: drain_pages_zone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void drain_pages_zone(unsigned int cpu, struct zone *zone);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811d4ab0)
Location: mm/page_alloc.c:2428
Inline: False
Direct callers:
  - mm/page_alloc.c:drain_pages
```
**Symbols:**

```
ffffffff811d4ab0-ffffffff811d4b06: drain_pages_zone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void drain_pages_zone(unsigned int cpu, struct zone *zone);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811f5780)
Location: mm/page_alloc.c:2535
Inline: False
Direct callers:
  - mm/page_alloc.c:drain_pages
```
**Symbols:**

```
ffffffff811f5780-ffffffff811f57c8: drain_pages_zone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void drain_pages_zone(unsigned int cpu, struct zone *zone);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812081e0)
Location: mm/page_alloc.c:2628
Inline: False
Direct callers:
  - mm/page_alloc.c:drain_local_pages
  - mm/page_alloc.c:drain_pages
```
**Symbols:**

```
ffffffff812081e0-ffffffff81208228: drain_pages_zone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void drain_pages_zone(unsigned int cpu, struct zone *zone);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8126e5d0)
Location: mm/page_alloc.c:2804
Inline: False
Direct callers:
  - mm/page_alloc.c:drain_local_pages
  - mm/page_alloc.c:drain_pages
```
**Symbols:**

```
ffffffff8126e5d0-ffffffff8126e619: drain_pages_zone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void drain_pages_zone(unsigned int cpu, struct zone *zone);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8127d410)
Location: mm/page_alloc.c:2795
Inline: False
Direct callers:
  - mm/page_alloc.c:drain_local_pages
  - mm/page_alloc.c:drain_pages
```
**Symbols:**

```
ffffffff8127d410-ffffffff8127d459: drain_pages_zone (STB_LOCAL)
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
In mm/page_alloc.c (ffffffff812af55a)
Location: mm/page_alloc.c:2887
Inline: True
Inline callers:
  - mm/page_alloc.c:drain_local_pages_wq
  - mm/page_alloc.c:drain_pages
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
In mm/page_alloc.c (ffffffff812bb1aa)
Location: mm/page_alloc.c:2967
Inline: True
Inline callers:
  - mm/page_alloc.c:drain_local_pages_wq
  - mm/page_alloc.c:drain_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void drain_pages_zone(unsigned int cpu, struct zone *zone);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812c0130)
Location: mm/page_alloc.c:3016
Inline: False
Direct callers:
  - mm/page_alloc.c:page_alloc_cpu_dead
  - mm/page_alloc.c:drain_local_pages_wq
  - mm/page_alloc.c:drain_local_pages_wq
```
**Symbols:**

```
ffffffff812c0130-ffffffff812c0184: drain_pages_zone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void drain_pages_zone(unsigned int cpu, struct zone *zone);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81302d90)
Location: mm/page_alloc.c:3093
Inline: False
Direct callers:
  - mm/page_alloc.c:page_alloc_cpu_dead
  - mm/page_alloc.c:drain_local_pages_wq
  - mm/page_alloc.c:drain_local_pages_wq
```
**Symbols:**

```
ffffffff81302d90-ffffffff81302e3c: drain_pages_zone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void drain_pages_zone(unsigned int cpu, struct zone *zone);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81369ab0)
Location: mm/page_alloc.c:3115
Inline: False
Direct callers:
  - mm/page_alloc.c:page_alloc_cpu_dead
  - mm/page_alloc.c:drain_local_pages_wq
  - mm/page_alloc.c:drain_local_pages_wq
```
**Symbols:**

```
ffffffff81369ab0-ffffffff81369b3e: drain_pages_zone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void drain_pages_zone(unsigned int cpu, struct zone *zone);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff813e5b50)
Location: mm/page_alloc.c:3184
Inline: False
Direct callers:
  - mm/page_alloc.c:page_alloc_cpu_dead
  - mm/page_alloc.c:__drain_all_pages
  - mm/page_alloc.c:__drain_all_pages
  - mm/page_alloc.c:drain_local_pages
  - mm/page_alloc.c:drain_local_pages
```
**Symbols:**

```
ffffffff813e5b50-ffffffff813e5bda: drain_pages_zone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void drain_pages_zone(unsigned int cpu, struct zone *zone);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8141a880)
Location: mm/page_alloc.c:2218
Inline: False
Direct callers:
  - mm/page_alloc.c:page_alloc_cpu_dead
  - mm/page_alloc.c:__drain_all_pages
  - mm/page_alloc.c:__drain_all_pages
  - mm/page_alloc.c:drain_local_pages
  - mm/page_alloc.c:drain_local_pages
```
**Symbols:**

```
ffffffff8141a880-ffffffff8141a90a: drain_pages_zone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void drain_pages_zone(unsigned int cpu, struct zone *zone);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81447a80)
Location: mm/page_alloc.c:2216
Inline: False
Direct callers:
  - mm/page_alloc.c:page_alloc_cpu_dead
  - mm/page_alloc.c:__drain_all_pages
  - mm/page_alloc.c:__drain_all_pages
  - mm/page_alloc.c:drain_local_pages
  - mm/page_alloc.c:drain_local_pages
```
**Symbols:**

```
ffffffff81447a80-ffffffff81447b0a: drain_pages_zone (STB_LOCAL)
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
void drain_pages_zone(unsigned int cpu, struct zone *zone);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffff800010314c50)
Location: mm/page_alloc.c:2795
Inline: False
Direct callers:
  - mm/page_alloc.c:drain_local_pages
  - mm/page_alloc.c:drain_pages
```
**Symbols:**

```
ffff800010314c50-ffff800010314ce0: drain_pages_zone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void drain_pages_zone(unsigned int cpu, struct zone *zone);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c052f2c8)
Location: mm/page_alloc.c:2795
Inline: False
Direct callers:
  - mm/page_alloc.c:drain_local_pages
  - mm/page_alloc.c:drain_pages
```
**Symbols:**

```
c052f2c8-c052f320: drain_pages_zone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void drain_pages_zone(unsigned int cpu, struct zone *zone);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c0000000003e68e0)
Location: mm/page_alloc.c:2795
Inline: False
Direct callers:
  - mm/page_alloc.c:drain_local_pages
  - mm/page_alloc.c:drain_pages
```
**Symbols:**

```
c0000000003e68e0-c0000000003e6988: drain_pages_zone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void drain_pages_zone(unsigned int cpu, struct zone *zone);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffe00021b7a8)
Location: mm/page_alloc.c:2795
Inline: False
Direct callers:
  - mm/page_alloc.c:drain_local_pages
  - mm/page_alloc.c:drain_pages
```
**Symbols:**

```
ffffffe00021b7a8-ffffffe00021b806: drain_pages_zone (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void drain_pages_zone(unsigned int cpu, struct zone *zone);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81275a60)
Location: mm/page_alloc.c:2795
Inline: False
Direct callers:
  - mm/page_alloc.c:drain_local_pages
  - mm/page_alloc.c:drain_pages
```
**Symbols:**

```
ffffffff81275a60-ffffffff81275aa9: drain_pages_zone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void drain_pages_zone(unsigned int cpu, struct zone *zone);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812679c0)
Location: mm/page_alloc.c:2795
Inline: False
Direct callers:
  - mm/page_alloc.c:drain_local_pages
  - mm/page_alloc.c:drain_pages
```
**Symbols:**

```
ffffffff812679c0-ffffffff812679f3: drain_pages_zone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void drain_pages_zone(unsigned int cpu, struct zone *zone);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81273800)
Location: mm/page_alloc.c:2795
Inline: False
Direct callers:
  - mm/page_alloc.c:drain_local_pages
  - mm/page_alloc.c:drain_pages
```
**Symbols:**

```
ffffffff81273800-ffffffff81273849: drain_pages_zone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void drain_pages_zone(unsigned int cpu, struct zone *zone);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81283300)
Location: mm/page_alloc.c:2795
Inline: False
Direct callers:
  - mm/page_alloc.c:drain_local_pages
  - mm/page_alloc.c:drain_pages
```
**Symbols:**

```
ffffffff81283300-ffffffff81283349: drain_pages_zone (STB_LOCAL)
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
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
