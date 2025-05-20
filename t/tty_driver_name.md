# Function: <code>tty_driver_name</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
const char *tty_driver_name(const struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81534983)
Location: drivers/tty/tty_io.c:252
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:__do_SAK
  - drivers/tty/tty_io.c:__do_SAK
  - drivers/tty/tty_io.c:__do_SAK
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_write
  - drivers/tty/tty_io.c:__proc_set_tty
  - drivers/tty/tty_io.c:check_tty_count
Direct callers:
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
```
**Symbols:**

```
ffffffff81532f90-ffffffff81532fb4: tty_driver_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
const char *tty_driver_name(const struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff815610b3)
Location: drivers/tty/tty_io.c:252
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:__do_SAK
  - drivers/tty/tty_io.c:__do_SAK
  - drivers/tty/tty_io.c:__do_SAK
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_write
  - drivers/tty/tty_io.c:__proc_set_tty
  - drivers/tty/tty_io.c:check_tty_count
Direct callers:
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
```
**Symbols:**

```
ffffffff8155f6c0-ffffffff8155f6e4: tty_driver_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
const char *tty_driver_name(const struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81573511)
Location: drivers/tty/tty_io.c:253
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_write
  - drivers/tty/tty_io.c:check_tty_count
Direct callers:
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
```
**Symbols:**

```
ffffffff81574c00-ffffffff81574c24: tty_driver_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
const char *tty_driver_name(const struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff815d8f94)
Location: drivers/tty/tty_io.c:254
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_write
  - drivers/tty/tty_io.c:check_tty_count
Direct callers:
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
```
**Symbols:**

```
ffffffff815d93d0-ffffffff815d93f4: tty_driver_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
const char *tty_driver_name(const struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff816117d4)
Location: drivers/tty/tty_io.c:254
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_write
  - drivers/tty/tty_io.c:check_tty_count
Direct callers:
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
```
**Symbols:**

```
ffffffff81612360-ffffffff81612384: tty_driver_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
const char *tty_driver_name(const struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff8162e544)
Location: drivers/tty/tty_io.c:255
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_write
  - drivers/tty/tty_io.c:check_tty_count
Direct callers:
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
```
**Symbols:**

```
ffffffff8162f400-ffffffff8162f424: tty_driver_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
const char *tty_driver_name(const struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81662119)
Location: drivers/tty/tty_io.c:255
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_write
  - drivers/tty/tty_io.c:check_tty_count
Direct callers:
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
```
**Symbols:**

```
ffffffff816632b0-ffffffff816632d6: tty_driver_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
const char *tty_driver_name(const struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81684789)
Location: drivers/tty/tty_io.c:255
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_write
  - drivers/tty/tty_io.c:check_tty_count
Direct callers:
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
```
**Symbols:**

```
ffffffff81685920-ffffffff81685946: tty_driver_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
const char *tty_driver_name(const struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81738754)
Location: drivers/tty/tty_io.c:256
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release_checks
  - drivers/tty/tty_io.c:tty_release_checks
  - drivers/tty/tty_io.c:tty_release_checks
  - drivers/tty/tty_io.c:tty_release_checks
  - drivers/tty/tty_io.c:tty_write
Direct callers:
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
```
**Symbols:**

```
ffffffff817372a0-ffffffff817372c6: tty_driver_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
const char *tty_driver_name(const struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81c0761c)
Location: drivers/tty/tty_io.c:253
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release_checks
  - drivers/tty/tty_io.c:tty_release_checks
  - drivers/tty/tty_io.c:tty_release_checks
  - drivers/tty/tty_io.c:tty_release_checks
Direct callers:
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
```
**Symbols:**

```
ffffffff81753660-ffffffff81753686: tty_driver_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
const char *tty_driver_name(const struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81bf92dc)
Location: drivers/tty/tty_io.c:254
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release_checks
  - drivers/tty/tty_io.c:tty_release_checks
  - drivers/tty/tty_io.c:tty_release_checks
  - drivers/tty/tty_io.c:tty_release_checks
Direct callers:
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
```
**Symbols:**

```
ffffffff81737500-ffffffff81737526: tty_driver_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
const char *tty_driver_name(const struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81cf8a79)
Location: drivers/tty/tty_io.c:253
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release_checks
  - drivers/tty/tty_io.c:tty_release_checks
  - drivers/tty/tty_io.c:tty_release_checks
  - drivers/tty/tty_io.c:tty_release_checks
Direct callers:
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
```
**Symbols:**

```
ffffffff817b7ee0-ffffffff817b7f06: tty_driver_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
const char *tty_driver_name(const struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81ec0ac2)
Location: drivers/tty/tty_io.c:252
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:__do_SAK
  - drivers/tty/tty_io.c:__do_SAK
  - drivers/tty/tty_io.c:__do_SAK
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release_checks
  - drivers/tty/tty_io.c:tty_release_checks
  - drivers/tty/tty_io.c:tty_release_checks
  - drivers/tty/tty_io.c:tty_release_checks
Direct callers:
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/tty_port.c:tty_port_close_start
  - drivers/tty/tty_port.c:tty_port_close_start
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
```
**Symbols:**

```
ffffffff818f3c40-ffffffff818f3c72: tty_driver_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
const char *tty_driver_name(const struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81a4c84c)
Location: drivers/tty/tty_io.c:251
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:__do_SAK
  - drivers/tty/tty_io.c:__do_SAK
  - drivers/tty/tty_io.c:__do_SAK
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release_checks
  - drivers/tty/tty_io.c:tty_release_checks
  - drivers/tty/tty_io.c:tty_release_checks
  - drivers/tty/tty_io.c:tty_release_checks
Direct callers:
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/tty_port.c:tty_port_close_start
  - drivers/tty/tty_port.c:tty_port_close_start
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
```
**Symbols:**

```
ffffffff81a4c2a0-ffffffff81a4c2d2: tty_driver_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
const char *tty_driver_name(const struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81a96b3c)
Location: drivers/tty/tty_io.c:252
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:__do_SAK
  - drivers/tty/tty_io.c:__do_SAK
  - drivers/tty/tty_io.c:__do_SAK
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release_checks
  - drivers/tty/tty_io.c:tty_release_checks
  - drivers/tty/tty_io.c:tty_release_checks
  - drivers/tty/tty_io.c:tty_release_checks
Direct callers:
  - drivers/tty/tty_port.c:tty_port_close_start
  - drivers/tty/tty_port.c:tty_port_close_start
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
```
**Symbols:**

```
ffffffff81a964d0-ffffffff81a96502: tty_driver_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
const char *tty_driver_name(const struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81ae952c)
Location: drivers/tty/tty_io.c:252
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:__do_SAK
  - drivers/tty/tty_io.c:__do_SAK
  - drivers/tty/tty_io.c:__do_SAK
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release_checks
  - drivers/tty/tty_io.c:tty_release_checks
  - drivers/tty/tty_io.c:tty_release_checks
  - drivers/tty/tty_io.c:tty_release_checks
  - drivers/tty/tty_io.c:check_tty_count
Direct callers:
  - drivers/tty/tty_port.c:tty_port_close_start
  - drivers/tty/tty_port.c:tty_port_close_start
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
```
**Symbols:**

```
ffffffff81ae8f90-ffffffff81ae8fc2: tty_driver_name (STB_GLOBAL)
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
const char *tty_driver_name(const struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffff800010851c2c)
Location: drivers/tty/tty_io.c:255
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_write
  - drivers/tty/tty_io.c:check_tty_count
Direct callers:
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
```
**Symbols:**

```
ffff800010853328-ffff800010853370: tty_driver_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
const char *tty_driver_name(const struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (c095c6d8)
Location: drivers/tty/tty_io.c:255
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_write
  - drivers/tty/tty_io.c:check_tty_count
Direct callers:
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
```
**Symbols:**

```
c095dcf8-c095dd34: tty_driver_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
const char *tty_driver_name(const struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (c0000000008ef56c)
Location: drivers/tty/tty_io.c:255
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_write
  - drivers/tty/tty_io.c:check_tty_count
Direct callers:
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
```
**Symbols:**

```
c0000000008f25d0-c0000000008f260c: tty_driver_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
const char *tty_driver_name(const struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffe00052f15c)
Location: drivers/tty/tty_io.c:255
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_write
  - drivers/tty/tty_io.c:check_tty_count
Direct callers:
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
```
**Symbols:**

```
ffffffe00052fc26-ffffffe00052fc60: tty_driver_name (STB_GLOBAL)
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
const char *tty_driver_name(const struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff8164a209)
Location: drivers/tty/tty_io.c:255
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_write
  - drivers/tty/tty_io.c:check_tty_count
Direct callers:
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
```
**Symbols:**

```
ffffffff8164b3a0-ffffffff8164b3c6: tty_driver_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
const char *tty_driver_name(const struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff8162a659)
Location: drivers/tty/tty_io.c:255
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_write
  - drivers/tty/tty_io.c:check_tty_count
Direct callers:
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
```
**Symbols:**

```
ffffffff8162b7f0-ffffffff8162b816: tty_driver_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
const char *tty_driver_name(const struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff816785c9)
Location: drivers/tty/tty_io.c:255
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_write
  - drivers/tty/tty_io.c:check_tty_count
Direct callers:
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
```
**Symbols:**

```
ffffffff81679760-ffffffff81679786: tty_driver_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
const char *tty_driver_name(const struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81693781)
Location: drivers/tty/tty_io.c:255
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_write
  - drivers/tty/tty_io.c:check_tty_count
Direct callers:
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/n_tty.c:n_tty_receive_char_flagged
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
```
**Symbols:**

```
ffffffff81693dc0-ffffffff81693de6: tty_driver_name (STB_GLOBAL)
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
