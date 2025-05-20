# Function: <code>__jbd2_log_start_commit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __jbd2_log_start_commit(journal_t *journal, tid_t target);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff812f1540)
Location: fs/jbd2/journal.c:494
Inline: False
Direct callers:
  - fs/jbd2/journal.c:__jbd2_journal_force_commit
  - fs/jbd2/journal.c:jbd2_complete_transaction
  - fs/jbd2/journal.c:jbd2_journal_start_commit
  - fs/jbd2/journal.c:jbd2_journal_flush
```
**Symbols:**

```
ffffffff812f1540-ffffffff812f15e7: __jbd2_log_start_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __jbd2_log_start_commit(journal_t *journal, tid_t target);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff8131ed50)
Location: fs/jbd2/journal.c:495
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_complete_transaction
  - fs/jbd2/journal.c:jbd2_journal_start_commit
  - fs/jbd2/journal.c:__jbd2_journal_force_commit
```
**Symbols:**

```
ffffffff8131ed50-ffffffff8131edf5: __jbd2_log_start_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __jbd2_log_start_commit(journal_t *journal, tid_t target);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff81334dd0)
Location: fs/jbd2/journal.c:495
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_complete_transaction
  - fs/jbd2/journal.c:jbd2_journal_start_commit
  - fs/jbd2/journal.c:__jbd2_journal_force_commit
```
**Symbols:**

```
ffffffff81334dd0-ffffffff81334e75: __jbd2_log_start_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __jbd2_log_start_commit(journal_t *journal, tid_t target);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff81349b80)
Location: fs/jbd2/journal.c:504
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_complete_transaction
  - fs/jbd2/journal.c:jbd2_journal_start_commit
  - fs/jbd2/journal.c:__jbd2_journal_force_commit
```
**Symbols:**

```
ffffffff81349b80-ffffffff81349c19: __jbd2_log_start_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __jbd2_log_start_commit(journal_t *journal, tid_t target);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff8136e1d0)
Location: fs/jbd2/journal.c:503
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_complete_transaction
  - fs/jbd2/journal.c:jbd2_journal_start_commit
  - fs/jbd2/journal.c:__jbd2_journal_force_commit
```
**Symbols:**

```
ffffffff8136e1d0-ffffffff8136e269: __jbd2_log_start_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __jbd2_log_start_commit(journal_t *journal, tid_t target);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff8139c860)
Location: fs/jbd2/journal.c:500
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_start_commit
  - fs/jbd2/journal.c:jbd2_log_start_commit
```
**Symbols:**

```
ffffffff8139c860-ffffffff8139c8f8: __jbd2_log_start_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __jbd2_log_start_commit(journal_t *journal, tid_t target);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff813b55d0)
Location: fs/jbd2/journal.c:500
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_start_commit
  - fs/jbd2/journal.c:jbd2_log_start_commit
```
**Symbols:**

```
ffffffff813b55d0-ffffffff813b5668: __jbd2_log_start_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __jbd2_log_start_commit(journal_t *journal, tid_t target);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff813dfca0)
Location: fs/jbd2/journal.c:483
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_start_commit
  - fs/jbd2/journal.c:jbd2_log_start_commit
```
**Symbols:**

```
ffffffff813dfca0-ffffffff813dfd38: __jbd2_log_start_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __jbd2_log_start_commit(journal_t *journal, tid_t target);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff813f9cf0)
Location: fs/jbd2/journal.c:481
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_start_commit
  - fs/jbd2/journal.c:jbd2_log_start_commit
```
**Symbols:**

```
ffffffff813f9cf0-ffffffff813f9d88: __jbd2_log_start_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __jbd2_log_start_commit(journal_t *journal, tid_t target);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff81447480)
Location: fs/jbd2/journal.c:480
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_abort
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_complete_transaction
  - fs/jbd2/journal.c:jbd2_journal_start_commit
  - fs/jbd2/journal.c:__jbd2_journal_force_commit
```
**Symbols:**

```
ffffffff81447480-ffffffff81447518: __jbd2_log_start_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __jbd2_log_start_commit(journal_t *journal, tid_t target);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff81463e10)
Location: fs/jbd2/journal.c:484
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_abort
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_complete_transaction
  - fs/jbd2/journal.c:jbd2_journal_start_commit
  - fs/jbd2/journal.c:__jbd2_journal_force_commit
```
**Symbols:**

```
ffffffff81463e10-ffffffff81463ea8: __jbd2_log_start_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __jbd2_log_start_commit(journal_t *journal, tid_t target);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff814694c0)
Location: fs/jbd2/journal.c:484
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_abort
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_complete_transaction
  - fs/jbd2/journal.c:jbd2_journal_start_commit
  - fs/jbd2/journal.c:__jbd2_journal_force_commit
```
**Symbols:**

```
ffffffff814694c0-ffffffff81469558: __jbd2_log_start_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int __jbd2_log_start_commit(journal_t *journal, tid_t target);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/journal.c (0)
Location: fs/jbd2/journal.c:484
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_abort
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_complete_transaction
  - fs/jbd2/journal.c:jbd2_journal_start_commit
  - fs/jbd2/journal.c:__jbd2_journal_force_commit
```
**Symbols:**

```
ffffffff81cceb84-ffffffff81cceb9f: __jbd2_log_start_commit.cold (STB_LOCAL)
ffffffff814bf930-ffffffff814bf9f1: __jbd2_log_start_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int __jbd2_log_start_commit(journal_t *journal, tid_t target);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/journal.c (0)
Location: fs/jbd2/journal.c:484
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_abort
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_complete_transaction
  - fs/jbd2/journal.c:jbd2_journal_start_commit
  - fs/jbd2/journal.c:__jbd2_journal_force_commit
```
**Symbols:**

```
ffffffff81e81c07-ffffffff81e81c22: __jbd2_log_start_commit.cold (STB_LOCAL)
ffffffff8154a080-ffffffff8154a15e: __jbd2_log_start_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int __jbd2_log_start_commit(journal_t *journal, tid_t target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/journal.c (0)
Location: fs/jbd2/journal.c:481
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_abort
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_complete_transaction
  - fs/jbd2/journal.c:jbd2_journal_start_commit
  - fs/jbd2/journal.c:__jbd2_journal_force_commit
```
**Symbols:**

```
ffffffff815e80a0-ffffffff815e817e: __jbd2_log_start_commit (STB_LOCAL)
ffffffff8207141d-ffffffff82071438: __jbd2_log_start_commit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int __jbd2_log_start_commit(journal_t *journal, tid_t target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/journal.c (0)
Location: fs/jbd2/journal.c:480
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_abort
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_complete_transaction
  - fs/jbd2/journal.c:jbd2_journal_start_commit
  - fs/jbd2/journal.c:__jbd2_journal_force_commit
```
**Symbols:**

```
ffffffff8161f9b0-ffffffff8161fa8e: __jbd2_log_start_commit (STB_LOCAL)
ffffffff820f10e2-ffffffff820f10fd: __jbd2_log_start_commit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int __jbd2_log_start_commit(journal_t *journal, tid_t target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/journal.c (0)
Location: fs/jbd2/journal.c:469
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_abort
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_complete_transaction
  - fs/jbd2/journal.c:jbd2_journal_start_commit
  - fs/jbd2/journal.c:__jbd2_journal_force_commit
```
**Symbols:**

```
ffffffff816588c0-ffffffff8165899e: __jbd2_log_start_commit (STB_LOCAL)
ffffffff821ce30f-ffffffff821ce32a: __jbd2_log_start_commit.cold (STB_LOCAL)
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
int __jbd2_log_start_commit(journal_t *journal, tid_t target);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffff8000104d6828)
Location: fs/jbd2/journal.c:481
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_start_commit
  - fs/jbd2/journal.c:jbd2_log_start_commit
```
**Symbols:**

```
ffff8000104d6828-ffff8000104d68ec: __jbd2_log_start_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __jbd2_log_start_commit(journal_t *journal, tid_t target);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (c0698b1c)
Location: fs/jbd2/journal.c:481
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_start_commit
  - fs/jbd2/journal.c:jbd2_log_start_commit
```
**Symbols:**

```
c0698b1c-c0698bfc: __jbd2_log_start_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __jbd2_log_start_commit(journal_t *journal, tid_t target);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (c000000000611350)
Location: fs/jbd2/journal.c:481
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_start_commit
  - fs/jbd2/journal.c:jbd2_log_start_commit
```
**Symbols:**

```
c000000000611350-c00000000061146c: __jbd2_log_start_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __jbd2_log_start_commit(journal_t *journal, tid_t target);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffe00034cacc)
Location: fs/jbd2/journal.c:481
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_start_commit
  - fs/jbd2/journal.c:jbd2_log_start_commit
```
**Symbols:**

```
ffffffe00034cacc-ffffffe00034cb6c: __jbd2_log_start_commit (STB_GLOBAL)
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
int __jbd2_log_start_commit(journal_t *journal, tid_t target);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff813f22d0)
Location: fs/jbd2/journal.c:481
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_start_commit
  - fs/jbd2/journal.c:jbd2_log_start_commit
```
**Symbols:**

```
ffffffff813f22d0-ffffffff813f2368: __jbd2_log_start_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __jbd2_log_start_commit(journal_t *journal, tid_t target);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff813e2d50)
Location: fs/jbd2/journal.c:481
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_start_commit
  - fs/jbd2/journal.c:jbd2_log_start_commit
```
**Symbols:**

```
ffffffff813e2d50-ffffffff813e2de8: __jbd2_log_start_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __jbd2_log_start_commit(journal_t *journal, tid_t target);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff813ef650)
Location: fs/jbd2/journal.c:481
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_start_commit
  - fs/jbd2/journal.c:jbd2_log_start_commit
```
**Symbols:**

```
ffffffff813ef650-ffffffff813ef6e8: __jbd2_log_start_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __jbd2_log_start_commit(journal_t *journal, tid_t target);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff81405010)
Location: fs/jbd2/journal.c:481
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_start_commit
  - fs/jbd2/journal.c:jbd2_log_start_commit
```
**Symbols:**

```
ffffffff81405010-ffffffff814050a8: __jbd2_log_start_commit (STB_GLOBAL)
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
