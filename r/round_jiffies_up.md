# Function: <code>round_jiffies_up</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long unsigned int round_jiffies_up(long unsigned int j);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff810eb820)
Location: kernel/time/timer.c:333
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:start_this_handle
  - block/blk-timeout.c:blk_add_timer
  - block/blk-timeout.c:blk_add_timer
  - block/blk-timeout.c:blk_rq_timed_out_timer
  - block/blk-mq.c:blk_mq_rq_timer
  - drivers/net/tun.c:tun_flow_cleanup
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:__tun_chr_ioctl
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
```
**Symbols:**

```
ffffffff810eb820-ffffffff810eb875: round_jiffies_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long unsigned int round_jiffies_up(long unsigned int j);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff810f2570)
Location: kernel/time/timer.c:431
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:start_this_handle
  - block/blk-timeout.c:blk_add_timer
  - block/blk-timeout.c:blk_add_timer
  - block/blk-timeout.c:blk_timeout_work
  - block/blk-mq.c:blk_mq_timeout_work
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_flow_cleanup
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
```
**Symbols:**

```
ffffffff810f2570-ffffffff810f25c8: round_jiffies_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long unsigned int round_jiffies_up(long unsigned int j);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff810f96f0)
Location: kernel/time/timer.c:431
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:start_this_handle
  - block/blk-timeout.c:blk_add_timer
  - block/blk-timeout.c:blk_add_timer
  - block/blk-timeout.c:blk_timeout_work
  - block/blk-mq.c:blk_mq_timeout_work
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_flow_cleanup
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
```
**Symbols:**

```
ffffffff810f96f0-ffffffff810f9748: round_jiffies_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long unsigned int round_jiffies_up(long unsigned int j);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff810fbc10)
Location: kernel/time/timer.c:434
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:start_this_handle
  - block/blk-timeout.c:blk_add_timer
  - block/blk-timeout.c:blk_add_timer
  - block/blk-timeout.c:blk_timeout_work
  - block/blk-mq.c:blk_mq_timeout_work
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_flow_cleanup
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
```
**Symbols:**

```
ffffffff810fbc10-ffffffff810fbc68: round_jiffies_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long unsigned int round_jiffies_up(long unsigned int j);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81106500)
Location: kernel/time/timer.c:434
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:start_this_handle
  - block/blk-timeout.c:blk_add_timer
  - block/blk-timeout.c:blk_add_timer
  - block/blk-timeout.c:blk_timeout_work
  - block/blk-mq.c:blk_mq_timeout_work
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_flow_cleanup
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
```
**Symbols:**

```
ffffffff81106500-ffffffff81106558: round_jiffies_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long unsigned int round_jiffies_up(long unsigned int j);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81111b50)
Location: kernel/time/timer.c:451
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:start_this_handle
  - block/blk-timeout.c:blk_add_timer
  - block/blk-timeout.c:blk_add_timer
  - block/blk-timeout.c:blk_timeout_work
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_flow_cleanup
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
```
**Symbols:**

```
ffffffff81111b50-ffffffff81111bc0: round_jiffies_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long unsigned int round_jiffies_up(long unsigned int j);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff8111d190)
Location: kernel/time/timer.c:450
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:start_this_handle
  - block/blk-timeout.c:blk_add_timer
  - block/blk-timeout.c:blk_add_timer
  - drivers/net/tun.c:tun_flow_update
  - drivers/net/tun.c:tun_flow_cleanup
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
```
**Symbols:**

```
ffffffff8111d190-ffffffff8111d200: round_jiffies_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long unsigned int round_jiffies_up(long unsigned int j);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81127e00)
Location: kernel/time/timer.c:450
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:start_this_handle
  - block/blk-timeout.c:blk_add_timer
  - block/blk-timeout.c:blk_add_timer
  - drivers/net/tun.c:tun_flow_update
  - drivers/net/tun.c:tun_flow_cleanup
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
```
**Symbols:**

```
ffffffff81127e00-ffffffff81127e73: round_jiffies_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long unsigned int round_jiffies_up(long unsigned int j);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81133da0)
Location: kernel/time/timer.c:454
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:start_this_handle
  - block/blk-timeout.c:blk_add_timer
  - block/blk-timeout.c:blk_add_timer
  - drivers/net/tun.c:tun_flow_update
  - drivers/net/tun.c:tun_flow_cleanup
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
```
**Symbols:**

```
ffffffff81133da0-ffffffff81133e13: round_jiffies_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long unsigned int round_jiffies_up(long unsigned int j);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81144c10)
Location: kernel/time/timer.c:454
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_get_transaction
  - block/blk-timeout.c:blk_add_timer
  - block/blk-timeout.c:blk_add_timer
  - drivers/net/tun.c:tun_flow_update
  - drivers/net/tun.c:tun_flow_cleanup
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
```
**Symbols:**

```
ffffffff81144c10-ffffffff81144c80: round_jiffies_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long unsigned int round_jiffies_up(long unsigned int j);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81140d10)
Location: kernel/time/timer.c:455
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_get_transaction
  - drivers/net/tun.c:tun_flow_update
  - drivers/net/tun.c:tun_flow_cleanup
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
```
**Symbols:**

```
ffffffff81140d10-ffffffff81140d80: round_jiffies_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long unsigned int round_jiffies_up(long unsigned int j);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81141f10)
Location: kernel/time/timer.c:456
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_get_transaction
  - drivers/net/tun.c:tun_flow_update
  - drivers/net/tun.c:tun_flow_cleanup
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
```
**Symbols:**

```
ffffffff81141f10-ffffffff81141f80: round_jiffies_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long unsigned int round_jiffies_up(long unsigned int j);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81165400)
Location: kernel/time/timer.c:456
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:start_this_handle
  - drivers/net/tun.c:tun_net_init
  - drivers/net/tun.c:tun_flow_update
  - drivers/net/tun.c:tun_flow_cleanup
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
```
**Symbols:**

```
ffffffff81165400-ffffffff81165470: round_jiffies_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long unsigned int round_jiffies_up(long unsigned int j);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81199530)
Location: kernel/time/timer.c:479
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:start_this_handle
  - drivers/net/tun.c:tun_net_init
  - drivers/net/tun.c:tun_flow_update
  - drivers/net/tun.c:tun_flow_cleanup
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
```
**Symbols:**

```
ffffffff81199530-ffffffff811995b8: round_jiffies_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long unsigned int round_jiffies_up(long unsigned int j);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff811d7b20)
Location: kernel/time/timer.c:479
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:start_this_handle
  - drivers/net/tun.c:tun_net_init
  - drivers/net/tun.c:tun_flow_update
  - drivers/net/tun.c:tun_flow_cleanup
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
```
**Symbols:**

```
ffffffff811d7b20-ffffffff811d7ba8: round_jiffies_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long unsigned int round_jiffies_up(long unsigned int j);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff811ebf90)
Location: kernel/time/timer.c:479
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:start_this_handle
  - drivers/net/tun.c:tun_net_init
  - drivers/net/tun.c:tun_flow_update
  - drivers/net/tun.c:tun_flow_cleanup
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
```
**Symbols:**

```
ffffffff811ebf90-ffffffff811ec018: round_jiffies_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long unsigned int round_jiffies_up(long unsigned int j);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81202050)
Location: kernel/time/timer.c:479
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:start_this_handle
  - drivers/net/tun.c:tun_net_init
  - drivers/net/tun.c:tun_flow_update
  - drivers/net/tun.c:tun_flow_cleanup
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
```
**Symbols:**

```
ffffffff81202050-ffffffff812020d9: round_jiffies_up (STB_GLOBAL)
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
long unsigned int round_jiffies_up(long unsigned int j);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffff80001019d6a0)
Location: kernel/time/timer.c:454
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:start_this_handle
  - block/blk-timeout.c:blk_add_timer
  - block/blk-timeout.c:blk_add_timer
  - drivers/net/tun.c:tun_flow_update
  - drivers/net/tun.c:tun_flow_cleanup
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
```
**Symbols:**

```
ffff80001019d6a0-ffff80001019d730: round_jiffies_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long unsigned int round_jiffies_up(long unsigned int j);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (c03e60fc)
Location: kernel/time/timer.c:454
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:start_this_handle
  - block/blk-timeout.c:blk_add_timer
  - block/blk-timeout.c:blk_add_timer
  - drivers/net/tun.c:tun_flow_update
  - drivers/net/tun.c:tun_flow_cleanup
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
```
**Symbols:**

```
c03e60fc-c03e616c: round_jiffies_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long unsigned int round_jiffies_up(long unsigned int j);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (c0000000001fbfe0)
Location: kernel/time/timer.c:454
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:start_this_handle
  - block/blk-timeout.c:blk_add_timer
  - block/blk-timeout.c:blk_add_timer
  - drivers/net/tun.c:tun_flow_update
  - drivers/net/tun.c:tun_flow_cleanup
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
```
**Symbols:**

```
c0000000001fbfe0-c0000000001fc058: round_jiffies_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long unsigned int round_jiffies_up(long unsigned int j);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffe00012af3c)
Location: kernel/time/timer.c:454
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:start_this_handle
  - block/blk-timeout.c:blk_add_timer
  - block/blk-timeout.c:blk_add_timer
  - drivers/net/tun.c:tun_flow_update
  - drivers/net/tun.c:tun_flow_cleanup
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
```
**Symbols:**

```
ffffffe00012af3c-ffffffe00012af90: round_jiffies_up (STB_GLOBAL)
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
long unsigned int round_jiffies_up(long unsigned int j);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff8112c550)
Location: kernel/time/timer.c:454
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:start_this_handle
  - block/blk-timeout.c:blk_add_timer
  - block/blk-timeout.c:blk_add_timer
  - drivers/net/tun.c:tun_flow_update
  - drivers/net/tun.c:tun_flow_cleanup
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
```
**Symbols:**

```
ffffffff8112c550-ffffffff8112c5c3: round_jiffies_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long unsigned int round_jiffies_up(long unsigned int j);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff8111edc0)
Location: kernel/time/timer.c:454
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:start_this_handle
  - block/blk-timeout.c:blk_add_timer
  - block/blk-timeout.c:blk_add_timer
  - drivers/net/tun.c:tun_flow_update
  - drivers/net/tun.c:tun_flow_cleanup
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
```
**Symbols:**

```
ffffffff8111edc0-ffffffff8111ee33: round_jiffies_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long unsigned int round_jiffies_up(long unsigned int j);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff8112a270)
Location: kernel/time/timer.c:454
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:start_this_handle
  - block/blk-timeout.c:blk_add_timer
  - block/blk-timeout.c:blk_add_timer
  - drivers/net/tun.c:tun_flow_update
  - drivers/net/tun.c:tun_flow_cleanup
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
```
**Symbols:**

```
ffffffff8112a270-ffffffff8112a2e3: round_jiffies_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long unsigned int round_jiffies_up(long unsigned int j);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff811368c0)
Location: kernel/time/timer.c:454
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:start_this_handle
  - block/blk-timeout.c:blk_add_timer
  - block/blk-timeout.c:blk_add_timer
  - drivers/net/tun.c:tun_flow_update
  - drivers/net/tun.c:tun_flow_cleanup
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
```
**Symbols:**

```
ffffffff811368c0-ffffffff81136934: round_jiffies_up (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
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
