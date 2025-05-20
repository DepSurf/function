# Function: <code>send_all_trees</code>

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
In lib/zlib_deflate/deftree.c (ffffffff8140d585)
Location: lib/zlib_deflate/deftree.c:760
Inline: True
Inline callers:
  - lib/zlib_deflate/deftree.c:zlib_tr_flush_block
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
In lib/zlib_deflate/deftree.c (ffffffff81455296)
Location: lib/zlib_deflate/deftree.c:760
Inline: True
Inline callers:
  - lib/zlib_deflate/deftree.c:zlib_tr_flush_block
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
In lib/zlib_deflate/deftree.c (ffffffff81473c56)
Location: lib/zlib_deflate/deftree.c:760
Inline: True
Inline callers:
  - lib/zlib_deflate/deftree.c:zlib_tr_flush_block
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
In lib/zlib_deflate/deftree.c (ffffffff81478f42)
Location: lib/zlib_deflate/deftree.c:760
Inline: True
Inline callers:
  - lib/zlib_deflate/deftree.c:zlib_tr_flush_block
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
In lib/zlib_deflate/deftree.c (ffffffff814a62e2)
Location: lib/zlib_deflate/deftree.c:760
Inline: True
Inline callers:
  - lib/zlib_deflate/deftree.c:zlib_tr_flush_block
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
In lib/zlib_deflate/deftree.c (ffffffff814db771)
Location: lib/zlib_deflate/deftree.c:760
Inline: True
Inline callers:
  - lib/zlib_deflate/deftree.c:zlib_tr_flush_block
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
In lib/zlib_deflate/deftree.c (ffffffff814f01e1)
Location: lib/zlib_deflate/deftree.c:760
Inline: True
Inline callers:
  - lib/zlib_deflate/deftree.c:zlib_tr_flush_block
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
In lib/zlib_deflate/deftree.c (ffffffff8151cf50)
Location: lib/zlib_deflate/deftree.c:760
Inline: True
Inline callers:
  - lib/zlib_deflate/deftree.c:zlib_tr_flush_block
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
In lib/zlib_deflate/deftree.c (ffffffff8153dde0)
Location: lib/zlib_deflate/deftree.c:706
Inline: True
Inline callers:
  - lib/zlib_deflate/deftree.c:zlib_tr_flush_block
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void send_all_trees(deflate_state *s, int lcodes, int dcodes, int blcodes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zlib_deflate/deftree.c (ffffffff815a1110)
Location: lib/zlib_deflate/deftree.c:706
Inline: False
Direct callers:
  - lib/zlib_deflate/deftree.c:zlib_tr_flush_block
```
**Symbols:**

```
ffffffff815a1110-ffffffff815a135a: send_all_trees (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void send_all_trees(deflate_state *s, int lcodes, int dcodes, int blcodes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zlib_deflate/deftree.c (ffffffff815bcb50)
Location: lib/zlib_deflate/deftree.c:706
Inline: False
Direct callers:
  - lib/zlib_deflate/deftree.c:zlib_tr_flush_block
```
**Symbols:**

```
ffffffff815bcb50-ffffffff815bce02: send_all_trees (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void send_all_trees(deflate_state *s, int lcodes, int dcodes, int blcodes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zlib_deflate/deftree.c (ffffffff815c7930)
Location: lib/zlib_deflate/deftree.c:706
Inline: False
Direct callers:
  - lib/zlib_deflate/deftree.c:zlib_tr_flush_block
```
**Symbols:**

```
ffffffff815c7930-ffffffff815c7b90: send_all_trees (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void send_all_trees(deflate_state *s, int lcodes, int dcodes, int blcodes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zlib_deflate/deftree.c (0)
Location: lib/zlib_deflate/deftree.c:706
Inline: False
Direct callers:
  - lib/zlib_deflate/deftree.c:zlib_tr_flush_block
```
**Symbols:**

```
ffffffff81630c20-ffffffff816310d5: send_all_trees (STB_LOCAL)
ffffffff81cdc847-ffffffff81cdca50: send_all_trees.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void send_all_trees(deflate_state *s, int lcodes, int dcodes, int blcodes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zlib_deflate/deftree.c (0)
Location: lib/zlib_deflate/deftree.c:706
Inline: False
Direct callers:
  - lib/zlib_deflate/deftree.c:zlib_tr_flush_block
```
**Symbols:**

```
ffffffff81702700-ffffffff81702bc1: send_all_trees (STB_LOCAL)
ffffffff81e94fd8-ffffffff81e951d5: send_all_trees.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void send_all_trees(deflate_state *s, int lcodes, int dcodes, int blcodes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zlib_deflate/deftree.c (0)
Location: lib/zlib_deflate/deftree.c:706
Inline: False
Direct callers:
  - lib/zlib_deflate/deftree.c:zlib_tr_flush_block
```
**Symbols:**

```
ffffffff817f5230-ffffffff817f56f1: send_all_trees (STB_LOCAL)
ffffffff8207a051-ffffffff8207a24e: send_all_trees.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void send_all_trees(deflate_state *s, int lcodes, int dcodes, int blcodes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zlib_deflate/deftree.c (0)
Location: lib/zlib_deflate/deftree.c:706
Inline: False
Direct callers:
  - lib/zlib_deflate/deftree.c:zlib_tr_flush_block
```
**Symbols:**

```
ffffffff81835660-ffffffff81835b14: send_all_trees (STB_LOCAL)
ffffffff820fa7c5-ffffffff820fa9df: send_all_trees.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void send_all_trees(deflate_state *s, int lcodes, int dcodes, int blcodes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zlib_deflate/deftree.c (0)
Location: lib/zlib_deflate/deftree.c:706
Inline: False
Direct callers:
  - lib/zlib_deflate/deftree.c:zlib_tr_flush_block
```
**Symbols:**

```
ffffffff81887220-ffffffff818876d4: send_all_trees (STB_LOCAL)
ffffffff821d8932-ffffffff821d8b4c: send_all_trees.cold (STB_LOCAL)
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
In lib/zlib_deflate/deftree.c (ffff80001064a4a4)
Location: lib/zlib_deflate/deftree.c:706
Inline: True
Inline callers:
  - lib/zlib_deflate/deftree.c:zlib_tr_flush_block
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
In lib/zlib_deflate/deftree.c (c07f1044)
Location: lib/zlib_deflate/deftree.c:706
Inline: True
Inline callers:
  - lib/zlib_deflate/deftree.c:zlib_tr_flush_block
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
In lib/zlib_deflate/deftree.c (c0000000007f8118)
Location: lib/zlib_deflate/deftree.c:706
Inline: True
Inline callers:
  - lib/zlib_deflate/deftree.c:zlib_tr_flush_block
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
In lib/zlib_deflate/deftree.c (ffffffe000476344)
Location: lib/zlib_deflate/deftree.c:706
Inline: True
Inline callers:
  - lib/zlib_deflate/deftree.c:zlib_tr_flush_block
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
In lib/zlib_deflate/deftree.c (ffffffff815363c0)
Location: lib/zlib_deflate/deftree.c:706
Inline: True
Inline callers:
  - lib/zlib_deflate/deftree.c:zlib_tr_flush_block
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
In lib/zlib_deflate/deftree.c (ffffffff815266a0)
Location: lib/zlib_deflate/deftree.c:706
Inline: True
Inline callers:
  - lib/zlib_deflate/deftree.c:zlib_tr_flush_block
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
In lib/zlib_deflate/deftree.c (ffffffff81532100)
Location: lib/zlib_deflate/deftree.c:706
Inline: True
Inline callers:
  - lib/zlib_deflate/deftree.c:zlib_tr_flush_block
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
In lib/zlib_deflate/deftree.c (ffffffff8154bf30)
Location: lib/zlib_deflate/deftree.c:706
Inline: True
Inline callers:
  - lib/zlib_deflate/deftree.c:zlib_tr_flush_block
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
