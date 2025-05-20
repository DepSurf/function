# Function: <code>tcf_chain_put</code>

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
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void tcf_chain_put(struct tcf_chain *chain);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81802c23)
Location: net/sched/cls_api.c:247
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_ctl_tfilter
Direct callers:
  - net/sched/act_api.c:free_tcf
```
**Symbols:**

```
ffffffff81801fd0-ffffffff81801ff5: tcf_chain_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void tcf_chain_put(struct tcf_chain *chain);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81880e11)
Location: net/sched/cls_api.c:249
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_ctl_tfilter
  - net/sched/cls_api.c:tcf_chain_tp_remove
  - net/sched/cls_api.c:tcf_block_put_ext
  - net/sched/cls_api.c:tcf_block_put_ext
  - net/sched/cls_api.c:tcf_chain_flush
Direct callers:
  - net/sched/act_api.c:free_tcf
```
**Symbols:**

```
ffffffff8187f5c0-ffffffff8187f5d8: tcf_chain_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void tcf_chain_put(struct tcf_chain *chain);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff818d3b48)
Location: net/sched/cls_api.c:265
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_chain_flush
Direct callers:
  - net/sched/act_api.c:__tcf_idr_release
```
**Symbols:**

```
ffffffff818d2400-ffffffff818d2417: tcf_chain_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff819000af)
Location: net/sched/cls_api.c:339
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:__tcf_block_put
  - net/sched/cls_api.c:__tcf_block_put
  - net/sched/cls_api.c:tcf_chain_flush
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81960a73)
Location: net/sched/cls_api.c:513
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_block_playback_offloads
  - net/sched/cls_api.c:tcf_block_playback_offloads
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:tcf_proto_destroy
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81997b53)
Location: net/sched/cls_api.c:565
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_block_playback_offloads
  - net/sched/cls_api.c:tcf_block_playback_offloads
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:tcf_proto_destroy
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a7158a)
Location: net/sched/cls_api.c:580
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_block_playback_offloads
  - net/sched/cls_api.c:tcf_block_playback_offloads
  - net/sched/cls_api.c:__tcf_block_put
  - net/sched/cls_api.c:tcf_chain0_head_change_cb_add
  - net/sched/cls_api.c:tcf_proto_destroy
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a7a00a)
Location: net/sched/cls_api.c:580
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_block_playback_offloads
  - net/sched/cls_api.c:tcf_block_playback_offloads
  - net/sched/cls_api.c:__tcf_block_put
  - net/sched/cls_api.c:tcf_chain0_head_change_cb_add
  - net/sched/cls_api.c:tcf_proto_destroy
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a6316f)
Location: net/sched/cls_api.c:580
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_block_playback_offloads
  - net/sched/cls_api.c:tcf_block_playback_offloads
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:__tcf_block_put
  - net/sched/cls_api.c:tcf_proto_destroy
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81b1c4df)
Location: net/sched/cls_api.c:580
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_block_playback_offloads
  - net/sched/cls_api.c:tcf_block_playback_offloads
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:__tcf_block_put
  - net/sched/cls_api.c:tcf_proto_destroy
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81ca1dc5)
Location: net/sched/cls_api.c:597
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_block_playback_offloads
  - net/sched/cls_api.c:tcf_block_playback_offloads
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:__tcf_block_put
  - net/sched/cls_api.c:tcf_proto_destroy
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81e5e63f)
Location: net/sched/cls_api.c:599
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_block_playback_offloads
  - net/sched/cls_api.c:tcf_block_playback_offloads
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:__tcf_block_put
  - net/sched/cls_api.c:tcf_proto_destroy
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81ebc3e7)
Location: net/sched/cls_api.c:704
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_block_playback_offloads
  - net/sched/cls_api.c:tcf_block_playback_offloads
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:__tcf_block_put
  - net/sched/cls_api.c:tcf_proto_destroy
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81f7f604)
Location: net/sched/cls_api.c:704
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_block_playback_offloads
  - net/sched/cls_api.c:tcf_block_playback_offloads
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:__tcf_block_put
  - net/sched/cls_api.c:tcf_proto_destroy
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffff800010c44c14)
Location: net/sched/cls_api.c:565
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_block_playback_offloads
  - net/sched/cls_api.c:tcf_block_playback_offloads
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:tcf_proto_destroy
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (c0d565bc)
Location: net/sched/cls_api.c:565
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_block_playback_offloads
  - net/sched/cls_api.c:tcf_block_playback_offloads
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:tcf_proto_destroy
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (c000000000d4194c)
Location: net/sched/cls_api.c:565
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_block_playback_offloads
  - net/sched/cls_api.c:tcf_block_playback_offloads
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:tcf_proto_destroy
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffe0007b3b52)
Location: net/sched/cls_api.c:565
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_block_playback_offloads
  - net/sched/cls_api.c:tcf_block_playback_offloads
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:tcf_proto_destroy
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff819379c3)
Location: net/sched/cls_api.c:565
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_block_playback_offloads
  - net/sched/cls_api.c:tcf_block_playback_offloads
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:tcf_proto_destroy
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff818f14c3)
Location: net/sched/cls_api.c:565
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_block_playback_offloads
  - net/sched/cls_api.c:tcf_block_playback_offloads
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:tcf_proto_destroy
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81988b53)
Location: net/sched/cls_api.c:565
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_block_playback_offloads
  - net/sched/cls_api.c:tcf_block_playback_offloads
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:tcf_proto_destroy
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff819abe53)
Location: net/sched/cls_api.c:565
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_block_playback_offloads
  - net/sched/cls_api.c:tcf_block_playback_offloads
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:tcf_proto_destroy
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
</ul>
