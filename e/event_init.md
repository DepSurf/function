# Function: <code>event_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int event_init(struct trace_event_call *call);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff8115dac0)
Location: kernel/trace/trace_events.c:2163
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:trace_module_notify
  - kernel/trace/trace_events.c:trace_add_event_call
  - kernel/trace/trace_events.c:trace_event_init
```
**Symbols:**

```
ffffffff8115dac0-ffffffff8115db35: event_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int event_init(struct trace_event_call *call);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff811683f0)
Location: kernel/trace/trace_events.c:2068
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:trace_event_init
  - kernel/trace/trace_events.c:trace_module_notify
  - kernel/trace/trace_events.c:trace_add_event_call
```
**Symbols:**

```
ffffffff811683f0-ffffffff81168475: event_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int event_init(struct trace_event_call *call);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff81173ae0)
Location: kernel/trace/trace_events.c:2037
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:trace_event_init
  - kernel/trace/trace_events.c:trace_module_notify
  - kernel/trace/trace_events.c:trace_add_event_call
```
**Symbols:**

```
ffffffff81173ae0-ffffffff81173b65: event_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int event_init(struct trace_event_call *call);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff81176760)
Location: kernel/trace/trace_events.c:2077
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:trace_event_init
  - kernel/trace/trace_events.c:trace_module_notify
  - kernel/trace/trace_events.c:trace_add_event_call
```
**Symbols:**

```
ffffffff81176760-ffffffff811767c3: event_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int event_init(struct trace_event_call *call);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff81183f20)
Location: kernel/trace/trace_events.c:2081
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:trace_event_init
  - kernel/trace/trace_events.c:trace_module_notify
  - kernel/trace/trace_events.c:trace_add_event_call
```
**Symbols:**

```
ffffffff81183f20-ffffffff81183f86: event_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int event_init(struct trace_event_call *call);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff81193060)
Location: kernel/trace/trace_events.c:2081
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:trace_event_init
  - kernel/trace/trace_events.c:trace_module_notify
  - kernel/trace/trace_events.c:trace_add_event_call
```
**Symbols:**

```
ffffffff81193060-ffffffff811930ca: event_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int event_init(struct trace_event_call *call);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff811a11d0)
Location: kernel/trace/trace_events.c:2082
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:trace_event_init
  - kernel/trace/trace_events.c:trace_module_notify
  - kernel/trace/trace_events.c:trace_add_event_call
```
**Symbols:**

```
ffffffff811a11d0-ffffffff811a123a: event_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int event_init(struct trace_event_call *call);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events.c (0)
Location: kernel/trace/trace_events.c:2072
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:trace_event_init
  - kernel/trace/trace_events.c:trace_module_notify
  - kernel/trace/trace_events.c:trace_add_event_call
```
**Symbols:**

```
ffffffff811aec40-ffffffff811aeca8: event_init (STB_LOCAL)
ffffffff811b245c-ffffffff811b2489: event_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int event_init(struct trace_event_call *call);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events.c (0)
Location: kernel/trace/trace_events.c:2071
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:trace_event_init
  - kernel/trace/trace_events.c:trace_module_notify
  - kernel/trace/trace_events.c:trace_add_event_call
```
**Symbols:**

```
ffffffff811ba5c0-ffffffff811ba631: event_init (STB_LOCAL)
ffffffff811bdac9-ffffffff811bdadd: event_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int event_init(struct trace_event_call *call);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events.c (0)
Location: kernel/trace/trace_events.c:2276
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:trace_module_notify
  - kernel/trace/trace_events.c:trace_add_event_call
```
**Symbols:**

```
ffffffff811d5080-ffffffff811d50f1: event_init (STB_LOCAL)
ffffffff811d73ac-ffffffff811d73c0: event_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int event_init(struct trace_event_call *call);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events.c (0)
Location: kernel/trace/trace_events.c:2289
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:trace_module_notify
  - kernel/trace/trace_events.c:trace_add_event_call
```
**Symbols:**

```
ffffffff811d2210-ffffffff811d2281: event_init (STB_LOCAL)
ffffffff81be6111-ffffffff81be6125: event_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int event_init(struct trace_event_call *call);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events.c (0)
Location: kernel/trace/trace_events.c:2500
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:trace_event_init
  - kernel/trace/trace_events.c:trace_module_notify
  - kernel/trace/trace_events.c:trace_add_event_call
```
**Symbols:**

```
ffffffff811d3660-ffffffff811d36d1: event_init (STB_LOCAL)
ffffffff81bd7da2-ffffffff81bd7db6: event_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int event_init(struct trace_event_call *call);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events.c (0)
Location: kernel/trace/trace_events.c:2502
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:trace_event_init
  - kernel/trace/trace_events.c:trace_module_notify
  - kernel/trace/trace_events.c:trace_add_event_call
```
**Symbols:**

```
ffffffff812003a0-ffffffff81200411: event_init (STB_LOCAL)
ffffffff81cb63a5-ffffffff81cb63b9: event_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int event_init(struct trace_event_call *call);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events.c (0)
Location: kernel/trace/trace_events.c:2521
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:trace_event_init
  - kernel/trace/trace_events.c:trace_module_notify
  - kernel/trace/trace_events.c:trace_add_event_call
```
**Symbols:**

```
ffffffff8123c020-ffffffff8123c09e: event_init (STB_LOCAL)
ffffffff81e67374-ffffffff81e67388: event_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int event_init(struct trace_event_call *call);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff81288870)
Location: kernel/trace/trace_events.c:2542
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:trace_event_init
  - kernel/trace/trace_events.c:trace_module_notify
  - kernel/trace/trace_events.c:trace_add_event_call
```
**Symbols:**

```
ffffffff81288870-ffffffff812888ea: event_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int event_init(struct trace_event_call *call);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff812a55a0)
Location: kernel/trace/trace_events.c:2536
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:trace_event_init
  - kernel/trace/trace_events.c:trace_module_notify
  - kernel/trace/trace_events.c:trace_add_event_call
```
**Symbols:**

```
ffffffff812a55a0-ffffffff812a561a: event_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int event_init(struct trace_event_call *call);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff812c0fc0)
Location: kernel/trace/trace_events.c:2684
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:trace_event_init
  - kernel/trace/trace_events.c:trace_module_notify
  - kernel/trace/trace_events.c:trace_add_event_call
```
**Symbols:**

```
ffffffff812c0fc0-ffffffff812c103a: event_init (STB_LOCAL)
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
int event_init(struct trace_event_call *call);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffff800010238f30)
Location: kernel/trace/trace_events.c:2071
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:trace_event_init
  - kernel/trace/trace_events.c:trace_module_notify
  - kernel/trace/trace_events.c:trace_add_event_call
```
**Symbols:**

```
ffff800010238f30-ffff800010238fc8: event_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int event_init(struct trace_event_call *call);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (c0477088)
Location: kernel/trace/trace_events.c:2071
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:trace_event_init
  - kernel/trace/trace_events.c:trace_module_notify
  - kernel/trace/trace_events.c:trace_add_event_call
```
**Symbols:**

```
c0477088-c0477120: event_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int event_init(struct trace_event_call *call);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (c0000000002c5680)
Location: kernel/trace/trace_events.c:2071
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:trace_event_init
  - kernel/trace/trace_events.c:trace_module_notify
  - kernel/trace/trace_events.c:trace_add_event_call
```
**Symbols:**

```
c0000000002c5680-c0000000002c5774: event_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int event_init(struct trace_event_call *call);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffffffe00018fc3e)
Location: kernel/trace/trace_events.c:2071
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:trace_event_init
  - kernel/trace/trace_events.c:trace_module_notify
  - kernel/trace/trace_events.c:trace_add_event_call
```
**Symbols:**

```
ffffffe00018fc3e-ffffffe00018fcba: event_init (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int event_init(struct trace_event_call *call);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events.c (0)
Location: kernel/trace/trace_events.c:2071
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:trace_event_init
  - kernel/trace/trace_events.c:trace_module_notify
  - kernel/trace/trace_events.c:trace_add_event_call
```
**Symbols:**

```
ffffffff811b2be0-ffffffff811b2c51: event_init (STB_LOCAL)
ffffffff811b60e9-ffffffff811b60fd: event_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int event_init(struct trace_event_call *call);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events.c (0)
Location: kernel/trace/trace_events.c:2071
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:trace_event_init
  - kernel/trace/trace_events.c:trace_module_notify
  - kernel/trace/trace_events.c:trace_add_event_call
```
**Symbols:**

```
ffffffff811a59e0-ffffffff811a5a51: event_init (STB_LOCAL)
ffffffff811a8ee9-ffffffff811a8efd: event_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int event_init(struct trace_event_call *call);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events.c (0)
Location: kernel/trace/trace_events.c:2071
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:trace_event_init
  - kernel/trace/trace_events.c:trace_module_notify
  - kernel/trace/trace_events.c:trace_add_event_call
```
**Symbols:**

```
ffffffff811b09b0-ffffffff811b0a21: event_init (STB_LOCAL)
ffffffff811b3eb9-ffffffff811b3ecd: event_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int event_init(struct trace_event_call *call);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events.c (0)
Location: kernel/trace/trace_events.c:2071
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:trace_event_init
  - kernel/trace/trace_events.c:trace_module_notify
  - kernel/trace/trace_events.c:trace_add_event_call
```
**Symbols:**

```
ffffffff811bea40-ffffffff811beab1: event_init (STB_LOCAL)
ffffffff811c1f59-ffffffff811c1f6d: event_init.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
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
