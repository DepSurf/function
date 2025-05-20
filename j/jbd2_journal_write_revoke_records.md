# Function: <code>jbd2_journal_write_revoke_records</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void jbd2_journal_write_revoke_records(journal_t *journal, transaction_t *transaction, struct list_head *log_bufs, int write_op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/revoke.c (ffffffff812edbe0)
Location: fs/jbd2/revoke.c:522
Inline: False
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
**Symbols:**

```
ffffffff812edbe0-ffffffff812ede81: jbd2_journal_write_revoke_records (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void jbd2_journal_write_revoke_records(transaction_t *transaction, struct list_head *log_bufs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/revoke.c (ffffffff8131b510)
Location: fs/jbd2/revoke.c:522
Inline: False
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
**Symbols:**

```
ffffffff8131b510-ffffffff8131b7f6: jbd2_journal_write_revoke_records (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void jbd2_journal_write_revoke_records(transaction_t *transaction, struct list_head *log_bufs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/revoke.c (ffffffff81331500)
Location: fs/jbd2/revoke.c:523
Inline: False
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
**Symbols:**

```
ffffffff81331500-ffffffff813317e6: jbd2_journal_write_revoke_records (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void jbd2_journal_write_revoke_records(transaction_t *transaction, struct list_head *log_bufs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/revoke.c (ffffffff81346470)
Location: fs/jbd2/revoke.c:523
Inline: False
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
**Symbols:**

```
ffffffff81346470-ffffffff813466dc: jbd2_journal_write_revoke_records (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void jbd2_journal_write_revoke_records(transaction_t *transaction, struct list_head *log_bufs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/revoke.c (ffffffff8136ab00)
Location: fs/jbd2/revoke.c:523
Inline: False
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
**Symbols:**

```
ffffffff8136ab00-ffffffff8136ad6c: jbd2_journal_write_revoke_records (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void jbd2_journal_write_revoke_records(transaction_t *transaction, struct list_head *log_bufs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/revoke.c (ffffffff81399230)
Location: fs/jbd2/revoke.c:516
Inline: False
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
**Symbols:**

```
ffffffff81399230-ffffffff813994a3: jbd2_journal_write_revoke_records (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void jbd2_journal_write_revoke_records(transaction_t *transaction, struct list_head *log_bufs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/revoke.c (ffffffff813b1fa0)
Location: fs/jbd2/revoke.c:516
Inline: False
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
**Symbols:**

```
ffffffff813b1fa0-ffffffff813b2213: jbd2_journal_write_revoke_records (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void jbd2_journal_write_revoke_records(transaction_t *transaction, struct list_head *log_bufs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/revoke.c (ffffffff813dc600)
Location: fs/jbd2/revoke.c:524
Inline: False
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
**Symbols:**

```
ffffffff813dc600-ffffffff813dc871: jbd2_journal_write_revoke_records (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void jbd2_journal_write_revoke_records(transaction_t *transaction, struct list_head *log_bufs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/revoke.c (ffffffff813f6650)
Location: fs/jbd2/revoke.c:524
Inline: False
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
**Symbols:**

```
ffffffff813f6650-ffffffff813f68ba: jbd2_journal_write_revoke_records (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void jbd2_journal_write_revoke_records(transaction_t *transaction, struct list_head *log_bufs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/revoke.c (ffffffff81443be0)
Location: fs/jbd2/revoke.c:530
Inline: False
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
**Symbols:**

```
ffffffff81443be0-ffffffff81443d23: jbd2_journal_write_revoke_records (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void jbd2_journal_write_revoke_records(transaction_t *transaction, struct list_head *log_bufs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/revoke.c (ffffffff8145fcc0)
Location: fs/jbd2/revoke.c:530
Inline: False
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
**Symbols:**

```
ffffffff8145fcc0-ffffffff8145fe03: jbd2_journal_write_revoke_records (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void jbd2_journal_write_revoke_records(transaction_t *transaction, struct list_head *log_bufs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/revoke.c (ffffffff814653a0)
Location: fs/jbd2/revoke.c:530
Inline: False
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
**Symbols:**

```
ffffffff814653a0-ffffffff814655d9: jbd2_journal_write_revoke_records (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void jbd2_journal_write_revoke_records(transaction_t *transaction, struct list_head *log_bufs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/revoke.c (ffffffff814bad20)
Location: fs/jbd2/revoke.c:530
Inline: False
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
**Symbols:**

```
ffffffff814bad20-ffffffff814baf59: jbd2_journal_write_revoke_records (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void jbd2_journal_write_revoke_records(transaction_t *transaction, struct list_head *log_bufs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/revoke.c (ffffffff81544bf0)
Location: fs/jbd2/revoke.c:530
Inline: False
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
**Symbols:**

```
ffffffff81544bf0-ffffffff81544e46: jbd2_journal_write_revoke_records (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void jbd2_journal_write_revoke_records(transaction_t *transaction, struct list_head *log_bufs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/revoke.c (ffffffff815e3d30)
Location: fs/jbd2/revoke.c:530
Inline: False
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
**Symbols:**

```
ffffffff815e3d30-ffffffff815e3f86: jbd2_journal_write_revoke_records (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void jbd2_journal_write_revoke_records(transaction_t *transaction, struct list_head *log_bufs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/revoke.c (ffffffff8161b4f0)
Location: fs/jbd2/revoke.c:530
Inline: False
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
**Symbols:**

```
ffffffff8161b4f0-ffffffff8161b754: jbd2_journal_write_revoke_records (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void jbd2_journal_write_revoke_records(transaction_t *transaction, struct list_head *log_bufs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/revoke.c (ffffffff81654410)
Location: fs/jbd2/revoke.c:530
Inline: False
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
**Symbols:**

```
ffffffff81654410-ffffffff81654674: jbd2_journal_write_revoke_records (STB_GLOBAL)
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
void jbd2_journal_write_revoke_records(transaction_t *transaction, struct list_head *log_bufs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/revoke.c (ffff8000104d2828)
Location: fs/jbd2/revoke.c:524
Inline: False
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
**Symbols:**

```
ffff8000104d2828-ffff8000104d2acc: jbd2_journal_write_revoke_records (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void jbd2_journal_write_revoke_records(transaction_t *transaction, struct list_head *log_bufs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/revoke.c (c0694e70)
Location: fs/jbd2/revoke.c:524
Inline: False
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
**Symbols:**

```
c0694e70-c0695138: jbd2_journal_write_revoke_records (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void jbd2_journal_write_revoke_records(transaction_t *transaction, struct list_head *log_bufs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/revoke.c (c00000000060c070)
Location: fs/jbd2/revoke.c:524
Inline: False
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
**Symbols:**

```
c00000000060c070-c00000000060c3bc: jbd2_journal_write_revoke_records (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void jbd2_journal_write_revoke_records(transaction_t *transaction, struct list_head *log_bufs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/revoke.c (ffffffe0003497de)
Location: fs/jbd2/revoke.c:524
Inline: False
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
**Symbols:**

```
ffffffe0003497de-ffffffe000349a34: jbd2_journal_write_revoke_records (STB_GLOBAL)
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
void jbd2_journal_write_revoke_records(transaction_t *transaction, struct list_head *log_bufs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/revoke.c (ffffffff813eec30)
Location: fs/jbd2/revoke.c:524
Inline: False
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
**Symbols:**

```
ffffffff813eec30-ffffffff813eee9a: jbd2_journal_write_revoke_records (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void jbd2_journal_write_revoke_records(transaction_t *transaction, struct list_head *log_bufs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/revoke.c (ffffffff813df6b0)
Location: fs/jbd2/revoke.c:524
Inline: False
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
**Symbols:**

```
ffffffff813df6b0-ffffffff813df91a: jbd2_journal_write_revoke_records (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void jbd2_journal_write_revoke_records(transaction_t *transaction, struct list_head *log_bufs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/revoke.c (ffffffff813ebfb0)
Location: fs/jbd2/revoke.c:524
Inline: False
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
**Symbols:**

```
ffffffff813ebfb0-ffffffff813ec21a: jbd2_journal_write_revoke_records (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void jbd2_journal_write_revoke_records(transaction_t *transaction, struct list_head *log_bufs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/revoke.c (ffffffff81401950)
Location: fs/jbd2/revoke.c:524
Inline: False
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
**Symbols:**

```
ffffffff81401950-ffffffff81401bba: jbd2_journal_write_revoke_records (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>journal_t *journal</code>
</li>
<li>
<b>Param removed. </b>
<code>int write_op</code>
</li>
<li>
<b>Param reordered. </b>
<code>journal, transaction, log_bufs, write_op</code> ➡️ <code>transaction, log_bufs</code>
</li>
</ul>
</details>
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
