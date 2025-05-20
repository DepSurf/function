# Function: <code>__unregister_prot_hook</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void __unregister_prot_hook(struct sock *sk, bool sync);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81803c60)
Location: net/packet/af_packet.c:362
Inline: True
Direct callers:
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_release
```
**Symbols:**

```
ffffffff81803c60-ffffffff81803d29: __unregister_prot_hook (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void __unregister_prot_hook(struct sock *sk, bool sync);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81874bc0)
Location: net/packet/af_packet.c:363
Inline: True
Direct callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_release
```
**Symbols:**

```
ffffffff81874bc0-ffffffff81874c89: __unregister_prot_hook (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void __unregister_prot_hook(struct sock *sk, bool sync);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff818a90d0)
Location: net/packet/af_packet.c:362
Inline: True
Direct callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_release
```
**Symbols:**

```
ffffffff818a90d0-ffffffff818a91ab: __unregister_prot_hook (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void __unregister_prot_hook(struct sock *sk, bool sync);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff818cfb10)
Location: net/packet/af_packet.c:362
Inline: True
Direct callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_release
```
**Symbols:**

```
ffffffff818cfb10-ffffffff818cfbf7: __unregister_prot_hook (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __unregister_prot_hook(struct sock *sk, bool sync);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81953cf0)
Location: net/packet/af_packet.c:357
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_release
```
**Symbols:**

```
ffffffff81953cf0-ffffffff81953de3: __unregister_prot_hook (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __unregister_prot_hook(struct sock *sk, bool sync);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff819b09b0)
Location: net/packet/af_packet.c:331
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_release
```
**Symbols:**

```
ffffffff819b09b0-ffffffff819b0ac1: __unregister_prot_hook (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __unregister_prot_hook(struct sock *sk, bool sync);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff819e5da0)
Location: net/packet/af_packet.c:332
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_release
```
**Symbols:**

```
ffffffff819e5da0-ffffffff819e5eb1: __unregister_prot_hook (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __unregister_prot_hook(struct sock *sk, bool sync);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81a55800)
Location: net/packet/af_packet.c:324
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_release
```
**Symbols:**

```
ffffffff81a55800-ffffffff81a558f5: __unregister_prot_hook (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __unregister_prot_hook(struct sock *sk, bool sync);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81a8c8d0)
Location: net/packet/af_packet.c:324
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_release
```
**Symbols:**

```
ffffffff81a8c8d0-ffffffff81a8c9c5: __unregister_prot_hook (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void __unregister_prot_hook(struct sock *sk, bool sync);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81b892f0)
Location: net/packet/af_packet.c:324
Inline: True
Direct callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_release
```
**Symbols:**

```
ffffffff81b892f0-ffffffff81b893f3: __unregister_prot_hook (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void __unregister_prot_hook(struct sock *sk, bool sync);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81b98df0)
Location: net/packet/af_packet.c:328
Inline: True
Direct callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_release
```
**Symbols:**

```
ffffffff81b98df0-ffffffff81b98ef5: __unregister_prot_hook (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void __unregister_prot_hook(struct sock *sk, bool sync);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81b88200)
Location: net/packet/af_packet.c:328
Inline: True
Direct callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_release
```
**Symbols:**

```
ffffffff81b88200-ffffffff81b88301: __unregister_prot_hook (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void __unregister_prot_hook(struct sock *sk, bool sync);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81c54310)
Location: net/packet/af_packet.c:329
Inline: True
Direct callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_release
```
**Symbols:**

```
ffffffff81c54310-ffffffff81c54412: __unregister_prot_hook (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void __unregister_prot_hook(struct sock *sk, bool sync);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81df1eb0)
Location: net/packet/af_packet.c:365
Inline: True
Direct callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_release
```
**Symbols:**

```
ffffffff81df1eb0-ffffffff81df1fce: __unregister_prot_hook (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void __unregister_prot_hook(struct sock *sk, bool sync);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81fc5f70)
Location: net/packet/af_packet.c:365
Inline: True
Direct callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_release
```
**Symbols:**

```
ffffffff81fc5f70-ffffffff81fc608e: __unregister_prot_hook (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void __unregister_prot_hook(struct sock *sk, bool sync);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff82026aa0)
Location: net/packet/af_packet.c:363
Inline: True
Direct callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_release
```
**Symbols:**

```
ffffffff82026aa0-ffffffff82026bbc: __unregister_prot_hook (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void __unregister_prot_hook(struct sock *sk, bool sync);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff820f64b0)
Location: net/packet/af_packet.c:363
Inline: True
Direct callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_release
```
**Symbols:**

```
ffffffff820f64b0-ffffffff820f65cc: __unregister_prot_hook (STB_LOCAL)
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
void __unregister_prot_hook(struct sock *sk, bool sync);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffff800010d5a590)
Location: net/packet/af_packet.c:324
Inline: True
Direct callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_release
```
**Symbols:**

```
ffff800010d5a590-ffff800010d5a6f0: __unregister_prot_hook (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void __unregister_prot_hook(struct sock *sk, bool sync);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (c0e578e0)
Location: net/packet/af_packet.c:324
Inline: True
Direct callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_release
```
**Symbols:**

```
c0e578e0-c0e579e0: __unregister_prot_hook (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void __unregister_prot_hook(struct sock *sk, bool sync);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (c000000000e90840)
Location: net/packet/af_packet.c:324
Inline: True
Direct callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_release
```
**Symbols:**

```
c000000000e90840-c000000000e90a38: __unregister_prot_hook (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void __unregister_prot_hook(struct sock *sk, bool sync);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffe0008907ea)
Location: net/packet/af_packet.c:324
Inline: True
Direct callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_release
```
**Symbols:**

```
ffffffe0008907ea-ffffffe00089094c: __unregister_prot_hook (STB_LOCAL)
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
void __unregister_prot_hook(struct sock *sk, bool sync);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81a2bf60)
Location: net/packet/af_packet.c:324
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_release
```
**Symbols:**

```
ffffffff81a2bf60-ffffffff81a2c055: __unregister_prot_hook (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __unregister_prot_hook(struct sock *sk, bool sync);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff819e9150)
Location: net/packet/af_packet.c:324
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_release
```
**Symbols:**

```
ffffffff819e9150-ffffffff819e9245: __unregister_prot_hook (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __unregister_prot_hook(struct sock *sk, bool sync);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81a97b10)
Location: net/packet/af_packet.c:324
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_release
```
**Symbols:**

```
ffffffff81a97b10-ffffffff81a97c05: __unregister_prot_hook (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __unregister_prot_hook(struct sock *sk, bool sync);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81aa0ee0)
Location: net/packet/af_packet.c:324
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_release
```
**Symbols:**

```
ffffffff81aa0ee0-ffffffff81aa0fd1: __unregister_prot_hook (STB_LOCAL)
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
