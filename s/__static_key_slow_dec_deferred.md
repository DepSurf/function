# Function: <code>__static_key_slow_dec_deferred</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void __static_key_slow_dec_deferred(struct static_key *key, struct delayed_work *work, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff81211340)
Location: kernel/jump_label.c:280
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:clean_acked_data_disable
  - net/ipv6/ip6_flowlabel.c:fl_free
```
**Symbols:**

```
ffffffff81211340-ffffffff812113a6: __static_key_slow_dec_deferred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void __static_key_slow_dec_deferred(struct static_key *key, struct delayed_work *work, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff8121ee10)
Location: kernel/jump_label.c:280
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:clean_acked_data_disable
  - net/ipv6/ip6_flowlabel.c:fl_free
```
**Symbols:**

```
ffffffff8121ee10-ffffffff8121ee76: __static_key_slow_dec_deferred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __static_key_slow_dec_deferred(struct static_key *key, struct delayed_work *work, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff8124ab90)
Location: kernel/jump_label.c:280
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:clean_acked_data_disable
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ip6_fl_gc
```
**Symbols:**

```
ffffffff8124ab90-ffffffff8124abf6: __static_key_slow_dec_deferred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __static_key_slow_dec_deferred(struct static_key *key, struct delayed_work *work, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff812552d0)
Location: kernel/jump_label.c:280
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:clean_acked_data_disable
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:ip6_fl_gc
```
**Symbols:**

```
ffffffff812552d0-ffffffff81255336: __static_key_slow_dec_deferred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __static_key_slow_dec_deferred(struct static_key *key, struct delayed_work *work, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff812597d0)
Location: kernel/jump_label.c:280
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:clean_acked_data_disable
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:ip6_fl_gc
```
**Symbols:**

```
ffffffff812597d0-ffffffff81259836: __static_key_slow_dec_deferred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void __static_key_slow_dec_deferred(struct static_key *key, struct delayed_work *work, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/jump_label.c (0)
Location: kernel/jump_label.c:280
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:clean_acked_data_disable
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:ip6_fl_gc
```
**Symbols:**

```
ffffffff81cb9c03-ffffffff81cb9c17: __static_key_slow_dec_deferred.cold (STB_LOCAL)
ffffffff81295510-ffffffff81295584: __static_key_slow_dec_deferred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void __static_key_slow_dec_deferred(struct static_key *key, struct delayed_work *work, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/jump_label.c (0)
Location: kernel/jump_label.c:280
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:clean_acked_data_disable
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:ip6_fl_gc
```
**Symbols:**

```
ffffffff81e6b1ff-ffffffff81e6b214: __static_key_slow_dec_deferred.cold (STB_LOCAL)
ffffffff812eb300-ffffffff812eb385: __static_key_slow_dec_deferred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void __static_key_slow_dec_deferred(struct static_key *key, struct delayed_work *work, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/jump_label.c (0)
Location: kernel/jump_label.c:308
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:clean_acked_data_disable
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:ip6_fl_gc
```
**Symbols:**

```
ffffffff82061f7d-ffffffff82061f92: __static_key_slow_dec_deferred.cold (STB_LOCAL)
ffffffff813553b0-ffffffff81355435: __static_key_slow_dec_deferred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void __static_key_slow_dec_deferred(struct static_key *key, struct delayed_work *work, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/jump_label.c (0)
Location: kernel/jump_label.c:308
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:clean_acked_data_disable
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:ip6_fl_gc
```
**Symbols:**

```
ffffffff820e17ab-ffffffff820e17c0: __static_key_slow_dec_deferred.cold (STB_LOCAL)
ffffffff813868a0-ffffffff81386925: __static_key_slow_dec_deferred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void __static_key_slow_dec_deferred(struct static_key *key, struct delayed_work *work, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/jump_label.c (0)
Location: kernel/jump_label.c:308
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:clean_acked_data_disable
  - net/ipv4/tcp_ipv4.c:tcp_md5sig_info_free_rcu
  - net/ipv4/tcp_minisocks.c:tcp_md5_twsk_free_rcu
  - net/ipv4/tcp_ao.c:tcp_ao_destroy_sock
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:ip6_fl_gc
```
**Symbols:**

```
ffffffff821be20e-ffffffff821be223: __static_key_slow_dec_deferred.cold (STB_LOCAL)
ffffffff813afd60-ffffffff813afde5: __static_key_slow_dec_deferred (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void __static_key_slow_dec_deferred(struct static_key *key, struct delayed_work *work, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffff8000102ab1a8)
Location: kernel/jump_label.c:280
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:clean_acked_data_disable
  - net/ipv6/ip6_flowlabel.c:fl_free
```
**Symbols:**

```
ffff8000102ab1a8-ffff8000102ab234: __static_key_slow_dec_deferred (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void __static_key_slow_dec_deferred(struct static_key *key, struct delayed_work *work, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (c00000000035ed40)
Location: kernel/jump_label.c:280
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:clean_acked_data_disable
  - net/ipv6/ip6_flowlabel.c:fl_free
```
**Symbols:**

```
c00000000035ed40-c00000000035ee04: __static_key_slow_dec_deferred (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void __static_key_slow_dec_deferred(struct static_key *key, struct delayed_work *work, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff81217460)
Location: kernel/jump_label.c:280
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:clean_acked_data_disable
  - net/ipv6/ip6_flowlabel.c:fl_free
```
**Symbols:**

```
ffffffff81217460-ffffffff812174c6: __static_key_slow_dec_deferred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void __static_key_slow_dec_deferred(struct static_key *key, struct delayed_work *work, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff8120a1c0)
Location: kernel/jump_label.c:280
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:clean_acked_data_disable
  - net/ipv6/ip6_flowlabel.c:fl_free
```
**Symbols:**

```
ffffffff8120a1c0-ffffffff8120a226: __static_key_slow_dec_deferred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void __static_key_slow_dec_deferred(struct static_key *key, struct delayed_work *work, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff81215200)
Location: kernel/jump_label.c:280
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:clean_acked_data_disable
  - net/ipv6/ip6_flowlabel.c:fl_free
```
**Symbols:**

```
ffffffff81215200-ffffffff81215266: __static_key_slow_dec_deferred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void __static_key_slow_dec_deferred(struct static_key *key, struct delayed_work *work, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff812241f0)
Location: kernel/jump_label.c:280
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:clean_acked_data_disable
  - net/ipv6/ip6_flowlabel.c:fl_free
```
**Symbols:**

```
ffffffff812241f0-ffffffff81224256: __static_key_slow_dec_deferred (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
