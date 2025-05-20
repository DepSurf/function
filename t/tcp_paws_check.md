# Function: <code>tcp_paws_check</code>

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
In net/ipv4/tcp_input.c (ffffffff817724f9)
Location: include/net/tcp.h:1258
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
```
```
In net/ipv4/tcp_minisocks.c (ffffffff8177f524)
Location: include/net/tcp.h:1258
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_check_req
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
In net/ipv4/tcp_input.c (ffffffff817e05d6)
Location: include/net/tcp.h:1274
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_ack
```
```
In net/ipv4/tcp_minisocks.c (ffffffff817ecda5)
Location: include/net/tcp.h:1274
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
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
In net/ipv4/tcp_input.c (ffffffff818109e2)
Location: include/net/tcp.h:1331
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_ack
```
```
In net/ipv4/tcp_minisocks.c (ffffffff8181d6ae)
Location: include/net/tcp.h:1331
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
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
In net/ipv4/tcp_input.c (ffffffff81830c35)
Location: include/net/tcp.h:1371
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_ack
```
```
In net/ipv4/tcp_minisocks.c (ffffffff8183dd32)
Location: include/net/tcp.h:1371
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
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
In net/ipv4/tcp_input.c (ffffffff818b00a4)
Location: include/net/tcp.h:1352
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_ack
```
```
In net/ipv4/tcp_minisocks.c (ffffffff818bd268)
Location: include/net/tcp.h:1352
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
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
In net/ipv4/tcp_input.c (ffffffff81905767)
Location: include/net/tcp.h:1369
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_ack
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819131af)
Location: include/net/tcp.h:1369
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
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
In net/ipv4/tcp_input.c (ffffffff8193390f)
Location: include/net/tcp.h:1427
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
```
```
In net/ipv4/tcp_minisocks.c (ffffffff8194196d)
Location: include/net/tcp.h:1427
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
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
In net/ipv4/tcp_input.c (ffffffff8199762b)
Location: include/net/tcp.h:1429
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819a5f6d)
Location: include/net/tcp.h:1429
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
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
In net/ipv4/tcp_input.c (ffffffff819ce1b3)
Location: include/net/tcp.h:1451
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819dcf3d)
Location: include/net/tcp.h:1451
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
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
In net/ipv4/tcp_input.c (ffffffff81aba325)
Location: include/net/tcp.h:1478
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ac9e22)
Location: include/net/tcp.h:1478
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
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
In net/ipv4/tcp_input.c (ffffffff81ac576b)
Location: include/net/tcp.h:1492
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ad5d6a)
Location: include/net/tcp.h:1492
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
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
In net/ipv4/tcp_input.c (ffffffff81ab0980)
Location: include/net/tcp.h:1496
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ac0dd4)
Location: include/net/tcp.h:1496
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
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
In net/ipv4/tcp_input.c (ffffffff81b6d7bc)
Location: include/net/tcp.h:1489
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81b7e8ed)
Location: include/net/tcp.h:1489
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
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
In net/ipv4/tcp_input.c (ffffffff81cfc8f6)
Location: include/net/tcp.h:1536
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_ack
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81d0f190)
Location: include/net/tcp.h:1536
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
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
In net/ipv4/tcp_input.c (ffffffff81ec14a6)
Location: include/net/tcp.h:1552
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_ack
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ed4cf0)
Location: include/net/tcp.h:1552
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
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
In net/ipv4/tcp_input.c (ffffffff81f1fa06)
Location: include/net/tcp.h:1565
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_ack
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81f339c3)
Location: include/net/tcp.h:1565
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
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
In net/ipv4/tcp_input.c (ffffffff81fe40d2)
Location: include/net/tcp.h:1635
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_ack
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ff9b37)
Location: include/net/tcp.h:1635
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
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
In net/ipv4/tcp_input.c (ffff800010c80c1c)
Location: include/net/tcp.h:1451
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
```
```
In net/ipv4/tcp_minisocks.c (ffff800010c90598)
Location: include/net/tcp.h:1451
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
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
In net/ipv4/tcp_input.c (c0d8fba8)
Location: include/net/tcp.h:1451
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
```
```
In net/ipv4/tcp_minisocks.c (c0d9ed24)
Location: include/net/tcp.h:1451
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
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
In net/ipv4/tcp_input.c (c000000000d8b9f0)
Location: include/net/tcp.h:1451
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
```
```
In net/ipv4/tcp_minisocks.c (c000000000d9f15c)
Location: include/net/tcp.h:1451
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
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
In net/ipv4/tcp_input.c (ffffffe0007e2b9c)
Location: include/net/tcp.h:1451
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
```
```
In net/ipv4/tcp_minisocks.c (ffffffe0007f00e0)
Location: include/net/tcp.h:1451
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
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
In net/ipv4/tcp_input.c (ffffffff8196e023)
Location: include/net/tcp.h:1451
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
```
```
In net/ipv4/tcp_minisocks.c (ffffffff8197cdad)
Location: include/net/tcp.h:1451
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
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
In net/ipv4/tcp_input.c (ffffffff81927b13)
Location: include/net/tcp.h:1451
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
```
```
In net/ipv4/tcp_minisocks.c (ffffffff8193686d)
Location: include/net/tcp.h:1451
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
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
In net/ipv4/tcp_input.c (ffffffff819d87f3)
Location: include/net/tcp.h:1451
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819e757d)
Location: include/net/tcp.h:1451
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
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
In net/ipv4/tcp_input.c (ffffffff819e2440)
Location: include/net/tcp.h:1451
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819f124d)
Location: include/net/tcp.h:1451
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
```
</details>
</li>
</ul>

## Differences
