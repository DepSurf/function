# Function: <code>ep_set_mstimeout</code>

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
In fs/eventpoll.c (ffffffff812553ec)
Location: fs/eventpoll.c:1557
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
In fs/eventpoll.c (ffffffff8127d76c)
Location: fs/eventpoll.c:1586
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
In fs/eventpoll.c (ffffffff812912fc)
Location: fs/eventpoll.c:1586
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
In fs/eventpoll.c (ffffffff8129e283)
Location: fs/eventpoll.c:1726
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
In fs/eventpoll.c (ffffffff812c1773)
Location: fs/eventpoll.c:1708
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
In fs/eventpoll.c (ffffffff812ea56b)
Location: fs/eventpoll.c:1710
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
In fs/eventpoll.c (ffffffff813006f5)
Location: fs/eventpoll.c:1719
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
In fs/eventpoll.c (ffffffff813219c5)
Location: fs/eventpoll.c:1797
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
In fs/eventpoll.c (ffffffff81333f25)
Location: fs/eventpoll.c:1797
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
In fs/eventpoll.c (ffffffff8136e454)
Location: fs/eventpoll.c:1790
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
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
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffff8000103f26dc)
Location: fs/eventpoll.c:1797
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
In fs/eventpoll.c (c05c6584)
Location: fs/eventpoll.c:1797
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
In fs/eventpoll.c (c0000000004f82a0)
Location: fs/eventpoll.c:1797
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct timespec64 ep_set_mstimeout(long int ms);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffe0002a2ee6)
Location: fs/eventpoll.c:1797
Inline: False
Direct callers:
  - fs/eventpoll.c:do_epoll_wait
```
**Symbols:**

```
ffffffe0002a2ee6-ffffffe0002a2f3c: ep_set_mstimeout (STB_LOCAL)
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
In fs/eventpoll.c (ffffffff8132c505)
Location: fs/eventpoll.c:1797
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
In fs/eventpoll.c (ffffffff8131bdf0)
Location: fs/eventpoll.c:1797
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
In fs/eventpoll.c (ffffffff81329fd5)
Location: fs/eventpoll.c:1797
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
In fs/eventpoll.c (ffffffff8133aab0)
Location: fs/eventpoll.c:1797
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
