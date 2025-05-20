# Function: <code>uncore_change_context</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void uncore_change_context(struct intel_uncore_type **uncores, int old_cpu, int new_cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff81015670)
Location: arch/x86/events/intel/uncore.c:1134
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_cpu_notifier
  - arch/x86/events/intel/uncore.c:uncore_cpu_notifier
```
**Symbols:**

```
ffffffff81015670-ffffffff81015836: uncore_change_context (STB_LOCAL)
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
In arch/x86/events/intel/uncore.c (ffffffff8101539e)
Location: arch/x86/events/intel/uncore.c:1167
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
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
In arch/x86/events/intel/uncore.c (ffffffff81015923)
Location: arch/x86/events/intel/uncore.c:1073
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
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
In arch/x86/events/intel/uncore.c (ffffffff81013e09)
Location: arch/x86/events/intel/uncore.c:1073
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
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
In arch/x86/events/intel/uncore.c (ffffffff81014754)
Location: arch/x86/events/intel/uncore.c:1081
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
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
In arch/x86/events/intel/uncore.c (ffffffff81015216)
Location: arch/x86/events/intel/uncore.c:1142
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff81015816)
Location: arch/x86/events/intel/uncore.c:1143
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff81016ace)
Location: arch/x86/events/intel/uncore.c:1155
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff8101747e)
Location: arch/x86/events/intel/uncore.c:1187
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void uncore_change_context(struct intel_uncore_type **uncores, int old_cpu, int new_cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff81017d80)
Location: arch/x86/events/intel/uncore.c:1187
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
```
**Symbols:**

```
ffffffff81017d80-ffffffff81017ea7: uncore_change_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void uncore_change_context(struct intel_uncore_type **uncores, int old_cpu, int new_cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff81018290)
Location: arch/x86/events/intel/uncore.c:1347
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
```
**Symbols:**

```
ffffffff81018290-ffffffff810183ba: uncore_change_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void uncore_change_context(struct intel_uncore_type **uncores, int old_cpu, int new_cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff810194f0)
Location: arch/x86/events/intel/uncore.c:1458
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
```
**Symbols:**

```
ffffffff810194f0-ffffffff8101961a: uncore_change_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void uncore_change_context(struct intel_uncore_type **uncores, int old_cpu, int new_cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff8101bf20)
Location: arch/x86/events/intel/uncore.c:1465
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
```
**Symbols:**

```
ffffffff8101bf20-ffffffff8101c06d: uncore_change_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void uncore_change_context(struct intel_uncore_type **uncores, int old_cpu, int new_cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff8101e6b0)
Location: arch/x86/events/intel/uncore.c:1465
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
```
**Symbols:**

```
ffffffff8101e6b0-ffffffff8101e80e: uncore_change_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void uncore_change_context(struct intel_uncore_type **uncores, int old_cpu, int new_cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff81022c50)
Location: arch/x86/events/intel/uncore.c:1465
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
```
**Symbols:**

```
ffffffff81022c50-ffffffff81022dae: uncore_change_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void uncore_change_context(struct intel_uncore_type **uncores, int old_cpu, int new_cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff81022930)
Location: arch/x86/events/intel/uncore.c:1486
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
```
**Symbols:**

```
ffffffff81022930-ffffffff81022a8f: uncore_change_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void uncore_change_context(struct intel_uncore_type **uncores, int old_cpu, int new_cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff81028a60)
Location: arch/x86/events/intel/uncore.c:1486
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
```
**Symbols:**

```
ffffffff81028a60-ffffffff81028bbe: uncore_change_context (STB_LOCAL)
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff8101747e)
Location: arch/x86/events/intel/uncore.c:1187
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff810168ae)
Location: arch/x86/events/intel/uncore.c:1187
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff8101743e)
Location: arch/x86/events/intel/uncore.c:1187
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff8101767e)
Location: arch/x86/events/intel/uncore.c:1187
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
