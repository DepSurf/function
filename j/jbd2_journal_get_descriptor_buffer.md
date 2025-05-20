# Function: <code>jbd2_journal_get_descriptor_buffer</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct buffer_head *jbd2_journal_get_descriptor_buffer(journal_t *journal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff812f2310)
Location: fs/jbd2/journal.c:808
Inline: False
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
```
**Symbols:**

```
ffffffff812f2310-ffffffff812f23be: jbd2_journal_get_descriptor_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct buffer_head *jbd2_journal_get_descriptor_buffer(transaction_t *transaction, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff8131fbd0)
Location: fs/jbd2/journal.c:811
Inline: False
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_commit_record
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
```
**Symbols:**

```
ffffffff8131fbd0-ffffffff8131fcad: jbd2_journal_get_descriptor_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct buffer_head *jbd2_journal_get_descriptor_buffer(transaction_t *transaction, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff81335a90)
Location: fs/jbd2/journal.c:811
Inline: False
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_commit_record
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
```
**Symbols:**

```
ffffffff81335a90-ffffffff81335b6d: jbd2_journal_get_descriptor_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct buffer_head *jbd2_journal_get_descriptor_buffer(transaction_t *transaction, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff8134a820)
Location: fs/jbd2/journal.c:833
Inline: False
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_commit_record
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
```
**Symbols:**

```
ffffffff8134a820-ffffffff8134a8fd: jbd2_journal_get_descriptor_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct buffer_head *jbd2_journal_get_descriptor_buffer(transaction_t *transaction, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff8136ee70)
Location: fs/jbd2/journal.c:849
Inline: False
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_commit_record
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
```
**Symbols:**

```
ffffffff8136ee70-ffffffff8136ef4d: jbd2_journal_get_descriptor_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct buffer_head *jbd2_journal_get_descriptor_buffer(transaction_t *transaction, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff8139d420)
Location: fs/jbd2/journal.c:846
Inline: False
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_commit_record
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
```
**Symbols:**

```
ffffffff8139d420-ffffffff8139d507: jbd2_journal_get_descriptor_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct buffer_head *jbd2_journal_get_descriptor_buffer(transaction_t *transaction, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff813b6190)
Location: fs/jbd2/journal.c:846
Inline: False
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
```
**Symbols:**

```
ffffffff813b6190-ffffffff813b6277: jbd2_journal_get_descriptor_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct buffer_head *jbd2_journal_get_descriptor_buffer(transaction_t *transaction, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff813e08c0)
Location: fs/jbd2/journal.c:829
Inline: False
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
```
**Symbols:**

```
ffffffff813e08c0-ffffffff813e09a8: jbd2_journal_get_descriptor_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct buffer_head *jbd2_journal_get_descriptor_buffer(transaction_t *transaction, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff813fa900)
Location: fs/jbd2/journal.c:827
Inline: False
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
```
**Symbols:**

```
ffffffff813fa900-ffffffff813fa9e8: jbd2_journal_get_descriptor_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct buffer_head *jbd2_journal_get_descriptor_buffer(transaction_t *transaction, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff81448090)
Location: fs/jbd2/journal.c:830
Inline: False
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/revoke.c:write_one_revoke_record
```
**Symbols:**

```
ffffffff81448090-ffffffff81448181: jbd2_journal_get_descriptor_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct buffer_head *jbd2_journal_get_descriptor_buffer(transaction_t *transaction, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff81464bd0)
Location: fs/jbd2/journal.c:1009
Inline: False
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/revoke.c:write_one_revoke_record
```
**Symbols:**

```
ffffffff81464bd0-ffffffff81464cc1: jbd2_journal_get_descriptor_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct buffer_head *jbd2_journal_get_descriptor_buffer(transaction_t *transaction, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff8146a360)
Location: fs/jbd2/journal.c:1009
Inline: False
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
```
**Symbols:**

```
ffffffff8146a360-ffffffff8146a451: jbd2_journal_get_descriptor_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct buffer_head *jbd2_journal_get_descriptor_buffer(transaction_t *transaction, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff814c0ac0)
Location: fs/jbd2/journal.c:1001
Inline: False
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
```
**Symbols:**

```
ffffffff814c0ac0-ffffffff814c0bb1: jbd2_journal_get_descriptor_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct buffer_head *jbd2_journal_get_descriptor_buffer(transaction_t *transaction, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff8154b350)
Location: fs/jbd2/journal.c:1003
Inline: False
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_commit_record
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
```
**Symbols:**

```
ffffffff8154b350-ffffffff8154b449: jbd2_journal_get_descriptor_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct buffer_head *jbd2_journal_get_descriptor_buffer(transaction_t *transaction, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff815eaff0)
Location: fs/jbd2/journal.c:1006
Inline: False
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_commit_record
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
```
**Symbols:**

```
ffffffff815eaff0-ffffffff815eb0f4: jbd2_journal_get_descriptor_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct buffer_head *jbd2_journal_get_descriptor_buffer(transaction_t *transaction, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff81622a60)
Location: fs/jbd2/journal.c:1008
Inline: False
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_commit_record
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
```
**Symbols:**

```
ffffffff81622a60-ffffffff81622b64: jbd2_journal_get_descriptor_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct buffer_head *jbd2_journal_get_descriptor_buffer(transaction_t *transaction, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff8165bab0)
Location: fs/jbd2/journal.c:997
Inline: False
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_commit_record
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
```
**Symbols:**

```
ffffffff8165bab0-ffffffff8165bbc3: jbd2_journal_get_descriptor_buffer (STB_GLOBAL)
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
struct buffer_head *jbd2_journal_get_descriptor_buffer(transaction_t *transaction, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffff8000104d7bf0)
Location: fs/jbd2/journal.c:827
Inline: False
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
```
**Symbols:**

```
ffff8000104d7bf0-ffff8000104d7d20: jbd2_journal_get_descriptor_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct buffer_head *jbd2_journal_get_descriptor_buffer(transaction_t *transaction, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (c0699b0c)
Location: fs/jbd2/journal.c:827
Inline: False
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
```
**Symbols:**

```
c0699b0c-c0699c40: jbd2_journal_get_descriptor_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct buffer_head *jbd2_journal_get_descriptor_buffer(transaction_t *transaction, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (c000000000612870)
Location: fs/jbd2/journal.c:827
Inline: False
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
```
**Symbols:**

```
c000000000612870-c0000000006129e8: jbd2_journal_get_descriptor_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct buffer_head *jbd2_journal_get_descriptor_buffer(transaction_t *transaction, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffe00034d85c)
Location: fs/jbd2/journal.c:827
Inline: False
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
```
**Symbols:**

```
ffffffe00034d85c-ffffffe00034d960: jbd2_journal_get_descriptor_buffer (STB_GLOBAL)
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
struct buffer_head *jbd2_journal_get_descriptor_buffer(transaction_t *transaction, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff813f2ee0)
Location: fs/jbd2/journal.c:827
Inline: False
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
```
**Symbols:**

```
ffffffff813f2ee0-ffffffff813f2fc8: jbd2_journal_get_descriptor_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct buffer_head *jbd2_journal_get_descriptor_buffer(transaction_t *transaction, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff813e3960)
Location: fs/jbd2/journal.c:827
Inline: False
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
```
**Symbols:**

```
ffffffff813e3960-ffffffff813e3a48: jbd2_journal_get_descriptor_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct buffer_head *jbd2_journal_get_descriptor_buffer(transaction_t *transaction, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff813f0260)
Location: fs/jbd2/journal.c:827
Inline: False
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
```
**Symbols:**

```
ffffffff813f0260-ffffffff813f0348: jbd2_journal_get_descriptor_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct buffer_head *jbd2_journal_get_descriptor_buffer(transaction_t *transaction, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff81405cb0)
Location: fs/jbd2/journal.c:827
Inline: False
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
```
**Symbols:**

```
ffffffff81405cb0-ffffffff81405d92: jbd2_journal_get_descriptor_buffer (STB_GLOBAL)
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
<b>Param added. </b>
<code>transaction_t *transaction</code>
</li>
<li>
<b>Param added. </b>
<code>int type</code>
</li>
<li>
<b>Param removed. </b>
<code>journal_t *journal</code>
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
