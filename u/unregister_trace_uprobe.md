# Function: <code>unregister_trace_uprobe</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int unregister_trace_uprobe(struct trace_uprobe *tu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff8116f200)
Location: kernel/trace/trace_uprobe.c:304
Inline: True
Direct callers:
  - kernel/trace/trace_uprobe.c:probes_open
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
```
**Symbols:**

```
ffffffff8116f200-ffffffff8116f271: unregister_trace_uprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int unregister_trace_uprobe(struct trace_uprobe *tu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff8117c8c0)
Location: kernel/trace/trace_uprobe.c:304
Inline: True
Direct callers:
  - kernel/trace/trace_uprobe.c:probes_open
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
```
**Symbols:**

```
ffffffff8117c8c0-ffffffff8117c931: unregister_trace_uprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int unregister_trace_uprobe(struct trace_uprobe *tu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff811884d0)
Location: kernel/trace/trace_uprobe.c:308
Inline: True
Direct callers:
  - kernel/trace/trace_uprobe.c:probes_open
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
```
**Symbols:**

```
ffffffff811884d0-ffffffff81188541: unregister_trace_uprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int unregister_trace_uprobe(struct trace_uprobe *tu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff8118b070)
Location: kernel/trace/trace_uprobe.c:310
Inline: True
Direct callers:
  - kernel/trace/trace_uprobe.c:probes_open
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
```
**Symbols:**

```
ffffffff8118b070-ffffffff8118b0dd: unregister_trace_uprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int unregister_trace_uprobe(struct trace_uprobe *tu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff81198b30)
Location: kernel/trace/trace_uprobe.c:310
Inline: True
Direct callers:
  - kernel/trace/trace_uprobe.c:probes_open
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
```
**Symbols:**

```
ffffffff81198b30-ffffffff81198b9d: unregister_trace_uprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int unregister_trace_uprobe(struct trace_uprobe *tu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff811aea60)
Location: kernel/trace/trace_uprobe.c:313
Inline: True
Direct callers:
  - kernel/trace/trace_uprobe.c:probes_open
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
```
**Symbols:**

```
ffffffff811aea60-ffffffff811aeacd: unregister_trace_uprobe (STB_LOCAL)
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
In kernel/trace/trace_uprobe.c (ffffffff811bd8d0)
Location: kernel/trace/trace_uprobe.c:341
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_release
  - kernel/trace/trace_uprobe.c:trace_uprobe_release
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
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
In kernel/trace/trace_uprobe.c (ffffffff811cd3c0)
Location: kernel/trace/trace_uprobe.c:351
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_release
  - kernel/trace/trace_uprobe.c:trace_uprobe_release
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
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
In kernel/trace/trace_uprobe.c (ffffffff811d85a0)
Location: kernel/trace/trace_uprobe.c:389
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_release
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
In kernel/trace/trace_uprobe.c (ffffffff811f6430)
Location: kernel/trace/trace_uprobe.c:389
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_release
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
In kernel/trace/trace_uprobe.c (ffffffff811f4e10)
Location: kernel/trace/trace_uprobe.c:389
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_release
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
In kernel/trace/trace_uprobe.c (ffffffff811f5d00)
Location: kernel/trace/trace_uprobe.c:389
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_release
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
In kernel/trace/trace_uprobe.c (ffffffff81227de0)
Location: kernel/trace/trace_uprobe.c:386
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_release
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
In kernel/trace/trace_uprobe.c (ffffffff81267190)
Location: kernel/trace/trace_uprobe.c:387
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_release
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
In kernel/trace/trace_uprobe.c (ffffffff812b9200)
Location: kernel/trace/trace_uprobe.c:389
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_release
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
In kernel/trace/trace_uprobe.c (ffffffff812dc860)
Location: kernel/trace/trace_uprobe.c:387
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_release
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
In kernel/trace/trace_uprobe.c (ffffffff812fa940)
Location: kernel/trace/trace_uprobe.c:382
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_release
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
In kernel/trace/trace_uprobe.c (ffff8000102588a0)
Location: kernel/trace/trace_uprobe.c:389
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_release
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
In kernel/trace/trace_uprobe.c (c048b818)
Location: kernel/trace/trace_uprobe.c:389
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_release
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
In kernel/trace/trace_uprobe.c (c0000000002fbc4c)
Location: kernel/trace/trace_uprobe.c:389
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_release
```
</details>
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
In kernel/trace/trace_uprobe.c (ffffffff811d0bc0)
Location: kernel/trace/trace_uprobe.c:389
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_release
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
In kernel/trace/trace_uprobe.c (ffffffff811c3990)
Location: kernel/trace/trace_uprobe.c:389
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_release
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
In kernel/trace/trace_uprobe.c (ffffffff811ce990)
Location: kernel/trace/trace_uprobe.c:389
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_release
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
In kernel/trace/trace_uprobe.c (ffffffff811dcc00)
Location: kernel/trace/trace_uprobe.c:389
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_release
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
</ul>
