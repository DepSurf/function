# Function: <code>tty_copy</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void tty_copy(struct tty_struct *tty, void *to, size_t tail, size_t n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/n_tty.c (ffffffff81755650)
Location: drivers/tty/n_tty.c:167
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:canon_copy_from_read_buf
  - drivers/tty/n_tty.c:canon_copy_from_read_buf
  - drivers/tty/n_tty.c:canon_copy_from_read_buf
```
**Symbols:**

```
ffffffff81755650-ffffffff81755793: tty_copy (STB_LOCAL)
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
In drivers/tty/n_tty.c (ffffffff81739779)
Location: drivers/tty/n_tty.c:168
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:canon_copy_from_read_buf
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
In drivers/tty/n_tty.c (ffffffff817ba237)
Location: drivers/tty/n_tty.c:168
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:canon_copy_from_read_buf
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void tty_copy(struct tty_struct *tty, void *to, size_t tail, size_t n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/n_tty.c (ffffffff818f60e0)
Location: drivers/tty/n_tty.c:168
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:canon_copy_from_read_buf
  - drivers/tty/n_tty.c:canon_copy_from_read_buf
  - drivers/tty/n_tty.c:canon_copy_from_read_buf
```
**Symbols:**

```
ffffffff818f60e0-ffffffff818f6238: tty_copy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void tty_copy(struct tty_struct *tty, void *to, size_t tail, size_t n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/n_tty.c (ffffffff81a4eae0)
Location: drivers/tty/n_tty.c:171
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:canon_copy_from_read_buf
  - drivers/tty/n_tty.c:canon_copy_from_read_buf
  - drivers/tty/n_tty.c:canon_copy_from_read_buf
```
**Symbols:**

```
ffffffff81a4eae0-ffffffff81a4ec38: tty_copy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void tty_copy(struct tty_struct *tty, void *to, size_t tail, size_t n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/n_tty.c (ffffffff81a98de0)
Location: drivers/tty/n_tty.c:170
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:canon_copy_from_read_buf
  - drivers/tty/n_tty.c:canon_copy_from_read_buf
  - drivers/tty/n_tty.c:canon_copy_from_read_buf
```
**Symbols:**

```
ffffffff81a98de0-ffffffff81a98f38: tty_copy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void tty_copy(const struct tty_struct *tty, void *to, size_t tail, size_t n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/n_tty.c (ffffffff81aeb480)
Location: drivers/tty/n_tty.c:167
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:canon_copy_from_read_buf
  - drivers/tty/n_tty.c:canon_copy_from_read_buf
  - drivers/tty/n_tty.c:canon_copy_from_read_buf
```
**Symbols:**

```
ffffffff81aeb480-ffffffff81aeb5d1: tty_copy (STB_LOCAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct tty_struct *tty</code> ➡️ <code>const struct tty_struct *tty</code>
</li>
</ul>
</details>
</li>
</ul>
