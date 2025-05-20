# Function: <code>errseq_check</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int errseq_check(errseq_t *eseq, errseq_t since);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/errseq.c (ffffffff8146c6b0)
Location: lib/errseq.c:149
Inline: False
Direct callers:
  - mm/filemap.c:file_check_and_advance_wb_err
```
**Symbols:**

```
ffffffff8146c6b0-ffffffff8146c6cb: errseq_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int errseq_check(errseq_t *eseq, errseq_t since);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/errseq.c (ffffffff814989d0)
Location: lib/errseq.c:147
Inline: False
Direct callers:
  - mm/filemap.c:file_check_and_advance_wb_err
```
**Symbols:**

```
ffffffff814989d0-ffffffff814989eb: errseq_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int errseq_check(errseq_t *eseq, errseq_t since);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/errseq.c (ffffffff814cdbe0)
Location: lib/errseq.c:144
Inline: False
Direct callers:
  - mm/filemap.c:file_check_and_advance_wb_err
```
**Symbols:**

```
ffffffff814cdbe0-ffffffff814cdbf6: errseq_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int errseq_check(errseq_t *eseq, errseq_t since);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/errseq.c (ffffffff814e24b0)
Location: lib/errseq.c:144
Inline: False
Direct callers:
  - mm/filemap.c:file_check_and_advance_wb_err
```
**Symbols:**

```
ffffffff814e24b0-ffffffff814e24c6: errseq_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int errseq_check(errseq_t *eseq, errseq_t since);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/errseq.c (ffffffff8150e390)
Location: lib/errseq.c:144
Inline: False
Direct callers:
  - mm/filemap.c:file_check_and_advance_wb_err
```
**Symbols:**

```
ffffffff8150e390-ffffffff8150e3a6: errseq_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int errseq_check(errseq_t *eseq, errseq_t since);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/errseq.c (ffffffff8152c2b0)
Location: lib/errseq.c:144
Inline: False
Direct callers:
  - mm/filemap.c:file_check_and_advance_wb_err
```
**Symbols:**

```
ffffffff8152c2b0-ffffffff8152c2c6: errseq_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int errseq_check(errseq_t *eseq, errseq_t since);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/errseq.c (ffffffff8158fc20)
Location: lib/errseq.c:144
Inline: False
Direct callers:
  - mm/filemap.c:file_check_and_advance_wb_err
  - fs/ext4/ext4_jbd2.c:ext4_check_bdev_write_error
```
**Symbols:**

```
ffffffff8158fc20-ffffffff8158fc36: errseq_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int errseq_check(errseq_t *eseq, errseq_t since);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/errseq.c (ffffffff815ac790)
Location: lib/errseq.c:145
Inline: False
Direct callers:
  - mm/filemap.c:file_check_and_advance_wb_err
  - fs/ext4/ext4_jbd2.c:ext4_check_bdev_write_error
```
**Symbols:**

```
ffffffff815ac790-ffffffff815ac7a6: errseq_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int errseq_check(errseq_t *eseq, errseq_t since);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/errseq.c (ffffffff815b7400)
Location: lib/errseq.c:145
Inline: False
Direct callers:
  - mm/filemap.c:file_check_and_advance_wb_err
  - fs/ext4/ext4_jbd2.c:__ext4_journal_get_write_access
```
**Symbols:**

```
ffffffff815b7400-ffffffff815b7416: errseq_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int errseq_check(errseq_t *eseq, errseq_t since);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/errseq.c (ffffffff8161da30)
Location: lib/errseq.c:145
Inline: False
Direct callers:
  - mm/filemap.c:file_check_and_advance_wb_err
  - fs/ext4/ext4_jbd2.c:__ext4_journal_get_write_access
```
**Symbols:**

```
ffffffff8161da30-ffffffff8161da46: errseq_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int errseq_check(errseq_t *eseq, errseq_t since);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/errseq.c (ffffffff816eb5c0)
Location: lib/errseq.c:145
Inline: False
Direct callers:
  - mm/filemap.c:file_check_and_advance_wb_err
  - fs/ext4/ext4_jbd2.c:__ext4_journal_get_write_access
```
**Symbols:**

```
ffffffff816eb5c0-ffffffff816eb5e0: errseq_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int errseq_check(errseq_t *eseq, errseq_t since);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/errseq.c (ffffffff817dbcc0)
Location: lib/errseq.c:145
Inline: False
Direct callers:
  - mm/filemap.c:file_check_and_advance_wb_err
  - fs/ext4/ext4_jbd2.c:__ext4_journal_get_write_access
```
**Symbols:**

```
ffffffff817dbcc0-ffffffff817dbce0: errseq_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int errseq_check(errseq_t *eseq, errseq_t since);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/errseq.c (ffffffff8181b080)
Location: lib/errseq.c:145
Inline: False
Direct callers:
  - mm/filemap.c:file_check_and_advance_wb_err
  - fs/ext4/ext4_jbd2.c:__ext4_journal_get_write_access
```
**Symbols:**

```
ffffffff8181b080-ffffffff8181b0a0: errseq_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int errseq_check(errseq_t *eseq, errseq_t since);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/errseq.c (ffffffff818603c0)
Location: lib/errseq.c:145
Inline: False
Direct callers:
  - mm/filemap.c:file_check_and_advance_wb_err
  - fs/ext4/ext4_jbd2.c:__ext4_journal_get_write_access
  - fs/jbd2/transaction.c:jbd2_journal_get_write_access
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
```
**Symbols:**

```
ffffffff818603c0-ffffffff818603e0: errseq_check (STB_GLOBAL)
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
int errseq_check(errseq_t *eseq, errseq_t since);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/errseq.c (ffff800010638140)
Location: lib/errseq.c:144
Inline: False
Direct callers:
  - mm/filemap.c:file_check_and_advance_wb_err
```
**Symbols:**

```
ffff800010638140-ffff800010638154: errseq_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int errseq_check(errseq_t *eseq, errseq_t since);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/errseq.c (c07ddaa0)
Location: lib/errseq.c:144
Inline: False
Direct callers:
  - mm/filemap.c:file_check_and_advance_wb_err
```
**Symbols:**

```
c07ddaa0-c07ddac4: errseq_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int errseq_check(errseq_t *eseq, errseq_t since);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/errseq.c (c0000000007de430)
Location: lib/errseq.c:144
Inline: False
Direct callers:
  - mm/filemap.c:file_check_and_advance_wb_err
```
**Symbols:**

```
c0000000007de430-c0000000007de460: errseq_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int errseq_check(errseq_t *eseq, errseq_t since);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/errseq.c (ffffffe000464ff4)
Location: lib/errseq.c:144
Inline: False
Direct callers:
  - mm/filemap.c:file_check_and_advance_wb_err
```
**Symbols:**

```
ffffffe000464ff4-ffffffe00046501a: errseq_check (STB_GLOBAL)
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
int errseq_check(errseq_t *eseq, errseq_t since);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/errseq.c (ffffffff81524890)
Location: lib/errseq.c:144
Inline: False
Direct callers:
  - mm/filemap.c:file_check_and_advance_wb_err
```
**Symbols:**

```
ffffffff81524890-ffffffff815248a6: errseq_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int errseq_check(errseq_t *eseq, errseq_t since);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/errseq.c (ffffffff81514b70)
Location: lib/errseq.c:144
Inline: False
Direct callers:
  - mm/filemap.c:file_check_and_advance_wb_err
```
**Symbols:**

```
ffffffff81514b70-ffffffff81514b86: errseq_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int errseq_check(errseq_t *eseq, errseq_t since);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/errseq.c (ffffffff81520920)
Location: lib/errseq.c:144
Inline: False
Direct callers:
  - mm/filemap.c:file_check_and_advance_wb_err
```
**Symbols:**

```
ffffffff81520920-ffffffff81520936: errseq_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int errseq_check(errseq_t *eseq, errseq_t since);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/errseq.c (ffffffff8153a2a0)
Location: lib/errseq.c:144
Inline: False
Direct callers:
  - mm/filemap.c:file_check_and_advance_wb_err
```
**Symbols:**

```
ffffffff8153a2a0-ffffffff8153a2b6: errseq_check (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
