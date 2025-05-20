# Function: <code>tcf_block_owner_del</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void tcf_block_owner_del(struct tcf_block *block, struct Qdisc *q, enum tcf_block_binder_type binder_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff818d2460)
Location: net/sched/cls_api.c:560
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_block_get_ext
```
**Symbols:**

```
ffffffff818d2460-ffffffff818d24bf: tcf_block_owner_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void tcf_block_owner_del(struct tcf_block *block, struct Qdisc *q, enum tcf_block_binder_type binder_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff818fd9c0)
Location: net/sched/cls_api.c:1028
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_block_get_ext
```
**Symbols:**

```
ffffffff818fd9c0-ffffffff818fda1f: tcf_block_owner_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tcf_block_owner_del(struct tcf_block *block, struct Qdisc *q, enum flow_block_binder_type binder_type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/cls_api.c (ffffffff81962c93)
Location: net/sched/cls_api.c:1406
Inline: True
Direct callers:
  - net/sched/cls_api.c:tcf_block_get_ext
```
**Symbols:**

```
ffffffff8195db50-ffffffff8195dbaf: tcf_block_owner_del (STB_LOCAL)
ffffffff81962c93-ffffffff81962ca6: tcf_block_owner_del.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void tcf_block_owner_del(struct tcf_block *block, struct Qdisc *q, enum flow_block_binder_type binder_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81993a30)
Location: net/sched/cls_api.c:1320
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_block_get_ext
```
**Symbols:**

```
ffffffff81993a30-ffffffff81993a8e: tcf_block_owner_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void tcf_block_owner_del(struct tcf_block *block, struct Qdisc *q, enum flow_block_binder_type binder_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a6ba50)
Location: net/sched/cls_api.c:1283
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_block_put
  - net/sched/cls_api.c:tcf_block_get_ext
```
**Symbols:**

```
ffffffff81a6ba50-ffffffff81a6bab0: tcf_block_owner_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void tcf_block_owner_del(struct tcf_block *block, struct Qdisc *q, enum flow_block_binder_type binder_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a74240)
Location: net/sched/cls_api.c:1284
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_block_put
  - net/sched/cls_api.c:tcf_block_get_ext
```
**Symbols:**

```
ffffffff81a74240-ffffffff81a742a0: tcf_block_owner_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void tcf_block_owner_del(struct tcf_block *block, struct Qdisc *q, enum flow_block_binder_type binder_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a5cd90)
Location: net/sched/cls_api.c:1284
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_block_put
  - net/sched/cls_api.c:tcf_block_get_ext
```
**Symbols:**

```
ffffffff81a5cd90-ffffffff81a5cdf0: tcf_block_owner_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void tcf_block_owner_del(struct tcf_block *block, struct Qdisc *q, enum flow_block_binder_type binder_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81b15f40)
Location: net/sched/cls_api.c:1285
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_block_put
  - net/sched/cls_api.c:tcf_block_get_ext
```
**Symbols:**

```
ffffffff81b15f40-ffffffff81b15fa0: tcf_block_owner_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void tcf_block_owner_del(struct tcf_block *block, struct Qdisc *q, enum flow_block_binder_type binder_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81c9d560)
Location: net/sched/cls_api.c:1302
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_block_put
  - net/sched/cls_api.c:tcf_block_get_ext
```
**Symbols:**

```
ffffffff81c9d560-ffffffff81c9d5d8: tcf_block_owner_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void tcf_block_owner_del(struct tcf_block *block, struct Qdisc *q, enum flow_block_binder_type binder_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81e59b20)
Location: net/sched/cls_api.c:1304
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_block_put
  - net/sched/cls_api.c:tcf_block_get_ext
```
**Symbols:**

```
ffffffff81e59b20-ffffffff81e59b98: tcf_block_owner_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void tcf_block_owner_del(struct tcf_block *block, struct Qdisc *q, enum flow_block_binder_type binder_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81eb5560)
Location: net/sched/cls_api.c:1409
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_block_put
  - net/sched/cls_api.c:tcf_block_get_ext
```
**Symbols:**

```
ffffffff81eb5560-ffffffff81eb55d8: tcf_block_owner_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void tcf_block_owner_del(struct tcf_block *block, struct Qdisc *q, enum flow_block_binder_type binder_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81f78280)
Location: net/sched/cls_api.c:1411
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_block_put_ext
  - net/sched/cls_api.c:tcf_block_get_ext
```
**Symbols:**

```
ffffffff81f78280-ffffffff81f782f8: tcf_block_owner_del (STB_LOCAL)
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
void tcf_block_owner_del(struct tcf_block *block, struct Qdisc *q, enum flow_block_binder_type binder_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffff800010c3fdc0)
Location: net/sched/cls_api.c:1320
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_block_get_ext
```
**Symbols:**

```
ffff800010c3fdc0-ffff800010c3fe64: tcf_block_owner_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void tcf_block_owner_del(struct tcf_block *block, struct Qdisc *q, enum flow_block_binder_type binder_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (c0d51d50)
Location: net/sched/cls_api.c:1320
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_block_get_ext
```
**Symbols:**

```
c0d51d50-c0d51de0: tcf_block_owner_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void tcf_block_owner_del(struct tcf_block *block, struct Qdisc *q, enum flow_block_binder_type binder_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (c000000000d3a8a0)
Location: net/sched/cls_api.c:1320
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_block_get_ext
```
**Symbols:**

```
c000000000d3a8a0-c000000000d3a968: tcf_block_owner_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void tcf_block_owner_del(struct tcf_block *block, struct Qdisc *q, enum flow_block_binder_type binder_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffe0007af9ae)
Location: net/sched/cls_api.c:1320
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_block_get_ext
```
**Symbols:**

```
ffffffe0007af9ae-ffffffe0007afa24: tcf_block_owner_del (STB_LOCAL)
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
void tcf_block_owner_del(struct tcf_block *block, struct Qdisc *q, enum flow_block_binder_type binder_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff819338a0)
Location: net/sched/cls_api.c:1320
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_block_get_ext
```
**Symbols:**

```
ffffffff819338a0-ffffffff819338fe: tcf_block_owner_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void tcf_block_owner_del(struct tcf_block *block, struct Qdisc *q, enum flow_block_binder_type binder_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff818ed3a0)
Location: net/sched/cls_api.c:1320
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_block_get_ext
```
**Symbols:**

```
ffffffff818ed3a0-ffffffff818ed3fe: tcf_block_owner_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void tcf_block_owner_del(struct tcf_block *block, struct Qdisc *q, enum flow_block_binder_type binder_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81984a30)
Location: net/sched/cls_api.c:1320
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_block_get_ext
```
**Symbols:**

```
ffffffff81984a30-ffffffff81984a8e: tcf_block_owner_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void tcf_block_owner_del(struct tcf_block *block, struct Qdisc *q, enum flow_block_binder_type binder_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff819a7220)
Location: net/sched/cls_api.c:1320
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_block_get_ext
```
**Symbols:**

```
ffffffff819a7220-ffffffff819a727e: tcf_block_owner_del (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>enum tcf_block_binder_type binder_type</code> ➡️ <code>enum flow_block_binder_type binder_type</code>
</li>
</ul>
</details>
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
