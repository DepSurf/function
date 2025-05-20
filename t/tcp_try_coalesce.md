# Function: <code>tcp_try_coalesce</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
bool tcp_try_coalesce(struct sock *sk, struct sk_buff *to, struct sk_buff *from, bool *fragstolen);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8176bd60)
Location: net/ipv4/tcp_input.c:4250
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
```
**Symbols:**

```
ffffffff8176bd60-ffffffff8176be1d: tcp_try_coalesce (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
bool tcp_try_coalesce(struct sock *sk, struct sk_buff *to, struct sk_buff *from, bool *fragstolen);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff817d8210)
Location: net/ipv4/tcp_input.c:4308
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_queue_rcv
```
**Symbols:**

```
ffffffff817d8210-ffffffff817d82d2: tcp_try_coalesce (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
bool tcp_try_coalesce(struct sock *sk, struct sk_buff *to, struct sk_buff *from, bool *fragstolen);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81808630)
Location: net/ipv4/tcp_input.c:4324
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_queue_rcv
```
**Symbols:**

```
ffffffff81808630-ffffffff818086f2: tcp_try_coalesce (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
bool tcp_try_coalesce(struct sock *sk, struct sk_buff *to, struct sk_buff *from, bool *fragstolen);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81828c40)
Location: net/ipv4/tcp_input.c:4283
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_queue_rcv
```
**Symbols:**

```
ffffffff81828c40-ffffffff81828d02: tcp_try_coalesce (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool tcp_try_coalesce(struct sock *sk, struct sk_buff *to, struct sk_buff *from, bool *fragstolen);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff818a8140)
Location: net/ipv4/tcp_input.c:4254
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_queue_rcv
```
**Symbols:**

```
ffffffff818a8140-ffffffff818a821f: tcp_try_coalesce (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool tcp_try_coalesce(struct sock *sk, struct sk_buff *to, struct sk_buff *from, bool *fragstolen);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff818fd420)
Location: net/ipv4/tcp_input.c:4337
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_queue_rcv
```
**Symbols:**

```
ffffffff818fd420-ffffffff818fd4ff: tcp_try_coalesce (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool tcp_try_coalesce(struct sock *sk, struct sk_buff *to, struct sk_buff *from, bool *fragstolen);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8192b4e0)
Location: net/ipv4/tcp_input.c:4348
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_queue_rcv
```
**Symbols:**

```
ffffffff8192b4e0-ffffffff8192b5f3: tcp_try_coalesce (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool tcp_try_coalesce(struct sock *sk, struct sk_buff *to, struct sk_buff *from, bool *fragstolen);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8198e770)
Location: net/ipv4/tcp_input.c:4365
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_queue_rcv
```
**Symbols:**

```
ffffffff8198e770-ffffffff8198e886: tcp_try_coalesce (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool tcp_try_coalesce(struct sock *sk, struct sk_buff *to, struct sk_buff *from, bool *fragstolen);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819c54b0)
Location: net/ipv4/tcp_input.c:4415
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_queue_rcv
```
**Symbols:**

```
ffffffff819c54b0-ffffffff819c55c6: tcp_try_coalesce (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool tcp_try_coalesce(struct sock *sk, struct sk_buff *to, struct sk_buff *from, bool *fragstolen);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81ab0760)
Location: net/ipv4/tcp_input.c:4441
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_ofo_queue
```
**Symbols:**

```
ffffffff81ab0760-ffffffff81ab084c: tcp_try_coalesce.part.0 (STB_LOCAL)
ffffffff81ab1b80-ffffffff81ab1c20: tcp_try_coalesce (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool tcp_try_coalesce(struct sock *sk, struct sk_buff *to, struct sk_buff *from, bool *fragstolen);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81abb740)
Location: net/ipv4/tcp_input.c:4579
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_ofo_queue
```
**Symbols:**

```
ffffffff81abb740-ffffffff81abb82c: tcp_try_coalesce.part.0 (STB_LOCAL)
ffffffff81abcb40-ffffffff81abcbe0: tcp_try_coalesce (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool tcp_try_coalesce(struct sock *sk, struct sk_buff *to, struct sk_buff *from, bool *fragstolen);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81aa80c0)
Location: net/ipv4/tcp_input.c:4589
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_ofo_queue
```
**Symbols:**

```
ffffffff81aa80c0-ffffffff81aa825c: tcp_try_coalesce (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool tcp_try_coalesce(struct sock *sk, struct sk_buff *to, struct sk_buff *from, bool *fragstolen);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81b63c70)
Location: net/ipv4/tcp_input.c:4623
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_ofo_queue
```
**Symbols:**

```
ffffffff81b63c70-ffffffff81b63e1a: tcp_try_coalesce (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool tcp_try_coalesce(struct sock *sk, struct sk_buff *to, struct sk_buff *from, bool *fragstolen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81cf2150)
Location: net/ipv4/tcp_input.c:4641
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_ofo_queue
```
**Symbols:**

```
ffffffff81cf2150-ffffffff81cf230b: tcp_try_coalesce (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool tcp_try_coalesce(struct sock *sk, struct sk_buff *to, struct sk_buff *from, bool *fragstolen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81eb67d0)
Location: net/ipv4/tcp_input.c:4654
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_ofo_queue
```
**Symbols:**

```
ffffffff81eb67d0-ffffffff81eb698b: tcp_try_coalesce (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool tcp_try_coalesce(struct sock *sk, struct sk_buff *to, struct sk_buff *from, bool *fragstolen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81f14bf0)
Location: net/ipv4/tcp_input.c:4659
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_ofo_queue
```
**Symbols:**

```
ffffffff81f14bf0-ffffffff81f14dac: tcp_try_coalesce (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool tcp_try_coalesce(struct sock *sk, struct sk_buff *to, struct sk_buff *from, bool *fragstolen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81fd9120)
Location: net/ipv4/tcp_input.c:4790
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_ofo_queue
```
**Symbols:**

```
ffffffff81fd9120-ffffffff81fd92e3: tcp_try_coalesce (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
bool tcp_try_coalesce(struct sock *sk, struct sk_buff *to, struct sk_buff *from, bool *fragstolen);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffff800010c79e10)
Location: net/ipv4/tcp_input.c:4415
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_queue_rcv
```
**Symbols:**

```
ffff800010c79e10-ffff800010c79f80: tcp_try_coalesce (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool tcp_try_coalesce(struct sock *sk, struct sk_buff *to, struct sk_buff *from, bool *fragstolen);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (c0d86654)
Location: net/ipv4/tcp_input.c:4415
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_queue_rcv
```
**Symbols:**

```
c0d86654-c0d867b0: tcp_try_coalesce (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool tcp_try_coalesce(struct sock *sk, struct sk_buff *to, struct sk_buff *from, bool *fragstolen);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (c000000000d80920)
Location: net/ipv4/tcp_input.c:4415
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_queue_rcv
```
**Symbols:**

```
c000000000d80920-c000000000d80af4: tcp_try_coalesce (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
bool tcp_try_coalesce(struct sock *sk, struct sk_buff *to, struct sk_buff *from, bool *fragstolen);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffe0007db1ae)
Location: net/ipv4/tcp_input.c:4415
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_queue_rcv
```
**Symbols:**

```
ffffffe0007db1ae-ffffffe0007db2b2: tcp_try_coalesce (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
bool tcp_try_coalesce(struct sock *sk, struct sk_buff *to, struct sk_buff *from, bool *fragstolen);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81965320)
Location: net/ipv4/tcp_input.c:4415
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_queue_rcv
```
**Symbols:**

```
ffffffff81965320-ffffffff81965436: tcp_try_coalesce (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool tcp_try_coalesce(struct sock *sk, struct sk_buff *to, struct sk_buff *from, bool *fragstolen);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8191ee10)
Location: net/ipv4/tcp_input.c:4415
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_queue_rcv
```
**Symbols:**

```
ffffffff8191ee10-ffffffff8191ef26: tcp_try_coalesce (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool tcp_try_coalesce(struct sock *sk, struct sk_buff *to, struct sk_buff *from, bool *fragstolen);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819cfaf0)
Location: net/ipv4/tcp_input.c:4415
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_queue_rcv
```
**Symbols:**

```
ffffffff819cfaf0-ffffffff819cfc06: tcp_try_coalesce (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool tcp_try_coalesce(struct sock *sk, struct sk_buff *to, struct sk_buff *from, bool *fragstolen);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819d9680)
Location: net/ipv4/tcp_input.c:4415
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_queue_rcv
```
**Symbols:**

```
ffffffff819d9680-ffffffff819d9796: tcp_try_coalesce (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
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
