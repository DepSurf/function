# Function: <code>trace_kprobe_create</code>

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
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int trace_kprobe_create(int argc, const char **argv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_kprobe.c (0)
Location: kernel/trace/trace_kprobe.c:576
Inline: False
```
**Symbols:**

```
ffffffff811b52e0-ffffffff811b5a61: trace_kprobe_create (STB_LOCAL)
ffffffff811b7066-ffffffff811b7186: trace_kprobe_create.cold.22 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int trace_kprobe_create(int argc, const char **argv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_kprobe.c (0)
Location: kernel/trace/trace_kprobe.c:539
Inline: False
```
**Symbols:**

```
ffffffff811c4090-ffffffff811c48ea: trace_kprobe_create (STB_LOCAL)
ffffffff811c60ba-ffffffff811c6141: trace_kprobe_create.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int trace_kprobe_create(int argc, const char **argv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_kprobe.c (0)
Location: kernel/trace/trace_kprobe.c:713
Inline: False
```
**Symbols:**

```
ffffffff811cffb0-ffffffff811d064d: trace_kprobe_create (STB_LOCAL)
ffffffff811d1e5a-ffffffff811d1e66: trace_kprobe_create.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int trace_kprobe_create(int argc, const char **argv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_kprobe.c (0)
Location: kernel/trace/trace_kprobe.c:712
Inline: False
```
**Symbols:**

```
ffffffff811edd80-ffffffff811ee444: trace_kprobe_create (STB_LOCAL)
ffffffff811ee839-ffffffff811ee845: trace_kprobe_create.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int trace_kprobe_create(int argc, const char **argv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_kprobe.c (0)
Location: kernel/trace/trace_kprobe.c:714
Inline: False
```
**Symbols:**

```
ffffffff811ebef0-ffffffff811ec685: trace_kprobe_create (STB_LOCAL)
ffffffff81be645b-ffffffff81be6467: trace_kprobe_create.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int trace_kprobe_create(const char *raw_command);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811eb685)
Location: kernel/trace/trace_kprobe.c:913
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kprobe_event_delete
  - kernel/trace/trace_kprobe.c:trace_kprobe_run_command
```
**Symbols:**

```
ffffffff811ea230-ffffffff811ea242: trace_kprobe_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int trace_kprobe_create(const char *raw_command);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff8121c585)
Location: kernel/trace/trace_kprobe.c:904
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kprobe_event_delete
  - kernel/trace/trace_kprobe.c:trace_kprobe_run_command
```
**Symbols:**

```
ffffffff8121b070-ffffffff8121b082: trace_kprobe_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int trace_kprobe_create(const char *raw_command);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff8125b357)
Location: kernel/trace/trace_kprobe.c:900
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kprobe_event_delete
  - kernel/trace/trace_kprobe.c:trace_kprobe_run_command
```
**Symbols:**

```
ffffffff8125a2a0-ffffffff8125a2ba: trace_kprobe_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int trace_kprobe_create(const char *raw_command);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff83eb6af0)
Location: kernel/trace/trace_kprobe.c:905
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/trace/trace_kprobe.c:kprobe_event_delete
  - kernel/trace/trace_kprobe.c:trace_kprobe_run_command
```
**Symbols:**

```
ffffffff812aa6a0-ffffffff812aa6ba: trace_kprobe_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int trace_kprobe_create(const char *raw_command);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff836dc0d0)
Location: kernel/trace/trace_kprobe.c:922
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/trace/trace_kprobe.c:kprobe_event_delete
  - kernel/trace/trace_kprobe.c:trace_kprobe_run_command
```
**Symbols:**

```
ffffffff812cce50-ffffffff812cce6a: trace_kprobe_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int trace_kprobe_create(const char *raw_command);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff8390e700)
Location: kernel/trace/trace_kprobe.c:983
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/trace/trace_kprobe.c:kprobe_event_delete
  - kernel/trace/trace_kprobe.c:trace_kprobe_run_command
```
**Symbols:**

```
ffffffff812ea840-ffffffff812ea85a: trace_kprobe_create (STB_LOCAL)
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
int trace_kprobe_create(int argc, const char **argv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffff800010250898)
Location: kernel/trace/trace_kprobe.c:713
Inline: False
```
**Symbols:**

```
ffff800010250898-ffff800010250d88: trace_kprobe_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int trace_kprobe_create(int argc, const char **argv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (c0483f90)
Location: kernel/trace/trace_kprobe.c:713
Inline: False
```
**Symbols:**

```
c0483f90-c0484520: trace_kprobe_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int trace_kprobe_create(int argc, const char **argv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (c0000000002ef0f0)
Location: kernel/trace/trace_kprobe.c:713
Inline: False
```
**Symbols:**

```
c0000000002ef0f0-c0000000002ef800: trace_kprobe_create (STB_LOCAL)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int trace_kprobe_create(int argc, const char **argv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_kprobe.c (0)
Location: kernel/trace/trace_kprobe.c:713
Inline: False
```
**Symbols:**

```
ffffffff811c85d0-ffffffff811c8c6d: trace_kprobe_create (STB_LOCAL)
ffffffff811ca47a-ffffffff811ca486: trace_kprobe_create.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int trace_kprobe_create(int argc, const char **argv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_kprobe.c (0)
Location: kernel/trace/trace_kprobe.c:713
Inline: False
```
**Symbols:**

```
ffffffff811bb3b0-ffffffff811bba4d: trace_kprobe_create (STB_LOCAL)
ffffffff811bd24a-ffffffff811bd256: trace_kprobe_create.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int trace_kprobe_create(int argc, const char **argv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_kprobe.c (0)
Location: kernel/trace/trace_kprobe.c:713
Inline: False
```
**Symbols:**

```
ffffffff811c63a0-ffffffff811c6a3d: trace_kprobe_create (STB_LOCAL)
ffffffff811c824a-ffffffff811c8256: trace_kprobe_create.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int trace_kprobe_create(int argc, const char **argv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_kprobe.c (0)
Location: kernel/trace/trace_kprobe.c:713
Inline: False
```
**Symbols:**

```
ffffffff811d4600-ffffffff811d4c9d: trace_kprobe_create (STB_LOCAL)
ffffffff811d64aa-ffffffff811d64b6: trace_kprobe_create.cold (STB_LOCAL)
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
<code>const char **argv</code>
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
