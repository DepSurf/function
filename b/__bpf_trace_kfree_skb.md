# Function: <code>__bpf_trace_kfree_skb</code>

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
void __bpf_trace_kfree_skb(void *__data, struct sk_buff *skb, void *location);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff818c35e0)
Location: include/trace/events/skb.h:15
Inline: False
```
**Symbols:**

```
ffffffff818c35e0-ffffffff818c35eb: __bpf_trace_kfree_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __bpf_trace_kfree_skb(void *__data, struct sk_buff *skb, void *location);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff818ec4c0)
Location: include/trace/events/skb.h:15
Inline: False
```
**Symbols:**

```
ffffffff818ec4c0-ffffffff818ec4cb: __bpf_trace_kfree_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __bpf_trace_kfree_skb(void *__data, struct sk_buff *skb, void *location);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff8193c3d0)
Location: include/trace/events/skb.h:15
Inline: False
```
**Symbols:**

```
ffffffff8193c3d0-ffffffff8193c3db: __bpf_trace_kfree_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __bpf_trace_kfree_skb(void *__data, struct sk_buff *skb, void *location);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff8196f260)
Location: include/trace/events/skb.h:15
Inline: False
```
**Symbols:**

```
ffffffff8196f260-ffffffff8196f26b: __bpf_trace_kfree_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_kfree_skb(void *__data, struct sk_buff *skb, void *location);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff81a43230)
Location: include/trace/events/skb.h:15
Inline: True
```
**Symbols:**

```
ffffffff81a43230-ffffffff81a4323b: __bpf_trace_kfree_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_kfree_skb(void *__data, struct sk_buff *skb, void *location);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff81a46cd0)
Location: include/trace/events/skb.h:15
Inline: True
```
**Symbols:**

```
ffffffff81a46cd0-ffffffff81a46cdb: __bpf_trace_kfree_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_kfree_skb(void *__data, struct sk_buff *skb, void *location);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff81a2b970)
Location: include/trace/events/skb.h:15
Inline: True
```
**Symbols:**

```
ffffffff81a2b970-ffffffff81a2b97b: __bpf_trace_kfree_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_kfree_skb(void *__data, struct sk_buff *skb, void *location);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff81ae09f0)
Location: include/trace/events/skb.h:15
Inline: True
```
**Symbols:**

```
ffffffff81ae09f0-ffffffff81ae09fb: __bpf_trace_kfree_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __bpf_trace_kfree_skb(void *__data, struct sk_buff *skb, void *location, enum skb_drop_reason reason);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff81c641b0)
Location: include/trace/events/skb.h:101
Inline: False
```
**Symbols:**

```
ffffffff81c641b0-ffffffff81c641c9: __bpf_trace_kfree_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __bpf_trace_kfree_skb(void *__data, struct sk_buff *skb, void *location, enum skb_drop_reason reason);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff81e1b200)
Location: include/trace/events/skb.h:24
Inline: False
```
**Symbols:**

```
ffffffff81e1b200-ffffffff81e1b219: __bpf_trace_kfree_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __bpf_trace_kfree_skb(void *__data, struct sk_buff *skb, void *location, enum skb_drop_reason reason);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff81e8f5c0)
Location: include/trace/events/skb.h:24
Inline: False
```
**Symbols:**

```
ffffffff81e8f5c0-ffffffff81e8f5d9: __bpf_trace_kfree_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __bpf_trace_kfree_skb(void *__data, struct sk_buff *skb, void *location, enum skb_drop_reason reason);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff81f515d0)
Location: include/trace/events/skb.h:24
Inline: False
```
**Symbols:**

```
ffffffff81f515d0-ffffffff81f515e9: __bpf_trace_kfree_skb (STB_LOCAL)
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
void __bpf_trace_kfree_skb(void *__data, struct sk_buff *skb, void *location);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffff800010c14d08)
Location: include/trace/events/skb.h:15
Inline: False
```
**Symbols:**

```
ffff800010c14d08-ffff800010c14d1c: __bpf_trace_kfree_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __bpf_trace_kfree_skb(void *__data, struct sk_buff *skb, void *location);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (c0d2d590)
Location: include/trace/events/skb.h:15
Inline: False
```
**Symbols:**

```
c0d2d590-c0d2d5b8: __bpf_trace_kfree_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __bpf_trace_kfree_skb(void *__data, struct sk_buff *skb, void *location);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (c000000000d03ea0)
Location: include/trace/events/skb.h:15
Inline: False
```
**Symbols:**

```
c000000000d03ea0-c000000000d03ecc: __bpf_trace_kfree_skb (STB_LOCAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void __bpf_trace_kfree_skb(void *__data, struct sk_buff *skb, void *location);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff8190f230)
Location: include/trace/events/skb.h:15
Inline: False
```
**Symbols:**

```
ffffffff8190f230-ffffffff8190f23b: __bpf_trace_kfree_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __bpf_trace_kfree_skb(void *__data, struct sk_buff *skb, void *location);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff818c8ff0)
Location: include/trace/events/skb.h:15
Inline: False
```
**Symbols:**

```
ffffffff818c8ff0-ffffffff818c8ffb: __bpf_trace_kfree_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __bpf_trace_kfree_skb(void *__data, struct sk_buff *skb, void *location);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff81960260)
Location: include/trace/events/skb.h:15
Inline: False
```
**Symbols:**

```
ffffffff81960260-ffffffff8196026b: __bpf_trace_kfree_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __bpf_trace_kfree_skb(void *__data, struct sk_buff *skb, void *location);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff819824d0)
Location: include/trace/events/skb.h:15
Inline: False
```
**Symbols:**

```
ffffffff819824d0-ffffffff819824db: __bpf_trace_kfree_skb (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>enum skb_drop_reason reason</code>
</li>
</ul>
</details>
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
