# Function: <code>tcp_sum_lost</code>

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
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff818076b4)
Location: net/ipv4/tcp_input.c:932
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_mark_head_lost
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_skb_mark_lost_uncond_verify
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81828232)
Location: net/ipv4/tcp_input.c:937
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_mark_head_lost
  - net/ipv4/tcp_input.c:tcp_enter_loss
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff818a7715)
Location: net/ipv4/tcp_input.c:906
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_mark_head_lost
  - net/ipv4/tcp_input.c:tcp_enter_loss
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff818fc865)
Location: net/ipv4/tcp_input.c:933
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_mark_head_lost
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8192a9d5)
Location: net/ipv4/tcp_input.c:919
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_mark_head_lost
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
In net/ipv4/tcp_input.c (ffffffff8198dd11)
Location: net/ipv4/tcp_input.c:929
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_mark_head_lost
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819c48c5)
Location: net/ipv4/tcp_input.c:932
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_mark_head_lost
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81ab13a9)
Location: net/ipv4/tcp_input.c:934
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_mark_head_lost
```
</details>
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffff800010c77350)
Location: net/ipv4/tcp_input.c:932
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_mark_head_lost
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (c0d858b4)
Location: net/ipv4/tcp_input.c:932
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_mark_head_lost
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (c000000000d7f6d0)
Location: net/ipv4/tcp_input.c:932
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_mark_head_lost
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffe0007da3ec)
Location: net/ipv4/tcp_input.c:932
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_mark_head_lost
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81964735)
Location: net/ipv4/tcp_input.c:932
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_mark_head_lost
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8191e225)
Location: net/ipv4/tcp_input.c:932
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_mark_head_lost
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819cef05)
Location: net/ipv4/tcp_input.c:932
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_mark_head_lost
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819d8a95)
Location: net/ipv4/tcp_input.c:932
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_mark_head_lost
```
</details>
</li>
</ul>

## Differences
