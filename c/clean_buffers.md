# Function: <code>clean_buffers</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void clean_buffers(struct page *page, unsigned int first_unmapped);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/mpage.c (ffffffff8124d6e0)
Location: fs/mpage.c:440
Inline: True
Direct callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
```
**Symbols:**

```
ffffffff8124d6e0-ffffffff8124d735: clean_buffers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void clean_buffers(struct page *page, unsigned int first_unmapped);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/mpage.c (ffffffff81275e30)
Location: fs/mpage.c:444
Inline: True
Direct callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
```
**Symbols:**

```
ffffffff81275e30-ffffffff81275e94: clean_buffers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void clean_buffers(struct page *page, unsigned int first_unmapped);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/mpage.c (ffffffff81289b10)
Location: fs/mpage.c:444
Inline: True
Direct callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
```
**Symbols:**

```
ffffffff81289b10-ffffffff81289b74: clean_buffers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void clean_buffers(struct page *page, unsigned int first_unmapped);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/mpage.c (ffffffff81296810)
Location: fs/mpage.c:446
Inline: True
Direct callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
```
**Symbols:**

```
ffffffff81296810-ffffffff81296873: clean_buffers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void clean_buffers(struct page *page, unsigned int first_unmapped);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/mpage.c (ffffffff812b9a70)
Location: fs/mpage.c:447
Inline: True
Direct callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:clean_page_buffers
```
**Symbols:**

```
ffffffff812b9a70-ffffffff812b9ad3: clean_buffers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void clean_buffers(struct page *page, unsigned int first_unmapped);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/mpage.c (ffffffff812e25e0)
Location: fs/mpage.c:447
Inline: True
Direct callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:clean_page_buffers
```
**Symbols:**

```
ffffffff812e25e0-ffffffff812e2642: clean_buffers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void clean_buffers(struct page *page, unsigned int first_unmapped);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/mpage.c (ffffffff812f7240)
Location: fs/mpage.c:461
Inline: True
Direct callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:clean_page_buffers
```
**Symbols:**

```
ffffffff812f7240-ffffffff812f72a2: clean_buffers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void clean_buffers(struct page *page, unsigned int first_unmapped);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/mpage.c (ffffffff81317860)
Location: fs/mpage.c:461
Inline: True
Direct callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:clean_page_buffers
```
**Symbols:**

```
ffffffff81317860-ffffffff813178c2: clean_buffers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void clean_buffers(struct page *page, unsigned int first_unmapped);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/mpage.c (ffffffff8132a6e0)
Location: fs/mpage.c:461
Inline: True
Direct callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:clean_page_buffers
```
**Symbols:**

```
ffffffff8132a6e0-ffffffff8132a742: clean_buffers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void clean_buffers(struct page *page, unsigned int first_unmapped);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/mpage.c (ffffffff813643a0)
Location: fs/mpage.c:445
Inline: True
Direct callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:clean_page_buffers
```
**Symbols:**

```
ffffffff813643a0-ffffffff81364402: clean_buffers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void clean_buffers(struct page *page, unsigned int first_unmapped);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/mpage.c (ffffffff813713a0)
Location: fs/mpage.c:445
Inline: True
Direct callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:clean_page_buffers
```
**Symbols:**

```
ffffffff813713a0-ffffffff81371402: clean_buffers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void clean_buffers(struct page *page, unsigned int first_unmapped);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/mpage.c (ffffffff81377d50)
Location: fs/mpage.c:443
Inline: True
Direct callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:clean_page_buffers
```
**Symbols:**

```
ffffffff81377d50-ffffffff81377db2: clean_buffers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void clean_buffers(struct page *page, unsigned int first_unmapped);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/mpage.c (ffffffff813c4410)
Location: fs/mpage.c:443
Inline: True
Direct callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:clean_page_buffers
```
**Symbols:**

```
ffffffff813c4410-ffffffff813c4472: clean_buffers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void clean_buffers(struct page *page, unsigned int first_unmapped);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/mpage.c (ffffffff8144be80)
Location: fs/mpage.c:412
Inline: True
Direct callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:clean_page_buffers
```
**Symbols:**

```
ffffffff8144be80-ffffffff8144bf5f: clean_buffers (STB_LOCAL)
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
In fs/mpage.c (ffffffff814daa0c)
Location: fs/mpage.c:413
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:clean_page_buffers
  - fs/mpage.c:clean_page_buffers
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
In fs/mpage.c (ffffffff8150efdc)
Location: fs/mpage.c:434
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:clean_page_buffers
  - fs/mpage.c:clean_page_buffers
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
In fs/mpage.c (ffffffff81543820)
Location: fs/mpage.c:433
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
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
void clean_buffers(struct page *page, unsigned int first_unmapped);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/mpage.c (ffff8000103e5e90)
Location: fs/mpage.c:461
Inline: True
Direct callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:clean_page_buffers
```
**Symbols:**

```
ffff8000103e5e90-ffff8000103e5f48: clean_buffers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void clean_buffers(struct page *page, unsigned int first_unmapped);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/mpage.c (c05bd9ac)
Location: fs/mpage.c:461
Inline: True
Direct callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:clean_page_buffers
```
**Symbols:**

```
c05bd9ac-c05bda58: clean_buffers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void clean_buffers(struct page *page, unsigned int first_unmapped);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/mpage.c (c0000000004ebff0)
Location: fs/mpage.c:461
Inline: True
Direct callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:clean_page_buffers
```
**Symbols:**

```
c0000000004ebff0-c0000000004ec0b0: clean_buffers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void clean_buffers(struct page *page, unsigned int first_unmapped);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/mpage.c (ffffffe00029b2c8)
Location: fs/mpage.c:461
Inline: True
Direct callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:clean_page_buffers
```
**Symbols:**

```
ffffffe00029b2c8-ffffffe00029b352: clean_buffers (STB_LOCAL)
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
void clean_buffers(struct page *page, unsigned int first_unmapped);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/mpage.c (ffffffff81322cc0)
Location: fs/mpage.c:461
Inline: True
Direct callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:clean_page_buffers
```
**Symbols:**

```
ffffffff81322cc0-ffffffff81322d22: clean_buffers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void clean_buffers(struct page *page, unsigned int first_unmapped);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/mpage.c (ffffffff81313860)
Location: fs/mpage.c:461
Inline: True
Direct callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:clean_page_buffers
```
**Symbols:**

```
ffffffff81313860-ffffffff813138c2: clean_buffers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void clean_buffers(struct page *page, unsigned int first_unmapped);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/mpage.c (ffffffff81320790)
Location: fs/mpage.c:461
Inline: True
Direct callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:clean_page_buffers
```
**Symbols:**

```
ffffffff81320790-ffffffff813207f2: clean_buffers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void clean_buffers(struct page *page, unsigned int first_unmapped);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/mpage.c (ffffffff813324b0)
Location: fs/mpage.c:461
Inline: True
Direct callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:clean_page_buffers
```
**Symbols:**

```
ffffffff813324b0-ffffffff81332512: clean_buffers (STB_LOCAL)
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
