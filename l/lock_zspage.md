# Function: <code>lock_zspage</code>

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
void lock_zspage(struct zspage *zspage);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff8122b8b0)
Location: mm/zsmalloc.c:952
Inline: False
Direct callers:
  - mm/zsmalloc.c:async_free_zspage
```
**Symbols:**

```
ffffffff8122b8b0-ffffffff8122b8ff: lock_zspage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void lock_zspage(struct zspage *zspage);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff8123de10)
Location: mm/zsmalloc.c:952
Inline: False
Direct callers:
  - mm/zsmalloc.c:async_free_zspage
```
**Symbols:**

```
ffffffff8123de10-ffffffff8123de5f: lock_zspage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void lock_zspage(struct zspage *zspage);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff812497c0)
Location: mm/zsmalloc.c:944
Inline: False
Direct callers:
  - mm/zsmalloc.c:async_free_zspage
```
**Symbols:**

```
ffffffff812497c0-ffffffff8124980f: lock_zspage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void lock_zspage(struct zspage *zspage);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff81269a20)
Location: mm/zsmalloc.c:948
Inline: False
Direct callers:
  - mm/zsmalloc.c:async_free_zspage
```
**Symbols:**

```
ffffffff81269a20-ffffffff81269a6f: lock_zspage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void lock_zspage(struct zspage *zspage);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff8128e3b0)
Location: mm/zsmalloc.c:931
Inline: False
Direct callers:
  - mm/zsmalloc.c:async_free_zspage
```
**Symbols:**

```
ffffffff8128e3b0-ffffffff8128e400: lock_zspage (STB_GLOBAL)
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
In mm/zsmalloc.c (ffffffff812a3061)
Location: mm/zsmalloc.c:1808
Inline: True
Inline callers:
  - mm/zsmalloc.c:async_free_zspage
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
In mm/zsmalloc.c (ffffffff812be38f)
Location: mm/zsmalloc.c:1798
Inline: True
Inline callers:
  - mm/zsmalloc.c:async_free_zspage
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
In mm/zsmalloc.c (ffffffff812d027f)
Location: mm/zsmalloc.c:1795
Inline: True
Inline callers:
  - mm/zsmalloc.c:async_free_zspage
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
In mm/zsmalloc.c (ffffffff8130682f)
Location: mm/zsmalloc.c:1797
Inline: True
Inline callers:
  - mm/zsmalloc.c:async_free_zspage
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
In mm/zsmalloc.c (ffffffff8131256f)
Location: mm/zsmalloc.c:1746
Inline: True
Inline callers:
  - mm/zsmalloc.c:async_free_zspage
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
In mm/zsmalloc.c (ffffffff813185ef)
Location: mm/zsmalloc.c:1745
Inline: True
Inline callers:
  - mm/zsmalloc.c:async_free_zspage
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
In mm/zsmalloc.c (ffffffff81364b22)
Location: mm/zsmalloc.c:1744
Inline: True
Inline callers:
  - mm/zsmalloc.c:async_free_zspage
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void lock_zspage(struct zspage *zspage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff813e2850)
Location: mm/zsmalloc.c:1719
Inline: False
Direct callers:
  - mm/zsmalloc.c:async_free_zspage
```
**Symbols:**

```
ffffffff813e2850-ffffffff813e2c3c: lock_zspage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void lock_zspage(struct zspage *zspage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff81469db0)
Location: mm/zsmalloc.c:1927
Inline: False
Direct callers:
  - mm/zsmalloc.c:async_free_zspage
```
**Symbols:**

```
ffffffff81469db0-ffffffff8146a19c: lock_zspage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void lock_zspage(struct zspage *zspage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff8149efb0)
Location: mm/zsmalloc.c:1692
Inline: False
Direct callers:
  - mm/zsmalloc.c:async_free_zspage
```
**Symbols:**

```
ffffffff8149efb0-ffffffff8149f39c: lock_zspage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void lock_zspage(struct zspage *zspage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff814ce710)
Location: mm/zsmalloc.c:1674
Inline: False
Direct callers:
  - mm/zsmalloc.c:async_free_zspage
```
**Symbols:**

```
ffffffff814ce710-ffffffff814ceae4: lock_zspage (STB_LOCAL)
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
In mm/zsmalloc.c (ffff800010374ee8)
Location: mm/zsmalloc.c:1795
Inline: True
Inline callers:
  - mm/zsmalloc.c:async_free_zspage
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
In mm/zsmalloc.c (c0561224)
Location: mm/zsmalloc.c:1795
Inline: True
Inline callers:
  - mm/zsmalloc.c:async_free_zspage
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
In mm/zsmalloc.c (c0000000004675d4)
Location: mm/zsmalloc.c:1795
Inline: True
Inline callers:
  - mm/zsmalloc.c:async_free_zspage
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
In mm/zsmalloc.c (ffffffe00024dd9a)
Location: mm/zsmalloc.c:1795
Inline: True
Inline callers:
  - mm/zsmalloc.c:async_free_zspage
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
In mm/zsmalloc.c (ffffffff812c885f)
Location: mm/zsmalloc.c:1795
Inline: True
Inline callers:
  - mm/zsmalloc.c:async_free_zspage
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
In mm/zsmalloc.c (ffffffff812b989f)
Location: mm/zsmalloc.c:1795
Inline: True
Inline callers:
  - mm/zsmalloc.c:async_free_zspage
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
In mm/zsmalloc.c (ffffffff812c666f)
Location: mm/zsmalloc.c:1795
Inline: True
Inline callers:
  - mm/zsmalloc.c:async_free_zspage
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
In mm/zsmalloc.c (ffffffff812d7edd)
Location: mm/zsmalloc.c:1795
Inline: True
Inline callers:
  - mm/zsmalloc.c:async_free_zspage
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
