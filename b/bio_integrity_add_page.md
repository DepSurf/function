# Function: <code>bio_integrity_add_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int bio_integrity_add_page(struct bio *bio, struct page *page, unsigned int len, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio-integrity.c (ffffffff813e71c0)
Location: block/bio-integrity.c:135
Inline: False
Direct callers:
  - block/bio-integrity.c:bio_integrity_prep
```
**Symbols:**

```
ffffffff813e71c0-ffffffff813e725c: bio_integrity_add_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int bio_integrity_add_page(struct bio *bio, struct page *page, unsigned int len, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio-integrity.c (ffffffff8142d440)
Location: block/bio-integrity.c:135
Inline: False
Direct callers:
  - block/bio-integrity.c:bio_integrity_prep
```
**Symbols:**

```
ffffffff8142d440-ffffffff8142d4dc: bio_integrity_add_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int bio_integrity_add_page(struct bio *bio, struct page *page, unsigned int len, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio-integrity.c (ffffffff81447220)
Location: block/bio-integrity.c:135
Inline: False
Direct callers:
  - block/bio-integrity.c:bio_integrity_prep
```
**Symbols:**

```
ffffffff81447220-ffffffff814472bc: bio_integrity_add_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int bio_integrity_add_page(struct bio *bio, struct page *page, unsigned int len, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio-integrity.c (ffffffff81455660)
Location: block/bio-integrity.c:135
Inline: False
Direct callers:
  - block/bio-integrity.c:bio_integrity_prep
```
**Symbols:**

```
ffffffff81455660-ffffffff814556fc: bio_integrity_add_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int bio_integrity_add_page(struct bio *bio, struct page *page, unsigned int len, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio-integrity.c (ffffffff814812e0)
Location: block/bio-integrity.c:135
Inline: False
Direct callers:
  - block/bio-integrity.c:bio_integrity_prep
```
**Symbols:**

```
ffffffff814812e0-ffffffff81481375: bio_integrity_add_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int bio_integrity_add_page(struct bio *bio, struct page *page, unsigned int len, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/bio-integrity.c (0)
Location: block/bio-integrity.c:135
Inline: False
Direct callers:
  - block/bio-integrity.c:bio_integrity_prep
```
**Symbols:**

```
ffffffff814b688c-ffffffff814b68a6: bio_integrity_add_page.cold.12 (STB_LOCAL)
ffffffff814b5f00-ffffffff814b5f82: bio_integrity_add_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int bio_integrity_add_page(struct bio *bio, struct page *page, unsigned int len, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/bio-integrity.c (0)
Location: block/bio-integrity.c:135
Inline: False
Direct callers:
  - block/bio-integrity.c:bio_integrity_prep
```
**Symbols:**

```
ffffffff814ca098-ffffffff814ca0b2: bio_integrity_add_page.cold.12 (STB_LOCAL)
ffffffff814c97c0-ffffffff814c983e: bio_integrity_add_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int bio_integrity_add_page(struct bio *bio, struct page *page, unsigned int len, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/bio-integrity.c (0)
Location: block/bio-integrity.c:120
Inline: False
Direct callers:
  - block/bio-integrity.c:bio_integrity_prep
```
**Symbols:**

```
ffffffff814f8958-ffffffff814f8973: bio_integrity_add_page.cold (STB_LOCAL)
ffffffff814f7ed0-ffffffff814f7f52: bio_integrity_add_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int bio_integrity_add_page(struct bio *bio, struct page *page, unsigned int len, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/bio-integrity.c (0)
Location: block/bio-integrity.c:120
Inline: False
Direct callers:
  - block/bio-integrity.c:bio_integrity_prep
```
**Symbols:**

```
ffffffff815167e8-ffffffff81516803: bio_integrity_add_page.cold (STB_LOCAL)
ffffffff81515d60-ffffffff81515de2: bio_integrity_add_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int bio_integrity_add_page(struct bio *bio, struct page *page, unsigned int len, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/bio-integrity.c (0)
Location: block/bio-integrity.c:129
Inline: False
Direct callers:
  - block/bio-integrity.c:bio_integrity_prep
```
**Symbols:**

```
ffffffff81576f5b-ffffffff81576f76: bio_integrity_add_page.cold (STB_LOCAL)
ffffffff815764c0-ffffffff81576552: bio_integrity_add_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int bio_integrity_add_page(struct bio *bio, struct page *page, unsigned int len, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/bio-integrity.c (0)
Location: block/bio-integrity.c:129
Inline: False
Direct callers:
  - block/bio-integrity.c:bio_integrity_prep
```
**Symbols:**

```
ffffffff81bf3c62-ffffffff81bf3c7d: bio_integrity_add_page.cold (STB_LOCAL)
ffffffff81593400-ffffffff8159348f: bio_integrity_add_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int bio_integrity_add_page(struct bio *bio, struct page *page, unsigned int len, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/bio-integrity.c (0)
Location: block/bio-integrity.c:124
Inline: False
Direct callers:
  - block/bio-integrity.c:bio_integrity_prep
```
**Symbols:**

```
ffffffff81be5ac4-ffffffff81be5adf: bio_integrity_add_page.cold (STB_LOCAL)
ffffffff8159a210-ffffffff8159a2a6: bio_integrity_add_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int bio_integrity_add_page(struct bio *bio, struct page *page, unsigned int len, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/bio-integrity.c (0)
Location: block/bio-integrity.c:123
Inline: False
Direct callers:
  - block/bio-integrity.c:bio_integrity_prep
```
**Symbols:**

```
ffffffff81cd9fc0-ffffffff81cd9fdb: bio_integrity_add_page.cold (STB_LOCAL)
ffffffff816021a0-ffffffff81602236: bio_integrity_add_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int bio_integrity_add_page(struct bio *bio, struct page *page, unsigned int len, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/bio-integrity.c (0)
Location: block/bio-integrity.c:123
Inline: False
Direct callers:
  - block/bio-integrity.c:bio_integrity_prep
```
**Symbols:**

```
ffffffff81e8daaa-ffffffff81e8dac2: bio_integrity_add_page.cold (STB_LOCAL)
ffffffff816b4d40-ffffffff816b4de5: bio_integrity_add_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bio_integrity_add_page(struct bio *bio, struct page *page, unsigned int len, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio-integrity.c (ffffffff81774820)
Location: block/bio-integrity.c:123
Inline: False
Direct callers:
  - block/bio-integrity.c:bio_integrity_prep
```
**Symbols:**

```
ffffffff81774820-ffffffff817748d8: bio_integrity_add_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bio_integrity_add_page(struct bio *bio, struct page *page, unsigned int len, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio-integrity.c (ffffffff817b4490)
Location: block/bio-integrity.c:123
Inline: False
Direct callers:
  - block/bio-integrity.c:bio_integrity_prep
```
**Symbols:**

```
ffffffff817b4490-ffffffff817b45f0: bio_integrity_add_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bio_integrity_add_page(struct bio *bio, struct page *page, unsigned int len, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio-integrity.c (ffffffff817f86e0)
Location: block/bio-integrity.c:166
Inline: False
Direct callers:
  - block/bio-integrity.c:bio_integrity_prep
  - block/bio-integrity.c:bio_integrity_copy_user
```
**Symbols:**

```
ffffffff817f86e0-ffffffff817f882d: bio_integrity_add_page (STB_GLOBAL)
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
int bio_integrity_add_page(struct bio *bio, struct page *page, unsigned int len, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio-integrity.c (ffff80001061cec8)
Location: block/bio-integrity.c:120
Inline: False
Direct callers:
  - block/bio-integrity.c:bio_integrity_prep
```
**Symbols:**

```
ffff80001061cec8-ffff80001061cf9c: bio_integrity_add_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int bio_integrity_add_page(struct bio *bio, struct page *page, unsigned int len, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio-integrity.c (c07c4b28)
Location: block/bio-integrity.c:120
Inline: False
Direct callers:
  - block/bio-integrity.c:bio_integrity_prep
```
**Symbols:**

```
c07c4b28-c07c4be4: bio_integrity_add_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int bio_integrity_add_page(struct bio *bio, struct page *page, unsigned int len, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio-integrity.c (c0000000007bbaf0)
Location: block/bio-integrity.c:120
Inline: False
Direct callers:
  - block/bio-integrity.c:bio_integrity_prep
```
**Symbols:**

```
c0000000007bbaf0-c0000000007bbbe0: bio_integrity_add_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int bio_integrity_add_page(struct bio *bio, struct page *page, unsigned int len, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio-integrity.c (ffffffe00044fda2)
Location: block/bio-integrity.c:120
Inline: False
Direct callers:
  - block/bio-integrity.c:bio_integrity_prep
```
**Symbols:**

```
ffffffe00044fda2-ffffffe00044fe60: bio_integrity_add_page (STB_GLOBAL)
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
int bio_integrity_add_page(struct bio *bio, struct page *page, unsigned int len, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/bio-integrity.c (0)
Location: block/bio-integrity.c:120
Inline: False
Direct callers:
  - block/bio-integrity.c:bio_integrity_prep
  - drivers/nvme/host/core.c:nvme_submit_user_cmd
  - drivers/nvme/host/core.c:nvme_submit_user_cmd
```
**Symbols:**

```
ffffffff8150edc8-ffffffff8150ede3: bio_integrity_add_page.cold (STB_LOCAL)
ffffffff8150e340-ffffffff8150e3c2: bio_integrity_add_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int bio_integrity_add_page(struct bio *bio, struct page *page, unsigned int len, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/bio-integrity.c (0)
Location: block/bio-integrity.c:120
Inline: False
Direct callers:
  - block/bio-integrity.c:bio_integrity_prep
  - drivers/nvme/host/core.c:nvme_submit_user_cmd
  - drivers/nvme/host/core.c:nvme_submit_user_cmd
```
**Symbols:**

```
ffffffff814ff1f8-ffffffff814ff213: bio_integrity_add_page.cold (STB_LOCAL)
ffffffff814fe770-ffffffff814fe7f2: bio_integrity_add_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int bio_integrity_add_page(struct bio *bio, struct page *page, unsigned int len, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/bio-integrity.c (0)
Location: block/bio-integrity.c:120
Inline: False
Direct callers:
  - block/bio-integrity.c:bio_integrity_prep
```
**Symbols:**

```
ffffffff8150ae58-ffffffff8150ae73: bio_integrity_add_page.cold (STB_LOCAL)
ffffffff8150a3d0-ffffffff8150a452: bio_integrity_add_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int bio_integrity_add_page(struct bio *bio, struct page *page, unsigned int len, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/bio-integrity.c (0)
Location: block/bio-integrity.c:120
Inline: False
Direct callers:
  - block/bio-integrity.c:bio_integrity_prep
```
**Symbols:**

```
ffffffff815244f8-ffffffff81524513: bio_integrity_add_page.cold (STB_LOCAL)
ffffffff81523a40-ffffffff81523ac2: bio_integrity_add_page (STB_GLOBAL)
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
