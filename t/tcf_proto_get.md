# Function: <code>tcf_proto_get</code>

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
<summary>In <code>5.3</code>: ✅</summary>

```c
void tcf_proto_get(struct tcf_proto *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff8195cfa0)
Location: net/sched/cls_api.c:216
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_chain_tp_find
  - net/sched/cls_api.c:__tcf_get_next_proto
```
**Symbols:**

```
ffffffff8195cfa0-ffffffff8195cfb5: tcf_proto_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void tcf_proto_get(struct tcf_proto *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff819934a0)
Location: net/sched/cls_api.c:286
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_chain_tp_find
  - net/sched/cls_api.c:__tcf_get_next_proto
```
**Symbols:**

```
ffffffff819934a0-ffffffff819934b5: tcf_proto_get (STB_LOCAL)
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
In net/sched/cls_api.c (ffffffff81a6cd40)
Location: net/sched/cls_api.c:287
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_chain_tp_find
  - net/sched/cls_api.c:tcf_chain_tp_insert_unique
  - net/sched/cls_api.c:__tcf_get_next_proto
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
In net/sched/cls_api.c (ffffffff81a755c0)
Location: net/sched/cls_api.c:287
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_chain_tp_find
  - net/sched/cls_api.c:tcf_chain_tp_insert_unique
  - net/sched/cls_api.c:__tcf_get_next_proto
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
In net/sched/cls_api.c (ffffffff81a5dd00)
Location: net/sched/cls_api.c:287
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_chain_tp_find
  - net/sched/cls_api.c:tcf_chain_tp_insert_unique
  - net/sched/cls_api.c:__tcf_get_next_proto
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
In net/sched/cls_api.c (ffffffff81b16ec0)
Location: net/sched/cls_api.c:287
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_chain_tp_find
  - net/sched/cls_api.c:tcf_chain_tp_insert_unique
  - net/sched/cls_api.c:__tcf_get_next_proto
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
In net/sched/cls_api.c (ffffffff81c9e8a0)
Location: net/sched/cls_api.c:304
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_chain_tp_find
  - net/sched/cls_api.c:tcf_chain_tp_insert_unique
  - net/sched/cls_api.c:__tcf_get_next_proto
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
In net/sched/cls_api.c (ffffffff81e5b040)
Location: net/sched/cls_api.c:306
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_chain_tp_find
  - net/sched/cls_api.c:tcf_chain_tp_insert_unique
  - net/sched/cls_api.c:__tcf_get_next_proto
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
In net/sched/cls_api.c (ffffffff81eb6e00)
Location: net/sched/cls_api.c:408
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_chain_tp_find
  - net/sched/cls_api.c:tcf_chain_tp_insert_unique
  - net/sched/cls_api.c:__tcf_get_next_proto
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
In net/sched/cls_api.c (ffffffff81f79ba0)
Location: net/sched/cls_api.c:408
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_chain_tp_find
  - net/sched/cls_api.c:tcf_chain_tp_insert_unique
  - net/sched/cls_api.c:__tcf_get_next_proto
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
In net/sched/cls_api.c (ffff800010c46414)
Location: net/sched/cls_api.c:286
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:__tcf_get_next_proto
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
In net/sched/cls_api.c (c0d56270)
Location: net/sched/cls_api.c:286
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_chain_tp_find
  - net/sched/cls_api.c:__tcf_get_next_proto
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
In net/sched/cls_api.c (c000000000d4052c)
Location: net/sched/cls_api.c:286
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:__tcf_get_next_proto
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
In net/sched/cls_api.c (ffffffe0007b2e72)
Location: net/sched/cls_api.c:286
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:__tcf_get_next_proto
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
void tcf_proto_get(struct tcf_proto *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81933310)
Location: net/sched/cls_api.c:286
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_chain_tp_find
  - net/sched/cls_api.c:__tcf_get_next_proto
```
**Symbols:**

```
ffffffff81933310-ffffffff81933325: tcf_proto_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void tcf_proto_get(struct tcf_proto *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff818ece10)
Location: net/sched/cls_api.c:286
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_chain_tp_find
  - net/sched/cls_api.c:__tcf_get_next_proto
```
**Symbols:**

```
ffffffff818ece10-ffffffff818ece25: tcf_proto_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void tcf_proto_get(struct tcf_proto *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff819844a0)
Location: net/sched/cls_api.c:286
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_chain_tp_find
  - net/sched/cls_api.c:__tcf_get_next_proto
```
**Symbols:**

```
ffffffff819844a0-ffffffff819844b5: tcf_proto_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void tcf_proto_get(struct tcf_proto *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff819a69e0)
Location: net/sched/cls_api.c:286
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_chain_tp_find
  - net/sched/cls_api.c:__tcf_get_next_proto
```
**Symbols:**

```
ffffffff819a69e0-ffffffff819a69f5: tcf_proto_get (STB_LOCAL)
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
</ul>
<b>Arch</b>
<ul>
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
