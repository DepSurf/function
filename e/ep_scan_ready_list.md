# Function: <code>ep_scan_ready_list</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ep_scan_ready_list(struct eventpoll *ep, int (*sproc)(struct eventpoll *, struct list_head *, void *), void *priv, int depth, bool ep_locked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff81255190)
Location: fs/eventpoll.c:592
Inline: False
Direct callers:
  - fs/eventpoll.c:ep_poll_readyevents_proc
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
```
**Symbols:**

```
ffffffff81255190-ffffffff8125537e: ep_scan_ready_list (STB_LOCAL)
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
In fs/eventpoll.c (ffffffff8127d520)
Location: fs/eventpoll.c:597
Inline: True
Direct callers:
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll_readyevents_proc
```
**Symbols:**

```
ffffffff8127d520-ffffffff8127d72b: ep_scan_ready_list.constprop.12 (STB_LOCAL)
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
In fs/eventpoll.c (ffffffff812910b0)
Location: fs/eventpoll.c:597
Inline: True
Direct callers:
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll_readyevents_proc
```
**Symbols:**

```
ffffffff812910b0-ffffffff812912b8: ep_scan_ready_list.constprop.14 (STB_LOCAL)
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
In fs/eventpoll.c (ffffffff8129dfa0)
Location: fs/eventpoll.c:679
Inline: True
Direct callers:
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll_readyevents_proc
```
**Symbols:**

```
ffffffff8129dfa0-ffffffff8129e1ac: ep_scan_ready_list.constprop.16 (STB_LOCAL)
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
In fs/eventpoll.c (ffffffff812c1490)
Location: fs/eventpoll.c:663
Inline: True
Direct callers:
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_eventpoll_poll
```
**Symbols:**

```
ffffffff812c1490-ffffffff812c1696: ep_scan_ready_list.constprop.17 (STB_LOCAL)
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
In fs/eventpoll.c (ffffffff812ea290)
Location: fs/eventpoll.c:664
Inline: True
Direct callers:
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_eventpoll_poll
```
**Symbols:**

```
ffffffff812ea290-ffffffff812ea495: ep_scan_ready_list.constprop.24 (STB_LOCAL)
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
In fs/eventpoll.c (ffffffff812ff460)
Location: fs/eventpoll.c:672
Inline: True
Direct callers:
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_eventpoll_poll
```
**Symbols:**

```
ffffffff812ff460-ffffffff812ff657: ep_scan_ready_list.constprop.23 (STB_LOCAL)
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
In fs/eventpoll.c (ffffffff81320610)
Location: fs/eventpoll.c:668
Inline: True
Direct callers:
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_eventpoll_poll
```
**Symbols:**

```
ffffffff81320610-ffffffff8132080a: ep_scan_ready_list.constprop.0 (STB_LOCAL)
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
In fs/eventpoll.c (ffffffff813333c0)
Location: fs/eventpoll.c:668
Inline: True
Direct callers:
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_eventpoll_poll
```
**Symbols:**

```
ffffffff813333c0-ffffffff813335ba: ep_scan_ready_list.constprop.0 (STB_LOCAL)
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
In fs/eventpoll.c (ffffffff8136d6c0)
Location: fs/eventpoll.c:677
Inline: True
Direct callers:
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_eventpoll_poll
  - fs/eventpoll.c:ep_item_poll
```
**Symbols:**

```
ffffffff8136d6c0-ffffffff8136d847: ep_scan_ready_list.constprop.0 (STB_LOCAL)
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
In fs/eventpoll.c (ffff8000103f06c0)
Location: fs/eventpoll.c:668
Inline: True
Direct callers:
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_eventpoll_poll
```
**Symbols:**

```
ffff8000103f06c0-ffff8000103f0968: ep_scan_ready_list.isra.0 (STB_LOCAL)
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
In fs/eventpoll.c (c05c61d0)
Location: fs/eventpoll.c:668
Inline: True
Direct callers:
  - fs/eventpoll.c:do_epoll_wait
  - fs/eventpoll.c:ep_eventpoll_poll
  - fs/eventpoll.c:ep_item_poll
```
**Symbols:**

```
c05c61d0-c05c63fc: ep_scan_ready_list.constprop.0 (STB_LOCAL)
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
In fs/eventpoll.c (c0000000004f7e20)
Location: fs/eventpoll.c:668
Inline: True
Direct callers:
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_eventpoll_poll
```
**Symbols:**

```
c0000000004f7e20-c0000000004f80d8: ep_scan_ready_list.isra.0 (STB_LOCAL)
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
In fs/eventpoll.c (ffffffe0002a302e)
Location: fs/eventpoll.c:668
Inline: True
Direct callers:
  - fs/eventpoll.c:do_epoll_wait
  - fs/eventpoll.c:ep_eventpoll_poll
```
**Symbols:**

```
ffffffe0002a302e-ffffffe0002a319e: ep_scan_ready_list.isra.0 (STB_LOCAL)
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
In fs/eventpoll.c (ffffffff8132b9a0)
Location: fs/eventpoll.c:668
Inline: True
Direct callers:
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_eventpoll_poll
```
**Symbols:**

```
ffffffff8132b9a0-ffffffff8132bb9a: ep_scan_ready_list.constprop.0 (STB_LOCAL)
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
In fs/eventpoll.c (ffffffff8131bb40)
Location: fs/eventpoll.c:668
Inline: True
Direct callers:
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_eventpoll_poll
```
**Symbols:**

```
ffffffff8131bb40-ffffffff8131bd2e: ep_scan_ready_list.constprop.0 (STB_LOCAL)
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
In fs/eventpoll.c (ffffffff81329470)
Location: fs/eventpoll.c:668
Inline: True
Direct callers:
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_eventpoll_poll
```
**Symbols:**

```
ffffffff81329470-ffffffff8132966a: ep_scan_ready_list.constprop.0 (STB_LOCAL)
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
In fs/eventpoll.c (ffffffff8133a800)
Location: fs/eventpoll.c:668
Inline: True
Direct callers:
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_eventpoll_poll
```
**Symbols:**

```
ffffffff8133a800-ffffffff8133a9e7: ep_scan_ready_list.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
