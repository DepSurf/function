# Function: <code>n_tty_receive_buf_closing</code>

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
In drivers/tty/n_tty.c (ffffffff814e7bde)
Location: drivers/tty/n_tty.c:1546
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
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
In drivers/tty/n_tty.c (ffffffff81538cd2)
Location: drivers/tty/n_tty.c:1517
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
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
In drivers/tty/n_tty.c (ffffffff815653e2)
Location: drivers/tty/n_tty.c:1517
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
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
In drivers/tty/n_tty.c (ffffffff8157850c)
Location: drivers/tty/n_tty.c:1517
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
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
In drivers/tty/n_tty.c (ffffffff815dce92)
Location: drivers/tty/n_tty.c:1515
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
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
In drivers/tty/n_tty.c (0)
Location: drivers/tty/n_tty.c:1533
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
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
In drivers/tty/n_tty.c (0)
Location: drivers/tty/n_tty.c:1546
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
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
In drivers/tty/n_tty.c (0)
Location: drivers/tty/n_tty.c:1548
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
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
In drivers/tty/n_tty.c (0)
Location: drivers/tty/n_tty.c:1548
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void n_tty_receive_buf_closing(struct tty_struct *tty, const unsigned char *cp, char *fp, int count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/n_tty.c (ffffffff81739190)
Location: drivers/tty/n_tty.c:1548
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:__receive_buf
```
**Symbols:**

```
ffffffff81739190-ffffffff81739293: n_tty_receive_buf_closing (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void n_tty_receive_buf_closing(struct tty_struct *tty, const unsigned char *cp, char *fp, int count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/n_tty.c (ffffffff81755190)
Location: drivers/tty/n_tty.c:1544
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:__receive_buf
```
**Symbols:**

```
ffffffff81755190-ffffffff81755293: n_tty_receive_buf_closing (STB_LOCAL)
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
In drivers/tty/n_tty.c (0)
Location: drivers/tty/n_tty.c:1545
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:__receive_buf
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
In drivers/tty/n_tty.c (0)
Location: drivers/tty/n_tty.c:1513
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:__receive_buf
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
In drivers/tty/n_tty.c (0)
Location: drivers/tty/n_tty.c:1498
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:__receive_buf
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void n_tty_receive_buf_closing(struct tty_struct *tty, const unsigned char *cp, const char *fp, int count, bool lookahead_done);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/n_tty.c (0)
Location: drivers/tty/n_tty.c:1542
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:__receive_buf
  - drivers/tty/n_tty.c:__receive_buf
```
**Symbols:**

```
ffffffff81a4f970-ffffffff81a4fb0c: n_tty_receive_buf_closing (STB_LOCAL)
ffffffff82095035-ffffffff8209508d: n_tty_receive_buf_closing.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void n_tty_receive_buf_closing(struct tty_struct *tty, const unsigned char *cp, const char *fp, int count, bool lookahead_done);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/n_tty.c (0)
Location: drivers/tty/n_tty.c:1541
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:__receive_buf
  - drivers/tty/n_tty.c:__receive_buf
```
**Symbols:**

```
ffffffff81a99b80-ffffffff81a99d16: n_tty_receive_buf_closing (STB_LOCAL)
ffffffff82115e53-ffffffff82115eab: n_tty_receive_buf_closing.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void n_tty_receive_buf_closing(struct tty_struct *tty, const u8 *cp, const u8 *fp, size_t count, bool lookahead_done);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/n_tty.c (0)
Location: drivers/tty/n_tty.c:1558
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:__receive_buf
  - drivers/tty/n_tty.c:__receive_buf
```
**Symbols:**

```
ffffffff81aec7a0-ffffffff81aec939: n_tty_receive_buf_closing (STB_LOCAL)
ffffffff821f3b5a-ffffffff821f3bb2: n_tty_receive_buf_closing.cold (STB_LOCAL)
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
In drivers/tty/n_tty.c (0)
Location: drivers/tty/n_tty.c:1548
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
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
In drivers/tty/n_tty.c (0)
Location: drivers/tty/n_tty.c:1548
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
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
In drivers/tty/n_tty.c (0)
Location: drivers/tty/n_tty.c:1548
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
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
In drivers/tty/n_tty.c (ffffffe000533128)
Location: drivers/tty/n_tty.c:1548
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
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
In drivers/tty/n_tty.c (0)
Location: drivers/tty/n_tty.c:1548
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
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
In drivers/tty/n_tty.c (0)
Location: drivers/tty/n_tty.c:1548
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
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
In drivers/tty/n_tty.c (0)
Location: drivers/tty/n_tty.c:1548
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
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
In drivers/tty/n_tty.c (0)
Location: drivers/tty/n_tty.c:1548
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>const unsigned char *cp</code> ➡️ <code>const u8 *cp</code>
</li>
<li>
<b>Param type changed. </b>
<code>const char *fp</code> ➡️ <code>const u8 *fp</code>
</li>
<li>
<b>Param type changed. </b>
<code>int count</code> ➡️ <code>size_t count</code>
</li>
</ul>
</details>
</li>
</ul>
