# Function: <code>tp_rcu_cond_sync</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/tracepoint.c (ffffffff811a9967)
Location: kernel/tracepoint.c:57
Inline: True
Inline callers:
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_add_func
  - kernel/tracepoint.c:tracepoint_add_func
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tp_rcu_cond_sync(enum tp_transition_sync sync);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/tracepoint.c (ffffffff811d3015)
Location: kernel/tracepoint.c:57
Inline: True
Direct callers:
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_add_func
```
**Symbols:**

```
ffffffff811d2fe0-ffffffff811d3072: tp_rcu_cond_sync (STB_LOCAL)
ffffffff81cb400b-ffffffff81cb4020: tp_rcu_cond_sync.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tp_rcu_cond_sync(enum tp_transition_sync sync);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/tracepoint.c (ffffffff81207a43)
Location: kernel/tracepoint.c:57
Inline: True
Direct callers:
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_add_func
```
**Symbols:**

```
ffffffff81207a00-ffffffff81207aad: tp_rcu_cond_sync (STB_LOCAL)
ffffffff81e64f55-ffffffff81e64f6a: tp_rcu_cond_sync.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tp_rcu_cond_sync(enum tp_transition_sync sync);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/tracepoint.c (ffffffff8124fe83)
Location: kernel/tracepoint.c:57
Inline: True
Direct callers:
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_add_func
```
**Symbols:**

```
ffffffff8124fe40-ffffffff8124feed: tp_rcu_cond_sync (STB_LOCAL)
ffffffff8205ca48-ffffffff8205ca5d: tp_rcu_cond_sync.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tp_rcu_cond_sync(enum tp_transition_sync sync);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/tracepoint.c (ffffffff81267233)
Location: kernel/tracepoint.c:57
Inline: True
Direct callers:
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_add_func
```
**Symbols:**

```
ffffffff812671f0-ffffffff8126729d: tp_rcu_cond_sync (STB_LOCAL)
ffffffff820db3e9-ffffffff820db3fe: tp_rcu_cond_sync.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tp_rcu_cond_sync(enum tp_transition_sync sync);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/tracepoint.c (ffffffff812811c3)
Location: kernel/tracepoint.c:57
Inline: True
Direct callers:
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_add_func
```
**Symbols:**

```
ffffffff81281180-ffffffff8128122d: tp_rcu_cond_sync (STB_LOCAL)
ffffffff821b710a-ffffffff821b711f: tp_rcu_cond_sync.cold (STB_LOCAL)
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
