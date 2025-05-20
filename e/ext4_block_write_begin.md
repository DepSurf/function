# Function: <code>ext4_block_write_begin</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ext4_block_write_begin(struct page *page, loff_t pos, unsigned int len, get_block_t *get_block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81297600)
Location: fs/ext4/inode.c:914
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_da_write_begin
```
**Symbols:**

```
ffffffff81297600-ffffffff81297ace: ext4_block_write_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ext4_block_write_begin(struct page *page, loff_t pos, unsigned int len, get_block_t *get_block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff812c4c30)
Location: fs/ext4/inode.c:1079
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_write_begin
```
**Symbols:**

```
ffffffff812c4c30-ffffffff812c513c: ext4_block_write_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ext4_block_write_begin(struct page *page, loff_t pos, unsigned int len, get_block_t *get_block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff812da2e0)
Location: fs/ext4/inode.c:1093
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_write_begin
```
**Symbols:**

```
ffffffff812da2e0-ffffffff812da7e7: ext4_block_write_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ext4_block_write_begin(struct page *page, loff_t pos, unsigned int len, get_block_t *get_block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff812fe190)
Location: fs/ext4/inode.c:1143
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_write_begin
```
**Symbols:**

```
ffffffff812fe190-ffffffff812fe5f3: ext4_block_write_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ext4_block_write_begin(struct page *page, loff_t pos, unsigned int len, get_block_t *get_block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81322980)
Location: fs/ext4/inode.c:1153
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_write_begin
```
**Symbols:**

```
ffffffff81322980-ffffffff81322dd7: ext4_block_write_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ext4_block_write_begin(struct page *page, loff_t pos, unsigned int len, get_block_t *get_block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81350340)
Location: fs/ext4/inode.c:1154
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_write_begin
```
**Symbols:**

```
ffffffff81350340-ffffffff813507cd: ext4_block_write_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ext4_block_write_begin(struct page *page, loff_t pos, unsigned int len, get_block_t *get_block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813686a0)
Location: fs/ext4/inode.c:1154
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_write_begin
```
**Symbols:**

```
ffffffff813686a0-ffffffff81368b5d: ext4_block_write_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int ext4_block_write_begin(struct page *page, loff_t pos, unsigned int len, get_block_t *get_block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (0)
Location: fs/ext4/inode.c:1162
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_write_begin
```
**Symbols:**

```
ffffffff813917f0-ffffffff81391d03: ext4_block_write_begin (STB_LOCAL)
ffffffff8139c6fc-ffffffff8139c72b: ext4_block_write_begin.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ext4_block_write_begin(struct page *page, loff_t pos, unsigned int len, get_block_t *get_block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813aa180)
Location: fs/ext4/inode.c:1171
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_write_begin
```
**Symbols:**

```
ffffffff813aa180-ffffffff813aa697: ext4_block_write_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ext4_block_write_begin(struct page *page, loff_t pos, unsigned int len, get_block_t *get_block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813f6c20)
Location: fs/ext4/inode.c:1020
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_write_begin
```
**Symbols:**

```
ffffffff813f6c20-ffffffff813f7166: ext4_block_write_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ext4_block_write_begin(struct page *page, loff_t pos, unsigned int len, get_block_t *get_block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81409460)
Location: fs/ext4/inode.c:1037
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_write_begin
```
**Symbols:**

```
ffffffff81409460-ffffffff81409867: ext4_block_write_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ext4_block_write_begin(struct page *page, loff_t pos, unsigned int len, get_block_t *get_block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8140f600)
Location: fs/ext4/inode.c:1038
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_write_begin
```
**Symbols:**

```
ffffffff8140f600-ffffffff8140fa06: ext4_block_write_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ext4_block_write_begin(struct page *page, loff_t pos, unsigned int len, get_block_t *get_block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (0)
Location: fs/ext4/inode.c:1040
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_write_begin
```
**Symbols:**

```
ffffffff814625f0-ffffffff81462ad2: ext4_block_write_begin (STB_LOCAL)
ffffffff81cca9cc-ffffffff81cca9f0: ext4_block_write_begin.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ext4_block_write_begin(struct page *page, loff_t pos, unsigned int len, get_block_t *get_block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (0)
Location: fs/ext4/inode.c:1053
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_write_begin
```
**Symbols:**

```
ffffffff814e1790-ffffffff814e1d85: ext4_block_write_begin (STB_LOCAL)
ffffffff81e7d80a-ffffffff81e7d83b: ext4_block_write_begin.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int ext4_block_write_begin(struct page *page, loff_t pos, unsigned int len, get_block_t *get_block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (0)
Location: fs/ext4/inode.c:1059
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_write_begin
```
**Symbols:**

```
ffffffff8157aab0-ffffffff8157b0b4: ext4_block_write_begin (STB_LOCAL)
ffffffff8206dd7d-ffffffff8206ddaf: ext4_block_write_begin.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int ext4_block_write_begin(struct folio *folio, loff_t pos, unsigned int len, get_block_t *get_block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (0)
Location: fs/ext4/inode.c:1002
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_write_begin
```
**Symbols:**

```
ffffffff815b0b90-ffffffff815b10c7: ext4_block_write_begin (STB_LOCAL)
ffffffff820ed773-ffffffff820ed7a7: ext4_block_write_begin.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int ext4_block_write_begin(struct folio *folio, loff_t pos, unsigned int len, get_block_t *get_block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (0)
Location: fs/ext4/inode.c:1016
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_write_begin
```
**Symbols:**

```
ffffffff815e9a30-ffffffff815e9f96: ext4_block_write_begin (STB_LOCAL)
ffffffff821ca886-ffffffff821ca8df: ext4_block_write_begin.cold (STB_LOCAL)
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
int ext4_block_write_begin(struct page *page, loff_t pos, unsigned int len, get_block_t *get_block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffff80001047f5a8)
Location: fs/ext4/inode.c:1171
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
```
**Symbols:**

```
ffff80001047f5a8-ffff80001047faf0: ext4_block_write_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ext4_block_write_begin(struct page *page, loff_t pos, unsigned int len, get_block_t *get_block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (c063ff3c)
Location: fs/ext4/inode.c:1171
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_write_begin
```
**Symbols:**

```
c063ff3c-c0640470: ext4_block_write_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ext4_block_write_begin(struct page *page, loff_t pos, unsigned int len, get_block_t *get_block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (c0000000005a4250)
Location: fs/ext4/inode.c:1171
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
```
**Symbols:**

```
c0000000005a4250-c0000000005a4828: ext4_block_write_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ext4_block_write_begin(struct page *page, loff_t pos, unsigned int len, get_block_t *get_block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffe000307e4a)
Location: fs/ext4/inode.c:1171
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
```
**Symbols:**

```
ffffffe000307e4a-ffffffe0003082b0: ext4_block_write_begin (STB_LOCAL)
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
int ext4_block_write_begin(struct page *page, loff_t pos, unsigned int len, get_block_t *get_block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813a2760)
Location: fs/ext4/inode.c:1171
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_write_begin
```
**Symbols:**

```
ffffffff813a2760-ffffffff813a2c77: ext4_block_write_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ext4_block_write_begin(struct page *page, loff_t pos, unsigned int len, get_block_t *get_block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813931f0)
Location: fs/ext4/inode.c:1171
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_write_begin
```
**Symbols:**

```
ffffffff813931f0-ffffffff81393707: ext4_block_write_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ext4_block_write_begin(struct page *page, loff_t pos, unsigned int len, get_block_t *get_block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8139ffc0)
Location: fs/ext4/inode.c:1171
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_write_begin
```
**Symbols:**

```
ffffffff8139ffc0-ffffffff813a04d7: ext4_block_write_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ext4_block_write_begin(struct page *page, loff_t pos, unsigned int len, get_block_t *get_block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813b3fe0)
Location: fs/ext4/inode.c:1171
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_write_begin
```
**Symbols:**

```
ffffffff813b3fe0-ffffffff813b44fb: ext4_block_write_begin (STB_LOCAL)
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct folio *folio</code>
</li>
<li>
<b>Param removed. </b>
<code>struct page *page</code>
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
