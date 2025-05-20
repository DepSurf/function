# Function: <code>__tcf_block_cb_register</code>

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
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct tcf_block_cb *__tcf_block_cb_register(struct tcf_block *block, tc_setup_cb_t *cb, void *cb_ident, void *cb_priv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81880053)
Location: net/sched/cls_api.c:415
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_cb_register
```
**Symbols:**

```
ffffffff818802f0-ffffffff81880353: __tcf_block_cb_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct tcf_block_cb *__tcf_block_cb_register(struct tcf_block *block, tc_setup_cb_t *cb, void *cb_ident, void *cb_priv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/cls_api.c (ffffffff818d3915)
Location: net/sched/cls_api.c:749
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_cb_register
Direct callers:
  - net/sched/cls_api.c:tcf_block_cb_register
```
**Symbols:**

```
ffffffff818d3870-ffffffff818d38e3: __tcf_block_cb_register.part.24 (STB_LOCAL)
ffffffff818d38f0-ffffffff818d390f: __tcf_block_cb_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct tcf_block_cb *__tcf_block_cb_register(struct tcf_block *block, tc_setup_cb_t *cb, void *cb_ident, void *cb_priv, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff818fe020)
Location: net/sched/cls_api.c:1212
Inline: True
Direct callers:
  - net/sched/cls_api.c:tcf_block_cb_register
```
**Symbols:**

```
ffffffff818fe020-ffffffff818fe0b8: __tcf_block_cb_register (STB_GLOBAL)
```
</details>
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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct netlink_ext_ack *extack</code>
</li>
</ul>
</details>
</li>
</ul>
