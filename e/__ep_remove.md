# Function: <code>__ep_remove</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
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
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool __ep_remove(struct eventpoll *ep, struct epitem *epi, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/eventpoll.c (0)
Location: fs/eventpoll.c:721
Inline: False
Direct callers:
  - fs/eventpoll.c:do_epoll_ctl
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:eventpoll_release_file
  - fs/eventpoll.c:ep_clear_and_put
```
**Symbols:**

```
ffffffff8151d4c0-ffffffff8151d710: __ep_remove (STB_LOCAL)
ffffffff820e9eaa-ffffffff820e9ebe: __ep_remove.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool __ep_remove(struct eventpoll *ep, struct epitem *epi, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/eventpoll.c (0)
Location: fs/eventpoll.c:720
Inline: False
Direct callers:
  - fs/eventpoll.c:do_epoll_ctl
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:eventpoll_release_file
  - fs/eventpoll.c:ep_clear_and_put
```
**Symbols:**

```
ffffffff81551aa0-ffffffff81551cf0: __ep_remove (STB_LOCAL)
ffffffff821c6997-ffffffff821c69ab: __ep_remove.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
