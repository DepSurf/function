# Function: <code>fix_fullness_group</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
enum fullness_group fix_fullness_group(struct size_class *class, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff81205380)
Location: mm/zsmalloc.c:714
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_malloc
```
**Symbols:**

```
ffffffff81205380-ffffffff8120541d: fix_fullness_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
enum fullness_group fix_fullness_group(struct size_class *class, struct zspage *zspage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff8122a450)
Location: mm/zsmalloc.c:800
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_malloc
```
**Symbols:**

```
ffffffff8122a450-ffffffff8122a524: fix_fullness_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
enum fullness_group fix_fullness_group(struct size_class *class, struct zspage *zspage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff8123c9a0)
Location: mm/zsmalloc.c:800
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_malloc
```
**Symbols:**

```
ffffffff8123c9a0-ffffffff8123ca74: fix_fullness_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
enum fullness_group fix_fullness_group(struct size_class *class, struct zspage *zspage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff812486a0)
Location: mm/zsmalloc.c:793
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_malloc
```
**Symbols:**

```
ffffffff812486a0-ffffffff81248781: fix_fullness_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
enum fullness_group fix_fullness_group(struct size_class *class, struct zspage *zspage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff81268870)
Location: mm/zsmalloc.c:797
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_malloc
```
**Symbols:**

```
ffffffff81268870-ffffffff81268951: fix_fullness_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
enum fullness_group fix_fullness_group(struct size_class *class, struct zspage *zspage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff8128d100)
Location: mm/zsmalloc.c:779
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_malloc
```
**Symbols:**

```
ffffffff8128d100-ffffffff8128d1e1: fix_fullness_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
enum fullness_group fix_fullness_group(struct size_class *class, struct zspage *zspage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff812a2200)
Location: mm/zsmalloc.c:779
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_malloc
```
**Symbols:**

```
ffffffff812a2200-ffffffff812a22e1: fix_fullness_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
enum fullness_group fix_fullness_group(struct size_class *class, struct zspage *zspage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff812bd350)
Location: mm/zsmalloc.c:769
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_malloc
```
**Symbols:**

```
ffffffff812bd350-ffffffff812bd42f: fix_fullness_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
enum fullness_group fix_fullness_group(struct size_class *class, struct zspage *zspage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff812cf240)
Location: mm/zsmalloc.c:766
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_malloc
```
**Symbols:**

```
ffffffff812cf240-ffffffff812cf31f: fix_fullness_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
enum fullness_group fix_fullness_group(struct size_class *class, struct zspage *zspage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff81306060)
Location: mm/zsmalloc.c:766
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_malloc
```
**Symbols:**

```
ffffffff81306060-ffffffff8130612e: fix_fullness_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
enum fullness_group fix_fullness_group(struct size_class *class, struct zspage *zspage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff81311dc0)
Location: mm/zsmalloc.c:759
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_malloc
```
**Symbols:**

```
ffffffff81311dc0-ffffffff81311e8e: fix_fullness_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
enum fullness_group fix_fullness_group(struct size_class *class, struct zspage *zspage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff81317c80)
Location: mm/zsmalloc.c:759
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_malloc
```
**Symbols:**

```
ffffffff81317c80-ffffffff81317d4e: fix_fullness_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
enum fullness_group fix_fullness_group(struct size_class *class, struct zspage *zspage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff813632f0)
Location: mm/zsmalloc.c:759
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_malloc
```
**Symbols:**

```
ffffffff813632f0-ffffffff813633be: fix_fullness_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
enum fullness_group fix_fullness_group(struct size_class *class, struct zspage *zspage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff813e0020)
Location: mm/zsmalloc.c:759
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_malloc
```
**Symbols:**

```
ffffffff813e0020-ffffffff813e00f6: fix_fullness_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
enum fullness_group fix_fullness_group(struct size_class *class, struct zspage *zspage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff81466f30)
Location: mm/zsmalloc.c:807
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_malloc
```
**Symbols:**

```
ffffffff81466f30-ffffffff81467006: fix_fullness_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int fix_fullness_group(struct size_class *class, struct zspage *zspage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff8149c470)
Location: mm/zsmalloc.c:722
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_malloc
```
**Symbols:**

```
ffffffff8149c470-ffffffff8149c5ec: fix_fullness_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int fix_fullness_group(struct size_class *class, struct zspage *zspage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff814cbb90)
Location: mm/zsmalloc.c:722
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_malloc
```
**Symbols:**

```
ffffffff814cbb90-ffffffff814cbd0c: fix_fullness_group (STB_LOCAL)
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
enum fullness_group fix_fullness_group(struct size_class *class, struct zspage *zspage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffff800010373fc8)
Location: mm/zsmalloc.c:766
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_malloc
```
**Symbols:**

```
ffff800010373fc8-ffff8000103740c8: fix_fullness_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
enum fullness_group fix_fullness_group(struct size_class *class, struct zspage *zspage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (c0560960)
Location: mm/zsmalloc.c:766
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_malloc
```
**Symbols:**

```
c0560960-c0560a44: fix_fullness_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
enum fullness_group fix_fullness_group(struct size_class *class, struct zspage *zspage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (c000000000465a00)
Location: mm/zsmalloc.c:766
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_malloc
```
**Symbols:**

```
c000000000465a00-c000000000465b50: fix_fullness_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
enum fullness_group fix_fullness_group(struct size_class *class, struct zspage *zspage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffe00024cd2c)
Location: mm/zsmalloc.c:766
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_malloc
```
**Symbols:**

```
ffffffe00024cd2c-ffffffe00024ce0a: fix_fullness_group (STB_LOCAL)
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
enum fullness_group fix_fullness_group(struct size_class *class, struct zspage *zspage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff812c7820)
Location: mm/zsmalloc.c:766
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_malloc
```
**Symbols:**

```
ffffffff812c7820-ffffffff812c78ff: fix_fullness_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
enum fullness_group fix_fullness_group(struct size_class *class, struct zspage *zspage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff812b8860)
Location: mm/zsmalloc.c:766
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_malloc
```
**Symbols:**

```
ffffffff812b8860-ffffffff812b893f: fix_fullness_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
enum fullness_group fix_fullness_group(struct size_class *class, struct zspage *zspage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff812c5630)
Location: mm/zsmalloc.c:766
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_malloc
```
**Symbols:**

```
ffffffff812c5630-ffffffff812c570f: fix_fullness_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
enum fullness_group fix_fullness_group(struct size_class *class, struct zspage *zspage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff812d6130)
Location: mm/zsmalloc.c:766
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_malloc
```
**Symbols:**

```
ffffffff812d6130-ffffffff812d620f: fix_fullness_group (STB_LOCAL)
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
<code>struct zspage *zspage</code>
</li>
<li>
<b>Param removed. </b>
<code>struct page *page</code>
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>enum fullness_group</code> ➡️ <code>int</code>
</li>
</ul>
</details>
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
