# Function: <code>tty_insert_flip_string_flags</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int tty_insert_flip_string_flags(struct tty_port *port, const unsigned char *chars, const char *flags, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff814ea810)
Location: drivers/tty/tty_buffer.c:366
Inline: False
Direct callers:
  - drivers/tty/vt/keyboard.c:puts_queue
  - drivers/tty/vt/keyboard.c:fn_send_intr
  - drivers/tty/vt/keyboard.c:k_shift
  - drivers/tty/vt/keyboard.c:handle_diacr
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/vt.c:respond_string
  - drivers/tty/hvc/hvc_console.c:hvc_poll
  - drivers/tty/serial/serial_core.c:uart_insert_char
  - drivers/tty/serial/serial_core.c:uart_insert_char
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_receiver
```
**Symbols:**

```
ffffffff814ea810-ffffffff814ea8d9: tty_insert_flip_string_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int tty_insert_flip_string_flags(struct tty_port *port, const unsigned char *chars, const char *flags, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff8153b7d0)
Location: drivers/tty/tty_buffer.c:341
Inline: False
Direct callers:
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:k_shift
  - drivers/tty/vt/keyboard.c:fn_send_intr
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:handle_diacr
  - drivers/tty/vt/keyboard.c:puts_queue
  - drivers/tty/vt/vt.c:respond_string
  - drivers/tty/hvc/hvc_console.c:hvc_poll
  - drivers/tty/serial/serial_core.c:uart_insert_char
  - drivers/tty/serial/serial_core.c:uart_insert_char
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_receiver
```
**Symbols:**

```
ffffffff8153b7d0-ffffffff8153b899: tty_insert_flip_string_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int tty_insert_flip_string_flags(struct tty_port *port, const unsigned char *chars, const char *flags, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff81567e50)
Location: drivers/tty/tty_buffer.c:341
Inline: False
Direct callers:
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:k_shift
  - drivers/tty/vt/keyboard.c:fn_send_intr
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:fn_enter
  - drivers/tty/vt/keyboard.c:handle_diacr
  - drivers/tty/vt/keyboard.c:puts_queue
  - drivers/tty/vt/vt.c:respond_string
  - drivers/tty/hvc/hvc_console.c:hvc_poll
  - drivers/tty/serial/serial_core.c:uart_insert_char
  - drivers/tty/serial/serial_core.c:uart_insert_char
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_receiver
```
**Symbols:**

```
ffffffff81567e50-ffffffff81567f19: tty_insert_flip_string_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int tty_insert_flip_string_flags(struct tty_port *port, const unsigned char *chars, const char *flags, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff8157b470)
Location: drivers/tty/tty_buffer.c:341
Inline: False
```
**Symbols:**

```
ffffffff8157b470-ffffffff8157b539: tty_insert_flip_string_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int tty_insert_flip_string_flags(struct tty_port *port, const unsigned char *chars, const char *flags, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff815dfe80)
Location: drivers/tty/tty_buffer.c:342
Inline: False
```
**Symbols:**

```
ffffffff815dfe80-ffffffff815dff49: tty_insert_flip_string_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int tty_insert_flip_string_flags(struct tty_port *port, const unsigned char *chars, const char *flags, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff816191d0)
Location: drivers/tty/tty_buffer.c:342
Inline: True
```
**Symbols:**

```
ffffffff816191d0-ffffffff8161929b: tty_insert_flip_string_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int tty_insert_flip_string_flags(struct tty_port *port, const unsigned char *chars, const char *flags, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff81636410)
Location: drivers/tty/tty_buffer.c:347
Inline: True
```
**Symbols:**

```
ffffffff81636410-ffffffff816364db: tty_insert_flip_string_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int tty_insert_flip_string_flags(struct tty_port *port, const unsigned char *chars, const char *flags, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff8166a4b0)
Location: drivers/tty/tty_buffer.c:347
Inline: False
```
**Symbols:**

```
ffffffff8166a4b0-ffffffff8166a57c: tty_insert_flip_string_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int tty_insert_flip_string_flags(struct tty_port *port, const unsigned char *chars, const char *flags, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff8168cba0)
Location: drivers/tty/tty_buffer.c:347
Inline: False
```
**Symbols:**

```
ffffffff8168cba0-ffffffff8168cc6c: tty_insert_flip_string_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int tty_insert_flip_string_flags(struct tty_port *port, const unsigned char *chars, const char *flags, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff8173ebc0)
Location: drivers/tty/tty_buffer.c:347
Inline: False
```
**Symbols:**

```
ffffffff8173ebc0-ffffffff8173ec8c: tty_insert_flip_string_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int tty_insert_flip_string_flags(struct tty_port *port, const unsigned char *chars, const char *flags, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff8175aaf0)
Location: drivers/tty/tty_buffer.c:347
Inline: False
```
**Symbols:**

```
ffffffff8175aaf0-ffffffff8175abbc: tty_insert_flip_string_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int tty_insert_flip_string_flags(struct tty_port *port, const unsigned char *chars, const char *flags, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff8173e990)
Location: drivers/tty/tty_buffer.c:347
Inline: False
```
**Symbols:**

```
ffffffff8173e990-ffffffff8173ea5a: tty_insert_flip_string_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int tty_insert_flip_string_flags(struct tty_port *port, const unsigned char *chars, const char *flags, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff817bf110)
Location: drivers/tty/tty_buffer.c:352
Inline: False
```
**Symbols:**

```
ffffffff817bf110-ffffffff817bf1da: tty_insert_flip_string_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int tty_insert_flip_string_flags(struct tty_port *port, const unsigned char *chars, const char *flags, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff818fb6d0)
Location: drivers/tty/tty_buffer.c:353
Inline: False
```
**Symbols:**

```
ffffffff818fb6d0-ffffffff818fb7a4: tty_insert_flip_string_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int tty_insert_flip_string_flags(struct tty_port *port, const unsigned char *chars, const char *flags, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff81a54900)
Location: drivers/tty/tty_buffer.c:358
Inline: False
```
**Symbols:**

```
ffffffff81a54900-ffffffff81a549d7: tty_insert_flip_string_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int tty_insert_flip_string_flags(struct tty_port *port, const unsigned char *chars, const char *flags, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff81a9eee0)
Location: drivers/tty/tty_buffer.c:358
Inline: False
```
**Symbols:**

```
ffffffff81a9eee0-ffffffff81a9efb7: tty_insert_flip_string_flags (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int tty_insert_flip_string_flags(struct tty_port *port, const unsigned char *chars, const char *flags, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffff80001085d328)
Location: drivers/tty/tty_buffer.c:347
Inline: False
```
**Symbols:**

```
ffff80001085d328-ffff80001085d400: tty_insert_flip_string_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int tty_insert_flip_string_flags(struct tty_port *port, const unsigned char *chars, const char *flags, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (c09650f0)
Location: drivers/tty/tty_buffer.c:347
Inline: False
```
**Symbols:**

```
c09650f0-c09651a4: tty_insert_flip_string_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int tty_insert_flip_string_flags(struct tty_port *port, const unsigned char *chars, const char *flags, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (c0000000008fc520)
Location: drivers/tty/tty_buffer.c:347
Inline: False
```
**Symbols:**

```
c0000000008fc520-c0000000008fc62c: tty_insert_flip_string_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int tty_insert_flip_string_flags(struct tty_port *port, const unsigned char *chars, const char *flags, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffe000536250)
Location: drivers/tty/tty_buffer.c:347
Inline: False
```
**Symbols:**

```
ffffffe000536250-ffffffe000536302: tty_insert_flip_string_flags (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int tty_insert_flip_string_flags(struct tty_port *port, const unsigned char *chars, const char *flags, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff81652620)
Location: drivers/tty/tty_buffer.c:347
Inline: False
```
**Symbols:**

```
ffffffff81652620-ffffffff816526ec: tty_insert_flip_string_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int tty_insert_flip_string_flags(struct tty_port *port, const unsigned char *chars, const char *flags, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff81632a60)
Location: drivers/tty/tty_buffer.c:347
Inline: False
```
**Symbols:**

```
ffffffff81632a60-ffffffff81632b2c: tty_insert_flip_string_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int tty_insert_flip_string_flags(struct tty_port *port, const unsigned char *chars, const char *flags, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff816809e0)
Location: drivers/tty/tty_buffer.c:347
Inline: False
```
**Symbols:**

```
ffffffff816809e0-ffffffff81680aac: tty_insert_flip_string_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int tty_insert_flip_string_flags(struct tty_port *port, const unsigned char *chars, const char *flags, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff8169b030)
Location: drivers/tty/tty_buffer.c:347
Inline: False
```
**Symbols:**

```
ffffffff8169b030-ffffffff8169b0fc: tty_insert_flip_string_flags (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
