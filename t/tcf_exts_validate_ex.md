# Function: <code>tcf_exts_validate_ex</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int tcf_exts_validate_ex(struct net *net, struct tcf_proto *tp, struct nlattr **tb, struct nlattr *rate_tlv, struct tcf_exts *exts, u32 flags, u32 fl_flags, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81c9d620)
Location: net/sched/cls_api.c:3055
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_exts_validate
```
**Symbols:**

```
ffffffff81c9d620-ffffffff81c9d7d1: tcf_exts_validate_ex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int tcf_exts_validate_ex(struct net *net, struct tcf_proto *tp, struct nlattr **tb, struct nlattr *rate_tlv, struct tcf_exts *exts, u32 flags, u32 fl_flags, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81e59c00)
Location: net/sched/cls_api.c:3055
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_exts_validate
```
**Symbols:**

```
ffffffff81e59c00-ffffffff81e59db1: tcf_exts_validate_ex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int tcf_exts_validate_ex(struct net *net, struct tcf_proto *tp, struct nlattr **tb, struct nlattr *rate_tlv, struct tcf_exts *exts, u32 flags, u32 fl_flags, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81eb55f0)
Location: net/sched/cls_api.c:3262
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_exts_validate
```
**Symbols:**

```
ffffffff81eb55f0-ffffffff81eb57a1: tcf_exts_validate_ex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int tcf_exts_validate_ex(struct net *net, struct tcf_proto *tp, struct nlattr **tb, struct nlattr *rate_tlv, struct tcf_exts *exts, u32 flags, u32 fl_flags, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81f78310)
Location: net/sched/cls_api.c:3319
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_exts_validate
```
**Symbols:**

```
ffffffff81f78310-ffffffff81f784b5: tcf_exts_validate_ex (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
