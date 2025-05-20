# Function: <code>process_output_block</code>

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
In drivers/tty/n_tty.c (ffffffff814e5792)
Location: drivers/tty/n_tty.c:554
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_write
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
In drivers/tty/n_tty.c (ffffffff815369e3)
Location: drivers/tty/n_tty.c:528
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_write
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
In drivers/tty/n_tty.c (ffffffff815630fe)
Location: drivers/tty/n_tty.c:528
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_write
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
In drivers/tty/n_tty.c (ffffffff8157623e)
Location: drivers/tty/n_tty.c:528
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_write
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
In drivers/tty/n_tty.c (ffffffff815daba9)
Location: drivers/tty/n_tty.c:526
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_write
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
In drivers/tty/n_tty.c (ffffffff81613cc9)
Location: drivers/tty/n_tty.c:527
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_write
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
In drivers/tty/n_tty.c (ffffffff81630d99)
Location: drivers/tty/n_tty.c:540
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_write
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
In drivers/tty/n_tty.c (ffffffff81664dee)
Location: drivers/tty/n_tty.c:542
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_write
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
In drivers/tty/n_tty.c (ffffffff8168743e)
Location: drivers/tty/n_tty.c:542
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_write
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t process_output_block(struct tty_struct *tty, const unsigned char *buf, unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/n_tty.c (ffffffff81738870)
Location: drivers/tty/n_tty.c:542
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:n_tty_write
```
**Symbols:**

```
ffffffff81738870-ffffffff81738a05: process_output_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t process_output_block(struct tty_struct *tty, const unsigned char *buf, unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/n_tty.c (ffffffff81754870)
Location: drivers/tty/n_tty.c:538
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:n_tty_write
```
**Symbols:**

```
ffffffff81754870-ffffffff81754a05: process_output_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t process_output_block(struct tty_struct *tty, const unsigned char *buf, unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/n_tty.c (ffffffff817387c0)
Location: drivers/tty/n_tty.c:539
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:n_tty_write
```
**Symbols:**

```
ffffffff817387c0-ffffffff81738955: process_output_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
ssize_t process_output_block(struct tty_struct *tty, const unsigned char *buf, unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/n_tty.c (ffffffff817b9250)
Location: drivers/tty/n_tty.c:539
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:n_tty_write
```
**Symbols:**

```
ffffffff817b9250-ffffffff817b93e5: process_output_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ssize_t process_output_block(struct tty_struct *tty, const unsigned char *buf, unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/n_tty.c (ffffffff818f5290)
Location: drivers/tty/n_tty.c:528
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:n_tty_write
```
**Symbols:**

```
ffffffff818f5290-ffffffff818f5456: process_output_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t process_output_block(struct tty_struct *tty, const unsigned char *buf, unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/n_tty.c (ffffffff81a4db80)
Location: drivers/tty/n_tty.c:533
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:n_tty_write
```
**Symbols:**

```
ffffffff81a4db80-ffffffff81a4dd46: process_output_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t process_output_block(struct tty_struct *tty, const unsigned char *buf, unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/n_tty.c (ffffffff81a97e50)
Location: drivers/tty/n_tty.c:532
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:n_tty_write
```
**Symbols:**

```
ffffffff81a97e50-ffffffff81a98044: process_output_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t process_output_block(struct tty_struct *tty, const u8 *buf, unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/n_tty.c (ffffffff81aea890)
Location: drivers/tty/n_tty.c:521
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:n_tty_write
```
**Symbols:**

```
ffffffff81aea890-ffffffff81aeaa50: process_output_block (STB_LOCAL)
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
In drivers/tty/n_tty.c (ffff8000108570bc)
Location: drivers/tty/n_tty.c:542
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_write
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
In drivers/tty/n_tty.c (c095f424)
Location: drivers/tty/n_tty.c:542
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_write
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
In drivers/tty/n_tty.c (c0000000008f43e0)
Location: drivers/tty/n_tty.c:542
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_write
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
In drivers/tty/n_tty.c (ffffffe00053185e)
Location: drivers/tty/n_tty.c:542
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_write
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
In drivers/tty/n_tty.c (ffffffff8164cebe)
Location: drivers/tty/n_tty.c:542
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_write
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
In drivers/tty/n_tty.c (ffffffff8162d30e)
Location: drivers/tty/n_tty.c:542
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_write
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
In drivers/tty/n_tty.c (ffffffff8167b27e)
Location: drivers/tty/n_tty.c:542
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_write
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
In drivers/tty/n_tty.c (ffffffff816958de)
Location: drivers/tty/n_tty.c:542
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_write
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
<code>const unsigned char *buf</code> ➡️ <code>const u8 *buf</code>
</li>
</ul>
</details>
</li>
</ul>
