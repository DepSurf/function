# Function: <code>cubictcp_acked</code>

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
void cubictcp_acked(struct sock *sk, const struct ack_sample *sample);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cubic.c (ffffffff81b04130)
Location: net/ipv4/tcp_cubic.c:445
Inline: False
```
**Symbols:**

```
ffffffff81b04130-ffffffff81b041aa: cubictcp_acked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void cubictcp_acked(struct sock *sk, const struct ack_sample *sample);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cubic.c (ffffffff81bc6470)
Location: net/ipv4/tcp_cubic.c:446
Inline: False
```
**Symbols:**

```
ffffffff81bc6470-ffffffff81bc64ea: cubictcp_acked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void cubictcp_acked(struct sock *sk, const struct ack_sample *sample);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cubic.c (ffffffff81d5b7b0)
Location: net/ipv4/tcp_cubic.c:448
Inline: False
```
**Symbols:**

```
ffffffff81d5b7b0-ffffffff81d5b842: cubictcp_acked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void cubictcp_acked(struct sock *sk, const struct ack_sample *sample);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cubic.c (ffffffff81f25c70)
Location: net/ipv4/tcp_cubic.c:448
Inline: False
```
**Symbols:**

```
ffffffff81f25c70-ffffffff81f25d02: cubictcp_acked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void cubictcp_acked(struct sock *sk, const struct ack_sample *sample);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cubic.c (ffffffff81f85c60)
Location: net/ipv4/tcp_cubic.c:448
Inline: False
```
**Symbols:**

```
ffffffff81f85c60-ffffffff81f85cf1: cubictcp_acked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void cubictcp_acked(struct sock *sk, const struct ack_sample *sample);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cubic.c (ffffffff8204c330)
Location: net/ipv4/tcp_cubic.c:448
Inline: False
```
**Symbols:**

```
ffffffff8204c330-ffffffff8204c3c1: cubictcp_acked (STB_LOCAL)
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
