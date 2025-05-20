# Function: <code>unset_locked_termios</code>

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
In drivers/tty/tty_ioctl.c (ffffffff814e874e)
Location: drivers/tty/tty_ioctl.c:242
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_set_termios
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
In drivers/tty/tty_ioctl.c (ffffffff8153992c)
Location: drivers/tty/tty_ioctl.c:242
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_set_termios
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
In drivers/tty/tty_ioctl.c (ffffffff8156600c)
Location: drivers/tty/tty_ioctl.c:242
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_set_termios
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
In drivers/tty/tty_ioctl.c (ffffffff81579619)
Location: drivers/tty/tty_ioctl.c:242
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_set_termios
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
In drivers/tty/tty_ioctl.c (ffffffff815ddfc9)
Location: drivers/tty/tty_ioctl.c:243
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_set_termios
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
In drivers/tty/tty_ioctl.c (ffffffff816172f9)
Location: drivers/tty/tty_ioctl.c:243
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_set_termios
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
In drivers/tty/tty_ioctl.c (ffffffff816344f9)
Location: drivers/tty/tty_ioctl.c:243
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_set_termios
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
In drivers/tty/tty_ioctl.c (ffffffff816685b8)
Location: drivers/tty/tty_ioctl.c:243
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_set_termios
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
In drivers/tty/tty_ioctl.c (ffffffff8168ad08)
Location: drivers/tty/tty_ioctl.c:243
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_set_termios
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void unset_locked_termios(struct tty_struct *tty, struct ktermios *old);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (ffffffff8173c730)
Location: drivers/tty/tty_ioctl.c:243
Inline: False
Direct callers:
  - drivers/tty/tty_ioctl.c:tty_set_termios
```
**Symbols:**

```
ffffffff8173c730-ffffffff8173c7e8: unset_locked_termios (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void unset_locked_termios(struct tty_struct *tty, struct ktermios *old);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (ffffffff817588a0)
Location: drivers/tty/tty_ioctl.c:243
Inline: False
Direct callers:
  - drivers/tty/tty_ioctl.c:tty_set_termios
```
**Symbols:**

```
ffffffff817588a0-ffffffff81758958: unset_locked_termios (STB_LOCAL)
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
In drivers/tty/tty_ioctl.c (ffffffff8173cc30)
Location: drivers/tty/tty_ioctl.c:243
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_set_termios
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
In drivers/tty/tty_ioctl.c (ffffffff817bd220)
Location: drivers/tty/tty_ioctl.c:222
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_set_termios
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
In drivers/tty/tty_ioctl.c (ffffffff818f9506)
Location: drivers/tty/tty_ioctl.c:222
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_set_termios
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
In drivers/tty/tty_ioctl.c (ffffffff81a523c6)
Location: drivers/tty/tty_ioctl.c:223
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_set_termios
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
In drivers/tty/tty_ioctl.c (ffffffff81a9c6c5)
Location: drivers/tty/tty_ioctl.c:224
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_set_termios
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
In drivers/tty/tty_ioctl.c (ffffffff81aef195)
Location: drivers/tty/tty_ioctl.c:206
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_set_termios
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
In drivers/tty/tty_ioctl.c (ffff8000108591e0)
Location: drivers/tty/tty_ioctl.c:243
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_set_termios
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
In drivers/tty/tty_ioctl.c (c0962c44)
Location: drivers/tty/tty_ioctl.c:243
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_set_termios
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
In drivers/tty/tty_ioctl.c (c0000000008f8de4)
Location: drivers/tty/tty_ioctl.c:243
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_set_termios
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
In drivers/tty/tty_ioctl.c (ffffffe00053432c)
Location: drivers/tty/tty_ioctl.c:243
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_set_termios
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
In drivers/tty/tty_ioctl.c (ffffffff81650788)
Location: drivers/tty/tty_ioctl.c:243
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_set_termios
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
In drivers/tty/tty_ioctl.c (ffffffff81630bd8)
Location: drivers/tty/tty_ioctl.c:243
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_set_termios
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
In drivers/tty/tty_ioctl.c (ffffffff8167eb48)
Location: drivers/tty/tty_ioctl.c:243
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_set_termios
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
In drivers/tty/tty_ioctl.c (ffffffff81699198)
Location: drivers/tty/tty_ioctl.c:243
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_set_termios
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
</ul>
