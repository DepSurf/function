# Function: <code>ima_alloc_pages</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void *ima_alloc_pages(loff_t max_size, size_t *allocated_size, int last_warn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffff81397a50)
Location: security/integrity/ima/ima_crypto.c:124
Inline: False
Direct callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
**Symbols:**

```
ffffffff81397a50-ffffffff81397af1: ima_alloc_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void *ima_alloc_pages(loff_t max_size, size_t *allocated_size, int last_warn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffff813d3d40)
Location: security/integrity/ima/ima_crypto.c:124
Inline: False
Direct callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
```
**Symbols:**

```
ffffffff813d3d40-ffffffff813d3dd8: ima_alloc_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void *ima_alloc_pages(loff_t max_size, size_t *allocated_size, int last_warn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffff813eb780)
Location: security/integrity/ima/ima_crypto.c:124
Inline: False
Direct callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
```
**Symbols:**

```
ffffffff813eb780-ffffffff813eb818: ima_alloc_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void *ima_alloc_pages(loff_t max_size, size_t *allocated_size, int last_warn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffff813f7aa0)
Location: security/integrity/ima/ima_crypto.c:124
Inline: False
Direct callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
```
**Symbols:**

```
ffffffff813f7aa0-ffffffff813f7b38: ima_alloc_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void *ima_alloc_pages(loff_t max_size, size_t *allocated_size, int last_warn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffff8141fba0)
Location: security/integrity/ima/ima_crypto.c:119
Inline: False
Direct callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
```
**Symbols:**

```
ffffffff8141fba0-ffffffff8141fc38: ima_alloc_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *ima_alloc_pages(loff_t max_size, size_t *allocated_size, int last_warn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffff81452170)
Location: security/integrity/ima/ima_crypto.c:121
Inline: False
Direct callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
```
**Symbols:**

```
ffffffff81452170-ffffffff81452214: ima_alloc_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *ima_alloc_pages(loff_t max_size, size_t *allocated_size, int last_warn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffff8146f290)
Location: security/integrity/ima/ima_crypto.c:121
Inline: False
Direct callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
```
**Symbols:**

```
ffffffff8146f290-ffffffff8146f334: ima_alloc_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void *ima_alloc_pages(loff_t max_size, size_t *allocated_size, int last_warn);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffff8149d060)
Location: security/integrity/ima/ima_crypto.c:118
Inline: True
Direct callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
**Symbols:**

```
ffffffff8149d060-ffffffff8149d109: ima_alloc_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void *ima_alloc_pages(loff_t max_size, size_t *allocated_size, int last_warn);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffff814b73c0)
Location: security/integrity/ima/ima_crypto.c:118
Inline: True
Direct callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
**Symbols:**

```
ffffffff814b73c0-ffffffff814b7469: ima_alloc_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void *ima_alloc_pages(loff_t max_size, size_t *allocated_size, int last_warn);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffff81516a50)
Location: security/integrity/ima/ima_crypto.c:242
Inline: True
Direct callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
**Symbols:**

```
ffffffff81516a50-ffffffff81516aea: ima_alloc_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *ima_alloc_pages(loff_t max_size, size_t *allocated_size, int last_warn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffff815339a0)
Location: security/integrity/ima/ima_crypto.c:242
Inline: False
Direct callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
**Symbols:**

```
ffffffff815339a0-ffffffff81533a49: ima_alloc_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *ima_alloc_pages(loff_t max_size, size_t *allocated_size, int last_warn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffff8153c000)
Location: security/integrity/ima/ima_crypto.c:242
Inline: False
Direct callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
**Symbols:**

```
ffffffff8153c000-ffffffff8153c09c: ima_alloc_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void *ima_alloc_pages(loff_t max_size, size_t *allocated_size, int last_warn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_crypto.c (0)
Location: security/integrity/ima/ima_crypto.c:242
Inline: False
Direct callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
**Symbols:**

```
ffffffff8159acc0-ffffffff8159ad71: ima_alloc_pages (STB_LOCAL)
ffffffff81cd6e9a-ffffffff81cd6ebb: ima_alloc_pages.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void *ima_alloc_pages(loff_t max_size, size_t *allocated_size, int last_warn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_crypto.c (0)
Location: security/integrity/ima/ima_crypto.c:243
Inline: False
Direct callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
**Symbols:**

```
ffffffff8163fac0-ffffffff8163fb89: ima_alloc_pages (STB_LOCAL)
ffffffff81e8a0c2-ffffffff81e8a0e3: ima_alloc_pages.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void *ima_alloc_pages(loff_t max_size, size_t *allocated_size, int last_warn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_crypto.c (0)
Location: security/integrity/ima/ima_crypto.c:243
Inline: False
Direct callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
**Symbols:**

```
ffffffff816f78b0-ffffffff816f7979: ima_alloc_pages (STB_LOCAL)
ffffffff8207533c-ffffffff8207535d: ima_alloc_pages.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void *ima_alloc_pages(loff_t max_size, size_t *allocated_size, int last_warn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_crypto.c (0)
Location: security/integrity/ima/ima_crypto.c:243
Inline: False
Direct callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
**Symbols:**

```
ffffffff81731b30-ffffffff81731bf9: ima_alloc_pages (STB_LOCAL)
ffffffff820f4ea8-ffffffff820f4ec9: ima_alloc_pages.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void *ima_alloc_pages(loff_t max_size, size_t *allocated_size, int last_warn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_crypto.c (0)
Location: security/integrity/ima/ima_crypto.c:243
Inline: False
Direct callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
**Symbols:**

```
ffffffff81772550-ffffffff81772619: ima_alloc_pages (STB_LOCAL)
ffffffff821d2036-ffffffff821d2057: ima_alloc_pages.cold (STB_LOCAL)
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
void *ima_alloc_pages(loff_t max_size, size_t *allocated_size, int last_warn);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffff8000105af630)
Location: security/integrity/ima/ima_crypto.c:118
Inline: True
Direct callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
**Symbols:**

```
ffff8000105af630-ffff8000105af700: ima_alloc_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void *ima_alloc_pages(loff_t max_size, size_t *allocated_size, int last_warn);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (c075eec0)
Location: security/integrity/ima/ima_crypto.c:118
Inline: True
Direct callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
**Symbols:**

```
c075eec0-c075ef68: ima_alloc_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void *ima_alloc_pages(loff_t max_size, size_t *allocated_size, int last_warn);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (c00000000072ee60)
Location: security/integrity/ima/ima_crypto.c:118
Inline: True
Direct callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
**Symbols:**

```
c00000000072ee60-c00000000072efbc: ima_alloc_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void *ima_alloc_pages(loff_t max_size, size_t *allocated_size, int last_warn);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffe0003f731a)
Location: security/integrity/ima/ima_crypto.c:118
Inline: True
Direct callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
**Symbols:**

```
ffffffe0003f731a-ffffffe0003f73ea: ima_alloc_pages (STB_LOCAL)
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
void *ima_alloc_pages(loff_t max_size, size_t *allocated_size, int last_warn);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffff814af9a0)
Location: security/integrity/ima/ima_crypto.c:118
Inline: True
Direct callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
**Symbols:**

```
ffffffff814af9a0-ffffffff814afa49: ima_alloc_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void *ima_alloc_pages(loff_t max_size, size_t *allocated_size, int last_warn);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffff814a03c0)
Location: security/integrity/ima/ima_crypto.c:118
Inline: True
Direct callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
**Symbols:**

```
ffffffff814a03c0-ffffffff814a0469: ima_alloc_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void *ima_alloc_pages(loff_t max_size, size_t *allocated_size, int last_warn);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffff814aba30)
Location: security/integrity/ima/ima_crypto.c:118
Inline: True
Direct callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
**Symbols:**

```
ffffffff814aba30-ffffffff814abad9: ima_alloc_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void *ima_alloc_pages(loff_t max_size, size_t *allocated_size, int last_warn);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffff814c4480)
Location: security/integrity/ima/ima_crypto.c:118
Inline: True
Direct callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
**Symbols:**

```
ffffffff814c4480-ffffffff814c4529: ima_alloc_pages (STB_LOCAL)
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
