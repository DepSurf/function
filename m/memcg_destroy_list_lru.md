# Function: <code>memcg_destroy_list_lru</code>

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
In mm/list_lru.c (ffffffff811b943b)
Location: mm/list_lru.c:411
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_destroy
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
In mm/list_lru.c (ffffffff811d373b)
Location: mm/list_lru.c:411
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_destroy
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
In mm/list_lru.c (ffffffff811e35eb)
Location: mm/list_lru.c:411
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_destroy
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
In mm/list_lru.c (ffffffff811eda22)
Location: mm/list_lru.c:409
Inline: True
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
In mm/list_lru.c (ffffffff81203e7f)
Location: mm/list_lru.c:410
Inline: True
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
In mm/list_lru.c (ffffffff81224a0f)
Location: mm/list_lru.c:433
Inline: True
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
In mm/list_lru.c (ffffffff8123796f)
Location: mm/list_lru.c:471
Inline: True
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
In mm/list_lru.c (ffffffff81248eed)
Location: mm/list_lru.c:471
Inline: True
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
In mm/list_lru.c (ffffffff8125733d)
Location: mm/list_lru.c:471
Inline: True
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
In mm/list_lru.c (ffffffff81285c41)
Location: mm/list_lru.c:461
Inline: True
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
In mm/list_lru.c (ffffffff8128ff01)
Location: mm/list_lru.c:461
Inline: True
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
In mm/list_lru.c (ffffffff81295301)
Location: mm/list_lru.c:453
Inline: True
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
In mm/list_lru.c (ffffffff812d5bb1)
Location: mm/list_lru.c:453
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void memcg_destroy_list_lru(struct list_lru *lru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/list_lru.c (0)
Location: mm/list_lru.c:374
Inline: False
```
**Symbols:**

```
ffffffff81334b30-ffffffff81334c97: memcg_destroy_list_lru (STB_LOCAL)
ffffffff81e6d8a6-ffffffff81e6d8ba: memcg_destroy_list_lru.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void memcg_destroy_list_lru(struct list_lru *lru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/list_lru.c (0)
Location: mm/list_lru.c:374
Inline: False
```
**Symbols:**

```
ffffffff813ab920-ffffffff813aba87: memcg_destroy_list_lru (STB_LOCAL)
ffffffff82063bc1-ffffffff82063bd5: memcg_destroy_list_lru.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void memcg_destroy_list_lru(struct list_lru *lru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/list_lru.c (0)
Location: mm/list_lru.c:374
Inline: False
```
**Symbols:**

```
ffffffff813dfcb0-ffffffff813dfe18: memcg_destroy_list_lru (STB_LOCAL)
ffffffff820e32b8-ffffffff820e32cc: memcg_destroy_list_lru.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void memcg_destroy_list_lru(struct list_lru *lru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/list_lru.c (0)
Location: mm/list_lru.c:375
Inline: False
```
**Symbols:**

```
ffffffff8140a420-ffffffff8140a588: memcg_destroy_list_lru (STB_LOCAL)
ffffffff821bfd05-ffffffff821bfd19: memcg_destroy_list_lru.cold (STB_LOCAL)
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
In mm/list_lru.c (ffff8000102eedd4)
Location: mm/list_lru.c:471
Inline: True
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
In mm/list_lru.c (c0512d70)
Location: mm/list_lru.c:471
Inline: True
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
In mm/list_lru.c (c0000000003b33cc)
Location: mm/list_lru.c:471
Inline: True
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
In mm/list_lru.c (ffffffe000202d12)
Location: mm/list_lru.c:471
Inline: True
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
In mm/list_lru.c (ffffffff8124f98d)
Location: mm/list_lru.c:471
Inline: True
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
In mm/list_lru.c (ffffffff8124292d)
Location: mm/list_lru.c:471
Inline: True
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
In mm/list_lru.c (ffffffff8124d72d)
Location: mm/list_lru.c:471
Inline: True
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
In mm/list_lru.c (ffffffff8125d3ed)
Location: mm/list_lru.c:471
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
