# Function: <code>__jbd2_journal_unreserve_handle</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __jbd2_journal_unreserve_handle(handle_t *handle, transaction_t *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff8143c9a0)
Location: fs/jbd2/transaction.c:544
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:stop_this_handle
  - fs/jbd2/transaction.c:jbd2_journal_free_reserved
```
**Symbols:**

```
ffffffff8143c9a0-ffffffff8143c9f7: __jbd2_journal_unreserve_handle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __jbd2_journal_unreserve_handle(handle_t *handle, transaction_t *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff81458d20)
Location: fs/jbd2/transaction.c:546
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:stop_this_handle
  - fs/jbd2/transaction.c:jbd2_journal_free_reserved
```
**Symbols:**

```
ffffffff81458d20-ffffffff81458d77: __jbd2_journal_unreserve_handle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __jbd2_journal_unreserve_handle(handle_t *handle, transaction_t *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff8145e720)
Location: fs/jbd2/transaction.c:551
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:stop_this_handle
  - fs/jbd2/transaction.c:jbd2_journal_free_reserved
```
**Symbols:**

```
ffffffff8145e720-ffffffff8145e777: __jbd2_journal_unreserve_handle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __jbd2_journal_unreserve_handle(handle_t *handle, transaction_t *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff814b3a90)
Location: fs/jbd2/transaction.c:568
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:stop_this_handle
  - fs/jbd2/transaction.c:jbd2_journal_free_reserved
```
**Symbols:**

```
ffffffff814b3a90-ffffffff814b3ae7: __jbd2_journal_unreserve_handle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __jbd2_journal_unreserve_handle(handle_t *handle, transaction_t *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff8153d250)
Location: fs/jbd2/transaction.c:563
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:stop_this_handle
  - fs/jbd2/transaction.c:jbd2_journal_start_reserved
  - fs/jbd2/transaction.c:jbd2_journal_start_reserved
```
**Symbols:**

```
ffffffff8153d250-ffffffff8153d2b5: __jbd2_journal_unreserve_handle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __jbd2_journal_unreserve_handle(handle_t *handle, transaction_t *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff815dba50)
Location: fs/jbd2/transaction.c:563
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:stop_this_handle
  - fs/jbd2/transaction.c:jbd2_journal_start_reserved
  - fs/jbd2/transaction.c:jbd2_journal_start_reserved
```
**Symbols:**

```
ffffffff815dba50-ffffffff815dbab5: __jbd2_journal_unreserve_handle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __jbd2_journal_unreserve_handle(handle_t *handle, transaction_t *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff81613510)
Location: fs/jbd2/transaction.c:563
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:stop_this_handle
  - fs/jbd2/transaction.c:jbd2_journal_start_reserved
  - fs/jbd2/transaction.c:jbd2_journal_start_reserved
```
**Symbols:**

```
ffffffff81613510-ffffffff81613575: __jbd2_journal_unreserve_handle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __jbd2_journal_unreserve_handle(handle_t *handle, transaction_t *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff8164c310)
Location: fs/jbd2/transaction.c:563
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:stop_this_handle
  - fs/jbd2/transaction.c:jbd2_journal_start_reserved
  - fs/jbd2/transaction.c:jbd2_journal_start_reserved
```
**Symbols:**

```
ffffffff8164c310-ffffffff8164c375: __jbd2_journal_unreserve_handle (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
