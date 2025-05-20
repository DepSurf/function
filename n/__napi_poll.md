# Function: <code>__napi_poll</code>

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
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int __napi_poll(struct napi_struct *n, bool *repoll);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:6994
Inline: False
Direct callers:
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:napi_threaded_poll
  - net/core/dev.c:napi_threaded_poll
```
**Symbols:**

```
ffffffff819f2cd0-ffffffff819f2e31: __napi_poll (STB_LOCAL)
ffffffff81c2361c-ffffffff81c2366d: __napi_poll.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int __napi_poll(struct napi_struct *n, bool *repoll);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:6984
Inline: False
Direct callers:
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:napi_threaded_poll
  - net/core/dev.c:napi_threaded_poll
```
**Symbols:**

```
ffffffff81aa3b30-ffffffff81aa3cad: __napi_poll (STB_LOCAL)
ffffffff81d3640c-ffffffff81d36486: __napi_poll.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int __napi_poll(struct napi_struct *n, bool *repoll);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:6479
Inline: False
Direct callers:
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:napi_threaded_poll
  - net/core/dev.c:napi_threaded_poll
```
**Symbols:**

```
ffffffff81c1c500-ffffffff81c1c695: __napi_poll (STB_LOCAL)
ffffffff81f02be9-ffffffff81f02c72: __napi_poll.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int __napi_poll(struct napi_struct *n, bool *repoll);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:6465
Inline: False
Direct callers:
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:napi_threaded_poll
  - net/core/dev.c:napi_threaded_poll
```
**Symbols:**

```
ffffffff81dcd520-ffffffff81dcd70a: __napi_poll (STB_LOCAL)
ffffffff820ab674-ffffffff820ab6a8: __napi_poll.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int __napi_poll(struct napi_struct *n, bool *repoll);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:6446
Inline: False
Direct callers:
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:napi_threaded_poll
  - net/core/dev.c:napi_threaded_poll
```
**Symbols:**

```
ffffffff81e3e080-ffffffff81e3e26f: __napi_poll (STB_LOCAL)
ffffffff8212cdf3-ffffffff8212ce25: __napi_poll.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int __napi_poll(struct napi_struct *n, bool *repoll);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:6562
Inline: False
Direct callers:
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:napi_threaded_poll
  - net/core/dev.c:napi_threaded_poll
```
**Symbols:**

```
ffffffff81efc920-ffffffff81efcb16: __napi_poll (STB_LOCAL)
ffffffff8220eb43-ffffffff8220eb75: __napi_poll.cold (STB_LOCAL)
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
