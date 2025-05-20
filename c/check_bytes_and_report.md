# Function: <code>check_bytes_and_report</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int check_bytes_and_report(struct kmem_cache *s, struct page *page, u8 *object, char *what, u8 *start, unsigned int value, unsigned int bytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff811e8230)
Location: mm/slub.c:696
Inline: False
Direct callers:
  - mm/slub.c:check_object
  - mm/slub.c:check_object
  - mm/slub.c:check_object
  - mm/slub.c:check_object
  - mm/slub.c:check_object
```
**Symbols:**

```
ffffffff811e8230-ffffffff811e8335: check_bytes_and_report (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int check_bytes_and_report(struct kmem_cache *s, struct page *page, u8 *object, char *what, u8 *start, unsigned int value, unsigned int bytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812077e0)
Location: mm/slub.c:714
Inline: False
Direct callers:
  - mm/slub.c:check_object
  - mm/slub.c:check_object
  - mm/slub.c:check_object
  - mm/slub.c:check_object
  - mm/slub.c:check_object
  - mm/slub.c:check_object
```
**Symbols:**

```
ffffffff812077e0-ffffffff812078d9: check_bytes_and_report (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int check_bytes_and_report(struct kmem_cache *s, struct page *page, u8 *object, char *what, u8 *start, unsigned int value, unsigned int bytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81219810)
Location: mm/slub.c:713
Inline: False
Direct callers:
  - mm/slub.c:check_object
  - mm/slub.c:check_object
  - mm/slub.c:check_object
  - mm/slub.c:check_object
  - mm/slub.c:check_object
  - mm/slub.c:check_object
```
**Symbols:**

```
ffffffff81219810-ffffffff81219909: check_bytes_and_report (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int check_bytes_and_report(struct kmem_cache *s, struct page *page, u8 *object, char *what, u8 *start, unsigned int value, unsigned int bytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81225310)
Location: mm/slub.c:715
Inline: False
Direct callers:
  - mm/slub.c:check_object
  - mm/slub.c:check_object
  - mm/slub.c:check_object
  - mm/slub.c:check_object
  - mm/slub.c:check_object
  - mm/slub.c:check_object
```
**Symbols:**

```
ffffffff81225310-ffffffff812253ed: check_bytes_and_report (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int check_bytes_and_report(struct kmem_cache *s, struct page *page, u8 *object, char *what, u8 *start, unsigned int value, unsigned int bytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81240990)
Location: mm/slub.c:750
Inline: False
Direct callers:
  - mm/slub.c:check_object
  - mm/slub.c:check_object
  - mm/slub.c:check_object
  - mm/slub.c:check_object
  - mm/slub.c:check_object
  - mm/slub.c:check_object
```
**Symbols:**

```
ffffffff81240990-ffffffff81240a6d: check_bytes_and_report (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int check_bytes_and_report(struct kmem_cache *s, struct page *page, u8 *object, char *what, u8 *start, unsigned int value, unsigned int bytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:736
Inline: False
Direct callers:
  - mm/slub.c:check_object
  - mm/slub.c:check_object
  - mm/slub.c:check_object
  - mm/slub.c:check_object
  - mm/slub.c:check_object
  - mm/slub.c:check_object
```
**Symbols:**

```
ffffffff81263e20-ffffffff81263ea0: check_bytes_and_report (STB_LOCAL)
ffffffff8126ae3f-ffffffff8126ae9f: check_bytes_and_report.cold.91 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int check_bytes_and_report(struct kmem_cache *s, struct page *page, u8 *object, char *what, u8 *start, unsigned int value, unsigned int bytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:741
Inline: False
Direct callers:
  - mm/slub.c:check_object
  - mm/slub.c:check_object
  - mm/slub.c:check_object
  - mm/slub.c:check_object
  - mm/slub.c:check_object
  - mm/slub.c:check_object
```
**Symbols:**

```
ffffffff81278590-ffffffff81278610: check_bytes_and_report (STB_LOCAL)
ffffffff8127f6cf-ffffffff8127f72f: check_bytes_and_report.cold.93 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int check_bytes_and_report(struct kmem_cache *s, struct page *page, u8 *object, char *what, u8 *start, unsigned int value, unsigned int bytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:733
Inline: False
Direct callers:
  - mm/slub.c:check_object
  - mm/slub.c:check_object
  - mm/slub.c:check_object
  - mm/slub.c:check_object
  - mm/slub.c:check_object
  - mm/slub.c:check_object
```
**Symbols:**

```
ffffffff81293ac0-ffffffff81293b46: check_bytes_and_report (STB_LOCAL)
ffffffff8129b4ab-ffffffff8129b513: check_bytes_and_report.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int check_bytes_and_report(struct kmem_cache *s, struct page *page, u8 *object, char *what, u8 *start, unsigned int value, unsigned int bytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:733
Inline: False
Direct callers:
  - mm/slub.c:check_object
  - mm/slub.c:check_object
  - mm/slub.c:check_object
  - mm/slub.c:check_object
  - mm/slub.c:check_object
  - mm/slub.c:check_object
```
**Symbols:**

```
ffffffff812a3820-ffffffff812a38a6: check_bytes_and_report (STB_LOCAL)
ffffffff812ab36b-ffffffff812ab3d3: check_bytes_and_report.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int check_bytes_and_report(struct kmem_cache *s, struct page *page, u8 *object, char *what, u8 *start, unsigned int value, unsigned int bytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:779
Inline: False
Direct callers:
  - mm/slub.c:check_object
  - mm/slub.c:check_object
  - mm/slub.c:check_object
  - mm/slub.c:check_object
  - mm/slub.c:check_object
  - mm/slub.c:check_object
```
**Symbols:**

```
ffffffff812d7e10-ffffffff812d7eac: check_bytes_and_report (STB_LOCAL)
ffffffff812dfc15-ffffffff812dfca5: check_bytes_and_report.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int check_bytes_and_report(struct kmem_cache *s, struct page *page, u8 *object, char *what, u8 *start, unsigned int value, unsigned int bytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:774
Inline: False
Direct callers:
  - mm/slub.c:check_object
  - mm/slub.c:check_object
  - mm/slub.c:check_object
  - mm/slub.c:check_object
  - mm/slub.c:check_object
  - mm/slub.c:check_object
```
**Symbols:**

```
ffffffff812e57b0-ffffffff812e584c: check_bytes_and_report (STB_LOCAL)
ffffffff81be948c-ffffffff81be951c: check_bytes_and_report.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int check_bytes_and_report(struct kmem_cache *s, struct page *page, u8 *object, char *what, u8 *start, unsigned int value, unsigned int bytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:786
Inline: False
Direct callers:
  - mm/slub.c:check_object
  - mm/slub.c:check_object
  - mm/slub.c:check_object
  - mm/slub.c:check_object
  - mm/slub.c:check_object
  - mm/slub.c:check_object
```
**Symbols:**

```
ffffffff812ecf80-ffffffff812ed01c: check_bytes_and_report (STB_LOCAL)
ffffffff81bdb603-ffffffff81bdb68d: check_bytes_and_report.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int check_bytes_and_report(struct kmem_cache *s, struct page *page, u8 *object, char *what, u8 *start, unsigned int value, unsigned int bytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:907
Inline: False
Direct callers:
  - mm/slub.c:check_object
  - mm/slub.c:check_object
  - mm/slub.c:check_object
  - mm/slub.c:check_object
  - mm/slub.c:check_object
  - mm/slub.c:check_object
```
**Symbols:**

```
ffffffff81335250-ffffffff813352ec: check_bytes_and_report (STB_LOCAL)
ffffffff81cc14e8-ffffffff81cc1587: check_bytes_and_report.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int check_bytes_and_report(struct kmem_cache *s, struct slab *slab, u8 *object, char *what, u8 *start, unsigned int value, unsigned int bytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:954
Inline: False
Direct callers:
  - mm/slub.c:check_object
  - mm/slub.c:check_object
  - mm/slub.c:check_object
  - mm/slub.c:check_object
  - mm/slub.c:check_object
  - mm/slub.c:check_object
```
**Symbols:**

```
ffffffff813a6e70-ffffffff813a6f20: check_bytes_and_report (STB_LOCAL)
ffffffff81e73b7c-ffffffff81e73c13: check_bytes_and_report.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int check_bytes_and_report(struct kmem_cache *s, struct slab *slab, u8 *object, char *what, u8 *start, unsigned int value, unsigned int bytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff814282e0)
Location: mm/slub.c:1032
Inline: False
Direct callers:
  - mm/slub.c:check_object
  - mm/slub.c:check_object
  - mm/slub.c:check_object
  - mm/slub.c:check_object
  - mm/slub.c:check_object
  - mm/slub.c:check_object
  - mm/slub.c:check_object
```
**Symbols:**

```
ffffffff814282e0-ffffffff8142842b: check_bytes_and_report (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int check_bytes_and_report(struct kmem_cache *s, struct slab *slab, u8 *object, char *what, u8 *start, unsigned int value, unsigned int bytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8145d6a0)
Location: mm/slub.c:1053
Inline: False
Direct callers:
  - mm/slub.c:check_object
  - mm/slub.c:check_object
  - mm/slub.c:check_object
  - mm/slub.c:check_object
  - mm/slub.c:check_object
  - mm/slub.c:check_object
  - mm/slub.c:check_object
```
**Symbols:**

```
ffffffff8145d6a0-ffffffff8145d7eb: check_bytes_and_report (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int check_bytes_and_report(struct kmem_cache *s, struct slab *slab, u8 *object, char *what, u8 *start, unsigned int value, unsigned int bytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81457da0)
Location: mm/slub.c:1166
Inline: False
Direct callers:
  - mm/slub.c:check_object
  - mm/slub.c:check_object
  - mm/slub.c:check_object
  - mm/slub.c:check_object
  - mm/slub.c:check_object
  - mm/slub.c:check_object
  - mm/slub.c:check_object
```
**Symbols:**

```
ffffffff81457da0-ffffffff81457eeb: check_bytes_and_report (STB_LOCAL)
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
int check_bytes_and_report(struct kmem_cache *s, struct page *page, u8 *object, char *what, u8 *start, unsigned int value, unsigned int bytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffff800010344178)
Location: mm/slub.c:733
Inline: False
Direct callers:
  - mm/slub.c:check_object
  - mm/slub.c:check_object
  - mm/slub.c:check_object
  - mm/slub.c:check_object
  - mm/slub.c:check_object
  - mm/slub.c:check_object
```
**Symbols:**

```
ffff800010344178-ffff800010344274: check_bytes_and_report (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int check_bytes_and_report(struct kmem_cache *s, struct page *page, u8 *object, char *what, u8 *start, unsigned int value, unsigned int bytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (c05494f0)
Location: mm/slub.c:733
Inline: False
Direct callers:
  - mm/slub.c:check_object
  - mm/slub.c:check_object
  - mm/slub.c:check_object
  - mm/slub.c:check_object
  - mm/slub.c:check_object
  - mm/slub.c:check_object
```
**Symbols:**

```
c05494f0-c05495d4: check_bytes_and_report (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int check_bytes_and_report(struct kmem_cache *s, struct page *page, u8 *object, char *what, u8 *start, unsigned int value, unsigned int bytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (c000000000421bf0)
Location: mm/slub.c:733
Inline: False
Direct callers:
  - mm/slub.c:check_object
  - mm/slub.c:check_object
  - mm/slub.c:check_object
  - mm/slub.c:check_object
  - mm/slub.c:check_object
  - mm/slub.c:check_object
```
**Symbols:**

```
c000000000421bf0-c000000000421d2c: check_bytes_and_report (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int check_bytes_and_report(struct kmem_cache *s, struct page *page, u8 *object, char *what, u8 *start, unsigned int value, unsigned int bytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffe0002379fe)
Location: mm/slub.c:733
Inline: False
Direct callers:
  - mm/slub.c:check_object
  - mm/slub.c:check_object
  - mm/slub.c:check_object
  - mm/slub.c:check_object
  - mm/slub.c:check_object
  - mm/slub.c:check_object
```
**Symbols:**

```
ffffffe0002379fe-ffffffe000237af0: check_bytes_and_report (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int check_bytes_and_report(struct kmem_cache *s, struct page *page, u8 *object, char *what, u8 *start, unsigned int value, unsigned int bytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:733
Inline: False
Direct callers:
  - mm/slub.c:check_object
  - mm/slub.c:check_object
  - mm/slub.c:check_object
  - mm/slub.c:check_object
  - mm/slub.c:check_object
  - mm/slub.c:check_object
```
**Symbols:**

```
ffffffff8129be00-ffffffff8129be86: check_bytes_and_report (STB_LOCAL)
ffffffff812a394b-ffffffff812a39b3: check_bytes_and_report.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int check_bytes_and_report(struct kmem_cache *s, struct page *page, u8 *object, char *what, u8 *start, unsigned int value, unsigned int bytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:733
Inline: False
Direct callers:
  - mm/slub.c:check_object
  - mm/slub.c:check_object
  - mm/slub.c:check_object
  - mm/slub.c:check_object
  - mm/slub.c:check_object
  - mm/slub.c:check_object
```
**Symbols:**

```
ffffffff8128d9c0-ffffffff8128da46: check_bytes_and_report (STB_LOCAL)
ffffffff8129541b-ffffffff81295483: check_bytes_and_report.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int check_bytes_and_report(struct kmem_cache *s, struct page *page, u8 *object, char *what, u8 *start, unsigned int value, unsigned int bytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:733
Inline: False
Direct callers:
  - mm/slub.c:check_object
  - mm/slub.c:check_object
  - mm/slub.c:check_object
  - mm/slub.c:check_object
  - mm/slub.c:check_object
  - mm/slub.c:check_object
```
**Symbols:**

```
ffffffff81299c10-ffffffff81299c96: check_bytes_and_report (STB_LOCAL)
ffffffff812a175b-ffffffff812a17c3: check_bytes_and_report.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int check_bytes_and_report(struct kmem_cache *s, struct page *page, u8 *object, char *what, u8 *start, unsigned int value, unsigned int bytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:733
Inline: False
Direct callers:
  - mm/slub.c:check_object
  - mm/slub.c:check_object
  - mm/slub.c:check_object
  - mm/slub.c:check_object
  - mm/slub.c:check_object
  - mm/slub.c:check_object
```
**Symbols:**

```
ffffffff812a9a50-ffffffff812a9ad6: check_bytes_and_report (STB_LOCAL)
ffffffff812b190b-ffffffff812b1973: check_bytes_and_report.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct slab *slab</code>
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
