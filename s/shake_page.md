# Function: <code>shake_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void shake_page(struct page *p, int access);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff81202060)
Location: mm/memory-failure.c:221
Inline: True
Direct callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:soft_offline_page
```
**Symbols:**

```
ffffffff81202060-ffffffff812020e1: shake_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void shake_page(struct page *p, int access);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff81225da0)
Location: mm/memory-failure.c:220
Inline: False
Direct callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:memory_failure
```
**Symbols:**

```
ffffffff81225da0-ffffffff81225e53: shake_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void shake_page(struct page *p, int access);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff81238380)
Location: mm/memory-failure.c:220
Inline: False
Direct callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:memory_failure
```
**Symbols:**

```
ffffffff81238380-ffffffff81238434: shake_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void shake_page(struct page *p, int access);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff812442f0)
Location: mm/memory-failure.c:220
Inline: True
Direct callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:memory_failure
```
**Symbols:**

```
ffffffff812442f0-ffffffff812443a6: shake_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void shake_page(struct page *p, int access);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff81264170)
Location: mm/memory-failure.c:220
Inline: True
Direct callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:memory_failure
```
**Symbols:**

```
ffffffff81264170-ffffffff81264226: shake_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void shake_page(struct page *p, int access);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff812883d0)
Location: mm/memory-failure.c:244
Inline: True
Direct callers:
  - mm/memory-failure.c:soft_offline_page
```
**Symbols:**

```
ffffffff812883d0-ffffffff81288486: shake_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void shake_page(struct page *p, int access);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff8129d3a0)
Location: mm/memory-failure.c:245
Inline: True
Direct callers:
  - mm/memory-failure.c:soft_offline_page
```
**Symbols:**

```
ffffffff8129d3a0-ffffffff8129d456: shake_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void shake_page(struct page *p, int access);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff812b8490)
Location: mm/memory-failure.c:242
Inline: True
Direct callers:
  - mm/memory-failure.c:soft_offline_page
```
**Symbols:**

```
ffffffff812b8490-ffffffff812b8546: shake_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void shake_page(struct page *p, int access);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff812ca370)
Location: mm/memory-failure.c:241
Inline: True
Direct callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:memory_failure
```
**Symbols:**

```
ffffffff812ca370-ffffffff812ca426: shake_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void shake_page(struct page *p, int access);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memory-failure.c (ffffffff81301e7b)
Location: mm/memory-failure.c:242
Inline: True
Inline callers:
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:memory_failure
Direct callers:
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:memory_failure
```
**Symbols:**

```
ffffffff813000a0-ffffffff81300148: shake_page.part.0 (STB_LOCAL)
ffffffff81300150-ffffffff8130017d: shake_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void shake_page(struct page *p, int access);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memory-failure.c (ffffffff8130e85b)
Location: mm/memory-failure.c:269
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:get_any_page
Direct callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:get_any_page
```
**Symbols:**

```
ffffffff8130c3d0-ffffffff8130c440: shake_page.part.0 (STB_LOCAL)
ffffffff8130c440-ffffffff8130c46d: shake_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void shake_page(struct page *p, int access);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memory-failure.c (ffffffff81314d05)
Location: mm/memory-failure.c:273
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:get_any_page
Direct callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:get_any_page
```
**Symbols:**

```
ffffffff81312b30-ffffffff81312ba0: shake_page.part.0 (STB_LOCAL)
ffffffff81312ba0-ffffffff81312bcd: shake_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void shake_page(struct page *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff8135e600)
Location: mm/memory-failure.c:287
Inline: True
Direct callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:hwpoison_user_mappings
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:get_any_page
```
**Symbols:**

```
ffffffff8135e600-ffffffff8135e65f: shake_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void shake_page(struct page *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff813d98b0)
Location: mm/memory-failure.c:282
Inline: True
Direct callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:hwpoison_user_mappings
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:get_any_page
```
**Symbols:**

```
ffffffff813d98b0-ffffffff813d9968: shake_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void shake_page(struct page *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff8145fc40)
Location: mm/memory-failure.c:304
Inline: True
Direct callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:hwpoison_user_mappings
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:get_any_page
```
**Symbols:**

```
ffffffff8145fc40-ffffffff8145fcf8: shake_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void shake_page(struct page *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff81496350)
Location: mm/memory-failure.c:362
Inline: True
Direct callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:hwpoison_user_mappings
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:get_any_page
```
**Symbols:**

```
ffffffff81496350-ffffffff81496408: shake_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void shake_page(struct page *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff814c8723)
Location: mm/memory-failure.c:361
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:get_any_page
Direct callers:
  - mm/memory-failure.c:hwpoison_user_mappings
```
**Symbols:**

```
ffffffff814c4c30-ffffffff814c4ca2: shake_page (STB_GLOBAL)
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
void shake_page(struct page *p, int access);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffff80001036dc68)
Location: mm/memory-failure.c:241
Inline: True
Direct callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:memory_failure
```
**Symbols:**

```
ffff80001036dc68-ffff80001036dd50: shake_page (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void shake_page(struct page *p, int access);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (c00000000045e390)
Location: mm/memory-failure.c:241
Inline: True
Direct callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:memory_failure
```
**Symbols:**

```
c00000000045e390-c00000000045e4f8: shake_page (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void shake_page(struct page *p, int access);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff812c2950)
Location: mm/memory-failure.c:241
Inline: True
Direct callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:memory_failure
```
**Symbols:**

```
ffffffff812c2950-ffffffff812c2a06: shake_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void shake_page(struct page *p, int access);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff812b39a0)
Location: mm/memory-failure.c:241
Inline: True
Direct callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:memory_failure
```
**Symbols:**

```
ffffffff812b39a0-ffffffff812b3a56: shake_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void shake_page(struct page *p, int access);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff812c0760)
Location: mm/memory-failure.c:241
Inline: True
Direct callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:memory_failure
```
**Symbols:**

```
ffffffff812c0760-ffffffff812c0816: shake_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void shake_page(struct page *p, int access);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff812d1220)
Location: mm/memory-failure.c:241
Inline: True
Direct callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:memory_failure
```
**Symbols:**

```
ffffffff812d1220-ffffffff812d12d6: shake_page (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int access</code>
</li>
</ul>
</details>
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
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
