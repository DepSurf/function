# Function: <code>mptcp_event</code>

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
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void mptcp_event(enum mptcp_event_type type, const struct mptcp_sock *msk, const struct sock *ssk, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff81bbb8f0)
Location: net/mptcp/pm_netlink.c:1793
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_finish_join
  - net/mptcp/protocol.c:mptcp_close
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/pm.c:mptcp_pm_mp_prio_received
  - net/mptcp/pm.c:mptcp_pm_fully_established
  - net/mptcp/pm.c:mptcp_pm_new_connection
```
**Symbols:**

```
ffffffff81bbb8f0-ffffffff81bbbba8: mptcp_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void mptcp_event(enum mptcp_event_type type, const struct mptcp_sock *msk, const struct sock *ssk, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff81c8b530)
Location: net/mptcp/pm_netlink.c:1983
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_finish_join
  - net/mptcp/protocol.c:mptcp_close
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/pm.c:mptcp_pm_mp_prio_received
  - net/mptcp/pm.c:mptcp_pm_fully_established
  - net/mptcp/pm.c:mptcp_pm_new_connection
```
**Symbols:**

```
ffffffff81c8b530-ffffffff81c8b7ee: mptcp_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void mptcp_event(enum mptcp_event_type type, const struct mptcp_sock *msk, const struct sock *ssk, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/pm_netlink.c (0)
Location: net/mptcp/pm_netlink.c:2145
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_finish_join
  - net/mptcp/protocol.c:mptcp_disconnect
  - net/mptcp/protocol.c:mptcp_close
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/pm.c:mptcp_pm_mp_prio_received
  - net/mptcp/pm.c:mptcp_pm_fully_established
  - net/mptcp/pm.c:mptcp_pm_new_connection
```
**Symbols:**

```
ffffffff81f10b99-ffffffff81f10bb5: mptcp_event.cold (STB_LOCAL)
ffffffff81e32ad0-ffffffff81e32db7: mptcp_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void mptcp_event(enum mptcp_event_type type, const struct mptcp_sock *msk, const struct sock *ssk, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/pm_netlink.c (0)
Location: net/mptcp/pm_netlink.c:2211
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_finish_join
  - net/mptcp/protocol.c:__mptcp_close
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/pm.c:mptcp_pm_mp_prio_received
  - net/mptcp/pm.c:mptcp_pm_fully_established
  - net/mptcp/pm.c:mptcp_pm_new_connection
```
**Symbols:**

```
ffffffff820b6e97-ffffffff820b6eb3: mptcp_event.cold (STB_LOCAL)
ffffffff8200b530-ffffffff8200b817: mptcp_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void mptcp_event(enum mptcp_event_type type, const struct mptcp_sock *msk, const struct sock *ssk, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/pm_netlink.c (0)
Location: net/mptcp/pm_netlink.c:2227
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_finish_join
  - net/mptcp/protocol.c:mptcp_disconnect
  - net/mptcp/protocol.c:__mptcp_close
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/pm.c:mptcp_pm_mp_prio_received
  - net/mptcp/pm.c:mptcp_pm_fully_established
  - net/mptcp/pm.c:mptcp_pm_new_connection
```
**Symbols:**

```
ffffffff821381e9-ffffffff82138205: mptcp_event.cold (STB_LOCAL)
ffffffff820879c0-ffffffff82087ca9: mptcp_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void mptcp_event(enum mptcp_event_type type, const struct mptcp_sock *msk, const struct sock *ssk, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/pm_netlink.c (0)
Location: net/mptcp/pm_netlink.c:2226
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_finish_join
  - net/mptcp/protocol.c:mptcp_disconnect
  - net/mptcp/protocol.c:__mptcp_close
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/pm.c:mptcp_pm_mp_prio_received
  - net/mptcp/pm.c:mptcp_pm_fully_established
  - net/mptcp/pm.c:mptcp_pm_new_connection
```
**Symbols:**

```
ffffffff8221a009-ffffffff8221a025: mptcp_event.cold (STB_LOCAL)
ffffffff8215d220-ffffffff8215d4da: mptcp_event (STB_GLOBAL)
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
