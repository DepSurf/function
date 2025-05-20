# Function: <code>tcp_skb_timestamp</code>

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
Location: include/net/tcp.h:713
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/net/tcp.h:713
Inline: True
```
```
In net/ipv4/tcp_timer.c (0)
Location: include/net/tcp.h:713
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/net/tcp.h:713
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
In net/ipv4/tcp_input.c (0)
Location: include/net/tcp.h:709
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/net/tcp.h:709
Inline: True
```
```
In net/ipv4/tcp_timer.c (0)
Location: include/net/tcp.h:709
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/net/tcp.h:709
Inline: True
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
In net/ipv4/tcp_input.c (0)
Location: include/net/tcp.h:707
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/net/tcp.h:707
Inline: True
```
```
In net/ipv4/tcp_timer.c (0)
Location: include/net/tcp.h:707
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/net/tcp.h:707
Inline: True
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
In net/ipv4/tcp_input.c (ffffffff8182af75)
Location: include/net/tcp.h:759
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
```
```
In net/ipv4/tcp_output.c (ffffffff81832439)
Location: include/net/tcp.h:759
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_established_options
```
```
In net/ipv4/tcp_timer.c (ffffffff818386c5)
Location: include/net/tcp.h:759
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
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
In net/ipv4/tcp_input.c (ffffffff818aabdd)
Location: include/net/tcp.h:735
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
```
```
In net/ipv4/tcp_output.c (ffffffff818b157b)
Location: include/net/tcp.h:735
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_established_options
```
```
In net/ipv4/tcp_timer.c (ffffffff818b7e01)
Location: include/net/tcp.h:735
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
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
In net/ipv4/tcp_input.c (ffffffff818ffa90)
Location: include/net/tcp.h:745
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
```
```
In net/ipv4/tcp_output.c (ffffffff81906dd1)
Location: include/net/tcp.h:745
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_established_options
```
```
In net/ipv4/tcp_timer.c (ffffffff8190d7b1)
Location: include/net/tcp.h:745
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
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
In net/ipv4/tcp_input.c (ffffffff8192d84d)
Location: include/net/tcp.h:762
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
```
```
In net/ipv4/tcp_output.c (ffffffff81934f89)
Location: include/net/tcp.h:762
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_established_options
```
```
In net/ipv4/tcp_timer.c (ffffffff8193bb9f)
Location: include/net/tcp.h:762
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
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
In net/ipv4/tcp_input.c (ffffffff819912aa)
Location: include/net/tcp.h:763
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
```
```
In net/ipv4/tcp_output.c (ffffffff81998f19)
Location: include/net/tcp.h:763
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_established_options
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
In net/ipv4/tcp_input.c (ffffffff819c7e7a)
Location: include/net/tcp.h:784
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
```
```
In net/ipv4/tcp_output.c (ffffffff819cfa39)
Location: include/net/tcp.h:784
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_established_options
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
In net/ipv4/tcp_input.c (ffffffff81ab5021)
Location: include/net/tcp.h:795
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
```
```
In net/ipv4/tcp_output.c (ffffffff81ac0c18)
Location: include/net/tcp.h:795
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_established_options
  - net/ipv4/tcp_output.c:tcp_synack_options
  - net/ipv4/tcp_output.c:tcp_syn_options
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
In net/ipv4/tcp_input.c (ffffffff81ac014b)
Location: include/net/tcp.h:801
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
```
```
In net/ipv4/tcp_output.c (ffffffff81acc688)
Location: include/net/tcp.h:801
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_established_options
  - net/ipv4/tcp_output.c:tcp_synack_options
  - net/ipv4/tcp_output.c:tcp_syn_options
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
In net/ipv4/tcp_input.c (ffffffff81aaa004)
Location: include/net/tcp.h:806
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff81ab7848)
Location: include/net/tcp.h:806
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_established_options
  - net/ipv4/tcp_output.c:tcp_synack_options
  - net/ipv4/tcp_output.c:tcp_syn_options
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
In net/ipv4/tcp_input.c (ffffffff81b663f4)
Location: include/net/tcp.h:799
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff81b74a68)
Location: include/net/tcp.h:799
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_established_options
  - net/ipv4/tcp_output.c:tcp_synack_options
  - net/ipv4/tcp_output.c:tcp_syn_options
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
In net/ipv4/tcp_input.c (ffffffff81cf46fd)
Location: include/net/tcp.h:813
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff81d041c8)
Location: include/net/tcp.h:813
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_established_options
  - net/ipv4/tcp_output.c:tcp_synack_options
  - net/ipv4/tcp_output.c:tcp_syn_options
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
In net/ipv4/tcp_input.c (ffffffff81eb90dd)
Location: include/net/tcp.h:826
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff81ec9128)
Location: include/net/tcp.h:826
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_established_options
  - net/ipv4/tcp_output.c:tcp_synack_options
  - net/ipv4/tcp_output.c:tcp_syn_options
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
In net/ipv4/tcp_input.c (ffffffff81f174ed)
Location: include/net/tcp.h:821
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff81f27c48)
Location: include/net/tcp.h:821
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_established_options
  - net/ipv4/tcp_output.c:tcp_synack_options
  - net/ipv4/tcp_output.c:tcp_syn_options
```
```
In net/ipv4/tcp_timer.c (ffffffff81f2a86f)
Location: include/net/tcp.h:821
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In net/ipv4/tcp_input.c (ffff800010c7b940)
Location: include/net/tcp.h:784
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
```
```
In net/ipv4/tcp_output.c (ffff800010c82c2c)
Location: include/net/tcp.h:784
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_established_options
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
In net/ipv4/tcp_input.c (c0d89b30)
Location: include/net/tcp.h:784
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
```
```
In net/ipv4/tcp_output.c (c0d91628)
Location: include/net/tcp.h:784
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_established_options
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
In net/ipv4/tcp_input.c (c000000000d844b4)
Location: include/net/tcp.h:784
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
```
```
In net/ipv4/tcp_output.c (c000000000d8dac0)
Location: include/net/tcp.h:784
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_established_options
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
In net/ipv4/tcp_input.c (ffffffe0007dd926)
Location: include/net/tcp.h:784
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
```
```
In net/ipv4/tcp_output.c (ffffffe0007e4428)
Location: include/net/tcp.h:784
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_established_options
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
In net/ipv4/tcp_input.c (ffffffff81967cea)
Location: include/net/tcp.h:784
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
```
```
In net/ipv4/tcp_output.c (ffffffff8196f8a9)
Location: include/net/tcp.h:784
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_established_options
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
In net/ipv4/tcp_input.c (ffffffff819217da)
Location: include/net/tcp.h:784
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
```
```
In net/ipv4/tcp_output.c (ffffffff81929379)
Location: include/net/tcp.h:784
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_established_options
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
In net/ipv4/tcp_input.c (ffffffff819d24ba)
Location: include/net/tcp.h:784
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
```
```
In net/ipv4/tcp_output.c (ffffffff819da079)
Location: include/net/tcp.h:784
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_established_options
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
In net/ipv4/tcp_input.c (ffffffff819dc05a)
Location: include/net/tcp.h:784
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
```
```
In net/ipv4/tcp_output.c (ffffffff819e3cee)
Location: include/net/tcp.h:784
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_established_options
```
</details>
</li>
</ul>

## Differences
