# Function: <code>release_probe</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void release_probe(struct ftrace_func_probe *probe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81154e10)
Location: kernel/trace/ftrace.c:4297
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:register_ftrace_function_probe
```
**Symbols:**

```
ffffffff81154e10-ffffffff81154ea7: release_probe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void release_probe(struct ftrace_func_probe *probe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81161640)
Location: kernel/trace/ftrace.c:4265
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:register_ftrace_function_probe
```
**Symbols:**

```
ffffffff81161640-ffffffff811616da: release_probe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void release_probe(struct ftrace_func_probe *probe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81170560)
Location: kernel/trace/ftrace.c:4253
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:register_ftrace_function_probe
```
**Symbols:**

```
ffffffff81170560-ffffffff81170601: release_probe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void release_probe(struct ftrace_func_probe *probe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8117df50)
Location: kernel/trace/ftrace.c:4212
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:register_ftrace_function_probe
```
**Symbols:**

```
ffffffff8117df50-ffffffff8117dff1: release_probe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void release_probe(struct ftrace_func_probe *probe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (0)
Location: kernel/trace/ftrace.c:4251
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:register_ftrace_function_probe
```
**Symbols:**

```
ffffffff8118b0d0-ffffffff8118b173: release_probe (STB_LOCAL)
ffffffff81191f42-ffffffff81191f5d: release_probe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void release_probe(struct ftrace_func_probe *probe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81196ee0)
Location: kernel/trace/ftrace.c:4275
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:register_ftrace_function_probe
```
**Symbols:**

```
ffffffff81196ee0-ffffffff81196f9c: release_probe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void release_probe(struct ftrace_func_probe *probe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811ac240)
Location: kernel/trace/ftrace.c:4402
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:register_ftrace_function_probe
```
**Symbols:**

```
ffffffff811ac240-ffffffff811ac2f4: release_probe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void release_probe(struct ftrace_func_probe *probe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811a9ad0)
Location: kernel/trace/ftrace.c:4479
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:register_ftrace_function_probe
```
**Symbols:**

```
ffffffff811a9ad0-ffffffff811a9b84: release_probe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void release_probe(struct ftrace_func_probe *probe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811aa690)
Location: kernel/trace/ftrace.c:4479
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:register_ftrace_function_probe
```
**Symbols:**

```
ffffffff811aa690-ffffffff811aa744: release_probe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void release_probe(struct ftrace_func_probe *probe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811d4310)
Location: kernel/trace/ftrace.c:4479
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:register_ftrace_function_probe
```
**Symbols:**

```
ffffffff811d4310-ffffffff811d43c4: release_probe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void release_probe(struct ftrace_func_probe *probe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81208fa0)
Location: kernel/trace/ftrace.c:4619
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:register_ftrace_function_probe
```
**Symbols:**

```
ffffffff81208fa0-ffffffff81209054: release_probe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void release_probe(struct ftrace_func_probe *probe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff812515c0)
Location: kernel/trace/ftrace.c:4640
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:register_ftrace_function_probe
```
**Symbols:**

```
ffffffff812515c0-ffffffff81251674: release_probe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void release_probe(struct ftrace_func_probe *probe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81268a60)
Location: kernel/trace/ftrace.c:4795
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:register_ftrace_function_probe
```
**Symbols:**

```
ffffffff81268a60-ffffffff81268b14: release_probe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void release_probe(struct ftrace_func_probe *probe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81282cd0)
Location: kernel/trace/ftrace.c:4761
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:register_ftrace_function_probe
```
**Symbols:**

```
ffffffff81282cd0-ffffffff81282d84: release_probe (STB_LOCAL)
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
void release_probe(struct ftrace_func_probe *probe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffff80001020f350)
Location: kernel/trace/ftrace.c:4275
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:register_ftrace_function_probe
```
**Symbols:**

```
ffff80001020f350-ffff80001020f3ec: release_probe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void release_probe(struct ftrace_func_probe *probe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (c044e7ac)
Location: kernel/trace/ftrace.c:4275
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:register_ftrace_function_probe
```
**Symbols:**

```
c044e7ac-c044e854: release_probe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void release_probe(struct ftrace_func_probe *probe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (c00000000028e030)
Location: kernel/trace/ftrace.c:4275
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:register_ftrace_function_probe
```
**Symbols:**

```
c00000000028e030-c00000000028e124: release_probe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void release_probe(struct ftrace_func_probe *probe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffe000170090)
Location: kernel/trace/ftrace.c:4275
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:register_ftrace_function_probe
```
**Symbols:**

```
ffffffe000170090-ffffffe000170126: release_probe (STB_LOCAL)
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
void release_probe(struct ftrace_func_probe *probe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8118f500)
Location: kernel/trace/ftrace.c:4275
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:register_ftrace_function_probe
```
**Symbols:**

```
ffffffff8118f500-ffffffff8118f5bc: release_probe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void release_probe(struct ftrace_func_probe *probe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81182640)
Location: kernel/trace/ftrace.c:4275
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:register_ftrace_function_probe
```
**Symbols:**

```
ffffffff81182640-ffffffff811826fc: release_probe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void release_probe(struct ftrace_func_probe *probe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8118d2d0)
Location: kernel/trace/ftrace.c:4275
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:register_ftrace_function_probe
```
**Symbols:**

```
ffffffff8118d2d0-ffffffff8118d38c: release_probe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void release_probe(struct ftrace_func_probe *probe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8119ae50)
Location: kernel/trace/ftrace.c:4275
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:register_ftrace_function_probe
```
**Symbols:**

```
ffffffff8119ae50-ffffffff8119af0c: release_probe (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
