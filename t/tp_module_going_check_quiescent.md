# Function: <code>tp_module_going_check_quiescent</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/tracepoint.c (ffffffff8113f626)
Location: kernel/tracepoint.c:389
Inline: True
Inline callers:
  - kernel/tracepoint.c:tracepoint_module_notify
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/tracepoint.c (ffffffff81147c8d)
Location: kernel/tracepoint.c:389
Inline: True
Inline callers:
  - kernel/tracepoint.c:tracepoint_module_notify
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/tracepoint.c (ffffffff81151b2d)
Location: kernel/tracepoint.c:393
Inline: True
Inline callers:
  - kernel/tracepoint.c:tracepoint_module_notify
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/tracepoint.c (ffffffff81154166)
Location: kernel/tracepoint.c:394
Inline: True
Inline callers:
  - kernel/tracepoint.c:tracepoint_module_notify
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/tracepoint.c (ffffffff81160966)
Location: kernel/tracepoint.c:394
Inline: True
Inline callers:
  - kernel/tracepoint.c:tracepoint_module_notify
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/tracepoint.c (ffffffff8116fb60)
Location: kernel/tracepoint.c:392
Inline: True
Inline callers:
  - kernel/tracepoint.c:tracepoint_module_notify
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void tp_module_going_check_quiescent(struct tracepoint *tp, void *priv);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/tracepoint.c (ffffffff8117d310)
Location: kernel/tracepoint.c:451
Inline: True
Direct callers:
  - kernel/tracepoint.c:tracepoint_module_notify
```
**Symbols:**

```
ffffffff8117d310-ffffffff8117d325: tp_module_going_check_quiescent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void tp_module_going_check_quiescent(struct tracepoint *tp, void *priv);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/tracepoint.c (ffffffff8118a1d0)
Location: kernel/tracepoint.c:438
Inline: True
Direct callers:
  - kernel/tracepoint.c:tracepoint_module_notify
```
**Symbols:**

```
ffffffff8118a1d0-ffffffff8118a1e6: tp_module_going_check_quiescent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void tp_module_going_check_quiescent(struct tracepoint *tp, void *priv);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/tracepoint.c (ffffffff811960e0)
Location: kernel/tracepoint.c:438
Inline: True
Direct callers:
  - kernel/tracepoint.c:tracepoint_module_notify
```
**Symbols:**

```
ffffffff811960e0-ffffffff811960f6: tp_module_going_check_quiescent (STB_LOCAL)
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
In kernel/tracepoint.c (ffffffff811ab771)
Location: kernel/tracepoint.c:438
Inline: True
Inline callers:
  - kernel/tracepoint.c:tracepoint_module_notify
  - kernel/tracepoint.c:tracepoint_module_notify
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
In kernel/tracepoint.c (ffffffff811a8d94)
Location: kernel/tracepoint.c:513
Inline: True
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
In kernel/tracepoint.c (ffffffff811a9634)
Location: kernel/tracepoint.c:634
Inline: True
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
In kernel/tracepoint.c (ffffffff811d3224)
Location: kernel/tracepoint.c:634
Inline: True
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
In kernel/tracepoint.c (ffffffff81207c7b)
Location: kernel/tracepoint.c:634
Inline: True
Inline callers:
  - kernel/tracepoint.c:tracepoint_module_notify
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
In kernel/tracepoint.c (ffffffff812500de)
Location: kernel/tracepoint.c:635
Inline: True
Inline callers:
  - kernel/tracepoint.c:tracepoint_module_notify
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
In kernel/tracepoint.c (ffffffff812673ff)
Location: kernel/tracepoint.c:635
Inline: True
Inline callers:
  - kernel/tracepoint.c:tracepoint_module_notify
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
In kernel/tracepoint.c (ffffffff8128138f)
Location: kernel/tracepoint.c:635
Inline: True
Inline callers:
  - kernel/tracepoint.c:tracepoint_module_notify
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void tp_module_going_check_quiescent(struct tracepoint *tp, void *priv);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/tracepoint.c (ffff80001020e398)
Location: kernel/tracepoint.c:438
Inline: True
Direct callers:
  - kernel/tracepoint.c:tracepoint_module_notify
```
**Symbols:**

```
ffff80001020e398-ffff80001020e3d4: tp_module_going_check_quiescent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void tp_module_going_check_quiescent(struct tracepoint *tp, void *priv);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/tracepoint.c (c044cf3c)
Location: kernel/tracepoint.c:438
Inline: True
Direct callers:
  - kernel/tracepoint.c:tracepoint_module_notify
```
**Symbols:**

```
c044cf3c-c044cf90: tp_module_going_check_quiescent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void tp_module_going_check_quiescent(struct tracepoint *tp, void *priv);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/tracepoint.c (c00000000028c6c0)
Location: kernel/tracepoint.c:438
Inline: True
Direct callers:
  - kernel/tracepoint.c:tracepoint_module_notify
```
**Symbols:**

```
c00000000028c6c0-c00000000028c6dc: tp_module_going_check_quiescent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void tp_module_going_check_quiescent(struct tracepoint *tp, void *priv);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/tracepoint.c (ffffffe00016f1bc)
Location: kernel/tracepoint.c:438
Inline: True
Direct callers:
  - kernel/tracepoint.c:tracepoint_module_notify
```
**Symbols:**

```
ffffffe00016f1bc-ffffffe00016f1ec: tp_module_going_check_quiescent (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void tp_module_going_check_quiescent(struct tracepoint *tp, void *priv);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/tracepoint.c (ffffffff8118e700)
Location: kernel/tracepoint.c:438
Inline: True
Direct callers:
  - kernel/tracepoint.c:tracepoint_module_notify
```
**Symbols:**

```
ffffffff8118e700-ffffffff8118e716: tp_module_going_check_quiescent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void tp_module_going_check_quiescent(struct tracepoint *tp, void *priv);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/tracepoint.c (ffffffff81181880)
Location: kernel/tracepoint.c:438
Inline: True
Direct callers:
  - kernel/tracepoint.c:tracepoint_module_notify
```
**Symbols:**

```
ffffffff81181880-ffffffff81181896: tp_module_going_check_quiescent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void tp_module_going_check_quiescent(struct tracepoint *tp, void *priv);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/tracepoint.c (ffffffff8118c4d0)
Location: kernel/tracepoint.c:438
Inline: True
Direct callers:
  - kernel/tracepoint.c:tracepoint_module_notify
```
**Symbols:**

```
ffffffff8118c4d0-ffffffff8118c4e6: tp_module_going_check_quiescent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void tp_module_going_check_quiescent(struct tracepoint *tp, void *priv);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/tracepoint.c (ffffffff81199e60)
Location: kernel/tracepoint.c:438
Inline: True
Direct callers:
  - kernel/tracepoint.c:tracepoint_module_notify
```
**Symbols:**

```
ffffffff81199e60-ffffffff81199e76: tp_module_going_check_quiescent (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
