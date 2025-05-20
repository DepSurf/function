# Function: <code>buffer_migrate_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int buffer_migrate_page(struct address_space *mapping, struct page *newpage, struct page *page, enum migrate_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff811f21c0)
Location: mm/migrate.c:617
Inline: False
```
**Symbols:**

```
ffffffff811f21c0-ffffffff811f22c0: buffer_migrate_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int buffer_migrate_page(struct address_space *mapping, struct page *newpage, struct page *page, enum migrate_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff81211070)
Location: mm/migrate.c:717
Inline: False
```
**Symbols:**

```
ffffffff81211070-ffffffff812111cd: buffer_migrate_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int buffer_migrate_page(struct address_space *mapping, struct page *newpage, struct page *page, enum migrate_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff81223230)
Location: mm/migrate.c:719
Inline: False
```
**Symbols:**

```
ffffffff81223230-ffffffff8122338d: buffer_migrate_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int buffer_migrate_page(struct address_space *mapping, struct page *newpage, struct page *page, enum migrate_mode mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff8122ec80)
Location: mm/migrate.c:705
Inline: True
```
**Symbols:**

```
ffffffff8122ec80-ffffffff8122ed9d: buffer_migrate_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int buffer_migrate_page(struct address_space *mapping, struct page *newpage, struct page *page, enum migrate_mode mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff8124adf0)
Location: mm/migrate.c:765
Inline: True
```
**Symbols:**

```
ffffffff8124adf0-ffffffff8124af47: buffer_migrate_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int buffer_migrate_page(struct address_space *mapping, struct page *newpage, struct page *page, enum migrate_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff8126ecc0)
Location: mm/migrate.c:777
Inline: False
```
**Symbols:**

```
ffffffff8126ecc0-ffffffff8126ee35: buffer_migrate_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int buffer_migrate_page(struct address_space *mapping, struct page *newpage, struct page *page, enum migrate_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff81282b60)
Location: mm/migrate.c:827
Inline: False
```
**Symbols:**

```
ffffffff81282b60-ffffffff81282b73: buffer_migrate_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int buffer_migrate_page(struct address_space *mapping, struct page *newpage, struct page *page, enum migrate_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff8129ed60)
Location: mm/migrate.c:825
Inline: False
```
**Symbols:**

```
ffffffff8129ed60-ffffffff8129ed73: buffer_migrate_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int buffer_migrate_page(struct address_space *mapping, struct page *newpage, struct page *page, enum migrate_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812ae600)
Location: mm/migrate.c:826
Inline: False
```
**Symbols:**

```
ffffffff812ae600-ffffffff812ae613: buffer_migrate_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int buffer_migrate_page(struct address_space *mapping, struct page *newpage, struct page *page, enum migrate_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812e4fe0)
Location: mm/migrate.c:840
Inline: False
```
**Symbols:**

```
ffffffff812e4fe0-ffffffff812e5002: buffer_migrate_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int buffer_migrate_page(struct address_space *mapping, struct page *newpage, struct page *page, enum migrate_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812ef9b0)
Location: mm/migrate.c:838
Inline: False
```
**Symbols:**

```
ffffffff812ef9b0-ffffffff812ef9d2: buffer_migrate_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int buffer_migrate_page(struct address_space *mapping, struct page *newpage, struct page *page, enum migrate_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812f66a0)
Location: mm/migrate.c:818
Inline: False
```
**Symbols:**

```
ffffffff812f66a0-ffffffff812f66c2: buffer_migrate_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int buffer_migrate_page(struct address_space *mapping, struct page *newpage, struct page *page, enum migrate_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff81340ce0)
Location: mm/migrate.c:781
Inline: False
```
**Symbols:**

```
ffffffff81340ce0-ffffffff81340d02: buffer_migrate_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int buffer_migrate_page(struct address_space *mapping, struct page *newpage, struct page *page, enum migrate_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff813b2bf0)
Location: mm/migrate.c:759
Inline: False
```
**Symbols:**

```
ffffffff813b2bf0-ffffffff813b2c12: buffer_migrate_page (STB_GLOBAL)
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
int buffer_migrate_page(struct address_space *mapping, struct page *newpage, struct page *page, enum migrate_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffff800010350518)
Location: mm/migrate.c:826
Inline: False
```
**Symbols:**

```
ffff800010350518-ffff800010350568: buffer_migrate_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int buffer_migrate_page(struct address_space *mapping, struct page *newpage, struct page *page, enum migrate_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (c0551c44)
Location: mm/migrate.c:826
Inline: False
```
**Symbols:**

```
c0551c44-c0551c70: buffer_migrate_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int buffer_migrate_page(struct address_space *mapping, struct page *newpage, struct page *page, enum migrate_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (c000000000434320)
Location: mm/migrate.c:826
Inline: False
```
**Symbols:**

```
c000000000434320-c000000000434338: buffer_migrate_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int buffer_migrate_page(struct address_space *mapping, struct page *newpage, struct page *page, enum migrate_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffe00023f120)
Location: mm/migrate.c:826
Inline: False
```
**Symbols:**

```
ffffffe00023f120-ffffffe00023f164: buffer_migrate_page (STB_GLOBAL)
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
int buffer_migrate_page(struct address_space *mapping, struct page *newpage, struct page *page, enum migrate_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812a6be0)
Location: mm/migrate.c:826
Inline: False
```
**Symbols:**

```
ffffffff812a6be0-ffffffff812a6bf3: buffer_migrate_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int buffer_migrate_page(struct address_space *mapping, struct page *newpage, struct page *page, enum migrate_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff81298680)
Location: mm/migrate.c:826
Inline: False
```
**Symbols:**

```
ffffffff81298680-ffffffff81298693: buffer_migrate_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int buffer_migrate_page(struct address_space *mapping, struct page *newpage, struct page *page, enum migrate_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812a49f0)
Location: mm/migrate.c:826
Inline: False
```
**Symbols:**

```
ffffffff812a49f0-ffffffff812a4a03: buffer_migrate_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int buffer_migrate_page(struct address_space *mapping, struct page *newpage, struct page *page, enum migrate_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812b5540)
Location: mm/migrate.c:826
Inline: False
```
**Symbols:**

```
ffffffff812b5540-ffffffff812b5553: buffer_migrate_page (STB_GLOBAL)
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
