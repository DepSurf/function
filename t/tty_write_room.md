# Function: <code>tty_write_room</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int tty_write_room(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (ffffffff814e8120)
Location: drivers/tty/tty_ioctl.c:75
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:__process_echoes
  - drivers/tty/n_tty.c:n_tty_poll
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_write
```
**Symbols:**

```
ffffffff814e8120-ffffffff814e8140: tty_write_room (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int tty_write_room(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (ffffffff81539280)
Location: drivers/tty/tty_ioctl.c:75
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:n_tty_poll
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:__process_echoes
```
**Symbols:**

```
ffffffff81539280-ffffffff815392a0: tty_write_room (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int tty_write_room(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (ffffffff81565990)
Location: drivers/tty/tty_ioctl.c:75
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:n_tty_poll
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:__process_echoes
```
**Symbols:**

```
ffffffff81565990-ffffffff815659b0: tty_write_room (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int tty_write_room(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (ffffffff81579190)
Location: drivers/tty/tty_ioctl.c:75
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:n_tty_poll
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:__process_echoes
```
**Symbols:**

```
ffffffff81579190-ffffffff815791b0: tty_write_room (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int tty_write_room(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (ffffffff815ddb20)
Location: drivers/tty/tty_ioctl.c:76
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:n_tty_poll
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:__process_echoes
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_room
```
**Symbols:**

```
ffffffff815ddb20-ffffffff815ddb43: tty_write_room (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int tty_write_room(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (ffffffff81616de0)
Location: drivers/tty/tty_ioctl.c:76
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:n_tty_poll
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:__process_echoes
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_room
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_room
```
**Symbols:**

```
ffffffff81616de0-ffffffff81616e03: tty_write_room (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int tty_write_room(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (ffffffff81633fe0)
Location: drivers/tty/tty_ioctl.c:76
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:n_tty_poll
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:__process_echoes
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_room
```
**Symbols:**

```
ffffffff81633fe0-ffffffff81634003: tty_write_room (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int tty_write_room(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (ffffffff81668090)
Location: drivers/tty/tty_ioctl.c:76
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:n_tty_poll
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:__process_echoes
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_room
```
**Symbols:**

```
ffffffff81668090-ffffffff816680b3: tty_write_room (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int tty_write_room(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (ffffffff8168a7e0)
Location: drivers/tty/tty_ioctl.c:76
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:n_tty_poll
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:__process_echoes
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_room
```
**Symbols:**

```
ffffffff8168a7e0-ffffffff8168a803: tty_write_room (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int tty_write_room(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (ffffffff8173c6d0)
Location: drivers/tty/tty_ioctl.c:76
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:n_tty_poll
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:__process_echoes
  - drivers/tty/n_tty.c:process_output_block
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_room
```
**Symbols:**

```
ffffffff8173c6d0-ffffffff8173c6f3: tty_write_room (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int tty_write_room(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (ffffffff81758840)
Location: drivers/tty/tty_ioctl.c:76
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:n_tty_poll
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:__process_echoes
  - drivers/tty/n_tty.c:process_output_block
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_room
```
**Symbols:**

```
ffffffff81758840-ffffffff81758863: tty_write_room (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int tty_write_room(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (ffffffff8173c7a0)
Location: drivers/tty/tty_ioctl.c:76
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:n_tty_poll
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:__process_echoes
  - drivers/tty/n_tty.c:process_output_block
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_room
```
**Symbols:**

```
ffffffff8173c7a0-ffffffff8173c7c3: tty_write_room (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
unsigned int tty_write_room(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (ffffffff817bcd70)
Location: drivers/tty/tty_ioctl.c:76
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:n_tty_poll
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:__process_echoes
  - drivers/tty/n_tty.c:process_output_block
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_room
```
**Symbols:**

```
ffffffff817bcd70-ffffffff817bcd93: tty_write_room (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
unsigned int tty_write_room(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (ffffffff818f8fa0)
Location: drivers/tty/tty_ioctl.c:76
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:n_tty_poll
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:__process_echoes
  - drivers/tty/n_tty.c:process_output_block
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_room
```
**Symbols:**

```
ffffffff818f8fa0-ffffffff818f8fd3: tty_write_room (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
unsigned int tty_write_room(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (ffffffff81a51dd0)
Location: drivers/tty/tty_ioctl.c:77
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:n_tty_poll
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:__process_echoes
  - drivers/tty/n_tty.c:process_output_block
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_room
```
**Symbols:**

```
ffffffff81a51dd0-ffffffff81a51e03: tty_write_room (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
unsigned int tty_write_room(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (ffffffff81a9c0e0)
Location: drivers/tty/tty_ioctl.c:78
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:n_tty_poll
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:__process_echoes
  - drivers/tty/n_tty.c:process_output_block
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_room
```
**Symbols:**

```
ffffffff81a9c0e0-ffffffff81a9c113: tty_write_room (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
unsigned int tty_write_room(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (ffffffff81aeebb0)
Location: drivers/tty/tty_ioctl.c:66
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:n_tty_poll
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:__process_echoes
  - drivers/tty/n_tty.c:process_output_block
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_room
```
**Symbols:**

```
ffffffff81aeebb0-ffffffff81aeebe3: tty_write_room (STB_GLOBAL)
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
int tty_write_room(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (ffff800010858d98)
Location: drivers/tty/tty_ioctl.c:76
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:n_tty_poll
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:__process_echoes
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_room
```
**Symbols:**

```
ffff800010858d98-ffff800010858dd4: tty_write_room (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int tty_write_room(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (c0962774)
Location: drivers/tty/tty_ioctl.c:76
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:n_tty_poll
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:__process_echoes
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_room
```
**Symbols:**

```
c0962774-c09627a8: tty_write_room (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int tty_write_room(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (c0000000008f8840)
Location: drivers/tty/tty_ioctl.c:76
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:n_tty_poll
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:__process_echoes
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_room
```
**Symbols:**

```
c0000000008f8840-c0000000008f8898: tty_write_room (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int tty_write_room(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (ffffffe000533f8a)
Location: drivers/tty/tty_ioctl.c:76
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:n_tty_poll
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:__process_echoes
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_room
```
**Symbols:**

```
ffffffe000533f8a-ffffffe000533fc4: tty_write_room (STB_GLOBAL)
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
int tty_write_room(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (ffffffff81650260)
Location: drivers/tty/tty_ioctl.c:76
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:n_tty_poll
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:__process_echoes
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_room
```
**Symbols:**

```
ffffffff81650260-ffffffff81650283: tty_write_room (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int tty_write_room(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (ffffffff816306b0)
Location: drivers/tty/tty_ioctl.c:76
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:n_tty_poll
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:__process_echoes
```
**Symbols:**

```
ffffffff816306b0-ffffffff816306d3: tty_write_room (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int tty_write_room(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (ffffffff8167e620)
Location: drivers/tty/tty_ioctl.c:76
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:n_tty_poll
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:__process_echoes
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_room
```
**Symbols:**

```
ffffffff8167e620-ffffffff8167e643: tty_write_room (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int tty_write_room(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (ffffffff81698c80)
Location: drivers/tty/tty_ioctl.c:76
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:n_tty_poll
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:__process_echoes
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_room
```
**Symbols:**

```
ffffffff81698c80-ffffffff81698ca3: tty_write_room (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>unsigned int</code>
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
