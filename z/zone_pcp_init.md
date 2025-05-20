# Function: <code>zone_pcp_init</code>

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
In mm/page_alloc.c (ffffffff8181d6d6)
Location: mm/page_alloc.c:4732
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_node
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
In mm/page_alloc.c (ffffffff818979cd)
Location: mm/page_alloc.c:5273
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_node
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
In mm/page_alloc.c (ffffffff818cc120)
Location: mm/page_alloc.c:5313
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_node
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
In mm/page_alloc.c (ffffffff819035f0)
Location: mm/page_alloc.c:5612
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_node
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
In mm/page_alloc.c (ffffffff8198d500)
Location: mm/page_alloc.c:5584
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_node
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
In mm/page_alloc.c (ffffffff819e9e94)
Location: mm/page_alloc.c:5722
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_node
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void zone_pcp_init(struct zone *zone);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81a24e12)
Location: mm/page_alloc.c:5966
Inline: False
Direct callers:
  - mm/page_alloc.c:free_area_init_node
  - mm/page_alloc.c:free_area_init_core_hotplug
```
**Symbols:**

```
ffffffff81a24e12-ffffffff81a24e51: zone_pcp_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void zone_pcp_init(struct zone *zone);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81a95249)
Location: mm/page_alloc.c:6152
Inline: False
Direct callers:
  - mm/page_alloc.c:free_area_init_node
  - mm/page_alloc.c:free_area_init_core_hotplug
```
**Symbols:**

```
ffffffff81a95249-ffffffff81a95288: zone_pcp_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void zone_pcp_init(struct zone *zone);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81accb2c)
Location: mm/page_alloc.c:6170
Inline: False
Direct callers:
  - mm/page_alloc.c:free_area_init_node
  - mm/page_alloc.c:free_area_init_core_hotplug
```
**Symbols:**

```
ffffffff81accb2c-ffffffff81accb6b: zone_pcp_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void zone_pcp_init(struct zone *zone);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81bc5490)
Location: mm/page_alloc.c:6282
Inline: False
Direct callers:
  - mm/page_alloc.c:free_area_init_core
  - mm/page_alloc.c:free_area_init_core_hotplug
```
**Symbols:**

```
ffffffff81bc5490-ffffffff81bc54cf: zone_pcp_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void zone_pcp_init(struct zone *zone);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81c3e316)
Location: mm/page_alloc.c:6527
Inline: False
Direct callers:
  - mm/page_alloc.c:free_area_init_core
  - mm/page_alloc.c:free_area_init_core_hotplug
```
**Symbols:**

```
ffffffff81c3e316-ffffffff81c3e362: zone_pcp_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void zone_pcp_init(struct zone *zone);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81c30622)
Location: mm/page_alloc.c:6748
Inline: False
Direct callers:
  - mm/page_alloc.c:free_area_init_node
  - mm/page_alloc.c:free_area_init_core_hotplug
```
**Symbols:**

```
ffffffff81c30622-ffffffff81c3066f: zone_pcp_init (STB_LOCAL)
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
In mm/page_alloc.c (ffffffff81d4ee65)
Location: mm/page_alloc.c:6990
Inline: True
Inline callers:
  - mm/page_alloc.c:zone_init_internals
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
In mm/page_alloc.c (ffffffff81f1ed1b)
Location: mm/page_alloc.c:7111
Inline: True
Inline callers:
  - mm/page_alloc.c:zone_init_internals
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void zone_pcp_init(struct zone *zone);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff820c7c40)
Location: mm/page_alloc.c:7295
Inline: False
Direct callers:
  - mm/page_alloc.c:free_area_init_core
  - mm/page_alloc.c:free_area_init_core_hotplug
```
**Symbols:**

```
ffffffff820c7c40-ffffffff820c7d20: zone_pcp_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void zone_pcp_init(struct zone *zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8214c6c0)
Location: mm/page_alloc.c:5501
Inline: False
Direct callers:
  - mm/mm_init.c:free_area_init_core
  - mm/mm_init.c:free_area_init_core_hotplug
```
**Symbols:**

```
ffffffff8214c6c0-ffffffff8214c7b6: zone_pcp_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void zone_pcp_init(struct zone *zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8222f240)
Location: mm/page_alloc.c:5642
Inline: False
Direct callers:
  - mm/mm_init.c:free_area_init_core
  - mm/mm_init.c:free_area_init_core_hotplug
```
**Symbols:**

```
ffffffff8222f240-ffffffff8222f2cb: zone_pcp_init (STB_GLOBAL)
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
void zone_pcp_init(struct zone *zone);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffff800010d9fa7c)
Location: mm/page_alloc.c:6170
Inline: False
Direct callers:
  - mm/page_alloc.c:free_area_init_node
  - mm/page_alloc.c:free_area_init_core_hotplug
```
**Symbols:**

```
ffff800010d9fa7c-ffff800010d9fac8: zone_pcp_init (STB_LOCAL)
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
In mm/page_alloc.c (c1531be4)
Location: mm/page_alloc.c:6170
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_node
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
In mm/page_alloc.c (c000000000eec450)
Location: mm/page_alloc.c:6170
Inline: True
Inline callers:
  - mm/page_alloc.c:zone_init_internals
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
In mm/page_alloc.c (ffffffe0000161a4)
Location: mm/page_alloc.c:6170
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_node
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
void zone_pcp_init(struct zone *zone);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81a6b99c)
Location: mm/page_alloc.c:6170
Inline: False
Direct callers:
  - mm/page_alloc.c:free_area_init_node
  - mm/page_alloc.c:free_area_init_core_hotplug
```
**Symbols:**

```
ffffffff81a6b99c-ffffffff81a6b9db: zone_pcp_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void zone_pcp_init(struct zone *zone);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81a27ee3)
Location: mm/page_alloc.c:6170
Inline: False
Direct callers:
  - mm/page_alloc.c:free_area_init_node
  - mm/page_alloc.c:free_area_init_core_hotplug
```
**Symbols:**

```
ffffffff81a27ee3-ffffffff81a27f22: zone_pcp_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void zone_pcp_init(struct zone *zone);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81ad7dac)
Location: mm/page_alloc.c:6170
Inline: False
Direct callers:
  - mm/page_alloc.c:free_area_init_node
  - mm/page_alloc.c:free_area_init_core_hotplug
```
**Symbols:**

```
ffffffff81ad7dac-ffffffff81ad7deb: zone_pcp_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void zone_pcp_init(struct zone *zone);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81ae426c)
Location: mm/page_alloc.c:6170
Inline: False
Direct callers:
  - mm/page_alloc.c:free_area_init_node
  - mm/page_alloc.c:free_area_init_core_hotplug
```
**Symbols:**

```
ffffffff81ae426c-ffffffff81ae42ab: zone_pcp_init (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
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
