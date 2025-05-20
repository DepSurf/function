# Function: <code>free_zbud_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void free_zbud_page(struct zbud_header *zhdr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zbud.c (ffffffff81204710)
Location: mm/zbud.c:250
Inline: False
Direct callers:
  - mm/zbud.c:zbud_free
  - mm/zbud.c:zbud_reclaim_page
```
**Symbols:**

```
ffffffff81204710-ffffffff81204754: free_zbud_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void free_zbud_page(struct zbud_header *zhdr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zbud.c (ffffffff812296a0)
Location: mm/zbud.c:250
Inline: False
Direct callers:
  - mm/zbud.c:zbud_reclaim_page
  - mm/zbud.c:zbud_free
```
**Symbols:**

```
ffffffff812296a0-ffffffff812296eb: free_zbud_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void free_zbud_page(struct zbud_header *zhdr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zbud.c (ffffffff8123bc40)
Location: mm/zbud.c:250
Inline: False
Direct callers:
  - mm/zbud.c:zbud_reclaim_page
  - mm/zbud.c:zbud_free
```
**Symbols:**

```
ffffffff8123bc40-ffffffff8123bc85: free_zbud_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void free_zbud_page(struct zbud_header *zhdr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zbud.c (ffffffff812478a0)
Location: mm/zbud.c:250
Inline: False
Direct callers:
  - mm/zbud.c:zbud_reclaim_page
  - mm/zbud.c:zbud_free
```
**Symbols:**

```
ffffffff812478a0-ffffffff812478e5: free_zbud_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void free_zbud_page(struct zbud_header *zhdr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zbud.c (ffffffff81267a50)
Location: mm/zbud.c:250
Inline: False
Direct callers:
  - mm/zbud.c:zbud_reclaim_page
  - mm/zbud.c:zbud_free
```
**Symbols:**

```
ffffffff81267a50-ffffffff81267a95: free_zbud_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void free_zbud_page(struct zbud_header *zhdr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zbud.c (ffffffff8128c3b0)
Location: mm/zbud.c:250
Inline: False
Direct callers:
  - mm/zbud.c:zbud_reclaim_page
  - mm/zbud.c:zbud_free
```
**Symbols:**

```
ffffffff8128c3b0-ffffffff8128c3f5: free_zbud_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void free_zbud_page(struct zbud_header *zhdr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zbud.c (ffffffff812a1320)
Location: mm/zbud.c:250
Inline: False
Direct callers:
  - mm/zbud.c:zbud_reclaim_page
  - mm/zbud.c:zbud_free
```
**Symbols:**

```
ffffffff812a1320-ffffffff812a1365: free_zbud_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void free_zbud_page(struct zbud_header *zhdr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zbud.c (ffffffff812bc5e0)
Location: mm/zbud.c:251
Inline: False
Direct callers:
  - mm/zbud.c:zbud_reclaim_page
  - mm/zbud.c:zbud_free
```
**Symbols:**

```
ffffffff812bc5e0-ffffffff812bc625: free_zbud_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void free_zbud_page(struct zbud_header *zhdr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zbud.c (ffffffff812ce4d0)
Location: mm/zbud.c:251
Inline: False
Direct callers:
  - mm/zbud.c:zbud_reclaim_page
  - mm/zbud.c:zbud_free
```
**Symbols:**

```
ffffffff812ce4d0-ffffffff812ce515: free_zbud_page (STB_LOCAL)
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
In mm/zbud.c (ffffffff81304e68)
Location: mm/zbud.c:251
Inline: True
Inline callers:
  - mm/zbud.c:zbud_reclaim_page
  - mm/zbud.c:zbud_free
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
In mm/zbud.c (ffffffff81310bc8)
Location: mm/zbud.c:251
Inline: True
Inline callers:
  - mm/zbud.c:zbud_reclaim_page
  - mm/zbud.c:zbud_free
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
In mm/zbud.c (ffffffff81316c98)
Location: mm/zbud.c:252
Inline: True
Inline callers:
  - mm/zbud.c:zbud_reclaim_page
  - mm/zbud.c:zbud_free
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
In mm/zbud.c (ffffffff81362fe1)
Location: mm/zbud.c:165
Inline: True
Inline callers:
  - mm/zbud.c:zbud_zpool_free
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
In mm/zbud.c (ffffffff813dfb9d)
Location: mm/zbud.c:165
Inline: True
Inline callers:
  - mm/zbud.c:zbud_zpool_free
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
In mm/zbud.c (ffffffff814664fd)
Location: mm/zbud.c:158
Inline: True
Inline callers:
  - mm/zbud.c:zbud_zpool_free
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
In mm/zbud.c (ffffffff8149be34)
Location: mm/zbud.c:146
Inline: True
Inline callers:
  - mm/zbud.c:zbud_zpool_free
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
In mm/zbud.c (ffffffff814cb534)
Location: mm/zbud.c:146
Inline: True
Inline callers:
  - mm/zbud.c:zbud_zpool_free
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
In mm/zbud.c (ffff800010373628)
Location: mm/zbud.c:251
Inline: True
Inline callers:
  - mm/zbud.c:zbud_reclaim_page
  - mm/zbud.c:zbud_free
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
In mm/zbud.c (c055fd64)
Location: mm/zbud.c:251
Inline: True
Inline callers:
  - mm/zbud.c:zbud_reclaim_page
  - mm/zbud.c:zbud_free
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
In mm/zbud.c (c000000000465400)
Location: mm/zbud.c:251
Inline: True
Inline callers:
  - mm/zbud.c:zbud_reclaim_page
  - mm/zbud.c:zbud_free
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
In mm/zbud.c (ffffffe00024c44e)
Location: mm/zbud.c:251
Inline: True
Inline callers:
  - mm/zbud.c:zbud_reclaim_page
  - mm/zbud.c:zbud_free
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
void free_zbud_page(struct zbud_header *zhdr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zbud.c (ffffffff812c6ab0)
Location: mm/zbud.c:251
Inline: False
Direct callers:
  - mm/zbud.c:zbud_reclaim_page
  - mm/zbud.c:zbud_free
```
**Symbols:**

```
ffffffff812c6ab0-ffffffff812c6af5: free_zbud_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void free_zbud_page(struct zbud_header *zhdr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zbud.c (ffffffff812b7af0)
Location: mm/zbud.c:251
Inline: False
Direct callers:
  - mm/zbud.c:zbud_reclaim_page
  - mm/zbud.c:zbud_free
```
**Symbols:**

```
ffffffff812b7af0-ffffffff812b7b35: free_zbud_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void free_zbud_page(struct zbud_header *zhdr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zbud.c (ffffffff812c48c0)
Location: mm/zbud.c:251
Inline: False
Direct callers:
  - mm/zbud.c:zbud_reclaim_page
  - mm/zbud.c:zbud_free
```
**Symbols:**

```
ffffffff812c48c0-ffffffff812c4905: free_zbud_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void free_zbud_page(struct zbud_header *zhdr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zbud.c (ffffffff812d5350)
Location: mm/zbud.c:251
Inline: False
Direct callers:
  - mm/zbud.c:zbud_reclaim_page
  - mm/zbud.c:zbud_free
```
**Symbols:**

```
ffffffff812d5350-ffffffff812d5395: free_zbud_page (STB_LOCAL)
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
</ul>
<b>Arch</b>
<ul>
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
