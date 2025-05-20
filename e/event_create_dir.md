# Function: <code>event_create_dir</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int event_create_dir(struct dentry *parent, struct trace_event_file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff81160200)
Location: kernel/trace/trace_events.c:2056
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:__trace_add_new_event
  - kernel/trace/trace_events.c:event_trace_init
```
**Symbols:**

```
ffffffff81160200-ffffffff811606b1: event_create_dir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int event_create_dir(struct dentry *parent, struct trace_event_file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff8116a650)
Location: kernel/trace/trace_events.c:1952
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:event_trace_init
  - kernel/trace/trace_events.c:__trace_add_new_event
```
**Symbols:**

```
ffffffff8116a650-ffffffff8116ab41: event_create_dir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int event_create_dir(struct dentry *parent, struct trace_event_file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff81175a00)
Location: kernel/trace/trace_events.c:1921
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:event_trace_init
  - kernel/trace/trace_events.c:__trace_add_new_event
```
**Symbols:**

```
ffffffff81175a00-ffffffff81175ef1: event_create_dir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int event_create_dir(struct dentry *parent, struct trace_event_file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff811787c0)
Location: kernel/trace/trace_events.c:1961
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:event_trace_init
  - kernel/trace/trace_events.c:__trace_add_new_event
```
**Symbols:**

```
ffffffff811787c0-ffffffff81178c91: event_create_dir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int event_create_dir(struct dentry *parent, struct trace_event_file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff81185f40)
Location: kernel/trace/trace_events.c:1961
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:event_trace_init
  - kernel/trace/trace_events.c:__trace_add_new_event
```
**Symbols:**

```
ffffffff81185f40-ffffffff81186413: event_create_dir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int event_create_dir(struct dentry *parent, struct trace_event_file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events.c (0)
Location: kernel/trace/trace_events.c:1959
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:event_trace_init
  - kernel/trace/trace_events.c:__trace_add_new_event
```
**Symbols:**

```
ffffffff81194fd0-ffffffff8119548c: event_create_dir (STB_LOCAL)
ffffffff81196523-ffffffff811965a9: event_create_dir.cold.29 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int event_create_dir(struct dentry *parent, struct trace_event_file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events.c (0)
Location: kernel/trace/trace_events.c:1960
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:event_trace_init
  - kernel/trace/trace_events.c:__trace_add_new_event
```
**Symbols:**

```
ffffffff811a3070-ffffffff811a352c: event_create_dir (STB_LOCAL)
ffffffff811a4664-ffffffff811a46ea: event_create_dir.cold.28 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int event_create_dir(struct dentry *parent, struct trace_event_file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events.c (0)
Location: kernel/trace/trace_events.c:1950
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:event_trace_init
  - kernel/trace/trace_events.c:__trace_add_new_event
```
**Symbols:**

```
ffffffff811b0f80-ffffffff811b1437: event_create_dir (STB_LOCAL)
ffffffff811b259a-ffffffff811b2639: event_create_dir.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int event_create_dir(struct dentry *parent, struct trace_event_file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events.c (0)
Location: kernel/trace/trace_events.c:1949
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:event_trace_init
  - kernel/trace/trace_events.c:__trace_add_new_event
```
**Symbols:**

```
ffffffff811bc430-ffffffff811bc8f2: event_create_dir (STB_LOCAL)
ffffffff811bdba5-ffffffff811bdc44: event_create_dir.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int event_create_dir(struct dentry *parent, struct trace_event_file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events.c (0)
Location: kernel/trace/trace_events.c:2127
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:event_trace_init
  - kernel/trace/trace_events.c:event_trace_add_tracer
  - kernel/trace/trace_events.c:trace_module_notify
  - kernel/trace/trace_events.c:trace_add_event_call
```
**Symbols:**

```
ffffffff811d5650-ffffffff811d58d3: event_create_dir (STB_LOCAL)
ffffffff811d73c0-ffffffff811d73f0: event_create_dir.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int event_create_dir(struct dentry *parent, struct trace_event_file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events.c (0)
Location: kernel/trace/trace_events.c:2166
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:event_trace_add_tracer
  - kernel/trace/trace_events.c:__trace_early_add_event_dirs
  - kernel/trace/trace_events.c:trace_module_notify
  - kernel/trace/trace_events.c:trace_add_event_call
```
**Symbols:**

```
ffffffff811d2870-ffffffff811d2a90: event_create_dir (STB_LOCAL)
ffffffff81be6142-ffffffff81be616e: event_create_dir.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int event_create_dir(struct dentry *parent, struct trace_event_file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events.c (0)
Location: kernel/trace/trace_events.c:2377
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:event_trace_add_tracer
  - kernel/trace/trace_events.c:__trace_early_add_event_dirs
  - kernel/trace/trace_events.c:trace_module_notify
  - kernel/trace/trace_events.c:trace_add_event_call
```
**Symbols:**

```
ffffffff811d4450-ffffffff811d4644: event_create_dir (STB_LOCAL)
ffffffff81bd7df8-ffffffff81bd7e24: event_create_dir.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int event_create_dir(struct dentry *parent, struct trace_event_file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events.c (0)
Location: kernel/trace/trace_events.c:2379
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:__trace_early_add_event_dirs
  - kernel/trace/trace_events.c:__trace_add_new_event
```
**Symbols:**

```
ffffffff812012b0-ffffffff812014a4: event_create_dir (STB_LOCAL)
ffffffff81cb6435-ffffffff81cb6461: event_create_dir.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int event_create_dir(struct dentry *parent, struct trace_event_file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events.c (0)
Location: kernel/trace/trace_events.c:2398
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:__trace_early_add_event_dirs
  - kernel/trace/trace_events.c:__trace_add_new_event
```
**Symbols:**

```
ffffffff8123c3b0-ffffffff8123c5c2: event_create_dir (STB_LOCAL)
ffffffff81e673ad-ffffffff81e673d9: event_create_dir.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int event_create_dir(struct dentry *parent, struct trace_event_file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff81288ce0)
Location: kernel/trace/trace_events.c:2419
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:__trace_early_add_event_dirs
  - kernel/trace/trace_events.c:__trace_add_new_event
```
**Symbols:**

```
ffffffff81288ce0-ffffffff81288f38: event_create_dir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int event_create_dir(struct dentry *parent, struct trace_event_file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff812a5a00)
Location: kernel/trace/trace_events.c:2413
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:__trace_early_add_event_dirs
  - kernel/trace/trace_events.c:__trace_add_new_event
```
**Symbols:**

```
ffffffff812a5a00-ffffffff812a5c58: event_create_dir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int event_create_dir(struct eventfs_inode *parent, struct trace_event_file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff812c1420)
Location: kernel/trace/trace_events.c:2552
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:__trace_early_add_event_dirs
  - kernel/trace/trace_events.c:__trace_add_new_event
```
**Symbols:**

```
ffffffff812c1420-ffffffff812c1559: event_create_dir (STB_LOCAL)
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
int event_create_dir(struct dentry *parent, struct trace_event_file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffff80001023a430)
Location: kernel/trace/trace_events.c:1949
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:event_trace_init
  - kernel/trace/trace_events.c:__trace_add_new_event
```
**Symbols:**

```
ffff80001023a430-ffff80001023a898: event_create_dir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int event_create_dir(struct dentry *parent, struct trace_event_file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (c0477238)
Location: kernel/trace/trace_events.c:1949
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:event_trace_init
  - kernel/trace/trace_events.c:__trace_add_new_event
```
**Symbols:**

```
c0477238-c0477740: event_create_dir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int event_create_dir(struct dentry *parent, struct trace_event_file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (c0000000002c9bf0)
Location: kernel/trace/trace_events.c:1949
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:event_trace_init
  - kernel/trace/trace_events.c:__trace_add_new_event
```
**Symbols:**

```
c0000000002c9bf0-c0000000002ca5f8: event_create_dir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int event_create_dir(struct dentry *parent, struct trace_event_file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffffffe000191908)
Location: kernel/trace/trace_events.c:1949
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:event_trace_init
  - kernel/trace/trace_events.c:__trace_add_new_event
```
**Symbols:**

```
ffffffe000191908-ffffffe000191d0a: event_create_dir (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int event_create_dir(struct dentry *parent, struct trace_event_file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events.c (0)
Location: kernel/trace/trace_events.c:1949
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:event_trace_init
  - kernel/trace/trace_events.c:__trace_add_new_event
```
**Symbols:**

```
ffffffff811b4a50-ffffffff811b4f12: event_create_dir (STB_LOCAL)
ffffffff811b61c5-ffffffff811b6264: event_create_dir.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int event_create_dir(struct dentry *parent, struct trace_event_file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events.c (0)
Location: kernel/trace/trace_events.c:1949
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:event_trace_init
  - kernel/trace/trace_events.c:__trace_add_new_event
```
**Symbols:**

```
ffffffff811a7850-ffffffff811a7d12: event_create_dir (STB_LOCAL)
ffffffff811a8fc5-ffffffff811a9064: event_create_dir.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int event_create_dir(struct dentry *parent, struct trace_event_file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events.c (0)
Location: kernel/trace/trace_events.c:1949
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:event_trace_init
  - kernel/trace/trace_events.c:__trace_add_new_event
```
**Symbols:**

```
ffffffff811b2820-ffffffff811b2ce2: event_create_dir (STB_LOCAL)
ffffffff811b3f95-ffffffff811b4034: event_create_dir.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int event_create_dir(struct dentry *parent, struct trace_event_file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events.c (0)
Location: kernel/trace/trace_events.c:1949
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:event_trace_init
  - kernel/trace/trace_events.c:__trace_add_new_event
```
**Symbols:**

```
ffffffff811c08c0-ffffffff811c0d82: event_create_dir (STB_LOCAL)
ffffffff811c2035-ffffffff811c20d4: event_create_dir.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct dentry *parent</code> ➡️ <code>struct eventfs_inode *parent</code>
</li>
</ul>
</details>
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
