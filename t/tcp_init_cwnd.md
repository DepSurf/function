# Function: <code>tcp_init_cwnd</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
__u32 tcp_init_cwnd(const struct tcp_sock *tp, const struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81770c30)
Location: net/ipv4/tcp_input.c:824
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_cwnd_restart
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
```
**Symbols:**

```
ffffffff81770c30-ffffffff81770c67: tcp_init_cwnd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
__u32 tcp_init_cwnd(const struct tcp_sock *tp, const struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff817dcba0)
Location: net/ipv4/tcp_input.c:826
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_cwnd_restart
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
```
**Symbols:**

```
ffffffff817dcba0-ffffffff817dcbd7: tcp_init_cwnd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
__u32 tcp_init_cwnd(const struct tcp_sock *tp, const struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8180cca0)
Location: net/ipv4/tcp_input.c:849
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_cwnd_restart
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
```
**Symbols:**

```
ffffffff8180cca0-ffffffff8180ccd7: tcp_init_cwnd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
__u32 tcp_init_cwnd(const struct tcp_sock *tp, const struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8182cf10)
Location: net/ipv4/tcp_input.c:856
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_cwnd_restart
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
```
**Symbols:**

```
ffffffff8182cf10-ffffffff8182cf47: tcp_init_cwnd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
__u32 tcp_init_cwnd(const struct tcp_sock *tp, const struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff818abe60)
Location: net/ipv4/tcp_input.c:839
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_cwnd_restart
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
```
**Symbols:**

```
ffffffff818abe60-ffffffff818abe97: tcp_init_cwnd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
__u32 tcp_init_cwnd(const struct tcp_sock *tp, const struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81901390)
Location: net/ipv4/tcp_input.c:866
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_cwnd_restart
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
```
**Symbols:**

```
ffffffff81901390-ffffffff819013c7: tcp_init_cwnd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
__u32 tcp_init_cwnd(const struct tcp_sock *tp, const struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8192f480)
Location: net/ipv4/tcp_input.c:851
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_cwnd_restart
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
```
**Symbols:**

```
ffffffff8192f480-ffffffff8192f4b7: tcp_init_cwnd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
__u32 tcp_init_cwnd(const struct tcp_sock *tp, const struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81996dc2)
Location: net/ipv4/tcp_input.c:861
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_init_transfer
Direct callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_cwnd_restart
```
**Symbols:**

```
ffffffff819929b0-ffffffff819929e7: tcp_init_cwnd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
__u32 tcp_init_cwnd(const struct tcp_sock *tp, const struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819cd942)
Location: net/ipv4/tcp_input.c:863
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_init_transfer
Direct callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_cwnd_restart
```
**Symbols:**

```
ffffffff819c94f0-ffffffff819c9527: tcp_init_cwnd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
__u32 tcp_init_cwnd(const struct tcp_sock *tp, const struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81ab9b12)
Location: net/ipv4/tcp_input.c:865
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_init_transfer
Direct callers:
  - net/ipv4/tcp_output.c:tcp_cwnd_validate
  - net/ipv4/tcp_output.c:tcp_cwnd_restart
```
**Symbols:**

```
ffffffff81ab56d0-ffffffff81ab5707: tcp_init_cwnd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
__u32 tcp_init_cwnd(const struct tcp_sock *tp, const struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81ac4f18)
Location: net/ipv4/tcp_input.c:929
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_init_transfer
Direct callers:
  - net/ipv4/tcp_output.c:tcp_cwnd_validate
  - net/ipv4/tcp_output.c:tcp_cwnd_restart
```
**Symbols:**

```
ffffffff81ac07d0-ffffffff81ac0807: tcp_init_cwnd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
__u32 tcp_init_cwnd(const struct tcp_sock *tp, const struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81ab0155)
Location: net/ipv4/tcp_input.c:929
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_init_transfer
Direct callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_cwnd_restart
```
**Symbols:**

```
ffffffff81aab690-ffffffff81aab6c5: tcp_init_cwnd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
__u32 tcp_init_cwnd(const struct tcp_sock *tp, const struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81b6cf44)
Location: net/ipv4/tcp_input.c:952
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_init_transfer
Direct callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_cwnd_restart
```
**Symbols:**

```
ffffffff81b67ad0-ffffffff81b67b05: tcp_init_cwnd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
__u32 tcp_init_cwnd(const struct tcp_sock *tp, const struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81cfc409)
Location: net/ipv4/tcp_input.c:961
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_init_transfer
Direct callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_cwnd_restart
```
**Symbols:**

```
ffffffff81cf6bb0-ffffffff81cf6bef: tcp_init_cwnd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
__u32 tcp_init_cwnd(const struct tcp_sock *tp, const struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81ec0f99)
Location: net/ipv4/tcp_input.c:960
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_init_transfer
Direct callers:
  - net/ipv4/tcp_output.c:tcp_cwnd_validate
  - net/ipv4/tcp_output.c:tcp_cwnd_restart
```
**Symbols:**

```
ffffffff81ebb5e0-ffffffff81ebb61f: tcp_init_cwnd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
__u32 tcp_init_cwnd(const struct tcp_sock *tp, const struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81f1f509)
Location: net/ipv4/tcp_input.c:959
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_init_transfer
Direct callers:
  - net/ipv4/tcp_output.c:tcp_cwnd_validate
  - net/ipv4/tcp_output.c:tcp_cwnd_restart
```
**Symbols:**

```
ffffffff81f19a60-ffffffff81f19a9f: tcp_init_cwnd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
__u32 tcp_init_cwnd(const struct tcp_sock *tp, const struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81fe3bc6)
Location: net/ipv4/tcp_input.c:993
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_init_transfer
Direct callers:
  - net/ipv4/tcp_output.c:tcp_cwnd_validate
  - net/ipv4/tcp_output.c:tcp_cwnd_restart
```
**Symbols:**

```
ffffffff81fde230-ffffffff81fde26f: tcp_init_cwnd (STB_GLOBAL)
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
__u32 tcp_init_cwnd(const struct tcp_sock *tp, const struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffff800010c804b4)
Location: net/ipv4/tcp_input.c:863
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_init_transfer
Direct callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_cwnd_restart
```
**Symbols:**

```
ffff800010c7c3d0-ffff800010c7c424: tcp_init_cwnd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
__u32 tcp_init_cwnd(const struct tcp_sock *tp, const struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (c0d8f704)
Location: net/ipv4/tcp_input.c:863
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_init_transfer
Direct callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_cwnd_restart
```
**Symbols:**

```
c0d8b350-c0d8b394: tcp_init_cwnd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
__u32 tcp_init_cwnd(const struct tcp_sock *tp, const struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (c000000000d8b064)
Location: net/ipv4/tcp_input.c:863
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_init_transfer
Direct callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_cwnd_restart
```
**Symbols:**

```
c000000000d85f10-c000000000d85f58: tcp_init_cwnd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
__u32 tcp_init_cwnd(const struct tcp_sock *tp, const struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffe0007e24ec)
Location: net/ipv4/tcp_input.c:863
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_init_transfer
Direct callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_cwnd_restart
```
**Symbols:**

```
ffffffe0007decf8-ffffffe0007ded38: tcp_init_cwnd (STB_GLOBAL)
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
__u32 tcp_init_cwnd(const struct tcp_sock *tp, const struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8196d7b2)
Location: net/ipv4/tcp_input.c:863
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_init_transfer
Direct callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_cwnd_restart
```
**Symbols:**

```
ffffffff81969360-ffffffff81969397: tcp_init_cwnd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
__u32 tcp_init_cwnd(const struct tcp_sock *tp, const struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819272a2)
Location: net/ipv4/tcp_input.c:863
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_init_transfer
Direct callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_cwnd_restart
```
**Symbols:**

```
ffffffff81922e50-ffffffff81922e87: tcp_init_cwnd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
__u32 tcp_init_cwnd(const struct tcp_sock *tp, const struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819d7f82)
Location: net/ipv4/tcp_input.c:863
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_init_transfer
Direct callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_cwnd_restart
```
**Symbols:**

```
ffffffff819d3b30-ffffffff819d3b67: tcp_init_cwnd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
__u32 tcp_init_cwnd(const struct tcp_sock *tp, const struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819e1bc2)
Location: net/ipv4/tcp_input.c:863
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_init_transfer
Direct callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_cwnd_restart
```
**Symbols:**

```
ffffffff819dd710-ffffffff819dd747: tcp_init_cwnd (STB_GLOBAL)
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
