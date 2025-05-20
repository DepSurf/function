# Function: <code>inet_compat_routing_ioctl</code>

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
int inet_compat_routing_ioctl(struct sock *sk, unsigned int cmd, struct compat_rtentry *ur);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81ae1fa0)
Location: net/ipv4/af_inet.c:978
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_compat_ioctl
```
**Symbols:**

```
ffffffff81ae1fa0-ffffffff81ae2091: inet_compat_routing_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int inet_compat_routing_ioctl(struct sock *sk, unsigned int cmd, struct compat_rtentry *ur);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81aeee20)
Location: net/ipv4/af_inet.c:981
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_compat_ioctl
```
**Symbols:**

```
ffffffff81aeee20-ffffffff81aeef11: inet_compat_routing_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int inet_compat_routing_ioctl(struct sock *sk, unsigned int cmd, struct compat_rtentry *ur);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81ada5a0)
Location: net/ipv4/af_inet.c:985
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_compat_ioctl
```
**Symbols:**

```
ffffffff81ada5a0-ffffffff81ada691: inet_compat_routing_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int inet_compat_routing_ioctl(struct sock *sk, unsigned int cmd, struct compat_rtentry *ur);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81b99810)
Location: net/ipv4/af_inet.c:987
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_compat_ioctl
```
**Symbols:**

```
ffffffff81b99810-ffffffff81b99901: inet_compat_routing_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int inet_compat_routing_ioctl(struct sock *sk, unsigned int cmd, struct compat_rtentry *ur);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81d2b700)
Location: net/ipv4/af_inet.c:982
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_compat_ioctl
```
**Symbols:**

```
ffffffff81d2b700-ffffffff81d2b813: inet_compat_routing_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int inet_compat_routing_ioctl(struct sock *sk, unsigned int cmd, struct compat_rtentry *ur);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81ef32d0)
Location: net/ipv4/af_inet.c:994
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_compat_ioctl
```
**Symbols:**

```
ffffffff81ef32d0-ffffffff81ef33e3: inet_compat_routing_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int inet_compat_routing_ioctl(struct sock *sk, unsigned int cmd, struct compat_rtentry *ur);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81f52d60)
Location: net/ipv4/af_inet.c:994
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_compat_ioctl
```
**Symbols:**

```
ffffffff81f52d60-ffffffff81f52e73: inet_compat_routing_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int inet_compat_routing_ioctl(struct sock *sk, unsigned int cmd, struct compat_rtentry *ur);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff82019090)
Location: net/ipv4/af_inet.c:1014
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_compat_ioctl
```
**Symbols:**

```
ffffffff82019090-ffffffff820191a3: inet_compat_routing_ioctl (STB_LOCAL)
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
