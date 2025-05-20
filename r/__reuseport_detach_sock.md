# Function: <code>__reuseport_detach_sock</code>

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
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff81ad1edd)
Location: net/core/sock_reuseport.c:53
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_stop_listen_sock
  - net/core/sock_reuseport.c:reuseport_detach_sock
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
In net/core/sock_reuseport.c (ffffffff81c4f8ca)
Location: net/core/sock_reuseport.c:53
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_stop_listen_sock
  - net/core/sock_reuseport.c:reuseport_detach_sock
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff81e04b50)
Location: net/core/sock_reuseport.c:134
Inline: True
Direct callers:
  - net/core/sock_reuseport.c:reuseport_stop_listen_sock
  - net/core/sock_reuseport.c:reuseport_detach_sock
```
**Symbols:**

```
ffffffff81e04b50-ffffffff81e04bb1: __reuseport_detach_sock.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff81e773a0)
Location: net/core/sock_reuseport.c:134
Inline: True
Direct callers:
  - net/core/sock_reuseport.c:reuseport_stop_listen_sock
  - net/core/sock_reuseport.c:reuseport_detach_sock
```
**Symbols:**

```
ffffffff81e773a0-ffffffff81e77401: __reuseport_detach_sock.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff81f37360)
Location: net/core/sock_reuseport.c:134
Inline: True
Direct callers:
  - net/core/sock_reuseport.c:reuseport_stop_listen_sock
  - net/core/sock_reuseport.c:reuseport_detach_sock
```
**Symbols:**

```
ffffffff81f37360-ffffffff81f373c1: __reuseport_detach_sock.isra.0 (STB_LOCAL)
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
