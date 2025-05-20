# Function: <code>jbd2_journal_bmap</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int jbd2_journal_bmap(journal_t *journal, long unsigned int blocknr, long long unsigned int *retp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff812f2040)
Location: fs/jbd2/journal.c:775
Inline: True
Direct callers:
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/journal.c:jbd2_journal_init_inode
```
**Symbols:**

```
ffffffff812f2040-ffffffff812f20b4: jbd2_journal_bmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int jbd2_journal_bmap(journal_t *journal, long unsigned int blocknr, long long unsigned int *retp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff8131f910)
Location: fs/jbd2/journal.c:777
Inline: True
Direct callers:
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/journal.c:jbd2_journal_init_inode
```
**Symbols:**

```
ffffffff8131f910-ffffffff8131f984: jbd2_journal_bmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int jbd2_journal_bmap(journal_t *journal, long unsigned int blocknr, long long unsigned int *retp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff81335990)
Location: fs/jbd2/journal.c:777
Inline: True
Direct callers:
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
```
**Symbols:**

```
ffffffff81335990-ffffffff81335a04: jbd2_journal_bmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int jbd2_journal_bmap(journal_t *journal, long unsigned int blocknr, long long unsigned int *retp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff8134a720)
Location: fs/jbd2/journal.c:799
Inline: True
Direct callers:
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
```
**Symbols:**

```
ffffffff8134a720-ffffffff8134a794: jbd2_journal_bmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int jbd2_journal_bmap(journal_t *journal, long unsigned int blocknr, long long unsigned int *retp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff8136ed70)
Location: fs/jbd2/journal.c:815
Inline: True
Direct callers:
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
```
**Symbols:**

```
ffffffff8136ed70-ffffffff8136ede4: jbd2_journal_bmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
int jbd2_journal_bmap(journal_t *journal, long unsigned int blocknr, long long unsigned int *retp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/jbd2/journal.c (0)
Location: fs/jbd2/journal.c:812
Inline: True
Direct callers:
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
```
**Symbols:**

```
ffffffff8139e497-ffffffff8139e4cc: jbd2_journal_bmap.cold.53 (STB_LOCAL)
ffffffff8139d350-ffffffff8139d396: jbd2_journal_bmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
int jbd2_journal_bmap(journal_t *journal, long unsigned int blocknr, long long unsigned int *retp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/jbd2/journal.c (ffffffff813b7207)
Location: fs/jbd2/journal.c:812
Inline: True
Direct callers:
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
```
**Symbols:**

```
ffffffff813b7207-ffffffff813b723c: jbd2_journal_bmap.cold.54 (STB_LOCAL)
ffffffff813b60c0-ffffffff813b6106: jbd2_journal_bmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int jbd2_journal_bmap(journal_t *journal, long unsigned int blocknr, long long unsigned int *retp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/jbd2/journal.c (ffffffff813e197f)
Location: fs/jbd2/journal.c:795
Inline: True
Direct callers:
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
```
**Symbols:**

```
ffffffff813e197f-ffffffff813e19b4: jbd2_journal_bmap.cold (STB_LOCAL)
ffffffff813e07f0-ffffffff813e0839: jbd2_journal_bmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int jbd2_journal_bmap(journal_t *journal, long unsigned int blocknr, long long unsigned int *retp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/jbd2/journal.c (ffffffff813fb9cf)
Location: fs/jbd2/journal.c:793
Inline: True
Direct callers:
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
```
**Symbols:**

```
ffffffff813fb9cf-ffffffff813fba04: jbd2_journal_bmap.cold (STB_LOCAL)
ffffffff813fa830-ffffffff813fa879: jbd2_journal_bmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int jbd2_journal_bmap(journal_t *journal, long unsigned int blocknr, long long unsigned int *retp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/jbd2/journal.c (ffffffff81447fa2)
Location: fs/jbd2/journal.c:792
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_next_log_block
Direct callers:
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/journal.c:jbd2_journal_next_log_block
```
**Symbols:**

```
ffffffff81449142-ffffffff81449183: jbd2_journal_bmap.part.0 (STB_LOCAL)
ffffffff81449193-ffffffff814491a3: jbd2_journal_bmap.cold (STB_LOCAL)
ffffffff81448000-ffffffff81448081: jbd2_journal_bmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int jbd2_journal_bmap(journal_t *journal, long unsigned int blocknr, long long unsigned int *retp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/jbd2/journal.c (ffffffff81bed290)
Location: fs/jbd2/journal.c:971
Inline: True
Direct callers:
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/journal.c:jbd2_fc_get_buf
  - fs/jbd2/journal.c:jbd2_journal_next_log_block
```
**Symbols:**

```
ffffffff81bed290-ffffffff81bed2c5: jbd2_journal_bmap.cold (STB_LOCAL)
ffffffff814649f0-ffffffff81464a71: jbd2_journal_bmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int jbd2_journal_bmap(journal_t *journal, long unsigned int blocknr, long long unsigned int *retp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/jbd2/journal.c (ffffffff81bdf374)
Location: fs/jbd2/journal.c:971
Inline: True
Direct callers:
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/journal.c:jbd2_fc_get_buf
  - fs/jbd2/journal.c:jbd2_journal_next_log_block
```
**Symbols:**

```
ffffffff81bdf374-ffffffff81bdf3a9: jbd2_journal_bmap.cold (STB_LOCAL)
ffffffff8146a180-ffffffff8146a201: jbd2_journal_bmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int jbd2_journal_bmap(journal_t *journal, long unsigned int blocknr, long long unsigned int *retp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/jbd2/journal.c (ffffffff81ccecac)
Location: fs/jbd2/journal.c:963
Inline: True
Direct callers:
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/journal.c:__jbd2_journal_erase
  - fs/jbd2/journal.c:jbd2_fc_get_buf
  - fs/jbd2/journal.c:jbd2_journal_next_log_block
```
**Symbols:**

```
ffffffff81ccecac-ffffffff81ccece1: jbd2_journal_bmap.cold (STB_LOCAL)
ffffffff814c0510-ffffffff814c0591: jbd2_journal_bmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int jbd2_journal_bmap(journal_t *journal, long unsigned int blocknr, long long unsigned int *retp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/jbd2/journal.c (ffffffff81e81d12)
Location: fs/jbd2/journal.c:965
Inline: True
Direct callers:
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/journal.c:__jbd2_journal_erase
  - fs/jbd2/journal.c:jbd2_fc_get_buf
  - fs/jbd2/journal.c:jbd2_journal_next_log_block
```
**Symbols:**

```
ffffffff81e81d12-ffffffff81e81d46: jbd2_journal_bmap.cold (STB_LOCAL)
ffffffff8154ad40-ffffffff8154adce: jbd2_journal_bmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int jbd2_journal_bmap(journal_t *journal, long unsigned int blocknr, long long unsigned int *retp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff815ea930)
Location: fs/jbd2/journal.c:968
Inline: True
Direct callers:
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/journal.c:__jbd2_journal_erase
  - fs/jbd2/journal.c:jbd2_fc_get_buf
  - fs/jbd2/journal.c:jbd2_journal_next_log_block
```
**Symbols:**

```
ffffffff815ea930-ffffffff815ea9e7: jbd2_journal_bmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int jbd2_journal_bmap(journal_t *journal, long unsigned int blocknr, long long unsigned int *retp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff81622370)
Location: fs/jbd2/journal.c:967
Inline: False
Direct callers:
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/journal.c:__jbd2_journal_erase
  - fs/jbd2/journal.c:jbd2_fc_get_buf
  - fs/jbd2/journal.c:jbd2_journal_next_log_block
```
**Symbols:**

```
ffffffff81622370-ffffffff81622456: jbd2_journal_bmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int jbd2_journal_bmap(journal_t *journal, long unsigned int blocknr, long long unsigned int *retp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff8165b3c0)
Location: fs/jbd2/journal.c:956
Inline: False
Direct callers:
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/journal.c:__jbd2_journal_erase
  - fs/jbd2/journal.c:jbd2_fc_get_buf
  - fs/jbd2/journal.c:jbd2_journal_next_log_block
```
**Symbols:**

```
ffffffff8165b3c0-ffffffff8165b4a6: jbd2_journal_bmap (STB_GLOBAL)
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
int jbd2_journal_bmap(journal_t *journal, long unsigned int blocknr, long long unsigned int *retp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffff8000104d7a80)
Location: fs/jbd2/journal.c:793
Inline: True
Direct callers:
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
```
**Symbols:**

```
ffff8000104d7a80-ffff8000104d7b20: jbd2_journal_bmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int jbd2_journal_bmap(journal_t *journal, long unsigned int blocknr, long long unsigned int *retp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (c06999fc)
Location: fs/jbd2/journal.c:793
Inline: True
Direct callers:
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
```
**Symbols:**

```
c06999fc-c0699a8c: jbd2_journal_bmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int jbd2_journal_bmap(journal_t *journal, long unsigned int blocknr, long long unsigned int *retp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (c0000000006126f0)
Location: fs/jbd2/journal.c:793
Inline: True
Direct callers:
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/journal.c:jbd2_journal_next_log_block
```
**Symbols:**

```
c0000000006126f0-c0000000006127c8: jbd2_journal_bmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int jbd2_journal_bmap(journal_t *journal, long unsigned int blocknr, long long unsigned int *retp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffe00034d762)
Location: fs/jbd2/journal.c:793
Inline: True
Direct callers:
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
```
**Symbols:**

```
ffffffe00034d762-ffffffe00034d7e8: jbd2_journal_bmap (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
int jbd2_journal_bmap(journal_t *journal, long unsigned int blocknr, long long unsigned int *retp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/jbd2/journal.c (ffffffff813f3faf)
Location: fs/jbd2/journal.c:793
Inline: True
Direct callers:
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
```
**Symbols:**

```
ffffffff813f3faf-ffffffff813f3fe4: jbd2_journal_bmap.cold (STB_LOCAL)
ffffffff813f2e10-ffffffff813f2e59: jbd2_journal_bmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int jbd2_journal_bmap(journal_t *journal, long unsigned int blocknr, long long unsigned int *retp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/jbd2/journal.c (ffffffff813e4a2f)
Location: fs/jbd2/journal.c:793
Inline: True
Direct callers:
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
```
**Symbols:**

```
ffffffff813e4a2f-ffffffff813e4a64: jbd2_journal_bmap.cold (STB_LOCAL)
ffffffff813e3890-ffffffff813e38d9: jbd2_journal_bmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int jbd2_journal_bmap(journal_t *journal, long unsigned int blocknr, long long unsigned int *retp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/jbd2/journal.c (ffffffff813f132f)
Location: fs/jbd2/journal.c:793
Inline: True
Direct callers:
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
```
**Symbols:**

```
ffffffff813f132f-ffffffff813f1364: jbd2_journal_bmap.cold (STB_LOCAL)
ffffffff813f0190-ffffffff813f01d9: jbd2_journal_bmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int jbd2_journal_bmap(journal_t *journal, long unsigned int blocknr, long long unsigned int *retp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/jbd2/journal.c (ffffffff81406f3a)
Location: fs/jbd2/journal.c:793
Inline: True
Direct callers:
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
```
**Symbols:**

```
ffffffff81406f3a-ffffffff81406f6f: jbd2_journal_bmap.cold (STB_LOCAL)
ffffffff81405bd0-ffffffff81405c19: jbd2_journal_bmap (STB_GLOBAL)
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
