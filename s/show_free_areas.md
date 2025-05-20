# Function: <code>show_free_areas</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void show_free_areas(unsigned int filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811931c0)
Location: mm/page_alloc.c:3682
Inline: False
Direct callers:
  - lib/show_mem.c:show_mem
```
**Symbols:**

```
ffffffff811931c0-ffffffff81193b0d: show_free_areas (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void show_free_areas(unsigned int filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811ab5a0)
Location: mm/page_alloc.c:4153
Inline: False
Direct callers:
  - lib/show_mem.c:show_mem
```
**Symbols:**

```
ffffffff811ab5a0-ffffffff811abfc4: show_free_areas (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void show_free_areas(unsigned int filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811bbb80)
Location: mm/page_alloc.c:4309
Inline: False
Direct callers:
  - lib/show_mem.c:show_mem
```
**Symbols:**

```
ffffffff811bbb80-ffffffff811bc5af: show_free_areas (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void show_free_areas(unsigned int filter, nodemask_t *nodemask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811c3e00)
Location: mm/page_alloc.c:4598
Inline: False
Direct callers:
  - lib/show_mem.c:show_mem
```
**Symbols:**

```
ffffffff811c3e00-ffffffff811c4770: show_free_areas (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void show_free_areas(unsigned int filter, nodemask_t *nodemask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811d8c20)
Location: mm/page_alloc.c:4717
Inline: False
Direct callers:
  - lib/show_mem.c:show_mem
```
**Symbols:**

```
ffffffff811d8c20-ffffffff811d9574: show_free_areas (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void show_free_areas(unsigned int filter, nodemask_t *nodemask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:4856
Inline: False
Direct callers:
  - lib/show_mem.c:show_mem
```
**Symbols:**

```
ffffffff811fae46-ffffffff811fb699: show_free_areas.cold.116 (STB_LOCAL)
ffffffff811f9de0-ffffffff811f9eb3: show_free_areas (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void show_free_areas(unsigned int filter, nodemask_t *nodemask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:5022
Inline: False
Direct callers:
  - lib/show_mem.c:show_mem
```
**Symbols:**

```
ffffffff8120d6ef-ffffffff8120df72: show_free_areas.cold.120 (STB_LOCAL)
ffffffff8120c490-ffffffff8120c566: show_free_areas (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void show_free_areas(unsigned int filter, nodemask_t *nodemask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:5208
Inline: False
Direct callers:
  - lib/show_mem.c:show_mem
```
**Symbols:**

```
ffffffff81273ba6-ffffffff81274434: show_free_areas.cold (STB_LOCAL)
ffffffff812726f0-ffffffff812727a9: show_free_areas (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void show_free_areas(unsigned int filter, nodemask_t *nodemask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:5226
Inline: False
Direct callers:
  - lib/show_mem.c:show_mem
```
**Symbols:**

```
ffffffff812829c1-ffffffff8128324b: show_free_areas.cold (STB_LOCAL)
ffffffff81281550-ffffffff81281609: show_free_areas (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void show_free_areas(unsigned int filter, nodemask_t *nodemask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:5329
Inline: False
Direct callers:
  - lib/show_mem.c:show_mem
```
**Symbols:**

```
ffffffff812b4a63-ffffffff812b52f0: show_free_areas.cold (STB_LOCAL)
ffffffff812b3a30-ffffffff812b3af2: show_free_areas (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void show_free_areas(unsigned int filter, nodemask_t *nodemask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:5495
Inline: False
Direct callers:
  - lib/show_mem.c:show_mem
```
**Symbols:**

```
ffffffff81be7d83-ffffffff81be8624: show_free_areas.cold (STB_LOCAL)
ffffffff812bf500-ffffffff812bf5c2: show_free_areas (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void show_free_areas(unsigned int filter, nodemask_t *nodemask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:5698
Inline: False
Direct callers:
  - lib/show_mem.c:show_mem
```
**Symbols:**

```
ffffffff81bd9b7a-ffffffff81bda427: show_free_areas.cold (STB_LOCAL)
ffffffff812c4b80-ffffffff812c4c50: show_free_areas (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void show_free_areas(unsigned int filter, nodemask_t *nodemask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:5879
Inline: False
Direct callers:
  - lib/show_mem.c:show_mem
```
**Symbols:**

```
ffffffff81cbda33-ffffffff81cbe484: show_free_areas.cold (STB_LOCAL)
ffffffff81308bc0-ffffffff81308ce8: show_free_areas (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void show_free_areas(unsigned int filter, nodemask_t *nodemask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:5934
Inline: False
Direct callers:
  - lib/show_mem.c:show_mem
```
**Symbols:**

```
ffffffff81e6f8ee-ffffffff81e703c7: show_free_areas.cold (STB_LOCAL)
ffffffff81371070-ffffffff81371191: show_free_areas (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void show_free_areas(unsigned int filter, nodemask_t *nodemask, int max_zone_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/show_mem.c (ffffffff814079e0)
Location: mm/show_mem.c:186
Inline: False
Direct callers:
  - mm/show_mem.c:__show_mem
```
**Symbols:**

```
ffffffff814079e0-ffffffff81408957: show_free_areas (STB_LOCAL)
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
void show_free_areas(unsigned int filter, nodemask_t *nodemask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffff800010319230)
Location: mm/page_alloc.c:5226
Inline: False
Direct callers:
  - lib/show_mem.c:show_mem
```
**Symbols:**

```
ffff800010319230-ffff800010319a98: show_free_areas (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void show_free_areas(unsigned int filter, nodemask_t *nodemask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c0533c98)
Location: mm/page_alloc.c:5226
Inline: False
Direct callers:
  - lib/show_mem.c:show_mem
```
**Symbols:**

```
c0533c98-c0534454: show_free_areas (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void show_free_areas(unsigned int filter, nodemask_t *nodemask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c0000000003ebc90)
Location: mm/page_alloc.c:5226
Inline: False
Direct callers:
  - lib/show_mem.c:show_mem
```
**Symbols:**

```
c0000000003ebc90-c0000000003ec798: show_free_areas (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void show_free_areas(unsigned int filter, nodemask_t *nodemask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffe00021ef6c)
Location: mm/page_alloc.c:5226
Inline: False
Direct callers:
  - lib/show_mem.c:show_mem
```
**Symbols:**

```
ffffffe00021ef6c-ffffffe00021f62e: show_free_areas (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void show_free_areas(unsigned int filter, nodemask_t *nodemask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:5226
Inline: False
Direct callers:
  - lib/show_mem.c:show_mem
```
**Symbols:**

```
ffffffff8127b011-ffffffff8127b89b: show_free_areas.cold (STB_LOCAL)
ffffffff81279ba0-ffffffff81279c59: show_free_areas (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void show_free_areas(unsigned int filter, nodemask_t *nodemask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:5226
Inline: False
Direct callers:
  - lib/show_mem.c:show_mem
```
**Symbols:**

```
ffffffff8126cef1-ffffffff8126d77b: show_free_areas.cold (STB_LOCAL)
ffffffff8126ba90-ffffffff8126bb49: show_free_areas (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void show_free_areas(unsigned int filter, nodemask_t *nodemask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:5226
Inline: False
Direct callers:
  - lib/show_mem.c:show_mem
```
**Symbols:**

```
ffffffff81278db1-ffffffff8127963b: show_free_areas.cold (STB_LOCAL)
ffffffff81277940-ffffffff812779f9: show_free_areas (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void show_free_areas(unsigned int filter, nodemask_t *nodemask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:5226
Inline: False
Direct callers:
  - lib/show_mem.c:show_mem
```
**Symbols:**

```
ffffffff812889a1-ffffffff8128922b: show_free_areas.cold (STB_LOCAL)
ffffffff81287530-ffffffff812875e9: show_free_areas (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>nodemask_t *nodemask</code>
</li>
</ul>
</details>
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
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
