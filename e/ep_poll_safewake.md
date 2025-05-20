# Function: <code>ep_poll_safewake</code>

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
In fs/eventpoll.c (ffffffff81254ddf)
Location: fs/eventpoll.c:506
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_free
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:ep_scan_ready_list
  - fs/eventpoll.c:SyS_epoll_ctl
  - fs/eventpoll.c:SyS_epoll_ctl
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
In fs/eventpoll.c (ffffffff8127e9ed)
Location: fs/eventpoll.c:511
Inline: True
Inline callers:
  - fs/eventpoll.c:SyS_epoll_ctl
  - fs/eventpoll.c:SyS_epoll_ctl
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:ep_free
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
In fs/eventpoll.c (ffffffff8129257d)
Location: fs/eventpoll.c:511
Inline: True
Inline callers:
  - fs/eventpoll.c:SyS_epoll_ctl
  - fs/eventpoll.c:SyS_epoll_ctl
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:ep_free
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
In fs/eventpoll.c (ffffffff8129f9f1)
Location: fs/eventpoll.c:588
Inline: True
Inline callers:
  - fs/eventpoll.c:SyS_epoll_ctl
  - fs/eventpoll.c:SyS_epoll_ctl
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:ep_free
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
In fs/eventpoll.c (ffffffff812c2e32)
Location: fs/eventpoll.c:575
Inline: True
Inline callers:
  - fs/eventpoll.c:SyS_epoll_ctl
  - fs/eventpoll.c:SyS_epoll_ctl
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:ep_free
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
In fs/eventpoll.c (ffffffff812ead0e)
Location: fs/eventpoll.c:576
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_modify
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:ep_free
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
In fs/eventpoll.c (ffffffff812ffb37)
Location: fs/eventpoll.c:584
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_modify
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:ep_free
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
In fs/eventpoll.c (ffffffff8132182a)
Location: fs/eventpoll.c:580
Inline: True
Inline callers:
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:ep_free
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
In fs/eventpoll.c (ffffffff8133561a)
Location: fs/eventpoll.c:580
Inline: True
Inline callers:
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:ep_free
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
In fs/eventpoll.c (ffffffff8136de67)
Location: fs/eventpoll.c:589
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_modify
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:ep_free
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
In fs/eventpoll.c (ffffffff8137c822)
Location: fs/eventpoll.c:525
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_modify
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:ep_free
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
In fs/eventpoll.c (ffffffff813839c9)
Location: fs/eventpoll.c:525
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_ctl
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:ep_free
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
In fs/eventpoll.c (ffffffff813d0c69)
Location: fs/eventpoll.c:525
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_ctl
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:ep_free
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
In fs/eventpoll.c (ffffffff81459f25)
Location: fs/eventpoll.c:532
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_ctl
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:ep_free
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
In fs/eventpoll.c (ffffffff814e9395)
Location: fs/eventpoll.c:533
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_ctl
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:ep_free
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
In fs/eventpoll.c (ffffffff81520140)
Location: fs/eventpoll.c:538
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_ctl
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:ep_clear_and_put
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
In fs/eventpoll.c (ffffffff81554750)
Location: fs/eventpoll.c:537
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_ctl
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:ep_clear_and_put
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
In fs/eventpoll.c (ffff8000103f2324)
Location: fs/eventpoll.c:580
Inline: True
Inline callers:
  - fs/eventpoll.c:__do_sys_epoll_ctl
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:ep_free
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
In fs/eventpoll.c (c05c7e44)
Location: fs/eventpoll.c:580
Inline: True
Inline callers:
  - fs/eventpoll.c:__do_sys_epoll_ctl
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:ep_free
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
In fs/eventpoll.c (c0000000004fa71c)
Location: fs/eventpoll.c:580
Inline: True
Inline callers:
  - fs/eventpoll.c:__se_sys_epoll_ctl
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:ep_free
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
In fs/eventpoll.c (ffffffe0002a4afa)
Location: fs/eventpoll.c:580
Inline: True
Inline callers:
  - fs/eventpoll.c:__se_sys_epoll_ctl
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:ep_free
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
In fs/eventpoll.c (ffffffff8132dbfa)
Location: fs/eventpoll.c:580
Inline: True
Inline callers:
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:ep_free
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
In fs/eventpoll.c (ffffffff8131e012)
Location: fs/eventpoll.c:580
Inline: True
Inline callers:
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:ep_free
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
In fs/eventpoll.c (ffffffff8132b6ca)
Location: fs/eventpoll.c:580
Inline: True
Inline callers:
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:ep_free
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
In fs/eventpoll.c (ffffffff8133c900)
Location: fs/eventpoll.c:580
Inline: True
Inline callers:
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:ep_free
```
</details>
</li>
</ul>

## Differences
