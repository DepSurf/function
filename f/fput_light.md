# Function: <code>fput_light</code>

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
In net/socket.c (ffffffff816fd5cf)
Location: include/linux/file.h:24
Inline: True
Inline callers:
  - net/socket.c:SYSC_accept4
  - net/socket.c:SYSC_getsockname
  - net/socket.c:SYSC_getpeername
  - net/socket.c:SYSC_getpeername
  - net/socket.c:SYSC_recvfrom
  - net/socket.c:SYSC_bind
  - net/socket.c:SYSC_connect
  - net/socket.c:SYSC_sendto
  - net/socket.c:__sys_sendmsg
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:__sys_recvmsg
  - net/socket.c:__sys_recvmmsg
  - net/socket.c:SyS_socketcall
  - net/socket.c:SyS_socketcall
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
In net/socket.c (ffffffff817667b4)
Location: include/linux/file.h:24
Inline: True
Inline callers:
  - net/socket.c:SyS_socketcall
  - net/socket.c:SyS_socketcall
  - net/socket.c:SyS_socketcall
  - net/socket.c:__sys_recvmmsg
  - net/socket.c:__sys_recvmsg
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:__sys_sendmsg
  - net/socket.c:SYSC_recvfrom
  - net/socket.c:SYSC_sendto
  - net/socket.c:SYSC_getpeername
  - net/socket.c:SYSC_getpeername
  - net/socket.c:SYSC_getsockname
  - net/socket.c:SYSC_connect
  - net/socket.c:SYSC_accept4
  - net/socket.c:SYSC_bind
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
In net/socket.c (ffffffff81793834)
Location: include/linux/file.h:24
Inline: True
Inline callers:
  - net/socket.c:SyS_socketcall
  - net/socket.c:SyS_socketcall
  - net/socket.c:SyS_socketcall
  - net/socket.c:__sys_recvmmsg
  - net/socket.c:__sys_recvmsg
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:__sys_sendmsg
  - net/socket.c:SYSC_recvfrom
  - net/socket.c:SYSC_sendto
  - net/socket.c:SYSC_getpeername
  - net/socket.c:SYSC_getpeername
  - net/socket.c:SYSC_getsockname
  - net/socket.c:SYSC_connect
  - net/socket.c:SYSC_accept4
  - net/socket.c:SYSC_bind
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
In net/socket.c (ffffffff817b1cb0)
Location: include/linux/file.h:24
Inline: True
Inline callers:
  - net/socket.c:SyS_socketcall
  - net/socket.c:SyS_socketcall
  - net/socket.c:__sys_recvmmsg
  - net/socket.c:__sys_recvmsg
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:__sys_sendmsg
  - net/socket.c:SYSC_recvfrom
  - net/socket.c:SYSC_sendto
  - net/socket.c:SYSC_getpeername
  - net/socket.c:SYSC_getpeername
  - net/socket.c:SYSC_getsockname
  - net/socket.c:SYSC_connect
  - net/socket.c:SYSC_accept4
  - net/socket.c:SYSC_bind
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
In net/socket.c (ffffffff81829e47)
Location: include/linux/file.h:25
Inline: True
Inline callers:
  - net/socket.c:SyS_socketcall
  - net/socket.c:SyS_socketcall
  - net/socket.c:__sys_recvmmsg
  - net/socket.c:__sys_recvmsg
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:__sys_sendmsg
  - net/socket.c:SYSC_recvfrom
  - net/socket.c:SYSC_sendto
  - net/socket.c:SYSC_getpeername
  - net/socket.c:SYSC_getpeername
  - net/socket.c:SYSC_getsockname
  - net/socket.c:SYSC_connect
  - net/socket.c:SYSC_accept4
  - net/socket.c:SYSC_bind
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
In net/socket.c (ffffffff81873ce0)
Location: include/linux/file.h:25
Inline: True
Inline callers:
  - net/socket.c:__sys_recvmmsg
  - net/socket.c:__sys_recvmsg
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:__sys_sendmsg
  - net/socket.c:__sys_shutdown
  - net/socket.c:__sys_getsockopt
  - net/socket.c:__sys_setsockopt
  - net/socket.c:__sys_recvfrom
  - net/socket.c:__sys_sendto
  - net/socket.c:__sys_getpeername
  - net/socket.c:__sys_getpeername
  - net/socket.c:__sys_getsockname
  - net/socket.c:__sys_connect
  - net/socket.c:__sys_accept4
  - net/socket.c:__sys_listen
  - net/socket.c:__sys_bind
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
In net/socket.c (ffffffff81892ca2)
Location: include/linux/file.h:27
Inline: True
Inline callers:
  - net/socket.c:do_recvmmsg
  - net/socket.c:__sys_recvmsg
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:__sys_sendmsg
  - net/socket.c:__sys_shutdown
  - net/socket.c:__sys_getsockopt
  - net/socket.c:__sys_setsockopt
  - net/socket.c:__sys_recvfrom
  - net/socket.c:__sys_sendto
  - net/socket.c:__sys_getpeername
  - net/socket.c:__sys_getpeername
  - net/socket.c:__sys_getsockname
  - net/socket.c:__sys_connect
  - net/socket.c:__sys_accept4
  - net/socket.c:__sys_listen
  - net/socket.c:__sys_bind
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
In net/socket.c (ffffffff818dcf84)
Location: include/linux/file.h:28
Inline: True
Inline callers:
  - net/socket.c:do_recvmmsg
  - net/socket.c:__sys_recvmsg
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:__sys_sendmsg
  - net/socket.c:__sys_shutdown
  - net/socket.c:__sys_getsockopt
  - net/socket.c:__sys_setsockopt
  - net/socket.c:__sys_recvfrom
  - net/socket.c:__sys_sendto
  - net/socket.c:__sys_getpeername
  - net/socket.c:__sys_getpeername
  - net/socket.c:__sys_getsockname
  - net/socket.c:__sys_connect
  - net/socket.c:__sys_accept4
  - net/socket.c:__sys_listen
  - net/socket.c:__sys_bind
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
In net/socket.c (ffffffff8190dc93)
Location: include/linux/file.h:28
Inline: True
Inline callers:
  - net/socket.c:do_recvmmsg
  - net/socket.c:__sys_recvmsg
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:__sys_sendmsg
  - net/socket.c:__sys_shutdown
  - net/socket.c:__sys_getsockopt
  - net/socket.c:__sys_setsockopt
  - net/socket.c:__sys_recvfrom
  - net/socket.c:__sys_sendto
  - net/socket.c:__sys_getpeername
  - net/socket.c:__sys_getpeername
  - net/socket.c:__sys_getsockname
  - net/socket.c:__sys_connect
  - net/socket.c:__sys_accept4
  - net/socket.c:__sys_listen
  - net/socket.c:__sys_bind
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819e2213)
Location: include/linux/file.h:29
Inline: True
Inline callers:
  - net/socket.c:do_recvmmsg
  - net/socket.c:__sys_recvmsg
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:__sys_sendmsg
  - net/socket.c:__sys_shutdown
  - net/socket.c:__sys_getsockopt
  - net/socket.c:__sys_setsockopt
  - net/socket.c:__sys_recvfrom
  - net/socket.c:__sys_sendto
  - net/socket.c:__sys_getpeername
  - net/socket.c:__sys_getpeername
  - net/socket.c:__sys_getsockname
  - net/socket.c:__sys_listen
  - net/socket.c:__sys_bind
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819e1eb2)
Location: include/linux/file.h:30
Inline: True
Inline callers:
  - net/socket.c:do_recvmmsg
  - net/socket.c:__sys_recvmsg
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:__sys_sendmsg
  - net/socket.c:__sys_shutdown
  - net/socket.c:__sys_getsockopt
  - net/socket.c:__sys_setsockopt
  - net/socket.c:__sys_recvfrom
  - net/socket.c:__sys_sendto
  - net/socket.c:__sys_getpeername
  - net/socket.c:__sys_getpeername
  - net/socket.c:__sys_getsockname
  - net/socket.c:__sys_listen
  - net/socket.c:__sys_bind
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
In net/socket.c (ffffffff819c7f12)
Location: include/linux/file.h:30
Inline: True
Inline callers:
  - net/socket.c:do_recvmmsg
  - net/socket.c:__sys_recvmsg
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:__sys_sendmsg
  - net/socket.c:__sys_shutdown
  - net/socket.c:__sys_getsockopt
  - net/socket.c:__sys_setsockopt
  - net/socket.c:__sys_recvfrom
  - net/socket.c:__sys_sendto
  - net/socket.c:__sys_getpeername
  - net/socket.c:__sys_getpeername
  - net/socket.c:__sys_getsockname
  - net/socket.c:__sys_listen
  - net/socket.c:__sys_bind
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
In net/socket.c (ffffffff81a77262)
Location: include/linux/file.h:30
Inline: True
Inline callers:
  - net/socket.c:do_recvmmsg
  - net/socket.c:__sys_recvmsg
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:__sys_sendmsg
  - net/socket.c:__sys_shutdown
  - net/socket.c:__sys_getsockopt
  - net/socket.c:__sys_setsockopt
  - net/socket.c:__sys_recvfrom
  - net/socket.c:__sys_sendto
  - net/socket.c:__sys_getpeername
  - net/socket.c:__sys_getpeername
  - net/socket.c:__sys_getsockname
  - net/socket.c:__sys_listen
  - net/socket.c:__sys_bind
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
In net/socket.c (ffffffff81bea583)
Location: include/linux/file.h:29
Inline: True
Inline callers:
  - net/socket.c:do_recvmmsg
  - net/socket.c:__sys_recvmsg
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:__sys_sendmsg
  - net/socket.c:__sys_shutdown
  - net/socket.c:__sys_getsockopt
  - net/socket.c:__sys_setsockopt
  - net/socket.c:__sys_recvfrom
  - net/socket.c:__sys_sendto
  - net/socket.c:__sys_getpeername
  - net/socket.c:__sys_getsockname
  - net/socket.c:__sys_listen
  - net/socket.c:__sys_bind
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
In net/socket.c (ffffffff81d96e33)
Location: include/linux/file.h:29
Inline: True
Inline callers:
  - net/socket.c:do_recvmmsg
  - net/socket.c:__sys_recvmsg
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:__sys_sendmsg
  - net/socket.c:__sys_shutdown
  - net/socket.c:__sys_getsockopt
  - net/socket.c:__sys_setsockopt
  - net/socket.c:__sys_recvfrom
  - net/socket.c:__sys_sendto
  - net/socket.c:__sys_getpeername
  - net/socket.c:__sys_getsockname
  - net/socket.c:__sys_listen
  - net/socket.c:__sys_bind
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
In net/socket.c (ffffffff81e054a3)
Location: include/linux/file.h:30
Inline: True
Inline callers:
  - net/socket.c:do_recvmmsg
  - net/socket.c:__sys_recvmsg
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:__sys_sendmsg
  - net/socket.c:__sys_shutdown
  - net/socket.c:__sys_getsockopt
  - net/socket.c:__sys_setsockopt
  - net/socket.c:__sys_recvfrom
  - net/socket.c:__sys_sendto
  - net/socket.c:__sys_getpeername
  - net/socket.c:__sys_getsockname
  - net/socket.c:__sys_listen
  - net/socket.c:__sys_bind
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
In net/socket.c (ffffffff81ec1d63)
Location: include/linux/file.h:30
Inline: True
Inline callers:
  - net/socket.c:do_recvmmsg
  - net/socket.c:__sys_recvmsg
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:__sys_sendmsg
  - net/socket.c:__sys_shutdown
  - net/socket.c:__sys_getsockopt
  - net/socket.c:__sys_setsockopt
  - net/socket.c:__sys_recvfrom
  - net/socket.c:__sys_sendto
  - net/socket.c:__sys_getpeername
  - net/socket.c:__sys_getsockname
  - net/socket.c:__sys_listen
  - net/socket.c:__sys_bind
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
In net/socket.c (ffff800010ba4c40)
Location: include/linux/file.h:28
Inline: True
Inline callers:
  - net/socket.c:do_recvmmsg
  - net/socket.c:__sys_recvmsg
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:__sys_sendmsg
  - net/socket.c:__sys_shutdown
  - net/socket.c:__arm64_sys_getsockopt
  - net/socket.c:__arm64_sys_setsockopt
  - net/socket.c:__sys_recvfrom
  - net/socket.c:__sys_sendto
  - net/socket.c:__sys_getpeername
  - net/socket.c:__sys_getpeername
  - net/socket.c:__sys_getsockname
  - net/socket.c:__sys_connect
  - net/socket.c:__sys_accept4
  - net/socket.c:__sys_listen
  - net/socket.c:__sys_bind
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
In net/socket.c (c0cc5c4c)
Location: include/linux/file.h:28
Inline: True
Inline callers:
  - net/socket.c:do_recvmmsg
  - net/socket.c:__sys_recvmsg
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:__sys_sendmsg
  - net/socket.c:__sys_shutdown
  - net/socket.c:__se_sys_getsockopt
  - net/socket.c:__se_sys_setsockopt
  - net/socket.c:__sys_recvfrom
  - net/socket.c:__sys_sendto
  - net/socket.c:__sys_getpeername
  - net/socket.c:__sys_getpeername
  - net/socket.c:__sys_getsockname
  - net/socket.c:__sys_connect
  - net/socket.c:__sys_accept4
  - net/socket.c:__sys_listen
  - net/socket.c:__sys_bind
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
In net/socket.c (c000000000c785d4)
Location: include/linux/file.h:28
Inline: True
Inline callers:
  - net/socket.c:do_recvmmsg
  - net/socket.c:__sys_recvmsg
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:__sys_sendmsg
  - net/socket.c:__sys_shutdown
  - net/socket.c:__sys_getsockopt
  - net/socket.c:__sys_setsockopt
  - net/socket.c:__sys_recvfrom
  - net/socket.c:__sys_sendto
  - net/socket.c:__sys_getpeername
  - net/socket.c:__sys_getpeername
  - net/socket.c:__sys_getsockname
  - net/socket.c:__sys_connect
  - net/socket.c:__sys_accept4
  - net/socket.c:__sys_listen
  - net/socket.c:__sys_bind
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
In net/socket.c (ffffffe00073a9bc)
Location: include/linux/file.h:28
Inline: True
Inline callers:
  - net/socket.c:do_recvmmsg
  - net/socket.c:__sys_recvmsg
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:__sys_sendmsg
  - net/socket.c:__sys_shutdown
  - net/socket.c:__se_sys_getsockopt
  - net/socket.c:__se_sys_setsockopt
  - net/socket.c:__sys_recvfrom
  - net/socket.c:__sys_sendto
  - net/socket.c:__sys_getpeername
  - net/socket.c:__sys_getpeername
  - net/socket.c:__sys_getsockname
  - net/socket.c:__sys_connect
  - net/socket.c:__sys_accept4
  - net/socket.c:__sys_listen
  - net/socket.c:__sys_bind
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
In net/socket.c (ffffffff818adc93)
Location: include/linux/file.h:28
Inline: True
Inline callers:
  - net/socket.c:do_recvmmsg
  - net/socket.c:__sys_recvmsg
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:__sys_sendmsg
  - net/socket.c:__sys_shutdown
  - net/socket.c:__sys_getsockopt
  - net/socket.c:__sys_setsockopt
  - net/socket.c:__sys_recvfrom
  - net/socket.c:__sys_sendto
  - net/socket.c:__sys_getpeername
  - net/socket.c:__sys_getpeername
  - net/socket.c:__sys_getsockname
  - net/socket.c:__sys_connect
  - net/socket.c:__sys_accept4
  - net/socket.c:__sys_listen
  - net/socket.c:__sys_bind
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
In net/socket.c (ffffffff81867be3)
Location: include/linux/file.h:28
Inline: True
Inline callers:
  - net/socket.c:do_recvmmsg
  - net/socket.c:__sys_recvmsg
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:__sys_sendmsg
  - net/socket.c:__sys_shutdown
  - net/socket.c:__sys_getsockopt
  - net/socket.c:__sys_setsockopt
  - net/socket.c:__sys_recvfrom
  - net/socket.c:__sys_sendto
  - net/socket.c:__sys_getpeername
  - net/socket.c:__sys_getpeername
  - net/socket.c:__sys_getsockname
  - net/socket.c:__sys_connect
  - net/socket.c:__sys_accept4
  - net/socket.c:__sys_listen
  - net/socket.c:__sys_bind
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
In net/socket.c (ffffffff818fec93)
Location: include/linux/file.h:28
Inline: True
Inline callers:
  - net/socket.c:do_recvmmsg
  - net/socket.c:__sys_recvmsg
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:__sys_sendmsg
  - net/socket.c:__sys_shutdown
  - net/socket.c:__sys_getsockopt
  - net/socket.c:__sys_setsockopt
  - net/socket.c:__sys_recvfrom
  - net/socket.c:__sys_sendto
  - net/socket.c:__sys_getpeername
  - net/socket.c:__sys_getpeername
  - net/socket.c:__sys_getsockname
  - net/socket.c:__sys_connect
  - net/socket.c:__sys_accept4
  - net/socket.c:__sys_listen
  - net/socket.c:__sys_bind
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
In net/socket.c (ffffffff8191fcfb)
Location: include/linux/file.h:28
Inline: True
Inline callers:
  - net/socket.c:do_recvmmsg
  - net/socket.c:__sys_recvmsg
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:__sys_sendmsg
  - net/socket.c:__sys_shutdown
  - net/socket.c:__sys_getsockopt
  - net/socket.c:__sys_setsockopt
  - net/socket.c:__sys_recvfrom
  - net/socket.c:__sys_sendto
  - net/socket.c:__sys_getpeername
  - net/socket.c:__sys_getpeername
  - net/socket.c:__sys_getsockname
  - net/socket.c:__sys_connect
  - net/socket.c:__sys_accept4
  - net/socket.c:__sys_listen
  - net/socket.c:__sys_bind
```
</details>
</li>
</ul>

## Differences
