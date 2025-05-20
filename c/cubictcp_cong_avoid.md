# Function: <code>cubictcp_cong_avoid</code>

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
void cubictcp_cong_avoid(struct sock *sk, u32 ack, u32 acked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cubic.c (ffffffff81b04400)
Location: net/ipv4/tcp_cubic.c:322
Inline: False
```
**Symbols:**

```
ffffffff81b04400-ffffffff81b044c9: cubictcp_cong_avoid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void cubictcp_cong_avoid(struct sock *sk, u32 ack, u32 acked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cubic.c (ffffffff81bc67f0)
Location: net/ipv4/tcp_cubic.c:322
Inline: False
```
**Symbols:**

```
ffffffff81bc67f0-ffffffff81bc686b: cubictcp_cong_avoid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void cubictcp_cong_avoid(struct sock *sk, u32 ack, u32 acked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cubic.c (ffffffff81d5bb70)
Location: net/ipv4/tcp_cubic.c:324
Inline: False
```
**Symbols:**

```
ffffffff81d5bb70-ffffffff81d5bbec: cubictcp_cong_avoid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void cubictcp_cong_avoid(struct sock *sk, u32 ack, u32 acked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cubic.c (ffffffff81f26050)
Location: net/ipv4/tcp_cubic.c:324
Inline: False
```
**Symbols:**

```
ffffffff81f26050-ffffffff81f260e7: cubictcp_cong_avoid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void cubictcp_cong_avoid(struct sock *sk, u32 ack, u32 acked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cubic.c (ffffffff81f85950)
Location: net/ipv4/tcp_cubic.c:324
Inline: False
```
**Symbols:**

```
ffffffff81f85950-ffffffff81f859e7: cubictcp_cong_avoid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void cubictcp_cong_avoid(struct sock *sk, u32 ack, u32 acked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cubic.c (ffffffff8204c020)
Location: net/ipv4/tcp_cubic.c:324
Inline: False
```
**Symbols:**

```
ffffffff8204c020-ffffffff8204c0b7: cubictcp_cong_avoid (STB_LOCAL)
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
