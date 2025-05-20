# Function: <code>balloon_page_migrate</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int balloon_page_migrate(struct page *newpage, struct page *page, enum migrate_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/balloon_compaction.c (ffffffff812076a0)
Location: mm/balloon_compaction.c:196
Inline: False
Direct callers:
  - mm/migrate.c:migrate_pages
```
**Symbols:**

```
ffffffff812076a0-ffffffff81207708: balloon_page_migrate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int balloon_page_migrate(struct address_space *mapping, struct page *newpage, struct page *page, enum migrate_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/balloon_compaction.c (ffffffff8122cdc0)
Location: mm/balloon_compaction.c:136
Inline: False
```
**Symbols:**

```
ffffffff8122cdc0-ffffffff8122cdd5: balloon_page_migrate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int balloon_page_migrate(struct address_space *mapping, struct page *newpage, struct page *page, enum migrate_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/balloon_compaction.c (ffffffff8123f2e0)
Location: mm/balloon_compaction.c:136
Inline: False
```
**Symbols:**

```
ffffffff8123f2e0-ffffffff8123f2f5: balloon_page_migrate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int balloon_page_migrate(struct address_space *mapping, struct page *newpage, struct page *page, enum migrate_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/balloon_compaction.c (ffffffff8124ac30)
Location: mm/balloon_compaction.c:136
Inline: False
```
**Symbols:**

```
ffffffff8124ac30-ffffffff8124ac45: balloon_page_migrate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int balloon_page_migrate(struct address_space *mapping, struct page *newpage, struct page *page, enum migrate_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/balloon_compaction.c (ffffffff8126ae90)
Location: mm/balloon_compaction.c:150
Inline: False
```
**Symbols:**

```
ffffffff8126ae90-ffffffff8126aeb3: balloon_page_migrate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int balloon_page_migrate(struct address_space *mapping, struct page *newpage, struct page *page, enum migrate_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/balloon_compaction.c (ffffffff8128f880)
Location: mm/balloon_compaction.c:150
Inline: False
```
**Symbols:**

```
ffffffff8128f880-ffffffff8128f8a3: balloon_page_migrate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int balloon_page_migrate(struct address_space *mapping, struct page *newpage, struct page *page, enum migrate_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/balloon_compaction.c (ffffffff812a47a0)
Location: mm/balloon_compaction.c:150
Inline: False
```
**Symbols:**

```
ffffffff812a47a0-ffffffff812a47c3: balloon_page_migrate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int balloon_page_migrate(struct address_space *mapping, struct page *newpage, struct page *page, enum migrate_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/balloon_compaction.c (ffffffff812bfbe0)
Location: mm/balloon_compaction.c:233
Inline: False
```
**Symbols:**

```
ffffffff812bfbe0-ffffffff812bfc03: balloon_page_migrate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int balloon_page_migrate(struct address_space *mapping, struct page *newpage, struct page *page, enum migrate_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/balloon_compaction.c (ffffffff812d1b30)
Location: mm/balloon_compaction.c:233
Inline: False
```
**Symbols:**

```
ffffffff812d1b30-ffffffff812d1b53: balloon_page_migrate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int balloon_page_migrate(struct address_space *mapping, struct page *newpage, struct page *page, enum migrate_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/balloon_compaction.c (ffffffff813078b0)
Location: mm/balloon_compaction.c:233
Inline: False
```
**Symbols:**

```
ffffffff813078b0-ffffffff813078d3: balloon_page_migrate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int balloon_page_migrate(struct address_space *mapping, struct page *newpage, struct page *page, enum migrate_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/balloon_compaction.c (ffffffff813135e0)
Location: mm/balloon_compaction.c:233
Inline: False
```
**Symbols:**

```
ffffffff813135e0-ffffffff81313603: balloon_page_migrate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int balloon_page_migrate(struct address_space *mapping, struct page *newpage, struct page *page, enum migrate_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/balloon_compaction.c (ffffffff81319770)
Location: mm/balloon_compaction.c:233
Inline: False
```
**Symbols:**

```
ffffffff81319770-ffffffff81319793: balloon_page_migrate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int balloon_page_migrate(struct address_space *mapping, struct page *newpage, struct page *page, enum migrate_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/balloon_compaction.c (ffffffff81365f60)
Location: mm/balloon_compaction.c:233
Inline: False
```
**Symbols:**

```
ffffffff81365f60-ffffffff81365f83: balloon_page_migrate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int balloon_page_migrate(struct address_space *mapping, struct page *newpage, struct page *page, enum migrate_mode mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/balloon_compaction.c (ffffffff813e2ef0)
Location: mm/balloon_compaction.c:233
Inline: False
```
**Symbols:**

```
ffffffff813e2ef0-ffffffff813e2f2b: balloon_page_migrate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int balloon_page_migrate(struct page *newpage, struct page *page, enum migrate_mode mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/balloon_compaction.c (ffffffff8146a810)
Location: mm/balloon_compaction.c:232
Inline: False
```
**Symbols:**

```
ffffffff8146a810-ffffffff8146a85d: balloon_page_migrate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int balloon_page_migrate(struct page *newpage, struct page *page, enum migrate_mode mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/balloon_compaction.c (ffffffff8149f6a0)
Location: mm/balloon_compaction.c:232
Inline: False
```
**Symbols:**

```
ffffffff8149f6a0-ffffffff8149f6ed: balloon_page_migrate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int balloon_page_migrate(struct page *newpage, struct page *page, enum migrate_mode mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/balloon_compaction.c (ffffffff814cedf0)
Location: mm/balloon_compaction.c:232
Inline: False
```
**Symbols:**

```
ffffffff814cedf0-ffffffff814cee3d: balloon_page_migrate (STB_LOCAL)
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
int balloon_page_migrate(struct address_space *mapping, struct page *newpage, struct page *page, enum migrate_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/balloon_compaction.c (ffff800010377438)
Location: mm/balloon_compaction.c:233
Inline: False
```
**Symbols:**

```
ffff800010377438-ffff800010377494: balloon_page_migrate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int balloon_page_migrate(struct address_space *mapping, struct page *newpage, struct page *page, enum migrate_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/balloon_compaction.c (c0563120)
Location: mm/balloon_compaction.c:233
Inline: False
```
**Symbols:**

```
c0563120-c0563154: balloon_page_migrate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int balloon_page_migrate(struct address_space *mapping, struct page *newpage, struct page *page, enum migrate_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/balloon_compaction.c (c000000000469c20)
Location: mm/balloon_compaction.c:233
Inline: False
```
**Symbols:**

```
c000000000469c20-c000000000469c74: balloon_page_migrate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int balloon_page_migrate(struct address_space *mapping, struct page *newpage, struct page *page, enum migrate_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/balloon_compaction.c (ffffffe00024f61a)
Location: mm/balloon_compaction.c:233
Inline: False
```
**Symbols:**

```
ffffffe00024f61a-ffffffe00024f65c: balloon_page_migrate (STB_GLOBAL)
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
int balloon_page_migrate(struct address_space *mapping, struct page *newpage, struct page *page, enum migrate_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/balloon_compaction.c (ffffffff812ca110)
Location: mm/balloon_compaction.c:233
Inline: False
```
**Symbols:**

```
ffffffff812ca110-ffffffff812ca133: balloon_page_migrate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int balloon_page_migrate(struct address_space *mapping, struct page *newpage, struct page *page, enum migrate_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/balloon_compaction.c (ffffffff812bb150)
Location: mm/balloon_compaction.c:233
Inline: False
```
**Symbols:**

```
ffffffff812bb150-ffffffff812bb173: balloon_page_migrate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int balloon_page_migrate(struct address_space *mapping, struct page *newpage, struct page *page, enum migrate_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/balloon_compaction.c (ffffffff812c7f20)
Location: mm/balloon_compaction.c:233
Inline: False
```
**Symbols:**

```
ffffffff812c7f20-ffffffff812c7f43: balloon_page_migrate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int balloon_page_migrate(struct address_space *mapping, struct page *newpage, struct page *page, enum migrate_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/balloon_compaction.c (ffffffff812d8c30)
Location: mm/balloon_compaction.c:233
Inline: False
```
**Symbols:**

```
ffffffff812d8c30-ffffffff812d8c53: balloon_page_migrate (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct address_space *mapping</code>
</li>
<li>
<b>Param reordered. </b>
<code>newpage, page, mode</code> ➡️ <code>mapping, newpage, page, mode</code>
</li>
</ul>
</details>
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
