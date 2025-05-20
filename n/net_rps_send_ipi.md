# Function: <code>net_rps_send_ipi</code>

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
<summary>In <code>4.13</code>: ✅</summary>

```c
void net_rps_send_ipi(struct softnet_data *remsd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817ca770)
Location: net/core/dev.c:5039
Inline: False
Direct callers:
  - net/core/dev.c:dev_cpu_dead
```
**Symbols:**

```
ffffffff817ca770-ffffffff817ca7c7: net_rps_send_ipi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void net_rps_send_ipi(struct softnet_data *remsd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81844270)
Location: net/core/dev.c:5180
Inline: False
Direct callers:
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:process_backlog
```
**Symbols:**

```
ffffffff81844270-ffffffff818442c7: net_rps_send_ipi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void net_rps_send_ipi(struct softnet_data *remsd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8188dfe0)
Location: net/core/dev.c:5310
Inline: False
Direct callers:
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:process_backlog
```
**Symbols:**

```
ffffffff8188dfe0-ffffffff8188e036: net_rps_send_ipi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void net_rps_send_ipi(struct softnet_data *remsd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818aed10)
Location: net/core/dev.c:5860
Inline: False
Direct callers:
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:process_backlog
```
**Symbols:**

```
ffffffff818aed10-ffffffff818aed66: net_rps_send_ipi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void net_rps_send_ipi(struct softnet_data *remsd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818fa8c0)
Location: net/core/dev.c:5870
Inline: False
Direct callers:
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:process_backlog
```
**Symbols:**

```
ffffffff818fa8c0-ffffffff818fa90e: net_rps_send_ipi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void net_rps_send_ipi(struct softnet_data *remsd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8192ca00)
Location: net/core/dev.c:5793
Inline: False
Direct callers:
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:process_backlog
```
**Symbols:**

```
ffffffff8192ca00-ffffffff8192ca4e: net_rps_send_ipi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void net_rps_send_ipi(struct softnet_data *remsd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a07009)
Location: net/core/dev.c:6176
Inline: True
Inline callers:
  - net/core/dev.c:dev_cpu_dead
Direct callers:
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:process_backlog
```
**Symbols:**

```
ffffffff81a02610-ffffffff81a02661: net_rps_send_ipi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void net_rps_send_ipi(struct softnet_data *remsd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a085b9)
Location: net/core/dev.c:6277
Inline: True
Inline callers:
  - net/core/dev.c:dev_cpu_dead
Direct callers:
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:process_backlog
```
**Symbols:**

```
ffffffff81a02e10-ffffffff81a02e61: net_rps_send_ipi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void net_rps_send_ipi(struct softnet_data *remsd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819e8240)
Location: net/core/dev.c:6390
Inline: False
Direct callers:
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:process_backlog
```
**Symbols:**

```
ffffffff819e8240-ffffffff819e8291: net_rps_send_ipi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void net_rps_send_ipi(struct softnet_data *remsd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a99240)
Location: net/core/dev.c:6376
Inline: False
Direct callers:
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:process_backlog
```
**Symbols:**

```
ffffffff81a99240-ffffffff81a99291: net_rps_send_ipi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void net_rps_send_ipi(struct softnet_data *remsd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81c10b80)
Location: net/core/dev.c:5864
Inline: False
Direct callers:
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:net_rps_action_and_irq_enable
```
**Symbols:**

```
ffffffff81c10b80-ffffffff81c10be9: net_rps_send_ipi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void net_rps_send_ipi(struct softnet_data *remsd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81dc0780)
Location: net/core/dev.c:5855
Inline: False
Direct callers:
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:net_rps_action_and_irq_enable
```
**Symbols:**

```
ffffffff81dc0780-ffffffff81dc07e9: net_rps_send_ipi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void net_rps_send_ipi(struct softnet_data *remsd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81e30300)
Location: net/core/dev.c:5831
Inline: False
Direct callers:
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:net_rps_action_and_irq_enable
```
**Symbols:**

```
ffffffff81e30300-ffffffff81e30369: net_rps_send_ipi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void net_rps_send_ipi(struct softnet_data *remsd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81eeee90)
Location: net/core/dev.c:5913
Inline: False
Direct callers:
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:net_rps_action_and_irq_enable
```
**Symbols:**

```
ffffffff81eeee90-ffffffff81eeeef9: net_rps_send_ipi (STB_LOCAL)
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
void net_rps_send_ipi(struct softnet_data *remsd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffff800010bc8ff0)
Location: net/core/dev.c:5793
Inline: False
Direct callers:
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:process_backlog
```
**Symbols:**

```
ffff800010bc8ff0-ffff800010bc9064: net_rps_send_ipi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void net_rps_send_ipi(struct softnet_data *remsd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c0ce56b8)
Location: net/core/dev.c:5793
Inline: False
Direct callers:
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:process_backlog
```
**Symbols:**

```
c0ce56b8-c0ce572c: net_rps_send_ipi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void net_rps_send_ipi(struct softnet_data *remsd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c000000000ca6010)
Location: net/core/dev.c:5793
Inline: False
Direct callers:
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:net_rps_action_and_irq_enable
```
**Symbols:**

```
c000000000ca6010-c000000000ca60b4: net_rps_send_ipi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void net_rps_send_ipi(struct softnet_data *remsd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffe00075577a)
Location: net/core/dev.c:5793
Inline: False
Direct callers:
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:process_backlog
```
**Symbols:**

```
ffffffe00075577a-ffffffe0007557de: net_rps_send_ipi (STB_LOCAL)
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
void net_rps_send_ipi(struct softnet_data *remsd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818cca00)
Location: net/core/dev.c:5793
Inline: False
Direct callers:
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:process_backlog
```
**Symbols:**

```
ffffffff818cca00-ffffffff818cca4e: net_rps_send_ipi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void net_rps_send_ipi(struct softnet_data *remsd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81886a90)
Location: net/core/dev.c:5793
Inline: False
Direct callers:
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:process_backlog
```
**Symbols:**

```
ffffffff81886a90-ffffffff81886ade: net_rps_send_ipi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void net_rps_send_ipi(struct softnet_data *remsd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8191da00)
Location: net/core/dev.c:5793
Inline: False
Direct callers:
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:process_backlog
```
**Symbols:**

```
ffffffff8191da00-ffffffff8191da4e: net_rps_send_ipi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void net_rps_send_ipi(struct softnet_data *remsd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8193f070)
Location: net/core/dev.c:5793
Inline: False
Direct callers:
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:process_backlog
```
**Symbols:**

```
ffffffff8193f070-ffffffff8193f0be: net_rps_send_ipi (STB_LOCAL)
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
