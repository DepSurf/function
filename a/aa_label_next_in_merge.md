# Function: <code>aa_label_next_in_merge</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct aa_profile *aa_label_next_in_merge(struct label_it *I, struct aa_label *a, struct aa_label *b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff8138ac80)
Location: security/apparmor/label.c:923
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_merge
```
**Symbols:**

```
ffffffff8138ac80-ffffffff8138ae76: aa_label_next_in_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct aa_profile *aa_label_next_in_merge(struct label_it *I, struct aa_label *a, struct aa_label *b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff813c5960)
Location: security/apparmor/label.c:923
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_find_merge
```
**Symbols:**

```
ffffffff813c5960-ffffffff813c5b56: aa_label_next_in_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct aa_profile *aa_label_next_in_merge(struct label_it *I, struct aa_label *a, struct aa_label *b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff813dcfa0)
Location: security/apparmor/label.c:939
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_find_merge
```
**Symbols:**

```
ffffffff813dcfa0-ffffffff813dd196: aa_label_next_in_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct aa_profile *aa_label_next_in_merge(struct label_it *I, struct aa_label *a, struct aa_label *b);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff813ed7b0)
Location: security/apparmor/label.c:937
Inline: True
Direct callers:
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_find_merge
```
**Symbols:**

```
ffffffff813ed7b0-ffffffff813ed86d: aa_label_next_in_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct aa_profile *aa_label_next_in_merge(struct label_it *I, struct aa_label *a, struct aa_label *b);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff814151c0)
Location: security/apparmor/label.c:937
Inline: True
Direct callers:
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_find_merge
```
**Symbols:**

```
ffffffff814151c0-ffffffff8141527d: aa_label_next_in_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct aa_profile *aa_label_next_in_merge(struct label_it *I, struct aa_label *a, struct aa_label *b);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff814475e0)
Location: security/apparmor/label.c:936
Inline: True
Direct callers:
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_find_merge
```
**Symbols:**

```
ffffffff814475e0-ffffffff8144769a: aa_label_next_in_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct aa_profile *aa_label_next_in_merge(struct label_it *I, struct aa_label *a, struct aa_label *b);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81464510)
Location: security/apparmor/label.c:937
Inline: True
Direct callers:
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_find_merge
```
**Symbols:**

```
ffffffff81464510-ffffffff814645ca: aa_label_next_in_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct aa_profile *aa_label_next_in_merge(struct label_it *I, struct aa_label *a, struct aa_label *b);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81491bd0)
Location: security/apparmor/label.c:933
Inline: True
Direct callers:
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_find_merge
```
**Symbols:**

```
ffffffff81491bd0-ffffffff81491c59: aa_label_next_in_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct aa_profile *aa_label_next_in_merge(struct label_it *I, struct aa_label *a, struct aa_label *b);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff814abb00)
Location: security/apparmor/label.c:960
Inline: True
Direct callers:
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_find_merge
```
**Symbols:**

```
ffffffff814abb00-ffffffff814abb89: aa_label_next_in_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct aa_profile *aa_label_next_in_merge(struct label_it *I, struct aa_label *a, struct aa_label *b);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81508666)
Location: security/apparmor/label.c:960
Inline: True
Inline callers:
  - security/apparmor/label.c:__label_find_merge
Direct callers:
  - security/apparmor/label.c:label_merge_insert
```
**Symbols:**

```
ffffffff8150a780-ffffffff8150a845: aa_label_next_in_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct aa_profile *aa_label_next_in_merge(struct label_it *I, struct aa_label *a, struct aa_label *b);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81525626)
Location: security/apparmor/label.c:960
Inline: True
Inline callers:
  - security/apparmor/label.c:__label_find_merge
Direct callers:
  - security/apparmor/label.c:label_merge_insert
```
**Symbols:**

```
ffffffff81527600-ffffffff815276c5: aa_label_next_in_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct aa_profile *aa_label_next_in_merge(struct label_it *I, struct aa_label *a, struct aa_label *b);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff8152d786)
Location: security/apparmor/label.c:960
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_find_merge
Direct callers:
  - security/apparmor/label.c:label_merge_insert
```
**Symbols:**

```
ffffffff8152d140-ffffffff8152d205: aa_label_next_in_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct aa_profile *aa_label_next_in_merge(struct label_it *I, struct aa_label *a, struct aa_label *b);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff8158bb76)
Location: security/apparmor/label.c:960
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_find_merge
Direct callers:
  - security/apparmor/label.c:label_merge_insert
```
**Symbols:**

```
ffffffff8158b530-ffffffff8158b5f5: aa_label_next_in_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct aa_profile *aa_label_next_in_merge(struct label_it *I, struct aa_label *a, struct aa_label *b);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff8162d199)
Location: security/apparmor/label.c:962
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_find_merge
Direct callers:
  - security/apparmor/label.c:label_merge_insert
```
**Symbols:**

```
ffffffff8162cab0-ffffffff8162cb9d: aa_label_next_in_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct aa_profile *aa_label_next_in_merge(struct label_it *I, struct aa_label *a, struct aa_label *b);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff816e1c79)
Location: security/apparmor/label.c:962
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_find_merge
Direct callers:
  - security/apparmor/label.c:label_merge_insert
```
**Symbols:**

```
ffffffff816e1570-ffffffff816e165d: aa_label_next_in_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct aa_profile *aa_label_next_in_merge(struct label_it *I, struct aa_label *a, struct aa_label *b);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff8171b274)
Location: security/apparmor/label.c:962
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_find_merge
Direct callers:
  - security/apparmor/label.c:label_merge_insert
```
**Symbols:**

```
ffffffff8171ab70-ffffffff8171ac5d: aa_label_next_in_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct aa_profile *aa_label_next_in_merge(struct label_it *I, struct aa_label *a, struct aa_label *b);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81759cc4)
Location: security/apparmor/label.c:969
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_find_merge
Direct callers:
  - security/apparmor/label.c:label_merge_insert
```
**Symbols:**

```
ffffffff81759620-ffffffff8175970f: aa_label_next_in_merge (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
struct aa_profile *aa_label_next_in_merge(struct label_it *I, struct aa_label *a, struct aa_label *b);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffff8000105a2ef8)
Location: security/apparmor/label.c:960
Inline: True
Direct callers:
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_find_merge
```
**Symbols:**

```
ffff8000105a2ef8-ffff8000105a2fbc: aa_label_next_in_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct aa_profile *aa_label_next_in_merge(struct label_it *I, struct aa_label *a, struct aa_label *b);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (c0753100)
Location: security/apparmor/label.c:960
Inline: True
Direct callers:
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_find_merge
```
**Symbols:**

```
c0753100-c07531a4: aa_label_next_in_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct aa_profile *aa_label_next_in_merge(struct label_it *I, struct aa_label *a, struct aa_label *b);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (c00000000071dfc0)
Location: security/apparmor/label.c:960
Inline: True
Direct callers:
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_find_merge
```
**Symbols:**

```
c00000000071dfc0-c00000000071e10c: aa_label_next_in_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct aa_profile *aa_label_next_in_merge(struct label_it *I, struct aa_label *a, struct aa_label *b);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffe0003ed410)
Location: security/apparmor/label.c:960
Inline: True
Direct callers:
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_find_merge
```
**Symbols:**

```
ffffffe0003ed410-ffffffe0003ed4b6: aa_label_next_in_merge (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
struct aa_profile *aa_label_next_in_merge(struct label_it *I, struct aa_label *a, struct aa_label *b);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff814a40e0)
Location: security/apparmor/label.c:960
Inline: True
Direct callers:
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_find_merge
```
**Symbols:**

```
ffffffff814a40e0-ffffffff814a4169: aa_label_next_in_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct aa_profile *aa_label_next_in_merge(struct label_it *I, struct aa_label *a, struct aa_label *b);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81494b00)
Location: security/apparmor/label.c:960
Inline: True
Direct callers:
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_find_merge
```
**Symbols:**

```
ffffffff81494b00-ffffffff81494b89: aa_label_next_in_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct aa_profile *aa_label_next_in_merge(struct label_it *I, struct aa_label *a, struct aa_label *b);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff814a0180)
Location: security/apparmor/label.c:960
Inline: True
Direct callers:
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_find_merge
```
**Symbols:**

```
ffffffff814a0180-ffffffff814a0209: aa_label_next_in_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct aa_profile *aa_label_next_in_merge(struct label_it *I, struct aa_label *a, struct aa_label *b);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff814b8800)
Location: security/apparmor/label.c:960
Inline: True
Direct callers:
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_find_merge
```
**Symbols:**

```
ffffffff814b8800-ffffffff814b8889: aa_label_next_in_merge (STB_GLOBAL)
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
