# Function: <code>putback_movable_page</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void putback_movable_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff81211350)
Location: mm/migrate.c:139
Inline: False
Direct callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:putback_movable_pages
```
**Symbols:**

```
ffffffff81211350-ffffffff81211373: putback_movable_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void putback_movable_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff81223510)
Location: mm/migrate.c:139
Inline: False
Direct callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:putback_movable_pages
```
**Symbols:**

```
ffffffff81223510-ffffffff81223533: putback_movable_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void putback_movable_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff8122eee0)
Location: mm/migrate.c:141
Inline: False
Direct callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:putback_movable_pages
```
**Symbols:**

```
ffffffff8122eee0-ffffffff8122ef03: putback_movable_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void putback_movable_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff8124bbc0)
Location: mm/migrate.c:145
Inline: False
Direct callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:putback_movable_pages
```
**Symbols:**

```
ffffffff8124bbc0-ffffffff8124bbe9: putback_movable_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void putback_movable_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff8126f690)
Location: mm/migrate.c:146
Inline: False
Direct callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:putback_movable_pages
```
**Symbols:**

```
ffffffff8126f690-ffffffff8126f6ba: putback_movable_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void putback_movable_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff81283d20)
Location: mm/migrate.c:146
Inline: False
Direct callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:putback_movable_pages
```
**Symbols:**

```
ffffffff81283d20-ffffffff81283d4a: putback_movable_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void putback_movable_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff8129eee0)
Location: mm/migrate.c:146
Inline: False
Direct callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:putback_movable_pages
```
**Symbols:**

```
ffffffff8129eee0-ffffffff8129ef0a: putback_movable_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void putback_movable_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812af8d0)
Location: mm/migrate.c:147
Inline: False
Direct callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:putback_movable_pages
```
**Symbols:**

```
ffffffff812af8d0-ffffffff812af8fa: putback_movable_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void putback_movable_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812e6809)
Location: mm/migrate.c:148
Inline: True
Inline callers:
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:putback_movable_pages
```
**Symbols:**

```
ffffffff812e5960-ffffffff812e598d: putback_movable_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void putback_movable_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812f0eb7)
Location: mm/migrate.c:144
Inline: True
Inline callers:
  - mm/migrate.c:putback_movable_pages
```
**Symbols:**

```
ffffffff812f0d20-ffffffff812f0d4d: putback_movable_page (STB_GLOBAL)
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
In mm/migrate.c (ffffffff812f71b7)
Location: mm/migrate.c:121
Inline: True
Inline callers:
  - mm/migrate.c:putback_movable_pages
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
In mm/migrate.c (ffffffff81341814)
Location: mm/migrate.c:122
Inline: True
Inline callers:
  - mm/migrate.c:putback_movable_pages
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
In mm/migrate.c (ffffffff813b33d6)
Location: mm/migrate.c:121
Inline: True
Inline callers:
  - mm/migrate.c:putback_movable_pages
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
In mm/migrate.c (ffffffff814338f6)
Location: mm/migrate.c:131
Inline: True
Inline callers:
  - mm/migrate.c:putback_movable_pages
```
</details>
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
void putback_movable_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffff800010350768)
Location: mm/migrate.c:147
Inline: False
Direct callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:putback_movable_pages
```
**Symbols:**

```
ffff800010350768-ffff8000103507b4: putback_movable_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void putback_movable_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (c0551e8c)
Location: mm/migrate.c:147
Inline: False
Direct callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:putback_movable_pages
```
**Symbols:**

```
c0551e8c-c0551ecc: putback_movable_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void putback_movable_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (c000000000435570)
Location: mm/migrate.c:147
Inline: False
Direct callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:putback_movable_pages
```
**Symbols:**

```
c000000000435570-c0000000004355dc: putback_movable_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void putback_movable_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffe00023f2ac)
Location: mm/migrate.c:147
Inline: False
Direct callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:putback_movable_pages
```
**Symbols:**

```
ffffffe00023f2ac-ffffffe00023f2ea: putback_movable_page (STB_GLOBAL)
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
void putback_movable_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812a7eb0)
Location: mm/migrate.c:147
Inline: False
Direct callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:putback_movable_pages
```
**Symbols:**

```
ffffffff812a7eb0-ffffffff812a7eda: putback_movable_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void putback_movable_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff81299870)
Location: mm/migrate.c:147
Inline: False
Direct callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:putback_movable_pages
```
**Symbols:**

```
ffffffff81299870-ffffffff8129989a: putback_movable_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void putback_movable_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812a5cc0)
Location: mm/migrate.c:147
Inline: False
Direct callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:putback_movable_pages
```
**Symbols:**

```
ffffffff812a5cc0-ffffffff812a5cea: putback_movable_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void putback_movable_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812b6010)
Location: mm/migrate.c:147
Inline: False
Direct callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:putback_movable_pages
```
**Symbols:**

```
ffffffff812b6010-ffffffff812b603a: putback_movable_page (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
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
