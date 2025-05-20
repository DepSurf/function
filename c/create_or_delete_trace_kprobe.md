# Function: <code>create_or_delete_trace_kprobe</code>

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
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int create_or_delete_trace_kprobe(int argc, char **argv);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811b5a70)
Location: kernel/trace/trace_kprobe.c:729
Inline: True
```
**Symbols:**

```
ffffffff811b5a70-ffffffff811b5a9b: create_or_delete_trace_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int create_or_delete_trace_kprobe(int argc, char **argv);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811c48f0)
Location: kernel/trace/trace_kprobe.c:720
Inline: True
```
**Symbols:**

```
ffffffff811c48f0-ffffffff811c491d: create_or_delete_trace_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int create_or_delete_trace_kprobe(int argc, char **argv);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811d0650)
Location: kernel/trace/trace_kprobe.c:894
Inline: True
```
**Symbols:**

```
ffffffff811d0650-ffffffff811d067d: create_or_delete_trace_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int create_or_delete_trace_kprobe(int argc, char **argv);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811ee450)
Location: kernel/trace/trace_kprobe.c:893
Inline: True
```
**Symbols:**

```
ffffffff811ee450-ffffffff811ee47d: create_or_delete_trace_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int create_or_delete_trace_kprobe(int argc, char **argv);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811ec690)
Location: kernel/trace/trace_kprobe.c:913
Inline: True
```
**Symbols:**

```
ffffffff811ec690-ffffffff811ec6bd: create_or_delete_trace_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int create_or_delete_trace_kprobe(const char *raw_command);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811eb67f)
Location: kernel/trace/trace_kprobe.c:918
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kprobe_event_delete
  - kernel/trace/trace_kprobe.c:kprobe_event_delete
  - kernel/trace/trace_kprobe.c:trace_kprobe_run_command
  - kernel/trace/trace_kprobe.c:trace_kprobe_run_command
Direct callers:
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
```
**Symbols:**

```
ffffffff811ea9f0-ffffffff811eaa21: create_or_delete_trace_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int create_or_delete_trace_kprobe(const char *raw_command);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff8121c57f)
Location: kernel/trace/trace_kprobe.c:909
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kprobe_event_delete
  - kernel/trace/trace_kprobe.c:kprobe_event_delete
  - kernel/trace/trace_kprobe.c:trace_kprobe_run_command
  - kernel/trace/trace_kprobe.c:trace_kprobe_run_command
Direct callers:
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
```
**Symbols:**

```
ffffffff8121b7f0-ffffffff8121b821: create_or_delete_trace_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int create_or_delete_trace_kprobe(const char *raw_command);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff8125b351)
Location: kernel/trace/trace_kprobe.c:905
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kprobe_event_delete
  - kernel/trace/trace_kprobe.c:kprobe_event_delete
  - kernel/trace/trace_kprobe.c:trace_kprobe_run_command
  - kernel/trace/trace_kprobe.c:trace_kprobe_run_command
Direct callers:
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
```
**Symbols:**

```
ffffffff8125abd0-ffffffff8125ac19: create_or_delete_trace_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int create_or_delete_trace_kprobe(const char *raw_command);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff83eb6ae6)
Location: kernel/trace/trace_kprobe.c:910
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/trace/trace_kprobe.c:kprobe_event_delete
  - kernel/trace/trace_kprobe.c:kprobe_event_delete
  - kernel/trace/trace_kprobe.c:trace_kprobe_run_command
  - kernel/trace/trace_kprobe.c:trace_kprobe_run_command
```
**Symbols:**

```
ffffffff812ab080-ffffffff812ab0c9: create_or_delete_trace_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int create_or_delete_trace_kprobe(const char *raw_command);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff836dc0c6)
Location: kernel/trace/trace_kprobe.c:927
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/trace/trace_kprobe.c:kprobe_event_delete
  - kernel/trace/trace_kprobe.c:kprobe_event_delete
  - kernel/trace/trace_kprobe.c:trace_kprobe_run_command
  - kernel/trace/trace_kprobe.c:trace_kprobe_run_command
```
**Symbols:**

```
ffffffff812cd840-ffffffff812cd889: create_or_delete_trace_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int create_or_delete_trace_kprobe(const char *raw_command);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff8390e6f6)
Location: kernel/trace/trace_kprobe.c:988
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/trace/trace_kprobe.c:kprobe_event_delete
  - kernel/trace/trace_kprobe.c:kprobe_event_delete
  - kernel/trace/trace_kprobe.c:trace_kprobe_run_command
  - kernel/trace/trace_kprobe.c:trace_kprobe_run_command
```
**Symbols:**

```
ffffffff812eb230-ffffffff812eb279: create_or_delete_trace_kprobe (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int create_or_delete_trace_kprobe(int argc, char **argv);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffff800010250d88)
Location: kernel/trace/trace_kprobe.c:894
Inline: True
```
**Symbols:**

```
ffff800010250d88-ffff800010250dd0: create_or_delete_trace_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int create_or_delete_trace_kprobe(int argc, char **argv);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (c0484520)
Location: kernel/trace/trace_kprobe.c:894
Inline: True
```
**Symbols:**

```
c0484520-c048455c: create_or_delete_trace_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int create_or_delete_trace_kprobe(int argc, char **argv);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (c0000000002ef800)
Location: kernel/trace/trace_kprobe.c:894
Inline: True
```
**Symbols:**

```
c0000000002ef800-c0000000002ef868: create_or_delete_trace_kprobe (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int create_or_delete_trace_kprobe(int argc, char **argv);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811c8c70)
Location: kernel/trace/trace_kprobe.c:894
Inline: True
```
**Symbols:**

```
ffffffff811c8c70-ffffffff811c8c9d: create_or_delete_trace_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int create_or_delete_trace_kprobe(int argc, char **argv);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811bba50)
Location: kernel/trace/trace_kprobe.c:894
Inline: True
```
**Symbols:**

```
ffffffff811bba50-ffffffff811bba7d: create_or_delete_trace_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int create_or_delete_trace_kprobe(int argc, char **argv);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811c6a40)
Location: kernel/trace/trace_kprobe.c:894
Inline: True
```
**Symbols:**

```
ffffffff811c6a40-ffffffff811c6a6d: create_or_delete_trace_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int create_or_delete_trace_kprobe(int argc, char **argv);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811d4ca0)
Location: kernel/trace/trace_kprobe.c:894
Inline: True
```
**Symbols:**

```
ffffffff811d4ca0-ffffffff811d4ccd: create_or_delete_trace_kprobe (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const char *raw_command</code>
</li>
<li>
<b>Param removed. </b>
<code>int argc</code>
</li>
<li>
<b>Param removed. </b>
<code>char **argv</code>
</li>
</ul>
</details>
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
