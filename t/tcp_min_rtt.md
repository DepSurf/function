# Function: <code>tcp_min_rtt</code>

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
In net/ipv4/tcp_recovery.c (ffffffff81783016)
Location: include/net/tcp.h:679
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_mark_lost
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
In net/ipv4/tcp.c (ffffffff817d2e73)
Location: include/net/tcp.h:675
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_info
```
```
In net/ipv4/tcp_recovery.c (ffffffff817f05a6)
Location: include/net/tcp.h:675
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_mark_lost
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
In net/ipv4/tcp.c (0)
Location: include/net/tcp.h:673
Inline: True
```
```
In net/ipv4/tcp_rate.c (0)
Location: include/net/tcp.h:673
Inline: True
```
```
In net/ipv4/tcp_recovery.c (0)
Location: include/net/tcp.h:673
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
In net/ipv4/tcp.c (0)
Location: include/net/tcp.h:681
Inline: True
```
```
In net/ipv4/tcp_rate.c (0)
Location: include/net/tcp.h:681
Inline: True
```
```
In net/ipv4/tcp_recovery.c (0)
Location: include/net/tcp.h:681
Inline: True
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
In net/ipv4/tcp.c (ffffffff818a224a)
Location: include/net/tcp.h:657
Inline: True
```
```
In net/ipv4/tcp_rate.c (ffffffff818c11a2)
Location: include/net/tcp.h:657
Inline: True
Inline callers:
  - net/ipv4/tcp_rate.c:tcp_rate_gen
```
```
In net/ipv4/tcp_recovery.c (ffffffff818c1286)
Location: include/net/tcp.h:657
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
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
In net/ipv4/tcp.c (ffffffff818fbf93)
Location: include/net/tcp.h:667
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
```
```
In net/ipv4/tcp_input.c (ffffffff818ff7f4)
Location: include/net/tcp.h:667
Inline: True
```
```
In net/ipv4/tcp_rate.c (ffffffff81916ce1)
Location: include/net/tcp.h:667
Inline: True
Inline callers:
  - net/ipv4/tcp_rate.c:tcp_rate_gen
```
```
In net/ipv4/tcp_recovery.c (ffffffff819170b0)
Location: include/net/tcp.h:667
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_advance
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
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
In net/ipv4/tcp.c (ffffffff81929f05)
Location: include/net/tcp.h:694
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
```
```
In net/ipv4/tcp_input.c (ffffffff8192d586)
Location: include/net/tcp.h:694
Inline: True
```
```
In net/ipv4/tcp_rate.c (ffffffff819454cb)
Location: include/net/tcp.h:694
Inline: True
Inline callers:
  - net/ipv4/tcp_rate.c:tcp_rate_gen
```
```
In net/ipv4/tcp_recovery.c (ffffffff819458c0)
Location: include/net/tcp.h:694
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_advance
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
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
In net/ipv4/tcp.c (ffffffff8198d116)
Location: include/net/tcp.h:695
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
```
```
In net/ipv4/tcp_input.c (ffffffff81990eaa)
Location: include/net/tcp.h:695
Inline: True
```
```
In net/ipv4/tcp_rate.c (ffffffff819a9ac8)
Location: include/net/tcp.h:695
Inline: True
Inline callers:
  - net/ipv4/tcp_rate.c:tcp_rate_gen
```
```
In net/ipv4/tcp_recovery.c (ffffffff819a9ec0)
Location: include/net/tcp.h:695
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_advance
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
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
In net/ipv4/tcp.c (ffffffff819c3ab6)
Location: include/net/tcp.h:716
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
```
```
In net/ipv4/tcp_input.c (ffffffff819c7a8a)
Location: include/net/tcp.h:716
Inline: True
```
```
In net/ipv4/tcp_rate.c (ffffffff819e0788)
Location: include/net/tcp.h:716
Inline: True
Inline callers:
  - net/ipv4/tcp_rate.c:tcp_rate_gen
```
```
In net/ipv4/tcp_recovery.c (ffffffff819e0b80)
Location: include/net/tcp.h:716
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_advance
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
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
In net/ipv4/tcp.c (ffffffff81aaf238)
Location: include/net/tcp.h:721
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
```
```
In net/ipv4/tcp_input.c (ffffffff81ab4a0b)
Location: include/net/tcp.h:721
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack_update_rtt
```
```
In net/ipv4/tcp_rate.c (ffffffff81acdd58)
Location: include/net/tcp.h:721
Inline: True
Inline callers:
  - net/ipv4/tcp_rate.c:tcp_rate_gen
```
```
In net/ipv4/tcp_recovery.c (ffffffff81ace170)
Location: include/net/tcp.h:721
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_advance
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
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
In net/ipv4/tcp.c (ffffffff81aba2ed)
Location: include/net/tcp.h:727
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
```
```
In net/ipv4/tcp_input.c (ffffffff81abfad8)
Location: include/net/tcp.h:727
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack_update_rtt
```
```
In net/ipv4/tcp_rate.c (ffffffff81ad9db8)
Location: include/net/tcp.h:727
Inline: True
Inline callers:
  - net/ipv4/tcp_rate.c:tcp_rate_gen
```
```
In net/ipv4/tcp_recovery.c (ffffffff81ada170)
Location: include/net/tcp.h:727
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_advance
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
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
In net/ipv4/tcp.c (ffffffff81aa5572)
Location: include/net/tcp.h:732
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
```
```
In net/ipv4/tcp_input.c (ffffffff81aa9e6e)
Location: include/net/tcp.h:732
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack_update_rtt
```
```
In net/ipv4/tcp_rate.c (ffffffff81ac4e07)
Location: include/net/tcp.h:732
Inline: True
Inline callers:
  - net/ipv4/tcp_rate.c:tcp_rate_gen
```
```
In net/ipv4/tcp_recovery.c (ffffffff81ac51d0)
Location: include/net/tcp.h:732
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_advance
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
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
In net/ipv4/tcp.c (ffffffff81b618c2)
Location: include/net/tcp.h:725
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
```
```
In net/ipv4/tcp_input.c (ffffffff81b6625e)
Location: include/net/tcp.h:725
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack_update_rtt
```
```
In net/ipv4/tcp_rate.c (ffffffff81b8369f)
Location: include/net/tcp.h:725
Inline: True
Inline callers:
  - net/ipv4/tcp_rate.c:tcp_rate_gen
  - net/ipv4/tcp_rate.c:tcp_rate_gen
```
```
In net/ipv4/tcp_recovery.c (ffffffff81b839e0)
Location: include/net/tcp.h:725
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_advance
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
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
In net/ipv4/tcp.c (ffffffff81cf0301)
Location: include/net/tcp.h:739
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_info
```
```
In net/ipv4/tcp_input.c (ffffffff81cf4562)
Location: include/net/tcp.h:739
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack_update_rtt
```
```
In net/ipv4/tcp_output.c (ffffffff81cfd814)
Location: include/net/tcp.h:739
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_tso_segs
```
```
In net/ipv4/tcp_rate.c (ffffffff81d13d5e)
Location: include/net/tcp.h:739
Inline: True
Inline callers:
  - net/ipv4/tcp_rate.c:tcp_rate_gen
  - net/ipv4/tcp_rate.c:tcp_rate_gen
```
```
In net/ipv4/tcp_recovery.c (ffffffff81d140d0)
Location: include/net/tcp.h:739
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_advance
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
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
In net/ipv4/tcp.c (ffffffff81eb3631)
Location: include/net/tcp.h:752
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_info
```
```
In net/ipv4/tcp_input.c (ffffffff81eb8f32)
Location: include/net/tcp.h:752
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack_update_rtt
```
```
In net/ipv4/tcp_output.c (ffffffff81ec2434)
Location: include/net/tcp.h:752
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_tso_segs
```
```
In net/ipv4/tcp_rate.c (ffffffff81ed9d6e)
Location: include/net/tcp.h:752
Inline: True
Inline callers:
  - net/ipv4/tcp_rate.c:tcp_rate_gen
  - net/ipv4/tcp_rate.c:tcp_rate_gen
```
```
In net/ipv4/tcp_recovery.c (ffffffff81eda120)
Location: include/net/tcp.h:752
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_advance
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
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
In net/ipv4/tcp.c (ffffffff81f11d51)
Location: include/net/tcp.h:747
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_info
```
```
In net/ipv4/tcp_input.c (ffffffff81f17342)
Location: include/net/tcp.h:747
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack_update_rtt
```
```
In net/ipv4/tcp_output.c (ffffffff81f20a3b)
Location: include/net/tcp.h:747
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_tso_segs
```
```
In net/ipv4/tcp_rate.c (ffffffff81f38e4e)
Location: include/net/tcp.h:747
Inline: True
Inline callers:
  - net/ipv4/tcp_rate.c:tcp_rate_gen
  - net/ipv4/tcp_rate.c:tcp_rate_gen
```
```
In net/ipv4/tcp_recovery.c (ffffffff81f39200)
Location: include/net/tcp.h:747
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_advance
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
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
In net/ipv4/tcp.c (ffffffff81fd5ff1)
Location: include/net/tcp.h:762
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_info
```
```
In net/ipv4/tcp_input.c (ffffffff81fdc801)
Location: include/net/tcp.h:762
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack_update_rtt
```
```
In net/ipv4/tcp_output.c (ffffffff81fe513b)
Location: include/net/tcp.h:762
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_tso_segs
```
```
In net/ipv4/tcp_rate.c (ffffffff81ffef2e)
Location: include/net/tcp.h:762
Inline: True
Inline callers:
  - net/ipv4/tcp_rate.c:tcp_rate_gen
  - net/ipv4/tcp_rate.c:tcp_rate_gen
```
```
In net/ipv4/tcp_recovery.c (ffffffff81fff2f0)
Location: include/net/tcp.h:762
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_advance
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
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
In net/ipv4/tcp.c (ffff800010c76638)
Location: include/net/tcp.h:716
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
```
```
In net/ipv4/tcp_input.c (ffff800010c79108)
Location: include/net/tcp.h:716
Inline: True
```
```
In net/ipv4/tcp_rate.c (ffff800010c94538)
Location: include/net/tcp.h:716
Inline: True
Inline callers:
  - net/ipv4/tcp_rate.c:tcp_rate_gen
```
```
In net/ipv4/tcp_recovery.c (ffff800010c949ac)
Location: include/net/tcp.h:716
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_advance
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
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
In net/ipv4/tcp.c (c0d84d58)
Location: include/net/tcp.h:716
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
```
```
In net/ipv4/tcp_input.c (c0d8919c)
Location: include/net/tcp.h:716
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack_update_rtt
```
```
In net/ipv4/tcp_rate.c (c0da2d3c)
Location: include/net/tcp.h:716
Inline: True
Inline callers:
  - net/ipv4/tcp_rate.c:tcp_rate_gen
```
```
In net/ipv4/tcp_recovery.c (c0da3258)
Location: include/net/tcp.h:716
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_advance
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
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
In net/ipv4/tcp.c (c000000000d7e1bc)
Location: include/net/tcp.h:716
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
```
```
In net/ipv4/tcp_input.c (c000000000d83f40)
Location: include/net/tcp.h:716
Inline: True
```
```
In net/ipv4/tcp_rate.c (c000000000da4c54)
Location: include/net/tcp.h:716
Inline: True
Inline callers:
  - net/ipv4/tcp_rate.c:tcp_rate_gen
```
```
In net/ipv4/tcp_recovery.c (c000000000da5218)
Location: include/net/tcp.h:716
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_advance
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
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
In net/ipv4/tcp.c (ffffffe0007d97b4)
Location: include/net/tcp.h:716
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
```
```
In net/ipv4/tcp_input.c (ffffffe0007dd65e)
Location: include/net/tcp.h:716
Inline: True
```
```
In net/ipv4/tcp_rate.c (ffffffe0007f3988)
Location: include/net/tcp.h:716
Inline: True
Inline callers:
  - net/ipv4/tcp_rate.c:tcp_rate_gen
```
```
In net/ipv4/tcp_recovery.c (ffffffe0007f3d60)
Location: include/net/tcp.h:716
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_advance
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
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
In net/ipv4/tcp.c (ffffffff81963926)
Location: include/net/tcp.h:716
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
```
```
In net/ipv4/tcp_input.c (ffffffff819678fa)
Location: include/net/tcp.h:716
Inline: True
```
```
In net/ipv4/tcp_rate.c (ffffffff819805f8)
Location: include/net/tcp.h:716
Inline: True
Inline callers:
  - net/ipv4/tcp_rate.c:tcp_rate_gen
```
```
In net/ipv4/tcp_recovery.c (ffffffff819809f0)
Location: include/net/tcp.h:716
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_advance
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
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
In net/ipv4/tcp.c (ffffffff8191d416)
Location: include/net/tcp.h:716
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
```
```
In net/ipv4/tcp_input.c (ffffffff819213ea)
Location: include/net/tcp.h:716
Inline: True
```
```
In net/ipv4/tcp_rate.c (ffffffff8193a0b8)
Location: include/net/tcp.h:716
Inline: True
Inline callers:
  - net/ipv4/tcp_rate.c:tcp_rate_gen
```
```
In net/ipv4/tcp_recovery.c (ffffffff8193a4b0)
Location: include/net/tcp.h:716
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_advance
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
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
In net/ipv4/tcp.c (ffffffff819ce0f6)
Location: include/net/tcp.h:716
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
```
```
In net/ipv4/tcp_input.c (ffffffff819d20ca)
Location: include/net/tcp.h:716
Inline: True
```
```
In net/ipv4/tcp_rate.c (ffffffff819eadc8)
Location: include/net/tcp.h:716
Inline: True
Inline callers:
  - net/ipv4/tcp_rate.c:tcp_rate_gen
```
```
In net/ipv4/tcp_recovery.c (ffffffff819eb1c0)
Location: include/net/tcp.h:716
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_advance
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
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
In net/ipv4/tcp.c (ffffffff819d7c86)
Location: include/net/tcp.h:716
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
```
```
In net/ipv4/tcp_input.c (ffffffff819dbc6a)
Location: include/net/tcp.h:716
Inline: True
```
```
In net/ipv4/tcp_rate.c (ffffffff819f4c48)
Location: include/net/tcp.h:716
Inline: True
Inline callers:
  - net/ipv4/tcp_rate.c:tcp_rate_gen
```
```
In net/ipv4/tcp_recovery.c (ffffffff819f5040)
Location: include/net/tcp.h:716
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_advance
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
```
</details>
</li>
</ul>

## Differences
