# Function: <code>resolve_var_refs</code>

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
bool resolve_var_refs(struct hist_trigger_data *hist_data, void *key, u64 *var_ref_vals, bool self);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff8119c4e0)
Location: kernel/trace/trace_events_hist.c:1630
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger
  - kernel/trace/trace_events_hist.c:event_hist_trigger
```
**Symbols:**

```
ffffffff8119c4e0-ffffffff8119c604: resolve_var_refs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool resolve_var_refs(struct hist_trigger_data *hist_data, void *key, u64 *var_ref_vals, bool self);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811aa8a0)
Location: kernel/trace/trace_events_hist.c:1714
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger
  - kernel/trace/trace_events_hist.c:event_hist_trigger
```
**Symbols:**

```
ffffffff811aa8a0-ffffffff811aa9c4: resolve_var_refs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool resolve_var_refs(struct hist_trigger_data *hist_data, void *key, u64 *var_ref_vals, bool self);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811b8930)
Location: kernel/trace/trace_events_hist.c:1866
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger
  - kernel/trace/trace_events_hist.c:event_hist_trigger
```
**Symbols:**

```
ffffffff811b8930-ffffffff811b8a30: resolve_var_refs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool resolve_var_refs(struct hist_trigger_data *hist_data, void *key, u64 *var_ref_vals, bool self);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811c3f10)
Location: kernel/trace/trace_events_hist.c:1944
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger
  - kernel/trace/trace_events_hist.c:event_hist_trigger
```
**Symbols:**

```
ffffffff811c3f10-ffffffff811c4010: resolve_var_refs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool resolve_var_refs(struct hist_trigger_data *hist_data, void *key, u64 *var_ref_vals, bool self);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811e0c40)
Location: kernel/trace/trace_events_hist.c:1035
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger
  - kernel/trace/trace_events_hist.c:event_hist_trigger
```
**Symbols:**

```
ffffffff811e0c40-ffffffff811e0d40: resolve_var_refs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool resolve_var_refs(struct hist_trigger_data *hist_data, void *key, u64 *var_ref_vals, bool self);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811de600)
Location: kernel/trace/trace_events_hist.c:1038
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger
  - kernel/trace/trace_events_hist.c:event_hist_trigger
```
**Symbols:**

```
ffffffff811de600-ffffffff811de700: resolve_var_refs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool resolve_var_refs(struct hist_trigger_data *hist_data, void *key, u64 *var_ref_vals, bool self);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811df9b0)
Location: kernel/trace/trace_events_hist.c:1055
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger
  - kernel/trace/trace_events_hist.c:event_hist_trigger
```
**Symbols:**

```
ffffffff811df9b0-ffffffff811dfab0: resolve_var_refs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool resolve_var_refs(struct hist_trigger_data *hist_data, void *key, u64 *var_ref_vals, bool self);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_hist.c (0)
Location: kernel/trace/trace_events_hist.c:1079
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger
  - kernel/trace/trace_events_hist.c:event_hist_trigger
```
**Symbols:**

```
ffffffff8120fdd0-ffffffff8120ff06: resolve_var_refs (STB_LOCAL)
ffffffff81cb6e98-ffffffff81cb6ebb: resolve_var_refs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool resolve_var_refs(struct hist_trigger_data *hist_data, void *key, u64 *var_ref_vals, bool self);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_hist.c (0)
Location: kernel/trace/trace_events_hist.c:1253
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger
  - kernel/trace/trace_events_hist.c:event_hist_trigger
```
**Symbols:**

```
ffffffff8124ca10-ffffffff8124cb68: resolve_var_refs (STB_LOCAL)
ffffffff81e67f35-ffffffff81e67f58: resolve_var_refs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool resolve_var_refs(struct hist_trigger_data *hist_data, void *key, u64 *var_ref_vals, bool self);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_hist.c (0)
Location: kernel/trace/trace_events_hist.c:1286
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger
  - kernel/trace/trace_events_hist.c:event_hist_trigger
```
**Symbols:**

```
ffffffff8129af60-ffffffff8129b0b8: resolve_var_refs (STB_LOCAL)
ffffffff8205e8c5-ffffffff8205e8e8: resolve_var_refs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool resolve_var_refs(struct hist_trigger_data *hist_data, void *key, u64 *var_ref_vals, bool self);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_hist.c (0)
Location: kernel/trace/trace_events_hist.c:1283
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger
  - kernel/trace/trace_events_hist.c:event_hist_trigger
```
**Symbols:**

```
ffffffff812b86d0-ffffffff812b8823: resolve_var_refs (STB_LOCAL)
ffffffff820dd409-ffffffff820dd42c: resolve_var_refs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool resolve_var_refs(struct hist_trigger_data *hist_data, void *key, u64 *var_ref_vals, bool self);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_hist.c (0)
Location: kernel/trace/trace_events_hist.c:1276
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger
  - kernel/trace/trace_events_hist.c:event_hist_trigger
```
**Symbols:**

```
ffffffff812d4d20-ffffffff812d4e73: resolve_var_refs (STB_LOCAL)
ffffffff821b920d-ffffffff821b9230: resolve_var_refs.cold (STB_LOCAL)
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
bool resolve_var_refs(struct hist_trigger_data *hist_data, void *key, u64 *var_ref_vals, bool self);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffff800010243b28)
Location: kernel/trace/trace_events_hist.c:1944
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger
  - kernel/trace/trace_events_hist.c:event_hist_trigger
```
**Symbols:**

```
ffff800010243b28-ffff800010243c34: resolve_var_refs (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool resolve_var_refs(struct hist_trigger_data *hist_data, void *key, u64 *var_ref_vals, bool self);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (c0000000002d6ac0)
Location: kernel/trace/trace_events_hist.c:1944
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger
  - kernel/trace/trace_events_hist.c:event_hist_trigger
```
**Symbols:**

```
c0000000002d6ac0-c0000000002d6c54: resolve_var_refs (STB_LOCAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
bool resolve_var_refs(struct hist_trigger_data *hist_data, void *key, u64 *var_ref_vals, bool self);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811bc530)
Location: kernel/trace/trace_events_hist.c:1944
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger
  - kernel/trace/trace_events_hist.c:event_hist_trigger
```
**Symbols:**

```
ffffffff811bc530-ffffffff811bc630: resolve_var_refs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool resolve_var_refs(struct hist_trigger_data *hist_data, void *key, u64 *var_ref_vals, bool self);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811af310)
Location: kernel/trace/trace_events_hist.c:1944
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger
  - kernel/trace/trace_events_hist.c:event_hist_trigger
```
**Symbols:**

```
ffffffff811af310-ffffffff811af410: resolve_var_refs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool resolve_var_refs(struct hist_trigger_data *hist_data, void *key, u64 *var_ref_vals, bool self);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811ba300)
Location: kernel/trace/trace_events_hist.c:1944
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger
  - kernel/trace/trace_events_hist.c:event_hist_trigger
```
**Symbols:**

```
ffffffff811ba300-ffffffff811ba400: resolve_var_refs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool resolve_var_refs(struct hist_trigger_data *hist_data, void *key, u64 *var_ref_vals, bool self);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811c83a0)
Location: kernel/trace/trace_events_hist.c:1944
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger
  - kernel/trace/trace_events_hist.c:event_hist_trigger
```
**Symbols:**

```
ffffffff811c83a0-ffffffff811c84a0: resolve_var_refs (STB_LOCAL)
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
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
