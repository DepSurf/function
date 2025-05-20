# Function: <code>tcp_ack_probe</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff817721d9)
Location: net/ipv4/tcp_input.c:3271
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff817ddb96)
Location: net/ipv4/tcp_input.c:3287
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8180ddcb)
Location: net/ipv4/tcp_input.c:3290
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack
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
In net/ipv4/tcp_input.c (ffffffff8182e2d3)
Location: net/ipv4/tcp_input.c:3253
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack
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
In net/ipv4/tcp_input.c (ffffffff818ad14d)
Location: net/ipv4/tcp_input.c:3196
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack
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
In net/ipv4/tcp_input.c (ffffffff819028c0)
Location: net/ipv4/tcp_input.c:3254
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack
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
In net/ipv4/tcp_input.c (ffffffff819309b6)
Location: net/ipv4/tcp_input.c:3247
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack
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
In net/ipv4/tcp_input.c (ffffffff81993fd1)
Location: net/ipv4/tcp_input.c:3267
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack
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
In net/ipv4/tcp_input.c (ffffffff819cab21)
Location: net/ipv4/tcp_input.c:3274
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack
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
In net/ipv4/tcp_input.c (ffffffff81ab7aa8)
Location: net/ipv4/tcp_input.c:3258
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void tcp_ack_probe(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81abd720)
Location: net/ipv4/tcp_input.c:3377
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffff81abd720-ffffffff81abd84b: tcp_ack_probe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81aadf12)
Location: net/ipv4/tcp_input.c:3384
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81b6aa4f)
Location: net/ipv4/tcp_input.c:3418
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81cf9d12)
Location: net/ipv4/tcp_input.c:3433
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81ebe81f)
Location: net/ipv4/tcp_input.c:3444
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81f1ccbf)
Location: net/ipv4/tcp_input.c:3443
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81fe135c)
Location: net/ipv4/tcp_input.c:3485
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack
```
</details>
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
In net/ipv4/tcp_input.c (ffff800010c7d7ac)
Location: net/ipv4/tcp_input.c:3274
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack
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
In net/ipv4/tcp_input.c (c0d8c660)
Location: net/ipv4/tcp_input.c:3274
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack
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
In net/ipv4/tcp_input.c (c000000000d875c4)
Location: net/ipv4/tcp_input.c:3274
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack
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
In net/ipv4/tcp_input.c (ffffffe0007dfcde)
Location: net/ipv4/tcp_input.c:3274
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack
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
In net/ipv4/tcp_input.c (ffffffff8196a991)
Location: net/ipv4/tcp_input.c:3274
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack
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
In net/ipv4/tcp_input.c (ffffffff81924481)
Location: net/ipv4/tcp_input.c:3274
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack
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
In net/ipv4/tcp_input.c (ffffffff819d5161)
Location: net/ipv4/tcp_input.c:3274
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack
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
In net/ipv4/tcp_input.c (ffffffff819ded41)
Location: net/ipv4/tcp_input.c:3274
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
