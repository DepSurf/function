# Function: <code>kill_pgrp</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int kill_pgrp(struct pid *pid, int sig, int priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8108f820)
Location: kernel/signal.c:1459
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_do_resize
  - drivers/tty/tty_io.c:__tty_hangup
  - drivers/tty/n_tty.c:__isig
  - drivers/tty/pty.c:pty_resize
  - drivers/tty/pty.c:pty_resize
```
**Symbols:**

```
ffffffff8108f820-ffffffff8108f869: kill_pgrp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int kill_pgrp(struct pid *pid, int sig, int priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810928a0)
Location: kernel/signal.c:1459
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_do_resize
  - drivers/tty/tty_io.c:__tty_hangup
  - drivers/tty/n_tty.c:__isig
  - drivers/tty/pty.c:pty_resize
  - drivers/tty/pty.c:pty_resize
```
**Symbols:**

```
ffffffff810928a0-ffffffff810928e9: kill_pgrp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int kill_pgrp(struct pid *pid, int sig, int priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81097830)
Location: kernel/signal.c:1465
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_do_resize
  - drivers/tty/tty_io.c:__tty_hangup
  - drivers/tty/n_tty.c:__isig
  - drivers/tty/pty.c:pty_resize
  - drivers/tty/pty.c:pty_resize
```
**Symbols:**

```
ffffffff81097830-ffffffff81097879: kill_pgrp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int kill_pgrp(struct pid *pid, int sig, int priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81094b60)
Location: kernel/signal.c:1487
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_do_resize
  - drivers/tty/n_tty.c:__isig
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/pty.c:pty_resize
  - drivers/tty/pty.c:pty_resize
```
**Symbols:**

```
ffffffff81094b60-ffffffff81094ba9: kill_pgrp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int kill_pgrp(struct pid *pid, int sig, int priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109ba00)
Location: kernel/signal.c:1488
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_do_resize
  - drivers/tty/n_tty.c:__isig
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/pty.c:pty_resize
  - drivers/tty/pty.c:pty_resize
```
**Symbols:**

```
ffffffff8109ba00-ffffffff8109ba49: kill_pgrp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int kill_pgrp(struct pid *pid, int sig, int priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109fa60)
Location: kernel/signal.c:1605
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_do_resize
  - drivers/tty/n_tty.c:__isig
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/pty.c:pty_resize
  - drivers/tty/pty.c:pty_resize
```
**Symbols:**

```
ffffffff8109fa60-ffffffff8109faa9: kill_pgrp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int kill_pgrp(struct pid *pid, int sig, int priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810a7d10)
Location: kernel/signal.c:1691
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_do_resize
  - drivers/tty/n_tty.c:__isig
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/pty.c:pty_resize
  - drivers/tty/pty.c:pty_resize
```
**Symbols:**

```
ffffffff810a7d10-ffffffff810a7d59: kill_pgrp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int kill_pgrp(struct pid *pid, int sig, int priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ad880)
Location: kernel/signal.c:1779
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_do_resize
  - drivers/tty/n_tty.c:__isig
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/pty.c:pty_resize
  - drivers/tty/pty.c:pty_resize
```
**Symbols:**

```
ffffffff810ad880-ffffffff810ad8c9: kill_pgrp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int kill_pgrp(struct pid *pid, int sig, int priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b3ea0)
Location: kernel/signal.c:1784
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_do_resize
  - drivers/tty/n_tty.c:__isig
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/pty.c:pty_resize
  - drivers/tty/pty.c:pty_resize
```
**Symbols:**

```
ffffffff810b3ea0-ffffffff810b3ee9: kill_pgrp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int kill_pgrp(struct pid *pid, int sig, int priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810bd020)
Location: kernel/signal.c:1780
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_do_resize
  - drivers/tty/n_tty.c:isig
  - drivers/tty/n_tty.c:isig
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/pty.c:pty_resize
  - drivers/tty/pty.c:pty_resize
  - drivers/tty/pty.c:pty_signal
```
**Symbols:**

```
ffffffff810bd020-ffffffff810bd069: kill_pgrp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int kill_pgrp(struct pid *pid, int sig, int priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b8350)
Location: kernel/signal.c:1781
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_do_resize
  - drivers/tty/n_tty.c:isig
  - drivers/tty/n_tty.c:isig
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/pty.c:pty_resize
  - drivers/tty/pty.c:pty_resize
  - drivers/tty/pty.c:pty_signal
```
**Symbols:**

```
ffffffff810b8350-ffffffff810b8399: kill_pgrp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int kill_pgrp(struct pid *pid, int sig, int priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b98d0)
Location: kernel/signal.c:1798
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_do_resize
  - drivers/tty/n_tty.c:isig
  - drivers/tty/n_tty.c:isig
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/pty.c:pty_resize
  - drivers/tty/pty.c:pty_resize
  - drivers/tty/pty.c:pty_signal
```
**Symbols:**

```
ffffffff810b98d0-ffffffff810b9919: kill_pgrp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int kill_pgrp(struct pid *pid, int sig, int priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810cbee0)
Location: kernel/signal.c:1890
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_do_resize
  - drivers/tty/n_tty.c:isig
  - drivers/tty/n_tty.c:isig
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/pty.c:pty_resize
  - drivers/tty/pty.c:pty_resize
  - drivers/tty/pty.c:pty_signal
```
**Symbols:**

```
ffffffff810cbee0-ffffffff810cbf29: kill_pgrp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int kill_pgrp(struct pid *pid, int sig, int priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810e2fc0)
Location: kernel/signal.c:1903
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_do_resize
  - drivers/tty/n_tty.c:isig
  - drivers/tty/n_tty.c:isig
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/pty.c:pty_resize
  - drivers/tty/pty.c:pty_resize
  - drivers/tty/pty.c:pty_signal
```
**Symbols:**

```
ffffffff810e2fc0-ffffffff810e3016: kill_pgrp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int kill_pgrp(struct pid *pid, int sig, int priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff811034c0)
Location: kernel/signal.c:1904
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_do_resize
  - drivers/tty/n_tty.c:isig
  - drivers/tty/n_tty.c:isig
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/pty.c:pty_resize
  - drivers/tty/pty.c:pty_resize
  - drivers/tty/pty.c:pty_signal
```
**Symbols:**

```
ffffffff811034c0-ffffffff81103516: kill_pgrp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int kill_pgrp(struct pid *pid, int sig, int priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8110f700)
Location: kernel/signal.c:1910
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_do_resize
  - drivers/tty/n_tty.c:isig
  - drivers/tty/n_tty.c:isig
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/pty.c:pty_resize
  - drivers/tty/pty.c:pty_resize
  - drivers/tty/pty.c:pty_signal
```
**Symbols:**

```
ffffffff8110f700-ffffffff8110f756: kill_pgrp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int kill_pgrp(struct pid *pid, int sig, int priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81119070)
Location: kernel/signal.c:1901
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_do_resize
  - drivers/tty/n_tty.c:isig
  - drivers/tty/n_tty.c:isig
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/pty.c:pty_resize
  - drivers/tty/pty.c:pty_resize
  - drivers/tty/pty.c:pty_signal
```
**Symbols:**

```
ffffffff81119070-ffffffff811190c6: kill_pgrp (STB_GLOBAL)
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
int kill_pgrp(struct pid *pid, int sig, int priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffff80001010fef0)
Location: kernel/signal.c:1784
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_do_resize
  - drivers/tty/n_tty.c:__isig
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/pty.c:pty_resize
  - drivers/tty/pty.c:pty_resize
```
**Symbols:**

```
ffff80001010fef0-ffff80001010ffb4: kill_pgrp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int kill_pgrp(struct pid *pid, int sig, int priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c0367cb0)
Location: kernel/signal.c:1784
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_do_resize
  - drivers/tty/n_tty.c:__isig
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/pty.c:pty_resize
  - drivers/tty/pty.c:pty_resize
  - drivers/tty/pty.c:pty_signal
```
**Symbols:**

```
c0367cb0-c0367d24: kill_pgrp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int kill_pgrp(struct pid *pid, int sig, int priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c000000000157640)
Location: kernel/signal.c:1784
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_do_resize
  - drivers/tty/n_tty.c:__isig
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/pty.c:pty_resize
  - drivers/tty/pty.c:pty_resize
  - drivers/tty/pty.c:pty_signal
```
**Symbols:**

```
c000000000157640-c0000000001576d0: kill_pgrp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int kill_pgrp(struct pid *pid, int sig, int priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffe0000d0204)
Location: kernel/signal.c:1784
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_do_resize
  - drivers/tty/n_tty.c:__isig
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/pty.c:pty_resize
  - drivers/tty/pty.c:pty_resize
  - drivers/tty/pty.c:pty_signal
```
**Symbols:**

```
ffffffe0000d0204-ffffffe0000d0262: kill_pgrp (STB_GLOBAL)
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
int kill_pgrp(struct pid *pid, int sig, int priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ae210)
Location: kernel/signal.c:1784
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_do_resize
  - drivers/tty/n_tty.c:__isig
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/pty.c:pty_resize
  - drivers/tty/pty.c:pty_resize
```
**Symbols:**

```
ffffffff810ae210-ffffffff810ae259: kill_pgrp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int kill_pgrp(struct pid *pid, int sig, int priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109cb60)
Location: kernel/signal.c:1784
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_do_resize
  - drivers/tty/n_tty.c:__isig
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/pty.c:pty_resize
  - drivers/tty/pty.c:pty_resize
```
**Symbols:**

```
ffffffff8109cb60-ffffffff8109cba9: kill_pgrp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int kill_pgrp(struct pid *pid, int sig, int priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ad770)
Location: kernel/signal.c:1784
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_do_resize
  - drivers/tty/n_tty.c:__isig
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/pty.c:pty_resize
  - drivers/tty/pty.c:pty_resize
```
**Symbols:**

```
ffffffff810ad770-ffffffff810ad7b9: kill_pgrp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int kill_pgrp(struct pid *pid, int sig, int priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b5980)
Location: kernel/signal.c:1784
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_do_resize
  - drivers/tty/n_tty.c:__isig
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/pty.c:pty_resize
  - drivers/tty/pty.c:pty_resize
```
**Symbols:**

```
ffffffff810b5980-ffffffff810b59ce: kill_pgrp (STB_GLOBAL)
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
