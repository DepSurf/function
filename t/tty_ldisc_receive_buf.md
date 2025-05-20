# Function: <code>tty_ldisc_receive_buf</code>

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
In drivers/tty/vt/selection.c (ffffffff814f1a54)
Location: include/linux/tty.h:590
Inline: True
Inline callers:
  - drivers/tty/vt/selection.c:paste_selection
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int tty_ldisc_receive_buf(struct tty_ldisc *ld, unsigned char *p, char *f, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff8153b520)
Location: drivers/tty/tty_buffer.c:425
Inline: False
Direct callers:
  - drivers/tty/tty_buffer.c:flush_to_ldisc
  - drivers/tty/vt/selection.c:paste_selection
```
**Symbols:**

```
ffffffff8153b520-ffffffff8153b56d: tty_ldisc_receive_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int tty_ldisc_receive_buf(struct tty_ldisc *ld, unsigned char *p, char *f, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff81567bc0)
Location: drivers/tty/tty_buffer.c:425
Inline: False
Direct callers:
  - drivers/tty/tty_buffer.c:flush_to_ldisc
  - drivers/tty/vt/selection.c:paste_selection
```
**Symbols:**

```
ffffffff81567bc0-ffffffff81567c0d: tty_ldisc_receive_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int tty_ldisc_receive_buf(struct tty_ldisc *ld, const unsigned char *p, char *f, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff8157b170)
Location: drivers/tty/tty_buffer.c:451
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_default_receive_buf
  - drivers/tty/vt/selection.c:paste_selection
```
**Symbols:**

```
ffffffff8157b170-ffffffff8157b1bd: tty_ldisc_receive_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int tty_ldisc_receive_buf(struct tty_ldisc *ld, const unsigned char *p, char *f, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff815dfb70)
Location: drivers/tty/tty_buffer.c:452
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_default_receive_buf
  - drivers/tty/vt/selection.c:paste_selection
```
**Symbols:**

```
ffffffff815dfb70-ffffffff815dfbc2: tty_ldisc_receive_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int tty_ldisc_receive_buf(struct tty_ldisc *ld, const unsigned char *p, char *f, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff81618df0)
Location: drivers/tty/tty_buffer.c:452
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_default_receive_buf
  - drivers/tty/vt/selection.c:paste_selection
```
**Symbols:**

```
ffffffff81618df0-ffffffff81618e42: tty_ldisc_receive_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int tty_ldisc_receive_buf(struct tty_ldisc *ld, const unsigned char *p, char *f, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff81636000)
Location: drivers/tty/tty_buffer.c:457
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_default_receive_buf
  - drivers/tty/vt/selection.c:paste_selection
```
**Symbols:**

```
ffffffff81636000-ffffffff81636052: tty_ldisc_receive_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int tty_ldisc_receive_buf(struct tty_ldisc *ld, const unsigned char *p, char *f, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff8166a210)
Location: drivers/tty/tty_buffer.c:457
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_default_receive_buf
  - drivers/tty/vt/selection.c:paste_selection
```
**Symbols:**

```
ffffffff8166a210-ffffffff8166a262: tty_ldisc_receive_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int tty_ldisc_receive_buf(struct tty_ldisc *ld, const unsigned char *p, char *f, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff8168c900)
Location: drivers/tty/tty_buffer.c:457
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_default_receive_buf
  - drivers/tty/vt/selection.c:paste_selection
```
**Symbols:**

```
ffffffff8168c900-ffffffff8168c952: tty_ldisc_receive_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int tty_ldisc_receive_buf(struct tty_ldisc *ld, const unsigned char *p, char *f, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff8173e960)
Location: drivers/tty/tty_buffer.c:457
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_default_receive_buf
  - drivers/tty/vt/selection.c:paste_selection
```
**Symbols:**

```
ffffffff8173e960-ffffffff8173e9b2: tty_ldisc_receive_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int tty_ldisc_receive_buf(struct tty_ldisc *ld, const unsigned char *p, char *f, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff8175a8b0)
Location: drivers/tty/tty_buffer.c:457
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_default_receive_buf
  - drivers/tty/vt/selection.c:paste_selection
```
**Symbols:**

```
ffffffff8175a8b0-ffffffff8175a902: tty_ldisc_receive_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int tty_ldisc_receive_buf(struct tty_ldisc *ld, const unsigned char *p, char *f, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff8173e760)
Location: drivers/tty/tty_buffer.c:457
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_default_receive_buf
  - drivers/tty/vt/selection.c:paste_selection
```
**Symbols:**

```
ffffffff8173e760-ffffffff8173e7ab: tty_ldisc_receive_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int tty_ldisc_receive_buf(struct tty_ldisc *ld, const unsigned char *p, const char *f, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff817beee0)
Location: drivers/tty/tty_buffer.c:467
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_default_receive_buf
  - drivers/tty/vt/selection.c:paste_selection
```
**Symbols:**

```
ffffffff817beee0-ffffffff817bef2b: tty_ldisc_receive_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int tty_ldisc_receive_buf(struct tty_ldisc *ld, const unsigned char *p, const char *f, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff818fb380)
Location: drivers/tty/tty_buffer.c:448
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_default_receive_buf
  - drivers/tty/vt/selection.c:paste_selection
```
**Symbols:**

```
ffffffff818fb380-ffffffff818fb3ea: tty_ldisc_receive_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int tty_ldisc_receive_buf(struct tty_ldisc *ld, const unsigned char *p, const char *f, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff81a545a0)
Location: drivers/tty/tty_buffer.c:453
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_default_receive_buf
  - drivers/tty/vt/selection.c:paste_selection
```
**Symbols:**

```
ffffffff81a545a0-ffffffff81a5460a: tty_ldisc_receive_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int tty_ldisc_receive_buf(struct tty_ldisc *ld, const unsigned char *p, const char *f, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff81a9eb80)
Location: drivers/tty/tty_buffer.c:453
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_default_receive_buf
  - drivers/tty/vt/selection.c:paste_selection
```
**Symbols:**

```
ffffffff81a9eb80-ffffffff81a9ebea: tty_ldisc_receive_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
size_t tty_ldisc_receive_buf(struct tty_ldisc *ld, const u8 *p, const u8 *f, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff81af16a0)
Location: drivers/tty/tty_buffer.c:382
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_default_receive_buf
  - drivers/tty/vt/selection.c:paste_selection
```
**Symbols:**

```
ffffffff81af16a0-ffffffff81af1710: tty_ldisc_receive_buf (STB_GLOBAL)
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
int tty_ldisc_receive_buf(struct tty_ldisc *ld, const unsigned char *p, char *f, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffff80001085cf70)
Location: drivers/tty/tty_buffer.c:457
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_default_receive_buf
  - drivers/tty/vt/selection.c:paste_selection
```
**Symbols:**

```
ffff80001085cf70-ffff80001085d008: tty_ldisc_receive_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int tty_ldisc_receive_buf(struct tty_ldisc *ld, const unsigned char *p, char *f, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (c0964dec)
Location: drivers/tty/tty_buffer.c:457
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_default_receive_buf
  - drivers/tty/vt/selection.c:paste_selection
```
**Symbols:**

```
c0964dec-c0964e58: tty_ldisc_receive_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int tty_ldisc_receive_buf(struct tty_ldisc *ld, const unsigned char *p, char *f, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (c0000000008fc030)
Location: drivers/tty/tty_buffer.c:457
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_default_receive_buf
  - drivers/tty/vt/selection.c:paste_selection
```
**Symbols:**

```
c0000000008fc030-c0000000008fc110: tty_ldisc_receive_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int tty_ldisc_receive_buf(struct tty_ldisc *ld, const unsigned char *p, char *f, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffe000535efa)
Location: drivers/tty/tty_buffer.c:457
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_default_receive_buf
  - drivers/tty/vt/selection.c:paste_selection
```
**Symbols:**

```
ffffffe000535efa-ffffffe000535f5e: tty_ldisc_receive_buf (STB_GLOBAL)
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
int tty_ldisc_receive_buf(struct tty_ldisc *ld, const unsigned char *p, char *f, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff81652380)
Location: drivers/tty/tty_buffer.c:457
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_default_receive_buf
  - drivers/tty/vt/selection.c:paste_selection
```
**Symbols:**

```
ffffffff81652380-ffffffff816523d2: tty_ldisc_receive_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int tty_ldisc_receive_buf(struct tty_ldisc *ld, const unsigned char *p, char *f, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff816327c0)
Location: drivers/tty/tty_buffer.c:457
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_default_receive_buf
  - drivers/tty/vt/selection.c:paste_selection
```
**Symbols:**

```
ffffffff816327c0-ffffffff81632812: tty_ldisc_receive_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int tty_ldisc_receive_buf(struct tty_ldisc *ld, const unsigned char *p, char *f, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff81680740)
Location: drivers/tty/tty_buffer.c:457
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_default_receive_buf
  - drivers/tty/vt/selection.c:paste_selection
```
**Symbols:**

```
ffffffff81680740-ffffffff81680792: tty_ldisc_receive_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int tty_ldisc_receive_buf(struct tty_ldisc *ld, const unsigned char *p, char *f, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_buffer.c (ffffffff8169ad90)
Location: drivers/tty/tty_buffer.c:457
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_default_receive_buf
  - drivers/tty/vt/selection.c:paste_selection
```
**Symbols:**

```
ffffffff8169ad90-ffffffff8169ade2: tty_ldisc_receive_buf (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>unsigned char *p</code> ➡️ <code>const unsigned char *p</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>char *f</code> ➡️ <code>const char *f</code>
</li>
</ul>
</details>
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
<code>const unsigned char *p</code> ➡️ <code>const u8 *p</code>
</li>
<li>
<b>Param type changed. </b>
<code>const char *f</code> ➡️ <code>const u8 *f</code>
</li>
<li>
<b>Param type changed. </b>
<code>int count</code> ➡️ <code>size_t count</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>size_t</code>
</li>
</ul>
</details>
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
