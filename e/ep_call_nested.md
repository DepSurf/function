# Function: <code>ep_call_nested</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/eventpoll.c (ffffffff81254bb0)
Location: fs/eventpoll.c:398
Inline: True
Direct callers:
  - fs/eventpoll.c:reverse_path_check_proc
  - fs/eventpoll.c:ep_free
  - fs/eventpoll.c:ep_loop_check_proc
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:ep_scan_ready_list
  - fs/eventpoll.c:ep_eventpoll_poll
  - fs/eventpoll.c:SyS_epoll_ctl
  - fs/eventpoll.c:SyS_epoll_ctl
  - fs/eventpoll.c:SyS_epoll_ctl
  - fs/eventpoll.c:SyS_epoll_ctl
```
**Symbols:**

```
ffffffff81254bb0-ffffffff81254cd3: ep_call_nested.constprop.11 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/eventpoll.c (ffffffff8127d3f0)
Location: fs/eventpoll.c:403
Inline: True
Direct callers:
  - fs/eventpoll.c:SyS_epoll_ctl
  - fs/eventpoll.c:SyS_epoll_ctl
  - fs/eventpoll.c:SyS_epoll_ctl
  - fs/eventpoll.c:SyS_epoll_ctl
  - fs/eventpoll.c:ep_loop_check_proc
  - fs/eventpoll.c:reverse_path_check_proc
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:ep_eventpoll_poll
  - fs/eventpoll.c:ep_free
```
**Symbols:**

```
ffffffff8127d3f0-ffffffff8127d513: ep_call_nested.constprop.13 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/eventpoll.c (ffffffff81290f80)
Location: fs/eventpoll.c:403
Inline: True
Direct callers:
  - fs/eventpoll.c:SyS_epoll_ctl
  - fs/eventpoll.c:SyS_epoll_ctl
  - fs/eventpoll.c:SyS_epoll_ctl
  - fs/eventpoll.c:SyS_epoll_ctl
  - fs/eventpoll.c:ep_loop_check_proc
  - fs/eventpoll.c:reverse_path_check_proc
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:ep_eventpoll_poll
  - fs/eventpoll.c:ep_free
```
**Symbols:**

```
ffffffff81290f80-ffffffff812910a3: ep_call_nested.constprop.15 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/eventpoll.c (ffffffff8129de70)
Location: fs/eventpoll.c:480
Inline: True
Direct callers:
  - fs/eventpoll.c:SyS_epoll_ctl
  - fs/eventpoll.c:SyS_epoll_ctl
  - fs/eventpoll.c:SyS_epoll_ctl
  - fs/eventpoll.c:SyS_epoll_ctl
  - fs/eventpoll.c:ep_loop_check_proc
  - fs/eventpoll.c:reverse_path_check_proc
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:ep_eventpoll_poll
  - fs/eventpoll.c:ep_free
```
**Symbols:**

```
ffffffff8129de70-ffffffff8129df92: ep_call_nested.constprop.17 (STB_LOCAL)
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
In fs/eventpoll.c (ffffffff812c1160)
Location: fs/eventpoll.c:474
Inline: True
Direct callers:
  - fs/eventpoll.c:SyS_epoll_ctl
  - fs/eventpoll.c:SyS_epoll_ctl
  - fs/eventpoll.c:ep_loop_check_proc
  - fs/eventpoll.c:reverse_path_check_proc
```
**Symbols:**

```
ffffffff812c1160-ffffffff812c12a0: ep_call_nested.constprop.16 (STB_LOCAL)
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
In fs/eventpoll.c (ffffffff812e9ec0)
Location: fs/eventpoll.c:475
Inline: True
Direct callers:
  - fs/eventpoll.c:ep_loop_check
  - fs/eventpoll.c:ep_loop_check_proc
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:reverse_path_check_proc
```
**Symbols:**

```
ffffffff812e9ec0-ffffffff812e9ff5: ep_call_nested.constprop.23 (STB_LOCAL)
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
In fs/eventpoll.c (ffffffff812fea40)
Location: fs/eventpoll.c:483
Inline: True
Direct callers:
  - fs/eventpoll.c:ep_loop_check
  - fs/eventpoll.c:ep_loop_check_proc
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:reverse_path_check_proc
```
**Symbols:**

```
ffffffff812fea40-ffffffff812feb75: ep_call_nested.constprop.22 (STB_LOCAL)
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
In fs/eventpoll.c (ffffffff8131fc10)
Location: fs/eventpoll.c:479
Inline: True
Direct callers:
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
  - fs/eventpoll.c:ep_loop_check_proc
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:reverse_path_check_proc
```
**Symbols:**

```
ffffffff8131fc10-ffffffff8131fd41: ep_call_nested.constprop.0 (STB_LOCAL)
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
In fs/eventpoll.c (ffffffff813329c0)
Location: fs/eventpoll.c:479
Inline: True
Direct callers:
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
  - fs/eventpoll.c:ep_loop_check_proc
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:reverse_path_check_proc
```
**Symbols:**

```
ffffffff813329c0-ffffffff81332af1: ep_call_nested.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/eventpoll.c (ffffffff8136cca0)
Location: fs/eventpoll.c:476
Inline: True
Direct callers:
  - fs/eventpoll.c:do_epoll_ctl
  - fs/eventpoll.c:ep_loop_check_proc
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:reverse_path_check_proc
```
**Symbols:**

```
ffffffff8136cca0-ffffffff8136cdca: ep_call_nested.constprop.0 (STB_LOCAL)
```
</details>
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
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/eventpoll.c (ffff8000103f0ff0)
Location: fs/eventpoll.c:479
Inline: True
Direct callers:
  - fs/eventpoll.c:__do_sys_epoll_ctl
  - fs/eventpoll.c:ep_loop_check_proc
  - fs/eventpoll.c:reverse_path_check_proc
```
**Symbols:**

```
ffff8000103f0ff0-ffff8000103f1204: ep_call_nested.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/eventpoll.c (c05c6df0)
Location: fs/eventpoll.c:479
Inline: True
Direct callers:
  - fs/eventpoll.c:__do_sys_epoll_ctl
  - fs/eventpoll.c:ep_loop_check_proc
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:reverse_path_check_proc
```
**Symbols:**

```
c05c6df0-c05c6f2c: ep_call_nested.constprop.0 (STB_LOCAL)
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
In fs/eventpoll.c (c0000000004f8a70)
Location: fs/eventpoll.c:479
Inline: True
Direct callers:
  - fs/eventpoll.c:__se_sys_epoll_ctl
  - fs/eventpoll.c:ep_loop_check_proc
  - fs/eventpoll.c:reverse_path_check_proc
```
**Symbols:**

```
c0000000004f8a70-c0000000004f8c44: ep_call_nested.constprop.0 (STB_LOCAL)
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
In fs/eventpoll.c (ffffffe0002a37ce)
Location: fs/eventpoll.c:479
Inline: True
Direct callers:
  - fs/eventpoll.c:__se_sys_epoll_ctl
  - fs/eventpoll.c:ep_loop_check_proc
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:reverse_path_check_proc
```
**Symbols:**

```
ffffffe0002a37ce-ffffffe0002a38c0: ep_call_nested.constprop.0 (STB_LOCAL)
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
In fs/eventpoll.c (ffffffff8132afa0)
Location: fs/eventpoll.c:479
Inline: True
Direct callers:
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
  - fs/eventpoll.c:ep_loop_check_proc
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:reverse_path_check_proc
```
**Symbols:**

```
ffffffff8132afa0-ffffffff8132b0d1: ep_call_nested.constprop.0 (STB_LOCAL)
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
In fs/eventpoll.c (ffffffff8131c6e0)
Location: fs/eventpoll.c:479
Inline: True
Direct callers:
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
  - fs/eventpoll.c:ep_loop_check_proc
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:reverse_path_check_proc
```
**Symbols:**

```
ffffffff8131c6e0-ffffffff8131c811: ep_call_nested.constprop.0 (STB_LOCAL)
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
In fs/eventpoll.c (ffffffff81328a70)
Location: fs/eventpoll.c:479
Inline: True
Direct callers:
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
  - fs/eventpoll.c:ep_loop_check_proc
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:reverse_path_check_proc
```
**Symbols:**

```
ffffffff81328a70-ffffffff81328ba1: ep_call_nested.constprop.0 (STB_LOCAL)
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
In fs/eventpoll.c (ffffffff8133b450)
Location: fs/eventpoll.c:479
Inline: True
Direct callers:
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
  - fs/eventpoll.c:ep_loop_check_proc
  - fs/eventpoll.c:reverse_path_check_proc
```
**Symbols:**

```
ffffffff8133b450-ffffffff8133b581: ep_call_nested.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
