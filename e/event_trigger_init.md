# Function: <code>event_trigger_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int event_trigger_init(struct event_trigger_ops *ops, struct event_trigger_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff81165820)
Location: kernel/trace/trace_events_trigger.c:404
Inline: False
```
**Symbols:**

```
ffffffff81165820-ffffffff8116582c: event_trigger_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int event_trigger_init(struct event_trigger_ops *ops, struct event_trigger_data *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff8116ff80)
Location: kernel/trace/trace_events_trigger.c:416
Inline: False
```
**Symbols:**

```
ffffffff8116ff80-ffffffff8116ff8c: event_trigger_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int event_trigger_init(struct event_trigger_ops *ops, struct event_trigger_data *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff8117b6f0)
Location: kernel/trace/trace_events_trigger.c:416
Inline: False
```
**Symbols:**

```
ffffffff8117b6f0-ffffffff8117b6fc: event_trigger_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int event_trigger_init(struct event_trigger_ops *ops, struct event_trigger_data *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff8117e3d0)
Location: kernel/trace/trace_events_trigger.c:417
Inline: False
```
**Symbols:**

```
ffffffff8117e3d0-ffffffff8117e3dc: event_trigger_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int event_trigger_init(struct event_trigger_ops *ops, struct event_trigger_data *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff8118bc60)
Location: kernel/trace/trace_events_trigger.c:417
Inline: False
```
**Symbols:**

```
ffffffff8118bc60-ffffffff8118bc6c: event_trigger_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int event_trigger_init(struct event_trigger_ops *ops, struct event_trigger_data *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff8119b479)
Location: kernel/trace/trace_events_trigger.c:416
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:event_trigger_callback
```
**Symbols:**

```
ffffffff8119a6a0-ffffffff8119a6a7: event_trigger_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int event_trigger_init(struct event_trigger_ops *ops, struct event_trigger_data *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff811a9679)
Location: kernel/trace/trace_events_trigger.c:405
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:event_trigger_callback
```
**Symbols:**

```
ffffffff811a8890-ffffffff811a8897: event_trigger_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int event_trigger_init(struct event_trigger_ops *ops, struct event_trigger_data *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff811b75f1)
Location: kernel/trace/trace_events_trigger.c:405
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:event_trigger_callback
```
**Symbols:**

```
ffffffff811b67d0-ffffffff811b67d7: event_trigger_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int event_trigger_init(struct event_trigger_ops *ops, struct event_trigger_data *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff811c2c61)
Location: kernel/trace/trace_events_trigger.c:412
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:event_trigger_callback
```
**Symbols:**

```
ffffffff811c1e10-ffffffff811c1e17: event_trigger_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int event_trigger_init(struct event_trigger_ops *ops, struct event_trigger_data *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff811dc51c)
Location: kernel/trace/trace_events_trigger.c:418
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:event_trigger_callback
```
**Symbols:**

```
ffffffff811db8e0-ffffffff811db8e7: event_trigger_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int event_trigger_init(struct event_trigger_ops *ops, struct event_trigger_data *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff811d964c)
Location: kernel/trace/trace_events_trigger.c:418
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:event_trigger_callback
```
**Symbols:**

```
ffffffff811d8a10-ffffffff811d8a17: event_trigger_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int event_trigger_init(struct event_trigger_ops *ops, struct event_trigger_data *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff811daba7)
Location: kernel/trace/trace_events_trigger.c:419
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:event_trigger_callback
```
**Symbols:**

```
ffffffff811d9f80-ffffffff811d9f87: event_trigger_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int event_trigger_init(struct event_trigger_ops *ops, struct event_trigger_data *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff81208177)
Location: kernel/trace/trace_events_trigger.c:431
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:event_trigger_callback
```
**Symbols:**

```
ffffffff812072f0-ffffffff812072f7: event_trigger_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int event_trigger_init(struct event_trigger_data *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff812447c6)
Location: kernel/trace/trace_events_trigger.c:444
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_parse
  - kernel/trace/trace_events_trigger.c:event_trigger_parse
```
**Symbols:**

```
ffffffff81242c40-ffffffff81242c4d: event_trigger_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int event_trigger_init(struct event_trigger_data *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff812924c6)
Location: kernel/trace/trace_events_trigger.c:445
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_parse
  - kernel/trace/trace_events_trigger.c:event_trigger_parse
```
**Symbols:**

```
ffffffff812905f0-ffffffff812905fd: event_trigger_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int event_trigger_init(struct event_trigger_data *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff812af726)
Location: kernel/trace/trace_events_trigger.c:447
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_parse
  - kernel/trace/trace_events_trigger.c:event_trigger_parse
```
**Symbols:**

```
ffffffff812ad860-ffffffff812ad86d: event_trigger_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int event_trigger_init(struct event_trigger_data *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff812cbc95)
Location: kernel/trace/trace_events_trigger.c:447
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_parse
  - kernel/trace/trace_events_trigger.c:event_trigger_parse
```
**Symbols:**

```
ffffffff812c9d80-ffffffff812c9d8d: event_trigger_init (STB_GLOBAL)
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
int event_trigger_init(struct event_trigger_ops *ops, struct event_trigger_data *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffff800010242524)
Location: kernel/trace/trace_events_trigger.c:412
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:event_trigger_callback
```
**Symbols:**

```
ffff800010241508-ffff80001024151c: event_trigger_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int event_trigger_init(struct event_trigger_ops *ops, struct event_trigger_data *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (c047de98)
Location: kernel/trace/trace_events_trigger.c:412
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:event_trigger_callback
```
**Symbols:**

```
c047cf84-c047cfa4: event_trigger_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int event_trigger_init(struct event_trigger_ops *ops, struct event_trigger_data *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (c0000000002d4814)
Location: kernel/trace/trace_events_trigger.c:412
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:event_trigger_callback
```
**Symbols:**

```
c0000000002d28c0-c0000000002d28d4: event_trigger_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int event_trigger_init(struct event_trigger_ops *ops, struct event_trigger_data *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffe000197244)
Location: kernel/trace/trace_events_trigger.c:412
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:event_trigger_callback
```
**Symbols:**

```
ffffffe0001964f8-ffffffe00019650c: event_trigger_init (STB_GLOBAL)
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
int event_trigger_init(struct event_trigger_ops *ops, struct event_trigger_data *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff811bb281)
Location: kernel/trace/trace_events_trigger.c:412
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:event_trigger_callback
```
**Symbols:**

```
ffffffff811ba430-ffffffff811ba437: event_trigger_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int event_trigger_init(struct event_trigger_ops *ops, struct event_trigger_data *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff811ae061)
Location: kernel/trace/trace_events_trigger.c:412
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:event_trigger_callback
```
**Symbols:**

```
ffffffff811ad210-ffffffff811ad217: event_trigger_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int event_trigger_init(struct event_trigger_ops *ops, struct event_trigger_data *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff811b9051)
Location: kernel/trace/trace_events_trigger.c:412
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:event_trigger_callback
```
**Symbols:**

```
ffffffff811b8200-ffffffff811b8207: event_trigger_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int event_trigger_init(struct event_trigger_ops *ops, struct event_trigger_data *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff811c70f1)
Location: kernel/trace/trace_events_trigger.c:412
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_func
  - kernel/trace/trace_events_trigger.c:event_trigger_callback
```
**Symbols:**

```
ffffffff811c62a0-ffffffff811c62a7: event_trigger_init (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct event_trigger_ops *ops</code>
</li>
<li>
<b>Param reordered. </b>
<code>ops, data</code> ➡️ <code>data</code>
</li>
</ul>
</details>
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
