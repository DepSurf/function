# Function: <code>dax_unlock_page</code>

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
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void dax_unlock_page(struct page *page, dax_entry_t cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff8130f1a0)
Location: fs/dax.c:430
Inline: False
```
**Symbols:**

```
ffffffff8130f1a0-ffffffff8130f21e: dax_unlock_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void dax_unlock_page(struct page *page, dax_entry_t cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff81336710)
Location: fs/dax.c:435
Inline: False
```
**Symbols:**

```
ffffffff81336710-ffffffff8133678e: dax_unlock_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void dax_unlock_page(struct page *page, dax_entry_t cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff8134a320)
Location: fs/dax.c:436
Inline: False
Direct callers:
  - mm/memory-failure.c:memory_failure
```
**Symbols:**

```
ffffffff8134a320-ffffffff8134a39e: dax_unlock_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void dax_unlock_page(struct page *page, dax_entry_t cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff8138fb00)
Location: fs/dax.c:436
Inline: False
Direct callers:
  - mm/memory-failure.c:memory_failure_dev_pagemap
  - mm/memory-failure.c:memory_failure_dev_pagemap
```
**Symbols:**

```
ffffffff8138fb00-ffffffff8138fb7c: dax_unlock_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void dax_unlock_page(struct page *page, dax_entry_t cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff813a10e0)
Location: fs/dax.c:436
Inline: False
Direct callers:
  - mm/memory-failure.c:memory_failure_dev_pagemap
  - mm/memory-failure.c:memory_failure_dev_pagemap
```
**Symbols:**

```
ffffffff813a10e0-ffffffff813a115c: dax_unlock_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void dax_unlock_page(struct page *page, dax_entry_t cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff813a8270)
Location: fs/dax.c:447
Inline: False
Direct callers:
  - mm/memory-failure.c:memory_failure_dev_pagemap
  - mm/memory-failure.c:memory_failure_dev_pagemap
```
**Symbols:**

```
ffffffff813a8270-ffffffff813a82ec: dax_unlock_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void dax_unlock_page(struct page *page, dax_entry_t cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff813f79b0)
Location: fs/dax.c:447
Inline: False
Direct callers:
  - mm/memory-failure.c:memory_failure_dev_pagemap
  - mm/memory-failure.c:memory_failure_dev_pagemap
```
**Symbols:**

```
ffffffff813f79b0-ffffffff813f7a2c: dax_unlock_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void dax_unlock_page(struct page *page, dax_entry_t cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff8146a7f0)
Location: fs/dax.c:447
Inline: False
Direct callers:
  - mm/memory-failure.c:memory_failure_dev_pagemap
  - mm/memory-failure.c:memory_failure_dev_pagemap
  - mm/memory-failure.c:memory_failure_dev_pagemap
```
**Symbols:**

```
ffffffff8146a7f0-ffffffff8146a881: dax_unlock_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void dax_unlock_page(struct page *page, dax_entry_t cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff814fb2d0)
Location: fs/dax.c:484
Inline: False
Direct callers:
  - mm/memory-failure.c:memory_failure_dev_pagemap
  - mm/memory-failure.c:memory_failure_dev_pagemap
  - mm/memory-failure.c:memory_failure_dev_pagemap
```
**Symbols:**

```
ffffffff814fb2d0-ffffffff814fb361: dax_unlock_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void dax_unlock_page(struct page *page, dax_entry_t cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff81532720)
Location: fs/dax.c:484
Inline: False
Direct callers:
  - mm/memory-failure.c:memory_failure_dev_pagemap
  - mm/memory-failure.c:memory_failure_dev_pagemap
  - mm/memory-failure.c:memory_failure_dev_pagemap
```
**Symbols:**

```
ffffffff81532720-ffffffff815327b1: dax_unlock_page (STB_GLOBAL)
```
</details>
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
void dax_unlock_page(struct page *page, dax_entry_t cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffff80001040a730)
Location: fs/dax.c:436
Inline: False
```
**Symbols:**

```
ffff80001040a730-ffff80001040a7c4: dax_unlock_page (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void dax_unlock_page(struct page *page, dax_entry_t cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (c000000000517240)
Location: fs/dax.c:436
Inline: False
Direct callers:
  - mm/memory-failure.c:memory_failure
```
**Symbols:**

```
c000000000517240-c0000000005172e8: dax_unlock_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void dax_unlock_page(struct page *page, dax_entry_t cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffe0002b478a)
Location: fs/dax.c:436
Inline: False
```
**Symbols:**

```
ffffffe0002b478a-ffffffe0002b47f0: dax_unlock_page (STB_GLOBAL)
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
void dax_unlock_page(struct page *page, dax_entry_t cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff81342900)
Location: fs/dax.c:436
Inline: False
Direct callers:
  - mm/memory-failure.c:memory_failure
```
**Symbols:**

```
ffffffff81342900-ffffffff8134297e: dax_unlock_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void dax_unlock_page(struct page *page, dax_entry_t cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff813335e0)
Location: fs/dax.c:436
Inline: False
Direct callers:
  - mm/memory-failure.c:memory_failure
```
**Symbols:**

```
ffffffff813335e0-ffffffff8133365e: dax_unlock_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void dax_unlock_page(struct page *page, dax_entry_t cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff813403d0)
Location: fs/dax.c:436
Inline: False
Direct callers:
  - mm/memory-failure.c:memory_failure
```
**Symbols:**

```
ffffffff813403d0-ffffffff8134044e: dax_unlock_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void dax_unlock_page(struct page *page, dax_entry_t cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff813536d0)
Location: fs/dax.c:436
Inline: False
Direct callers:
  - mm/memory-failure.c:memory_failure
```
**Symbols:**

```
ffffffff813536d0-ffffffff8135374e: dax_unlock_page (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
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
