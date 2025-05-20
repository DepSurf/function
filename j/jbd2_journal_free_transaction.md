# Function: <code>jbd2_journal_free_transaction</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void jbd2_journal_free_transaction(transaction_t *transaction);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff812e7035)
Location: fs/jbd2/transaction.c:60
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/checkpoint.c:__jbd2_journal_remove_checkpoint
```
**Symbols:**

```
ffffffff812e77b0-ffffffff812e77d1: jbd2_journal_free_transaction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void jbd2_journal_free_transaction(transaction_t *transaction);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff81314b95)
Location: fs/jbd2/transaction.c:60
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/checkpoint.c:__jbd2_journal_remove_checkpoint
```
**Symbols:**

```
ffffffff81315420-ffffffff81315441: jbd2_journal_free_transaction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void jbd2_journal_free_transaction(transaction_t *transaction);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff8132ab68)
Location: fs/jbd2/transaction.c:60
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/checkpoint.c:__jbd2_journal_remove_checkpoint
```
**Symbols:**

```
ffffffff8132b420-ffffffff8132b441: jbd2_journal_free_transaction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void jbd2_journal_free_transaction(transaction_t *transaction);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff8133fd8e)
Location: fs/jbd2/transaction.c:61
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/checkpoint.c:__jbd2_journal_remove_checkpoint
```
**Symbols:**

```
ffffffff81340660-ffffffff81340682: jbd2_journal_free_transaction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void jbd2_journal_free_transaction(transaction_t *transaction);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff8136439e)
Location: fs/jbd2/transaction.c:61
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/checkpoint.c:__jbd2_journal_remove_checkpoint
```
**Symbols:**

```
ffffffff81364c70-ffffffff81364c92: jbd2_journal_free_transaction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void jbd2_journal_free_transaction(transaction_t *transaction);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff81392b52)
Location: fs/jbd2/transaction.c:56
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/checkpoint.c:__jbd2_journal_remove_checkpoint
```
**Symbols:**

```
ffffffff813933e0-ffffffff81393401: jbd2_journal_free_transaction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void jbd2_journal_free_transaction(transaction_t *transaction);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff813ab7c7)
Location: fs/jbd2/transaction.c:56
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/checkpoint.c:__jbd2_journal_remove_checkpoint
```
**Symbols:**

```
ffffffff813ac100-ffffffff813ac121: jbd2_journal_free_transaction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void jbd2_journal_free_transaction(transaction_t *transaction);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff813d5a0a)
Location: fs/jbd2/transaction.c:58
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/checkpoint.c:__jbd2_journal_remove_checkpoint
```
**Symbols:**

```
ffffffff813d6380-ffffffff813d63a1: jbd2_journal_free_transaction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void jbd2_journal_free_transaction(transaction_t *transaction);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff813efa3a)
Location: fs/jbd2/transaction.c:58
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/checkpoint.c:__jbd2_journal_remove_checkpoint
```
**Symbols:**

```
ffffffff813f03b0-ffffffff813f03d1: jbd2_journal_free_transaction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void jbd2_journal_free_transaction(transaction_t *transaction);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff8143d179)
Location: fs/jbd2/transaction.c:58
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/checkpoint.c:__jbd2_journal_remove_checkpoint
```
**Symbols:**

```
ffffffff8143d900-ffffffff8143d921: jbd2_journal_free_transaction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void jbd2_journal_free_transaction(transaction_t *transaction);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff814594f9)
Location: fs/jbd2/transaction.c:58
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/checkpoint.c:__jbd2_journal_remove_checkpoint
```
**Symbols:**

```
ffffffff81459c50-ffffffff81459c71: jbd2_journal_free_transaction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void jbd2_journal_free_transaction(transaction_t *transaction);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff8145edb9)
Location: fs/jbd2/transaction.c:58
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/checkpoint.c:__jbd2_journal_remove_checkpoint
```
**Symbols:**

```
ffffffff8145f500-ffffffff8145f521: jbd2_journal_free_transaction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void jbd2_journal_free_transaction(transaction_t *transaction);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff814b4124)
Location: fs/jbd2/transaction.c:58
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/checkpoint.c:__jbd2_journal_remove_checkpoint
```
**Symbols:**

```
ffffffff814b49b0-ffffffff814b49d1: jbd2_journal_free_transaction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void jbd2_journal_free_transaction(transaction_t *transaction);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff8153d997)
Location: fs/jbd2/transaction.c:58
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/checkpoint.c:__jbd2_journal_remove_checkpoint
```
**Symbols:**

```
ffffffff8153e1a0-ffffffff8153e1d1: jbd2_journal_free_transaction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void jbd2_journal_free_transaction(transaction_t *transaction);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff815dc207)
Location: fs/jbd2/transaction.c:58
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/checkpoint.c:__jbd2_journal_remove_checkpoint
```
**Symbols:**

```
ffffffff815dcaa0-ffffffff815dcad1: jbd2_journal_free_transaction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void jbd2_journal_free_transaction(transaction_t *transaction);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff81613cb9)
Location: fs/jbd2/transaction.c:58
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/checkpoint.c:__jbd2_journal_remove_checkpoint
```
**Symbols:**

```
ffffffff81614540-ffffffff81614571: jbd2_journal_free_transaction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void jbd2_journal_free_transaction(transaction_t *transaction);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff8164caa9)
Location: fs/jbd2/transaction.c:58
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/checkpoint.c:__jbd2_journal_remove_checkpoint
```
**Symbols:**

```
ffffffff8164d330-ffffffff8164d361: jbd2_journal_free_transaction (STB_GLOBAL)
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
void jbd2_journal_free_transaction(transaction_t *transaction);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffff8000104c96bc)
Location: fs/jbd2/transaction.c:58
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/checkpoint.c:__jbd2_journal_remove_checkpoint
```
**Symbols:**

```
ffff8000104c9cf0-ffff8000104c9d2c: jbd2_journal_free_transaction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void jbd2_journal_free_transaction(transaction_t *transaction);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (c068cd4c)
Location: fs/jbd2/transaction.c:58
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/checkpoint.c:__jbd2_journal_remove_checkpoint
```
**Symbols:**

```
c068d7e8-c068d81c: jbd2_journal_free_transaction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void jbd2_journal_free_transaction(transaction_t *transaction);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (c000000000601e0c)
Location: fs/jbd2/transaction.c:58
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/checkpoint.c:__jbd2_journal_remove_checkpoint
```
**Symbols:**

```
c000000000602a60-c000000000602aa8: jbd2_journal_free_transaction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void jbd2_journal_free_transaction(transaction_t *transaction);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffe0003428be)
Location: fs/jbd2/transaction.c:58
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/checkpoint.c:__jbd2_journal_remove_checkpoint
```
**Symbols:**

```
ffffffe0003431b0-ffffffe0003431e8: jbd2_journal_free_transaction (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void jbd2_journal_free_transaction(transaction_t *transaction);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff813e801a)
Location: fs/jbd2/transaction.c:58
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/checkpoint.c:__jbd2_journal_remove_checkpoint
```
**Symbols:**

```
ffffffff813e8990-ffffffff813e89b1: jbd2_journal_free_transaction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void jbd2_journal_free_transaction(transaction_t *transaction);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff813d8a9a)
Location: fs/jbd2/transaction.c:58
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/checkpoint.c:__jbd2_journal_remove_checkpoint
```
**Symbols:**

```
ffffffff813d9410-ffffffff813d9431: jbd2_journal_free_transaction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void jbd2_journal_free_transaction(transaction_t *transaction);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff813e539a)
Location: fs/jbd2/transaction.c:58
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/checkpoint.c:__jbd2_journal_remove_checkpoint
```
**Symbols:**

```
ffffffff813e5d10-ffffffff813e5d31: jbd2_journal_free_transaction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void jbd2_journal_free_transaction(transaction_t *transaction);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff813fa91f)
Location: fs/jbd2/transaction.c:58
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/checkpoint.c:__jbd2_journal_remove_checkpoint
```
**Symbols:**

```
ffffffff813fb1b0-ffffffff813fb1d1: jbd2_journal_free_transaction (STB_GLOBAL)
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
