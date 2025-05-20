# Function: <code>signotset</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81090953)
Location: include/linux/signal.h:142
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
  - kernel/signal.c:do_sigtimedwait
```
```
In fs/signalfd.c (ffffffff81257025)
Location: include/linux/signal.h:142
Inline: True
Inline callers:
  - fs/signalfd.c:signalfd_show_fdinfo
  - fs/signalfd.c:SyS_signalfd
  - fs/signalfd.c:compat_SyS_signalfd
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81094403)
Location: include/linux/signal.h:157
Inline: True
Inline callers:
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:exit_signals
```
```
In fs/signalfd.c (ffffffff81280614)
Location: include/linux/signal.h:157
Inline: True
Inline callers:
  - fs/signalfd.c:compat_SyS_signalfd
  - fs/signalfd.c:SyS_signalfd
  - fs/signalfd.c:signalfd_show_fdinfo
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810993f3)
Location: include/linux/signal.h:174
Inline: True
Inline callers:
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:exit_signals
```
```
In fs/signalfd.c (ffffffff81294184)
Location: include/linux/signal.h:174
Inline: True
Inline callers:
  - fs/signalfd.c:compat_SyS_signalfd
  - fs/signalfd.c:SyS_signalfd
  - fs/signalfd.c:signalfd_show_fdinfo
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109314e)
Location: include/linux/signal.h:152
Inline: True
Inline callers:
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:exit_signals
```
```
In fs/signalfd.c (ffffffff812a1459)
Location: include/linux/signal.h:152
Inline: True
Inline callers:
  - fs/signalfd.c:compat_SyS_signalfd
  - fs/signalfd.c:SyS_signalfd
  - fs/signalfd.c:signalfd_show_fdinfo
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109a02e)
Location: include/linux/signal.h:167
Inline: True
Inline callers:
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:exit_signals
```
```
In fs/signalfd.c (ffffffff812c4786)
Location: include/linux/signal.h:167
Inline: True
Inline callers:
  - fs/signalfd.c:compat_SyS_signalfd
  - fs/signalfd.c:SyS_signalfd
  - fs/signalfd.c:signalfd_show_fdinfo
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810a0e46)
Location: include/linux/signal.h:169
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
```
```
In fs/signalfd.c (ffffffff812ecdc5)
Location: include/linux/signal.h:169
Inline: True
Inline callers:
  - fs/signalfd.c:signalfd_show_fdinfo
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810a9286)
Location: include/linux/signal.h:177
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
```
```
In fs/signalfd.c (ffffffff81301755)
Location: include/linux/signal.h:177
Inline: True
Inline callers:
  - fs/signalfd.c:signalfd_show_fdinfo
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ad6b8)
Location: include/linux/signal.h:177
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
```
```
In fs/signalfd.c (ffffffff81322cc5)
Location: include/linux/signal.h:177
Inline: True
Inline callers:
  - fs/signalfd.c:signalfd_show_fdinfo
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b3cd8)
Location: include/linux/signal.h:177
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
```
```
In fs/signalfd.c (ffffffff81335a25)
Location: include/linux/signal.h:177
Inline: True
Inline callers:
  - fs/signalfd.c:signalfd_show_fdinfo
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b9142)
Location: include/linux/signal.h:185
Inline: True
Inline callers:
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:exit_signals
```
```
In fs/signalfd.c (ffffffff8136f8ab)
Location: include/linux/signal.h:185
Inline: True
Inline callers:
  - fs/signalfd.c:do_signalfd4
  - fs/signalfd.c:signalfd_show_fdinfo
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b43f2)
Location: include/linux/signal.h:185
Inline: True
Inline callers:
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:exit_signals
```
```
In fs/signalfd.c (ffffffff8137d60b)
Location: include/linux/signal.h:185
Inline: True
Inline callers:
  - fs/signalfd.c:do_signalfd4
  - fs/signalfd.c:signalfd_show_fdinfo
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b6003)
Location: include/linux/signal.h:187
Inline: True
Inline callers:
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:exit_signals
```
```
In fs/signalfd.c (ffffffff8138428b)
Location: include/linux/signal.h:187
Inline: True
Inline callers:
  - fs/signalfd.c:do_signalfd4
  - fs/signalfd.c:signalfd_show_fdinfo
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810c8e93)
Location: include/linux/signal.h:187
Inline: True
Inline callers:
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:exit_signals
```
```
In fs/signalfd.c (ffffffff813d152b)
Location: include/linux/signal.h:187
Inline: True
Inline callers:
  - fs/signalfd.c:do_signalfd4
  - fs/signalfd.c:signalfd_show_fdinfo
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810e0414)
Location: include/linux/signal.h:186
Inline: True
Inline callers:
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:exit_signals
```
```
In fs/signalfd.c (ffffffff8145a7c0)
Location: include/linux/signal.h:186
Inline: True
Inline callers:
  - fs/signalfd.c:do_signalfd4
  - fs/signalfd.c:signalfd_show_fdinfo
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81100ab4)
Location: include/linux/signal.h:186
Inline: True
Inline callers:
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:exit_signals
```
```
In fs/signalfd.c (ffffffff814e9d10)
Location: include/linux/signal.h:186
Inline: True
Inline callers:
  - fs/signalfd.c:do_signalfd4
  - fs/signalfd.c:signalfd_show_fdinfo
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff811114d8)
Location: include/linux/signal.h:186
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
```
```
In fs/signalfd.c (ffffffff81520ab0)
Location: include/linux/signal.h:186
Inline: True
Inline callers:
  - fs/signalfd.c:do_signalfd4
  - fs/signalfd.c:signalfd_show_fdinfo
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8111ae6c)
Location: include/linux/signal.h:187
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
```
```
In fs/signalfd.c (ffffffff815550c0)
Location: include/linux/signal.h:187
Inline: True
Inline callers:
  - fs/signalfd.c:do_signalfd4
  - fs/signalfd.c:signalfd_show_fdinfo
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffff80001010fcd0)
Location: include/linux/signal.h:177
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
```
```
In fs/signalfd.c (ffff8000103f3430)
Location: include/linux/signal.h:177
Inline: True
Inline callers:
  - fs/signalfd.c:signalfd_show_fdinfo
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c036553c)
Location: include/linux/signal.h:177
Inline: True
Inline callers:
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:exit_signals
```
```
In fs/signalfd.c (c05c89d4)
Location: include/linux/signal.h:177
Inline: True
Inline callers:
  - fs/signalfd.c:do_signalfd4
  - fs/signalfd.c:signalfd_show_fdinfo
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c000000000157384)
Location: include/linux/signal.h:177
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
```
```
In fs/signalfd.c (c0000000004fb230)
Location: include/linux/signal.h:177
Inline: True
Inline callers:
  - fs/signalfd.c:signalfd_show_fdinfo
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffe0000d13d2)
Location: include/linux/signal.h:177
Inline: True
Inline callers:
  - kernel/signal.c:__se_sys_rt_sigtimedwait
  - kernel/signal.c:exit_signals
```
```
In fs/signalfd.c (ffffffe0002a4e02)
Location: include/linux/signal.h:177
Inline: True
Inline callers:
  - fs/signalfd.c:signalfd_show_fdinfo
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ae048)
Location: include/linux/signal.h:177
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
```
```
In fs/signalfd.c (ffffffff8132e005)
Location: include/linux/signal.h:177
Inline: True
Inline callers:
  - fs/signalfd.c:signalfd_show_fdinfo
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109c9a2)
Location: include/linux/signal.h:177
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
```
```
In fs/signalfd.c (ffffffff8131ec65)
Location: include/linux/signal.h:177
Inline: True
Inline callers:
  - fs/signalfd.c:signalfd_show_fdinfo
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ad5a8)
Location: include/linux/signal.h:177
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
```
```
In fs/signalfd.c (ffffffff8132bad5)
Location: include/linux/signal.h:177
Inline: True
Inline callers:
  - fs/signalfd.c:signalfd_show_fdinfo
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b577f)
Location: include/linux/signal.h:177
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
```
```
In fs/signalfd.c (ffffffff8133e485)
Location: include/linux/signal.h:177
Inline: True
Inline callers:
  - fs/signalfd.c:signalfd_show_fdinfo
```
</details>
</li>
</ul>

## Differences
