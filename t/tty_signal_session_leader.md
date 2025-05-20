# Function: <code>tty_signal_session_leader</code>

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
In drivers/tty/tty_io.c (ffffffff814e141d)
Location: drivers/tty/tty_io.c:615
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:__tty_hangup
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
In drivers/tty/tty_io.c (ffffffff8153282f)
Location: drivers/tty/tty_io.c:622
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:__tty_hangup
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
In drivers/tty/tty_io.c (ffffffff8155ef5f)
Location: drivers/tty/tty_io.c:622
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:__tty_hangup
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int tty_signal_session_leader(struct tty_struct *tty, int exit_session);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_jobctrl.c (ffffffff8157d3f0)
Location: drivers/tty/tty_jobctrl.c:190
Inline: False
```
**Symbols:**

```
ffffffff8157d3f0-ffffffff8157d594: tty_signal_session_leader (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int tty_signal_session_leader(struct tty_struct *tty, int exit_session);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_jobctrl.c (ffffffff815e1f10)
Location: drivers/tty/tty_jobctrl.c:191
Inline: False
```
**Symbols:**

```
ffffffff815e1f10-ffffffff815e20b4: tty_signal_session_leader (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int tty_signal_session_leader(struct tty_struct *tty, int exit_session);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_jobctrl.c (ffffffff8161b1c0)
Location: drivers/tty/tty_jobctrl.c:191
Inline: False
```
**Symbols:**

```
ffffffff8161b1c0-ffffffff8161b364: tty_signal_session_leader (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int tty_signal_session_leader(struct tty_struct *tty, int exit_session);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_jobctrl.c (ffffffff81638430)
Location: drivers/tty/tty_jobctrl.c:191
Inline: False
```
**Symbols:**

```
ffffffff81638430-ffffffff816385d4: tty_signal_session_leader (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int tty_signal_session_leader(struct tty_struct *tty, int exit_session);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_jobctrl.c (ffffffff8166c6e0)
Location: drivers/tty/tty_jobctrl.c:191
Inline: False
```
**Symbols:**

```
ffffffff8166c6e0-ffffffff8166c886: tty_signal_session_leader (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int tty_signal_session_leader(struct tty_struct *tty, int exit_session);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_jobctrl.c (ffffffff8168ed50)
Location: drivers/tty/tty_jobctrl.c:191
Inline: False
```
**Symbols:**

```
ffffffff8168ed50-ffffffff8168eef6: tty_signal_session_leader (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int tty_signal_session_leader(struct tty_struct *tty, int exit_session);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_jobctrl.c (ffffffff817414f0)
Location: drivers/tty/tty_jobctrl.c:191
Inline: False
```
**Symbols:**

```
ffffffff817414f0-ffffffff8174172a: tty_signal_session_leader (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int tty_signal_session_leader(struct tty_struct *tty, int exit_session);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_jobctrl.c (ffffffff8175d3e0)
Location: drivers/tty/tty_jobctrl.c:193
Inline: False
```
**Symbols:**

```
ffffffff8175d3e0-ffffffff8175d61a: tty_signal_session_leader (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int tty_signal_session_leader(struct tty_struct *tty, int exit_session);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_jobctrl.c (ffffffff81740f60)
Location: drivers/tty/tty_jobctrl.c:196
Inline: False
```
**Symbols:**

```
ffffffff81740f60-ffffffff81741192: tty_signal_session_leader (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int tty_signal_session_leader(struct tty_struct *tty, int exit_session);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_jobctrl.c (ffffffff817c19c0)
Location: drivers/tty/tty_jobctrl.c:196
Inline: False
```
**Symbols:**

```
ffffffff817c19c0-ffffffff817c1bf2: tty_signal_session_leader (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int tty_signal_session_leader(struct tty_struct *tty, int exit_session);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_jobctrl.c (ffffffff818fe3e0)
Location: drivers/tty/tty_jobctrl.c:196
Inline: False
```
**Symbols:**

```
ffffffff818fe3e0-ffffffff818fe631: tty_signal_session_leader (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int tty_signal_session_leader(struct tty_struct *tty, int exit_session);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_jobctrl.c (ffffffff81a57bf0)
Location: drivers/tty/tty_jobctrl.c:196
Inline: False
```
**Symbols:**

```
ffffffff81a57bf0-ffffffff81a57e41: tty_signal_session_leader (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int tty_signal_session_leader(struct tty_struct *tty, int exit_session);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_jobctrl.c (ffffffff81aa21f0)
Location: drivers/tty/tty_jobctrl.c:196
Inline: False
```
**Symbols:**

```
ffffffff81aa21f0-ffffffff81aa2441: tty_signal_session_leader (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int tty_signal_session_leader(struct tty_struct *tty, int exit_session);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_jobctrl.c (ffffffff81af4bd0)
Location: drivers/tty/tty_jobctrl.c:196
Inline: False
```
**Symbols:**

```
ffffffff81af4bd0-ffffffff81af4e21: tty_signal_session_leader (STB_GLOBAL)
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
int tty_signal_session_leader(struct tty_struct *tty, int exit_session);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_jobctrl.c (ffff800010860660)
Location: drivers/tty/tty_jobctrl.c:191
Inline: False
```
**Symbols:**

```
ffff800010860660-ffff8000108608e0: tty_signal_session_leader (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int tty_signal_session_leader(struct tty_struct *tty, int exit_session);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_jobctrl.c (c0967684)
Location: drivers/tty/tty_jobctrl.c:191
Inline: False
```
**Symbols:**

```
c0967684-c0967844: tty_signal_session_leader (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int tty_signal_session_leader(struct tty_struct *tty, int exit_session);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_jobctrl.c (c0000000008ffa80)
Location: drivers/tty/tty_jobctrl.c:191
Inline: False
```
**Symbols:**

```
c0000000008ffa80-c0000000008ffd6c: tty_signal_session_leader (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int tty_signal_session_leader(struct tty_struct *tty, int exit_session);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_jobctrl.c (ffffffe0005384ba)
Location: drivers/tty/tty_jobctrl.c:191
Inline: False
```
**Symbols:**

```
ffffffe0005384ba-ffffffe00053869a: tty_signal_session_leader (STB_GLOBAL)
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
int tty_signal_session_leader(struct tty_struct *tty, int exit_session);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_jobctrl.c (ffffffff816547d0)
Location: drivers/tty/tty_jobctrl.c:191
Inline: False
```
**Symbols:**

```
ffffffff816547d0-ffffffff81654976: tty_signal_session_leader (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int tty_signal_session_leader(struct tty_struct *tty, int exit_session);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_jobctrl.c (ffffffff81634bb0)
Location: drivers/tty/tty_jobctrl.c:191
Inline: False
```
**Symbols:**

```
ffffffff81634bb0-ffffffff81634d50: tty_signal_session_leader (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int tty_signal_session_leader(struct tty_struct *tty, int exit_session);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_jobctrl.c (ffffffff81682b90)
Location: drivers/tty/tty_jobctrl.c:191
Inline: False
```
**Symbols:**

```
ffffffff81682b90-ffffffff81682d36: tty_signal_session_leader (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int tty_signal_session_leader(struct tty_struct *tty, int exit_session);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_jobctrl.c (ffffffff8169d1e0)
Location: drivers/tty/tty_jobctrl.c:191
Inline: False
```
**Symbols:**

```
ffffffff8169d1e0-ffffffff8169d389: tty_signal_session_leader (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
