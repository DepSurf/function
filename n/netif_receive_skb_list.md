# Function: <code>netif_receive_skb_list</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void netif_receive_skb_list(struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818b7ee0)
Location: net/core/dev.c:5278
Inline: False
```
**Symbols:**

```
ffffffff818b7ee0-ffffffff818b82f5: netif_receive_skb_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void netif_receive_skb_list(struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81904130)
Location: net/core/dev.c:5288
Inline: False
```
**Symbols:**

```
ffffffff81904130-ffffffff819044ab: netif_receive_skb_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void netif_receive_skb_list(struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81935540)
Location: net/core/dev.c:5190
Inline: False
```
**Symbols:**

```
ffffffff81935540-ffffffff8193560b: netif_receive_skb_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void netif_receive_skb_list(struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a0a210)
Location: net/core/dev.c:5573
Inline: False
```
**Symbols:**

```
ffffffff81a0a210-ffffffff81a0a2db: netif_receive_skb_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void netif_receive_skb_list(struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a0b7c0)
Location: net/core/dev.c:5630
Inline: False
```
**Symbols:**

```
ffffffff81a0b7c0-ffffffff81a0b866: netif_receive_skb_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void netif_receive_skb_list(struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819f1d10)
Location: net/core/dev.c:5754
Inline: False
Direct callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
**Symbols:**

```
ffffffff819f1d10-ffffffff819f1db6: netif_receive_skb_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void netif_receive_skb_list(struct list_head *head);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81aa3630)
Location: net/core/dev.c:5724
Inline: True
Direct callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
**Symbols:**

```
ffffffff81aa3630-ffffffff81aa36cd: netif_receive_skb_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void netif_receive_skb_list(struct list_head *head);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dev.c (ffffffff81c1bd60)
Location: net/core/dev.c:5761
Inline: True
Direct callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
**Symbols:**

```
ffffffff81c1bd60-ffffffff81c1be28: netif_receive_skb_list.part.0 (STB_LOCAL)
ffffffff81c1be30-ffffffff81c1be59: netif_receive_skb_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void netif_receive_skb_list(struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81dccd40)
Location: net/core/dev.c:5752
Inline: False
Direct callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
**Symbols:**

```
ffffffff81dccd40-ffffffff81dcce18: netif_receive_skb_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void netif_receive_skb_list(struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81e3d8a0)
Location: net/core/dev.c:5728
Inline: False
Direct callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
**Symbols:**

```
ffffffff81e3d8a0-ffffffff81e3d978: netif_receive_skb_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void netif_receive_skb_list(struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81efc140)
Location: net/core/dev.c:5810
Inline: False
Direct callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
**Symbols:**

```
ffffffff81efc140-ffffffff81efc218: netif_receive_skb_list (STB_GLOBAL)
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
void netif_receive_skb_list(struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffff800010bd37d8)
Location: net/core/dev.c:5190
Inline: False
```
**Symbols:**

```
ffff800010bd37d8-ffff800010bd392c: netif_receive_skb_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void netif_receive_skb_list(struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c0cee51c)
Location: net/core/dev.c:5190
Inline: False
```
**Symbols:**

```
c0cee51c-c0cee668: netif_receive_skb_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void netif_receive_skb_list(struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c000000000cb2460)
Location: net/core/dev.c:5190
Inline: False
```
**Symbols:**

```
c000000000cb2460-c000000000cb25f8: netif_receive_skb_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void netif_receive_skb_list(struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffe00075d9cc)
Location: net/core/dev.c:5190
Inline: False
```
**Symbols:**

```
ffffffe00075d9cc-ffffffe00075dad0: netif_receive_skb_list (STB_GLOBAL)
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
void netif_receive_skb_list(struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818d5510)
Location: net/core/dev.c:5190
Inline: False
```
**Symbols:**

```
ffffffff818d5510-ffffffff818d55db: netif_receive_skb_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void netif_receive_skb_list(struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8188f380)
Location: net/core/dev.c:5190
Inline: False
```
**Symbols:**

```
ffffffff8188f380-ffffffff8188f44b: netif_receive_skb_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void netif_receive_skb_list(struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81926540)
Location: net/core/dev.c:5190
Inline: False
```
**Symbols:**

```
ffffffff81926540-ffffffff8192660b: netif_receive_skb_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void netif_receive_skb_list(struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81947af0)
Location: net/core/dev.c:5190
Inline: False
```
**Symbols:**

```
ffffffff81947af0-ffffffff81947beb: netif_receive_skb_list (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
