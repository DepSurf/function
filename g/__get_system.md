# Function: <code>__get_system</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __get_system(struct event_subsystem *system);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff8115d860)
Location: kernel/trace/trace_events.c:634
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:subsystem_open
  - kernel/trace/trace_events.c:event_create_dir
```
**Symbols:**

```
ffffffff8115d860-ffffffff8115d89e: __get_system (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __get_system(struct event_subsystem *system);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff81168180)
Location: kernel/trace/trace_events.c:669
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:subsystem_open
```
**Symbols:**

```
ffffffff81168180-ffffffff811681be: __get_system (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __get_system(struct event_subsystem *system);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff811735c0)
Location: kernel/trace/trace_events.c:629
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:subsystem_open
```
**Symbols:**

```
ffffffff811735c0-ffffffff811735fe: __get_system (STB_LOCAL)
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
In kernel/trace/trace_events.c (ffffffff81178a3b)
Location: kernel/trace/trace_events.c:669
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:subsystem_open
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __get_system(struct event_subsystem *system);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff81183a80)
Location: kernel/trace/trace_events.c:669
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:subsystem_open
```
**Symbols:**

```
ffffffff81183a80-ffffffff81183a9c: __get_system (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __get_system(struct event_subsystem *system);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff81192ab0)
Location: kernel/trace/trace_events.c:669
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:subsystem_open
```
**Symbols:**

```
ffffffff81192ab0-ffffffff81192acc: __get_system (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __get_system(struct event_subsystem *system);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff811a0c20)
Location: kernel/trace/trace_events.c:670
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:subsystem_open
```
**Symbols:**

```
ffffffff811a0c20-ffffffff811a0c3c: __get_system (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __get_system(struct event_subsystem *system);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff811aebe0)
Location: kernel/trace/trace_events.c:662
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:subsystem_open
```
**Symbols:**

```
ffffffff811aebe0-ffffffff811aebf7: __get_system (STB_LOCAL)
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
In kernel/trace/trace_events.c (ffffffff811bc6d8)
Location: kernel/trace/trace_events.c:663
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:subsystem_open
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
In kernel/trace/trace_events.c (ffffffff811d451a)
Location: kernel/trace/trace_events.c:710
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_subsystem_dir
  - kernel/trace/trace_events.c:subsystem_open
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
In kernel/trace/trace_events.c (ffffffff811d169a)
Location: kernel/trace/trace_events.c:711
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_subsystem_dir
  - kernel/trace/trace_events.c:subsystem_open
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
In kernel/trace/trace_events.c (ffffffff811d27fe)
Location: kernel/trace/trace_events.c:918
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_subsystem_dir
  - kernel/trace/trace_events.c:subsystem_open
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
In kernel/trace/trace_events.c (ffffffff811ff55e)
Location: kernel/trace/trace_events.c:919
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_subsystem_dir
  - kernel/trace/trace_events.c:subsystem_open
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
In kernel/trace/trace_events.c (ffffffff8123af7b)
Location: kernel/trace/trace_events.c:939
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_subsystem_dir
  - kernel/trace/trace_events.c:subsystem_open
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
In kernel/trace/trace_events.c (ffffffff81287c5c)
Location: kernel/trace/trace_events.c:954
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_subsystem_dir
  - kernel/trace/trace_events.c:subsystem_open
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
In kernel/trace/trace_events.c (ffffffff812a4984)
Location: kernel/trace/trace_events.c:950
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_subsystem_dir
  - kernel/trace/trace_events.c:subsystem_open
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
In kernel/trace/trace_events.c (ffffffff812c03d3)
Location: kernel/trace/trace_events.c:950
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_subsystem_dir
  - kernel/trace/trace_events.c:subsystem_open
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffff80001023a6cc)
Location: kernel/trace/trace_events.c:663
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:subsystem_open
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __get_system(struct event_subsystem *system);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (c0474828)
Location: kernel/trace/trace_events.c:663
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:subsystem_open
```
**Symbols:**

```
c0474828-c0474888: __get_system (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (c0000000002ca37c)
Location: kernel/trace/trace_events.c:663
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:subsystem_open
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffffffe000191b36)
Location: kernel/trace/trace_events.c:663
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:subsystem_open
```
</details>
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
In kernel/trace/trace_events.c (ffffffff811b4cf8)
Location: kernel/trace/trace_events.c:663
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:subsystem_open
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
In kernel/trace/trace_events.c (ffffffff811a7af8)
Location: kernel/trace/trace_events.c:663
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:subsystem_open
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
In kernel/trace/trace_events.c (ffffffff811b2ac8)
Location: kernel/trace/trace_events.c:663
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:subsystem_open
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
In kernel/trace/trace_events.c (ffffffff811c0b68)
Location: kernel/trace/trace_events.c:663
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:subsystem_open
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
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
