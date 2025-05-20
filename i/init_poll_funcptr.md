# Function: <code>init_poll_funcptr</code>

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
In mm/memcontrol.c (ffffffff811fc34c)
Location: include/linux/poll.h:69
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/select.c (ffffffff81220a46)
Location: include/linux/poll.h:69
Inline: True
Inline callers:
  - fs/select.c:do_select
  - fs/select.c:do_sys_poll
```
```
In fs/eventpoll.c (ffffffff81254687)
Location: include/linux/poll.h:69
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
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8121f67c)
Location: include/linux/poll.h:69
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/select.c (ffffffff81249c34)
Location: include/linux/poll.h:69
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffffffff8127e81a)
Location: include/linux/poll.h:69
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
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81231cec)
Location: include/linux/poll.h:69
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/select.c (ffffffff8125cc04)
Location: include/linux/poll.h:69
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffffffff812923aa)
Location: include/linux/poll.h:69
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
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8123de5a)
Location: include/linux/poll.h:69
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/select.c (ffffffff812697d7)
Location: include/linux/poll.h:69
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffffffff8129f474)
Location: include/linux/poll.h:69
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
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8125d9ea)
Location: include/linux/poll.h:70
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/select.c (ffffffff8128c087)
Location: include/linux/poll.h:70
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffffffff812c28eb)
Location: include/linux/poll.h:70
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
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812813a4)
Location: include/linux/poll.h:71
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/select.c (ffffffff812b2858)
Location: include/linux/poll.h:71
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffffffff812eadce)
Location: include/linux/poll.h:71
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_modify
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_read_events_proc
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
In mm/memcontrol.c (ffffffff81295dd4)
Location: include/linux/poll.h:71
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/select.c (ffffffff812c7968)
Location: include/linux/poll.h:71
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffffffff812ff824)
Location: include/linux/poll.h:71
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_modify
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_read_events_proc
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
In mm/memcontrol.c (ffffffff812b1e17)
Location: include/linux/poll.h:75
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/select.c (ffffffff812e45bc)
Location: include/linux/poll.h:75
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffffffff813215a8)
Location: include/linux/poll.h:75
Inline: True
Inline callers:
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_read_events_proc
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
In mm/memcontrol.c (ffffffff812c37b7)
Location: include/linux/poll.h:75
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/select.c (ffffffff812f5f83)
Location: include/linux/poll.h:75
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffffffff81335398)
Location: include/linux/poll.h:75
Inline: True
Inline callers:
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_read_events_proc
```
```
In drivers/vfio/virqfd.c (ffffffff817d2926)
Location: include/linux/poll.h:75
Inline: True
Inline callers:
  - drivers/vfio/virqfd.c:vfio_virqfd_enable
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
In mm/memcontrol.c (ffffffff812f9437)
Location: include/linux/poll.h:75
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/select.c (ffffffff8132f098)
Location: include/linux/poll.h:75
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffffffff8136da01)
Location: include/linux/poll.h:75
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_modify
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_read_events_proc
```
```
In drivers/vfio/virqfd.c (ffffffff8189da86)
Location: include/linux/poll.h:75
Inline: True
Inline callers:
  - drivers/vfio/virqfd.c:vfio_virqfd_enable
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
In mm/memcontrol.c (ffffffff81305ad7)
Location: include/linux/poll.h:75
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/select.c (ffffffff8133a984)
Location: include/linux/poll.h:75
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffffffff8137b660)
Location: include/linux/poll.h:75
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_send_events
  - fs/eventpoll.c:ep_modify
  - fs/eventpoll.c:ep_insert
```
```
In drivers/vfio/virqfd.c (ffffffff818ac6a6)
Location: include/linux/poll.h:75
Inline: True
Inline callers:
  - drivers/vfio/virqfd.c:vfio_virqfd_enable
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
In mm/memcontrol.c (ffffffff8130af77)
Location: include/linux/poll.h:75
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/select.c (ffffffff81340e92)
Location: include/linux/poll.h:75
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffffffff81383940)
Location: include/linux/poll.h:75
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_ctl
  - fs/eventpoll.c:ep_send_events
  - fs/eventpoll.c:ep_insert
```
```
In drivers/vfio/virqfd.c (ffffffff8188f7c3)
Location: include/linux/poll.h:75
Inline: True
Inline callers:
  - drivers/vfio/virqfd.c:vfio_virqfd_enable
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
In mm/memcontrol.c (ffffffff813557f7)
Location: include/linux/poll.h:75
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/select.c (ffffffff8138e852)
Location: include/linux/poll.h:75
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffffffff813d0be0)
Location: include/linux/poll.h:75
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_ctl
  - fs/eventpoll.c:ep_send_events
  - fs/eventpoll.c:ep_insert
```
```
In drivers/vfio/virqfd.c (ffffffff819230c3)
Location: include/linux/poll.h:75
Inline: True
Inline callers:
  - drivers/vfio/virqfd.c:vfio_virqfd_enable
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
In mm/memcontrol.c (ffffffff813ce17d)
Location: include/linux/poll.h:73
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/select.c (ffffffff8140fb3d)
Location: include/linux/poll.h:73
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffffffff81459dba)
Location: include/linux/poll.h:73
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_ctl
  - fs/eventpoll.c:ep_send_events
  - fs/eventpoll.c:ep_insert
```
```
In drivers/vfio/virqfd.c (ffffffff81a78ae4)
Location: include/linux/poll.h:73
Inline: True
Inline callers:
  - drivers/vfio/virqfd.c:vfio_virqfd_enable
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
In mm/memcontrol.c (ffffffff814536ad)
Location: include/linux/poll.h:73
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/select.c (ffffffff8149a77d)
Location: include/linux/poll.h:73
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffffffff814e922a)
Location: include/linux/poll.h:73
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_ctl
  - fs/eventpoll.c:ep_send_events
  - fs/eventpoll.c:ep_insert
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
In mm/memcontrol.c (ffffffff814894bd)
Location: include/linux/poll.h:73
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/select.c (ffffffff814cf82d)
Location: include/linux/poll.h:73
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffffffff8151ffd4)
Location: include/linux/poll.h:73
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_ctl
  - fs/eventpoll.c:ep_send_events
  - fs/eventpoll.c:ep_insert
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
In mm/memcontrol.c (ffffffff814b891c)
Location: include/linux/poll.h:73
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/select.c (ffffffff8150216d)
Location: include/linux/poll.h:73
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffffffff815545e4)
Location: include/linux/poll.h:73
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_ctl
  - fs/eventpoll.c:ep_send_events
  - fs/eventpoll.c:ep_insert
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
In virt/kvm/eventfd.c (ffff8000100c126c)
Location: include/linux/poll.h:75
Inline: True
Inline callers:
  - virt/kvm/eventfd.c:kvm_irqfd_assign
```
```
In mm/memcontrol.c (ffff800010364e88)
Location: include/linux/poll.h:75
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/select.c (ffff8000103a3110)
Location: include/linux/poll.h:75
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffff8000103f2284)
Location: include/linux/poll.h:75
Inline: True
Inline callers:
  - fs/eventpoll.c:__do_sys_epoll_ctl
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_read_events_proc
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
In mm/memcontrol.c (c0557db8)
Location: include/linux/poll.h:75
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/select.c (c05859cc)
Location: include/linux/poll.h:75
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (c05c7dc4)
Location: include/linux/poll.h:75
Inline: True
Inline callers:
  - fs/eventpoll.c:__do_sys_epoll_ctl
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_read_events_proc
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
In mm/memcontrol.c (c00000000045331c)
Location: include/linux/poll.h:75
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/select.c (c00000000049ce68)
Location: include/linux/poll.h:75
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (c0000000004fa460)
Location: include/linux/poll.h:75
Inline: True
Inline callers:
  - fs/eventpoll.c:__se_sys_epoll_ctl
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_read_events_proc
```
```
In drivers/vfio/virqfd.c (c000000000ab1d2c)
Location: include/linux/poll.h:75
Inline: True
Inline callers:
  - drivers/vfio/virqfd.c:vfio_virqfd_enable
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
In mm/memcontrol.c (ffffffe00024497a)
Location: include/linux/poll.h:75
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/select.c (ffffffe00026b164)
Location: include/linux/poll.h:75
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffffffe0002a493a)
Location: include/linux/poll.h:75
Inline: True
Inline callers:
  - fs/eventpoll.c:__se_sys_epoll_ctl
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_read_events_proc
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
In mm/memcontrol.c (ffffffff812bbd97)
Location: include/linux/poll.h:75
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/select.c (ffffffff812ee563)
Location: include/linux/poll.h:75
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffffffff8132d978)
Location: include/linux/poll.h:75
Inline: True
Inline callers:
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_read_events_proc
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
In mm/memcontrol.c (ffffffff812acef7)
Location: include/linux/poll.h:75
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/select.c (ffffffff812df193)
Location: include/linux/poll.h:75
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffffffff8131dcf6)
Location: include/linux/poll.h:75
Inline: True
Inline callers:
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_read_events_proc
```
```
In drivers/vfio/virqfd.c (ffffffff8177c9ca)
Location: include/linux/poll.h:75
Inline: True
Inline callers:
  - drivers/vfio/virqfd.c:vfio_virqfd_enable
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
In mm/memcontrol.c (ffffffff812b9ba7)
Location: include/linux/poll.h:75
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/select.c (ffffffff812ec373)
Location: include/linux/poll.h:75
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffffffff8132b448)
Location: include/linux/poll.h:75
Inline: True
Inline callers:
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_read_events_proc
```
```
In drivers/vfio/virqfd.c (ffffffff817c77a6)
Location: include/linux/poll.h:75
Inline: True
Inline callers:
  - drivers/vfio/virqfd.c:vfio_virqfd_enable
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
In mm/memcontrol.c (ffffffff812ca237)
Location: include/linux/poll.h:75
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/select.c (ffffffff812fd373)
Location: include/linux/poll.h:75
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffffffff8133bf92)
Location: include/linux/poll.h:75
Inline: True
Inline callers:
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_read_events_proc
```
```
In drivers/vfio/virqfd.c (ffffffff817e19cb)
Location: include/linux/poll.h:75
Inline: True
Inline callers:
  - drivers/vfio/virqfd.c:vfio_virqfd_enable
```
</details>
</li>
</ul>

## Differences
