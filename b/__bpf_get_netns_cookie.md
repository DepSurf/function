# Function: <code>__bpf_get_netns_cookie</code>

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
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a29e68)
Location: net/core/filter.c:4235
Inline: True
Inline callers:
  - net/core/filter.c:bpf_get_netns_cookie_sock_addr
  - net/core/filter.c:bpf_get_netns_cookie_sock
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a2a7c8)
Location: net/core/filter.c:4642
Inline: True
Inline callers:
  - net/core/filter.c:bpf_get_netns_cookie_sock_addr
  - net/core/filter.c:bpf_get_netns_cookie_sock
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a0aa68)
Location: net/core/filter.c:4593
Inline: True
Inline callers:
  - net/core/filter.c:bpf_get_netns_cookie_sock_addr
  - net/core/filter.c:bpf_get_netns_cookie_sock
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
In net/core/filter.c (ffffffff81abce2c)
Location: net/core/filter.c:4651
Inline: True
Inline callers:
  - net/core/filter.c:bpf_get_netns_cookie_sk_msg
  - net/core/filter.c:bpf_get_netns_cookie_sock_ops
  - net/core/filter.c:bpf_get_netns_cookie_sock_addr
  - net/core/filter.c:bpf_get_netns_cookie_sock
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
In net/core/filter.c (ffffffff81c3797c)
Location: net/core/filter.c:4944
Inline: True
Inline callers:
  - net/core/filter.c:bpf_get_netns_cookie_sk_msg
  - net/core/filter.c:bpf_get_netns_cookie_sock_ops
  - net/core/filter.c:bpf_get_netns_cookie_sock_addr
  - net/core/filter.c:bpf_get_netns_cookie_sock
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
In net/core/filter.c (ffffffff81deb26c)
Location: net/core/filter.c:4962
Inline: True
Inline callers:
  - net/core/filter.c:bpf_get_netns_cookie_sk_msg
  - net/core/filter.c:bpf_get_netns_cookie_sock_ops
  - net/core/filter.c:bpf_get_netns_cookie_sock_addr
  - net/core/filter.c:bpf_get_netns_cookie_sock
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
In net/core/filter.c (ffffffff81e5ca6c)
Location: net/core/filter.c:5016
Inline: True
Inline callers:
  - net/core/filter.c:bpf_get_netns_cookie_sk_msg
  - net/core/filter.c:bpf_get_netns_cookie_sock_ops
  - net/core/filter.c:bpf_get_netns_cookie_sock_addr
  - net/core/filter.c:bpf_get_netns_cookie_sock
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81f1be5c)
Location: net/core/filter.c:5090
Inline: True
Inline callers:
  - net/core/filter.c:bpf_get_netns_cookie_sk_msg
  - net/core/filter.c:bpf_get_netns_cookie_sock_ops
  - net/core/filter.c:bpf_get_netns_cookie_sock_addr
  - net/core/filter.c:bpf_get_netns_cookie_sock
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
