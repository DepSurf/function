# Function: <code>event_subsystem_dir</code>

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
In kernel/trace/trace_events.c (ffffffff811603c6)
Location: kernel/trace/trace_events.c:1981
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
In kernel/trace/trace_events.c (ffffffff8116a826)
Location: kernel/trace/trace_events.c:1877
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
In kernel/trace/trace_events.c (ffffffff81175bd6)
Location: kernel/trace/trace_events.c:1846
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
In kernel/trace/trace_events.c (ffffffff8117895d)
Location: kernel/trace/trace_events.c:1886
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
In kernel/trace/trace_events.c (ffffffff811860e6)
Location: kernel/trace/trace_events.c:1886
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
In kernel/trace/trace_events.c (ffffffff81195154)
Location: kernel/trace/trace_events.c:1884
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
In kernel/trace/trace_events.c (ffffffff811a31f4)
Location: kernel/trace/trace_events.c:1885
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
In kernel/trace/trace_events.c (ffffffff811b1109)
Location: kernel/trace/trace_events.c:1875
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
In kernel/trace/trace_events.c (ffffffff811bc5b9)
Location: kernel/trace/trace_events.c:1874
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_create_dir
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct dentry *event_subsystem_dir(struct trace_array *tr, const char *name, struct trace_event_file *file, struct dentry *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events.c (0)
Location: kernel/trace/trace_events.c:2052
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:event_create_dir
```
**Symbols:**

```
ffffffff811d4400-ffffffff811d460f: event_subsystem_dir (STB_LOCAL)
ffffffff811d7345-ffffffff811d73ac: event_subsystem_dir.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct dentry *event_subsystem_dir(struct trace_array *tr, const char *name, struct trace_event_file *file, struct dentry *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events.c (0)
Location: kernel/trace/trace_events.c:2054
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:event_create_dir
```
**Symbols:**

```
ffffffff811d1580-ffffffff811d178f: event_subsystem_dir (STB_LOCAL)
ffffffff81be60aa-ffffffff81be6111: event_subsystem_dir.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct dentry *event_subsystem_dir(struct trace_array *tr, const char *name, struct trace_event_file *file, struct dentry *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events.c (0)
Location: kernel/trace/trace_events.c:2261
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:event_create_dir
```
**Symbols:**

```
ffffffff811d2660-ffffffff811d2924: event_subsystem_dir (STB_LOCAL)
ffffffff81bd7d43-ffffffff81bd7da2: event_subsystem_dir.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct dentry *event_subsystem_dir(struct trace_array *tr, const char *name, struct trace_event_file *file, struct dentry *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events.c (0)
Location: kernel/trace/trace_events.c:2262
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:event_create_dir
```
**Symbols:**

```
ffffffff811ff3c0-ffffffff811ff684: event_subsystem_dir (STB_LOCAL)
ffffffff81cb631d-ffffffff81cb637c: event_subsystem_dir.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct dentry *event_subsystem_dir(struct trace_array *tr, const char *name, struct trace_event_file *file, struct dentry *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events.c (0)
Location: kernel/trace/trace_events.c:2281
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:event_create_dir
```
**Symbols:**

```
ffffffff8123ae70-ffffffff8123b162: event_subsystem_dir (STB_LOCAL)
ffffffff81e67339-ffffffff81e6735f: event_subsystem_dir.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct dentry *event_subsystem_dir(struct trace_array *tr, const char *name, struct trace_event_file *file, struct dentry *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff81287ad0)
Location: kernel/trace/trace_events.c:2301
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:event_create_dir
```
**Symbols:**

```
ffffffff81287ad0-ffffffff81287df1: event_subsystem_dir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct dentry *event_subsystem_dir(struct trace_array *tr, const char *name, struct trace_event_file *file, struct dentry *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff812a4800)
Location: kernel/trace/trace_events.c:2295
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:event_create_dir
```
**Symbols:**

```
ffffffff812a4800-ffffffff812a4b19: event_subsystem_dir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct eventfs_inode *event_subsystem_dir(struct trace_array *tr, const char *name, struct trace_event_file *file, struct eventfs_inode *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff812c0190)
Location: kernel/trace/trace_events.c:2356
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:event_create_dir
```
**Symbols:**

```
ffffffff812c0190-ffffffff812c0535: event_subsystem_dir (STB_LOCAL)
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
In kernel/trace/trace_events.c (ffff80001023a5ac)
Location: kernel/trace/trace_events.c:1874
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
In kernel/trace/trace_events.c (c047739c)
Location: kernel/trace/trace_events.c:1874
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
In kernel/trace/trace_events.c (c0000000002c9d74)
Location: kernel/trace/trace_events.c:1874
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
In kernel/trace/trace_events.c (ffffffe000191a2c)
Location: kernel/trace/trace_events.c:1874
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
In kernel/trace/trace_events.c (ffffffff811b4bd9)
Location: kernel/trace/trace_events.c:1874
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
In kernel/trace/trace_events.c (ffffffff811a79d9)
Location: kernel/trace/trace_events.c:1874
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
In kernel/trace/trace_events.c (ffffffff811b29a9)
Location: kernel/trace/trace_events.c:1874
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
In kernel/trace/trace_events.c (ffffffff811c0a49)
Location: kernel/trace/trace_events.c:1874
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
<li>
<b>Return type changed. </b>
<code>struct dentry *</code> ➡️ <code>struct eventfs_inode *</code>
</li>
</ul>
</details>
</li>
</ul>
