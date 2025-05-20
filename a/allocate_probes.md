# Function: <code>allocate_probes</code>

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
In kernel/tracepoint.c (ffffffff8113f7b6)
Location: kernel/tracepoint.c:62
Inline: True
Inline callers:
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_probe_register_prio
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
In kernel/tracepoint.c (ffffffff81147e2a)
Location: kernel/tracepoint.c:62
Inline: True
Inline callers:
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_probe_register_prio
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
In kernel/tracepoint.c (ffffffff81151cca)
Location: kernel/tracepoint.c:62
Inline: True
Inline callers:
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_probe_register_prio
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
In kernel/tracepoint.c (ffffffff81154393)
Location: kernel/tracepoint.c:63
Inline: True
Inline callers:
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_probe_register_prio
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
In kernel/tracepoint.c (ffffffff81160bac)
Location: kernel/tracepoint.c:63
Inline: True
Inline callers:
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_probe_register_prio
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
In kernel/tracepoint.c (ffffffff8116fd3d)
Location: kernel/tracepoint.c:63
Inline: True
Inline callers:
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_probe_register_prio
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
In kernel/tracepoint.c (ffffffff8117d5cd)
Location: kernel/tracepoint.c:69
Inline: True
Inline callers:
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_probe_register_prio
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *allocate_probes(int count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/tracepoint.c (ffffffff8118a380)
Location: kernel/tracepoint.c:56
Inline: False
Direct callers:
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_probe_register_prio
  - kernel/tracepoint.c:tracepoint_probe_register_prio
  - kernel/tracepoint.c:tracepoint_probe_register_prio
```
**Symbols:**

```
ffffffff8118a380-ffffffff8118a3bf: allocate_probes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *allocate_probes(int count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/tracepoint.c (ffffffff81196290)
Location: kernel/tracepoint.c:56
Inline: False
Direct callers:
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_probe_register_prio
  - kernel/tracepoint.c:tracepoint_probe_register_prio
  - kernel/tracepoint.c:tracepoint_probe_register_prio
```
**Symbols:**

```
ffffffff81196290-ffffffff811962cf: allocate_probes (STB_LOCAL)
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
In kernel/tracepoint.c (ffffffff811ab2e4)
Location: kernel/tracepoint.c:56
Inline: True
Inline callers:
  - kernel/tracepoint.c:tracepoint_remove_func
  - kernel/tracepoint.c:func_add
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
In kernel/tracepoint.c (ffffffff811a90b2)
Location: kernel/tracepoint.c:62
Inline: True
Inline callers:
  - kernel/tracepoint.c:func_remove
  - kernel/tracepoint.c:func_add
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
In kernel/tracepoint.c (ffffffff811a9714)
Location: kernel/tracepoint.c:107
Inline: True
Inline callers:
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_add_func
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
In kernel/tracepoint.c (ffffffff811d3304)
Location: kernel/tracepoint.c:107
Inline: True
Inline callers:
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_add_func
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
In kernel/tracepoint.c (ffffffff81207d7d)
Location: kernel/tracepoint.c:107
Inline: True
Inline callers:
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_add_func
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
In kernel/tracepoint.c (ffffffff812507ed)
Location: kernel/tracepoint.c:107
Inline: True
Inline callers:
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_add_func
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
In kernel/tracepoint.c (ffffffff81267b8c)
Location: kernel/tracepoint.c:107
Inline: True
Inline callers:
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_add_func
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
In kernel/tracepoint.c (ffffffff8128153c)
Location: kernel/tracepoint.c:107
Inline: True
Inline callers:
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_add_func
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
In kernel/tracepoint.c (ffff80001020e6dc)
Location: kernel/tracepoint.c:56
Inline: True
Inline callers:
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_probe_register_prio
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
In kernel/tracepoint.c (c044d228)
Location: kernel/tracepoint.c:56
Inline: True
Inline callers:
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_probe_register_prio
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *allocate_probes(int count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/tracepoint.c (c00000000028c940)
Location: kernel/tracepoint.c:56
Inline: False
Direct callers:
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_probe_register_prio
  - kernel/tracepoint.c:tracepoint_probe_register_prio
  - kernel/tracepoint.c:tracepoint_probe_register_prio
```
**Symbols:**

```
c00000000028c940-c00000000028c9bc: allocate_probes (STB_LOCAL)
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
In kernel/tracepoint.c (ffffffe00016f454)
Location: kernel/tracepoint.c:56
Inline: True
Inline callers:
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_probe_register_prio
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void *allocate_probes(int count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/tracepoint.c (ffffffff8118e8b0)
Location: kernel/tracepoint.c:56
Inline: False
Direct callers:
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_probe_register_prio
  - kernel/tracepoint.c:tracepoint_probe_register_prio
  - kernel/tracepoint.c:tracepoint_probe_register_prio
```
**Symbols:**

```
ffffffff8118e8b0-ffffffff8118e8ef: allocate_probes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *allocate_probes(int count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/tracepoint.c (ffffffff81181a30)
Location: kernel/tracepoint.c:56
Inline: False
Direct callers:
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_probe_register_prio
  - kernel/tracepoint.c:tracepoint_probe_register_prio
  - kernel/tracepoint.c:tracepoint_probe_register_prio
```
**Symbols:**

```
ffffffff81181a30-ffffffff81181a6f: allocate_probes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *allocate_probes(int count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/tracepoint.c (ffffffff8118c680)
Location: kernel/tracepoint.c:56
Inline: False
Direct callers:
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_probe_register_prio
  - kernel/tracepoint.c:tracepoint_probe_register_prio
  - kernel/tracepoint.c:tracepoint_probe_register_prio
```
**Symbols:**

```
ffffffff8118c680-ffffffff8118c6bf: allocate_probes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *allocate_probes(int count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/tracepoint.c (ffffffff8119a010)
Location: kernel/tracepoint.c:56
Inline: False
Direct callers:
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_probe_register_prio
  - kernel/tracepoint.c:tracepoint_probe_register_prio
  - kernel/tracepoint.c:tracepoint_probe_register_prio
```
**Symbols:**

```
ffffffff8119a010-ffffffff8119a04f: allocate_probes (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
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
