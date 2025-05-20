# Function: <code>soft_offline_in_use_page</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff81227bcd)
Location: mm/memory-failure.c:1689
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
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
In mm/memory-failure.c (ffffffff8123a15a)
Location: mm/memory-failure.c:1685
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
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
In mm/memory-failure.c (ffffffff81245d2c)
Location: mm/memory-failure.c:1683
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
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
In mm/memory-failure.c (ffffffff81265d50)
Location: mm/memory-failure.c:1681
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
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
In mm/memory-failure.c (ffffffff8128a0ce)
Location: mm/memory-failure.c:1807
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
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
In mm/memory-failure.c (ffffffff8129f042)
Location: mm/memory-failure.c:1821
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
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
In mm/memory-failure.c (0)
Location: mm/memory-failure.c:1816
Inline: True
Direct callers:
  - mm/memory-failure.c:soft_offline_page
```
**Symbols:**

```
ffffffff812b9560-ffffffff812b9a08: soft_offline_in_use_page.isra.0 (STB_LOCAL)
ffffffff812bac62-ffffffff812bad51: soft_offline_in_use_page.isra.0.cold (STB_LOCAL)
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
In mm/memory-failure.c (0)
Location: mm/memory-failure.c:1822
Inline: True
Direct callers:
  - mm/memory-failure.c:soft_offline_page
```
**Symbols:**

```
ffffffff812cb460-ffffffff812cb908: soft_offline_in_use_page.isra.0 (STB_LOCAL)
ffffffff812ccb3a-ffffffff812ccc29: soft_offline_in_use_page.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memory-failure.c (0)
Location: mm/memory-failure.c:1858
Inline: True
Direct callers:
  - mm/memory-failure.c:soft_offline_page
```
**Symbols:**

```
ffffffff81301bd0-ffffffff81301cdd: soft_offline_in_use_page.isra.0 (STB_LOCAL)
ffffffff81302e60-ffffffff81302eaa: soft_offline_in_use_page.isra.0.cold (STB_LOCAL)
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
In mm/memory-failure.c (ffffffff8130ed6b)
Location: mm/memory-failure.c:1874
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
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
In mm/memory-failure.c (ffffffff813150c1)
Location: mm/memory-failure.c:1965
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
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
In mm/memory-failure.c (ffffffff81361166)
Location: mm/memory-failure.c:2120
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
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
In mm/memory-failure.c (ffffffff813dd436)
Location: mm/memory-failure.c:2274
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int soft_offline_in_use_page(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff81461790)
Location: mm/memory-failure.c:2474
Inline: False
Direct callers:
  - mm/memory-failure.c:soft_offline_page
```
**Symbols:**

```
ffffffff81461790-ffffffff81461f1e: soft_offline_in_use_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int soft_offline_in_use_page(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff81496fb0)
Location: mm/memory-failure.c:2607
Inline: False
Direct callers:
  - mm/memory-failure.c:soft_offline_page
```
**Symbols:**

```
ffffffff81496fb0-ffffffff814976b6: soft_offline_in_use_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int soft_offline_in_use_page(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff814c6340)
Location: mm/memory-failure.c:2658
Inline: False
Direct callers:
  - mm/memory-failure.c:soft_offline_page
```
**Symbols:**

```
ffffffff814c6340-ffffffff814c686f: soft_offline_in_use_page (STB_LOCAL)
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
In mm/memory-failure.c (ffff8000103701bc)
Location: mm/memory-failure.c:1822
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memory-failure.c (c00000000045fed0)
Location: mm/memory-failure.c:1822
Inline: True
Direct callers:
  - mm/memory-failure.c:soft_offline_page
```
**Symbols:**

```
c00000000045fed0-c000000000460708: soft_offline_in_use_page.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
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
In mm/memory-failure.c (0)
Location: mm/memory-failure.c:1822
Inline: True
Direct callers:
  - mm/memory-failure.c:soft_offline_page
```
**Symbols:**

```
ffffffff812c3a40-ffffffff812c3ee8: soft_offline_in_use_page.isra.0 (STB_LOCAL)
ffffffff812c511a-ffffffff812c5209: soft_offline_in_use_page.isra.0.cold (STB_LOCAL)
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
In mm/memory-failure.c (0)
Location: mm/memory-failure.c:1822
Inline: True
Direct callers:
  - mm/memory-failure.c:soft_offline_page
```
**Symbols:**

```
ffffffff812b4a80-ffffffff812b4f28: soft_offline_in_use_page.isra.0 (STB_LOCAL)
ffffffff812b615a-ffffffff812b6249: soft_offline_in_use_page.isra.0.cold (STB_LOCAL)
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
In mm/memory-failure.c (0)
Location: mm/memory-failure.c:1822
Inline: True
Direct callers:
  - mm/memory-failure.c:soft_offline_page
```
**Symbols:**

```
ffffffff812c1850-ffffffff812c1cf8: soft_offline_in_use_page.isra.0 (STB_LOCAL)
ffffffff812c2f2a-ffffffff812c3019: soft_offline_in_use_page.isra.0.cold (STB_LOCAL)
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
In mm/memory-failure.c (0)
Location: mm/memory-failure.c:1822
Inline: True
Direct callers:
  - mm/memory-failure.c:soft_offline_page
```
**Symbols:**

```
ffffffff812d2310-ffffffff812d27a9: soft_offline_in_use_page.isra.0 (STB_LOCAL)
ffffffff812d39ca-ffffffff812d3ab9: soft_offline_in_use_page.isra.0.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
