# Function: <code>tcp_ca_dst_init</code>

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
In net/ipv4/tcp_output.c (ffffffff817779f8)
Location: net/ipv4/tcp_output.c:3037
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
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
In net/ipv4/tcp_output.c (ffffffff817e4a18)
Location: net/ipv4/tcp_output.c:3089
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
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
In net/ipv4/tcp_output.c (ffffffff81814e68)
Location: net/ipv4/tcp_output.c:3213
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
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
In net/ipv4/tcp_output.c (ffffffff8183505c)
Location: net/ipv4/tcp_output.c:3235
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
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
In net/ipv4/tcp_output.c (ffffffff818b44f0)
Location: net/ipv4/tcp_output.c:3289
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
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
In net/ipv4/tcp_output.c (ffffffff81909b06)
Location: net/ipv4/tcp_output.c:3270
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
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
In net/ipv4/tcp_output.c (ffffffff81937db2)
Location: net/ipv4/tcp_output.c:3302
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
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
In net/ipv4/tcp_output.c (ffffffff81999511)
Location: net/ipv4/tcp_output.c:3336
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
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
In net/ipv4/tcp_output.c (ffffffff819cfef1)
Location: net/ipv4/tcp_output.c:3368
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void tcp_ca_dst_init(struct sock *sk, const struct dst_entry *dst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81abc730)
Location: net/ipv4/tcp_output.c:3441
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
```
**Symbols:**

```
ffffffff81abc730-ffffffff81abc7ef: tcp_ca_dst_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void tcp_ca_dst_init(struct sock *sk, const struct dst_entry *dst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81ac7e90)
Location: net/ipv4/tcp_output.c:3621
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
```
**Symbols:**

```
ffffffff81ac7e90-ffffffff81ac7f54: tcp_ca_dst_init (STB_LOCAL)
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
In net/ipv4/tcp_output.c (ffffffff81ab33e5)
Location: net/ipv4/tcp_output.c:3618
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
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
In net/ipv4/tcp_output.c (ffffffff81b70219)
Location: net/ipv4/tcp_output.c:3619
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
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
In net/ipv4/tcp_output.c (ffffffff81cff7b8)
Location: net/ipv4/tcp_output.c:3626
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
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
In net/ipv4/tcp_output.c (ffffffff81ec4858)
Location: net/ipv4/tcp_output.c:3628
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
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
In net/ipv4/tcp_output.c (ffffffff81f231c8)
Location: net/ipv4/tcp_output.c:3710
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
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
In net/ipv4/tcp_output.c (ffffffff81fe763a)
Location: net/ipv4/tcp_output.c:3812
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
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
In net/ipv4/tcp_output.c (ffff800010c825b8)
Location: net/ipv4/tcp_output.c:3368
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
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
In net/ipv4/tcp_output.c (c0d91c2c)
Location: net/ipv4/tcp_output.c:3368
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
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
In net/ipv4/tcp_output.c (c000000000d8e120)
Location: net/ipv4/tcp_output.c:3368
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
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
In net/ipv4/tcp_output.c (ffffffe0007e48e2)
Location: net/ipv4/tcp_output.c:3368
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
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
In net/ipv4/tcp_output.c (ffffffff8196fd61)
Location: net/ipv4/tcp_output.c:3368
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
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
In net/ipv4/tcp_output.c (ffffffff81929831)
Location: net/ipv4/tcp_output.c:3368
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
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
In net/ipv4/tcp_output.c (ffffffff819da531)
Location: net/ipv4/tcp_output.c:3368
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
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
In net/ipv4/tcp_output.c (ffffffff819e41b1)
Location: net/ipv4/tcp_output.c:3368
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
