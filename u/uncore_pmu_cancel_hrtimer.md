# Function: <code>uncore_pmu_cancel_hrtimer</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void uncore_pmu_cancel_hrtimer(struct intel_uncore_box *box);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff810156bc)
Location: arch/x86/events/intel/uncore.c:294
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_change_context
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
Direct callers:
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_event_stop
```
**Symbols:**

```
ffffffff810170f0-ffffffff81017107: uncore_pmu_cancel_hrtimer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void uncore_pmu_cancel_hrtimer(struct intel_uncore_box *box);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff81015e8e)
Location: arch/x86/events/intel/uncore.c:277
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
Direct callers:
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_event_stop
```
**Symbols:**

```
ffffffff81016370-ffffffff81016387: uncore_pmu_cancel_hrtimer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void uncore_pmu_cancel_hrtimer(struct intel_uncore_box *box);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff81016067)
Location: arch/x86/events/intel/uncore.c:283
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
Direct callers:
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_event_stop
```
**Symbols:**

```
ffffffff81016580-ffffffff81016597: uncore_pmu_cancel_hrtimer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void uncore_pmu_cancel_hrtimer(struct intel_uncore_box *box);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff810144e4)
Location: arch/x86/events/intel/uncore.c:283
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
Direct callers:
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_event_stop
```
**Symbols:**

```
ffffffff810149b0-ffffffff810149c7: uncore_pmu_cancel_hrtimer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void uncore_pmu_cancel_hrtimer(struct intel_uncore_box *box);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff81014d4d)
Location: arch/x86/events/intel/uncore.c:283
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
Direct callers:
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_event_stop
```
**Symbols:**

```
ffffffff81015210-ffffffff81015227: uncore_pmu_cancel_hrtimer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void uncore_pmu_cancel_hrtimer(struct intel_uncore_box *box);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff810158ca)
Location: arch/x86/events/intel/uncore.c:285
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
```
**Symbols:**

```
ffffffff81015e00-ffffffff81015e17: uncore_pmu_cancel_hrtimer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void uncore_pmu_cancel_hrtimer(struct intel_uncore_box *box);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff81015fea)
Location: arch/x86/events/intel/uncore.c:285
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
```
**Symbols:**

```
ffffffff81016580-ffffffff81016597: uncore_pmu_cancel_hrtimer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void uncore_pmu_cancel_hrtimer(struct intel_uncore_box *box);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff810175fb)
Location: arch/x86/events/intel/uncore.c:302
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
```
**Symbols:**

```
ffffffff81017ba0-ffffffff81017bb7: uncore_pmu_cancel_hrtimer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void uncore_pmu_cancel_hrtimer(struct intel_uncore_box *box);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff81017fd6)
Location: arch/x86/events/intel/uncore.c:302
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
```
**Symbols:**

```
ffffffff81018530-ffffffff81018547: uncore_pmu_cancel_hrtimer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void uncore_pmu_cancel_hrtimer(struct intel_uncore_box *box);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff81017e18)
Location: arch/x86/events/intel/uncore.c:302
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_change_context
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
```
**Symbols:**

```
ffffffff81019e80-ffffffff81019e97: uncore_pmu_cancel_hrtimer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void uncore_pmu_cancel_hrtimer(struct intel_uncore_box *box);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff8101832b)
Location: arch/x86/events/intel/uncore.c:307
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_change_context
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
```
**Symbols:**

```
ffffffff8101a4f0-ffffffff8101a507: uncore_pmu_cancel_hrtimer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void uncore_pmu_cancel_hrtimer(struct intel_uncore_box *box);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff8101958b)
Location: arch/x86/events/intel/uncore.c:324
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_change_context
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
```
**Symbols:**

```
ffffffff8101b890-ffffffff8101b8a7: uncore_pmu_cancel_hrtimer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void uncore_pmu_cancel_hrtimer(struct intel_uncore_box *box);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff8101bfc9)
Location: arch/x86/events/intel/uncore.c:324
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_change_context
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
```
**Symbols:**

```
ffffffff8101e470-ffffffff8101e487: uncore_pmu_cancel_hrtimer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void uncore_pmu_cancel_hrtimer(struct intel_uncore_box *box);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff8101e759)
Location: arch/x86/events/intel/uncore.c:324
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_change_context
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
```
**Symbols:**

```
ffffffff81020fa0-ffffffff81020fbf: uncore_pmu_cancel_hrtimer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void uncore_pmu_cancel_hrtimer(struct intel_uncore_box *box);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff81022cf9)
Location: arch/x86/events/intel/uncore.c:324
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_change_context
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
```
**Symbols:**

```
ffffffff81025950-ffffffff8102596f: uncore_pmu_cancel_hrtimer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void uncore_pmu_cancel_hrtimer(struct intel_uncore_box *box);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff810229dc)
Location: arch/x86/events/intel/uncore.c:339
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_change_context
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
```
**Symbols:**

```
ffffffff81025840-ffffffff8102585f: uncore_pmu_cancel_hrtimer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void uncore_pmu_cancel_hrtimer(struct intel_uncore_box *box);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff81028b0b)
Location: arch/x86/events/intel/uncore.c:339
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_change_context
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
```
**Symbols:**

```
ffffffff8102b9a0-ffffffff8102b9bf: uncore_pmu_cancel_hrtimer (STB_GLOBAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void uncore_pmu_cancel_hrtimer(struct intel_uncore_box *box);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff81017fd6)
Location: arch/x86/events/intel/uncore.c:302
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
```
**Symbols:**

```
ffffffff81018530-ffffffff81018547: uncore_pmu_cancel_hrtimer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void uncore_pmu_cancel_hrtimer(struct intel_uncore_box *box);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff81017406)
Location: arch/x86/events/intel/uncore.c:302
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
```
**Symbols:**

```
ffffffff81017960-ffffffff81017977: uncore_pmu_cancel_hrtimer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void uncore_pmu_cancel_hrtimer(struct intel_uncore_box *box);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff81017f96)
Location: arch/x86/events/intel/uncore.c:302
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
```
**Symbols:**

```
ffffffff810184f0-ffffffff81018507: uncore_pmu_cancel_hrtimer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void uncore_pmu_cancel_hrtimer(struct intel_uncore_box *box);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff810181d6)
Location: arch/x86/events/intel/uncore.c:302
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
```
**Symbols:**

```
ffffffff81018730-ffffffff81018747: uncore_pmu_cancel_hrtimer (STB_GLOBAL)
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
