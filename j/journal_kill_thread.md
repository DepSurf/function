# Function: <code>journal_kill_thread</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff812f1bbd)
Location: fs/jbd2/journal.c:299
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_destroy
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff8131f45f)
Location: fs/jbd2/journal.c:300
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_destroy
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff813354df)
Location: fs/jbd2/journal.c:300
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_destroy
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff8134a25f)
Location: fs/jbd2/journal.c:309
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_destroy
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff8136e8af)
Location: fs/jbd2/journal.c:308
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_destroy
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff8139cf16)
Location: fs/jbd2/journal.c:305
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_destroy
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff813b5c86)
Location: fs/jbd2/journal.c:305
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_destroy
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff813e0387)
Location: fs/jbd2/journal.c:288
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_destroy
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff813fa3c7)
Location: fs/jbd2/journal.c:286
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_destroy
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void journal_kill_thread(journal_t *journal);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff814453e0)
Location: fs/jbd2/journal.c:285
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_destroy
```
**Symbols:**

```
ffffffff814453e0-ffffffff814454c9: journal_kill_thread (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void journal_kill_thread(journal_t *journal);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff81461aa0)
Location: fs/jbd2/journal.c:289
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_destroy
```
**Symbols:**

```
ffffffff81461aa0-ffffffff81461b89: journal_kill_thread (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff81469a07)
Location: fs/jbd2/journal.c:289
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_destroy
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff814bfef7)
Location: fs/jbd2/journal.c:289
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_destroy
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff8154a6e6)
Location: fs/jbd2/journal.c:289
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_destroy
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff815ea1e6)
Location: fs/jbd2/journal.c:286
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_destroy
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff81621fd6)
Location: fs/jbd2/journal.c:285
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_destroy
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff8165a4f6)
Location: fs/jbd2/journal.c:277
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_destroy
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffff8000104d733c)
Location: fs/jbd2/journal.c:286
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_destroy
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (c0699498)
Location: fs/jbd2/journal.c:286
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_destroy
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (c000000000611f6c)
Location: fs/jbd2/journal.c:286
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_destroy
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffe00034d206)
Location: fs/jbd2/journal.c:286
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_destroy
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff813f29a7)
Location: fs/jbd2/journal.c:286
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_destroy
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff813e3427)
Location: fs/jbd2/journal.c:286
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_destroy
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff813efd27)
Location: fs/jbd2/journal.c:286
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_destroy
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff81405737)
Location: fs/jbd2/journal.c:286
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_destroy
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
