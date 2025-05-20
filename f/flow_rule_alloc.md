# Function: <code>flow_rule_alloc</code>

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
struct flow_rule *flow_rule_alloc(unsigned int num_actions);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff819315f0)
Location: net/core/flow_offload.c:6
Inline: False
Direct callers:
  - net/core/ethtool.c:ethtool_rx_flow_rule_create
```
**Symbols:**

```
ffffffff819315f0-ffffffff8193161c: flow_rule_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct flow_rule *flow_rule_alloc(unsigned int num_actions);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff81963900)
Location: net/core/flow_offload.c:8
Inline: False
Direct callers:
  - net/core/ethtool.c:ethtool_rx_flow_rule_create
```
**Symbols:**

```
ffffffff81963900-ffffffff81963930: flow_rule_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct flow_rule *flow_rule_alloc(unsigned int num_actions);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff81a36dd0)
Location: net/core/flow_offload.c:9
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:ethtool_rx_flow_rule_create
```
**Symbols:**

```
ffffffff81a36dd0-ffffffff81a36e2a: flow_rule_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct flow_rule *flow_rule_alloc(unsigned int num_actions);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff81a39180)
Location: net/core/flow_offload.c:9
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:ethtool_rx_flow_rule_create
```
**Symbols:**

```
ffffffff81a39180-ffffffff81a391da: flow_rule_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct flow_rule *flow_rule_alloc(unsigned int num_actions);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff81a20430)
Location: net/core/flow_offload.c:9
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:ethtool_rx_flow_rule_create
```
**Symbols:**

```
ffffffff81a20430-ffffffff81a20483: flow_rule_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct flow_rule *flow_rule_alloc(unsigned int num_actions);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff81ad46a0)
Location: net/core/flow_offload.c:9
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:ethtool_rx_flow_rule_create
```
**Symbols:**

```
ffffffff81ad46a0-ffffffff81ad46f3: flow_rule_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct flow_rule *flow_rule_alloc(unsigned int num_actions);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff81c53000)
Location: net/core/flow_offload.c:10
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:ethtool_rx_flow_rule_create
```
**Symbols:**

```
ffffffff81c53000-ffffffff81c5306d: flow_rule_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct flow_rule *flow_rule_alloc(unsigned int num_actions);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff81e08600)
Location: net/core/flow_offload.c:10
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:ethtool_rx_flow_rule_create
```
**Symbols:**

```
ffffffff81e08600-ffffffff81e0866d: flow_rule_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct flow_rule *flow_rule_alloc(unsigned int num_actions);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff81e7af20)
Location: net/core/flow_offload.c:10
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:ethtool_rx_flow_rule_create
```
**Symbols:**

```
ffffffff81e7af20-ffffffff81e7af77: flow_rule_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct flow_rule *flow_rule_alloc(unsigned int num_actions);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff81f3b180)
Location: net/core/flow_offload.c:10
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:ethtool_rx_flow_rule_create
```
**Symbols:**

```
ffffffff81f3b180-ffffffff81f3b1d7: flow_rule_alloc (STB_GLOBAL)
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
struct flow_rule *flow_rule_alloc(unsigned int num_actions);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffff800010c07e48)
Location: net/core/flow_offload.c:8
Inline: False
Direct callers:
  - net/core/ethtool.c:ethtool_rx_flow_rule_create
```
**Symbols:**

```
ffff800010c07e48-ffff800010c07e88: flow_rule_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct flow_rule *flow_rule_alloc(unsigned int num_actions);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (c0d20cc0)
Location: net/core/flow_offload.c:8
Inline: False
Direct callers:
  - net/core/ethtool.c:ethtool_rx_flow_rule_create
```
**Symbols:**

```
c0d20cc0-c0d20d18: flow_rule_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct flow_rule *flow_rule_alloc(unsigned int num_actions);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (c000000000cf2200)
Location: net/core/flow_offload.c:8
Inline: False
Direct callers:
  - net/core/ethtool.c:ethtool_rx_flow_rule_create
```
**Symbols:**

```
c000000000cf2200-c000000000cf2258: flow_rule_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct flow_rule *flow_rule_alloc(unsigned int num_actions);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffe000785ef4)
Location: net/core/flow_offload.c:8
Inline: False
Direct callers:
  - net/core/ethtool.c:ethtool_rx_flow_rule_create
```
**Symbols:**

```
ffffffe000785ef4-ffffffe000785f38: flow_rule_alloc (STB_GLOBAL)
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
struct flow_rule *flow_rule_alloc(unsigned int num_actions);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff819038d0)
Location: net/core/flow_offload.c:8
Inline: False
Direct callers:
  - net/core/ethtool.c:ethtool_rx_flow_rule_create
```
**Symbols:**

```
ffffffff819038d0-ffffffff81903900: flow_rule_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct flow_rule *flow_rule_alloc(unsigned int num_actions);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff818bd700)
Location: net/core/flow_offload.c:8
Inline: False
Direct callers:
  - net/core/ethtool.c:ethtool_rx_flow_rule_create
```
**Symbols:**

```
ffffffff818bd700-ffffffff818bd730: flow_rule_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct flow_rule *flow_rule_alloc(unsigned int num_actions);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff81954900)
Location: net/core/flow_offload.c:8
Inline: False
Direct callers:
  - net/core/ethtool.c:ethtool_rx_flow_rule_create
```
**Symbols:**

```
ffffffff81954900-ffffffff81954930: flow_rule_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct flow_rule *flow_rule_alloc(unsigned int num_actions);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff819765b0)
Location: net/core/flow_offload.c:8
Inline: False
Direct callers:
  - net/core/ethtool.c:ethtool_rx_flow_rule_create
```
**Symbols:**

```
ffffffff819765b0-ffffffff819765e0: flow_rule_alloc (STB_GLOBAL)
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
