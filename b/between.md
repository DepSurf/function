# Function: <code>between</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (0)
Location: include/net/tcp.h:312
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/net/tcp.h:312
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/net/tcp.h:312
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/net/tcp.h:312
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff817e08c9)
Location: include/net/tcp.h:301
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
```
```
In net/ipv4/tcp_output.c (ffffffff817e6884)
Location: include/net/tcp.h:301
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_wakeup
```
```
In net/ipv4/tcp_ipv4.c (ffffffff817eb087)
Location: include/net/tcp.h:301
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81860ee2)
Location: include/net/tcp.h:301
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81810cd5)
Location: include/net/tcp.h:299
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
```
```
In net/ipv4/tcp_output.c (ffffffff81816fc4)
Location: include/net/tcp.h:299
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_wakeup
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8181b9d7)
Location: include/net/tcp.h:299
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81892e12)
Location: include/net/tcp.h:299
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81830f0f)
Location: include/net/tcp.h:306
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
```
```
In net/ipv4/tcp_output.c (ffffffff81837434)
Location: include/net/tcp.h:306
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_wakeup
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8183c151)
Location: include/net/tcp.h:306
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv6/tcp_ipv6.c (ffffffff818b93e6)
Location: include/net/tcp.h:306
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff818b038c)
Location: include/net/tcp.h:274
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
```
```
In net/ipv4/tcp_output.c (ffffffff818b6af1)
Location: include/net/tcp.h:274
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_wakeup
```
```
In net/ipv4/tcp_ipv4.c (ffffffff818bb864)
Location: include/net/tcp.h:274
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8193c34b)
Location: include/net/tcp.h:274
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81905537)
Location: include/net/tcp.h:275
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
```
```
In net/ipv4/tcp_output.c (ffffffff8190c331)
Location: include/net/tcp.h:275
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_wakeup
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819112d7)
Location: include/net/tcp.h:275
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8199472c)
Location: include/net/tcp.h:275
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819336dd)
Location: include/net/tcp.h:276
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
```
```
In net/ipv4/tcp_output.c (ffffffff8193a611)
Location: include/net/tcp.h:276
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_wakeup
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8193faf9)
Location: include/net/tcp.h:276
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819cb043)
Location: include/net/tcp.h:276
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8199707d)
Location: include/net/tcp.h:275
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
```
```
In net/ipv4/tcp_output.c (ffffffff8199e961)
Location: include/net/tcp.h:275
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_wakeup
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819a3fd8)
Location: include/net/tcp.h:275
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a39a91)
Location: include/net/tcp.h:275
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819cdbfd)
Location: include/net/tcp.h:275
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
```
```
In net/ipv4/tcp_output.c (ffffffff819d5471)
Location: include/net/tcp.h:275
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_wakeup
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819dabf8)
Location: include/net/tcp.h:275
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a70621)
Location: include/net/tcp.h:275
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81ab9db3)
Location: include/net/tcp.h:277
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
```
```
In net/ipv4/tcp_output.c (ffffffff81ac1db1)
Location: include/net/tcp.h:277
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_wakeup
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ac7d46)
Location: include/net/tcp.h:277
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b6916a)
Location: include/net/tcp.h:277
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81ac51f3)
Location: include/net/tcp.h:278
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
```
```
In net/ipv4/tcp_output.c (ffffffff81acd821)
Location: include/net/tcp.h:278
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_wakeup
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ad3ba6)
Location: include/net/tcp.h:278
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b77b9a)
Location: include/net/tcp.h:278
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81ab042a)
Location: include/net/tcp.h:278
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
```
```
In net/ipv4/tcp_output.c (ffffffff81ab89e1)
Location: include/net/tcp.h:278
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_wakeup
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81abec68)
Location: include/net/tcp.h:278
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b6669b)
Location: include/net/tcp.h:278
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81b6d25a)
Location: include/net/tcp.h:280
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
```
```
In net/ipv4/tcp_output.c (ffffffff81b75c01)
Location: include/net/tcp.h:280
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_wakeup
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81b7c7a8)
Location: include/net/tcp.h:280
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81c2e24b)
Location: include/net/tcp.h:280
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81cfc9c6)
Location: include/net/tcp.h:280
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
```
```
In net/ipv4/tcp_output.c (ffffffff81d05501)
Location: include/net/tcp.h:280
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_wakeup
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81d0c6d5)
Location: include/net/tcp.h:280
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81dcbb07)
Location: include/net/tcp.h:280
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81ec1576)
Location: include/net/tcp.h:282
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
```
```
In net/ipv4/tcp_output.c (ffffffff81eca601)
Location: include/net/tcp.h:282
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_wakeup
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ed2115)
Location: include/net/tcp.h:282
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81f9cc17)
Location: include/net/tcp.h:282
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81f1fade)
Location: include/net/tcp.h:281
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
```
```
In net/ipv4/tcp_output.c (ffffffff81f29141)
Location: include/net/tcp.h:281
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_wakeup
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f30dcf)
Location: include/net/tcp.h:281
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81ffd65c)
Location: include/net/tcp.h:281
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81fe41c4)
Location: include/net/tcp.h:292
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
```
```
In net/ipv4/tcp_output.c (ffffffff81fedc81)
Location: include/net/tcp.h:292
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_wakeup
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff6d1d)
Location: include/net/tcp.h:292
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv6/tcp_ipv6.c (ffffffff820cc4cb)
Location: include/net/tcp.h:292
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffff800010c80768)
Location: include/net/tcp.h:275
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
```
```
In net/ipv4/tcp_output.c (ffff800010c880f8)
Location: include/net/tcp.h:275
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_wakeup
```
```
In net/ipv4/tcp_ipv4.c (ffff800010c8df7c)
Location: include/net/tcp.h:275
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv6/tcp_ipv6.c (ffff800010d39ae4)
Location: include/net/tcp.h:275
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (c0d8fc44)
Location: include/net/tcp.h:275
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
```
```
In net/ipv4/tcp_output.c (c0d973e8)
Location: include/net/tcp.h:275
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_wakeup
```
```
In net/ipv4/tcp_ipv4.c (c0d9d02c)
Location: include/net/tcp.h:275
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv6/tcp_ipv6.c (c0e3aa74)
Location: include/net/tcp.h:275
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (c000000000d8b3e0)
Location: include/net/tcp.h:275
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
```
```
In net/ipv4/tcp_output.c (c000000000d94f54)
Location: include/net/tcp.h:275
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_wakeup
```
```
In net/ipv4/tcp_ipv4.c (c000000000d9c878)
Location: include/net/tcp.h:275
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv6/tcp_ipv6.c (c000000000e6aa68)
Location: include/net/tcp.h:275
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffe0007e26f6)
Location: include/net/tcp.h:275
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
```
```
In net/ipv4/tcp_output.c (ffffffe0007e936e)
Location: include/net/tcp.h:275
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_wakeup
```
```
In net/ipv4/tcp_ipv4.c (ffffffe0007ee468)
Location: include/net/tcp.h:275
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv6/tcp_ipv6.c (ffffffe000875956)
Location: include/net/tcp.h:275
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8196da6d)
Location: include/net/tcp.h:275
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
```
```
In net/ipv4/tcp_output.c (ffffffff819752e1)
Location: include/net/tcp.h:275
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_wakeup
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8197aa68)
Location: include/net/tcp.h:275
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a0fcb1)
Location: include/net/tcp.h:275
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8192755d)
Location: include/net/tcp.h:275
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
```
```
In net/ipv4/tcp_output.c (ffffffff8192eda1)
Location: include/net/tcp.h:275
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_wakeup
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81934528)
Location: include/net/tcp.h:275
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819cca71)
Location: include/net/tcp.h:275
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819d823d)
Location: include/net/tcp.h:275
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
```
```
In net/ipv4/tcp_output.c (ffffffff819dfab1)
Location: include/net/tcp.h:275
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_wakeup
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819e5238)
Location: include/net/tcp.h:275
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a7a731)
Location: include/net/tcp.h:275
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819e1e7d)
Location: include/net/tcp.h:275
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
```
```
In net/ipv4/tcp_output.c (ffffffff819e9761)
Location: include/net/tcp.h:275
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_wakeup
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819eeee8)
Location: include/net/tcp.h:275
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a86f71)
Location: include/net/tcp.h:275
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
</details>
</li>
</ul>

## Differences
