# Function: <code>jbd2_get_transaction</code>

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
In fs/jbd2/transaction.c (ffffffff812e6f59)
Location: fs/jbd2/transaction.c:83
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:start_this_handle
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
In fs/jbd2/transaction.c (ffffffff81314adc)
Location: fs/jbd2/transaction.c:83
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:start_this_handle
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
In fs/jbd2/transaction.c (ffffffff8132aab8)
Location: fs/jbd2/transaction.c:83
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:start_this_handle
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
In fs/jbd2/transaction.c (ffffffff8133fcda)
Location: fs/jbd2/transaction.c:84
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:start_this_handle
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
In fs/jbd2/transaction.c (ffffffff813642ea)
Location: fs/jbd2/transaction.c:84
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:start_this_handle
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
In fs/jbd2/transaction.c (ffffffff81392c5f)
Location: fs/jbd2/transaction.c:79
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:start_this_handle
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
In fs/jbd2/transaction.c (ffffffff813ab966)
Location: fs/jbd2/transaction.c:79
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:start_this_handle
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
In fs/jbd2/transaction.c (ffffffff813d5b7e)
Location: fs/jbd2/transaction.c:80
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:start_this_handle
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
In fs/jbd2/transaction.c (ffffffff813efbb5)
Location: fs/jbd2/transaction.c:80
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:start_this_handle
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void jbd2_get_transaction(journal_t *journal, transaction_t *transaction);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff8143c710)
Location: fs/jbd2/transaction.c:102
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:start_this_handle
```
**Symbols:**

```
ffffffff8143c710-ffffffff8143c890: jbd2_get_transaction (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void jbd2_get_transaction(journal_t *journal, transaction_t *transaction);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff81458af0)
Location: fs/jbd2/transaction.c:102
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:start_this_handle
```
**Symbols:**

```
ffffffff81458af0-ffffffff81458c70: jbd2_get_transaction (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void jbd2_get_transaction(journal_t *journal, transaction_t *transaction);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff8145e470)
Location: fs/jbd2/transaction.c:102
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:start_this_handle
```
**Symbols:**

```
ffffffff8145e470-ffffffff8145e5f0: jbd2_get_transaction (STB_LOCAL)
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
In fs/jbd2/transaction.c (ffffffff814b42f4)
Location: fs/jbd2/transaction.c:102
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:start_this_handle
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
In fs/jbd2/transaction.c (ffffffff8153db90)
Location: fs/jbd2/transaction.c:102
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:start_this_handle
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
In fs/jbd2/transaction.c (ffffffff815dc400)
Location: fs/jbd2/transaction.c:102
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:start_this_handle
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
In fs/jbd2/transaction.c (ffffffff81613eaf)
Location: fs/jbd2/transaction.c:102
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:start_this_handle
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
In fs/jbd2/transaction.c (ffffffff8164cc9f)
Location: fs/jbd2/transaction.c:102
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:start_this_handle
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
In fs/jbd2/transaction.c (ffff8000104c9610)
Location: fs/jbd2/transaction.c:80
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:start_this_handle
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
In fs/jbd2/transaction.c (c068d07c)
Location: fs/jbd2/transaction.c:80
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:start_this_handle
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
In fs/jbd2/transaction.c (c000000000602068)
Location: fs/jbd2/transaction.c:80
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:start_this_handle
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
In fs/jbd2/transaction.c (ffffffe00034281e)
Location: fs/jbd2/transaction.c:80
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:start_this_handle
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
In fs/jbd2/transaction.c (ffffffff813e8195)
Location: fs/jbd2/transaction.c:80
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:start_this_handle
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
In fs/jbd2/transaction.c (ffffffff813d8c15)
Location: fs/jbd2/transaction.c:80
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:start_this_handle
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
In fs/jbd2/transaction.c (ffffffff813e5515)
Location: fs/jbd2/transaction.c:80
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:start_this_handle
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
In fs/jbd2/transaction.c (ffffffff813faae0)
Location: fs/jbd2/transaction.c:80
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:start_this_handle
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
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
</ul>
