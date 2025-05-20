# Function: <code>tcp_collapse</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void tcp_collapse(struct sock *sk, struct sk_buff_head *list, struct sk_buff *head, struct sk_buff *tail, u32 start, u32 end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8176e4a0)
Location: net/ipv4/tcp_input.c:4677
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
```
**Symbols:**

```
ffffffff8176e4a0-ffffffff8176e82f: tcp_collapse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void tcp_collapse(struct sock *sk, struct sk_buff_head *list, struct sk_buff *head, struct sk_buff *tail, u32 start, u32 end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff817da440)
Location: net/ipv4/tcp_input.c:4740
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
```
**Symbols:**

```
ffffffff817da440-ffffffff817da7f6: tcp_collapse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void tcp_collapse(struct sock *sk, struct sk_buff_head *list, struct rb_root *root, struct sk_buff *head, struct sk_buff *tail, u32 start, u32 end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81808dc0)
Location: net/ipv4/tcp_input.c:4802
Inline: False
```
**Symbols:**

```
ffffffff81808dc0-ffffffff81809172: tcp_collapse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void tcp_collapse(struct sock *sk, struct sk_buff_head *list, struct rb_root *root, struct sk_buff *head, struct sk_buff *tail, u32 start, u32 end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff818290a0)
Location: net/ipv4/tcp_input.c:4762
Inline: False
```
**Symbols:**

```
ffffffff818290a0-ffffffff81829432: tcp_collapse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void tcp_collapse(struct sock *sk, struct sk_buff_head *list, struct rb_root *root, struct sk_buff *head, struct sk_buff *tail, u32 start, u32 end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff818ae0b0)
Location: net/ipv4/tcp_input.c:4721
Inline: False
```
**Symbols:**

```
ffffffff818ae0b0-ffffffff818ae432: tcp_collapse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void tcp_collapse(struct sock *sk, struct sk_buff_head *list, struct rb_root *root, struct sk_buff *head, struct sk_buff *tail, u32 start, u32 end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81903760)
Location: net/ipv4/tcp_input.c:4830
Inline: False
```
**Symbols:**

```
ffffffff81903760-ffffffff81903aea: tcp_collapse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void tcp_collapse(struct sock *sk, struct sk_buff_head *list, struct rb_root *root, struct sk_buff *head, struct sk_buff *tail, u32 start, u32 end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81931900)
Location: net/ipv4/tcp_input.c:4854
Inline: False
```
**Symbols:**

```
ffffffff81931900-ffffffff81931cb9: tcp_collapse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void tcp_collapse(struct sock *sk, struct sk_buff_head *list, struct rb_root *root, struct sk_buff *head, struct sk_buff *tail, u32 start, u32 end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81995000)
Location: net/ipv4/tcp_input.c:4861
Inline: False
```
**Symbols:**

```
ffffffff81995000-ffffffff819953b6: tcp_collapse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void tcp_collapse(struct sock *sk, struct sk_buff_head *list, struct rb_root *root, struct sk_buff *head, struct sk_buff *tail, u32 start, u32 end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819cbb50)
Location: net/ipv4/tcp_input.c:4912
Inline: False
```
**Symbols:**

```
ffffffff819cbb50-ffffffff819cbf06: tcp_collapse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void tcp_collapse(struct sock *sk, struct sk_buff_head *list, struct rb_root *root, struct sk_buff *head, struct sk_buff *tail, u32 start, u32 end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81ab1d40)
Location: net/ipv4/tcp_input.c:4953
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_prune_queue
  - net/ipv4/tcp_input.c:tcp_collapse_ofo_queue
```
**Symbols:**

```
ffffffff81ab1d40-ffffffff81ab22c5: tcp_collapse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void tcp_collapse(struct sock *sk, struct sk_buff_head *list, struct rb_root *root, struct sk_buff *head, struct sk_buff *tail, u32 start, u32 end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81abcd00)
Location: net/ipv4/tcp_input.c:5092
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_prune_queue
  - net/ipv4/tcp_input.c:tcp_collapse_ofo_queue
```
**Symbols:**

```
ffffffff81abcd00-ffffffff81abd28b: tcp_collapse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void tcp_collapse(struct sock *sk, struct sk_buff_head *list, struct rb_root *root, struct sk_buff *head, struct sk_buff *tail, u32 start, u32 end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81aa7b10)
Location: net/ipv4/tcp_input.c:5100
Inline: False
```
**Symbols:**

```
ffffffff81aa7b10-ffffffff81aa80b7: tcp_collapse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void tcp_collapse(struct sock *sk, struct sk_buff_head *list, struct rb_root *root, struct sk_buff *head, struct sk_buff *tail, u32 start, u32 end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (0)
Location: net/ipv4/tcp_input.c:5134
Inline: False
```
**Symbols:**

```
ffffffff81b64020-ffffffff81b645e1: tcp_collapse (STB_LOCAL)
ffffffff81d3a7ca-ffffffff81d3a82a: tcp_collapse.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void tcp_collapse(struct sock *sk, struct sk_buff_head *list, struct rb_root *root, struct sk_buff *head, struct sk_buff *tail, u32 start, u32 end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (0)
Location: net/ipv4/tcp_input.c:5164
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
```
**Symbols:**

```
ffffffff81cf2da0-ffffffff81cf33af: tcp_collapse (STB_LOCAL)
ffffffff81f06ff9-ffffffff81f0704d: tcp_collapse.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void tcp_collapse(struct sock *sk, struct sk_buff_head *list, struct rb_root *root, struct sk_buff *head, struct sk_buff *tail, u32 start, u32 end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (0)
Location: net/ipv4/tcp_input.c:5177
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
```
**Symbols:**

```
ffffffff81eb73d0-ffffffff81eb79df: tcp_collapse (STB_LOCAL)
ffffffff820aea9e-ffffffff820aeaf2: tcp_collapse.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void tcp_collapse(struct sock *sk, struct sk_buff_head *list, struct rb_root *root, struct sk_buff *head, struct sk_buff *tail, u32 start, u32 end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (0)
Location: net/ipv4/tcp_input.c:5182
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
```
**Symbols:**

```
ffffffff81f15ab0-ffffffff81f160c5: tcp_collapse (STB_LOCAL)
ffffffff8212ff3c-ffffffff8212ff90: tcp_collapse.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void tcp_collapse(struct sock *sk, struct sk_buff_head *list, struct rb_root *root, struct sk_buff *head, struct sk_buff *tail, u32 start, u32 end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81fd9e70)
Location: net/ipv4/tcp_input.c:5320
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
```
**Symbols:**

```
ffffffff81fd9e70-ffffffff81fda45f: tcp_collapse (STB_LOCAL)
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
void tcp_collapse(struct sock *sk, struct sk_buff_head *list, struct rb_root *root, struct sk_buff *head, struct sk_buff *tail, u32 start, u32 end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffff800010c7e7a0)
Location: net/ipv4/tcp_input.c:4912
Inline: False
```
**Symbols:**

```
ffff800010c7e7a0-ffff800010c7eb68: tcp_collapse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void tcp_collapse(struct sock *sk, struct sk_buff_head *list, struct rb_root *root, struct sk_buff *head, struct sk_buff *tail, u32 start, u32 end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (c0d8d798)
Location: net/ipv4/tcp_input.c:4912
Inline: False
```
**Symbols:**

```
c0d8d798-c0d8dba0: tcp_collapse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void tcp_collapse(struct sock *sk, struct sk_buff_head *list, struct rb_root *root, struct sk_buff *head, struct sk_buff *tail, u32 start, u32 end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (c000000000d88ab0)
Location: net/ipv4/tcp_input.c:4912
Inline: False
```
**Symbols:**

```
c000000000d88ab0-c000000000d88fd8: tcp_collapse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void tcp_collapse(struct sock *sk, struct sk_buff_head *list, struct rb_root *root, struct sk_buff *head, struct sk_buff *tail, u32 start, u32 end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffe0007e0afa)
Location: net/ipv4/tcp_input.c:4912
Inline: False
```
**Symbols:**

```
ffffffe0007e0afa-ffffffe0007e0dd6: tcp_collapse (STB_LOCAL)
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
void tcp_collapse(struct sock *sk, struct sk_buff_head *list, struct rb_root *root, struct sk_buff *head, struct sk_buff *tail, u32 start, u32 end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8196b9c0)
Location: net/ipv4/tcp_input.c:4912
Inline: False
```
**Symbols:**

```
ffffffff8196b9c0-ffffffff8196bd76: tcp_collapse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void tcp_collapse(struct sock *sk, struct sk_buff_head *list, struct rb_root *root, struct sk_buff *head, struct sk_buff *tail, u32 start, u32 end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819254b0)
Location: net/ipv4/tcp_input.c:4912
Inline: False
```
**Symbols:**

```
ffffffff819254b0-ffffffff81925866: tcp_collapse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void tcp_collapse(struct sock *sk, struct sk_buff_head *list, struct rb_root *root, struct sk_buff *head, struct sk_buff *tail, u32 start, u32 end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819d6190)
Location: net/ipv4/tcp_input.c:4912
Inline: False
```
**Symbols:**

```
ffffffff819d6190-ffffffff819d6546: tcp_collapse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void tcp_collapse(struct sock *sk, struct sk_buff_head *list, struct rb_root *root, struct sk_buff *head, struct sk_buff *tail, u32 start, u32 end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819dfdb0)
Location: net/ipv4/tcp_input.c:4912
Inline: False
```
**Symbols:**

```
ffffffff819dfdb0-ffffffff819e0166: tcp_collapse (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct rb_root *root</code>
</li>
<li>
<b>Param reordered. </b>
<code>sk, list, head, tail, start, end</code> ➡️ <code>sk, list, root, head, tail, start, end</code>
</li>
</ul>
</details>
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
