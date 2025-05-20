# Function: <code>count_inuse</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int count_inuse(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff811e7140)
Location: mm/slub.c:4076
Inline: False
```
**Symbols:**

```
ffffffff811e7140-ffffffff811e714f: count_inuse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int count_inuse(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81206210)
Location: mm/slub.c:4303
Inline: False
```
**Symbols:**

```
ffffffff81206210-ffffffff8120621f: count_inuse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int count_inuse(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81218230)
Location: mm/slub.c:4272
Inline: False
```
**Symbols:**

```
ffffffff81218230-ffffffff8121823f: count_inuse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int count_inuse(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81223db0)
Location: mm/slub.c:4314
Inline: False
```
**Symbols:**

```
ffffffff81223db0-ffffffff81223dbf: count_inuse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int count_inuse(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8123f400)
Location: mm/slub.c:4330
Inline: False
```
**Symbols:**

```
ffffffff8123f400-ffffffff8123f40f: count_inuse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int count_inuse(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81262d70)
Location: mm/slub.c:4332
Inline: False
```
**Symbols:**

```
ffffffff81262d70-ffffffff81262d7f: count_inuse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int count_inuse(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81277600)
Location: mm/slub.c:4384
Inline: False
```
**Symbols:**

```
ffffffff81277600-ffffffff8127760f: count_inuse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int count_inuse(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81292e60)
Location: mm/slub.c:4375
Inline: False
```
**Symbols:**

```
ffffffff81292e60-ffffffff81292e6f: count_inuse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int count_inuse(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812a2be0)
Location: mm/slub.c:4393
Inline: False
```
**Symbols:**

```
ffffffff812a2be0-ffffffff812a2bef: count_inuse (STB_LOCAL)
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
In mm/slub.c (ffffffff812de083)
Location: mm/slub.c:4472
Inline: True
Inline callers:
  - mm/slub.c:show_slab_objects
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
In mm/slub.c (ffffffff812e8f93)
Location: mm/slub.c:4521
Inline: True
Inline callers:
  - mm/slub.c:show_slab_objects
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
In mm/slub.c (ffffffff812f10be)
Location: mm/slub.c:4602
Inline: True
Inline callers:
  - mm/slub.c:show_slab_objects
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
In mm/slub.c (ffffffff81339891)
Location: mm/slub.c:4958
Inline: True
Inline callers:
  - mm/slub.c:show_slab_objects
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
In mm/slub.c (ffffffff813ab536)
Location: mm/slub.c:4990
Inline: True
Inline callers:
  - mm/slub.c:show_slab_objects
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
In mm/slub.c (ffffffff81427638)
Location: mm/slub.c:5111
Inline: True
Inline callers:
  - mm/slub.c:show_slab_objects
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8145c5f8)
Location: mm/slub.c:5126
Inline: True
Inline callers:
  - mm/slub.c:show_slab_objects
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8145d858)
Location: mm/slub.c:5737
Inline: True
Inline callers:
  - mm/slub.c:show_slab_objects
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
int count_inuse(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffff800010342c78)
Location: mm/slub.c:4393
Inline: False
```
**Symbols:**

```
ffff800010342c78-ffff800010342ca0: count_inuse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int count_inuse(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (c0548384)
Location: mm/slub.c:4393
Inline: False
```
**Symbols:**

```
c0548384-c05483a0: count_inuse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int count_inuse(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (c000000000420290)
Location: mm/slub.c:4393
Inline: False
```
**Symbols:**

```
c000000000420290-c0000000004202a0: count_inuse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int count_inuse(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffe000236924)
Location: mm/slub.c:4393
Inline: False
```
**Symbols:**

```
ffffffe000236924-ffffffe000236948: count_inuse (STB_LOCAL)
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
int count_inuse(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8129b1c0)
Location: mm/slub.c:4393
Inline: False
```
**Symbols:**

```
ffffffff8129b1c0-ffffffff8129b1cf: count_inuse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int count_inuse(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8128cd80)
Location: mm/slub.c:4393
Inline: False
```
**Symbols:**

```
ffffffff8128cd80-ffffffff8128cd8f: count_inuse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int count_inuse(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81298fd0)
Location: mm/slub.c:4393
Inline: False
```
**Symbols:**

```
ffffffff81298fd0-ffffffff81298fdf: count_inuse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int count_inuse(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812a8df0)
Location: mm/slub.c:4393
Inline: False
```
**Symbols:**

```
ffffffff812a8df0-ffffffff812a8dff: count_inuse (STB_LOCAL)
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
