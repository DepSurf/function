# Function: <code>wake_up_page_bit</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void wake_up_page_bit(struct page *page, int bit_nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811af2e0)
Location: mm/filemap.c:791
Inline: False
Direct callers:
  - mm/filemap.c:end_page_writeback
  - mm/filemap.c:unlock_page
```
**Symbols:**

```
ffffffff811af2e0-ffffffff811af39d: wake_up_page_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void wake_up_page_bit(struct page *page, int bit_nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811b6220)
Location: mm/filemap.c:912
Inline: False
Direct callers:
  - mm/filemap.c:end_page_writeback
  - mm/filemap.c:unlock_page
```
**Symbols:**

```
ffffffff811b6220-ffffffff811b62dd: wake_up_page_bit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void wake_up_page_bit(struct page *page, int bit_nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811ca4f0)
Location: mm/filemap.c:1013
Inline: False
Direct callers:
  - mm/filemap.c:end_page_writeback
  - mm/filemap.c:unlock_page
```
**Symbols:**

```
ffffffff811ca4f0-ffffffff811ca5ec: wake_up_page_bit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void wake_up_page_bit(struct page *page, int bit_nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811eb5a0)
Location: mm/filemap.c:1013
Inline: False
Direct callers:
  - mm/filemap.c:end_page_writeback
  - mm/filemap.c:unlock_page
```
**Symbols:**

```
ffffffff811eb5a0-ffffffff811eb69e: wake_up_page_bit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void wake_up_page_bit(struct page *page, int bit_nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811fc0e0)
Location: mm/filemap.c:998
Inline: False
Direct callers:
  - mm/filemap.c:end_page_writeback
  - mm/filemap.c:unlock_page
```
**Symbols:**

```
ffffffff811fc0e0-ffffffff811fc1de: wake_up_page_bit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void wake_up_page_bit(struct page *page, int bit_nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81213810)
Location: mm/filemap.c:1046
Inline: False
Direct callers:
  - mm/filemap.c:unlock_page
```
**Symbols:**

```
ffffffff81213810-ffffffff81213908: wake_up_page_bit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void wake_up_page_bit(struct page *page, int bit_nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81220fe0)
Location: mm/filemap.c:1055
Inline: False
Direct callers:
  - mm/filemap.c:unlock_page
```
**Symbols:**

```
ffffffff81220fe0-ffffffff812210d8: wake_up_page_bit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void wake_up_page_bit(struct page *page, int bit_nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8124ec00)
Location: mm/filemap.c:1030
Inline: False
Direct callers:
  - mm/filemap.c:end_page_writeback
  - mm/filemap.c:unlock_page
```
**Symbols:**

```
ffffffff8124ec00-ffffffff8124ecf6: wake_up_page_bit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void wake_up_page_bit(struct page *page, int bit_nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81258fc0)
Location: mm/filemap.c:1100
Inline: False
Direct callers:
  - mm/filemap.c:end_page_writeback
  - mm/filemap.c:unlock_page
```
**Symbols:**

```
ffffffff81258fc0-ffffffff812590b6: wake_up_page_bit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void wake_up_page_bit(struct page *page, int bit_nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8125d3e0)
Location: mm/filemap.c:1124
Inline: False
Direct callers:
  - mm/filemap.c:end_page_writeback
  - mm/filemap.c:end_page_private_2
  - mm/filemap.c:unlock_page
```
**Symbols:**

```
ffffffff8125d3e0-ffffffff8125d4d6: wake_up_page_bit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void wake_up_page_bit(struct page *page, int bit_nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81299330)
Location: mm/filemap.c:1179
Inline: False
Direct callers:
  - mm/filemap.c:end_page_writeback
  - mm/filemap.c:end_page_private_2
  - mm/filemap.c:unlock_page
```
**Symbols:**

```
ffffffff81299330-ffffffff81299426: wake_up_page_bit (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
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
void wake_up_page_bit(struct page *page, int bit_nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffff8000102af018)
Location: mm/filemap.c:1055
Inline: False
Direct callers:
  - mm/filemap.c:unlock_page
```
**Symbols:**

```
ffff8000102af018-ffff8000102af220: wake_up_page_bit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void wake_up_page_bit(struct page *page, int bit_nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (c04db0dc)
Location: mm/filemap.c:1055
Inline: False
Direct callers:
  - mm/filemap.c:unlock_page
```
**Symbols:**

```
c04db0dc-c04db238: wake_up_page_bit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void wake_up_page_bit(struct page *page, int bit_nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (c000000000362ab0)
Location: mm/filemap.c:1055
Inline: False
Direct callers:
  - mm/filemap.c:unlock_page
```
**Symbols:**

```
c000000000362ab0-c000000000362c50: wake_up_page_bit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void wake_up_page_bit(struct page *page, int bit_nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffe0001d4886)
Location: mm/filemap.c:1055
Inline: False
Direct callers:
  - mm/filemap.c:unlock_page
```
**Symbols:**

```
ffffffe0001d4886-ffffffe0001d4960: wake_up_page_bit (STB_LOCAL)
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
void wake_up_page_bit(struct page *page, int bit_nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81219630)
Location: mm/filemap.c:1055
Inline: False
Direct callers:
  - mm/filemap.c:unlock_page
```
**Symbols:**

```
ffffffff81219630-ffffffff81219728: wake_up_page_bit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void wake_up_page_bit(struct page *page, int bit_nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8120c840)
Location: mm/filemap.c:1055
Inline: False
Direct callers:
  - mm/filemap.c:unlock_page
```
**Symbols:**

```
ffffffff8120c840-ffffffff8120c938: wake_up_page_bit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void wake_up_page_bit(struct page *page, int bit_nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff812173d0)
Location: mm/filemap.c:1055
Inline: False
Direct callers:
  - mm/filemap.c:unlock_page
```
**Symbols:**

```
ffffffff812173d0-ffffffff812174c8: wake_up_page_bit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void wake_up_page_bit(struct page *page, int bit_nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81226480)
Location: mm/filemap.c:1055
Inline: False
Direct callers:
  - mm/filemap.c:unlock_page
```
**Symbols:**

```
ffffffff81226480-ffffffff81226578: wake_up_page_bit (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
