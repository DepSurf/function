# Function: <code>writeout</code>

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
In mm/migrate.c (ffffffff811f20d8)
Location: mm/migrate.c:674
Inline: True
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
In mm/migrate.c (ffffffff81211629)
Location: mm/migrate.c:774
Inline: True
Inline callers:
  - mm/migrate.c:move_to_new_page
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
In mm/migrate.c (ffffffff812237e9)
Location: mm/migrate.c:776
Inline: True
Inline callers:
  - mm/migrate.c:move_to_new_page
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
In mm/migrate.c (ffffffff8122f1e7)
Location: mm/migrate.c:762
Inline: True
Inline callers:
  - mm/migrate.c:move_to_new_page
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
In mm/migrate.c (ffffffff8124bf33)
Location: mm/migrate.c:825
Inline: True
Inline callers:
  - mm/migrate.c:move_to_new_page
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
In mm/migrate.c (ffffffff8126f9d2)
Location: mm/migrate.c:837
Inline: True
Inline callers:
  - mm/migrate.c:move_to_new_page
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
In mm/migrate.c (ffffffff81284062)
Location: mm/migrate.c:850
Inline: True
Inline callers:
  - mm/migrate.c:move_to_new_page
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
In mm/migrate.c (ffffffff8129f22a)
Location: mm/migrate.c:848
Inline: True
Inline callers:
  - mm/migrate.c:move_to_new_page
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
In mm/migrate.c (ffffffff812afc1a)
Location: mm/migrate.c:849
Inline: True
Inline callers:
  - mm/migrate.c:move_to_new_page
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
In mm/migrate.c (ffffffff812e5cca)
Location: mm/migrate.c:863
Inline: True
Inline callers:
  - mm/migrate.c:move_to_new_page
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
In mm/migrate.c (ffffffff812f108a)
Location: mm/migrate.c:861
Inline: True
Inline callers:
  - mm/migrate.c:move_to_new_page
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
In mm/migrate.c (ffffffff812f738a)
Location: mm/migrate.c:841
Inline: True
Inline callers:
  - mm/migrate.c:move_to_new_page
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
In mm/migrate.c (ffffffff813419ed)
Location: mm/migrate.c:804
Inline: True
Inline callers:
  - mm/migrate.c:move_to_new_page
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int writeout(struct address_space *mapping, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff813b34c0)
Location: mm/migrate.c:782
Inline: False
Direct callers:
  - mm/migrate.c:move_to_new_folio
```
**Symbols:**

```
ffffffff813b34c0-ffffffff813b363a: writeout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int writeout(struct address_space *mapping, struct folio *folio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff814339f0)
Location: mm/migrate.c:860
Inline: False
Direct callers:
  - mm/migrate.c:move_to_new_folio
```
**Symbols:**

```
ffffffff814339f0-ffffffff81433ad9: writeout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int writeout(struct address_space *mapping, struct folio *folio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff81469450)
Location: mm/migrate.c:865
Inline: False
Direct callers:
  - mm/migrate.c:move_to_new_folio
```
**Symbols:**

```
ffffffff81469450-ffffffff81469533: writeout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int writeout(struct address_space *mapping, struct folio *folio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff81498360)
Location: mm/migrate.c:874
Inline: False
Direct callers:
  - mm/migrate.c:move_to_new_folio
```
**Symbols:**

```
ffffffff81498360-ffffffff81498443: writeout (STB_LOCAL)
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
In mm/migrate.c (ffff800010350b54)
Location: mm/migrate.c:849
Inline: True
Inline callers:
  - mm/migrate.c:move_to_new_page
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
In mm/migrate.c (c0552220)
Location: mm/migrate.c:849
Inline: True
Inline callers:
  - mm/migrate.c:move_to_new_page
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
In mm/migrate.c (c000000000435b08)
Location: mm/migrate.c:849
Inline: True
Inline callers:
  - mm/migrate.c:move_to_new_page
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
In mm/migrate.c (ffffffe00023f586)
Location: mm/migrate.c:849
Inline: True
Inline callers:
  - mm/migrate.c:move_to_new_page
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
In mm/migrate.c (ffffffff812a81fa)
Location: mm/migrate.c:849
Inline: True
Inline callers:
  - mm/migrate.c:move_to_new_page
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
In mm/migrate.c (ffffffff81299bba)
Location: mm/migrate.c:849
Inline: True
Inline callers:
  - mm/migrate.c:move_to_new_page
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
In mm/migrate.c (ffffffff812a600a)
Location: mm/migrate.c:849
Inline: True
Inline callers:
  - mm/migrate.c:move_to_new_page
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
In mm/migrate.c (ffffffff812b635a)
Location: mm/migrate.c:849
Inline: True
Inline callers:
  - mm/migrate.c:move_to_new_page
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct folio *folio</code>
</li>
<li>
<b>Param removed. </b>
<code>struct page *page</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
