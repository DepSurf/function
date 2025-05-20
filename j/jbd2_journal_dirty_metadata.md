# Function: <code>jbd2_journal_dirty_metadata</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int jbd2_journal_dirty_metadata(handle_t *handle, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff812e8bf0)
Location: fs/jbd2/transaction.c:1328
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_super
```
**Symbols:**

```
ffffffff812e8bf0-ffffffff812e8ebf: jbd2_journal_dirty_metadata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int jbd2_journal_dirty_metadata(handle_t *handle, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff81316810)
Location: fs/jbd2/transaction.c:1313
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_super
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
```
**Symbols:**

```
ffffffff81316810-ffffffff81316ab0: jbd2_journal_dirty_metadata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int jbd2_journal_dirty_metadata(handle_t *handle, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff8132c800)
Location: fs/jbd2/transaction.c:1316
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_super
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
```
**Symbols:**

```
ffffffff8132c800-ffffffff8132caa0: jbd2_journal_dirty_metadata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int jbd2_journal_dirty_metadata(handle_t *handle, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff813419f0)
Location: fs/jbd2/transaction.c:1329
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_super
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
```
**Symbols:**

```
ffffffff813419f0-ffffffff81341c71: jbd2_journal_dirty_metadata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int jbd2_journal_dirty_metadata(handle_t *handle, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff81366020)
Location: fs/jbd2/transaction.c:1332
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_super
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
```
**Symbols:**

```
ffffffff81366020-ffffffff813662a1: jbd2_journal_dirty_metadata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int jbd2_journal_dirty_metadata(handle_t *handle, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/transaction.c (0)
Location: fs/jbd2/transaction.c:1328
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_super
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
```
**Symbols:**

```
ffffffff813952f0-ffffffff813953bc: jbd2_journal_dirty_metadata.cold.19 (STB_LOCAL)
ffffffff81394740-ffffffff81394987: jbd2_journal_dirty_metadata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int jbd2_journal_dirty_metadata(handle_t *handle, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/transaction.c (0)
Location: fs/jbd2/transaction.c:1362
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_super
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
```
**Symbols:**

```
ffffffff813ae05f-ffffffff813ae12b: jbd2_journal_dirty_metadata.cold.20 (STB_LOCAL)
ffffffff813ad490-ffffffff813ad6d7: jbd2_journal_dirty_metadata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int jbd2_journal_dirty_metadata(handle_t *handle, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/transaction.c (0)
Location: fs/jbd2/transaction.c:1362
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_super
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
```
**Symbols:**

```
ffffffff813d84ae-ffffffff813d8595: jbd2_journal_dirty_metadata.cold (STB_LOCAL)
ffffffff813d7730-ffffffff813d795d: jbd2_journal_dirty_metadata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int jbd2_journal_dirty_metadata(handle_t *handle, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/transaction.c (0)
Location: fs/jbd2/transaction.c:1369
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_super
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
```
**Symbols:**

```
ffffffff813f24a9-ffffffff813f2584: jbd2_journal_dirty_metadata.cold (STB_LOCAL)
ffffffff813f1800-ffffffff813f1a2d: jbd2_journal_dirty_metadata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int jbd2_journal_dirty_metadata(handle_t *handle, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/transaction.c (0)
Location: fs/jbd2/transaction.c:1448
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_super
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
```
**Symbols:**

```
ffffffff8143f839-ffffffff8143f929: jbd2_journal_dirty_metadata.cold (STB_LOCAL)
ffffffff8143ec80-ffffffff8143eec5: jbd2_journal_dirty_metadata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int jbd2_journal_dirty_metadata(handle_t *handle, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/transaction.c (0)
Location: fs/jbd2/transaction.c:1451
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/super.c:flush_stashed_error_work
```
**Symbols:**

```
ffffffff81becbdd-ffffffff81becccd: jbd2_journal_dirty_metadata.cold (STB_LOCAL)
ffffffff8145aee0-ffffffff8145b125: jbd2_journal_dirty_metadata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int jbd2_journal_dirty_metadata(handle_t *handle, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/transaction.c (0)
Location: fs/jbd2/transaction.c:1456
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/super.c:flush_stashed_error_work
```
**Symbols:**

```
ffffffff81bdec9d-ffffffff81bded8d: jbd2_journal_dirty_metadata.cold (STB_LOCAL)
ffffffff81460820-ffffffff81460a65: jbd2_journal_dirty_metadata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int jbd2_journal_dirty_metadata(handle_t *handle, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/transaction.c (0)
Location: fs/jbd2/transaction.c:1473
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/super.c:flush_stashed_error_work
```
**Symbols:**

```
ffffffff81cce4e1-ffffffff81cce5d1: jbd2_journal_dirty_metadata.cold (STB_LOCAL)
ffffffff814b5cb0-ffffffff814b5efc: jbd2_journal_dirty_metadata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int jbd2_journal_dirty_metadata(handle_t *handle, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/transaction.c (0)
Location: fs/jbd2/transaction.c:1482
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/super.c:flush_stashed_error_work
```
**Symbols:**

```
ffffffff81e81532-ffffffff81e81625: jbd2_journal_dirty_metadata.cold (STB_LOCAL)
ffffffff8153f5a0-ffffffff8153f7fc: jbd2_journal_dirty_metadata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int jbd2_journal_dirty_metadata(handle_t *handle, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff815ddfc0)
Location: fs/jbd2/transaction.c:1490
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/super.c:flush_stashed_error_work
```
**Symbols:**

```
ffffffff815ddfc0-ffffffff815de2e3: jbd2_journal_dirty_metadata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int jbd2_journal_dirty_metadata(handle_t *handle, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff81615a40)
Location: fs/jbd2/transaction.c:1490
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/super.c:flush_stashed_error_work
```
**Symbols:**

```
ffffffff81615a40-ffffffff81615d63: jbd2_journal_dirty_metadata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int jbd2_journal_dirty_metadata(handle_t *handle, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff8164e870)
Location: fs/jbd2/transaction.c:1500
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/super.c:update_super_work
```
**Symbols:**

```
ffffffff8164e870-ffffffff8164eb90: jbd2_journal_dirty_metadata (STB_GLOBAL)
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
int jbd2_journal_dirty_metadata(handle_t *handle, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffff8000104cb968)
Location: fs/jbd2/transaction.c:1369
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_super
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
```
**Symbols:**

```
ffff8000104cb968-ffff8000104cbd68: jbd2_journal_dirty_metadata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int jbd2_journal_dirty_metadata(handle_t *handle, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (c068f2d8)
Location: fs/jbd2/transaction.c:1369
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_super
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
```
**Symbols:**

```
c068f2d8-c068f758: jbd2_journal_dirty_metadata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int jbd2_journal_dirty_metadata(handle_t *handle, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (c000000000604c20)
Location: fs/jbd2/transaction.c:1369
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_super
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
```
**Symbols:**

```
c000000000604c20-c000000000605164: jbd2_journal_dirty_metadata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int jbd2_journal_dirty_metadata(handle_t *handle, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffe00034468c)
Location: fs/jbd2/transaction.c:1369
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_super
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
```
**Symbols:**

```
ffffffe00034468c-ffffffe00034497a: jbd2_journal_dirty_metadata (STB_GLOBAL)
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
int jbd2_journal_dirty_metadata(handle_t *handle, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/transaction.c (0)
Location: fs/jbd2/transaction.c:1369
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_super
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
```
**Symbols:**

```
ffffffff813eaa89-ffffffff813eab64: jbd2_journal_dirty_metadata.cold (STB_LOCAL)
ffffffff813e9de0-ffffffff813ea00d: jbd2_journal_dirty_metadata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int jbd2_journal_dirty_metadata(handle_t *handle, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/transaction.c (0)
Location: fs/jbd2/transaction.c:1369
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_super
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
```
**Symbols:**

```
ffffffff813db509-ffffffff813db5e4: jbd2_journal_dirty_metadata.cold (STB_LOCAL)
ffffffff813da860-ffffffff813daa8d: jbd2_journal_dirty_metadata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int jbd2_journal_dirty_metadata(handle_t *handle, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/transaction.c (0)
Location: fs/jbd2/transaction.c:1369
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_super
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
```
**Symbols:**

```
ffffffff813e7e09-ffffffff813e7ee4: jbd2_journal_dirty_metadata.cold (STB_LOCAL)
ffffffff813e7160-ffffffff813e738d: jbd2_journal_dirty_metadata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int jbd2_journal_dirty_metadata(handle_t *handle, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/transaction.c (0)
Location: fs/jbd2/transaction.c:1369
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_super
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
```
**Symbols:**

```
ffffffff813fd628-ffffffff813fd6fc: jbd2_journal_dirty_metadata.cold (STB_LOCAL)
ffffffff813fc820-ffffffff813fcad9: jbd2_journal_dirty_metadata (STB_GLOBAL)
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
