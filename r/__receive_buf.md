# Function: <code>__receive_buf</code>

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
In drivers/tty/n_tty.c (ffffffff814e743c)
Location: drivers/tty/n_tty.c:1621
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
In drivers/tty/n_tty.c (ffffffff815384ec)
Location: drivers/tty/n_tty.c:1590
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
In drivers/tty/n_tty.c (ffffffff81564bfc)
Location: drivers/tty/n_tty.c:1590
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
In drivers/tty/n_tty.c (ffffffff81577d2d)
Location: drivers/tty/n_tty.c:1590
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
In drivers/tty/n_tty.c (ffffffff815dc6b0)
Location: drivers/tty/n_tty.c:1588
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
In drivers/tty/n_tty.c (ffffffff81615978)
Location: drivers/tty/n_tty.c:1606
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
In drivers/tty/n_tty.c (ffffffff81632957)
Location: drivers/tty/n_tty.c:1619
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
In drivers/tty/n_tty.c (ffffffff81667428)
Location: drivers/tty/n_tty.c:1621
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
In drivers/tty/n_tty.c (ffffffff81689b78)
Location: drivers/tty/n_tty.c:1621
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
void __receive_buf(struct tty_struct *tty, const unsigned char *cp, char *fp, int count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/n_tty.c (ffffffff8173bd30)
Location: drivers/tty/n_tty.c:1621
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
```
**Symbols:**

```
ffffffff8173bd30-ffffffff8173bf8f: __receive_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __receive_buf(struct tty_struct *tty, const unsigned char *cp, char *fp, int count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/n_tty.c (ffffffff81757ea0)
Location: drivers/tty/n_tty.c:1617
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
```
**Symbols:**

```
ffffffff81757ea0-ffffffff817580ff: __receive_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __receive_buf(struct tty_struct *tty, const unsigned char *cp, char *fp, int count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/n_tty.c (ffffffff8173bf80)
Location: drivers/tty/n_tty.c:1618
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
```
**Symbols:**

```
ffffffff8173bf80-ffffffff8173c426: __receive_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void __receive_buf(struct tty_struct *tty, const unsigned char *cp, const char *fp, int count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/n_tty.c (0)
Location: drivers/tty/n_tty.c:1564
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
```
**Symbols:**

```
ffffffff817bc5a0-ffffffff817bc9fc: __receive_buf (STB_LOCAL)
ffffffff81cf8bfc-ffffffff81cf8c60: __receive_buf.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void __receive_buf(struct tty_struct *tty, const unsigned char *cp, const char *fp, int count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/n_tty.c (0)
Location: drivers/tty/n_tty.c:1549
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
```
**Symbols:**

```
ffffffff818f87e0-ffffffff818f8c49: __receive_buf (STB_LOCAL)
ffffffff81ec0d1e-ffffffff81ec0d6e: __receive_buf.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __receive_buf(struct tty_struct *tty, const unsigned char *cp, const char *fp, int count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/n_tty.c (ffffffff81a515e0)
Location: drivers/tty/n_tty.c:1593
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
```
**Symbols:**

```
ffffffff81a515e0-ffffffff81a51a2c: __receive_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __receive_buf(struct tty_struct *tty, const unsigned char *cp, const char *fp, int count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/n_tty.c (ffffffff81a9b890)
Location: drivers/tty/n_tty.c:1592
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
```
**Symbols:**

```
ffffffff81a9b890-ffffffff81a9bcdc: __receive_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void __receive_buf(struct tty_struct *tty, const u8 *cp, const u8 *fp, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/n_tty.c (0)
Location: drivers/tty/n_tty.c:1610
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
```
**Symbols:**

```
ffffffff81aee3e0-ffffffff81aee795: __receive_buf (STB_LOCAL)
ffffffff821f3c61-ffffffff821f3c84: __receive_buf.cold (STB_LOCAL)
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
In drivers/tty/n_tty.c (ffff800010858088)
Location: drivers/tty/n_tty.c:1621
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
In drivers/tty/n_tty.c (c0961cdc)
Location: drivers/tty/n_tty.c:1621
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
In drivers/tty/n_tty.c (c0000000008f7018)
Location: drivers/tty/n_tty.c:1621
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
In drivers/tty/n_tty.c (ffffffe000532bb8)
Location: drivers/tty/n_tty.c:1621
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
In drivers/tty/n_tty.c (ffffffff8164f5f8)
Location: drivers/tty/n_tty.c:1621
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
In drivers/tty/n_tty.c (ffffffff8162fa48)
Location: drivers/tty/n_tty.c:1621
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
In drivers/tty/n_tty.c (ffffffff8167d9b8)
Location: drivers/tty/n_tty.c:1621
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
In drivers/tty/n_tty.c (ffffffff81698018)
Location: drivers/tty/n_tty.c:1621
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
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>char *fp</code> ➡️ <code>const char *fp</code>
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
