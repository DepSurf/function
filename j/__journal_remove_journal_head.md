# Function: <code>__journal_remove_journal_head</code>

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
In fs/jbd2/journal.c (ffffffff812f30f7)
Location: fs/jbd2/journal.c:2498
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
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
In fs/jbd2/journal.c (ffffffff81320abd)
Location: fs/jbd2/journal.c:2515
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
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
In fs/jbd2/journal.c (ffffffff8133696d)
Location: fs/jbd2/journal.c:2485
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
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
In fs/jbd2/journal.c (ffffffff8134b61d)
Location: fs/jbd2/journal.c:2508
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
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
In fs/jbd2/journal.c (ffffffff8136fc49)
Location: fs/jbd2/journal.c:2524
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
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
In fs/jbd2/journal.c (ffffffff8139e158)
Location: fs/jbd2/journal.c:2534
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
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
In fs/jbd2/journal.c (ffffffff813b6ec8)
Location: fs/jbd2/journal.c:2534
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
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
In fs/jbd2/journal.c (ffffffff813e15c4)
Location: fs/jbd2/journal.c:2522
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
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
In fs/jbd2/journal.c (ffffffff813fb614)
Location: fs/jbd2/journal.c:2517
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __journal_remove_journal_head(struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff81445ed0)
Location: fs/jbd2/journal.c:2548
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
```
**Symbols:**

```
ffffffff81445ed0-ffffffff81445f2b: __journal_remove_journal_head (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __journal_remove_journal_head(struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff814622b0)
Location: fs/jbd2/journal.c:2795
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
```
**Symbols:**

```
ffffffff814622b0-ffffffff8146230b: __journal_remove_journal_head (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __journal_remove_journal_head(struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff81467960)
Location: fs/jbd2/journal.c:2795
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
```
**Symbols:**

```
ffffffff81467960-ffffffff814679bb: __journal_remove_journal_head (STB_LOCAL)
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
In fs/jbd2/journal.c (ffffffff814c17eb)
Location: fs/jbd2/journal.c:2975
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
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
In fs/jbd2/journal.c (ffffffff8154c182)
Location: fs/jbd2/journal.c:2978
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
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
In fs/jbd2/journal.c (ffffffff815ebf62)
Location: fs/jbd2/journal.c:2981
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
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
In fs/jbd2/journal.c (ffffffff81623a42)
Location: fs/jbd2/journal.c:2981
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
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
In fs/jbd2/journal.c (ffffffff8165cae2)
Location: fs/jbd2/journal.c:2968
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
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
In fs/jbd2/journal.c (ffff8000104d8df0)
Location: fs/jbd2/journal.c:2517
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
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
In fs/jbd2/journal.c (c069ad0c)
Location: fs/jbd2/journal.c:2517
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
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
In fs/jbd2/journal.c (c000000000613de0)
Location: fs/jbd2/journal.c:2517
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
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
In fs/jbd2/journal.c (ffffffe00034e758)
Location: fs/jbd2/journal.c:2517
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
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
In fs/jbd2/journal.c (ffffffff813f3bf4)
Location: fs/jbd2/journal.c:2517
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
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
In fs/jbd2/journal.c (ffffffff813e4674)
Location: fs/jbd2/journal.c:2517
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
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
In fs/jbd2/journal.c (ffffffff813f0f74)
Location: fs/jbd2/journal.c:2517
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
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
In fs/jbd2/journal.c (ffffffff81406b3b)
Location: fs/jbd2/journal.c:2517
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
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
