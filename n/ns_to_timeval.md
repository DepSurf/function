# Function: <code>ns_to_timeval</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct timeval ns_to_timeval(const s64 nsec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff810eb0b0)
Location: kernel/time/time.c:414
Inline: False
Direct callers:
  - kernel/time/itimer.c:itimer_get_remtime
  - kernel/time/itimer.c:itimer_get_remtime
  - kernel/time/itimer.c:do_getitimer
  - kernel/time/itimer.c:do_setitimer
  - drivers/input/evdev.c:evdev_pass_values
  - drivers/input/evdev.c:__evdev_queue_syn_dropped
  - net/socket.c:__sock_recv_timestamp
  - net/core/sock.c:sock_get_timestamp
  - net/core/sock.c:sock_get_timestamp
  - net/compat.c:compat_sock_get_timestamp
  - net/compat.c:compat_sock_get_timestamp
```
**Symbols:**

```
ffffffff810eb0b0-ffffffff810eb12b: ns_to_timeval (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct timeval ns_to_timeval(const s64 nsec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff810f1d80)
Location: kernel/time/time.c:421
Inline: False
Direct callers:
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:do_getitimer
  - kernel/time/itimer.c:itimer_get_remtime
  - kernel/time/itimer.c:itimer_get_remtime
  - drivers/input/evdev.c:evdev_pass_values
  - drivers/input/evdev.c:__evdev_queue_syn_dropped
  - net/socket.c:__sock_recv_timestamp
  - net/core/sock.c:sock_get_timestamp
  - net/core/sock.c:sock_get_timestamp
  - net/compat.c:compat_sock_get_timestamp
  - net/compat.c:compat_sock_get_timestamp
```
**Symbols:**

```
ffffffff810f1d80-ffffffff810f1dfe: ns_to_timeval (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct timeval ns_to_timeval(const s64 nsec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff810f8f00)
Location: kernel/time/time.c:421
Inline: False
Direct callers:
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:do_getitimer
  - kernel/time/itimer.c:itimer_get_remtime
  - kernel/time/itimer.c:itimer_get_remtime
  - drivers/input/evdev.c:evdev_pass_values
  - drivers/input/evdev.c:__evdev_queue_syn_dropped
  - net/socket.c:__sock_recv_timestamp
  - net/core/sock.c:sock_get_timestamp
  - net/core/sock.c:sock_get_timestamp
  - net/compat.c:compat_sock_get_timestamp
  - net/compat.c:compat_sock_get_timestamp
```
**Symbols:**

```
ffffffff810f8f00-ffffffff810f8f7e: ns_to_timeval (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct timeval ns_to_timeval(const s64 nsec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff810fb1a0)
Location: kernel/time/time.c:511
Inline: False
Direct callers:
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:set_cpu_itimer
  - kernel/time/itimer.c:set_cpu_itimer
  - kernel/time/itimer.c:do_getitimer
  - kernel/time/itimer.c:get_cpu_itimer
  - kernel/time/itimer.c:get_cpu_itimer
  - kernel/time/itimer.c:itimer_get_remtime
  - kernel/time/itimer.c:itimer_get_remtime
  - drivers/input/evdev.c:evdev_pass_values
  - drivers/input/evdev.c:__evdev_queue_syn_dropped
  - net/socket.c:__sock_recv_timestamp
  - net/core/sock.c:sock_get_timestamp
  - net/core/sock.c:sock_get_timestamp
  - net/compat.c:compat_sock_get_timestamp
  - net/compat.c:compat_sock_get_timestamp
```
**Symbols:**

```
ffffffff810fb1a0-ffffffff810fb224: ns_to_timeval (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct timeval ns_to_timeval(const s64 nsec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81105b40)
Location: kernel/time/time.c:479
Inline: False
Direct callers:
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:set_cpu_itimer
  - kernel/time/itimer.c:set_cpu_itimer
  - kernel/time/itimer.c:do_getitimer
  - kernel/time/itimer.c:get_cpu_itimer
  - kernel/time/itimer.c:get_cpu_itimer
  - kernel/time/itimer.c:itimer_get_remtime
  - kernel/time/itimer.c:itimer_get_remtime
  - drivers/input/evdev.c:evdev_pass_values
  - drivers/input/evdev.c:__evdev_queue_syn_dropped
  - net/socket.c:__sock_recv_timestamp
  - net/core/sock.c:sock_get_timestamp
  - net/core/sock.c:sock_get_timestamp
  - net/compat.c:compat_sock_get_timestamp
  - net/compat.c:compat_sock_get_timestamp
```
**Symbols:**

```
ffffffff81105b40-ffffffff81105bc4: ns_to_timeval (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct timeval ns_to_timeval(const s64 nsec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81110d90)
Location: kernel/time/time.c:479
Inline: False
Direct callers:
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:set_cpu_itimer
  - kernel/time/itimer.c:set_cpu_itimer
  - kernel/time/itimer.c:do_getitimer
  - kernel/time/itimer.c:get_cpu_itimer
  - kernel/time/itimer.c:get_cpu_itimer
  - kernel/time/itimer.c:itimer_get_remtime
  - kernel/time/itimer.c:itimer_get_remtime
  - net/socket.c:__sock_recv_timestamp
  - net/core/sock.c:sock_get_timestamp
  - net/core/sock.c:sock_get_timestamp
  - net/compat.c:compat_sock_get_timestamp
  - net/compat.c:compat_sock_get_timestamp
```
**Symbols:**

```
ffffffff81110d90-ffffffff81110e0e: ns_to_timeval (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct timeval ns_to_timeval(const s64 nsec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff8111c560)
Location: kernel/time/time.c:417
Inline: False
Direct callers:
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:set_cpu_itimer
  - kernel/time/itimer.c:set_cpu_itimer
  - kernel/time/itimer.c:do_getitimer
  - kernel/time/itimer.c:get_cpu_itimer
  - kernel/time/itimer.c:get_cpu_itimer
  - kernel/time/itimer.c:itimer_get_remtime
  - kernel/time/itimer.c:itimer_get_remtime
  - net/socket.c:__sock_recv_timestamp
  - net/core/sock.c:sock_get_timestamp
  - net/core/sock.c:sock_get_timestamp
```
**Symbols:**

```
ffffffff8111c560-ffffffff8111c5d7: ns_to_timeval (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct timeval ns_to_timeval(const s64 nsec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81126e90)
Location: kernel/time/time.c:485
Inline: False
Direct callers:
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:set_cpu_itimer
  - kernel/time/itimer.c:set_cpu_itimer
  - kernel/time/itimer.c:do_getitimer
  - kernel/time/itimer.c:get_cpu_itimer
  - kernel/time/itimer.c:get_cpu_itimer
  - kernel/time/itimer.c:itimer_get_remtime
  - kernel/time/itimer.c:itimer_get_remtime
```
**Symbols:**

```
ffffffff81126e90-ffffffff81126f0b: ns_to_timeval (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct timeval ns_to_timeval(const s64 nsec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81132e30)
Location: kernel/time/time.c:485
Inline: False
Direct callers:
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:set_cpu_itimer
  - kernel/time/itimer.c:set_cpu_itimer
  - kernel/time/itimer.c:do_getitimer
  - kernel/time/itimer.c:get_cpu_itimer
  - kernel/time/itimer.c:get_cpu_itimer
  - kernel/time/itimer.c:itimer_get_remtime
  - kernel/time/itimer.c:itimer_get_remtime
```
**Symbols:**

```
ffffffff81132e30-ffffffff81132eab: ns_to_timeval (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
struct timeval ns_to_timeval(const s64 nsec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffff80001019a138)
Location: kernel/time/time.c:485
Inline: False
Direct callers:
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:set_cpu_itimer
  - kernel/time/itimer.c:set_cpu_itimer
  - kernel/time/itimer.c:do_getitimer
  - kernel/time/itimer.c:get_cpu_itimer
  - kernel/time/itimer.c:get_cpu_itimer
  - kernel/time/itimer.c:itimer_get_remtime
  - kernel/time/itimer.c:itimer_get_remtime
```
**Symbols:**

```
ffff80001019a138-ffff80001019a1cc: ns_to_timeval (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct timeval ns_to_timeval(const s64 nsec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (c03e4a3c)
Location: kernel/time/time.c:485
Inline: False
Direct callers:
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:set_cpu_itimer
  - kernel/time/itimer.c:set_cpu_itimer
  - kernel/time/itimer.c:do_getitimer
  - kernel/time/itimer.c:get_cpu_itimer
  - kernel/time/itimer.c:get_cpu_itimer
  - kernel/time/itimer.c:itimer_get_remtime
  - fs/binfmt_elf_fdpic.c:fill_prstatus
  - fs/binfmt_elf_fdpic.c:fill_prstatus
  - fs/binfmt_elf_fdpic.c:fill_prstatus
  - fs/binfmt_elf_fdpic.c:fill_prstatus
  - fs/binfmt_elf_fdpic.c:fill_prstatus
```
**Symbols:**

```
c03e4a3c-c03e4ad4: ns_to_timeval (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct timeval ns_to_timeval(const s64 nsec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (c0000000001faac0)
Location: kernel/time/time.c:485
Inline: False
Direct callers:
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:set_cpu_itimer
  - kernel/time/itimer.c:set_cpu_itimer
  - kernel/time/itimer.c:do_getitimer
  - kernel/time/itimer.c:get_cpu_itimer
  - kernel/time/itimer.c:get_cpu_itimer
  - kernel/time/itimer.c:itimer_get_remtime
  - kernel/time/itimer.c:itimer_get_remtime
  - kernel/time/itimer.c:itimer_get_remtime
```
**Symbols:**

```
c0000000001faac0-c0000000001fab54: ns_to_timeval (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct timeval ns_to_timeval(const s64 nsec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffe00012a872)
Location: kernel/time/time.c:485
Inline: False
Direct callers:
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:set_cpu_itimer
  - kernel/time/itimer.c:set_cpu_itimer
  - kernel/time/itimer.c:do_getitimer
  - kernel/time/itimer.c:get_cpu_itimer
  - kernel/time/itimer.c:get_cpu_itimer
  - kernel/time/itimer.c:itimer_get_remtime
```
**Symbols:**

```
ffffffe00012a872-ffffffe00012a8be: ns_to_timeval (STB_GLOBAL)
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
struct timeval ns_to_timeval(const s64 nsec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff8112b5e0)
Location: kernel/time/time.c:485
Inline: False
Direct callers:
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:set_cpu_itimer
  - kernel/time/itimer.c:set_cpu_itimer
  - kernel/time/itimer.c:do_getitimer
  - kernel/time/itimer.c:get_cpu_itimer
  - kernel/time/itimer.c:get_cpu_itimer
  - kernel/time/itimer.c:itimer_get_remtime
  - kernel/time/itimer.c:itimer_get_remtime
```
**Symbols:**

```
ffffffff8112b5e0-ffffffff8112b65b: ns_to_timeval (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct timeval ns_to_timeval(const s64 nsec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff8111de50)
Location: kernel/time/time.c:485
Inline: False
Direct callers:
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:set_cpu_itimer
  - kernel/time/itimer.c:set_cpu_itimer
  - kernel/time/itimer.c:do_getitimer
  - kernel/time/itimer.c:get_cpu_itimer
  - kernel/time/itimer.c:get_cpu_itimer
  - kernel/time/itimer.c:itimer_get_remtime
  - kernel/time/itimer.c:itimer_get_remtime
```
**Symbols:**

```
ffffffff8111de50-ffffffff8111decb: ns_to_timeval (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct timeval ns_to_timeval(const s64 nsec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81129300)
Location: kernel/time/time.c:485
Inline: False
Direct callers:
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:set_cpu_itimer
  - kernel/time/itimer.c:set_cpu_itimer
  - kernel/time/itimer.c:do_getitimer
  - kernel/time/itimer.c:get_cpu_itimer
  - kernel/time/itimer.c:get_cpu_itimer
  - kernel/time/itimer.c:itimer_get_remtime
  - kernel/time/itimer.c:itimer_get_remtime
```
**Symbols:**

```
ffffffff81129300-ffffffff8112937b: ns_to_timeval (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct timeval ns_to_timeval(const s64 nsec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81135950)
Location: kernel/time/time.c:485
Inline: False
Direct callers:
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:set_cpu_itimer
  - kernel/time/itimer.c:set_cpu_itimer
  - kernel/time/itimer.c:do_getitimer
  - kernel/time/itimer.c:get_cpu_itimer
  - kernel/time/itimer.c:get_cpu_itimer
  - kernel/time/itimer.c:itimer_get_remtime
  - kernel/time/itimer.c:itimer_get_remtime
```
**Symbols:**

```
ffffffff81135950-ffffffff811359cb: ns_to_timeval (STB_GLOBAL)
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
