# Function: <code>read_buf_addr</code>

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
In drivers/tty/n_tty.c (ffffffff814e4cbc)
Location: drivers/tty/n_tty.c:141
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:copy_from_read_buf
  - drivers/tty/n_tty.c:n_tty_receive_char_lnext
  - drivers/tty/n_tty.c:n_tty_receive_char_lnext
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
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
In drivers/tty/n_tty.c (ffffffff81537339)
Location: drivers/tty/n_tty.c:139
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:copy_from_read_buf
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_char_lnext
  - drivers/tty/n_tty.c:n_tty_receive_char_lnext
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
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
In drivers/tty/n_tty.c (ffffffff81563a59)
Location: drivers/tty/n_tty.c:139
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:copy_from_read_buf
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_char_lnext
  - drivers/tty/n_tty.c:n_tty_receive_char_lnext
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
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
In drivers/tty/n_tty.c (ffffffff81578e54)
Location: drivers/tty/n_tty.c:139
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:copy_from_read_buf
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
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
In drivers/tty/n_tty.c (ffffffff815dd7e7)
Location: drivers/tty/n_tty.c:137
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:copy_from_read_buf
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
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
In drivers/tty/n_tty.c (ffffffff81616ad8)
Location: drivers/tty/n_tty.c:139
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:copy_from_read_buf
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
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
In drivers/tty/n_tty.c (ffffffff81633c3d)
Location: drivers/tty/n_tty.c:139
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:copy_from_read_buf
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
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
In drivers/tty/n_tty.c (ffffffff81666a11)
Location: drivers/tty/n_tty.c:141
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:copy_from_read_buf
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
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
In drivers/tty/n_tty.c (ffffffff81688ce7)
Location: drivers/tty/n_tty.c:141
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:copy_from_read_buf
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
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
In drivers/tty/n_tty.c (ffffffff8173a63d)
Location: drivers/tty/n_tty.c:141
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:copy_from_read_buf
  - drivers/tty/n_tty.c:__receive_buf
  - drivers/tty/n_tty.c:n_tty_receive_buf_fast
  - drivers/tty/n_tty.c:n_tty_receive_buf_standard
  - drivers/tty/n_tty.c:n_tty_receive_buf_standard
  - drivers/tty/n_tty.c:n_tty_receive_buf_standard
  - drivers/tty/n_tty.c:n_tty_receive_char_lnext
  - drivers/tty/n_tty.c:n_tty_receive_char_lnext
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:tty_copy_to_user
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
In drivers/tty/n_tty.c (ffffffff81755506)
Location: drivers/tty/n_tty.c:141
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:copy_from_read_buf
  - drivers/tty/n_tty.c:__receive_buf
  - drivers/tty/n_tty.c:n_tty_receive_buf_fast
  - drivers/tty/n_tty.c:n_tty_receive_buf_standard
  - drivers/tty/n_tty.c:n_tty_receive_buf_standard
  - drivers/tty/n_tty.c:n_tty_receive_buf_standard
  - drivers/tty/n_tty.c:n_tty_receive_char_lnext
  - drivers/tty/n_tty.c:n_tty_receive_char_lnext
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:tty_copy
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
In drivers/tty/n_tty.c (ffffffff81739783)
Location: drivers/tty/n_tty.c:142
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:canon_copy_from_read_buf
  - drivers/tty/n_tty.c:copy_from_read_buf
  - drivers/tty/n_tty.c:__receive_buf
  - drivers/tty/n_tty.c:__receive_buf
  - drivers/tty/n_tty.c:__receive_buf
  - drivers/tty/n_tty.c:n_tty_receive_buf_fast
  - drivers/tty/n_tty.c:n_tty_receive_buf_standard
  - drivers/tty/n_tty.c:n_tty_receive_buf_standard
  - drivers/tty/n_tty.c:n_tty_receive_buf_standard
  - drivers/tty/n_tty.c:n_tty_receive_char_lnext
  - drivers/tty/n_tty.c:n_tty_receive_char_lnext
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
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
In drivers/tty/n_tty.c (ffffffff817ba241)
Location: drivers/tty/n_tty.c:142
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:canon_copy_from_read_buf
  - drivers/tty/n_tty.c:copy_from_read_buf
  - drivers/tty/n_tty.c:__receive_buf
  - drivers/tty/n_tty.c:__receive_buf
  - drivers/tty/n_tty.c:__receive_buf
  - drivers/tty/n_tty.c:n_tty_receive_buf_standard
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char
  - drivers/tty/n_tty.c:n_tty_receive_char
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
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
In drivers/tty/n_tty.c (ffffffff818f5f75)
Location: drivers/tty/n_tty.c:142
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:copy_from_read_buf
  - drivers/tty/n_tty.c:__receive_buf
  - drivers/tty/n_tty.c:__receive_buf
  - drivers/tty/n_tty.c:__receive_buf
  - drivers/tty/n_tty.c:n_tty_receive_buf_standard
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char
  - drivers/tty/n_tty.c:n_tty_receive_char
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:tty_copy
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
In drivers/tty/n_tty.c (ffffffff81a4e994)
Location: drivers/tty/n_tty.c:145
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:copy_from_read_buf
  - drivers/tty/n_tty.c:__receive_buf
  - drivers/tty/n_tty.c:__receive_buf
  - drivers/tty/n_tty.c:__receive_buf
  - drivers/tty/n_tty.c:n_tty_receive_buf_standard
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char
  - drivers/tty/n_tty.c:n_tty_receive_char
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:tty_copy
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
In drivers/tty/n_tty.c (ffffffff81a98c94)
Location: drivers/tty/n_tty.c:144
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:copy_from_read_buf
  - drivers/tty/n_tty.c:__receive_buf
  - drivers/tty/n_tty.c:__receive_buf
  - drivers/tty/n_tty.c:__receive_buf
  - drivers/tty/n_tty.c:n_tty_receive_buf_standard
  - drivers/tty/n_tty.c:n_tty_receive_char
  - drivers/tty/n_tty.c:n_tty_receive_char
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:tty_copy
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
In drivers/tty/n_tty.c (ffffffff81aeb885)
Location: drivers/tty/n_tty.c:144
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:copy_from_read_buf
  - drivers/tty/n_tty.c:__receive_buf
  - drivers/tty/n_tty.c:__receive_buf
  - drivers/tty/n_tty.c:n_tty_receive_buf_standard
  - drivers/tty/n_tty.c:n_tty_receive_char
  - drivers/tty/n_tty.c:n_tty_receive_char
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_canon
  - drivers/tty/n_tty.c:n_tty_receive_handle_newline
  - drivers/tty/n_tty.c:tty_copy
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
In drivers/tty/n_tty.c (ffff80001085652c)
Location: drivers/tty/n_tty.c:141
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:copy_from_read_buf
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_char_lnext
  - drivers/tty/n_tty.c:n_tty_receive_char_lnext
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
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
In drivers/tty/n_tty.c (c0960c4c)
Location: drivers/tty/n_tty.c:141
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:copy_from_read_buf
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_char_lnext
  - drivers/tty/n_tty.c:n_tty_receive_char_lnext
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
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
In drivers/tty/n_tty.c (c0000000008f8074)
Location: drivers/tty/n_tty.c:141
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:copy_from_read_buf
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_char_lnext
  - drivers/tty/n_tty.c:n_tty_receive_char_lnext
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
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
In drivers/tty/n_tty.c (ffffffe000533a06)
Location: drivers/tty/n_tty.c:141
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:copy_from_read_buf
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
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
In drivers/tty/n_tty.c (ffffffff8164e767)
Location: drivers/tty/n_tty.c:141
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:copy_from_read_buf
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
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
In drivers/tty/n_tty.c (ffffffff8162ebb7)
Location: drivers/tty/n_tty.c:141
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:copy_from_read_buf
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
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
In drivers/tty/n_tty.c (ffffffff8167cb27)
Location: drivers/tty/n_tty.c:141
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:copy_from_read_buf
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
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
In drivers/tty/n_tty.c (ffffffff81697187)
Location: drivers/tty/n_tty.c:141
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:copy_from_read_buf
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_char_special
```
</details>
</li>
</ul>

## Differences
