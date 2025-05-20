# Function: <code>tcp_timeout_init</code>

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
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8182c985)
Location: include/net/tcp.h:2070
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_output.c (ffffffff8183522a)
Location: include/net/tcp.h:2070
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
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
In net/ipv4/tcp_input.c (ffffffff818ab870)
Location: include/net/tcp.h:2035
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_output.c (ffffffff818b46c7)
Location: include/net/tcp.h:2035
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
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
In net/ipv4/tcp_input.c (ffffffff81900d85)
Location: include/net/tcp.h:2094
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_output.c (ffffffff81909cf4)
Location: include/net/tcp.h:2094
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
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
In net/ipv4/tcp_input.c (ffffffff8192ee98)
Location: include/net/tcp.h:2174
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_output.c (ffffffff81937fa2)
Location: include/net/tcp.h:2174
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
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
In net/ipv4/tcp_input.c (ffffffff8199243f)
Location: include/net/tcp.h:2206
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_output.c (ffffffff81999732)
Location: include/net/tcp.h:2206
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
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
In net/ipv4/tcp_input.c (ffffffff819c900e)
Location: include/net/tcp.h:2234
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_output.c (ffffffff819d0132)
Location: include/net/tcp.h:2234
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
```
```
In net/ipv4/tcp_timer.c (ffffffff819d5c45)
Location: include/net/tcp.h:2234
Inline: True
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
In net/ipv4/tcp_input.c (ffffffff81ab44f5)
Location: include/net/tcp.h:2287
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_output.c (ffffffff81abd17e)
Location: include/net/tcp.h:2287
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
```
```
In net/ipv4/tcp_timer.c (ffffffff81ac2385)
Location: include/net/tcp.h:2287
Inline: True
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
In net/ipv4/tcp_input.c (ffffffff81abee06)
Location: include/net/tcp.h:2311
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_output.c (ffffffff81ac88d5)
Location: include/net/tcp.h:2311
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
```
```
In net/ipv4/tcp_timer.c (ffffffff81acddf8)
Location: include/net/tcp.h:2311
Inline: True
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
In net/ipv4/tcp_input.c (ffffffff81aab23a)
Location: include/net/tcp.h:2316
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_output.c (ffffffff81ab360a)
Location: include/net/tcp.h:2316
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
```
```
In net/ipv4/tcp_timer.c (ffffffff81ab8ea8)
Location: include/net/tcp.h:2316
Inline: True
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
In net/ipv4/tcp_input.c (ffffffff81b67623)
Location: include/net/tcp.h:2308
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_output.c (ffffffff81b7041c)
Location: include/net/tcp.h:2308
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
```
```
In net/ipv4/tcp_timer.c (ffffffff81b76105)
Location: include/net/tcp.h:2308
Inline: True
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
In net/ipv4/tcp_input.c (ffffffff81cf66a8)
Location: include/net/tcp.h:2368
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_output.c (ffffffff81cff98f)
Location: include/net/tcp.h:2368
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
```
```
In net/ipv4/tcp_timer.c (ffffffff81d05a82)
Location: include/net/tcp.h:2368
Inline: True
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
In net/ipv4/tcp_input.c (ffffffff81ebb0b8)
Location: include/net/tcp.h:2416
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_output.c (ffffffff81ec4a2f)
Location: include/net/tcp.h:2416
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
```
```
In net/ipv4/tcp_timer.c (ffffffff81ecabc2)
Location: include/net/tcp.h:2416
Inline: True
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ed898a)
Location: include/net/tcp.h:2416
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_create_child
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
In net/ipv4/tcp_input.c (ffffffff81f19548)
Location: include/net/tcp.h:2441
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_output.c (ffffffff81f23398)
Location: include/net/tcp.h:2441
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
```
```
In net/ipv4/tcp_timer.c (ffffffff81f2966a)
Location: include/net/tcp.h:2441
Inline: True
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81f37a9a)
Location: include/net/tcp.h:2441
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_create_child
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
In net/ipv4/tcp_input.c (ffffffff81fddd5d)
Location: include/net/tcp.h:2637
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_output.c (ffffffff81fe782c)
Location: include/net/tcp.h:2637
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
```
```
In net/ipv4/tcp_timer.c (ffffffff81fee1bd)
Location: include/net/tcp.h:2637
Inline: True
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ffdb6a)
Location: include/net/tcp.h:2637
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_create_child
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
In net/ipv4/tcp_input.c (ffff800010c7ab3c)
Location: include/net/tcp.h:2234
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_output.c (ffff800010c82760)
Location: include/net/tcp.h:2234
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
```
```
In net/ipv4/tcp_timer.c (ffff800010c88654)
Location: include/net/tcp.h:2234
Inline: True
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
In net/ipv4/tcp_input.c (c0d88678)
Location: include/net/tcp.h:2234
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_output.c (c0d91e1c)
Location: include/net/tcp.h:2234
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
```
```
In net/ipv4/tcp_timer.c (c0d97d30)
Location: include/net/tcp.h:2234
Inline: True
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
In net/ipv4/tcp_input.c (c000000000d85854)
Location: include/net/tcp.h:2234
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_output.c (c000000000d8e318)
Location: include/net/tcp.h:2234
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
```
```
In net/ipv4/tcp_timer.c (c000000000d95d10)
Location: include/net/tcp.h:2234
Inline: True
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
In net/ipv4/tcp_input.c (ffffffe0007de6ca)
Location: include/net/tcp.h:2234
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_output.c (ffffffe0007e4a56)
Location: include/net/tcp.h:2234
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
```
```
In net/ipv4/tcp_timer.c (ffffffe0007e9c8c)
Location: include/net/tcp.h:2234
Inline: True
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
In net/ipv4/tcp_input.c (ffffffff81968e7e)
Location: include/net/tcp.h:2234
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_output.c (ffffffff8196ffa2)
Location: include/net/tcp.h:2234
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
```
```
In net/ipv4/tcp_timer.c (ffffffff81975ab5)
Location: include/net/tcp.h:2234
Inline: True
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
In net/ipv4/tcp_input.c (ffffffff8192296e)
Location: include/net/tcp.h:2234
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_output.c (ffffffff81929a72)
Location: include/net/tcp.h:2234
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
```
```
In net/ipv4/tcp_timer.c (ffffffff8192f575)
Location: include/net/tcp.h:2234
Inline: True
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
In net/ipv4/tcp_input.c (ffffffff819d364e)
Location: include/net/tcp.h:2234
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_output.c (ffffffff819da772)
Location: include/net/tcp.h:2234
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
```
```
In net/ipv4/tcp_timer.c (ffffffff819e0285)
Location: include/net/tcp.h:2234
Inline: True
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
In net/ipv4/tcp_input.c (ffffffff819dd1f8)
Location: include/net/tcp.h:2234
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_output.c (ffffffff819e43f4)
Location: include/net/tcp.h:2234
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
```
```
In net/ipv4/tcp_timer.c (ffffffff819e9f45)
Location: include/net/tcp.h:2234
Inline: True
```
</details>
</li>
</ul>

## Differences
