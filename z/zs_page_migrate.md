# Function: <code>zs_page_migrate</code>

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
int zs_page_migrate(struct address_space *mapping, struct page *newpage, struct page *page, enum migrate_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff8122b320)
Location: mm/zsmalloc.c:2017
Inline: False
```
**Symbols:**

```
ffffffff8122b320-ffffffff8122b7af: zs_page_migrate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int zs_page_migrate(struct address_space *mapping, struct page *newpage, struct page *page, enum migrate_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff8123d880)
Location: mm/zsmalloc.c:1977
Inline: False
```
**Symbols:**

```
ffffffff8123d880-ffffffff8123dd0b: zs_page_migrate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int zs_page_migrate(struct address_space *mapping, struct page *newpage, struct page *page, enum migrate_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff812488a0)
Location: mm/zsmalloc.c:1956
Inline: False
```
**Symbols:**

```
ffffffff812488a0-ffffffff81248c5d: zs_page_migrate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int zs_page_migrate(struct address_space *mapping, struct page *newpage, struct page *page, enum migrate_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff81268a70)
Location: mm/zsmalloc.c:1960
Inline: False
```
**Symbols:**

```
ffffffff81268a70-ffffffff81268e8f: zs_page_migrate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int zs_page_migrate(struct address_space *mapping, struct page *newpage, struct page *page, enum migrate_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff8128da00)
Location: mm/zsmalloc.c:1963
Inline: False
```
**Symbols:**

```
ffffffff8128da00-ffffffff8128de27: zs_page_migrate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int zs_page_migrate(struct address_space *mapping, struct page *newpage, struct page *page, enum migrate_mode mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff812a3340)
Location: mm/zsmalloc.c:1963
Inline: False
```
**Symbols:**

```
ffffffff812a3340-ffffffff812a3756: zs_page_migrate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int zs_page_migrate(struct address_space *mapping, struct page *newpage, struct page *page, enum migrate_mode mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff812be6a0)
Location: mm/zsmalloc.c:1974
Inline: False
```
**Symbols:**

```
ffffffff812be6a0-ffffffff812beb4c: zs_page_migrate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int zs_page_migrate(struct address_space *mapping, struct page *newpage, struct page *page, enum migrate_mode mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff812d0590)
Location: mm/zsmalloc.c:1971
Inline: False
```
**Symbols:**

```
ffffffff812d0590-ffffffff812d0aad: zs_page_migrate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int zs_page_migrate(struct address_space *mapping, struct page *newpage, struct page *page, enum migrate_mode mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff81306f00)
Location: mm/zsmalloc.c:1973
Inline: False
```
**Symbols:**

```
ffffffff81306f00-ffffffff81307478: zs_page_migrate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int zs_page_migrate(struct address_space *mapping, struct page *newpage, struct page *page, enum migrate_mode mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff81312c40)
Location: mm/zsmalloc.c:1922
Inline: False
```
**Symbols:**

```
ffffffff81312c40-ffffffff813131b5: zs_page_migrate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int zs_page_migrate(struct address_space *mapping, struct page *newpage, struct page *page, enum migrate_mode mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff81318f00)
Location: mm/zsmalloc.c:1921
Inline: False
```
**Symbols:**

```
ffffffff81318f00-ffffffff8131942f: zs_page_migrate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int zs_page_migrate(struct address_space *mapping, struct page *newpage, struct page *page, enum migrate_mode mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/zsmalloc.c (0)
Location: mm/zsmalloc.c:1921
Inline: False
```
**Symbols:**

```
ffffffff81365520-ffffffff81365bd0: zs_page_migrate (STB_LOCAL)
ffffffff81cc351f-ffffffff81cc3544: zs_page_migrate.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int zs_page_migrate(struct address_space *mapping, struct page *newpage, struct page *page, enum migrate_mode mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff813e1b00)
Location: mm/zsmalloc.c:1868
Inline: False
```
**Symbols:**

```
ffffffff813e1b00-ffffffff813e2022: zs_page_migrate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int zs_page_migrate(struct page *newpage, struct page *page, enum migrate_mode mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff814690f0)
Location: mm/zsmalloc.c:2070
Inline: False
```
**Symbols:**

```
ffffffff814690f0-ffffffff814695f5: zs_page_migrate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int zs_page_migrate(struct page *newpage, struct page *page, enum migrate_mode mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff8149e090)
Location: mm/zsmalloc.c:1819
Inline: False
```
**Symbols:**

```
ffffffff8149e090-ffffffff8149e5a4: zs_page_migrate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int zs_page_migrate(struct page *newpage, struct page *page, enum migrate_mode mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff814cd1d0)
Location: mm/zsmalloc.c:1801
Inline: False
```
**Symbols:**

```
ffffffff814cd1d0-ffffffff814cd6b2: zs_page_migrate (STB_LOCAL)
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
int zs_page_migrate(struct address_space *mapping, struct page *newpage, struct page *page, enum migrate_mode mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffff8000103759e0)
Location: mm/zsmalloc.c:1971
Inline: False
```
**Symbols:**

```
ffff8000103759e0-ffff800010375f64: zs_page_migrate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int zs_page_migrate(struct address_space *mapping, struct page *newpage, struct page *page, enum migrate_mode mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (c0561bdc)
Location: mm/zsmalloc.c:1971
Inline: False
```
**Symbols:**

```
c0561bdc-c05620a8: zs_page_migrate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int zs_page_migrate(struct address_space *mapping, struct page *newpage, struct page *page, enum migrate_mode mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (c000000000468220)
Location: mm/zsmalloc.c:1971
Inline: False
```
**Symbols:**

```
c000000000468220-c00000000046885c: zs_page_migrate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int zs_page_migrate(struct address_space *mapping, struct page *newpage, struct page *page, enum migrate_mode mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffe00024e1ac)
Location: mm/zsmalloc.c:1971
Inline: False
```
**Symbols:**

```
ffffffe00024e1ac-ffffffe00024e5e0: zs_page_migrate (STB_LOCAL)
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
int zs_page_migrate(struct address_space *mapping, struct page *newpage, struct page *page, enum migrate_mode mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff812c8b70)
Location: mm/zsmalloc.c:1971
Inline: False
```
**Symbols:**

```
ffffffff812c8b70-ffffffff812c908d: zs_page_migrate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int zs_page_migrate(struct address_space *mapping, struct page *newpage, struct page *page, enum migrate_mode mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff812b9bb0)
Location: mm/zsmalloc.c:1971
Inline: False
```
**Symbols:**

```
ffffffff812b9bb0-ffffffff812ba0cd: zs_page_migrate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int zs_page_migrate(struct address_space *mapping, struct page *newpage, struct page *page, enum migrate_mode mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff812c6980)
Location: mm/zsmalloc.c:1971
Inline: False
```
**Symbols:**

```
ffffffff812c6980-ffffffff812c6e9d: zs_page_migrate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int zs_page_migrate(struct address_space *mapping, struct page *newpage, struct page *page, enum migrate_mode mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff812d6f00)
Location: mm/zsmalloc.c:1971
Inline: False
```
**Symbols:**

```
ffffffff812d6f00-ffffffff812d745c: zs_page_migrate (STB_LOCAL)
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
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct address_space *mapping</code>
</li>
<li>
<b>Param reordered. </b>
<code>mapping, newpage, page, mode</code> ➡️ <code>newpage, page, mode</code>
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
