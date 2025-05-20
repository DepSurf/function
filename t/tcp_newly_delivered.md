# Function: <code>tcp_newly_delivered</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
u32 tcp_newly_delivered(struct sock *sk, u32 prior_delivered, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff818fc570)
Location: net/ipv4/tcp_input.c:3549
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffff818fc570-ffffffff818fc5b2: tcp_newly_delivered (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
u32 tcp_newly_delivered(struct sock *sk, u32 prior_delivered, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8192a5b0)
Location: net/ipv4/tcp_input.c:3542
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffff8192a5b0-ffffffff8192a5f2: tcp_newly_delivered (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
u32 tcp_newly_delivered(struct sock *sk, u32 prior_delivered, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8198d7a0)
Location: net/ipv4/tcp_input.c:3562
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffff8198d7a0-ffffffff8198d7e2: tcp_newly_delivered (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u32 tcp_newly_delivered(struct sock *sk, u32 prior_delivered, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819c4100)
Location: net/ipv4/tcp_input.c:3569
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffff819c4100-ffffffff819c4142: tcp_newly_delivered (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u32 tcp_newly_delivered(struct sock *sk, u32 prior_delivered, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81aaf780)
Location: net/ipv4/tcp_input.c:3554
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffff81aaf780-ffffffff81aaf7c4: tcp_newly_delivered (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u32 tcp_newly_delivered(struct sock *sk, u32 prior_delivered, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81aba7d0)
Location: net/ipv4/tcp_input.c:3674
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffff81aba7d0-ffffffff81aba80e: tcp_newly_delivered (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u32 tcp_newly_delivered(struct sock *sk, u32 prior_delivered, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81aa5ab0)
Location: net/ipv4/tcp_input.c:3681
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffff81aa5ab0-ffffffff81aa5aee: tcp_newly_delivered (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u32 tcp_newly_delivered(struct sock *sk, u32 prior_delivered, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81b61e00)
Location: net/ipv4/tcp_input.c:3715
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffff81b61e00-ffffffff81b61e3e: tcp_newly_delivered (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u32 tcp_newly_delivered(struct sock *sk, u32 prior_delivered, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81cf08d0)
Location: net/ipv4/tcp_input.c:3732
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffff81cf08d0-ffffffff81cf091b: tcp_newly_delivered (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u32 tcp_newly_delivered(struct sock *sk, u32 prior_delivered, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81eb4f70)
Location: net/ipv4/tcp_input.c:3745
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffff81eb4f70-ffffffff81eb4fbb: tcp_newly_delivered (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u32 tcp_newly_delivered(struct sock *sk, u32 prior_delivered, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81f133a0)
Location: net/ipv4/tcp_input.c:3750
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffff81f133a0-ffffffff81f133eb: tcp_newly_delivered (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u32 tcp_newly_delivered(struct sock *sk, u32 prior_delivered, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81fd7880)
Location: net/ipv4/tcp_input.c:3824
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffff81fd7880-ffffffff81fd78cb: tcp_newly_delivered (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
u32 tcp_newly_delivered(struct sock *sk, u32 prior_delivered, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffff800010c78c60)
Location: net/ipv4/tcp_input.c:3569
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffff800010c78c60-ffff800010c78d04: tcp_newly_delivered (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u32 tcp_newly_delivered(struct sock *sk, u32 prior_delivered, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (c0d85194)
Location: net/ipv4/tcp_input.c:3569
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
c0d85194-c0d85218: tcp_newly_delivered (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u32 tcp_newly_delivered(struct sock *sk, u32 prior_delivered, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (c000000000d7eb30)
Location: net/ipv4/tcp_input.c:3569
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
c000000000d7eb30-c000000000d7ec40: tcp_newly_delivered (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
u32 tcp_newly_delivered(struct sock *sk, u32 prior_delivered, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffe0007d9ba6)
Location: net/ipv4/tcp_input.c:3569
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffe0007d9ba6-ffffffe0007d9c54: tcp_newly_delivered (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
u32 tcp_newly_delivered(struct sock *sk, u32 prior_delivered, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81963f70)
Location: net/ipv4/tcp_input.c:3569
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffff81963f70-ffffffff81963fb2: tcp_newly_delivered (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u32 tcp_newly_delivered(struct sock *sk, u32 prior_delivered, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8191da60)
Location: net/ipv4/tcp_input.c:3569
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffff8191da60-ffffffff8191daa2: tcp_newly_delivered (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u32 tcp_newly_delivered(struct sock *sk, u32 prior_delivered, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819ce740)
Location: net/ipv4/tcp_input.c:3569
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffff819ce740-ffffffff819ce782: tcp_newly_delivered (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u32 tcp_newly_delivered(struct sock *sk, u32 prior_delivered, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819d82d0)
Location: net/ipv4/tcp_input.c:3569
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffff819d82d0-ffffffff819d8312: tcp_newly_delivered (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
