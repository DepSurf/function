# Function: <code>tty_buffer_free</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void tty_buffer_free(struct tty_port *port, struct tty_buffer *b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff814ea630)
Location: drivers/tty/tty_buffer.c:211
Inline: False
Direct callers:
  - drivers/tty/tty_buffer.c:flush_to_ldisc
  - drivers/tty/tty_buffer.c:tty_buffer_flush
```
**Symbols:**

```
ffffffff814ea630-ffffffff814ea699: tty_buffer_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void tty_buffer_free(struct tty_port *port, struct tty_buffer *b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff8153b600)
Location: drivers/tty/tty_buffer.c:188
Inline: False
Direct callers:
  - drivers/tty/tty_buffer.c:flush_to_ldisc
  - drivers/tty/tty_buffer.c:tty_buffer_flush
```
**Symbols:**

```
ffffffff8153b600-ffffffff8153b669: tty_buffer_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void tty_buffer_free(struct tty_port *port, struct tty_buffer *b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff81567c90)
Location: drivers/tty/tty_buffer.c:188
Inline: False
Direct callers:
  - drivers/tty/tty_buffer.c:flush_to_ldisc
  - drivers/tty/tty_buffer.c:tty_buffer_flush
```
**Symbols:**

```
ffffffff81567c90-ffffffff81567cf6: tty_buffer_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void tty_buffer_free(struct tty_port *port, struct tty_buffer *b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff8157b240)
Location: drivers/tty/tty_buffer.c:188
Inline: False
Direct callers:
  - drivers/tty/tty_buffer.c:flush_to_ldisc
  - drivers/tty/tty_buffer.c:tty_buffer_flush
```
**Symbols:**

```
ffffffff8157b240-ffffffff8157b289: tty_buffer_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void tty_buffer_free(struct tty_port *port, struct tty_buffer *b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff815dfc50)
Location: drivers/tty/tty_buffer.c:189
Inline: False
Direct callers:
  - drivers/tty/tty_buffer.c:flush_to_ldisc
  - drivers/tty/tty_buffer.c:tty_buffer_flush
```
**Symbols:**

```
ffffffff815dfc50-ffffffff815dfc99: tty_buffer_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void tty_buffer_free(struct tty_port *port, struct tty_buffer *b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff81618ed0)
Location: drivers/tty/tty_buffer.c:189
Inline: False
Direct callers:
  - drivers/tty/tty_buffer.c:flush_to_ldisc
  - drivers/tty/tty_buffer.c:tty_buffer_flush
```
**Symbols:**

```
ffffffff81618ed0-ffffffff81618f1b: tty_buffer_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void tty_buffer_free(struct tty_port *port, struct tty_buffer *b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff816360e0)
Location: drivers/tty/tty_buffer.c:194
Inline: False
Direct callers:
  - drivers/tty/tty_buffer.c:flush_to_ldisc
  - drivers/tty/tty_buffer.c:tty_buffer_flush
```
**Symbols:**

```
ffffffff816360e0-ffffffff8163612b: tty_buffer_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void tty_buffer_free(struct tty_port *port, struct tty_buffer *b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_buffer.c (0)
Location: drivers/tty/tty_buffer.c:194
Inline: False
Direct callers:
  - drivers/tty/tty_buffer.c:flush_to_ldisc
  - drivers/tty/tty_buffer.c:tty_buffer_flush
```
**Symbols:**

```
ffffffff8166a310-ffffffff8166a35c: tty_buffer_free (STB_LOCAL)
ffffffff8166aae4-ffffffff8166ab07: tty_buffer_free.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void tty_buffer_free(struct tty_port *port, struct tty_buffer *b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff8168ca00)
Location: drivers/tty/tty_buffer.c:194
Inline: False
Direct callers:
  - drivers/tty/tty_buffer.c:flush_to_ldisc
  - drivers/tty/tty_buffer.c:tty_buffer_flush
```
**Symbols:**

```
ffffffff8168ca00-ffffffff8168ca45: tty_buffer_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void tty_buffer_free(struct tty_port *port, struct tty_buffer *b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff8173ea30)
Location: drivers/tty/tty_buffer.c:194
Inline: False
Direct callers:
  - drivers/tty/tty_buffer.c:flush_to_ldisc
  - drivers/tty/tty_buffer.c:tty_buffer_flush
```
**Symbols:**

```
ffffffff8173ea30-ffffffff8173ea75: tty_buffer_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void tty_buffer_free(struct tty_port *port, struct tty_buffer *b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff8175a980)
Location: drivers/tty/tty_buffer.c:194
Inline: False
Direct callers:
  - drivers/tty/tty_buffer.c:flush_to_ldisc
  - drivers/tty/tty_buffer.c:tty_buffer_flush
```
**Symbols:**

```
ffffffff8175a980-ffffffff8175a9c5: tty_buffer_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void tty_buffer_free(struct tty_port *port, struct tty_buffer *b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff8173e820)
Location: drivers/tty/tty_buffer.c:194
Inline: False
Direct callers:
  - drivers/tty/tty_buffer.c:flush_to_ldisc
  - drivers/tty/tty_buffer.c:tty_buffer_flush
```
**Symbols:**

```
ffffffff8173e820-ffffffff8173e868: tty_buffer_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void tty_buffer_free(struct tty_port *port, struct tty_buffer *b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff817befa0)
Location: drivers/tty/tty_buffer.c:196
Inline: False
Direct callers:
  - drivers/tty/tty_buffer.c:flush_to_ldisc
  - drivers/tty/tty_buffer.c:tty_buffer_flush
```
**Symbols:**

```
ffffffff817befa0-ffffffff817befe8: tty_buffer_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void tty_buffer_free(struct tty_port *port, struct tty_buffer *b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff818fb480)
Location: drivers/tty/tty_buffer.c:197
Inline: False
Direct callers:
  - drivers/tty/tty_buffer.c:flush_to_ldisc
  - drivers/tty/tty_buffer.c:tty_buffer_flush
```
**Symbols:**

```
ffffffff818fb480-ffffffff818fb4f2: tty_buffer_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void tty_buffer_free(struct tty_port *port, struct tty_buffer *b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff81a546e0)
Location: drivers/tty/tty_buffer.c:199
Inline: False
Direct callers:
  - drivers/tty/tty_buffer.c:flush_to_ldisc
  - drivers/tty/tty_buffer.c:tty_buffer_flush
```
**Symbols:**

```
ffffffff81a546e0-ffffffff81a54752: tty_buffer_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void tty_buffer_free(struct tty_port *port, struct tty_buffer *b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff81a9ecc0)
Location: drivers/tty/tty_buffer.c:199
Inline: False
Direct callers:
  - drivers/tty/tty_buffer.c:flush_to_ldisc
  - drivers/tty/tty_buffer.c:tty_buffer_flush
```
**Symbols:**

```
ffffffff81a9ecc0-ffffffff81a9ed32: tty_buffer_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void tty_buffer_free(struct tty_port *port, struct tty_buffer *b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff81af17e0)
Location: drivers/tty/tty_buffer.c:197
Inline: False
Direct callers:
  - drivers/tty/tty_buffer.c:flush_to_ldisc
  - drivers/tty/tty_buffer.c:tty_buffer_flush
```
**Symbols:**

```
ffffffff81af17e0-ffffffff81af1852: tty_buffer_free (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void tty_buffer_free(struct tty_port *port, struct tty_buffer *b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffff80001085d620)
Location: drivers/tty/tty_buffer.c:194
Inline: False
Direct callers:
  - drivers/tty/tty_buffer.c:flush_to_ldisc
  - drivers/tty/tty_buffer.c:tty_buffer_flush
```
**Symbols:**

```
ffff80001085d620-ffff80001085d6cc: tty_buffer_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void tty_buffer_free(struct tty_port *port, struct tty_buffer *b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (c0964f1c)
Location: drivers/tty/tty_buffer.c:194
Inline: False
Direct callers:
  - drivers/tty/tty_buffer.c:flush_to_ldisc
  - drivers/tty/tty_buffer.c:tty_buffer_flush
```
**Symbols:**

```
c0964f1c-c0964fb8: tty_buffer_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void tty_buffer_free(struct tty_port *port, struct tty_buffer *b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (c0000000008fc250)
Location: drivers/tty/tty_buffer.c:194
Inline: False
Direct callers:
  - drivers/tty/tty_buffer.c:flush_to_ldisc
  - drivers/tty/tty_buffer.c:tty_buffer_flush
```
**Symbols:**

```
c0000000008fc250-c0000000008fc300: tty_buffer_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void tty_buffer_free(struct tty_port *port, struct tty_buffer *b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffe000536034)
Location: drivers/tty/tty_buffer.c:194
Inline: False
Direct callers:
  - drivers/tty/tty_buffer.c:flush_to_ldisc
  - drivers/tty/tty_buffer.c:tty_buffer_flush
```
**Symbols:**

```
ffffffe000536034-ffffffe0005360b6: tty_buffer_free (STB_LOCAL)
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
void tty_buffer_free(struct tty_port *port, struct tty_buffer *b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff81652480)
Location: drivers/tty/tty_buffer.c:194
Inline: False
Direct callers:
  - drivers/tty/tty_buffer.c:flush_to_ldisc
  - drivers/tty/tty_buffer.c:tty_buffer_flush
```
**Symbols:**

```
ffffffff81652480-ffffffff816524c5: tty_buffer_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void tty_buffer_free(struct tty_port *port, struct tty_buffer *b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff816328c0)
Location: drivers/tty/tty_buffer.c:194
Inline: False
Direct callers:
  - drivers/tty/tty_buffer.c:flush_to_ldisc
  - drivers/tty/tty_buffer.c:tty_buffer_flush
```
**Symbols:**

```
ffffffff816328c0-ffffffff81632905: tty_buffer_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void tty_buffer_free(struct tty_port *port, struct tty_buffer *b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff81680840)
Location: drivers/tty/tty_buffer.c:194
Inline: False
Direct callers:
  - drivers/tty/tty_buffer.c:flush_to_ldisc
  - drivers/tty/tty_buffer.c:tty_buffer_flush
```
**Symbols:**

```
ffffffff81680840-ffffffff81680885: tty_buffer_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void tty_buffer_free(struct tty_port *port, struct tty_buffer *b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff8169ae90)
Location: drivers/tty/tty_buffer.c:194
Inline: False
Direct callers:
  - drivers/tty/tty_buffer.c:flush_to_ldisc
  - drivers/tty/tty_buffer.c:tty_buffer_flush
```
**Symbols:**

```
ffffffff8169ae90-ffffffff8169aed5: tty_buffer_free (STB_LOCAL)
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
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
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
