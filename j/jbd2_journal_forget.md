# Function: <code>jbd2_journal_forget</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int jbd2_journal_forget(handle_t *handle, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff812e8ec0)
Location: fs/jbd2/transaction.c:1484
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
  - fs/jbd2/revoke.c:jbd2_journal_revoke
```
**Symbols:**

```
ffffffff812e8ec0-ffffffff812e90f7: jbd2_journal_forget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int jbd2_journal_forget(handle_t *handle, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff81316ab0)
Location: fs/jbd2/transaction.c:1469
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
  - fs/jbd2/revoke.c:jbd2_journal_revoke
```
**Symbols:**

```
ffffffff81316ab0-ffffffff81316cd5: jbd2_journal_forget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int jbd2_journal_forget(handle_t *handle, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff8132caa0)
Location: fs/jbd2/transaction.c:1472
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
  - fs/jbd2/revoke.c:jbd2_journal_revoke
```
**Symbols:**

```
ffffffff8132caa0-ffffffff8132ccc5: jbd2_journal_forget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int jbd2_journal_forget(handle_t *handle, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff81341c80)
Location: fs/jbd2/transaction.c:1485
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
  - fs/jbd2/revoke.c:jbd2_journal_revoke
```
**Symbols:**

```
ffffffff81341c80-ffffffff81341eb0: jbd2_journal_forget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int jbd2_journal_forget(handle_t *handle, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff813662b0)
Location: fs/jbd2/transaction.c:1488
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
  - fs/jbd2/revoke.c:jbd2_journal_revoke
```
**Symbols:**

```
ffffffff813662b0-ffffffff813664e0: jbd2_journal_forget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int jbd2_journal_forget(handle_t *handle, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/transaction.c (0)
Location: fs/jbd2/transaction.c:1491
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
  - fs/jbd2/revoke.c:jbd2_journal_revoke
```
**Symbols:**

```
ffffffff813953bc-ffffffff813953f4: jbd2_journal_forget.cold.20 (STB_LOCAL)
ffffffff81394990-ffffffff81394b89: jbd2_journal_forget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int jbd2_journal_forget(handle_t *handle, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/transaction.c (0)
Location: fs/jbd2/transaction.c:1524
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
  - fs/jbd2/revoke.c:jbd2_journal_revoke
```
**Symbols:**

```
ffffffff813ae12b-ffffffff813ae163: jbd2_journal_forget.cold.21 (STB_LOCAL)
ffffffff813ad6e0-ffffffff813ad8f7: jbd2_journal_forget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int jbd2_journal_forget(handle_t *handle, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/transaction.c (0)
Location: fs/jbd2/transaction.c:1524
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
  - fs/jbd2/revoke.c:jbd2_journal_revoke
```
**Symbols:**

```
ffffffff813d8595-ffffffff813d85d2: jbd2_journal_forget.cold (STB_LOCAL)
ffffffff813d7960-ffffffff813d7c37: jbd2_journal_forget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int jbd2_journal_forget(handle_t *handle, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/transaction.c (0)
Location: fs/jbd2/transaction.c:1531
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
  - fs/jbd2/revoke.c:jbd2_journal_revoke
```
**Symbols:**

```
ffffffff813f2584-ffffffff813f25c1: jbd2_journal_forget.cold (STB_LOCAL)
ffffffff813f1a30-ffffffff813f1d07: jbd2_journal_forget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int jbd2_journal_forget(handle_t *handle, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/transaction.c (0)
Location: fs/jbd2/transaction.c:1610
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
  - fs/jbd2/revoke.c:jbd2_journal_revoke
```
**Symbols:**

```
ffffffff8143f929-ffffffff8143f961: jbd2_journal_forget.cold (STB_LOCAL)
ffffffff8143eed0-ffffffff8143f13e: jbd2_journal_forget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int jbd2_journal_forget(handle_t *handle, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/transaction.c (0)
Location: fs/jbd2/transaction.c:1613
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
  - fs/jbd2/revoke.c:jbd2_journal_revoke
```
**Symbols:**

```
ffffffff81becccd-ffffffff81becd05: jbd2_journal_forget.cold (STB_LOCAL)
ffffffff8145b130-ffffffff8145b39e: jbd2_journal_forget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int jbd2_journal_forget(handle_t *handle, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/transaction.c (0)
Location: fs/jbd2/transaction.c:1618
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
  - fs/jbd2/revoke.c:jbd2_journal_revoke
```
**Symbols:**

```
ffffffff81bded8d-ffffffff81bdedc5: jbd2_journal_forget.cold (STB_LOCAL)
ffffffff81460a70-ffffffff81460cdb: jbd2_journal_forget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int jbd2_journal_forget(handle_t *handle, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/transaction.c (0)
Location: fs/jbd2/transaction.c:1635
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
  - fs/jbd2/revoke.c:jbd2_journal_revoke
```
**Symbols:**

```
ffffffff81cce5d1-ffffffff81cce609: jbd2_journal_forget.cold (STB_LOCAL)
ffffffff814b5f00-ffffffff814b6193: jbd2_journal_forget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int jbd2_journal_forget(handle_t *handle, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/transaction.c (0)
Location: fs/jbd2/transaction.c:1654
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
  - fs/jbd2/revoke.c:jbd2_journal_revoke
```
**Symbols:**

```
ffffffff81e81625-ffffffff81e81670: jbd2_journal_forget.cold (STB_LOCAL)
ffffffff8153f800-ffffffff8153fa72: jbd2_journal_forget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int jbd2_journal_forget(handle_t *handle, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff815de300)
Location: fs/jbd2/transaction.c:1662
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
  - fs/jbd2/revoke.c:jbd2_journal_revoke
```
**Symbols:**

```
ffffffff815de300-ffffffff815de5c2: jbd2_journal_forget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int jbd2_journal_forget(handle_t *handle, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff81615d80)
Location: fs/jbd2/transaction.c:1662
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
  - fs/jbd2/revoke.c:jbd2_journal_revoke
```
**Symbols:**

```
ffffffff81615d80-ffffffff81616030: jbd2_journal_forget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int jbd2_journal_forget(handle_t *handle, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff8164eba0)
Location: fs/jbd2/transaction.c:1672
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
  - fs/jbd2/revoke.c:jbd2_journal_revoke
```
**Symbols:**

```
ffffffff8164eba0-ffffffff8164ee4d: jbd2_journal_forget (STB_GLOBAL)
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
int jbd2_journal_forget(handle_t *handle, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffff8000104cbd68)
Location: fs/jbd2/transaction.c:1531
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
  - fs/jbd2/revoke.c:jbd2_journal_revoke
```
**Symbols:**

```
ffff8000104cbd68-ffff8000104cc18c: jbd2_journal_forget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int jbd2_journal_forget(handle_t *handle, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (c068f758)
Location: fs/jbd2/transaction.c:1531
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
  - fs/jbd2/revoke.c:jbd2_journal_revoke
```
**Symbols:**

```
c068f758-c068fb08: jbd2_journal_forget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int jbd2_journal_forget(handle_t *handle, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (c000000000605170)
Location: fs/jbd2/transaction.c:1531
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
  - fs/jbd2/revoke.c:jbd2_journal_revoke
```
**Symbols:**

```
c000000000605170-c0000000006056d8: jbd2_journal_forget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int jbd2_journal_forget(handle_t *handle, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffe00034497a)
Location: fs/jbd2/transaction.c:1531
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
  - fs/jbd2/revoke.c:jbd2_journal_revoke
```
**Symbols:**

```
ffffffe00034497a-ffffffe000344d48: jbd2_journal_forget (STB_GLOBAL)
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
int jbd2_journal_forget(handle_t *handle, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/transaction.c (0)
Location: fs/jbd2/transaction.c:1531
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
  - fs/jbd2/revoke.c:jbd2_journal_revoke
```
**Symbols:**

```
ffffffff813eab64-ffffffff813eaba1: jbd2_journal_forget.cold (STB_LOCAL)
ffffffff813ea010-ffffffff813ea2e7: jbd2_journal_forget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int jbd2_journal_forget(handle_t *handle, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/transaction.c (0)
Location: fs/jbd2/transaction.c:1531
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
  - fs/jbd2/revoke.c:jbd2_journal_revoke
```
**Symbols:**

```
ffffffff813db5e4-ffffffff813db621: jbd2_journal_forget.cold (STB_LOCAL)
ffffffff813daa90-ffffffff813dad67: jbd2_journal_forget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int jbd2_journal_forget(handle_t *handle, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/transaction.c (0)
Location: fs/jbd2/transaction.c:1531
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
  - fs/jbd2/revoke.c:jbd2_journal_revoke
```
**Symbols:**

```
ffffffff813e7ee4-ffffffff813e7f21: jbd2_journal_forget.cold (STB_LOCAL)
ffffffff813e7390-ffffffff813e7667: jbd2_journal_forget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int jbd2_journal_forget(handle_t *handle, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/transaction.c (0)
Location: fs/jbd2/transaction.c:1531
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
  - fs/jbd2/revoke.c:jbd2_journal_revoke
```
**Symbols:**

```
ffffffff813fd6fc-ffffffff813fd735: jbd2_journal_forget.cold (STB_LOCAL)
ffffffff813fcae0-ffffffff813fce13: jbd2_journal_forget (STB_GLOBAL)
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
