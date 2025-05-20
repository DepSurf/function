# Function: <code>tty_insert_flip_string_and_push_buffer</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int tty_insert_flip_string_and_push_buffer(struct tty_port *port, const unsigned char *chars, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff818fbc20)
Location: drivers/tty/tty_buffer.c:577
Inline: False
Direct callers:
  - drivers/tty/pty.c:pty_write
```
**Symbols:**

```
ffffffff818fbc20-ffffffff818fbcab: tty_insert_flip_string_and_push_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int tty_insert_flip_string_and_push_buffer(struct tty_port *port, const unsigned char *chars, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff81a55040)
Location: drivers/tty/tty_buffer.c:622
Inline: False
Direct callers:
  - drivers/tty/pty.c:pty_write
```
**Symbols:**

```
ffffffff81a55040-ffffffff81a550cb: tty_insert_flip_string_and_push_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int tty_insert_flip_string_and_push_buffer(struct tty_port *port, const unsigned char *chars, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff81a9f620)
Location: drivers/tty/tty_buffer.c:622
Inline: False
Direct callers:
  - drivers/tty/pty.c:pty_write
```
**Symbols:**

```
ffffffff81a9f620-ffffffff81a9f6ab: tty_insert_flip_string_and_push_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int tty_insert_flip_string_and_push_buffer(struct tty_port *port, const u8 *chars, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff81af2020)
Location: drivers/tty/tty_buffer.c:551
Inline: False
Direct callers:
  - drivers/tty/pty.c:pty_write
```
**Symbols:**

```
ffffffff81af2020-ffffffff81af20e2: tty_insert_flip_string_and_push_buffer (STB_GLOBAL)
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
<code>const unsigned char *chars</code> ➡️ <code>const u8 *chars</code>
</li>
</ul>
</details>
</li>
</ul>
