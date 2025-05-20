# Function: <code>pageout</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/vmscan.c (ffffffff811a0930)
Location: mm/vmscan.c:534
Inline: True
Direct callers:
  - mm/vmscan.c:shrink_page_list
```
**Symbols:**

```
ffffffff811a0930-ffffffff811a0ba9: pageout.isra.44 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/vmscan.c (ffffffff811b6d30)
Location: mm/vmscan.c:553
Inline: True
Direct callers:
  - mm/vmscan.c:shrink_page_list
```
**Symbols:**

```
ffffffff811b6d30-ffffffff811b6fcd: pageout.isra.41 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/vmscan.c (ffffffff811c7330)
Location: mm/vmscan.c:588
Inline: True
Direct callers:
  - mm/vmscan.c:shrink_page_list
```
**Symbols:**

```
ffffffff811c7330-ffffffff811c75cd: pageout.isra.43 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/vmscan.c (ffffffff811cfa80)
Location: mm/vmscan.c:589
Inline: True
Direct callers:
  - mm/vmscan.c:shrink_page_list
```
**Symbols:**

```
ffffffff811cfa80-ffffffff811cfd50: pageout.isra.51 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/vmscan.c (ffffffff811e4eb0)
Location: mm/vmscan.c:596
Inline: True
Direct callers:
  - mm/vmscan.c:shrink_page_list
```
**Symbols:**

```
ffffffff811e4eb0-ffffffff811e51f9: pageout.isra.54 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/vmscan.c (ffffffff812065f0)
Location: mm/vmscan.c:631
Inline: True
Direct callers:
  - mm/vmscan.c:shrink_page_list
```
**Symbols:**

```
ffffffff812065f0-ffffffff8120692b: pageout.isra.48 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/vmscan.c (ffffffff812191b0)
Location: mm/vmscan.c:804
Inline: True
Direct callers:
  - mm/vmscan.c:shrink_page_list
```
**Symbols:**

```
ffffffff812191b0-ffffffff812194ed: pageout.isra.50 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/vmscan.c (ffffffff812289a0)
Location: mm/vmscan.c:823
Inline: True
Direct callers:
  - mm/vmscan.c:shrink_page_list
```
**Symbols:**

```
ffffffff812289a0-ffffffff81228ce6: pageout.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/vmscan.c (ffffffff81236840)
Location: mm/vmscan.c:826
Inline: True
Direct callers:
  - mm/vmscan.c:shrink_page_list
```
**Symbols:**

```
ffffffff81236840-ffffffff81236b86: pageout.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
pageout_t pageout(struct page *page, struct address_space *mapping);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81265af0)
Location: mm/vmscan.c:783
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_page_list
```
**Symbols:**

```
ffffffff81265af0-ffffffff81265e5c: pageout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
pageout_t pageout(struct page *page, struct address_space *mapping);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff812704e0)
Location: mm/vmscan.c:778
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_page_list
```
**Symbols:**

```
ffffffff812704e0-ffffffff812707f7: pageout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
pageout_t pageout(struct page *page, struct address_space *mapping);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81274a80)
Location: mm/vmscan.c:978
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_page_list
```
**Symbols:**

```
ffffffff81274a80-ffffffff81274d97: pageout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
pageout_t pageout(struct page *page, struct address_space *mapping);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff812b1d20)
Location: mm/vmscan.c:1025
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_page_list
```
**Symbols:**

```
ffffffff812b1d20-ffffffff812b2047: pageout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
pageout_t pageout(struct folio *folio, struct address_space *mapping, struct swap_iocb **plug);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8130dcf0)
Location: mm/vmscan.c:1154
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_page_list
```
**Symbols:**

```
ffffffff8130dcf0-ffffffff8130dff1: pageout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
pageout_t pageout(struct folio *folio, struct address_space *mapping, struct swap_iocb **plug);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81379040)
Location: mm/vmscan.c:1252
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_folio_list
```
**Symbols:**

```
ffffffff81379040-ffffffff813792a9: pageout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
pageout_t pageout(struct folio *folio, struct address_space *mapping, struct swap_iocb **plug);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff813ad610)
Location: mm/vmscan.c:1305
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_folio_list
```
**Symbols:**

```
ffffffff813ad610-ffffffff813ad86d: pageout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
pageout_t pageout(struct folio *folio, struct address_space *mapping, struct swap_iocb **plug);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff813d6a20)
Location: mm/vmscan.c:604
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_folio_list
```
**Symbols:**

```
ffffffff813d6a20-ffffffff813d6c76: pageout (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/vmscan.c (ffff8000102c8568)
Location: mm/vmscan.c:826
Inline: True
Direct callers:
  - mm/vmscan.c:shrink_page_list
```
**Symbols:**

```
ffff8000102c8568-ffff8000102c8934: pageout.isra.0 (STB_LOCAL)
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
In mm/vmscan.c (c04f4cb0)
Location: mm/vmscan.c:826
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/vmscan.c (c000000000384550)
Location: mm/vmscan.c:826
Inline: True
Direct callers:
  - mm/vmscan.c:shrink_page_list
```
**Symbols:**

```
c000000000384550-c000000000384a68: pageout.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/vmscan.c (ffffffe0001e6fce)
Location: mm/vmscan.c:826
Inline: True
Direct callers:
  - mm/vmscan.c:shrink_page_list
```
**Symbols:**

```
ffffffe0001e6fce-ffffffe0001e7274: pageout.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/vmscan.c (ffffffff8122ee90)
Location: mm/vmscan.c:826
Inline: True
Direct callers:
  - mm/vmscan.c:shrink_page_list
```
**Symbols:**

```
ffffffff8122ee90-ffffffff8122f1d6: pageout.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/vmscan.c (ffffffff81221f50)
Location: mm/vmscan.c:826
Inline: True
Direct callers:
  - mm/vmscan.c:shrink_page_list
```
**Symbols:**

```
ffffffff81221f50-ffffffff81222296: pageout.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/vmscan.c (ffffffff8122cc30)
Location: mm/vmscan.c:826
Inline: True
Direct callers:
  - mm/vmscan.c:shrink_page_list
```
**Symbols:**

```
ffffffff8122cc30-ffffffff8122cf76: pageout.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/vmscan.c (ffffffff8123c060)
Location: mm/vmscan.c:826
Inline: True
Direct callers:
  - mm/vmscan.c:shrink_page_list
```
**Symbols:**

```
ffffffff8123c060-ffffffff8123c3ba: pageout.isra.0 (STB_LOCAL)
```
</details>
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct folio *folio</code>
</li>
<li>
<b>Param added. </b>
<code>struct swap_iocb **plug</code>
</li>
<li>
<b>Param removed. </b>
<code>struct page *page</code>
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
