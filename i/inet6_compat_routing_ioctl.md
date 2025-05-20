# Function: <code>inet6_compat_routing_ioctl</code>

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
<summary>In <code>5.8</code>: ✅</summary>

```c
int inet6_compat_routing_ioctl(struct sock *sk, unsigned int cmd, struct compat_in6_rtmsg *ur);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/af_inet6.c (ffffffff81b29e30)
Location: net/ipv6/af_inet6.c:593
Inline: False
Direct callers:
  - net/ipv6/af_inet6.c:inet6_compat_ioctl
```
**Symbols:**

```
ffffffff81b29e30-ffffffff81b29f1f: inet6_compat_routing_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int inet6_compat_routing_ioctl(struct sock *sk, unsigned int cmd, struct compat_in6_rtmsg *ur);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/af_inet6.c (ffffffff81b38770)
Location: net/ipv6/af_inet6.c:593
Inline: False
Direct callers:
  - net/ipv6/af_inet6.c:inet6_compat_ioctl
```
**Symbols:**

```
ffffffff81b38770-ffffffff81b3885f: inet6_compat_routing_ioctl (STB_LOCAL)
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
In net/ipv6/af_inet6.c (ffffffff81b2648e)
Location: net/ipv6/af_inet6.c:597
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_compat_ioctl
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
In net/ipv6/af_inet6.c (ffffffff81bebeee)
Location: net/ipv6/af_inet6.c:599
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_compat_ioctl
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
In net/ipv6/af_inet6.c (ffffffff81d843ed)
Location: net/ipv6/af_inet6.c:605
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_compat_ioctl
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
In net/ipv6/af_inet6.c (ffffffff81f51cdd)
Location: net/ipv6/af_inet6.c:613
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_compat_ioctl
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
In net/ipv6/af_inet6.c (ffffffff81fb16fd)
Location: net/ipv6/af_inet6.c:603
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_compat_ioctl
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
In net/ipv6/af_inet6.c (ffffffff8207ee1d)
Location: net/ipv6/af_inet6.c:612
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_compat_ioctl
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
