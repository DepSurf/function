# Function: <code>tcf_block_bind</code>

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
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff8195eeb5)
Location: net/sched/cls_api.c:1561
Inline: True
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
In net/sched/cls_api.c (ffffffff81996315)
Location: net/sched/cls_api.c:1477
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int tcf_block_bind(struct tcf_block *block, struct flow_block_offload *bo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a6ed10)
Location: net/sched/cls_api.c:1440
Inline: False
```
**Symbols:**

```
ffffffff81a6ed10-ffffffff81a6eea3: tcf_block_bind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int tcf_block_bind(struct tcf_block *block, struct flow_block_offload *bo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a776e0)
Location: net/sched/cls_api.c:1441
Inline: False
```
**Symbols:**

```
ffffffff81a776e0-ffffffff81a77873: tcf_block_bind (STB_LOCAL)
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
In net/sched/cls_api.c (ffffffff81a5fd45)
Location: net/sched/cls_api.c:1441
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int tcf_block_bind(struct tcf_block *block, struct flow_block_offload *bo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/sched/cls_api.c (0)
Location: net/sched/cls_api.c:1442
Inline: False
```
**Symbols:**

```
ffffffff81b18f40-ffffffff81b190e7: tcf_block_bind (STB_LOCAL)
ffffffff81d391d7-ffffffff81d3920d: tcf_block_bind.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int tcf_block_bind(struct tcf_block *block, struct flow_block_offload *bo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/sched/cls_api.c (0)
Location: net/sched/cls_api.c:1459
Inline: False
```
**Symbols:**

```
ffffffff81ca0620-ffffffff81ca07e9: tcf_block_bind (STB_LOCAL)
ffffffff81f059d7-ffffffff81f05a0d: tcf_block_bind.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int tcf_block_bind(struct tcf_block *block, struct flow_block_offload *bo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/sched/cls_api.c (0)
Location: net/sched/cls_api.c:1461
Inline: False
```
**Symbols:**

```
ffffffff81e5c620-ffffffff81e5c7e9: tcf_block_bind (STB_LOCAL)
ffffffff820ad7e1-ffffffff820ad817: tcf_block_bind.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int tcf_block_bind(struct tcf_block *block, struct flow_block_offload *bo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/sched/cls_api.c (0)
Location: net/sched/cls_api.c:1566
Inline: False
```
**Symbols:**

```
ffffffff81eb91b0-ffffffff81eb93a2: tcf_block_bind (STB_LOCAL)
ffffffff8212e9d9-ffffffff8212ea0f: tcf_block_bind.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int tcf_block_bind(struct tcf_block *block, struct flow_block_offload *bo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/sched/cls_api.c (0)
Location: net/sched/cls_api.c:1596
Inline: False
```
**Symbols:**

```
ffffffff81f7c300-ffffffff81f7c4fb: tcf_block_bind (STB_LOCAL)
ffffffff8221077d-ffffffff822107b3: tcf_block_bind.cold (STB_LOCAL)
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
In net/sched/cls_api.c (ffff800010c42bcc)
Location: net/sched/cls_api.c:1477
Inline: True
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
In net/sched/cls_api.c (c0d541bc)
Location: net/sched/cls_api.c:1477
Inline: True
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
In net/sched/cls_api.c (c000000000d3e5f0)
Location: net/sched/cls_api.c:1477
Inline: True
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
In net/sched/cls_api.c (ffffffe0007b1c26)
Location: net/sched/cls_api.c:1477
Inline: True
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
In net/sched/cls_api.c (ffffffff81936185)
Location: net/sched/cls_api.c:1477
Inline: True
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
In net/sched/cls_api.c (ffffffff818efc85)
Location: net/sched/cls_api.c:1477
Inline: True
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
In net/sched/cls_api.c (ffffffff81987315)
Location: net/sched/cls_api.c:1477
Inline: True
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
In net/sched/cls_api.c (ffffffff819a97d5)
Location: net/sched/cls_api.c:1477
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
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
