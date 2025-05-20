# Function: <code>trace_event_trigger_enable_disable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff811663ad)
Location: kernel/trace/trace_events_trigger.c:433
Inline: True
Direct callers:
  - kernel/trace/trace_events_trigger.c:event_enable_unregister_trigger
  - kernel/trace/trace_events_trigger.c:unregister_trigger
  - kernel/trace/trace_events_trigger.c:clear_event_triggers
```
**Symbols:**

```
ffffffff811664e0-ffffffff8116650b: trace_event_trigger_enable_disable.constprop.11 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int trace_event_trigger_enable_disable(struct trace_event_file *file, int trigger_enable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff811712df)
Location: kernel/trace/trace_events_trigger.c:445
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_register_trigger
  - kernel/trace/trace_events_trigger.c:register_trigger
Direct callers:
  - kernel/trace/trace_events_trigger.c:event_enable_unregister_trigger
  - kernel/trace/trace_events_trigger.c:event_enable_register_trigger
  - kernel/trace/trace_events_trigger.c:unregister_trigger
  - kernel/trace/trace_events_trigger.c:register_trigger
  - kernel/trace/trace_events_trigger.c:clear_event_triggers
  - kernel/trace/trace_events_hist.c:hist_enable_unreg_all
  - kernel/trace/trace_events_hist.c:hist_unreg_all
  - kernel/trace/trace_events_hist.c:hist_unregister_trigger
  - kernel/trace/trace_events_hist.c:hist_register_trigger
```
**Symbols:**

```
ffffffff81170a60-ffffffff81170a8f: trace_event_trigger_enable_disable.part.8 (STB_LOCAL)
ffffffff81171090-ffffffff811710c5: trace_event_trigger_enable_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

```c
int trace_event_trigger_enable_disable(struct trace_event_file *file, int trigger_enable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff8117ca4f)
Location: kernel/trace/trace_events_trigger.c:445
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_register_trigger
  - kernel/trace/trace_events_trigger.c:register_trigger
Direct callers:
  - kernel/trace/trace_events_trigger.c:event_enable_unregister_trigger
  - kernel/trace/trace_events_trigger.c:event_enable_register_trigger
  - kernel/trace/trace_events_trigger.c:unregister_trigger
  - kernel/trace/trace_events_trigger.c:register_trigger
  - kernel/trace/trace_events_trigger.c:clear_event_triggers
  - kernel/trace/trace_events_hist.c:hist_enable_unreg_all
  - kernel/trace/trace_events_hist.c:hist_unreg_all
  - kernel/trace/trace_events_hist.c:hist_unregister_trigger
  - kernel/trace/trace_events_hist.c:hist_register_trigger
```
**Symbols:**

```
ffffffff8117c1d0-ffffffff8117c1ff: trace_event_trigger_enable_disable.part.10 (STB_LOCAL)
ffffffff8117c800-ffffffff8117c835: trace_event_trigger_enable_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int trace_event_trigger_enable_disable(struct trace_event_file *file, int trigger_enable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff8117f6be)
Location: kernel/trace/trace_events_trigger.c:446
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_register_trigger
  - kernel/trace/trace_events_trigger.c:register_trigger
Direct callers:
  - kernel/trace/trace_events_trigger.c:event_enable_unregister_trigger
  - kernel/trace/trace_events_trigger.c:event_enable_register_trigger
  - kernel/trace/trace_events_trigger.c:unregister_trigger
  - kernel/trace/trace_events_trigger.c:register_trigger
  - kernel/trace/trace_events_trigger.c:clear_event_triggers
  - kernel/trace/trace_events_hist.c:hist_enable_unreg_all
  - kernel/trace/trace_events_hist.c:hist_unreg_all
  - kernel/trace/trace_events_hist.c:hist_unregister_trigger
  - kernel/trace/trace_events_hist.c:hist_register_trigger
```
**Symbols:**

```
ffffffff8117ee90-ffffffff8117eebf: trace_event_trigger_enable_disable.part.10 (STB_LOCAL)
ffffffff8117f460-ffffffff8117f495: trace_event_trigger_enable_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int trace_event_trigger_enable_disable(struct trace_event_file *file, int trigger_enable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff8118cfc1)
Location: kernel/trace/trace_events_trigger.c:446
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_register_trigger
  - kernel/trace/trace_events_trigger.c:register_trigger
Direct callers:
  - kernel/trace/trace_events_trigger.c:event_enable_unregister_trigger
  - kernel/trace/trace_events_trigger.c:event_enable_register_trigger
  - kernel/trace/trace_events_trigger.c:unregister_trigger
  - kernel/trace/trace_events_trigger.c:register_trigger
  - kernel/trace/trace_events_trigger.c:clear_event_triggers
  - kernel/trace/trace_events_hist.c:hist_enable_unreg_all
  - kernel/trace/trace_events_hist.c:hist_unreg_all
  - kernel/trace/trace_events_hist.c:hist_unregister_trigger
  - kernel/trace/trace_events_hist.c:hist_register_trigger
```
**Symbols:**

```
ffffffff8118c750-ffffffff8118c780: trace_event_trigger_enable_disable.part.10 (STB_LOCAL)
ffffffff8118cd60-ffffffff8118cd95: trace_event_trigger_enable_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
int trace_event_trigger_enable_disable(struct trace_event_file *file, int trigger_enable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff8119bb01)
Location: kernel/trace/trace_events_trigger.c:445
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_register_trigger
  - kernel/trace/trace_events_trigger.c:register_trigger
Direct callers:
  - kernel/trace/trace_events_trigger.c:event_enable_unregister_trigger
  - kernel/trace/trace_events_trigger.c:event_enable_register_trigger
  - kernel/trace/trace_events_trigger.c:unregister_trigger
  - kernel/trace/trace_events_trigger.c:register_trigger
  - kernel/trace/trace_events_trigger.c:clear_event_triggers
  - kernel/trace/trace_events_hist.c:hist_enable_unreg_all
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:hist_unregister_trigger
```
**Symbols:**

```
ffffffff8119b1e0-ffffffff8119b210: trace_event_trigger_enable_disable.part.13 (STB_LOCAL)
ffffffff8119b860-ffffffff8119b895: trace_event_trigger_enable_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
int trace_event_trigger_enable_disable(struct trace_event_file *file, int trigger_enable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff811a9c61)
Location: kernel/trace/trace_events_trigger.c:434
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_register_trigger
  - kernel/trace/trace_events_trigger.c:register_trigger
Direct callers:
  - kernel/trace/trace_events_trigger.c:event_enable_unregister_trigger
  - kernel/trace/trace_events_trigger.c:event_enable_register_trigger
  - kernel/trace/trace_events_trigger.c:unregister_trigger
  - kernel/trace/trace_events_trigger.c:register_trigger
  - kernel/trace/trace_events_trigger.c:clear_event_triggers
  - kernel/trace/trace_events_hist.c:hist_enable_unreg_all
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:hist_unregister_trigger
```
**Symbols:**

```
ffffffff811a93e0-ffffffff811a9410: trace_event_trigger_enable_disable.part.13 (STB_LOCAL)
ffffffff811a9a60-ffffffff811a9a95: trace_event_trigger_enable_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int trace_event_trigger_enable_disable(struct trace_event_file *file, int trigger_enable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff811b7be0)
Location: kernel/trace/trace_events_trigger.c:434
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_register_trigger
  - kernel/trace/trace_events_trigger.c:register_trigger
Direct callers:
  - kernel/trace/trace_events_trigger.c:event_enable_unregister_trigger
  - kernel/trace/trace_events_trigger.c:event_enable_register_trigger
  - kernel/trace/trace_events_trigger.c:unregister_trigger
  - kernel/trace/trace_events_trigger.c:register_trigger
  - kernel/trace/trace_events_trigger.c:clear_event_triggers
  - kernel/trace/trace_events_hist.c:hist_enable_unreg_all
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:hist_unregister_trigger
```
**Symbols:**

```
ffffffff811b7330-ffffffff811b7363: trace_event_trigger_enable_disable.part.0 (STB_LOCAL)
ffffffff811b79e0-ffffffff811b7a15: trace_event_trigger_enable_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int trace_event_trigger_enable_disable(struct trace_event_file *file, int trigger_enable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff811c3250)
Location: kernel/trace/trace_events_trigger.c:441
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_register_trigger
  - kernel/trace/trace_events_trigger.c:register_trigger
Direct callers:
  - kernel/trace/trace_events_trigger.c:event_enable_unregister_trigger
  - kernel/trace/trace_events_trigger.c:event_enable_register_trigger
  - kernel/trace/trace_events_trigger.c:unregister_trigger
  - kernel/trace/trace_events_trigger.c:register_trigger
  - kernel/trace/trace_events_trigger.c:clear_event_triggers
  - kernel/trace/trace_events_hist.c:hist_enable_unreg_all
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:hist_unregister_trigger
```
**Symbols:**

```
ffffffff811c29a0-ffffffff811c29d3: trace_event_trigger_enable_disable.part.0 (STB_LOCAL)
ffffffff811c3050-ffffffff811c3085: trace_event_trigger_enable_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int trace_event_trigger_enable_disable(struct trace_event_file *file, int trigger_enable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff811dccad)
Location: kernel/trace/trace_events_trigger.c:447
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:clear_event_triggers
Direct callers:
  - kernel/trace/trace_events_trigger.c:event_enable_unregister_trigger
  - kernel/trace/trace_events_trigger.c:event_enable_register_trigger
  - kernel/trace/trace_events_trigger.c:unregister_trigger
  - kernel/trace/trace_events_trigger.c:register_trigger
  - kernel/trace/trace_events_hist.c:hist_enable_unreg_all
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:hist_unregister_trigger
```
**Symbols:**

```
ffffffff811dcc00-ffffffff811dcc58: trace_event_trigger_enable_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int trace_event_trigger_enable_disable(struct trace_event_file *file, int trigger_enable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff811d9ddd)
Location: kernel/trace/trace_events_trigger.c:447
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:clear_event_triggers
Direct callers:
  - kernel/trace/trace_events_trigger.c:event_enable_unregister_trigger
  - kernel/trace/trace_events_trigger.c:event_enable_register_trigger
  - kernel/trace/trace_events_trigger.c:unregister_trigger
  - kernel/trace/trace_events_trigger.c:register_trigger
  - kernel/trace/trace_events_hist.c:hist_enable_unreg_all
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:hist_unregister_trigger
```
**Symbols:**

```
ffffffff811d9d30-ffffffff811d9d88: trace_event_trigger_enable_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int trace_event_trigger_enable_disable(struct trace_event_file *file, int trigger_enable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff811db33d)
Location: kernel/trace/trace_events_trigger.c:448
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:clear_event_triggers
Direct callers:
  - kernel/trace/trace_events_trigger.c:event_enable_unregister_trigger
  - kernel/trace/trace_events_trigger.c:event_enable_register_trigger
  - kernel/trace/trace_events_trigger.c:unregister_trigger
  - kernel/trace/trace_events_trigger.c:register_trigger
  - kernel/trace/trace_events_hist.c:hist_enable_unreg_all
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:hist_unregister_trigger
```
**Symbols:**

```
ffffffff811db290-ffffffff811db2e8: trace_event_trigger_enable_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int trace_event_trigger_enable_disable(struct trace_event_file *file, int trigger_enable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff8120894d)
Location: kernel/trace/trace_events_trigger.c:460
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:clear_event_triggers
Direct callers:
  - kernel/trace/trace_events_trigger.c:event_enable_unregister_trigger
  - kernel/trace/trace_events_trigger.c:event_enable_register_trigger
  - kernel/trace/trace_events_trigger.c:unregister_trigger
  - kernel/trace/trace_events_trigger.c:register_trigger
  - kernel/trace/trace_eprobe.c:enable_trace_eprobe
  - kernel/trace/trace_events_hist.c:hist_enable_unreg_all
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:hist_unregister_trigger
```
**Symbols:**

```
ffffffff812088a0-ffffffff812088f8: trace_event_trigger_enable_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int trace_event_trigger_enable_disable(struct trace_event_file *file, int trigger_enable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff81243f6a)
Location: kernel/trace/trace_events_trigger.c:470
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:clear_event_triggers
Direct callers:
  - kernel/trace/trace_events_trigger.c:event_enable_unregister_trigger
  - kernel/trace/trace_events_trigger.c:event_enable_register_trigger
  - kernel/trace/trace_events_trigger.c:unregister_trigger
  - kernel/trace/trace_events_trigger.c:register_trigger
  - kernel/trace/trace_eprobe.c:enable_trace_eprobe
  - kernel/trace/trace_events_hist.c:hist_enable_unreg_all
  - kernel/trace/trace_events_hist.c:event_hist_trigger_parse
  - kernel/trace/trace_events_hist.c:hist_unregister_trigger
```
**Symbols:**

```
ffffffff81243e90-ffffffff81243f06: trace_event_trigger_enable_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int trace_event_trigger_enable_disable(struct trace_event_file *file, int trigger_enable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff81291baa)
Location: kernel/trace/trace_events_trigger.c:471
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:clear_event_triggers
Direct callers:
  - kernel/trace/trace_events_trigger.c:event_enable_unregister_trigger
  - kernel/trace/trace_events_trigger.c:event_enable_register_trigger
  - kernel/trace/trace_events_trigger.c:unregister_trigger
  - kernel/trace/trace_events_trigger.c:register_trigger
  - kernel/trace/trace_eprobe.c:enable_trace_eprobe
  - kernel/trace/trace_events_hist.c:hist_enable_unreg_all
  - kernel/trace/trace_events_hist.c:event_hist_trigger_parse
  - kernel/trace/trace_events_hist.c:hist_unregister_trigger
```
**Symbols:**

```
ffffffff81291ac0-ffffffff81291b36: trace_event_trigger_enable_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int trace_event_trigger_enable_disable(struct trace_event_file *file, int trigger_enable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff812aee0a)
Location: kernel/trace/trace_events_trigger.c:473
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:clear_event_triggers
Direct callers:
  - kernel/trace/trace_events_trigger.c:event_enable_unregister_trigger
  - kernel/trace/trace_events_trigger.c:event_enable_register_trigger
  - kernel/trace/trace_events_trigger.c:unregister_trigger
  - kernel/trace/trace_events_trigger.c:register_trigger
  - kernel/trace/trace_eprobe.c:enable_trace_eprobe
  - kernel/trace/trace_events_hist.c:hist_enable_unreg_all
  - kernel/trace/trace_events_hist.c:event_hist_trigger_parse
  - kernel/trace/trace_events_hist.c:hist_unregister_trigger
```
**Symbols:**

```
ffffffff812aed20-ffffffff812aed96: trace_event_trigger_enable_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int trace_event_trigger_enable_disable(struct trace_event_file *file, int trigger_enable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff812cb32a)
Location: kernel/trace/trace_events_trigger.c:473
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:clear_event_triggers
Direct callers:
  - kernel/trace/trace_events_trigger.c:event_enable_unregister_trigger
  - kernel/trace/trace_events_trigger.c:event_enable_register_trigger
  - kernel/trace/trace_events_trigger.c:unregister_trigger
  - kernel/trace/trace_events_trigger.c:register_trigger
  - kernel/trace/trace_eprobe.c:enable_trace_eprobe
  - kernel/trace/trace_events_hist.c:hist_enable_unreg_all
  - kernel/trace/trace_events_hist.c:event_hist_trigger_parse
  - kernel/trace/trace_events_hist.c:hist_unregister_trigger
```
**Symbols:**

```
ffffffff812cb240-ffffffff812cb2b6: trace_event_trigger_enable_disable (STB_GLOBAL)
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
int trace_event_trigger_enable_disable(struct trace_event_file *file, int trigger_enable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffff800010242920)
Location: kernel/trace/trace_events_trigger.c:441
Inline: True
Direct callers:
  - kernel/trace/trace_events_trigger.c:event_enable_unregister_trigger
  - kernel/trace/trace_events_trigger.c:event_enable_register_trigger
  - kernel/trace/trace_events_trigger.c:unregister_trigger
  - kernel/trace/trace_events_trigger.c:register_trigger
  - kernel/trace/trace_events_trigger.c:clear_event_triggers
  - kernel/trace/trace_events_hist.c:hist_enable_unreg_all
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:hist_unregister_trigger
```
**Symbols:**

```
ffff800010242920-ffff800010242a08: trace_event_trigger_enable_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
int trace_event_trigger_enable_disable(struct trace_event_file *file, int trigger_enable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_trigger.c (c047e4c4)
Location: kernel/trace/trace_events_trigger.c:441
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_register_trigger
  - kernel/trace/trace_events_trigger.c:register_trigger
Direct callers:
  - kernel/trace/trace_events_trigger.c:event_enable_unregister_trigger
  - kernel/trace/trace_events_trigger.c:event_enable_register_trigger
  - kernel/trace/trace_events_trigger.c:unregister_trigger
  - kernel/trace/trace_events_trigger.c:register_trigger
  - kernel/trace/trace_events_trigger.c:clear_event_triggers
```
**Symbols:**

```
c047daac-c047db10: trace_event_trigger_enable_disable.part.0 (STB_LOCAL)
c047e274-c047e2e8: trace_event_trigger_enable_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int trace_event_trigger_enable_disable(struct trace_event_file *file, int trigger_enable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (c0000000002d5020)
Location: kernel/trace/trace_events_trigger.c:441
Inline: True
Direct callers:
  - kernel/trace/trace_events_trigger.c:event_enable_unregister_trigger
  - kernel/trace/trace_events_trigger.c:event_enable_register_trigger
  - kernel/trace/trace_events_trigger.c:unregister_trigger
  - kernel/trace/trace_events_trigger.c:register_trigger
  - kernel/trace/trace_events_trigger.c:clear_event_triggers
  - kernel/trace/trace_events_hist.c:hist_enable_unreg_all
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:hist_unregister_trigger
```
**Symbols:**

```
c0000000002d5020-c0000000002d5110: trace_event_trigger_enable_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int trace_event_trigger_enable_disable(struct trace_event_file *file, int trigger_enable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffe000197708)
Location: kernel/trace/trace_events_trigger.c:441
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_register_trigger
  - kernel/trace/trace_events_trigger.c:event_enable_register_trigger
  - kernel/trace/trace_events_trigger.c:register_trigger
  - kernel/trace/trace_events_trigger.c:register_trigger
Direct callers:
  - kernel/trace/trace_events_trigger.c:event_enable_unregister_trigger
  - kernel/trace/trace_events_trigger.c:unregister_trigger
  - kernel/trace/trace_events_trigger.c:clear_event_triggers
```
**Symbols:**

```
ffffffe000197508-ffffffe00019757c: trace_event_trigger_enable_disable (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
int trace_event_trigger_enable_disable(struct trace_event_file *file, int trigger_enable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff811bb870)
Location: kernel/trace/trace_events_trigger.c:441
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_register_trigger
  - kernel/trace/trace_events_trigger.c:register_trigger
Direct callers:
  - kernel/trace/trace_events_trigger.c:event_enable_unregister_trigger
  - kernel/trace/trace_events_trigger.c:event_enable_register_trigger
  - kernel/trace/trace_events_trigger.c:unregister_trigger
  - kernel/trace/trace_events_trigger.c:register_trigger
  - kernel/trace/trace_events_trigger.c:clear_event_triggers
  - kernel/trace/trace_events_hist.c:hist_enable_unreg_all
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:hist_unregister_trigger
```
**Symbols:**

```
ffffffff811bafc0-ffffffff811baff3: trace_event_trigger_enable_disable.part.0 (STB_LOCAL)
ffffffff811bb670-ffffffff811bb6a5: trace_event_trigger_enable_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int trace_event_trigger_enable_disable(struct trace_event_file *file, int trigger_enable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff811ae650)
Location: kernel/trace/trace_events_trigger.c:441
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_register_trigger
  - kernel/trace/trace_events_trigger.c:register_trigger
Direct callers:
  - kernel/trace/trace_events_trigger.c:event_enable_unregister_trigger
  - kernel/trace/trace_events_trigger.c:event_enable_register_trigger
  - kernel/trace/trace_events_trigger.c:unregister_trigger
  - kernel/trace/trace_events_trigger.c:register_trigger
  - kernel/trace/trace_events_trigger.c:clear_event_triggers
  - kernel/trace/trace_events_hist.c:hist_enable_unreg_all
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:hist_unregister_trigger
```
**Symbols:**

```
ffffffff811adda0-ffffffff811addd3: trace_event_trigger_enable_disable.part.0 (STB_LOCAL)
ffffffff811ae450-ffffffff811ae485: trace_event_trigger_enable_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int trace_event_trigger_enable_disable(struct trace_event_file *file, int trigger_enable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff811b9640)
Location: kernel/trace/trace_events_trigger.c:441
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_register_trigger
  - kernel/trace/trace_events_trigger.c:register_trigger
Direct callers:
  - kernel/trace/trace_events_trigger.c:event_enable_unregister_trigger
  - kernel/trace/trace_events_trigger.c:event_enable_register_trigger
  - kernel/trace/trace_events_trigger.c:unregister_trigger
  - kernel/trace/trace_events_trigger.c:register_trigger
  - kernel/trace/trace_events_trigger.c:clear_event_triggers
  - kernel/trace/trace_events_hist.c:hist_enable_unreg_all
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:hist_unregister_trigger
```
**Symbols:**

```
ffffffff811b8d90-ffffffff811b8dc3: trace_event_trigger_enable_disable.part.0 (STB_LOCAL)
ffffffff811b9440-ffffffff811b9475: trace_event_trigger_enable_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int trace_event_trigger_enable_disable(struct trace_event_file *file, int trigger_enable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff811c76e0)
Location: kernel/trace/trace_events_trigger.c:441
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_register_trigger
  - kernel/trace/trace_events_trigger.c:register_trigger
Direct callers:
  - kernel/trace/trace_events_trigger.c:event_enable_unregister_trigger
  - kernel/trace/trace_events_trigger.c:event_enable_register_trigger
  - kernel/trace/trace_events_trigger.c:unregister_trigger
  - kernel/trace/trace_events_trigger.c:register_trigger
  - kernel/trace/trace_events_trigger.c:clear_event_triggers
  - kernel/trace/trace_events_hist.c:hist_enable_unreg_all
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:hist_unregister_trigger
```
**Symbols:**

```
ffffffff811c6e30-ffffffff811c6e63: trace_event_trigger_enable_disable.part.0 (STB_LOCAL)
ffffffff811c74e0-ffffffff811c7515: trace_event_trigger_enable_disable (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
