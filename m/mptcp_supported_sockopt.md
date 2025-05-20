# Function: <code>mptcp_supported_sockopt</code>

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
bool mptcp_supported_sockopt(int level, int optname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/sockopt.c (ffffffff81bbbbb0)
Location: net/mptcp/sockopt.c:300
Inline: False
Direct callers:
  - net/mptcp/sockopt.c:mptcp_setsockopt
```
**Symbols:**

```
ffffffff81bbbbb0-ffffffff81bbbc6a: mptcp_supported_sockopt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/mptcp/sockopt.c (ffffffff81c8c639)
Location: net/mptcp/sockopt.c:409
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:mptcp_setsockopt
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/mptcp/sockopt.c (ffffffff81e34a79)
Location: net/mptcp/sockopt.c:431
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:mptcp_setsockopt
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/mptcp/sockopt.c (ffffffff8200d6d9)
Location: net/mptcp/sockopt.c:431
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:mptcp_setsockopt
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/mptcp/sockopt.c (ffffffff8208a069)
Location: net/mptcp/sockopt.c:433
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:mptcp_setsockopt
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool mptcp_supported_sockopt(int level, int optname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/sockopt.c (ffffffff8215d4f0)
Location: net/mptcp/sockopt.c:436
Inline: False
Direct callers:
  - net/mptcp/sockopt.c:mptcp_setsockopt
```
**Symbols:**

```
ffffffff8215d4f0-ffffffff8215d590: mptcp_supported_sockopt (STB_LOCAL)
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
</ul>
