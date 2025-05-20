# Function: <code>netif_receive_skb_list_internal</code>

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
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818b7f1f)
Location: net/core/dev.c:5191
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb_list
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8190416f)
Location: net/core/dev.c:5217
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb_list
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void netif_receive_skb_list_internal(struct list_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81935290)
Location: net/core/dev.c:5119
Inline: False
Direct callers:
  - net/core/dev.c:netif_receive_skb_list
```
**Symbols:**

```
ffffffff81935290-ffffffff81935539: netif_receive_skb_list_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void netif_receive_skb_list_internal(struct list_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a0a090)
Location: net/core/dev.c:5502
Inline: False
Direct callers:
  - net/core/dev.c:napi_poll
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:napi_complete_done
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:napi_gro_receive
  - net/core/dev.c:netif_receive_skb_list
```
**Symbols:**

```
ffffffff81a0a090-ffffffff81a0a20e: netif_receive_skb_list_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void netif_receive_skb_list_internal(struct list_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a0b630)
Location: net/core/dev.c:5559
Inline: False
Direct callers:
  - net/core/dev.c:napi_poll
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:napi_complete_done
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:napi_gro_receive
  - net/core/dev.c:netif_receive_skb_list
```
**Symbols:**

```
ffffffff81a0b630-ffffffff81a0b7b3: netif_receive_skb_list_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void netif_receive_skb_list_internal(struct list_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819f1a70)
Location: net/core/dev.c:5683
Inline: False
Direct callers:
  - net/core/dev.c:__napi_poll
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:napi_complete_done
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:napi_gro_receive
  - net/core/dev.c:netif_receive_skb_list
```
**Symbols:**

```
ffffffff819f1a70-ffffffff819f1d0b: netif_receive_skb_list_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void netif_receive_skb_list_internal(struct list_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81aa3390)
Location: net/core/dev.c:5653
Inline: False
Direct callers:
  - net/core/dev.c:__napi_poll
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:napi_complete_done
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:napi_gro_receive
```
**Symbols:**

```
ffffffff81aa3390-ffffffff81aa362b: netif_receive_skb_list_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void netif_receive_skb_list_internal(struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81c1ba90)
Location: net/core/dev.c:5690
Inline: False
Direct callers:
  - net/core/dev.c:__napi_poll
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:napi_complete_done
  - net/core/gro.c:napi_gro_frags
  - net/core/gro.c:napi_gro_receive
```
**Symbols:**

```
ffffffff81c1ba90-ffffffff81c1bd56: netif_receive_skb_list_internal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void netif_receive_skb_list_internal(struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81dcca60)
Location: net/core/dev.c:5681
Inline: False
Direct callers:
  - net/core/dev.c:__napi_poll
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:napi_complete_done
  - net/core/dev.c:netif_receive_skb_list
  - net/core/gro.c:napi_gro_frags
  - net/core/gro.c:napi_gro_receive
```
**Symbols:**

```
ffffffff81dcca60-ffffffff81dccd26: netif_receive_skb_list_internal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void netif_receive_skb_list_internal(struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81e3d5c0)
Location: net/core/dev.c:5657
Inline: False
Direct callers:
  - net/core/dev.c:__napi_poll
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:napi_complete_done
  - net/core/dev.c:netif_receive_skb_list
  - net/core/gro.c:napi_gro_frags
  - net/core/gro.c:napi_gro_receive
```
**Symbols:**

```
ffffffff81e3d5c0-ffffffff81e3d886: netif_receive_skb_list_internal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void netif_receive_skb_list_internal(struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81efbe60)
Location: net/core/dev.c:5739
Inline: False
Direct callers:
  - net/core/dev.c:__napi_poll
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:napi_complete_done
  - net/core/dev.c:netif_receive_skb_list
  - net/core/gro.c:napi_gro_frags
  - net/core/gro.c:napi_gro_receive
```
**Symbols:**

```
ffffffff81efbe60-ffffffff81efc126: netif_receive_skb_list_internal (STB_GLOBAL)
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
void netif_receive_skb_list_internal(struct list_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffff800010bd3538)
Location: net/core/dev.c:5119
Inline: False
Direct callers:
  - net/core/dev.c:netif_receive_skb_list
```
**Symbols:**

```
ffff800010bd3538-ffff800010bd37d8: netif_receive_skb_list_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void netif_receive_skb_list_internal(struct list_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c0cee214)
Location: net/core/dev.c:5119
Inline: False
Direct callers:
  - net/core/dev.c:netif_receive_skb_list
```
**Symbols:**

```
c0cee214-c0cee51c: netif_receive_skb_list_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void netif_receive_skb_list_internal(struct list_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c000000000cb20f0)
Location: net/core/dev.c:5119
Inline: False
Direct callers:
  - net/core/dev.c:netif_receive_skb_list
```
**Symbols:**

```
c000000000cb20f0-c000000000cb245c: netif_receive_skb_list_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void netif_receive_skb_list_internal(struct list_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffe00075d766)
Location: net/core/dev.c:5119
Inline: False
Direct callers:
  - net/core/dev.c:netif_receive_skb_list
```
**Symbols:**

```
ffffffe00075d766-ffffffe00075d9cc: netif_receive_skb_list_internal (STB_LOCAL)
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
void netif_receive_skb_list_internal(struct list_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818d5270)
Location: net/core/dev.c:5119
Inline: False
Direct callers:
  - net/core/dev.c:netif_receive_skb_list
```
**Symbols:**

```
ffffffff818d5270-ffffffff818d550d: netif_receive_skb_list_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void netif_receive_skb_list_internal(struct list_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8188f0e0)
Location: net/core/dev.c:5119
Inline: False
Direct callers:
  - net/core/dev.c:netif_receive_skb_list
```
**Symbols:**

```
ffffffff8188f0e0-ffffffff8188f37d: netif_receive_skb_list_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void netif_receive_skb_list_internal(struct list_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81926290)
Location: net/core/dev.c:5119
Inline: False
Direct callers:
  - net/core/dev.c:netif_receive_skb_list
```
**Symbols:**

```
ffffffff81926290-ffffffff81926539: netif_receive_skb_list_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void netif_receive_skb_list_internal(struct list_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81947830)
Location: net/core/dev.c:5119
Inline: False
Direct callers:
  - net/core/dev.c:netif_receive_skb_list
```
**Symbols:**

```
ffffffff81947830-ffffffff81947ae3: netif_receive_skb_list_internal (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
