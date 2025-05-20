# Function: <code>sock_ioctl_inout</code>

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
<summary>In <code>6.5</code>: ✅</summary>

```c
int sock_ioctl_inout(struct sock *sk, unsigned int cmd, void *arg, void *karg, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81e082f0)
Location: net/core/sock.c:4154
Inline: False
Direct callers:
  - net/core/sock.c:ip6mr_sk_ioctl
  - net/core/sock.c:ip6mr_sk_ioctl
  - net/ipv4/ipmr.c:ipmr_sk_ioctl
  - net/ipv4/ipmr.c:ipmr_sk_ioctl
```
**Symbols:**

```
ffffffff81e082f0-ffffffff81e083a5: sock_ioctl_inout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int sock_ioctl_inout(struct sock *sk, unsigned int cmd, void *arg, void *karg, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81ec4d60)
Location: net/core/sock.c:4168
Inline: False
Direct callers:
  - net/core/sock.c:ip6mr_sk_ioctl
  - net/core/sock.c:ip6mr_sk_ioctl
  - net/ipv4/ipmr.c:ipmr_sk_ioctl
  - net/ipv4/ipmr.c:ipmr_sk_ioctl
```
**Symbols:**

```
ffffffff81ec4d60-ffffffff81ec4e15: sock_ioctl_inout (STB_GLOBAL)
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
