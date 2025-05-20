# Function: <code>create_new_subsystem</code>

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
In kernel/trace/trace_events.c (ffffffff81160587)
Location: kernel/trace/trace_events.c:1948
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_create_dir
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
In kernel/trace/trace_events.c (ffffffff8116aa17)
Location: kernel/trace/trace_events.c:1844
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_create_dir
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
In kernel/trace/trace_events.c (ffffffff81175dc7)
Location: kernel/trace/trace_events.c:1813
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_create_dir
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
In kernel/trace/trace_events.c (ffffffff81178b49)
Location: kernel/trace/trace_events.c:1853
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_create_dir
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
In kernel/trace/trace_events.c (ffffffff811862cf)
Location: kernel/trace/trace_events.c:1853
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_create_dir
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
In kernel/trace/trace_events.c (ffffffff8119537e)
Location: kernel/trace/trace_events.c:1851
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_create_dir
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
In kernel/trace/trace_events.c (ffffffff811a341e)
Location: kernel/trace/trace_events.c:1852
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_create_dir
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
In kernel/trace/trace_events.c (ffffffff811b1330)
Location: kernel/trace/trace_events.c:1842
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_create_dir
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
In kernel/trace/trace_events.c (ffffffff811bc7e0)
Location: kernel/trace/trace_events.c:1841
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_create_dir
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct event_subsystem *create_new_subsystem(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff811d4340)
Location: kernel/trace/trace_events.c:2019
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:event_subsystem_dir
```
**Symbols:**

```
ffffffff811d4340-ffffffff811d43f9: create_new_subsystem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct event_subsystem *create_new_subsystem(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff811d14c0)
Location: kernel/trace/trace_events.c:2021
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:event_subsystem_dir
```
**Symbols:**

```
ffffffff811d14c0-ffffffff811d1579: create_new_subsystem (STB_LOCAL)
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
In kernel/trace/trace_events.c (ffffffff811d270a)
Location: kernel/trace/trace_events.c:2228
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_subsystem_dir
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
In kernel/trace/trace_events.c (ffffffff811ff46a)
Location: kernel/trace/trace_events.c:2229
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_subsystem_dir
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
In kernel/trace/trace_events.c (ffffffff8123b03d)
Location: kernel/trace/trace_events.c:2248
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_subsystem_dir
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
In kernel/trace/trace_events.c (ffffffff81287b88)
Location: kernel/trace/trace_events.c:2268
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_subsystem_dir
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
In kernel/trace/trace_events.c (ffffffff812a48b8)
Location: kernel/trace/trace_events.c:2264
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_subsystem_dir
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
In kernel/trace/trace_events.c (ffffffff812c0277)
Location: kernel/trace/trace_events.c:2309
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_subsystem_dir
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
In kernel/trace/trace_events.c (ffff80001023a77c)
Location: kernel/trace/trace_events.c:1841
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_create_dir
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (c04775b4)
Location: kernel/trace/trace_events.c:1841
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_create_dir
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
In kernel/trace/trace_events.c (c0000000002ca468)
Location: kernel/trace/trace_events.c:1841
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_create_dir
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
In kernel/trace/trace_events.c (ffffffe000191bf8)
Location: kernel/trace/trace_events.c:1841
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_create_dir
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
In kernel/trace/trace_events.c (ffffffff811b4e00)
Location: kernel/trace/trace_events.c:1841
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_create_dir
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
In kernel/trace/trace_events.c (ffffffff811a7c00)
Location: kernel/trace/trace_events.c:1841
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_create_dir
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
In kernel/trace/trace_events.c (ffffffff811b2bd0)
Location: kernel/trace/trace_events.c:1841
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_create_dir
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
In kernel/trace/trace_events.c (ffffffff811c0c70)
Location: kernel/trace/trace_events.c:1841
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_create_dir
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
</ul>
