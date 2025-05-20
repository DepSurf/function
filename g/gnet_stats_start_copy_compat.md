# Function: <code>gnet_stats_start_copy_compat</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int gnet_stats_start_copy_compat(struct sk_buff *skb, int type, int tc_stats_type, int xstats_type, spinlock_t *lock, struct gnet_dump *d);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (ffffffff8170ef10)
Location: net/core/gen_stats.c:61
Inline: False
Direct callers:
  - net/core/gen_stats.c:gnet_stats_start_copy
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/act_api.c:tcf_action_copy_stats
```
**Symbols:**

```
ffffffff8170ef10-ffffffff8170efeb: gnet_stats_start_copy_compat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int gnet_stats_start_copy_compat(struct sk_buff *skb, int type, int tc_stats_type, int xstats_type, spinlock_t *lock, struct gnet_dump *d, int padattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (ffffffff81776760)
Location: net/core/gen_stats.c:63
Inline: False
Direct callers:
  - net/core/gen_stats.c:gnet_stats_start_copy
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/act_api.c:tcf_action_copy_stats
```
**Symbols:**

```
ffffffff81776760-ffffffff8177682d: gnet_stats_start_copy_compat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int gnet_stats_start_copy_compat(struct sk_buff *skb, int type, int tc_stats_type, int xstats_type, spinlock_t *lock, struct gnet_dump *d, int padattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (ffffffff817a39e0)
Location: net/core/gen_stats.c:63
Inline: False
Direct callers:
  - net/core/gen_stats.c:gnet_stats_start_copy
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/act_api.c:tcf_action_copy_stats
```
**Symbols:**

```
ffffffff817a39e0-ffffffff817a3aad: gnet_stats_start_copy_compat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int gnet_stats_start_copy_compat(struct sk_buff *skb, int type, int tc_stats_type, int xstats_type, spinlock_t *lock, struct gnet_dump *d, int padattr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (ffffffff817c1c20)
Location: net/core/gen_stats.c:63
Inline: True
Direct callers:
  - net/core/gen_stats.c:gnet_stats_start_copy
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/act_api.c:tcf_action_copy_stats
```
**Symbols:**

```
ffffffff817c1c20-ffffffff817c1cf2: gnet_stats_start_copy_compat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int gnet_stats_start_copy_compat(struct sk_buff *skb, int type, int tc_stats_type, int xstats_type, spinlock_t *lock, struct gnet_dump *d, int padattr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (ffffffff8183b640)
Location: net/core/gen_stats.c:63
Inline: True
Direct callers:
  - net/core/gen_stats.c:gnet_stats_start_copy
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/act_api.c:tcf_action_copy_stats
```
**Symbols:**

```
ffffffff8183b640-ffffffff8183b712: gnet_stats_start_copy_compat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int gnet_stats_start_copy_compat(struct sk_buff *skb, int type, int tc_stats_type, int xstats_type, spinlock_t *lock, struct gnet_dump *d, int padattr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (ffffffff818860a0)
Location: net/core/gen_stats.c:63
Inline: True
Direct callers:
  - net/core/gen_stats.c:gnet_stats_start_copy
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/act_api.c:tcf_action_copy_stats
```
**Symbols:**

```
ffffffff818860a0-ffffffff8188618f: gnet_stats_start_copy_compat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int gnet_stats_start_copy_compat(struct sk_buff *skb, int type, int tc_stats_type, int xstats_type, spinlock_t *lock, struct gnet_dump *d, int padattr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (ffffffff818a6580)
Location: net/core/gen_stats.c:63
Inline: True
Direct callers:
  - net/core/gen_stats.c:gnet_stats_start_copy
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/act_api.c:tcf_action_copy_stats
```
**Symbols:**

```
ffffffff818a6580-ffffffff818a666f: gnet_stats_start_copy_compat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int gnet_stats_start_copy_compat(struct sk_buff *skb, int type, int tc_stats_type, int xstats_type, spinlock_t *lock, struct gnet_dump *d, int padattr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (ffffffff818f18c0)
Location: net/core/gen_stats.c:59
Inline: True
Direct callers:
  - net/core/gen_stats.c:gnet_stats_start_copy
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/act_api.c:tcf_action_copy_stats
```
**Symbols:**

```
ffffffff818f18c0-ffffffff818f19af: gnet_stats_start_copy_compat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int gnet_stats_start_copy_compat(struct sk_buff *skb, int type, int tc_stats_type, int xstats_type, spinlock_t *lock, struct gnet_dump *d, int padattr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (ffffffff81923810)
Location: net/core/gen_stats.c:59
Inline: True
Direct callers:
  - net/core/gen_stats.c:gnet_stats_start_copy
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/act_api.c:tcf_action_copy_stats
```
**Symbols:**

```
ffffffff81923810-ffffffff819238ff: gnet_stats_start_copy_compat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int gnet_stats_start_copy_compat(struct sk_buff *skb, int type, int tc_stats_type, int xstats_type, spinlock_t *lock, struct gnet_dump *d, int padattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (ffffffff819f7600)
Location: net/core/gen_stats.c:59
Inline: False
Direct callers:
  - net/core/gen_stats.c:gnet_stats_start_copy
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/act_api.c:tcf_action_copy_stats
```
**Symbols:**

```
ffffffff819f7600-ffffffff819f76f1: gnet_stats_start_copy_compat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int gnet_stats_start_copy_compat(struct sk_buff *skb, int type, int tc_stats_type, int xstats_type, spinlock_t *lock, struct gnet_dump *d, int padattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (ffffffff819f7070)
Location: net/core/gen_stats.c:59
Inline: False
Direct callers:
  - net/core/gen_stats.c:gnet_stats_start_copy
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/act_api.c:tcf_action_copy_stats
```
**Symbols:**

```
ffffffff819f7070-ffffffff819f7161: gnet_stats_start_copy_compat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int gnet_stats_start_copy_compat(struct sk_buff *skb, int type, int tc_stats_type, int xstats_type, spinlock_t *lock, struct gnet_dump *d, int padattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (ffffffff819dd200)
Location: net/core/gen_stats.c:59
Inline: False
Direct callers:
  - net/core/gen_stats.c:gnet_stats_start_copy
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/act_api.c:tcf_action_copy_stats
```
**Symbols:**

```
ffffffff819dd200-ffffffff819dd2f1: gnet_stats_start_copy_compat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int gnet_stats_start_copy_compat(struct sk_buff *skb, int type, int tc_stats_type, int xstats_type, spinlock_t *lock, struct gnet_dump *d, int padattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (ffffffff81a8d490)
Location: net/core/gen_stats.c:59
Inline: False
Direct callers:
  - net/core/gen_stats.c:gnet_stats_start_copy
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/act_api.c:tcf_action_copy_stats
```
**Symbols:**

```
ffffffff81a8d490-ffffffff81a8d581: gnet_stats_start_copy_compat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int gnet_stats_start_copy_compat(struct sk_buff *skb, int type, int tc_stats_type, int xstats_type, spinlock_t *lock, struct gnet_dump *d, int padattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (ffffffff81c02e70)
Location: net/core/gen_stats.c:59
Inline: False
Direct callers:
  - net/core/gen_stats.c:gnet_stats_start_copy
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/act_api.c:tcf_action_copy_stats
```
**Symbols:**

```
ffffffff81c02e70-ffffffff81c02f79: gnet_stats_start_copy_compat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int gnet_stats_start_copy_compat(struct sk_buff *skb, int type, int tc_stats_type, int xstats_type, spinlock_t *lock, struct gnet_dump *d, int padattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (ffffffff81db24c0)
Location: net/core/gen_stats.c:59
Inline: False
Direct callers:
  - net/core/gen_stats.c:gnet_stats_start_copy
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/act_api.c:tcf_action_copy_stats
```
**Symbols:**

```
ffffffff81db24c0-ffffffff81db25c9: gnet_stats_start_copy_compat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int gnet_stats_start_copy_compat(struct sk_buff *skb, int type, int tc_stats_type, int xstats_type, spinlock_t *lock, struct gnet_dump *d, int padattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (ffffffff81e22a90)
Location: net/core/gen_stats.c:59
Inline: False
Direct callers:
  - net/core/gen_stats.c:gnet_stats_start_copy
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/act_api.c:tcf_action_copy_stats
```
**Symbols:**

```
ffffffff81e22a90-ffffffff81e22b99: gnet_stats_start_copy_compat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int gnet_stats_start_copy_compat(struct sk_buff *skb, int type, int tc_stats_type, int xstats_type, spinlock_t *lock, struct gnet_dump *d, int padattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (ffffffff81ee09d0)
Location: net/core/gen_stats.c:59
Inline: False
Direct callers:
  - net/core/gen_stats.c:gnet_stats_start_copy
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/act_api.c:tcf_action_copy_stats
```
**Symbols:**

```
ffffffff81ee09d0-ffffffff81ee0ad9: gnet_stats_start_copy_compat (STB_GLOBAL)
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
int gnet_stats_start_copy_compat(struct sk_buff *skb, int type, int tc_stats_type, int xstats_type, spinlock_t *lock, struct gnet_dump *d, int padattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (ffff800010bbf278)
Location: net/core/gen_stats.c:59
Inline: False
Direct callers:
  - net/core/gen_stats.c:gnet_stats_start_copy
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/act_api.c:tcf_action_copy_stats
```
**Symbols:**

```
ffff800010bbf278-ffff800010bbf3e8: gnet_stats_start_copy_compat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int gnet_stats_start_copy_compat(struct sk_buff *skb, int type, int tc_stats_type, int xstats_type, spinlock_t *lock, struct gnet_dump *d, int padattr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (c0cda8ec)
Location: net/core/gen_stats.c:59
Inline: True
Direct callers:
  - net/core/gen_stats.c:gnet_stats_start_copy
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/act_api.c:tcf_action_copy_stats
```
**Symbols:**

```
c0cda8ec-c0cda9ec: gnet_stats_start_copy_compat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int gnet_stats_start_copy_compat(struct sk_buff *skb, int type, int tc_stats_type, int xstats_type, spinlock_t *lock, struct gnet_dump *d, int padattr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (c000000000c98010)
Location: net/core/gen_stats.c:59
Inline: True
Direct callers:
  - net/core/gen_stats.c:gnet_stats_start_copy
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/act_api.c:tcf_action_copy_stats
```
**Symbols:**

```
c000000000c98010-c000000000c98180: gnet_stats_start_copy_compat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int gnet_stats_start_copy_compat(struct sk_buff *skb, int type, int tc_stats_type, int xstats_type, spinlock_t *lock, struct gnet_dump *d, int padattr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (ffffffe00074caea)
Location: net/core/gen_stats.c:59
Inline: True
Direct callers:
  - net/core/gen_stats.c:gnet_stats_start_copy
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/act_api.c:tcf_action_copy_stats
```
**Symbols:**

```
ffffffe00074caea-ffffffe00074cbc6: gnet_stats_start_copy_compat (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int gnet_stats_start_copy_compat(struct sk_buff *skb, int type, int tc_stats_type, int xstats_type, spinlock_t *lock, struct gnet_dump *d, int padattr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (ffffffff818c3810)
Location: net/core/gen_stats.c:59
Inline: True
Direct callers:
  - net/core/gen_stats.c:gnet_stats_start_copy
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/act_api.c:tcf_action_copy_stats
```
**Symbols:**

```
ffffffff818c3810-ffffffff818c38ff: gnet_stats_start_copy_compat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int gnet_stats_start_copy_compat(struct sk_buff *skb, int type, int tc_stats_type, int xstats_type, spinlock_t *lock, struct gnet_dump *d, int padattr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (ffffffff8187d750)
Location: net/core/gen_stats.c:59
Inline: True
Direct callers:
  - net/core/gen_stats.c:gnet_stats_start_copy
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/act_api.c:tcf_action_copy_stats
```
**Symbols:**

```
ffffffff8187d750-ffffffff8187d83f: gnet_stats_start_copy_compat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int gnet_stats_start_copy_compat(struct sk_buff *skb, int type, int tc_stats_type, int xstats_type, spinlock_t *lock, struct gnet_dump *d, int padattr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (ffffffff81914810)
Location: net/core/gen_stats.c:59
Inline: True
Direct callers:
  - net/core/gen_stats.c:gnet_stats_start_copy
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/act_api.c:tcf_action_copy_stats
```
**Symbols:**

```
ffffffff81914810-ffffffff819148ff: gnet_stats_start_copy_compat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int gnet_stats_start_copy_compat(struct sk_buff *skb, int type, int tc_stats_type, int xstats_type, spinlock_t *lock, struct gnet_dump *d, int padattr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (ffffffff819359e0)
Location: net/core/gen_stats.c:59
Inline: True
Direct callers:
  - net/core/gen_stats.c:gnet_stats_start_copy
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/act_api.c:tcf_action_copy_stats
```
**Symbols:**

```
ffffffff819359e0-ffffffff81935acf: gnet_stats_start_copy_compat (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int padattr</code>
</li>
</ul>
</details>
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
