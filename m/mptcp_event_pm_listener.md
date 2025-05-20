# Function: <code>mptcp_event_pm_listener</code>

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
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void mptcp_event_pm_listener(const struct sock *ssk, enum mptcp_event_type event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/pm_netlink.c (0)
Location: net/mptcp/pm_netlink.c:2159
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_listen
  - net/mptcp/protocol.c:__mptcp_close_ssk
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_create_listen_socket
```
**Symbols:**

```
ffffffff820b6e62-ffffffff820b6e82: mptcp_event_pm_listener.cold (STB_LOCAL)
ffffffff8200ae60-ffffffff8200b05d: mptcp_event_pm_listener (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void mptcp_event_pm_listener(const struct sock *ssk, enum mptcp_event_type event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/pm_netlink.c (0)
Location: net/mptcp/pm_netlink.c:2175
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_listen
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_create_listen_socket
```
**Symbols:**

```
ffffffff821381bb-ffffffff821381d4: mptcp_event_pm_listener.cold (STB_LOCAL)
ffffffff82087290-ffffffff82087496: mptcp_event_pm_listener (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void mptcp_event_pm_listener(const struct sock *ssk, enum mptcp_event_type event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/pm_netlink.c (0)
Location: net/mptcp/pm_netlink.c:2174
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_listen
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_create_listen_socket
```
**Symbols:**

```
ffffffff82219fdb-ffffffff82219ff4: mptcp_event_pm_listener.cold (STB_LOCAL)
ffffffff8215cae0-ffffffff8215ccae: mptcp_event_pm_listener (STB_GLOBAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
