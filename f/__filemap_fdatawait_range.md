# Function: <code>__filemap_fdatawait_range</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __filemap_fdatawait_range(struct address_space *mapping, loff_t start_byte, loff_t end_byte);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8118ca00)
Location: mm/filemap.c:334
Inline: False
Direct callers:
  - mm/filemap.c:filemap_fdatawait_range
  - mm/filemap.c:filemap_fdatawait_keep_errors
```
**Symbols:**

```
ffffffff8118ca00-ffffffff8118cb5f: __filemap_fdatawait_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __filemap_fdatawait_range(struct address_space *mapping, loff_t start_byte, loff_t end_byte);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8119f9e0)
Location: mm/filemap.c:413
Inline: False
Direct callers:
  - mm/filemap.c:filemap_fdatawait_keep_errors
  - mm/filemap.c:filemap_fdatawait_range
```
**Symbols:**

```
ffffffff8119f9e0-ffffffff8119fb43: __filemap_fdatawait_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __filemap_fdatawait_range(struct address_space *mapping, loff_t start_byte, loff_t end_byte);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811afc20)
Location: mm/filemap.c:378
Inline: False
Direct callers:
  - mm/filemap.c:filemap_fdatawait_keep_errors
  - mm/filemap.c:filemap_fdatawait_range
```
**Symbols:**

```
ffffffff811afc20-ffffffff811afda8: __filemap_fdatawait_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __filemap_fdatawait_range(struct address_space *mapping, loff_t start_byte, loff_t end_byte);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811b6cc0)
Location: mm/filemap.c:414
Inline: False
Direct callers:
  - mm/filemap.c:file_write_and_wait_range
  - mm/filemap.c:filemap_fdatawait
```
**Symbols:**

```
ffffffff811b6cc0-ffffffff811b6e20: __filemap_fdatawait_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __filemap_fdatawait_range(struct address_space *mapping, loff_t start_byte, loff_t end_byte);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811cae40)
Location: mm/filemap.c:511
Inline: False
Direct callers:
  - mm/filemap.c:file_write_and_wait_range
  - mm/filemap.c:filemap_fdatawait_keep_errors
  - mm/filemap.c:file_fdatawait_range
```
**Symbols:**

```
ffffffff811cae40-ffffffff811caf97: __filemap_fdatawait_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __filemap_fdatawait_range(struct address_space *mapping, loff_t start_byte, loff_t end_byte);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811ec0a0)
Location: mm/filemap.c:511
Inline: False
Direct callers:
  - mm/filemap.c:file_write_and_wait_range
  - mm/filemap.c:filemap_fdatawait_keep_errors
  - mm/filemap.c:file_fdatawait_range
```
**Symbols:**

```
ffffffff811ec0a0-ffffffff811ec1f1: __filemap_fdatawait_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __filemap_fdatawait_range(struct address_space *mapping, loff_t start_byte, loff_t end_byte);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811fe400)
Location: mm/filemap.c:488
Inline: False
Direct callers:
  - mm/filemap.c:file_write_and_wait_range
  - mm/filemap.c:filemap_fdatawait_keep_errors
  - mm/filemap.c:file_fdatawait_range
```
**Symbols:**

```
ffffffff811fe400-ffffffff811fe555: __filemap_fdatawait_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __filemap_fdatawait_range(struct address_space *mapping, loff_t start_byte, loff_t end_byte);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81213530)
Location: mm/filemap.c:497
Inline: False
Direct callers:
  - mm/filemap.c:file_write_and_wait_range
  - mm/filemap.c:filemap_fdatawait_keep_errors
  - mm/filemap.c:file_fdatawait_range
  - mm/filemap.c:filemap_fdatawait_range_keep_errors
```
**Symbols:**

```
ffffffff81213530-ffffffff8121361e: __filemap_fdatawait_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __filemap_fdatawait_range(struct address_space *mapping, loff_t start_byte, loff_t end_byte);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81220cf0)
Location: mm/filemap.c:503
Inline: False
Direct callers:
  - mm/filemap.c:file_write_and_wait_range
  - mm/filemap.c:filemap_fdatawait_keep_errors
  - mm/filemap.c:file_fdatawait_range
  - mm/filemap.c:filemap_fdatawait_range_keep_errors
```
**Symbols:**

```
ffffffff81220cf0-ffffffff81220def: __filemap_fdatawait_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __filemap_fdatawait_range(struct address_space *mapping, loff_t start_byte, loff_t end_byte);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8124e750)
Location: mm/filemap.c:503
Inline: False
Direct callers:
  - mm/filemap.c:file_write_and_wait_range
  - mm/filemap.c:filemap_fdatawait_keep_errors
  - mm/filemap.c:file_fdatawait_range
  - mm/filemap.c:filemap_fdatawait_range_keep_errors
```
**Symbols:**

```
ffffffff8124e750-ffffffff8124e84d: __filemap_fdatawait_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __filemap_fdatawait_range(struct address_space *mapping, loff_t start_byte, loff_t end_byte);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81258c10)
Location: mm/filemap.c:504
Inline: False
Direct callers:
  - mm/filemap.c:file_write_and_wait_range
  - mm/filemap.c:filemap_fdatawait_keep_errors
  - mm/filemap.c:file_fdatawait_range
  - mm/filemap.c:filemap_fdatawait_range_keep_errors
```
**Symbols:**

```
ffffffff81258c10-ffffffff81258d0d: __filemap_fdatawait_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __filemap_fdatawait_range(struct address_space *mapping, loff_t start_byte, loff_t end_byte);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8125d0c0)
Location: mm/filemap.c:495
Inline: False
Direct callers:
  - mm/filemap.c:file_write_and_wait_range
  - mm/filemap.c:filemap_fdatawait_keep_errors
  - mm/filemap.c:file_fdatawait_range
  - mm/filemap.c:filemap_fdatawait_range_keep_errors
```
**Symbols:**

```
ffffffff8125d0c0-ffffffff8125d1bd: __filemap_fdatawait_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __filemap_fdatawait_range(struct address_space *mapping, loff_t start_byte, loff_t end_byte);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81299000)
Location: mm/filemap.c:513
Inline: False
Direct callers:
  - mm/filemap.c:file_write_and_wait_range
  - mm/filemap.c:filemap_fdatawait_keep_errors
  - mm/filemap.c:file_fdatawait_range
  - mm/filemap.c:filemap_fdatawait_range_keep_errors
```
**Symbols:**

```
ffffffff81299000-ffffffff8129910c: __filemap_fdatawait_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __filemap_fdatawait_range(struct address_space *mapping, loff_t start_byte, loff_t end_byte);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff812efc40)
Location: mm/filemap.c:501
Inline: False
Direct callers:
  - mm/filemap.c:file_write_and_wait_range
  - mm/filemap.c:filemap_fdatawait_keep_errors
  - mm/filemap.c:file_fdatawait_range
  - mm/filemap.c:filemap_fdatawait_range_keep_errors
```
**Symbols:**

```
ffffffff812efc40-ffffffff812efd9e: __filemap_fdatawait_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __filemap_fdatawait_range(struct address_space *mapping, loff_t start_byte, loff_t end_byte);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8135adf0)
Location: mm/filemap.c:501
Inline: False
Direct callers:
  - mm/filemap.c:file_write_and_wait_range
  - mm/filemap.c:filemap_fdatawait_keep_errors
  - mm/filemap.c:file_fdatawait_range
  - mm/filemap.c:filemap_fdatawait_range_keep_errors
  - mm/filemap.c:filemap_fdatawait_range
```
**Symbols:**

```
ffffffff8135adf0-ffffffff8135af39: __filemap_fdatawait_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __filemap_fdatawait_range(struct address_space *mapping, loff_t start_byte, loff_t end_byte);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8138db30)
Location: mm/filemap.c:506
Inline: False
Direct callers:
  - mm/filemap.c:file_write_and_wait_range
  - mm/filemap.c:filemap_fdatawait_keep_errors
  - mm/filemap.c:file_fdatawait_range
  - mm/filemap.c:filemap_fdatawait_range_keep_errors
  - mm/filemap.c:filemap_fdatawait_range
```
**Symbols:**

```
ffffffff8138db30-ffffffff8138dc38: __filemap_fdatawait_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __filemap_fdatawait_range(struct address_space *mapping, loff_t start_byte, loff_t end_byte);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff813b7270)
Location: mm/filemap.c:501
Inline: False
Direct callers:
  - mm/filemap.c:file_write_and_wait_range
  - mm/filemap.c:filemap_fdatawait_keep_errors
  - mm/filemap.c:file_fdatawait_range
  - mm/filemap.c:filemap_fdatawait_range_keep_errors
  - mm/filemap.c:filemap_fdatawait_range
```
**Symbols:**

```
ffffffff813b7270-ffffffff813b7378: __filemap_fdatawait_range (STB_LOCAL)
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
void __filemap_fdatawait_range(struct address_space *mapping, loff_t start_byte, loff_t end_byte);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffff8000102ae710)
Location: mm/filemap.c:503
Inline: False
Direct callers:
  - mm/filemap.c:file_write_and_wait_range
  - mm/filemap.c:filemap_fdatawait_keep_errors
  - mm/filemap.c:file_fdatawait_range
  - mm/filemap.c:filemap_fdatawait_range_keep_errors
```
**Symbols:**

```
ffff8000102ae710-ffff8000102ae838: __filemap_fdatawait_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __filemap_fdatawait_range(struct address_space *mapping, loff_t start_byte, loff_t end_byte);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (c04dac90)
Location: mm/filemap.c:503
Inline: False
Direct callers:
  - mm/filemap.c:file_write_and_wait_range
  - mm/filemap.c:filemap_fdatawait_keep_errors
  - mm/filemap.c:file_fdatawait_range
  - mm/filemap.c:filemap_fdatawait_range_keep_errors
```
**Symbols:**

```
c04dac90-c04dada0: __filemap_fdatawait_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __filemap_fdatawait_range(struct address_space *mapping, loff_t start_byte, loff_t end_byte);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (c000000000362570)
Location: mm/filemap.c:503
Inline: False
Direct callers:
  - mm/filemap.c:file_write_and_wait_range
  - mm/filemap.c:filemap_fdatawait_keep_errors
  - mm/filemap.c:file_fdatawait_range
  - mm/filemap.c:filemap_fdatawait_range_keep_errors
```
**Symbols:**

```
c000000000362570-c000000000362700: __filemap_fdatawait_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __filemap_fdatawait_range(struct address_space *mapping, loff_t start_byte, loff_t end_byte);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffe0001d44ce)
Location: mm/filemap.c:503
Inline: False
Direct callers:
  - mm/filemap.c:file_write_and_wait_range
  - mm/filemap.c:filemap_fdatawait_keep_errors
  - mm/filemap.c:file_fdatawait_range
  - mm/filemap.c:filemap_fdatawait_range_keep_errors
  - mm/filemap.c:filemap_fdatawait_range
```
**Symbols:**

```
ffffffe0001d44ce-ffffffe0001d459a: __filemap_fdatawait_range (STB_LOCAL)
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
void __filemap_fdatawait_range(struct address_space *mapping, loff_t start_byte, loff_t end_byte);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81219340)
Location: mm/filemap.c:503
Inline: False
Direct callers:
  - mm/filemap.c:file_write_and_wait_range
  - mm/filemap.c:filemap_fdatawait_keep_errors
  - mm/filemap.c:file_fdatawait_range
  - mm/filemap.c:filemap_fdatawait_range_keep_errors
```
**Symbols:**

```
ffffffff81219340-ffffffff8121943f: __filemap_fdatawait_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __filemap_fdatawait_range(struct address_space *mapping, loff_t start_byte, loff_t end_byte);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8120c550)
Location: mm/filemap.c:503
Inline: False
Direct callers:
  - mm/filemap.c:file_write_and_wait_range
  - mm/filemap.c:filemap_fdatawait_keep_errors
  - mm/filemap.c:file_fdatawait_range
  - mm/filemap.c:filemap_fdatawait_range_keep_errors
```
**Symbols:**

```
ffffffff8120c550-ffffffff8120c64f: __filemap_fdatawait_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __filemap_fdatawait_range(struct address_space *mapping, loff_t start_byte, loff_t end_byte);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff812170e0)
Location: mm/filemap.c:503
Inline: False
Direct callers:
  - mm/filemap.c:file_write_and_wait_range
  - mm/filemap.c:filemap_fdatawait_keep_errors
  - mm/filemap.c:file_fdatawait_range
  - mm/filemap.c:filemap_fdatawait_range_keep_errors
```
**Symbols:**

```
ffffffff812170e0-ffffffff812171df: __filemap_fdatawait_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __filemap_fdatawait_range(struct address_space *mapping, loff_t start_byte, loff_t end_byte);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81226170)
Location: mm/filemap.c:503
Inline: False
Direct callers:
  - mm/filemap.c:file_write_and_wait_range
  - mm/filemap.c:filemap_fdatawait_keep_errors
  - mm/filemap.c:file_fdatawait_range
  - mm/filemap.c:filemap_fdatawait_range_keep_errors
```
**Symbols:**

```
ffffffff81226170-ffffffff8122626d: __filemap_fdatawait_range (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
</details>
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
