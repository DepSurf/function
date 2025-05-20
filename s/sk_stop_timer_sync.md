# Function: <code>sk_stop_timer_sync</code>

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
void sk_stop_timer_sync(struct sock *sk, struct timer_list *timer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819e47a0)
Location: net/core/sock.c:2958
Inline: False
Direct callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_free_anno_list
  - net/mptcp/pm_netlink.c:mptcp_pm_del_add_timer
```
**Symbols:**

```
ffffffff819e47a0-ffffffff819e47e4: sk_stop_timer_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void sk_stop_timer_sync(struct sock *sk, struct timer_list *timer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819ca820)
Location: net/core/sock.c:2981
Inline: False
Direct callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_free_anno_list
  - net/mptcp/pm_netlink.c:mptcp_pm_del_add_timer
```
**Symbols:**

```
ffffffff819ca820-ffffffff819ca864: sk_stop_timer_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void sk_stop_timer_sync(struct sock *sk, struct timer_list *timer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81a79850)
Location: net/core/sock.c:3112
Inline: False
Direct callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_free_anno_list
  - net/mptcp/pm_netlink.c:mptcp_pm_del_add_timer
```
**Symbols:**

```
ffffffff81a79850-ffffffff81a79894: sk_stop_timer_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void sk_stop_timer_sync(struct sock *sk, struct timer_list *timer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81bedb20)
Location: net/core/sock.c:3297
Inline: True
Direct callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_free_anno_list
  - net/mptcp/pm_netlink.c:mptcp_pm_del_add_timer
```
**Symbols:**

```
ffffffff81bedb20-ffffffff81bedb6e: sk_stop_timer_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void sk_stop_timer_sync(struct sock *sk, struct timer_list *timer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81d99610)
Location: net/core/sock.c:3377
Inline: True
Direct callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_free_anno_list
  - net/mptcp/pm_netlink.c:mptcp_pm_del_add_timer
```
**Symbols:**

```
ffffffff81d99610-ffffffff81d9965e: sk_stop_timer_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void sk_stop_timer_sync(struct sock *sk, struct timer_list *timer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81e088c0)
Location: net/core/sock.c:3410
Inline: True
Direct callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_free_anno_list
  - net/mptcp/pm_netlink.c:mptcp_pm_del_add_timer
```
**Symbols:**

```
ffffffff81e088c0-ffffffff81e0890e: sk_stop_timer_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void sk_stop_timer_sync(struct sock *sk, struct timer_list *timer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81ec4370)
Location: net/core/sock.c:3420
Inline: True
Direct callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_free_anno_list
  - net/mptcp/pm_netlink.c:mptcp_pm_del_add_timer
```
**Symbols:**

```
ffffffff81ec4370-ffffffff81ec43be: sk_stop_timer_sync (STB_GLOBAL)
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
