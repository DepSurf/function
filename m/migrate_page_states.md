# Function: <code>migrate_page_states</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void migrate_page_states(struct page *newpage, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff81249280)
Location: mm/migrate.c:658
Inline: False
Direct callers:
  - mm/migrate.c:migrate_page_copy
```
**Symbols:**

```
ffffffff81249280-ffffffff81249477: migrate_page_states (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void migrate_page_states(struct page *newpage, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff8126cd00)
Location: mm/migrate.c:670
Inline: False
Direct callers:
  - mm/migrate.c:buffer_migrate_page
  - mm/migrate.c:migrate_page_copy
```
**Symbols:**

```
ffffffff8126cd00-ffffffff8126cf06: migrate_page_states (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void migrate_page_states(struct page *newpage, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff81281500)
Location: mm/migrate.c:597
Inline: False
Direct callers:
  - mm/migrate.c:migrate_page_copy
```
**Symbols:**

```
ffffffff81281500-ffffffff81281732: migrate_page_states (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void migrate_page_states(struct page *newpage, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff8129d790)
Location: mm/migrate.c:593
Inline: False
Direct callers:
  - mm/migrate.c:migrate_page_copy
```
**Symbols:**

```
ffffffff8129d790-ffffffff8129d9be: migrate_page_states (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void migrate_page_states(struct page *newpage, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812ad090)
Location: mm/migrate.c:594
Inline: False
Direct callers:
  - mm/migrate.c:migrate_page_copy
```
**Symbols:**

```
ffffffff812ad090-ffffffff812ad2dc: migrate_page_states (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void migrate_page_states(struct page *newpage, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812e2bd0)
Location: mm/migrate.c:606
Inline: False
Direct callers:
  - mm/migrate.c:migrate_page
  - mm/migrate.c:migrate_page_copy
```
**Symbols:**

```
ffffffff812e2bd0-ffffffff812e2e52: migrate_page_states (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void migrate_page_states(struct page *newpage, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812ee000)
Location: mm/migrate.c:603
Inline: False
Direct callers:
  - mm/migrate.c:migrate_page
  - mm/migrate.c:migrate_page_copy
```
**Symbols:**

```
ffffffff812ee000-ffffffff812ee294: migrate_page_states (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void migrate_page_states(struct page *newpage, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812f3af0)
Location: mm/migrate.c:583
Inline: False
Direct callers:
  - mm/migrate.c:migrate_page
  - mm/migrate.c:migrate_page_copy
```
**Symbols:**

```
ffffffff812f3af0-ffffffff812f3d84: migrate_page_states (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void migrate_page_states(struct page *newpage, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff8133e490)
Location: mm/migrate.c:543
Inline: False
Direct callers:
  - mm/migrate.c:migrate_page
  - mm/migrate.c:migrate_page_copy
```
**Symbols:**

```
ffffffff8133e490-ffffffff8133e730: migrate_page_states (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void migrate_page_states(struct page *newpage, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/folio-compat.c (ffffffff81301180)
Location: mm/folio-compat.c:63
Inline: False
Direct callers:
  - mm/migrate.c:__buffer_migrate_page
```
**Symbols:**

```
ffffffff81301180-ffffffff81301211: migrate_page_states (STB_GLOBAL)
```
</details>
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
void migrate_page_states(struct page *newpage, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffff80001034f320)
Location: mm/migrate.c:594
Inline: False
Direct callers:
  - mm/migrate.c:__buffer_migrate_page
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
```
**Symbols:**

```
ffff80001034f320-ffff80001034f7d0: migrate_page_states (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void migrate_page_states(struct page *newpage, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (c05512bc)
Location: mm/migrate.c:594
Inline: False
Direct callers:
  - mm/migrate.c:__buffer_migrate_page
  - mm/migrate.c:__buffer_migrate_page
```
**Symbols:**

```
c05512bc-c05515a8: migrate_page_states (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void migrate_page_states(struct page *newpage, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (c000000000431720)
Location: mm/migrate.c:594
Inline: False
Direct callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
```
**Symbols:**

```
c000000000431720-c000000000431c38: migrate_page_states (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void migrate_page_states(struct page *newpage, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffe00023e3a6)
Location: mm/migrate.c:594
Inline: False
Direct callers:
  - mm/migrate.c:__buffer_migrate_page
  - mm/migrate.c:migrate_page_copy
```
**Symbols:**

```
ffffffe00023e3a6-ffffffe00023e658: migrate_page_states (STB_GLOBAL)
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
void migrate_page_states(struct page *newpage, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812a5670)
Location: mm/migrate.c:594
Inline: False
Direct callers:
  - mm/migrate.c:migrate_page_copy
```
**Symbols:**

```
ffffffff812a5670-ffffffff812a58bc: migrate_page_states (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void migrate_page_states(struct page *newpage, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff81297140)
Location: mm/migrate.c:594
Inline: False
Direct callers:
  - mm/migrate.c:migrate_page_copy
```
**Symbols:**

```
ffffffff81297140-ffffffff8129738c: migrate_page_states (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void migrate_page_states(struct page *newpage, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812a3480)
Location: mm/migrate.c:594
Inline: False
Direct callers:
  - mm/migrate.c:migrate_page_copy
```
**Symbols:**

```
ffffffff812a3480-ffffffff812a36cc: migrate_page_states (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void migrate_page_states(struct page *newpage, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812b3c90)
Location: mm/migrate.c:594
Inline: False
Direct callers:
  - mm/migrate.c:migrate_page_copy
```
**Symbols:**

```
ffffffff812b3c90-ffffffff812b3edc: migrate_page_states (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
