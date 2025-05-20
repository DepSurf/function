# Function: <code>tty_get_pgrp</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct pid *tty_get_pgrp(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff814df5e0)
Location: drivers/tty/tty_io.c:2507
Inline: False
Direct callers:
  - fs/proc/array.c:do_task_stat
  - drivers/tty/tty_io.c:tty_do_resize
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/n_tty.c:__isig
  - drivers/tty/pty.c:pty_resize
  - drivers/tty/pty.c:pty_resize
```
**Symbols:**

```
ffffffff814df5e0-ffffffff814df620: tty_get_pgrp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct pid *tty_get_pgrp(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff815306b0)
Location: drivers/tty/tty_io.c:2514
Inline: False
Direct callers:
  - fs/proc/array.c:do_task_stat
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_do_resize
  - drivers/tty/n_tty.c:__isig
  - drivers/tty/pty.c:pty_resize
  - drivers/tty/pty.c:pty_resize
```
**Symbols:**

```
ffffffff815306b0-ffffffff815306f0: tty_get_pgrp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct pid *tty_get_pgrp(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff8155ce00)
Location: drivers/tty/tty_io.c:2514
Inline: False
Direct callers:
  - fs/proc/array.c:do_task_stat
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_do_resize
  - drivers/tty/n_tty.c:__isig
  - drivers/tty/pty.c:pty_resize
  - drivers/tty/pty.c:pty_resize
```
**Symbols:**

```
ffffffff8155ce00-ffffffff8155ce40: tty_get_pgrp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct pid *tty_get_pgrp(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_jobctrl.c (ffffffff8157ccf0)
Location: drivers/tty/tty_jobctrl.c:397
Inline: False
Direct callers:
  - fs/proc/array.c:do_task_stat
  - drivers/tty/tty_io.c:tty_do_resize
  - drivers/tty/n_tty.c:__isig
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/pty.c:pty_resize
  - drivers/tty/pty.c:pty_resize
```
**Symbols:**

```
ffffffff8157ccf0-ffffffff8157cd30: tty_get_pgrp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct pid *tty_get_pgrp(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_jobctrl.c (ffffffff815e17a0)
Location: drivers/tty/tty_jobctrl.c:398
Inline: False
Direct callers:
  - fs/proc/array.c:do_task_stat
  - drivers/tty/tty_io.c:tty_do_resize
  - drivers/tty/n_tty.c:__isig
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/pty.c:pty_resize
  - drivers/tty/pty.c:pty_resize
```
**Symbols:**

```
ffffffff815e17a0-ffffffff815e17e0: tty_get_pgrp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct pid *tty_get_pgrp(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_jobctrl.c (ffffffff8161aa50)
Location: drivers/tty/tty_jobctrl.c:398
Inline: False
Direct callers:
  - fs/proc/array.c:do_task_stat
  - drivers/tty/tty_io.c:tty_do_resize
  - drivers/tty/n_tty.c:__isig
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/pty.c:pty_resize
  - drivers/tty/pty.c:pty_resize
```
**Symbols:**

```
ffffffff8161aa50-ffffffff8161aa90: tty_get_pgrp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct pid *tty_get_pgrp(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_jobctrl.c (ffffffff81637cc0)
Location: drivers/tty/tty_jobctrl.c:398
Inline: False
Direct callers:
  - fs/proc/array.c:do_task_stat
  - drivers/tty/tty_io.c:tty_do_resize
  - drivers/tty/n_tty.c:__isig
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/pty.c:pty_resize
  - drivers/tty/pty.c:pty_resize
```
**Symbols:**

```
ffffffff81637cc0-ffffffff81637d00: tty_get_pgrp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct pid *tty_get_pgrp(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_jobctrl.c (ffffffff8166c160)
Location: drivers/tty/tty_jobctrl.c:398
Inline: False
Direct callers:
  - fs/proc/array.c:do_task_stat
  - drivers/tty/tty_io.c:tty_do_resize
  - drivers/tty/n_tty.c:__isig
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/pty.c:pty_resize
  - drivers/tty/pty.c:pty_resize
```
**Symbols:**

```
ffffffff8166c160-ffffffff8166c1ac: tty_get_pgrp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct pid *tty_get_pgrp(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_jobctrl.c (ffffffff8168e7d0)
Location: drivers/tty/tty_jobctrl.c:398
Inline: False
Direct callers:
  - fs/proc/array.c:do_task_stat
  - drivers/tty/tty_io.c:tty_do_resize
  - drivers/tty/n_tty.c:__isig
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/pty.c:pty_resize
  - drivers/tty/pty.c:pty_resize
```
**Symbols:**

```
ffffffff8168e7d0-ffffffff8168e81c: tty_get_pgrp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct pid *tty_get_pgrp(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_jobctrl.c (ffffffff8174185f)
Location: drivers/tty/tty_jobctrl.c:398
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
Direct callers:
  - fs/proc/array.c:do_task_stat
  - drivers/tty/tty_io.c:tty_do_resize
  - drivers/tty/n_tty.c:isig
  - drivers/tty/n_tty.c:isig
  - drivers/tty/pty.c:pty_resize
  - drivers/tty/pty.c:pty_resize
  - drivers/tty/pty.c:pty_signal
```
**Symbols:**

```
ffffffff81740a20-ffffffff81740a9c: tty_get_pgrp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct pid *tty_get_pgrp(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_jobctrl.c (ffffffff8175c950)
Location: drivers/tty/tty_jobctrl.c:404
Inline: False
Direct callers:
  - fs/proc/array.c:do_task_stat
  - drivers/tty/tty_io.c:tty_do_resize
  - drivers/tty/n_tty.c:isig
  - drivers/tty/n_tty.c:isig
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/pty.c:pty_resize
  - drivers/tty/pty.c:pty_resize
  - drivers/tty/pty.c:pty_signal
```
**Symbols:**

```
ffffffff8175c950-ffffffff8175c9cc: tty_get_pgrp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct pid *tty_get_pgrp(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_jobctrl.c (ffffffff817407e0)
Location: drivers/tty/tty_jobctrl.c:414
Inline: False
Direct callers:
  - fs/proc/array.c:do_task_stat
  - drivers/tty/tty_io.c:tty_do_resize
  - drivers/tty/n_tty.c:isig
  - drivers/tty/n_tty.c:isig
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/pty.c:pty_resize
  - drivers/tty/pty.c:pty_resize
  - drivers/tty/pty.c:pty_signal
```
**Symbols:**

```
ffffffff817407e0-ffffffff8174085c: tty_get_pgrp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct pid *tty_get_pgrp(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_jobctrl.c (ffffffff817c1240)
Location: drivers/tty/tty_jobctrl.c:416
Inline: False
Direct callers:
  - fs/proc/array.c:do_task_stat
  - drivers/tty/tty_io.c:tty_do_resize
  - drivers/tty/n_tty.c:isig
  - drivers/tty/n_tty.c:isig
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/pty.c:pty_resize
  - drivers/tty/pty.c:pty_resize
  - drivers/tty/pty.c:pty_signal
```
**Symbols:**

```
ffffffff817c1240-ffffffff817c12bc: tty_get_pgrp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct pid *tty_get_pgrp(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_jobctrl.c (ffffffff818fdc00)
Location: drivers/tty/tty_jobctrl.c:416
Inline: False
Direct callers:
  - fs/proc/array.c:do_task_stat
  - drivers/tty/tty_io.c:tty_do_resize
  - drivers/tty/n_tty.c:isig
  - drivers/tty/n_tty.c:isig
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/pty.c:pty_resize
  - drivers/tty/pty.c:pty_resize
  - drivers/tty/pty.c:pty_signal
```
**Symbols:**

```
ffffffff818fdc00-ffffffff818fdc80: tty_get_pgrp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct pid *tty_get_pgrp(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_jobctrl.c (ffffffff81a57390)
Location: drivers/tty/tty_jobctrl.c:416
Inline: False
Direct callers:
  - fs/proc/array.c:do_task_stat
  - drivers/tty/tty_io.c:tty_do_resize
  - drivers/tty/n_tty.c:isig
  - drivers/tty/n_tty.c:isig
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/pty.c:pty_resize
  - drivers/tty/pty.c:pty_resize
  - drivers/tty/pty.c:pty_signal
```
**Symbols:**

```
ffffffff81a57390-ffffffff81a57410: tty_get_pgrp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct pid *tty_get_pgrp(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_jobctrl.c (ffffffff81aa1990)
Location: drivers/tty/tty_jobctrl.c:416
Inline: False
Direct callers:
  - fs/proc/array.c:do_task_stat
  - drivers/tty/tty_io.c:tty_do_resize
  - drivers/tty/n_tty.c:isig
  - drivers/tty/n_tty.c:isig
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/pty.c:pty_resize
  - drivers/tty/pty.c:pty_resize
  - drivers/tty/pty.c:pty_signal
```
**Symbols:**

```
ffffffff81aa1990-ffffffff81aa1a10: tty_get_pgrp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct pid *tty_get_pgrp(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_jobctrl.c (ffffffff81af43f0)
Location: drivers/tty/tty_jobctrl.c:421
Inline: False
Direct callers:
  - fs/proc/array.c:do_task_stat
  - drivers/tty/tty_io.c:tty_do_resize
  - drivers/tty/n_tty.c:isig
  - drivers/tty/n_tty.c:isig
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/pty.c:pty_resize
  - drivers/tty/pty.c:pty_resize
  - drivers/tty/pty.c:pty_signal
```
**Symbols:**

```
ffffffff81af43f0-ffffffff81af4470: tty_get_pgrp (STB_GLOBAL)
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
struct pid *tty_get_pgrp(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_jobctrl.c (ffff80001085fbe0)
Location: drivers/tty/tty_jobctrl.c:398
Inline: False
Direct callers:
  - fs/proc/array.c:do_task_stat
  - drivers/tty/tty_io.c:tty_do_resize
  - drivers/tty/n_tty.c:__isig
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/pty.c:pty_resize
  - drivers/tty/pty.c:pty_resize
```
**Symbols:**

```
ffff80001085fbe0-ffff80001085fc98: tty_get_pgrp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct pid *tty_get_pgrp(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_jobctrl.c (c0966e50)
Location: drivers/tty/tty_jobctrl.c:398
Inline: False
Direct callers:
  - fs/proc/array.c:do_task_stat
  - drivers/tty/tty_io.c:tty_do_resize
  - drivers/tty/n_tty.c:__isig
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/pty.c:pty_resize
  - drivers/tty/pty.c:pty_resize
  - drivers/tty/pty.c:pty_signal
```
**Symbols:**

```
c0966e50-c0966ea0: tty_get_pgrp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct pid *tty_get_pgrp(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_jobctrl.c (c0000000008ff110)
Location: drivers/tty/tty_jobctrl.c:398
Inline: False
Direct callers:
  - fs/proc/array.c:do_task_stat
  - drivers/tty/tty_io.c:tty_do_resize
  - drivers/tty/n_tty.c:__isig
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/pty.c:pty_resize
  - drivers/tty/pty.c:pty_resize
  - drivers/tty/pty.c:pty_signal
```
**Symbols:**

```
c0000000008ff110-c0000000008ff190: tty_get_pgrp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct pid *tty_get_pgrp(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_jobctrl.c (ffffffe000537e54)
Location: drivers/tty/tty_jobctrl.c:398
Inline: False
Direct callers:
  - fs/proc/array.c:do_task_stat
  - drivers/tty/tty_io.c:tty_do_resize
  - drivers/tty/n_tty.c:__isig
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/pty.c:pty_resize
  - drivers/tty/pty.c:pty_resize
  - drivers/tty/pty.c:pty_signal
```
**Symbols:**

```
ffffffe000537e54-ffffffe000537ea0: tty_get_pgrp (STB_GLOBAL)
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
struct pid *tty_get_pgrp(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_jobctrl.c (ffffffff81654250)
Location: drivers/tty/tty_jobctrl.c:398
Inline: False
Direct callers:
  - fs/proc/array.c:do_task_stat
  - drivers/tty/tty_io.c:tty_do_resize
  - drivers/tty/n_tty.c:__isig
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/pty.c:pty_resize
  - drivers/tty/pty.c:pty_resize
```
**Symbols:**

```
ffffffff81654250-ffffffff8165429c: tty_get_pgrp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct pid *tty_get_pgrp(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_jobctrl.c (ffffffff81634630)
Location: drivers/tty/tty_jobctrl.c:398
Inline: False
Direct callers:
  - fs/proc/array.c:do_task_stat
  - drivers/tty/tty_io.c:tty_do_resize
  - drivers/tty/n_tty.c:__isig
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/pty.c:pty_resize
  - drivers/tty/pty.c:pty_resize
```
**Symbols:**

```
ffffffff81634630-ffffffff8163467c: tty_get_pgrp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct pid *tty_get_pgrp(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_jobctrl.c (ffffffff81682610)
Location: drivers/tty/tty_jobctrl.c:398
Inline: False
Direct callers:
  - fs/proc/array.c:do_task_stat
  - drivers/tty/tty_io.c:tty_do_resize
  - drivers/tty/n_tty.c:__isig
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/pty.c:pty_resize
  - drivers/tty/pty.c:pty_resize
```
**Symbols:**

```
ffffffff81682610-ffffffff8168265c: tty_get_pgrp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct pid *tty_get_pgrp(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_jobctrl.c (ffffffff8169cc70)
Location: drivers/tty/tty_jobctrl.c:398
Inline: False
Direct callers:
  - fs/proc/array.c:do_task_stat
  - drivers/tty/tty_io.c:tty_do_resize
  - drivers/tty/n_tty.c:__isig
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/pty.c:pty_resize
  - drivers/tty/pty.c:pty_resize
```
**Symbols:**

```
ffffffff8169cc70-ffffffff8169ccbc: tty_get_pgrp (STB_GLOBAL)
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
