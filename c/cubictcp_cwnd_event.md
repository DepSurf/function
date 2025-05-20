# Function: <code>cubictcp_cwnd_event</code>

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
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void cubictcp_cwnd_event(struct sock *sk, enum tcp_ca_event event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cubic.c (ffffffff81b044d0)
Location: net/ipv4/tcp_cubic.c:140
Inline: True
```
**Symbols:**

```
ffffffff81b044d0-ffffffff81b0450b: cubictcp_cwnd_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void cubictcp_cwnd_event(struct sock *sk, enum tcp_ca_event event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cubic.c (ffffffff81bc6870)
Location: net/ipv4/tcp_cubic.c:140
Inline: True
```
**Symbols:**

```
ffffffff81bc6870-ffffffff81bc68ab: cubictcp_cwnd_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void cubictcp_cwnd_event(struct sock *sk, enum tcp_ca_event event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cubic.c (ffffffff81d5bbf0)
Location: net/ipv4/tcp_cubic.c:142
Inline: True
```
**Symbols:**

```
ffffffff81d5bbf0-ffffffff81d5bc47: cubictcp_cwnd_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void cubictcp_cwnd_event(struct sock *sk, enum tcp_ca_event event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cubic.c (ffffffff81f26100)
Location: net/ipv4/tcp_cubic.c:142
Inline: True
```
**Symbols:**

```
ffffffff81f26100-ffffffff81f26157: cubictcp_cwnd_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void cubictcp_cwnd_event(struct sock *sk, enum tcp_ca_event event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cubic.c (ffffffff81f85530)
Location: net/ipv4/tcp_cubic.c:142
Inline: False
```
**Symbols:**

```
ffffffff81f85530-ffffffff81f85587: cubictcp_cwnd_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void cubictcp_cwnd_event(struct sock *sk, enum tcp_ca_event event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cubic.c (ffffffff8204bc00)
Location: net/ipv4/tcp_cubic.c:142
Inline: False
```
**Symbols:**

```
ffffffff8204bc00-ffffffff8204bc57: cubictcp_cwnd_event (STB_LOCAL)
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
