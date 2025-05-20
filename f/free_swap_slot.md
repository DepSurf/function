# Function: <code>free_swap_slot</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int free_swap_slot(swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_slots.c (ffffffff811ec870)
Location: mm/swap_slots.c:272
Inline: False
Direct callers:
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:swap_free
```
**Symbols:**

```
ffffffff811ec870-ffffffff811ec956: free_swap_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int free_swap_slot(swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_slots.c (ffffffff81202be0)
Location: mm/swap_slots.c:280
Inline: False
Direct callers:
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:swap_free
```
**Symbols:**

```
ffffffff81202be0-ffffffff81202cbf: free_swap_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int free_swap_slot(swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_slots.c (ffffffff8124eb40)
Location: mm/swap_slots.c:278
Inline: False
Direct callers:
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:swap_free
```
**Symbols:**

```
ffffffff8124eb40-ffffffff8124ec2d: free_swap_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int free_swap_slot(swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_slots.c (ffffffff81263020)
Location: mm/swap_slots.c:278
Inline: False
Direct callers:
  - mm/swapfile.c:put_swap_page
```
**Symbols:**

```
ffffffff81263020-ffffffff8126310d: free_swap_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int free_swap_slot(swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_slots.c (ffffffff8127df90)
Location: mm/swap_slots.c:278
Inline: False
Direct callers:
  - mm/swapfile.c:put_swap_page
```
**Symbols:**

```
ffffffff8127df90-ffffffff8127e07d: free_swap_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int free_swap_slot(swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_slots.c (ffffffff8128d9e0)
Location: mm/swap_slots.c:278
Inline: False
Direct callers:
  - mm/swapfile.c:put_swap_page
```
**Symbols:**

```
ffffffff8128d9e0-ffffffff8128dacd: free_swap_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int free_swap_slot(swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_slots.c (ffffffff812c04a0)
Location: mm/swap_slots.c:278
Inline: False
Direct callers:
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:__swap_entry_free
```
**Symbols:**

```
ffffffff812c04a0-ffffffff812c058d: free_swap_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int free_swap_slot(swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_slots.c (ffffffff812cbee0)
Location: mm/swap_slots.c:274
Inline: False
Direct callers:
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:__swap_entry_free
```
**Symbols:**

```
ffffffff812cbee0-ffffffff812cbfb3: free_swap_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int free_swap_slot(swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_slots.c (ffffffff812d2a90)
Location: mm/swap_slots.c:273
Inline: False
Direct callers:
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:__swap_entry_free
```
**Symbols:**

```
ffffffff812d2a90-ffffffff812d2b63: free_swap_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int free_swap_slot(swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/swap_slots.c (0)
Location: mm/swap_slots.c:271
Inline: False
Direct callers:
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:__swap_entry_free
```
**Symbols:**

```
ffffffff81cbed48-ffffffff81cbed9c: free_swap_slot.cold (STB_LOCAL)
ffffffff81318410-ffffffff81318531: free_swap_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void free_swap_slot(swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/swap_slots.c (0)
Location: mm/swap_slots.c:272
Inline: False
Direct callers:
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:__swap_entry_free
```
**Symbols:**

```
ffffffff81e70f33-ffffffff81e70f87: free_swap_slot.cold (STB_LOCAL)
ffffffff81383ad0-ffffffff81383bf3: free_swap_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void free_swap_slot(swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/swap_slots.c (0)
Location: mm/swap_slots.c:272
Inline: False
Direct callers:
  - mm/swapfile.c:put_swap_folio
  - mm/swapfile.c:__swap_entry_free
```
**Symbols:**

```
ffffffff82065d3a-ffffffff82065d8e: free_swap_slot.cold (STB_LOCAL)
ffffffff81401590-ffffffff814016b3: free_swap_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void free_swap_slot(swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/swap_slots.c (0)
Location: mm/swap_slots.c:272
Inline: False
Direct callers:
  - mm/swapfile.c:put_swap_folio
  - mm/swapfile.c:__swap_entry_free
```
**Symbols:**

```
ffffffff820e5502-ffffffff820e5556: free_swap_slot.cold (STB_LOCAL)
ffffffff81434470-ffffffff81434593: free_swap_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void free_swap_slot(swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/swap_slots.c (0)
Location: mm/swap_slots.c:272
Inline: False
Direct callers:
  - mm/swapfile.c:swapcache_clear
  - mm/swapfile.c:put_swap_folio
  - mm/swapfile.c:__swap_entry_free
```
**Symbols:**

```
ffffffff821c26ab-ffffffff821c26ff: free_swap_slot.cold (STB_LOCAL)
ffffffff8146d870-ffffffff8146d993: free_swap_slot (STB_GLOBAL)
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
int free_swap_slot(swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_slots.c (ffff800010329c50)
Location: mm/swap_slots.c:278
Inline: False
Direct callers:
  - mm/swapfile.c:put_swap_page
```
**Symbols:**

```
ffff800010329c50-ffff800010329dac: free_swap_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int free_swap_slot(swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_slots.c (c0540540)
Location: mm/swap_slots.c:278
Inline: False
Direct callers:
  - mm/swapfile.c:put_swap_page
```
**Symbols:**

```
c0540540-c0540668: free_swap_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int free_swap_slot(swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_slots.c (c0000000004008a0)
Location: mm/swap_slots.c:278
Inline: False
Direct callers:
  - mm/swapfile.c:put_swap_page
```
**Symbols:**

```
c0000000004008a0-c000000000400a80: free_swap_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int free_swap_slot(swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_slots.c (ffffffe000228fa2)
Location: mm/swap_slots.c:278
Inline: False
Direct callers:
  - mm/swapfile.c:put_swap_page
```
**Symbols:**

```
ffffffe000228fa2-ffffffe0002290ee: free_swap_slot (STB_GLOBAL)
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
int free_swap_slot(swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_slots.c (ffffffff81285fc0)
Location: mm/swap_slots.c:278
Inline: False
Direct callers:
  - mm/swapfile.c:put_swap_page
```
**Symbols:**

```
ffffffff81285fc0-ffffffff812860ad: free_swap_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int free_swap_slot(swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_slots.c (ffffffff81277e30)
Location: mm/swap_slots.c:278
Inline: False
Direct callers:
  - mm/swapfile.c:put_swap_page
```
**Symbols:**

```
ffffffff81277e30-ffffffff81277f0d: free_swap_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int free_swap_slot(swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_slots.c (ffffffff81283dd0)
Location: mm/swap_slots.c:278
Inline: False
Direct callers:
  - mm/swapfile.c:put_swap_page
```
**Symbols:**

```
ffffffff81283dd0-ffffffff81283ebd: free_swap_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int free_swap_slot(swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_slots.c (ffffffff81293ac0)
Location: mm/swap_slots.c:278
Inline: False
Direct callers:
  - mm/swapfile.c:put_swap_page
```
**Symbols:**

```
ffffffff81293ac0-ffffffff81293b93: free_swap_slot (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
</details>
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
