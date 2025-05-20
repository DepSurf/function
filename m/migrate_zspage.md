# Function: <code>migrate_zspage</code>

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
In mm/zsmalloc.c (ffffffff8120611f)
Location: mm/zsmalloc.c:1612
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
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
In mm/zsmalloc.c (ffffffff8122bce6)
Location: mm/zsmalloc.c:1775
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
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
In mm/zsmalloc.c (ffffffff8123e236)
Location: mm/zsmalloc.c:1735
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
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
In mm/zsmalloc.c (ffffffff81249be6)
Location: mm/zsmalloc.c:1714
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
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
In mm/zsmalloc.c (ffffffff81269fb2)
Location: mm/zsmalloc.c:1718
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
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
In mm/zsmalloc.c (ffffffff8128e8d1)
Location: mm/zsmalloc.c:1721
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
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
In mm/zsmalloc.c (ffffffff812a2a71)
Location: mm/zsmalloc.c:1708
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
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
In mm/zsmalloc.c (ffffffff812bddec)
Location: mm/zsmalloc.c:1698
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
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
In mm/zsmalloc.c (ffffffff812cfcdc)
Location: mm/zsmalloc.c:1695
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
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
In mm/zsmalloc.c (ffffffff813061d0)
Location: mm/zsmalloc.c:1697
Inline: True
Direct callers:
  - mm/zsmalloc.c:__zs_compact
```
**Symbols:**

```
ffffffff813061d0-ffffffff813062ea: migrate_zspage.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/zsmalloc.c (ffffffff81311f30)
Location: mm/zsmalloc.c:1646
Inline: True
Direct callers:
  - mm/zsmalloc.c:__zs_compact
```
**Symbols:**

```
ffffffff81311f30-ffffffff8131204a: migrate_zspage.constprop.0 (STB_LOCAL)
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
In mm/zsmalloc.c (ffffffff8131800b)
Location: mm/zsmalloc.c:1645
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
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
In mm/zsmalloc.c (ffffffff81364511)
Location: mm/zsmalloc.c:1644
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
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
In mm/zsmalloc.c (ffffffff813e2493)
Location: mm/zsmalloc.c:1631
Inline: True
Inline callers:
  - mm/zsmalloc.c:__zs_compact
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
In mm/zsmalloc.c (ffffffff81469a8d)
Location: mm/zsmalloc.c:1839
Inline: True
Inline callers:
  - mm/zsmalloc.c:__zs_compact
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/zsmalloc.c (ffffffff8149e950)
Location: mm/zsmalloc.c:1599
Inline: True
Direct callers:
  - mm/zsmalloc.c:__zs_compact
```
**Symbols:**

```
ffffffff8149e950-ffffffff8149eb55: migrate_zspage.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void migrate_zspage(struct zs_pool *pool, struct zspage *src_zspage, struct zspage *dst_zspage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff814ce0f0)
Location: mm/zsmalloc.c:1581
Inline: False
Direct callers:
  - mm/zsmalloc.c:__zs_compact
```
**Symbols:**

```
ffffffff814ce0f0-ffffffff814ce31b: migrate_zspage (STB_LOCAL)
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
In mm/zsmalloc.c (ffff80001037486c)
Location: mm/zsmalloc.c:1695
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
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
In mm/zsmalloc.c (c056169c)
Location: mm/zsmalloc.c:1695
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
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
In mm/zsmalloc.c (c000000000467bd8)
Location: mm/zsmalloc.c:1695
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
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
In mm/zsmalloc.c (ffffffe00024d71e)
Location: mm/zsmalloc.c:1695
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
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
In mm/zsmalloc.c (ffffffff812c82bc)
Location: mm/zsmalloc.c:1695
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
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
In mm/zsmalloc.c (ffffffff812b92fc)
Location: mm/zsmalloc.c:1695
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
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
In mm/zsmalloc.c (ffffffff812c60cc)
Location: mm/zsmalloc.c:1695
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
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
In mm/zsmalloc.c (ffffffff812d783f)
Location: mm/zsmalloc.c:1695
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
