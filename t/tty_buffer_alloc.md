# Function: <code>tty_buffer_alloc</code>

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
In drivers/tty/tty_buffer.c (ffffffff814ea6dc)
Location: drivers/tty/tty_buffer.c:172
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:__tty_buffer_request_room
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
In drivers/tty/tty_buffer.c (ffffffff8153b6af)
Location: drivers/tty/tty_buffer.c:149
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:__tty_buffer_request_room
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
In drivers/tty/tty_buffer.c (ffffffff81567d3f)
Location: drivers/tty/tty_buffer.c:149
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:__tty_buffer_request_room
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
In drivers/tty/tty_buffer.c (ffffffff8157b36f)
Location: drivers/tty/tty_buffer.c:149
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:__tty_buffer_request_room
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
In drivers/tty/tty_buffer.c (ffffffff815dfd7f)
Location: drivers/tty/tty_buffer.c:150
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:__tty_buffer_request_room
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
In drivers/tty/tty_buffer.c (ffffffff8161900d)
Location: drivers/tty/tty_buffer.c:150
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:__tty_buffer_request_room
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
In drivers/tty/tty_buffer.c (ffffffff8163617d)
Location: drivers/tty/tty_buffer.c:155
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:__tty_buffer_request_room
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
In drivers/tty/tty_buffer.c (ffffffff8166a3a8)
Location: drivers/tty/tty_buffer.c:155
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:__tty_buffer_request_room
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
In drivers/tty/tty_buffer.c (ffffffff8168ca98)
Location: drivers/tty/tty_buffer.c:155
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:__tty_buffer_request_room
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct tty_buffer *tty_buffer_alloc(struct tty_port *port, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff8173eaa0)
Location: drivers/tty/tty_buffer.c:155
Inline: False
```
**Symbols:**

```
ffffffff8173eaa0-ffffffff8173eb23: tty_buffer_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct tty_buffer *tty_buffer_alloc(struct tty_port *port, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff8175a9d0)
Location: drivers/tty/tty_buffer.c:155
Inline: False
```
**Symbols:**

```
ffffffff8175a9d0-ffffffff8175aa53: tty_buffer_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct tty_buffer *tty_buffer_alloc(struct tty_port *port, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff8173e870)
Location: drivers/tty/tty_buffer.c:155
Inline: False
```
**Symbols:**

```
ffffffff8173e870-ffffffff8173e8f3: tty_buffer_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct tty_buffer *tty_buffer_alloc(struct tty_port *port, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff817beff0)
Location: drivers/tty/tty_buffer.c:156
Inline: False
```
**Symbols:**

```
ffffffff817beff0-ffffffff817bf073: tty_buffer_alloc (STB_LOCAL)
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
In drivers/tty/tty_buffer.c (ffffffff818fb544)
Location: drivers/tty/tty_buffer.c:157
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:__tty_buffer_request_room
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
In drivers/tty/tty_buffer.c (ffffffff81a547de)
Location: drivers/tty/tty_buffer.c:159
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:__tty_buffer_request_room
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
In drivers/tty/tty_buffer.c (ffffffff81a9edbe)
Location: drivers/tty/tty_buffer.c:159
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:__tty_buffer_request_room
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct tty_buffer *tty_buffer_alloc(struct tty_port *port, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff81af1870)
Location: drivers/tty/tty_buffer.c:158
Inline: False
Direct callers:
  - drivers/tty/tty_buffer.c:__tty_buffer_request_room
  - drivers/tty/tty_buffer.c:__tty_buffer_request_room
```
**Symbols:**

```
ffffffff81af1870-ffffffff81af1924: tty_buffer_alloc (STB_LOCAL)
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
In drivers/tty/tty_buffer.c (ffff80001085d204)
Location: drivers/tty/tty_buffer.c:155
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:__tty_buffer_request_room
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
In drivers/tty/tty_buffer.c (c0964ffc)
Location: drivers/tty/tty_buffer.c:155
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:__tty_buffer_request_room
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
In drivers/tty/tty_buffer.c (c0000000008fc368)
Location: drivers/tty/tty_buffer.c:155
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:__tty_buffer_request_room
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
In drivers/tty/tty_buffer.c (ffffffe000536166)
Location: drivers/tty/tty_buffer.c:155
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:__tty_buffer_request_room
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
In drivers/tty/tty_buffer.c (ffffffff81652518)
Location: drivers/tty/tty_buffer.c:155
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:__tty_buffer_request_room
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
In drivers/tty/tty_buffer.c (ffffffff81632958)
Location: drivers/tty/tty_buffer.c:155
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:__tty_buffer_request_room
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
In drivers/tty/tty_buffer.c (ffffffff816808d8)
Location: drivers/tty/tty_buffer.c:155
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:__tty_buffer_request_room
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
In drivers/tty/tty_buffer.c (ffffffff8169af28)
Location: drivers/tty/tty_buffer.c:155
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:__tty_buffer_request_room
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
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
</ul>
