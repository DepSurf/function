# Function: <code>jbd2_journal_start_reserved</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int jbd2_journal_start_reserved(handle_t *handle, unsigned int type, unsigned int line_no);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff812e8020)
Location: fs/jbd2/transaction.c:503
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
```
**Symbols:**

```
ffffffff812e8020-ffffffff812e8109: jbd2_journal_start_reserved (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int jbd2_journal_start_reserved(handle_t *handle, unsigned int type, unsigned int line_no);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff81315ca0)
Location: fs/jbd2/transaction.c:500
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
```
**Symbols:**

```
ffffffff81315ca0-ffffffff81315d9a: jbd2_journal_start_reserved (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int jbd2_journal_start_reserved(handle_t *handle, unsigned int type, unsigned int line_no);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff8132bc90)
Location: fs/jbd2/transaction.c:502
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
```
**Symbols:**

```
ffffffff8132bc90-ffffffff8132bd8a: jbd2_journal_start_reserved (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int jbd2_journal_start_reserved(handle_t *handle, unsigned int type, unsigned int line_no);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff81340eb0)
Location: fs/jbd2/transaction.c:509
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
```
**Symbols:**

```
ffffffff81340eb0-ffffffff81340f81: jbd2_journal_start_reserved (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int jbd2_journal_start_reserved(handle_t *handle, unsigned int type, unsigned int line_no);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff813654d0)
Location: fs/jbd2/transaction.c:511
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
```
**Symbols:**

```
ffffffff813654d0-ffffffff813655a1: jbd2_journal_start_reserved (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int jbd2_journal_start_reserved(handle_t *handle, unsigned int type, unsigned int line_no);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff81393c40)
Location: fs/jbd2/transaction.c:506
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
```
**Symbols:**

```
ffffffff81393c40-ffffffff81393d14: jbd2_journal_start_reserved (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int jbd2_journal_start_reserved(handle_t *handle, unsigned int type, unsigned int line_no);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff813ac960)
Location: fs/jbd2/transaction.c:539
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
```
**Symbols:**

```
ffffffff813ac960-ffffffff813aca34: jbd2_journal_start_reserved (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int jbd2_journal_start_reserved(handle_t *handle, unsigned int type, unsigned int line_no);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/transaction.c (0)
Location: fs/jbd2/transaction.c:539
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
```
**Symbols:**

```
ffffffff813d8409-ffffffff813d8449: jbd2_journal_start_reserved.cold (STB_LOCAL)
ffffffff813d6be0-ffffffff813d6c95: jbd2_journal_start_reserved (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int jbd2_journal_start_reserved(handle_t *handle, unsigned int type, unsigned int line_no);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff813f0c20)
Location: fs/jbd2/transaction.c:539
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
```
**Symbols:**

```
ffffffff813f0c20-ffffffff813f0d88: jbd2_journal_start_reserved (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int jbd2_journal_start_reserved(handle_t *handle, unsigned int type, unsigned int line_no);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff8143e0e0)
Location: fs/jbd2/transaction.c:580
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
```
**Symbols:**

```
ffffffff8143e0e0-ffffffff8143e240: jbd2_journal_start_reserved (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int jbd2_journal_start_reserved(handle_t *handle, unsigned int type, unsigned int line_no);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff8145a3a0)
Location: fs/jbd2/transaction.c:582
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
```
**Symbols:**

```
ffffffff8145a3a0-ffffffff8145a4d9: jbd2_journal_start_reserved (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int jbd2_journal_start_reserved(handle_t *handle, unsigned int type, unsigned int line_no);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff8145fc40)
Location: fs/jbd2/transaction.c:587
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
```
**Symbols:**

```
ffffffff8145fc40-ffffffff8145fd79: jbd2_journal_start_reserved (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int jbd2_journal_start_reserved(handle_t *handle, unsigned int type, unsigned int line_no);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff814b50e0)
Location: fs/jbd2/transaction.c:604
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
```
**Symbols:**

```
ffffffff814b50e0-ffffffff814b5216: jbd2_journal_start_reserved (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int jbd2_journal_start_reserved(handle_t *handle, unsigned int type, unsigned int line_no);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff8153e9d0)
Location: fs/jbd2/transaction.c:599
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
```
**Symbols:**

```
ffffffff8153e9d0-ffffffff8153eb6e: jbd2_journal_start_reserved (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int jbd2_journal_start_reserved(handle_t *handle, unsigned int type, unsigned int line_no);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff815dd370)
Location: fs/jbd2/transaction.c:599
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
```
**Symbols:**

```
ffffffff815dd370-ffffffff815dd50e: jbd2_journal_start_reserved (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int jbd2_journal_start_reserved(handle_t *handle, unsigned int type, unsigned int line_no);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff81614e10)
Location: fs/jbd2/transaction.c:599
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
```
**Symbols:**

```
ffffffff81614e10-ffffffff81614fae: jbd2_journal_start_reserved (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int jbd2_journal_start_reserved(handle_t *handle, unsigned int type, unsigned int line_no);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff8164dc00)
Location: fs/jbd2/transaction.c:599
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
```
**Symbols:**

```
ffffffff8164dc00-ffffffff8164dd9e: jbd2_journal_start_reserved (STB_GLOBAL)
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
int jbd2_journal_start_reserved(handle_t *handle, unsigned int type, unsigned int line_no);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffff8000104ca880)
Location: fs/jbd2/transaction.c:539
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
```
**Symbols:**

```
ffff8000104ca880-ffff8000104caa1c: jbd2_journal_start_reserved (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int jbd2_journal_start_reserved(handle_t *handle, unsigned int type, unsigned int line_no);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (c068e290)
Location: fs/jbd2/transaction.c:539
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
```
**Symbols:**

```
c068e290-c068e440: jbd2_journal_start_reserved (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int jbd2_journal_start_reserved(handle_t *handle, unsigned int type, unsigned int line_no);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (c0000000006036f0)
Location: fs/jbd2/transaction.c:539
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
```
**Symbols:**

```
c0000000006036f0-c000000000603910: jbd2_journal_start_reserved (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int jbd2_journal_start_reserved(handle_t *handle, unsigned int type, unsigned int line_no);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffe0003439d2)
Location: fs/jbd2/transaction.c:539
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
```
**Symbols:**

```
ffffffe0003439d2-ffffffe000343b12: jbd2_journal_start_reserved (STB_GLOBAL)
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
int jbd2_journal_start_reserved(handle_t *handle, unsigned int type, unsigned int line_no);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff813e9200)
Location: fs/jbd2/transaction.c:539
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
```
**Symbols:**

```
ffffffff813e9200-ffffffff813e9368: jbd2_journal_start_reserved (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int jbd2_journal_start_reserved(handle_t *handle, unsigned int type, unsigned int line_no);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff813d9c80)
Location: fs/jbd2/transaction.c:539
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
```
**Symbols:**

```
ffffffff813d9c80-ffffffff813d9de8: jbd2_journal_start_reserved (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int jbd2_journal_start_reserved(handle_t *handle, unsigned int type, unsigned int line_no);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff813e6580)
Location: fs/jbd2/transaction.c:539
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
```
**Symbols:**

```
ffffffff813e6580-ffffffff813e66e8: jbd2_journal_start_reserved (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int jbd2_journal_start_reserved(handle_t *handle, unsigned int type, unsigned int line_no);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff813fba90)
Location: fs/jbd2/transaction.c:539
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
```
**Symbols:**

```
ffffffff813fba90-ffffffff813fbc11: jbd2_journal_start_reserved (STB_GLOBAL)
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
