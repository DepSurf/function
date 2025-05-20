# Function: <code>ep_done_scan</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ep_done_scan(struct eventpoll *ep, struct list_head *txlist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff8137aae0)
Location: fs/eventpoll.c:620
Inline: False
Direct callers:
  - fs/eventpoll.c:ep_send_events
```
**Symbols:**

```
ffffffff8137aae0-ffffffff8137aba1: ep_done_scan (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ep_done_scan(struct eventpoll *ep, struct list_head *txlist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff81381620)
Location: fs/eventpoll.c:620
Inline: False
Direct callers:
  - fs/eventpoll.c:ep_send_events
```
**Symbols:**

```
ffffffff81381620-ffffffff81381718: ep_done_scan (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void ep_done_scan(struct eventpoll *ep, struct list_head *txlist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff813ce860)
Location: fs/eventpoll.c:620
Inline: False
Direct callers:
  - fs/eventpoll.c:ep_send_events
```
**Symbols:**

```
ffffffff813ce860-ffffffff813ce958: ep_done_scan (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void ep_done_scan(struct eventpoll *ep, struct list_head *txlist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff814572c0)
Location: fs/eventpoll.c:627
Inline: False
Direct callers:
  - fs/eventpoll.c:ep_send_events
```
**Symbols:**

```
ffffffff814572c0-ffffffff814573bd: ep_done_scan (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ep_done_scan(struct eventpoll *ep, struct list_head *txlist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff814e6510)
Location: fs/eventpoll.c:629
Inline: False
Direct callers:
  - fs/eventpoll.c:ep_send_events
```
**Symbols:**

```
ffffffff814e6510-ffffffff814e660d: ep_done_scan (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ep_done_scan(struct eventpoll *ep, struct list_head *txlist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff8151d080)
Location: fs/eventpoll.c:633
Inline: False
Direct callers:
  - fs/eventpoll.c:ep_send_events
```
**Symbols:**

```
ffffffff8151d080-ffffffff8151d17d: ep_done_scan (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ep_done_scan(struct eventpoll *ep, struct list_head *txlist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff81551660)
Location: fs/eventpoll.c:632
Inline: False
Direct callers:
  - fs/eventpoll.c:ep_send_events
```
**Symbols:**

```
ffffffff81551660-ffffffff8155175d: ep_done_scan (STB_LOCAL)
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
