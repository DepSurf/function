# Function: <code>uncore_perf_event_update</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void uncore_perf_event_update(struct intel_uncore_box *box, struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff810169a0)
Location: arch/x86/events/intel/uncore.c:227
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_read
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_event_stop
```
**Symbols:**

```
ffffffff810169a0-ffffffff81016a2c: uncore_perf_event_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void uncore_perf_event_update(struct intel_uncore_box *box, struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff81015c20)
Location: arch/x86/events/intel/uncore.c:210
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_read
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_event_stop
```
**Symbols:**

```
ffffffff81015c20-ffffffff81015cac: uncore_perf_event_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void uncore_perf_event_update(struct intel_uncore_box *box, struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff81015df0)
Location: arch/x86/events/intel/uncore.c:216
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_read
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_event_stop
```
**Symbols:**

```
ffffffff81015df0-ffffffff81015e7f: uncore_perf_event_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void uncore_perf_event_update(struct intel_uncore_box *box, struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff810142a0)
Location: arch/x86/events/intel/uncore.c:216
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_read
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_event_stop
```
**Symbols:**

```
ffffffff810142a0-ffffffff8101432f: uncore_perf_event_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void uncore_perf_event_update(struct intel_uncore_box *box, struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff81014ad0)
Location: arch/x86/events/intel/uncore.c:216
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_read
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_event_stop
```
**Symbols:**

```
ffffffff81014ad0-ffffffff81014b65: uncore_perf_event_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void uncore_perf_event_update(struct intel_uncore_box *box, struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff81015610)
Location: arch/x86/events/intel/uncore.c:216
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_read
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
```
**Symbols:**

```
ffffffff81015610-ffffffff810156dd: uncore_perf_event_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void uncore_perf_event_update(struct intel_uncore_box *box, struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff81015d20)
Location: arch/x86/events/intel/uncore.c:216
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_read
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
```
**Symbols:**

```
ffffffff81015d20-ffffffff81015df7: uncore_perf_event_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void uncore_perf_event_update(struct intel_uncore_box *box, struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff81017330)
Location: arch/x86/events/intel/uncore.c:233
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_read
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
```
**Symbols:**

```
ffffffff81017330-ffffffff81017402: uncore_perf_event_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void uncore_perf_event_update(struct intel_uncore_box *box, struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff81017ce0)
Location: arch/x86/events/intel/uncore.c:233
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_read
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
```
**Symbols:**

```
ffffffff81017ce0-ffffffff81017db2: uncore_perf_event_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void uncore_perf_event_update(struct intel_uncore_box *box, struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff81019890)
Location: arch/x86/events/intel/uncore.c:233
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_read
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
```
**Symbols:**

```
ffffffff81019890-ffffffff8101995a: uncore_perf_event_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void uncore_perf_event_update(struct intel_uncore_box *box, struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff81019f00)
Location: arch/x86/events/intel/uncore.c:238
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_read
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
```
**Symbols:**

```
ffffffff81019f00-ffffffff81019fca: uncore_perf_event_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void uncore_perf_event_update(struct intel_uncore_box *box, struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff8101b280)
Location: arch/x86/events/intel/uncore.c:255
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_read
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
```
**Symbols:**

```
ffffffff8101b280-ffffffff8101b34a: uncore_perf_event_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void uncore_perf_event_update(struct intel_uncore_box *box, struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/uncore.c (0)
Location: arch/x86/events/intel/uncore.c:255
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_read
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
```
**Symbols:**

```
ffffffff81c96889-ffffffff81c968c8: uncore_perf_event_update.cold (STB_LOCAL)
ffffffff8101dbc0-ffffffff8101dcba: uncore_perf_event_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void uncore_perf_event_update(struct intel_uncore_box *box, struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/uncore.c (0)
Location: arch/x86/events/intel/uncore.c:255
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_read
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
```
**Symbols:**

```
ffffffff81e45d12-ffffffff81e45d51: uncore_perf_event_update.cold (STB_LOCAL)
ffffffff81020640-ffffffff81020756: uncore_perf_event_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void uncore_perf_event_update(struct intel_uncore_box *box, struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/uncore.c (0)
Location: arch/x86/events/intel/uncore.c:255
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_read
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
```
**Symbols:**

```
ffffffff82051355-ffffffff82051394: uncore_perf_event_update.cold (STB_LOCAL)
ffffffff81024f80-ffffffff81025096: uncore_perf_event_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void uncore_perf_event_update(struct intel_uncore_box *box, struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/uncore.c (0)
Location: arch/x86/events/intel/uncore.c:270
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_read
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
```
**Symbols:**

```
ffffffff820cf787-ffffffff820cf7c6: uncore_perf_event_update.cold (STB_LOCAL)
ffffffff81024e80-ffffffff81024f89: uncore_perf_event_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void uncore_perf_event_update(struct intel_uncore_box *box, struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/uncore.c (0)
Location: arch/x86/events/intel/uncore.c:270
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_read
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
```
**Symbols:**

```
ffffffff821aa0f5-ffffffff821aa134: uncore_perf_event_update.cold (STB_LOCAL)
ffffffff8102afe0-ffffffff8102b0e9: uncore_perf_event_update (STB_GLOBAL)
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
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void uncore_perf_event_update(struct intel_uncore_box *box, struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff81017ce0)
Location: arch/x86/events/intel/uncore.c:233
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_read
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
```
**Symbols:**

```
ffffffff81017ce0-ffffffff81017db2: uncore_perf_event_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void uncore_perf_event_update(struct intel_uncore_box *box, struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff81017130)
Location: arch/x86/events/intel/uncore.c:233
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_read
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
```
**Symbols:**

```
ffffffff81017130-ffffffff81017202: uncore_perf_event_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void uncore_perf_event_update(struct intel_uncore_box *box, struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff81017ca0)
Location: arch/x86/events/intel/uncore.c:233
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_read
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
```
**Symbols:**

```
ffffffff81017ca0-ffffffff81017d72: uncore_perf_event_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void uncore_perf_event_update(struct intel_uncore_box *box, struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff81017ee0)
Location: arch/x86/events/intel/uncore.c:233
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_read
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
```
**Symbols:**

```
ffffffff81017ee0-ffffffff81017fb2: uncore_perf_event_update (STB_GLOBAL)
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
