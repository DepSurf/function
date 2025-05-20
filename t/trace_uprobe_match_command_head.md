# Function: <code>trace_uprobe_match_command_head</code>

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
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff811d7e5f)
Location: kernel/trace/trace_uprobe.c:284
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_match
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
In kernel/trace/trace_uprobe.c (ffffffff811f59cf)
Location: kernel/trace/trace_uprobe.c:284
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_match
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
In kernel/trace/trace_uprobe.c (ffffffff811f435f)
Location: kernel/trace/trace_uprobe.c:284
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_match
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
In kernel/trace/trace_uprobe.c (ffffffff811f51bc)
Location: kernel/trace/trace_uprobe.c:284
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_match
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
In kernel/trace/trace_uprobe.c (ffffffff812272ac)
Location: kernel/trace/trace_uprobe.c:281
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_match
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool trace_uprobe_match_command_head(struct trace_uprobe *tu, int argc, const char **argv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff81265210)
Location: kernel/trace/trace_uprobe.c:282
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_match
```
**Symbols:**

```
ffffffff81265210-ffffffff81265336: trace_uprobe_match_command_head (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool trace_uprobe_match_command_head(struct trace_uprobe *tu, int argc, const char **argv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff812b6e30)
Location: kernel/trace/trace_uprobe.c:283
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_match
```
**Symbols:**

```
ffffffff812b6e30-ffffffff812b6f56: trace_uprobe_match_command_head (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool trace_uprobe_match_command_head(struct trace_uprobe *tu, int argc, const char **argv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff812da480)
Location: kernel/trace/trace_uprobe.c:281
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_match
```
**Symbols:**

```
ffffffff812da480-ffffffff812da5a6: trace_uprobe_match_command_head (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool trace_uprobe_match_command_head(struct trace_uprobe *tu, int argc, const char **argv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff812f86d0)
Location: kernel/trace/trace_uprobe.c:276
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_match
```
**Symbols:**

```
ffffffff812f86d0-ffffffff812f87f6: trace_uprobe_match_command_head (STB_LOCAL)
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
In kernel/trace/trace_uprobe.c (ffff800010258258)
Location: kernel/trace/trace_uprobe.c:284
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_match
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
In kernel/trace/trace_uprobe.c (c048c4bc)
Location: kernel/trace/trace_uprobe.c:284
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_match
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
In kernel/trace/trace_uprobe.c (c0000000002fad30)
Location: kernel/trace/trace_uprobe.c:284
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_match
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
In kernel/trace/trace_uprobe.c (ffffffff811d047f)
Location: kernel/trace/trace_uprobe.c:284
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_match
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
In kernel/trace/trace_uprobe.c (ffffffff811c324f)
Location: kernel/trace/trace_uprobe.c:284
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_match
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
In kernel/trace/trace_uprobe.c (ffffffff811ce24f)
Location: kernel/trace/trace_uprobe.c:284
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_match
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
In kernel/trace/trace_uprobe.c (ffffffff811dc4af)
Location: kernel/trace/trace_uprobe.c:284
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_match
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
