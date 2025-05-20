# Function: <code>canon_copy_from_read_buf</code>

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
In drivers/tty/n_tty.c (ffffffff814e6372)
Location: drivers/tty/n_tty.c:2045
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_read
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
In drivers/tty/n_tty.c (ffffffff815371fc)
Location: drivers/tty/n_tty.c:1995
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_read
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
In drivers/tty/n_tty.c (ffffffff8156391c)
Location: drivers/tty/n_tty.c:1995
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_read
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
In drivers/tty/n_tty.c (ffffffff81578d36)
Location: drivers/tty/n_tty.c:1995
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_read
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
In drivers/tty/n_tty.c (ffffffff815dd6c9)
Location: drivers/tty/n_tty.c:1993
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_read
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
In drivers/tty/n_tty.c (ffffffff8161697b)
Location: drivers/tty/n_tty.c:2002
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_read
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
In drivers/tty/n_tty.c (ffffffff81633ae8)
Location: drivers/tty/n_tty.c:2016
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_read
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
In drivers/tty/n_tty.c (ffffffff816668f0)
Location: drivers/tty/n_tty.c:2018
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_read
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
In drivers/tty/n_tty.c (ffffffff81688bca)
Location: drivers/tty/n_tty.c:2018
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_read
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int canon_copy_from_read_buf(struct tty_struct *tty, unsigned char **b, size_t *nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/n_tty.c (ffffffff8173a3c0)
Location: drivers/tty/n_tty.c:2018
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:n_tty_read
```
**Symbols:**

```
ffffffff8173a3c0-ffffffff8173a5c5: canon_copy_from_read_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool canon_copy_from_read_buf(struct tty_struct *tty, unsigned char **kbp, size_t *nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/n_tty.c (ffffffff817557a0)
Location: drivers/tty/n_tty.c:2014
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
```
**Symbols:**

```
ffffffff817557a0-ffffffff8175599b: canon_copy_from_read_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool canon_copy_from_read_buf(struct tty_struct *tty, unsigned char **kbp, size_t *nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/n_tty.c (ffffffff81739670)
Location: drivers/tty/n_tty.c:2017
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
```
**Symbols:**

```
ffffffff81739670-ffffffff81739990: canon_copy_from_read_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool canon_copy_from_read_buf(struct tty_struct *tty, unsigned char **kbp, size_t *nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/n_tty.c (ffffffff817ba130)
Location: drivers/tty/n_tty.c:1951
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
```
**Symbols:**

```
ffffffff817ba130-ffffffff817ba43f: canon_copy_from_read_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool canon_copy_from_read_buf(struct tty_struct *tty, unsigned char **kbp, size_t *nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/n_tty.c (ffffffff818f6240)
Location: drivers/tty/n_tty.c:1927
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
```
**Symbols:**

```
ffffffff818f6240-ffffffff818f6465: canon_copy_from_read_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool canon_copy_from_read_buf(struct tty_struct *tty, unsigned char **kbp, size_t *nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/n_tty.c (ffffffff81a4ec50)
Location: drivers/tty/n_tty.c:1980
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
```
**Symbols:**

```
ffffffff81a4ec50-ffffffff81a4ee68: canon_copy_from_read_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool canon_copy_from_read_buf(struct tty_struct *tty, unsigned char **kbp, size_t *nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/n_tty.c (ffffffff81a98f50)
Location: drivers/tty/n_tty.c:1990
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
```
**Symbols:**

```
ffffffff81a98f50-ffffffff81a9916b: canon_copy_from_read_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool canon_copy_from_read_buf(const struct tty_struct *tty, u8 **kbp, size_t *nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/n_tty.c (ffffffff81aeb5f0)
Location: drivers/tty/n_tty.c:2008
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
```
**Symbols:**

```
ffffffff81aeb5f0-ffffffff81aeb80b: canon_copy_from_read_buf (STB_LOCAL)
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
In drivers/tty/n_tty.c (ffff800010856448)
Location: drivers/tty/n_tty.c:2018
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_read
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
In drivers/tty/n_tty.c (c0960b30)
Location: drivers/tty/n_tty.c:2018
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_read
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
In drivers/tty/n_tty.c (c0000000008f7fa0)
Location: drivers/tty/n_tty.c:2018
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_read
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
In drivers/tty/n_tty.c (ffffffe0005337d4)
Location: drivers/tty/n_tty.c:2018
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_read
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
In drivers/tty/n_tty.c (ffffffff8164e64a)
Location: drivers/tty/n_tty.c:2018
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_read
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
In drivers/tty/n_tty.c (ffffffff8162ea9a)
Location: drivers/tty/n_tty.c:2018
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_read
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
In drivers/tty/n_tty.c (ffffffff8167ca0a)
Location: drivers/tty/n_tty.c:2018
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_read
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
In drivers/tty/n_tty.c (ffffffff8169706a)
Location: drivers/tty/n_tty.c:2018
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_read
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned char **kbp</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned char **b</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>bool</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct tty_struct *tty</code> ➡️ <code>const struct tty_struct *tty</code>
</li>
<li>
<b>Param type changed. </b>
<code>unsigned char **kbp</code> ➡️ <code>u8 **kbp</code>
</li>
</ul>
</details>
</li>
</ul>
