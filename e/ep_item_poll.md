# Function: <code>ep_item_poll</code>

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
In fs/eventpoll.c (ffffffff812546f4)
Location: fs/eventpoll.c:796
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_read_events_proc
  - fs/eventpoll.c:ep_send_events_proc
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
In fs/eventpoll.c (ffffffff8127e86f)
Location: fs/eventpoll.c:801
Inline: True
Inline callers:
  - fs/eventpoll.c:SyS_epoll_ctl
  - fs/eventpoll.c:SyS_epoll_ctl
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_read_events_proc
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
In fs/eventpoll.c (ffffffff812923ff)
Location: fs/eventpoll.c:801
Inline: True
Inline callers:
  - fs/eventpoll.c:SyS_epoll_ctl
  - fs/eventpoll.c:SyS_epoll_ctl
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_read_events_proc
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
In fs/eventpoll.c (ffffffff8129f512)
Location: fs/eventpoll.c:883
Inline: True
Inline callers:
  - fs/eventpoll.c:SyS_epoll_ctl
  - fs/eventpoll.c:SyS_epoll_ctl
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_read_events_proc
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/eventpoll.c (ffffffff812c1a40)
Location: fs/eventpoll.c:877
Inline: True
Direct callers:
  - fs/eventpoll.c:SyS_epoll_ctl
  - fs/eventpoll.c:SyS_epoll_ctl
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_read_events_proc
```
**Symbols:**

```
ffffffff812c1a40-ffffffff812c1ae0: ep_item_poll.isra.10 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/eventpoll.c (ffffffff812eaab0)
Location: fs/eventpoll.c:879
Inline: True
Direct callers:
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_modify
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_read_events_proc
```
**Symbols:**

```
ffffffff812eaab0-ffffffff812eab6a: ep_item_poll.isra.17 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/eventpoll.c (ffffffff812ff660)
Location: fs/eventpoll.c:884
Inline: True
Direct callers:
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_modify
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_read_events_proc
```
**Symbols:**

```
ffffffff812ff660-ffffffff812ff71a: ep_item_poll.isra.20 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/eventpoll.c (ffffffff81320810)
Location: fs/eventpoll.c:884
Inline: True
Direct callers:
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_read_events_proc
```
**Symbols:**

```
ffffffff81320810-ffffffff813208c6: ep_item_poll.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/eventpoll.c (ffffffff813335c0)
Location: fs/eventpoll.c:884
Inline: True
Direct callers:
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_read_events_proc
```
**Symbols:**

```
ffffffff813335c0-ffffffff81333676: ep_item_poll.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
__poll_t ep_item_poll(const struct epitem *epi, poll_table *pt, int depth);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff8136d850)
Location: fs/eventpoll.c:877
Inline: False
Direct callers:
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_modify
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_read_events_proc
```
**Symbols:**

```
ffffffff8136d850-ffffffff8136d8fa: ep_item_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/eventpoll.c (ffffffff8137ad10)
Location: fs/eventpoll.c:832
Inline: True
Direct callers:
  - fs/eventpoll.c:ep_send_events
  - fs/eventpoll.c:ep_modify
  - fs/eventpoll.c:ep_insert
```
**Symbols:**

```
ffffffff8137ad10-ffffffff8137ad5f: ep_item_poll.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/eventpoll.c (ffffffff81381880)
Location: fs/eventpoll.c:838
Inline: True
Direct callers:
  - fs/eventpoll.c:do_epoll_ctl
  - fs/eventpoll.c:ep_send_events
  - fs/eventpoll.c:ep_insert
```
**Symbols:**

```
ffffffff81381880-ffffffff813818cf: ep_item_poll.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/eventpoll.c (ffffffff813ceac0)
Location: fs/eventpoll.c:838
Inline: True
Direct callers:
  - fs/eventpoll.c:do_epoll_ctl
  - fs/eventpoll.c:ep_send_events
  - fs/eventpoll.c:ep_insert
```
**Symbols:**

```
ffffffff813ceac0-ffffffff813ceb0f: ep_item_poll.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/eventpoll.c (ffffffff81457d20)
Location: fs/eventpoll.c:845
Inline: True
Direct callers:
  - fs/eventpoll.c:do_epoll_ctl
  - fs/eventpoll.c:ep_send_events
  - fs/eventpoll.c:ep_insert
```
**Symbols:**

```
ffffffff81457d20-ffffffff81457d7f: ep_item_poll.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/eventpoll.c (ffffffff814e7060)
Location: fs/eventpoll.c:847
Inline: True
Direct callers:
  - fs/eventpoll.c:do_epoll_ctl
  - fs/eventpoll.c:ep_send_events
  - fs/eventpoll.c:ep_insert
```
**Symbols:**

```
ffffffff814e7060-ffffffff814e70bf: ep_item_poll.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/eventpoll.c (ffffffff8151d8a0)
Location: fs/eventpoll.c:884
Inline: True
Direct callers:
  - fs/eventpoll.c:do_epoll_ctl
  - fs/eventpoll.c:ep_send_events
  - fs/eventpoll.c:ep_insert
```
**Symbols:**

```
ffffffff8151d8a0-ffffffff8151d902: ep_item_poll.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/eventpoll.c (ffffffff81551e80)
Location: fs/eventpoll.c:883
Inline: True
Direct callers:
  - fs/eventpoll.c:do_epoll_ctl
  - fs/eventpoll.c:ep_send_events
  - fs/eventpoll.c:ep_insert
```
**Symbols:**

```
ffffffff81551e80-ffffffff81551ee2: ep_item_poll.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/eventpoll.c (ffff8000103f0a08)
Location: fs/eventpoll.c:884
Inline: True
Direct callers:
  - fs/eventpoll.c:__do_sys_epoll_ctl
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_read_events_proc
```
**Symbols:**

```
ffff8000103f0a08-ffff8000103f0ae4: ep_item_poll.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
__poll_t ep_item_poll(const struct epitem *epi, poll_table *pt, int depth);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (c05c68e0)
Location: fs/eventpoll.c:884
Inline: False
Direct callers:
  - fs/eventpoll.c:__do_sys_epoll_ctl
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_read_events_proc
```
**Symbols:**

```
c05c68e0-c05c69bc: ep_item_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/eventpoll.c (c0000000004f87c0)
Location: fs/eventpoll.c:884
Inline: True
Direct callers:
  - fs/eventpoll.c:__se_sys_epoll_ctl
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_read_events_proc
```
**Symbols:**

```
c0000000004f87c0-c0000000004f8908: ep_item_poll.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/eventpoll.c (ffffffe0002a3520)
Location: fs/eventpoll.c:884
Inline: True
Direct callers:
  - fs/eventpoll.c:__se_sys_epoll_ctl
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_read_events_proc
```
**Symbols:**

```
ffffffe0002a3520-ffffffe0002a35d0: ep_item_poll.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/eventpoll.c (ffffffff8132bba0)
Location: fs/eventpoll.c:884
Inline: True
Direct callers:
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_read_events_proc
```
**Symbols:**

```
ffffffff8132bba0-ffffffff8132bc56: ep_item_poll.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/eventpoll.c (ffffffff8131c300)
Location: fs/eventpoll.c:884
Inline: True
Direct callers:
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_read_events_proc
```
**Symbols:**

```
ffffffff8131c300-ffffffff8131c3b6: ep_item_poll.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/eventpoll.c (ffffffff81329670)
Location: fs/eventpoll.c:884
Inline: True
Direct callers:
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_read_events_proc
```
**Symbols:**

```
ffffffff81329670-ffffffff81329726: ep_item_poll.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/eventpoll.c (ffffffff8133afd0)
Location: fs/eventpoll.c:884
Inline: True
Direct callers:
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_read_events_proc
```
**Symbols:**

```
ffffffff8133afd0-ffffffff8133b086: ep_item_poll.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
<b>Arch</b>
<ul>
</ul>
