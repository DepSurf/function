# Function: <code>add_echo_byte</code>

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
In drivers/tty/n_tty.c (ffffffff814e4362)
Location: drivers/tty/n_tty.c:839
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:echo_char
  - drivers/tty/n_tty.c:echo_char
  - drivers/tty/n_tty.c:echo_char
  - drivers/tty/n_tty.c:echo_char
  - drivers/tty/n_tty.c:n_tty_receive_char_lnext
  - drivers/tty/n_tty.c:n_tty_receive_char_lnext
  - drivers/tty/n_tty.c:n_tty_receive_char_lnext
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
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
In drivers/tty/n_tty.c (ffffffff81538d99)
Location: drivers/tty/n_tty.c:813
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_char_lnext
  - drivers/tty/n_tty.c:n_tty_receive_char_lnext
  - drivers/tty/n_tty.c:n_tty_receive_char_lnext
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:echo_char
  - drivers/tty/n_tty.c:echo_char
  - drivers/tty/n_tty.c:echo_char
  - drivers/tty/n_tty.c:echo_char
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
In drivers/tty/n_tty.c (ffffffff815654a9)
Location: drivers/tty/n_tty.c:813
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_char_lnext
  - drivers/tty/n_tty.c:n_tty_receive_char_lnext
  - drivers/tty/n_tty.c:n_tty_receive_char_lnext
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:echo_char
  - drivers/tty/n_tty.c:echo_char
  - drivers/tty/n_tty.c:echo_char
  - drivers/tty/n_tty.c:echo_char
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
In drivers/tty/n_tty.c (ffffffff815784e6)
Location: drivers/tty/n_tty.c:813
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_char_lnext
  - drivers/tty/n_tty.c:n_tty_receive_char_lnext
  - drivers/tty/n_tty.c:n_tty_receive_char_lnext
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:echo_char
  - drivers/tty/n_tty.c:echo_char
  - drivers/tty/n_tty.c:echo_char
  - drivers/tty/n_tty.c:echo_char
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
In drivers/tty/n_tty.c (ffffffff815dce6c)
Location: drivers/tty/n_tty.c:811
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_char_lnext
  - drivers/tty/n_tty.c:n_tty_receive_char_lnext
  - drivers/tty/n_tty.c:n_tty_receive_char_lnext
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:echo_char
  - drivers/tty/n_tty.c:echo_char
  - drivers/tty/n_tty.c:echo_char
  - drivers/tty/n_tty.c:echo_char
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
In drivers/tty/n_tty.c (ffffffff81615a6d)
Location: drivers/tty/n_tty.c:826
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_char_lnext
  - drivers/tty/n_tty.c:n_tty_receive_char_lnext
  - drivers/tty/n_tty.c:n_tty_receive_char_lnext
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:echo_char
  - drivers/tty/n_tty.c:echo_char
  - drivers/tty/n_tty.c:echo_char
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
In drivers/tty/n_tty.c (ffffffff81632a62)
Location: drivers/tty/n_tty.c:839
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_char_lnext
  - drivers/tty/n_tty.c:n_tty_receive_char_lnext
  - drivers/tty/n_tty.c:n_tty_receive_char_lnext
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:echo_char
  - drivers/tty/n_tty.c:echo_char
  - drivers/tty/n_tty.c:echo_char
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
In drivers/tty/n_tty.c (ffffffff8166754d)
Location: drivers/tty/n_tty.c:841
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_char_lnext
  - drivers/tty/n_tty.c:n_tty_receive_char_lnext
  - drivers/tty/n_tty.c:n_tty_receive_char_lnext
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:echo_char
  - drivers/tty/n_tty.c:echo_char
  - drivers/tty/n_tty.c:echo_char
  - drivers/tty/n_tty.c:echo_char
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
In drivers/tty/n_tty.c (ffffffff81689c9d)
Location: drivers/tty/n_tty.c:841
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_char_lnext
  - drivers/tty/n_tty.c:n_tty_receive_char_lnext
  - drivers/tty/n_tty.c:n_tty_receive_char_lnext
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:echo_char
  - drivers/tty/n_tty.c:echo_char
  - drivers/tty/n_tty.c:echo_char
  - drivers/tty/n_tty.c:echo_char
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/n_tty.c (ffffffff8173b997)
Location: drivers/tty/n_tty.c:841
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_receive_buf_fast
  - drivers/tty/n_tty.c:n_tty_receive_buf_fast
  - drivers/tty/n_tty.c:n_tty_receive_buf_standard
  - drivers/tty/n_tty.c:n_tty_receive_buf_standard
  - drivers/tty/n_tty.c:n_tty_receive_char_lnext
  - drivers/tty/n_tty.c:n_tty_receive_char_lnext
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/n_tty.c (ffffffff81757b07)
Location: drivers/tty/n_tty.c:837
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_receive_buf_fast
  - drivers/tty/n_tty.c:n_tty_receive_buf_fast
  - drivers/tty/n_tty.c:n_tty_receive_buf_standard
  - drivers/tty/n_tty.c:n_tty_receive_buf_standard
  - drivers/tty/n_tty.c:n_tty_receive_char_lnext
  - drivers/tty/n_tty.c:n_tty_receive_char_lnext
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
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
In drivers/tty/n_tty.c (ffffffff8173bbf1)
Location: drivers/tty/n_tty.c:838
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_receive_buf_fast
  - drivers/tty/n_tty.c:n_tty_receive_buf_fast
  - drivers/tty/n_tty.c:n_tty_receive_buf_standard
  - drivers/tty/n_tty.c:n_tty_receive_buf_standard
  - drivers/tty/n_tty.c:n_tty_receive_char_lnext
  - drivers/tty/n_tty.c:n_tty_receive_char_lnext
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
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
In drivers/tty/n_tty.c (ffffffff817bba46)
Location: drivers/tty/n_tty.c:838
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_receive_char
  - drivers/tty/n_tty.c:n_tty_receive_char
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
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
In drivers/tty/n_tty.c (ffffffff818f8029)
Location: drivers/tty/n_tty.c:823
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_receive_char
  - drivers/tty/n_tty.c:n_tty_receive_char
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
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
In drivers/tty/n_tty.c (ffffffff81a50db9)
Location: drivers/tty/n_tty.c:828
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_receive_char
  - drivers/tty/n_tty.c:n_tty_receive_char
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
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
In drivers/tty/n_tty.c (ffffffff81a9b094)
Location: drivers/tty/n_tty.c:827
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_receive_char
  - drivers/tty/n_tty.c:n_tty_receive_char
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
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
In drivers/tty/n_tty.c (ffffffff81aedf14)
Location: drivers/tty/n_tty.c:818
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_receive_char
  - drivers/tty/n_tty.c:n_tty_receive_char
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_canon
  - drivers/tty/n_tty.c:n_tty_receive_char_canon
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
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
In drivers/tty/n_tty.c (ffff80001085823c)
Location: drivers/tty/n_tty.c:841
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_char_lnext
  - drivers/tty/n_tty.c:n_tty_receive_char_lnext
  - drivers/tty/n_tty.c:n_tty_receive_char_lnext
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
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
In drivers/tty/n_tty.c (c0961dcc)
Location: drivers/tty/n_tty.c:841
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_char_lnext
  - drivers/tty/n_tty.c:n_tty_receive_char_lnext
  - drivers/tty/n_tty.c:n_tty_receive_char_lnext
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:echo_char
  - drivers/tty/n_tty.c:echo_char
  - drivers/tty/n_tty.c:echo_char
  - drivers/tty/n_tty.c:echo_char
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
In drivers/tty/n_tty.c (c0000000008f7134)
Location: drivers/tty/n_tty.c:841
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_char_lnext
  - drivers/tty/n_tty.c:n_tty_receive_char_lnext
  - drivers/tty/n_tty.c:n_tty_receive_char_lnext
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:echo_char
  - drivers/tty/n_tty.c:echo_char
  - drivers/tty/n_tty.c:echo_char
  - drivers/tty/n_tty.c:echo_char
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
In drivers/tty/n_tty.c (ffffffe000532d68)
Location: drivers/tty/n_tty.c:841
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_char_lnext
  - drivers/tty/n_tty.c:n_tty_receive_char_lnext
  - drivers/tty/n_tty.c:n_tty_receive_char_lnext
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:echo_char
  - drivers/tty/n_tty.c:echo_char
  - drivers/tty/n_tty.c:echo_char
  - drivers/tty/n_tty.c:echo_char
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
In drivers/tty/n_tty.c (ffffffff8164f71d)
Location: drivers/tty/n_tty.c:841
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_char_lnext
  - drivers/tty/n_tty.c:n_tty_receive_char_lnext
  - drivers/tty/n_tty.c:n_tty_receive_char_lnext
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:echo_char
  - drivers/tty/n_tty.c:echo_char
  - drivers/tty/n_tty.c:echo_char
  - drivers/tty/n_tty.c:echo_char
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
In drivers/tty/n_tty.c (ffffffff8162fb6d)
Location: drivers/tty/n_tty.c:841
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_char_lnext
  - drivers/tty/n_tty.c:n_tty_receive_char_lnext
  - drivers/tty/n_tty.c:n_tty_receive_char_lnext
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:echo_char
  - drivers/tty/n_tty.c:echo_char
  - drivers/tty/n_tty.c:echo_char
  - drivers/tty/n_tty.c:echo_char
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
In drivers/tty/n_tty.c (ffffffff8167dadd)
Location: drivers/tty/n_tty.c:841
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_char_lnext
  - drivers/tty/n_tty.c:n_tty_receive_char_lnext
  - drivers/tty/n_tty.c:n_tty_receive_char_lnext
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:echo_char
  - drivers/tty/n_tty.c:echo_char
  - drivers/tty/n_tty.c:echo_char
  - drivers/tty/n_tty.c:echo_char
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
In drivers/tty/n_tty.c (ffffffff8169813d)
Location: drivers/tty/n_tty.c:841
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_char_lnext
  - drivers/tty/n_tty.c:n_tty_receive_char_lnext
  - drivers/tty/n_tty.c:n_tty_receive_char_lnext
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:eraser
  - drivers/tty/n_tty.c:echo_char
  - drivers/tty/n_tty.c:echo_char
  - drivers/tty/n_tty.c:echo_char
  - drivers/tty/n_tty.c:echo_char
```
</details>
</li>
</ul>

## Differences
