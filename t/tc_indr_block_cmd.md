# Function: <code>tc_indr_block_cmd</code>

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
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void tc_indr_block_cmd(struct net_device *dev, struct tcf_block *block, flow_indr_block_bind_cb_t *cb, void *cb_priv, enum flow_block_command command, bool ingress);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff819965e0)
Location: net/sched/cls_api.c:608
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_indr_block_get_and_cmd
  - net/sched/cls_api.c:tc_indr_block_get_and_cmd
```
**Symbols:**

```
ffffffff819965e0-ffffffff819966d3: tc_indr_block_cmd (STB_LOCAL)
```
</details>
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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void tc_indr_block_cmd(struct net_device *dev, struct tcf_block *block, flow_indr_block_bind_cb_t *cb, void *cb_priv, enum flow_block_command command, bool ingress);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffff800010c42ed8)
Location: net/sched/cls_api.c:608
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_indr_block_get_and_cmd
  - net/sched/cls_api.c:tc_indr_block_get_and_cmd
```
**Symbols:**

```
ffff800010c42ed8-ffff800010c42ff0: tc_indr_block_cmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void tc_indr_block_cmd(struct net_device *dev, struct tcf_block *block, flow_indr_block_bind_cb_t *cb, void *cb_priv, enum flow_block_command command, bool ingress);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (c0d544a8)
Location: net/sched/cls_api.c:608
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_indr_block_get_and_cmd
  - net/sched/cls_api.c:tc_indr_block_get_and_cmd
```
**Symbols:**

```
c0d544a8-c0d545c0: tc_indr_block_cmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void tc_indr_block_cmd(struct net_device *dev, struct tcf_block *block, flow_indr_block_bind_cb_t *cb, void *cb_priv, enum flow_block_command command, bool ingress);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (c000000000d3ea80)
Location: net/sched/cls_api.c:608
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_indr_block_get_and_cmd
  - net/sched/cls_api.c:tc_indr_block_get_and_cmd
```
**Symbols:**

```
c000000000d3ea80-c000000000d3ec04: tc_indr_block_cmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void tc_indr_block_cmd(struct net_device *dev, struct tcf_block *block, flow_indr_block_bind_cb_t *cb, void *cb_priv, enum flow_block_command command, bool ingress);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffe0007b1e3e)
Location: net/sched/cls_api.c:608
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_indr_block_get_and_cmd
  - net/sched/cls_api.c:tc_indr_block_get_and_cmd
```
**Symbols:**

```
ffffffe0007b1e3e-ffffffe0007b1f14: tc_indr_block_cmd (STB_LOCAL)
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
void tc_indr_block_cmd(struct net_device *dev, struct tcf_block *block, flow_indr_block_bind_cb_t *cb, void *cb_priv, enum flow_block_command command, bool ingress);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81936450)
Location: net/sched/cls_api.c:608
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_indr_block_get_and_cmd
  - net/sched/cls_api.c:tc_indr_block_get_and_cmd
```
**Symbols:**

```
ffffffff81936450-ffffffff81936543: tc_indr_block_cmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void tc_indr_block_cmd(struct net_device *dev, struct tcf_block *block, flow_indr_block_bind_cb_t *cb, void *cb_priv, enum flow_block_command command, bool ingress);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff818eff50)
Location: net/sched/cls_api.c:608
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_indr_block_get_and_cmd
  - net/sched/cls_api.c:tc_indr_block_get_and_cmd
```
**Symbols:**

```
ffffffff818eff50-ffffffff818f0043: tc_indr_block_cmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void tc_indr_block_cmd(struct net_device *dev, struct tcf_block *block, flow_indr_block_bind_cb_t *cb, void *cb_priv, enum flow_block_command command, bool ingress);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff819875e0)
Location: net/sched/cls_api.c:608
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_indr_block_get_and_cmd
  - net/sched/cls_api.c:tc_indr_block_get_and_cmd
```
**Symbols:**

```
ffffffff819875e0-ffffffff819876d3: tc_indr_block_cmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void tc_indr_block_cmd(struct net_device *dev, struct tcf_block *block, flow_indr_block_bind_cb_t *cb, void *cb_priv, enum flow_block_command command, bool ingress);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff819a9aa0)
Location: net/sched/cls_api.c:608
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_indr_block_get_and_cmd
  - net/sched/cls_api.c:tc_indr_block_get_and_cmd
```
**Symbols:**

```
ffffffff819a9aa0-ffffffff819a9b93: tc_indr_block_cmd (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
