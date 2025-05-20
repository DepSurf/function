# Function: <code>jbd2_journal_commit_transaction</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void jbd2_journal_commit_transaction(journal_t *journal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/commit.c (ffffffff812e9ca0)
Location: fs/jbd2/commit.c:368
Inline: False
Direct callers:
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:jbd2_journal_destroy
```
**Symbols:**

```
ffffffff812e9ca0-ffffffff812eb509: jbd2_journal_commit_transaction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void jbd2_journal_commit_transaction(journal_t *journal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/commit.c (ffffffff813177a0)
Location: fs/jbd2/commit.c:354
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:kjournald2
```
**Symbols:**

```
ffffffff813177a0-ffffffff81318f52: jbd2_journal_commit_transaction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void jbd2_journal_commit_transaction(journal_t *journal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/commit.c (ffffffff8132d790)
Location: fs/jbd2/commit.c:354
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:kjournald2
```
**Symbols:**

```
ffffffff8132d790-ffffffff8132ef4a: jbd2_journal_commit_transaction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void jbd2_journal_commit_transaction(journal_t *journal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/commit.c (ffffffff81342930)
Location: fs/jbd2/commit.c:346
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:kjournald2
```
**Symbols:**

```
ffffffff81342930-ffffffff81343fdc: jbd2_journal_commit_transaction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void jbd2_journal_commit_transaction(journal_t *journal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/commit.c (ffffffff81366f60)
Location: fs/jbd2/commit.c:346
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:kjournald2
```
**Symbols:**

```
ffffffff81366f60-ffffffff81368679: jbd2_journal_commit_transaction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void jbd2_journal_commit_transaction(journal_t *journal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/commit.c (0)
Location: fs/jbd2/commit.c:343
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:kjournald2
```
**Symbols:**

```
ffffffff81396ee2-ffffffff81396f0e: jbd2_journal_commit_transaction.cold.23 (STB_LOCAL)
ffffffff81395820-ffffffff81396ee2: jbd2_journal_commit_transaction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void jbd2_journal_commit_transaction(journal_t *journal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/commit.c (0)
Location: fs/jbd2/commit.c:344
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:kjournald2
```
**Symbols:**

```
ffffffff813afc48-ffffffff813afc74: jbd2_journal_commit_transaction.cold.25 (STB_LOCAL)
ffffffff813ae560-ffffffff813afc48: jbd2_journal_commit_transaction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void jbd2_journal_commit_transaction(journal_t *journal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/commit.c (0)
Location: fs/jbd2/commit.c:355
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:kjournald2
```
**Symbols:**

```
ffffffff813da1ad-ffffffff813da1d9: jbd2_journal_commit_transaction.cold (STB_LOCAL)
ffffffff813d8a20-ffffffff813da1ad: jbd2_journal_commit_transaction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void jbd2_journal_commit_transaction(journal_t *journal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/commit.c (0)
Location: fs/jbd2/commit.c:355
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:kjournald2
```
**Symbols:**

```
ffffffff813f41f8-ffffffff813f4224: jbd2_journal_commit_transaction.cold (STB_LOCAL)
ffffffff813f2a10-ffffffff813f41f8: jbd2_journal_commit_transaction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void jbd2_journal_commit_transaction(journal_t *journal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/commit.c (0)
Location: fs/jbd2/commit.c:355
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:kjournald2
```
**Symbols:**

```
ffffffff81441574-ffffffff814415a0: jbd2_journal_commit_transaction.cold (STB_LOCAL)
ffffffff81440120-ffffffff81441574: jbd2_journal_commit_transaction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void jbd2_journal_commit_transaction(journal_t *journal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/commit.c (0)
Location: fs/jbd2/commit.c:381
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:kjournald2
```
**Symbols:**

```
ffffffff81becd05-ffffffff81becd31: jbd2_journal_commit_transaction.cold (STB_LOCAL)
ffffffff8145c2b0-ffffffff8145d787: jbd2_journal_commit_transaction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void jbd2_journal_commit_transaction(journal_t *journal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/commit.c (0)
Location: fs/jbd2/commit.c:381
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:kjournald2
```
**Symbols:**

```
ffffffff81bdedc5-ffffffff81bdedf1: jbd2_journal_commit_transaction.cold (STB_LOCAL)
ffffffff81461920-ffffffff814630ab: jbd2_journal_commit_transaction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void jbd2_journal_commit_transaction(journal_t *journal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/commit.c (0)
Location: fs/jbd2/commit.c:381
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:kjournald2
```
**Symbols:**

```
ffffffff81cce609-ffffffff81cce635: jbd2_journal_commit_transaction.cold (STB_LOCAL)
ffffffff814b6e10-ffffffff814b85ab: jbd2_journal_commit_transaction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void jbd2_journal_commit_transaction(journal_t *journal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/commit.c (0)
Location: fs/jbd2/commit.c:383
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:kjournald2
```
**Symbols:**

```
ffffffff81e816bc-ffffffff81e816e8: jbd2_journal_commit_transaction.cold (STB_LOCAL)
ffffffff81540850-ffffffff815420a8: jbd2_journal_commit_transaction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void jbd2_journal_commit_transaction(journal_t *journal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/commit.c (ffffffff815df450)
Location: fs/jbd2/commit.c:380
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:kjournald2
```
**Symbols:**

```
ffffffff815df450-ffffffff815e0cf8: jbd2_journal_commit_transaction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void jbd2_journal_commit_transaction(journal_t *journal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/commit.c (ffffffff81616c30)
Location: fs/jbd2/commit.c:351
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:kjournald2
```
**Symbols:**

```
ffffffff81616c30-ffffffff816185e9: jbd2_journal_commit_transaction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void jbd2_journal_commit_transaction(journal_t *journal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/commit.c (0)
Location: fs/jbd2/commit.c:348
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:kjournald2
```
**Symbols:**

```
ffffffff821ce228-ffffffff821ce288: jbd2_journal_commit_transaction.cold (STB_LOCAL)
ffffffff8164fa50-ffffffff81651540: jbd2_journal_commit_transaction (STB_GLOBAL)
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
void jbd2_journal_commit_transaction(journal_t *journal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/commit.c (ffff8000104cdf18)
Location: fs/jbd2/commit.c:355
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:kjournald2
```
**Symbols:**

```
ffff8000104cdf18-ffff8000104cf7cc: jbd2_journal_commit_transaction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void jbd2_journal_commit_transaction(journal_t *journal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/commit.c (c0690aec)
Location: fs/jbd2/commit.c:355
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:kjournald2
```
**Symbols:**

```
c0690aec-c06925dc: jbd2_journal_commit_transaction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void jbd2_journal_commit_transaction(journal_t *journal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/commit.c (c000000000606a60)
Location: fs/jbd2/commit.c:355
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:kjournald2
```
**Symbols:**

```
c000000000606a60-c0000000006089b8: jbd2_journal_commit_transaction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void jbd2_journal_commit_transaction(journal_t *journal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/commit.c (ffffffe000345af0)
Location: fs/jbd2/commit.c:355
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:kjournald2
```
**Symbols:**

```
ffffffe000345af0-ffffffe0003471e2: jbd2_journal_commit_transaction (STB_GLOBAL)
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
void jbd2_journal_commit_transaction(journal_t *journal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/commit.c (0)
Location: fs/jbd2/commit.c:355
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:kjournald2
```
**Symbols:**

```
ffffffff813ec7d8-ffffffff813ec804: jbd2_journal_commit_transaction.cold (STB_LOCAL)
ffffffff813eaff0-ffffffff813ec7d8: jbd2_journal_commit_transaction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void jbd2_journal_commit_transaction(journal_t *journal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/commit.c (0)
Location: fs/jbd2/commit.c:355
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:kjournald2
```
**Symbols:**

```
ffffffff813dd258-ffffffff813dd284: jbd2_journal_commit_transaction.cold (STB_LOCAL)
ffffffff813dba70-ffffffff813dd258: jbd2_journal_commit_transaction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void jbd2_journal_commit_transaction(journal_t *journal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/commit.c (0)
Location: fs/jbd2/commit.c:355
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:kjournald2
```
**Symbols:**

```
ffffffff813e9b58-ffffffff813e9b84: jbd2_journal_commit_transaction.cold (STB_LOCAL)
ffffffff813e8370-ffffffff813e9b58: jbd2_journal_commit_transaction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void jbd2_journal_commit_transaction(journal_t *journal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/commit.c (0)
Location: fs/jbd2/commit.c:355
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:kjournald2
```
**Symbols:**

```
ffffffff813ff4aa-ffffffff813ff4d6: jbd2_journal_commit_transaction.cold (STB_LOCAL)
ffffffff813fdb90-ffffffff813ff4aa: jbd2_journal_commit_transaction (STB_GLOBAL)
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
