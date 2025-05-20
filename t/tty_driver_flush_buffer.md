# Function: <code>tty_driver_flush_buffer</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void tty_driver_flush_buffer(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (ffffffff814e8140)
Location: drivers/tty/tty_ioctl.c:91
Inline: True
Direct callers:
  - drivers/tty/tty_io.c:__do_SAK
  - drivers/tty/n_tty.c:isig
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
```
**Symbols:**

```
ffffffff814e8140-ffffffff814e815e: tty_driver_flush_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void tty_driver_flush_buffer(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (ffffffff815392a0)
Location: drivers/tty/tty_ioctl.c:91
Inline: True
Direct callers:
  - drivers/tty/tty_io.c:__do_SAK
  - drivers/tty/n_tty.c:isig
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
```
**Symbols:**

```
ffffffff815392a0-ffffffff815392be: tty_driver_flush_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void tty_driver_flush_buffer(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (ffffffff815659b0)
Location: drivers/tty/tty_ioctl.c:91
Inline: True
Direct callers:
  - drivers/tty/tty_io.c:__do_SAK
  - drivers/tty/n_tty.c:isig
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
```
**Symbols:**

```
ffffffff815659b0-ffffffff815659ce: tty_driver_flush_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void tty_driver_flush_buffer(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (ffffffff815791b0)
Location: drivers/tty/tty_ioctl.c:91
Inline: True
Direct callers:
  - drivers/tty/n_tty.c:isig
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
```
**Symbols:**

```
ffffffff815791b0-ffffffff815791cf: tty_driver_flush_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void tty_driver_flush_buffer(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (ffffffff815ddb50)
Location: drivers/tty/tty_ioctl.c:92
Inline: True
Direct callers:
  - drivers/tty/n_tty.c:isig
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_flush
```
**Symbols:**

```
ffffffff815ddb50-ffffffff815ddb72: tty_driver_flush_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void tty_driver_flush_buffer(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (ffffffff81616e10)
Location: drivers/tty/tty_ioctl.c:92
Inline: True
Direct callers:
  - drivers/tty/n_tty.c:isig
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_flush
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_flush
```
**Symbols:**

```
ffffffff81616e10-ffffffff81616e31: tty_driver_flush_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void tty_driver_flush_buffer(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (ffffffff81634010)
Location: drivers/tty/tty_ioctl.c:92
Inline: True
Direct callers:
  - drivers/tty/n_tty.c:isig
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_flush
```
**Symbols:**

```
ffffffff81634010-ffffffff81634031: tty_driver_flush_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void tty_driver_flush_buffer(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (ffffffff816680c0)
Location: drivers/tty/tty_ioctl.c:92
Inline: True
Direct callers:
  - drivers/tty/n_tty.c:isig
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_flush
```
**Symbols:**

```
ffffffff816680c0-ffffffff816680e1: tty_driver_flush_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void tty_driver_flush_buffer(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (ffffffff8168a810)
Location: drivers/tty/tty_ioctl.c:92
Inline: True
Direct callers:
  - drivers/tty/n_tty.c:isig
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_flush
```
**Symbols:**

```
ffffffff8168a810-ffffffff8168a831: tty_driver_flush_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void tty_driver_flush_buffer(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (ffffffff8173c92c)
Location: drivers/tty/tty_ioctl.c:92
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:__tty_perform_flush
Direct callers:
  - drivers/tty/n_tty.c:isig
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_flush
```
**Symbols:**

```
ffffffff8173c700-ffffffff8173c721: tty_driver_flush_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void tty_driver_flush_buffer(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (ffffffff81758a9c)
Location: drivers/tty/tty_ioctl.c:92
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:__tty_perform_flush
Direct callers:
  - drivers/tty/n_tty.c:isig
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_flush
```
**Symbols:**

```
ffffffff81758870-ffffffff81758891: tty_driver_flush_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void tty_driver_flush_buffer(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (ffffffff8173c93c)
Location: drivers/tty/tty_ioctl.c:92
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:__tty_perform_flush
Direct callers:
  - drivers/tty/n_tty.c:isig
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_flush
```
**Symbols:**

```
ffffffff8173c7d0-ffffffff8173c7f1: tty_driver_flush_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void tty_driver_flush_buffer(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (ffffffff817bcf3c)
Location: drivers/tty/tty_ioctl.c:92
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:__tty_perform_flush
Direct callers:
  - drivers/tty/n_tty.c:isig
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_flush
```
**Symbols:**

```
ffffffff817bcda0-ffffffff817bcdc1: tty_driver_flush_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void tty_driver_flush_buffer(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (ffffffff818f91d5)
Location: drivers/tty/tty_ioctl.c:92
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:__tty_perform_flush
Direct callers:
  - drivers/tty/tty_io.c:__do_SAK
  - drivers/tty/tty_io.c:__do_SAK
  - drivers/tty/n_tty.c:isig
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_port.c:tty_port_close_start
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_flush
```
**Symbols:**

```
ffffffff818f8fe0-ffffffff818f9011: tty_driver_flush_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void tty_driver_flush_buffer(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (ffffffff81a52075)
Location: drivers/tty/tty_ioctl.c:93
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:__tty_perform_flush
Direct callers:
  - drivers/tty/tty_io.c:__do_SAK
  - drivers/tty/tty_io.c:__do_SAK
  - drivers/tty/n_tty.c:isig
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_port.c:tty_port_close_start
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_flush
```
**Symbols:**

```
ffffffff81a51e20-ffffffff81a51e51: tty_driver_flush_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void tty_driver_flush_buffer(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (ffffffff81a9c3a7)
Location: drivers/tty/tty_ioctl.c:94
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:__tty_perform_flush
Direct callers:
  - drivers/tty/tty_io.c:__do_SAK
  - drivers/tty/tty_io.c:__do_SAK
  - drivers/tty/n_tty.c:isig
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_port.c:tty_port_close_start
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_flush
```
**Symbols:**

```
ffffffff81a9c130-ffffffff81a9c161: tty_driver_flush_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void tty_driver_flush_buffer(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (ffffffff81aeee77)
Location: drivers/tty/tty_ioctl.c:82
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:__tty_perform_flush
Direct callers:
  - drivers/tty/tty_io.c:__do_SAK
  - drivers/tty/tty_io.c:__do_SAK
  - drivers/tty/n_tty.c:isig
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_port.c:tty_port_close_start
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_flush
```
**Symbols:**

```
ffffffff81aeec00-ffffffff81aeec31: tty_driver_flush_buffer (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void tty_driver_flush_buffer(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (ffff800010858dd8)
Location: drivers/tty/tty_ioctl.c:92
Inline: True
Direct callers:
  - drivers/tty/n_tty.c:isig
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_flush
```
**Symbols:**

```
ffff800010858dd8-ffff800010858e10: tty_driver_flush_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void tty_driver_flush_buffer(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (c09627a8)
Location: drivers/tty/tty_ioctl.c:92
Inline: True
Direct callers:
  - drivers/tty/n_tty.c:isig
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_flush
```
**Symbols:**

```
c09627a8-c09627d4: tty_driver_flush_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void tty_driver_flush_buffer(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (c0000000008f88a0)
Location: drivers/tty/tty_ioctl.c:92
Inline: True
Direct callers:
  - drivers/tty/n_tty.c:isig
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_flush
```
**Symbols:**

```
c0000000008f88a0-c0000000008f88ec: tty_driver_flush_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void tty_driver_flush_buffer(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (ffffffe000533fc4)
Location: drivers/tty/tty_ioctl.c:92
Inline: True
Direct callers:
  - drivers/tty/n_tty.c:isig
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_flush
```
**Symbols:**

```
ffffffe000533fc4-ffffffe000533fee: tty_driver_flush_buffer (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void tty_driver_flush_buffer(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (ffffffff81650290)
Location: drivers/tty/tty_ioctl.c:92
Inline: True
Direct callers:
  - drivers/tty/n_tty.c:isig
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_flush
```
**Symbols:**

```
ffffffff81650290-ffffffff816502b1: tty_driver_flush_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void tty_driver_flush_buffer(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (ffffffff816306e0)
Location: drivers/tty/tty_ioctl.c:92
Inline: True
Direct callers:
  - drivers/tty/n_tty.c:isig
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
```
**Symbols:**

```
ffffffff816306e0-ffffffff81630701: tty_driver_flush_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void tty_driver_flush_buffer(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (ffffffff8167e650)
Location: drivers/tty/tty_ioctl.c:92
Inline: True
Direct callers:
  - drivers/tty/n_tty.c:isig
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_flush
```
**Symbols:**

```
ffffffff8167e650-ffffffff8167e671: tty_driver_flush_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void tty_driver_flush_buffer(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (ffffffff81698cb0)
Location: drivers/tty/tty_ioctl.c:92
Inline: True
Direct callers:
  - drivers/tty/n_tty.c:isig
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_flush
```
**Symbols:**

```
ffffffff81698cb0-ffffffff81698cd1: tty_driver_flush_buffer (STB_GLOBAL)
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
