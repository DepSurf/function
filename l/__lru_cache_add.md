# Function: <code>__lru_cache_add</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __lru_cache_add(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff8119dc50)
Location: mm/swap.c:631
Inline: False
Direct callers:
  - mm/swap.c:lru_cache_add_file
  - mm/swap.c:lru_cache_add_active_or_unevictable
```
**Symbols:**

```
ffffffff8119dc50-ffffffff8119dcb4: __lru_cache_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __lru_cache_add(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff811b2ea0)
Location: mm/swap.c:391
Inline: False
Direct callers:
  - mm/swap.c:lru_cache_add_active_or_unevictable
  - mm/swap.c:lru_cache_add_file
```
**Symbols:**

```
ffffffff811b2ea0-ffffffff811b2f27: __lru_cache_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __lru_cache_add(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff811c3510)
Location: mm/swap.c:392
Inline: False
Direct callers:
  - mm/swap.c:lru_cache_add_active_or_unevictable
  - mm/swap.c:lru_cache_add_file
```
**Symbols:**

```
ffffffff811c3510-ffffffff811c3597: __lru_cache_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __lru_cache_add(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff811cb980)
Location: mm/swap.c:403
Inline: False
Direct callers:
  - mm/swap.c:lru_cache_add_active_or_unevictable
  - mm/swap.c:lru_cache_add_anon
```
**Symbols:**

```
ffffffff811cb980-ffffffff811cb9e4: __lru_cache_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __lru_cache_add(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff811e0d70)
Location: mm/swap.c:403
Inline: False
Direct callers:
  - mm/swap.c:lru_cache_add_active_or_unevictable
  - mm/swap.c:lru_cache_add_anon
```
**Symbols:**

```
ffffffff811e0d70-ffffffff811e0dd5: __lru_cache_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __lru_cache_add(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81202600)
Location: mm/swap.c:404
Inline: False
Direct callers:
  - mm/swap.c:lru_cache_add_active_or_unevictable
  - mm/swap.c:lru_cache_add_anon
```
**Symbols:**

```
ffffffff81202600-ffffffff81202663: __lru_cache_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __lru_cache_add(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81214f80)
Location: mm/swap.c:398
Inline: False
Direct callers:
  - mm/swap.c:lru_cache_add_active_or_unevictable
  - mm/swap.c:lru_cache_add_anon
```
**Symbols:**

```
ffffffff81214f80-ffffffff81214fe6: __lru_cache_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __lru_cache_add(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81224230)
Location: mm/swap.c:399
Inline: False
Direct callers:
  - mm/swap.c:lru_cache_add_active_or_unevictable
  - mm/swap.c:lru_cache_add_file
  - mm/swap.c:lru_cache_add_anon
```
**Symbols:**

```
ffffffff81224230-ffffffff81224295: __lru_cache_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __lru_cache_add(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81231fc0)
Location: mm/swap.c:400
Inline: False
Direct callers:
  - mm/swap.c:lru_cache_add_active_or_unevictable
  - mm/swap.c:lru_cache_add_file
  - mm/swap.c:lru_cache_add_anon
```
**Symbols:**

```
ffffffff81231fc0-ffffffff81232025: __lru_cache_add (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void __lru_cache_add(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffff8000102c1d88)
Location: mm/swap.c:400
Inline: False
Direct callers:
  - mm/swap.c:lru_cache_add_active_or_unevictable
  - mm/swap.c:lru_cache_add_anon
  - mm/swap.c:lru_cache_add_anon
```
**Symbols:**

```
ffff8000102c1d88-ffff8000102c1e54: __lru_cache_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __lru_cache_add(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (c04ecf68)
Location: mm/swap.c:400
Inline: False
Direct callers:
  - mm/swap.c:lru_cache_add_active_or_unevictable
  - mm/swap.c:lru_cache_add_anon
```
**Symbols:**

```
c04ecf68-c04ed00c: __lru_cache_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __lru_cache_add(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (c00000000037bc60)
Location: mm/swap.c:400
Inline: False
Direct callers:
  - mm/swap.c:lru_cache_add_active_or_unevictable
  - mm/swap.c:lru_cache_add_file
  - mm/swap.c:lru_cache_add_anon
```
**Symbols:**

```
c00000000037bc60-c00000000037bd28: __lru_cache_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __lru_cache_add(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffe0001e30a4)
Location: mm/swap.c:400
Inline: False
Direct callers:
  - mm/swap.c:lru_cache_add_active_or_unevictable
  - mm/swap.c:lru_cache_add_anon
```
**Symbols:**

```
ffffffe0001e30a4-ffffffe0001e3144: __lru_cache_add (STB_LOCAL)
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
void __lru_cache_add(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff8122a610)
Location: mm/swap.c:400
Inline: False
Direct callers:
  - mm/swap.c:lru_cache_add_active_or_unevictable
  - mm/swap.c:lru_cache_add_file
  - mm/swap.c:lru_cache_add_anon
```
**Symbols:**

```
ffffffff8122a610-ffffffff8122a675: __lru_cache_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __lru_cache_add(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff8121d730)
Location: mm/swap.c:400
Inline: False
Direct callers:
  - mm/swap.c:lru_cache_add_active_or_unevictable
  - mm/swap.c:lru_cache_add_file
  - mm/swap.c:lru_cache_add_anon
```
**Symbols:**

```
ffffffff8121d730-ffffffff8121d795: __lru_cache_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __lru_cache_add(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff812283b0)
Location: mm/swap.c:400
Inline: False
Direct callers:
  - mm/swap.c:lru_cache_add_active_or_unevictable
  - mm/swap.c:lru_cache_add_file
  - mm/swap.c:lru_cache_add_anon
```
**Symbols:**

```
ffffffff812283b0-ffffffff81228415: __lru_cache_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __lru_cache_add(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff812376f0)
Location: mm/swap.c:400
Inline: False
Direct callers:
  - mm/swap.c:lru_cache_add_active_or_unevictable
  - mm/swap.c:lru_cache_add_file
  - mm/swap.c:lru_cache_add_anon
```
**Symbols:**

```
ffffffff812376f0-ffffffff8123776d: __lru_cache_add (STB_LOCAL)
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
