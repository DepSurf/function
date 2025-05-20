# Function: <code>tcp_rack_skb_timeout</code>

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
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
s32 tcp_rack_skb_timeout(struct tcp_sock *tp, struct sk_buff *skb, u32 reo_wnd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_recovery.c (ffffffff81916ee8)
Location: net/ipv4/tcp_recovery.c:50
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
Direct callers:
  - net/ipv4/tcp_input.c:tcp_enter_loss
```
**Symbols:**

```
ffffffff81916f80-ffffffff81916fa9: tcp_rack_skb_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
s32 tcp_rack_skb_timeout(struct tcp_sock *tp, struct sk_buff *skb, u32 reo_wnd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_recovery.c (ffffffff819456d6)
Location: net/ipv4/tcp_recovery.c:50
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
Direct callers:
  - net/ipv4/tcp_input.c:tcp_enter_loss
```
**Symbols:**

```
ffffffff81945770-ffffffff819457b8: tcp_rack_skb_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
s32 tcp_rack_skb_timeout(struct tcp_sock *tp, struct sk_buff *skb, u32 reo_wnd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_recovery.c (ffffffff819a9cda)
Location: net/ipv4/tcp_recovery.c:50
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
Direct callers:
  - net/ipv4/tcp_input.c:tcp_enter_loss
```
**Symbols:**

```
ffffffff819a9d70-ffffffff819a9db6: tcp_rack_skb_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
s32 tcp_rack_skb_timeout(struct tcp_sock *tp, struct sk_buff *skb, u32 reo_wnd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_recovery.c (ffffffff819e099a)
Location: net/ipv4/tcp_recovery.c:50
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
Direct callers:
  - net/ipv4/tcp_input.c:tcp_enter_loss
```
**Symbols:**

```
ffffffff819e0a30-ffffffff819e0a76: tcp_rack_skb_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
s32 tcp_rack_skb_timeout(struct tcp_sock *tp, struct sk_buff *skb, u32 reo_wnd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_recovery.c (ffffffff81acdf15)
Location: net/ipv4/tcp_recovery.c:50
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
Direct callers:
  - net/ipv4/tcp_input.c:tcp_timeout_mark_lost
```
**Symbols:**

```
ffffffff81ace020-ffffffff81ace066: tcp_rack_skb_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
s32 tcp_rack_skb_timeout(struct tcp_sock *tp, struct sk_buff *skb, u32 reo_wnd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_recovery.c (ffffffff81ad9f7a)
Location: net/ipv4/tcp_recovery.c:36
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
Direct callers:
  - net/ipv4/tcp_input.c:tcp_timeout_mark_lost
```
**Symbols:**

```
ffffffff81ada010-ffffffff81ada056: tcp_rack_skb_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
s32 tcp_rack_skb_timeout(struct tcp_sock *tp, struct sk_buff *skb, u32 reo_wnd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_recovery.c (ffffffff81ac4fd3)
Location: net/ipv4/tcp_recovery.c:36
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
Direct callers:
  - net/ipv4/tcp_input.c:tcp_enter_loss
```
**Symbols:**

```
ffffffff81ac5060-ffffffff81ac50a9: tcp_rack_skb_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
s32 tcp_rack_skb_timeout(struct tcp_sock *tp, struct sk_buff *skb, u32 reo_wnd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_recovery.c (ffffffff81b837e3)
Location: net/ipv4/tcp_recovery.c:36
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
Direct callers:
  - net/ipv4/tcp_input.c:tcp_enter_loss
```
**Symbols:**

```
ffffffff81b83870-ffffffff81b838b9: tcp_rack_skb_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
s32 tcp_rack_skb_timeout(struct tcp_sock *tp, struct sk_buff *skb, u32 reo_wnd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_recovery.c (ffffffff81d13ec3)
Location: net/ipv4/tcp_recovery.c:32
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
Direct callers:
  - net/ipv4/tcp_input.c:tcp_enter_loss
```
**Symbols:**

```
ffffffff81d13f50-ffffffff81d13fa2: tcp_rack_skb_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
s32 tcp_rack_skb_timeout(struct tcp_sock *tp, struct sk_buff *skb, u32 reo_wnd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_recovery.c (ffffffff81ed9ee3)
Location: net/ipv4/tcp_recovery.c:32
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
Direct callers:
  - net/ipv4/tcp_input.c:tcp_enter_loss
```
**Symbols:**

```
ffffffff81ed9f80-ffffffff81ed9fd2: tcp_rack_skb_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
s32 tcp_rack_skb_timeout(struct tcp_sock *tp, struct sk_buff *skb, u32 reo_wnd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_recovery.c (ffffffff81f38fc3)
Location: net/ipv4/tcp_recovery.c:32
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
Direct callers:
  - net/ipv4/tcp_input.c:tcp_enter_loss
```
**Symbols:**

```
ffffffff81f39060-ffffffff81f390b2: tcp_rack_skb_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
s32 tcp_rack_skb_timeout(struct tcp_sock *tp, struct sk_buff *skb, u32 reo_wnd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_recovery.c (ffffffff81fff0a3)
Location: net/ipv4/tcp_recovery.c:32
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
Direct callers:
  - net/ipv4/tcp_input.c:tcp_enter_loss
```
**Symbols:**

```
ffffffff81fff140-ffffffff81fff192: tcp_rack_skb_timeout (STB_GLOBAL)
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
s32 tcp_rack_skb_timeout(struct tcp_sock *tp, struct sk_buff *skb, u32 reo_wnd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_recovery.c (ffff800010c94778)
Location: net/ipv4/tcp_recovery.c:50
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
Direct callers:
  - net/ipv4/tcp_input.c:tcp_enter_loss
```
**Symbols:**

```
ffff800010c94818-ffff800010c94880: tcp_rack_skb_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
s32 tcp_rack_skb_timeout(struct tcp_sock *tp, struct sk_buff *skb, u32 reo_wnd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_recovery.c (c0da2e8c)
Location: net/ipv4/tcp_recovery.c:50
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
```
**Symbols:**

```
c0da2e8c-c0da2f28: tcp_rack_skb_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
s32 tcp_rack_skb_timeout(struct tcp_sock *tp, struct sk_buff *skb, u32 reo_wnd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_recovery.c (c000000000da4f90)
Location: net/ipv4/tcp_recovery.c:50
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
Direct callers:
  - net/ipv4/tcp_input.c:tcp_enter_loss
```
**Symbols:**

```
c000000000da5040-c000000000da5094: tcp_rack_skb_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
s32 tcp_rack_skb_timeout(struct tcp_sock *tp, struct sk_buff *skb, u32 reo_wnd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_recovery.c (ffffffe0007f3b96)
Location: net/ipv4/tcp_recovery.c:50
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
Direct callers:
  - net/ipv4/tcp_input.c:tcp_enter_loss
```
**Symbols:**

```
ffffffe0007f3c10-ffffffe0007f3c60: tcp_rack_skb_timeout (STB_GLOBAL)
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
s32 tcp_rack_skb_timeout(struct tcp_sock *tp, struct sk_buff *skb, u32 reo_wnd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_recovery.c (ffffffff8198080a)
Location: net/ipv4/tcp_recovery.c:50
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
Direct callers:
  - net/ipv4/tcp_input.c:tcp_enter_loss
```
**Symbols:**

```
ffffffff819808a0-ffffffff819808e6: tcp_rack_skb_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
s32 tcp_rack_skb_timeout(struct tcp_sock *tp, struct sk_buff *skb, u32 reo_wnd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_recovery.c (ffffffff8193a2ca)
Location: net/ipv4/tcp_recovery.c:50
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
Direct callers:
  - net/ipv4/tcp_input.c:tcp_enter_loss
```
**Symbols:**

```
ffffffff8193a360-ffffffff8193a3a6: tcp_rack_skb_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
s32 tcp_rack_skb_timeout(struct tcp_sock *tp, struct sk_buff *skb, u32 reo_wnd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_recovery.c (ffffffff819eafda)
Location: net/ipv4/tcp_recovery.c:50
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
Direct callers:
  - net/ipv4/tcp_input.c:tcp_enter_loss
```
**Symbols:**

```
ffffffff819eb070-ffffffff819eb0b6: tcp_rack_skb_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
s32 tcp_rack_skb_timeout(struct tcp_sock *tp, struct sk_buff *skb, u32 reo_wnd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_recovery.c (ffffffff819f4e5a)
Location: net/ipv4/tcp_recovery.c:50
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
Direct callers:
  - net/ipv4/tcp_input.c:tcp_enter_loss
```
**Symbols:**

```
ffffffff819f4ef0-ffffffff819f4f36: tcp_rack_skb_timeout (STB_GLOBAL)
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
