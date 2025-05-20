# Function: <code>ep_send_events</code>

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
In fs/eventpoll.c (ffffffff812554b7)
Location: fs/eventpoll.c:1546
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
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
In fs/eventpoll.c (ffffffff8127d899)
Location: fs/eventpoll.c:1575
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
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
In fs/eventpoll.c (ffffffff81291429)
Location: fs/eventpoll.c:1575
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
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
In fs/eventpoll.c (ffffffff8129e36a)
Location: fs/eventpoll.c:1715
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
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
In fs/eventpoll.c (ffffffff812c185a)
Location: fs/eventpoll.c:1697
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
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
In fs/eventpoll.c (ffffffff812ea66a)
Location: fs/eventpoll.c:1698
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
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
In fs/eventpoll.c (ffffffff8130068d)
Location: fs/eventpoll.c:1707
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
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
In fs/eventpoll.c (ffffffff8132195a)
Location: fs/eventpoll.c:1785
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
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
In fs/eventpoll.c (ffffffff81333eba)
Location: fs/eventpoll.c:1785
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
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
In fs/eventpoll.c (ffffffff8136e645)
Location: fs/eventpoll.c:1778
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ep_send_events(struct eventpoll *ep, struct epoll_event *events, int maxevents);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff8137b610)
Location: fs/eventpoll.c:1622
Inline: False
Direct callers:
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
```
**Symbols:**

```
ffffffff8137b610-ffffffff8137b87e: ep_send_events (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ep_send_events(struct eventpoll *ep, struct epoll_event *events, int maxevents);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff81381d90)
Location: fs/eventpoll.c:1628
Inline: False
Direct callers:
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
```
**Symbols:**

```
ffffffff81381d90-ffffffff81381ffe: ep_send_events (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ep_send_events(struct eventpoll *ep, struct epoll_event *events, int maxevents);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff813cefe0)
Location: fs/eventpoll.c:1630
Inline: False
Direct callers:
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
```
**Symbols:**

```
ffffffff813cefe0-ffffffff813cf264: ep_send_events (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ep_send_events(struct eventpoll *ep, struct epoll_event *events, int maxevents);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff81457d80)
Location: fs/eventpoll.c:1637
Inline: False
Direct callers:
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
```
**Symbols:**

```
ffffffff81457d80-ffffffff81458016: ep_send_events (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ep_send_events(struct eventpoll *ep, struct epoll_event *events, int maxevents);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff814e70d0)
Location: fs/eventpoll.c:1639
Inline: False
Direct callers:
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
```
**Symbols:**

```
ffffffff814e70d0-ffffffff814e7366: ep_send_events (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ep_send_events(struct eventpoll *ep, struct epoll_event *events, int maxevents);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff8151d920)
Location: fs/eventpoll.c:1684
Inline: False
Direct callers:
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
```
**Symbols:**

```
ffffffff8151d920-ffffffff8151dbb6: ep_send_events (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ep_send_events(struct eventpoll *ep, struct epoll_event *events, int maxevents);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff81551f00)
Location: fs/eventpoll.c:1675
Inline: False
Direct callers:
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
```
**Symbols:**

```
ffffffff81551f00-ffffffff81552196: ep_send_events (STB_LOCAL)
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
In fs/eventpoll.c (ffff8000103f2678)
Location: fs/eventpoll.c:1785
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
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
In fs/eventpoll.c (c05c650c)
Location: fs/eventpoll.c:1785
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_wait
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
In fs/eventpoll.c (c0000000004f8214)
Location: fs/eventpoll.c:1785
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
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
In fs/eventpoll.c (ffffffe0002a32c6)
Location: fs/eventpoll.c:1785
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_wait
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
In fs/eventpoll.c (ffffffff8132c49a)
Location: fs/eventpoll.c:1785
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
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
In fs/eventpoll.c (ffffffff8131bd8a)
Location: fs/eventpoll.c:1785
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
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
In fs/eventpoll.c (ffffffff81329f6a)
Location: fs/eventpoll.c:1785
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
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
In fs/eventpoll.c (ffffffff8133aa4a)
Location: fs/eventpoll.c:1785
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
