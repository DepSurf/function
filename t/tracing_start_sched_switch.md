# Function: <code>tracing_start_sched_switch</code>

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
In kernel/trace/trace_sched_switch.c (ffffffff81156641)
Location: kernel/trace/trace_sched_switch.c:78
Inline: True
Inline callers:
  - kernel/trace/trace_sched_switch.c:tracing_start_cmdline_record
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
In kernel/trace/trace_sched_switch.c (ffffffff81160eb1)
Location: kernel/trace/trace_sched_switch.c:78
Inline: True
Inline callers:
  - kernel/trace/trace_sched_switch.c:tracing_start_cmdline_record
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
In kernel/trace/trace_sched_switch.c (ffffffff8116b911)
Location: kernel/trace/trace_sched_switch.c:78
Inline: True
Inline callers:
  - kernel/trace/trace_sched_switch.c:tracing_start_cmdline_record
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void tracing_start_sched_switch(int ops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_sched_switch.c (ffffffff8116e950)
Location: kernel/trace/trace_sched_switch.c:89
Inline: False
Direct callers:
  - kernel/trace/trace_sched_switch.c:tracing_start_tgid_record
  - kernel/trace/trace_sched_switch.c:tracing_start_cmdline_record
```
**Symbols:**

```
ffffffff8116e950-ffffffff8116ea9f: tracing_start_sched_switch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void tracing_start_sched_switch(int ops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_sched_switch.c (ffffffff8117ba40)
Location: kernel/trace/trace_sched_switch.c:90
Inline: False
Direct callers:
  - kernel/trace/trace_sched_switch.c:tracing_start_tgid_record
  - kernel/trace/trace_sched_switch.c:tracing_start_cmdline_record
```
**Symbols:**

```
ffffffff8117ba40-ffffffff8117bb8f: tracing_start_sched_switch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void tracing_start_sched_switch(int ops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_sched_switch.c (0)
Location: kernel/trace/trace_sched_switch.c:90
Inline: False
Direct callers:
  - kernel/trace/trace_sched_switch.c:tracing_start_tgid_record
  - kernel/trace/trace_sched_switch.c:tracing_start_cmdline_record
```
**Symbols:**

```
ffffffff8118ab70-ffffffff8118ac74: tracing_start_sched_switch (STB_LOCAL)
ffffffff8118ad88-ffffffff8118ade2: tracing_start_sched_switch.cold.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void tracing_start_sched_switch(int ops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_sched_switch.c (0)
Location: kernel/trace/trace_sched_switch.c:90
Inline: False
Direct callers:
  - kernel/trace/trace_sched_switch.c:tracing_start_tgid_record
  - kernel/trace/trace_sched_switch.c:tracing_start_cmdline_record
```
**Symbols:**

```
ffffffff811984d0-ffffffff811985d4: tracing_start_sched_switch (STB_LOCAL)
ffffffff811986e8-ffffffff81198742: tracing_start_sched_switch.cold.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void tracing_start_sched_switch(int ops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_sched_switch.c (0)
Location: kernel/trace/trace_sched_switch.c:90
Inline: False
Direct callers:
  - kernel/trace/trace_sched_switch.c:tracing_start_tgid_record
  - kernel/trace/trace_sched_switch.c:tracing_start_cmdline_record
```
**Symbols:**

```
ffffffff811a6040-ffffffff811a6163: tracing_start_sched_switch (STB_LOCAL)
ffffffff811a6278-ffffffff811a62d2: tracing_start_sched_switch.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void tracing_start_sched_switch(int ops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_sched_switch.c (0)
Location: kernel/trace/trace_sched_switch.c:90
Inline: False
Direct callers:
  - kernel/trace/trace_sched_switch.c:tracing_start_tgid_record
  - kernel/trace/trace_sched_switch.c:tracing_start_cmdline_record
```
**Symbols:**

```
ffffffff811b1870-ffffffff811b195c: tracing_start_sched_switch (STB_LOCAL)
ffffffff811b1a68-ffffffff811b1ac2: tracing_start_sched_switch.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void tracing_start_sched_switch(int ops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_sched_switch.c (ffffffff811c9ba0)
Location: kernel/trace/trace_sched_switch.c:90
Inline: False
Direct callers:
  - kernel/trace/trace_sched_switch.c:tracing_start_tgid_record
  - kernel/trace/trace_sched_switch.c:tracing_start_cmdline_record
```
**Symbols:**

```
ffffffff811c9ba0-ffffffff811c9c12: tracing_start_sched_switch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void tracing_start_sched_switch(int ops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_sched_switch.c (ffffffff811c7260)
Location: kernel/trace/trace_sched_switch.c:90
Inline: False
Direct callers:
  - kernel/trace/trace_sched_switch.c:tracing_start_tgid_record
  - kernel/trace/trace_sched_switch.c:tracing_start_cmdline_record
```
**Symbols:**

```
ffffffff811c7260-ffffffff811c72d2: tracing_start_sched_switch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void tracing_start_sched_switch(int ops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_sched_switch.c (0)
Location: kernel/trace/trace_sched_switch.c:90
Inline: False
Direct callers:
  - kernel/trace/trace_sched_switch.c:tracing_start_tgid_record
  - kernel/trace/trace_sched_switch.c:tracing_start_cmdline_record
```
**Symbols:**

```
ffffffff811c8330-ffffffff811c83fa: tracing_start_sched_switch (STB_LOCAL)
ffffffff81bd7991-ffffffff81bd79eb: tracing_start_sched_switch.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void tracing_start_sched_switch(int ops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_sched_switch.c (0)
Location: kernel/trace/trace_sched_switch.c:90
Inline: False
Direct callers:
  - kernel/trace/trace_sched_switch.c:tracing_start_tgid_record
  - kernel/trace/trace_sched_switch.c:tracing_start_cmdline_record
```
**Symbols:**

```
ffffffff811f3d00-ffffffff811f3dca: tracing_start_sched_switch (STB_LOCAL)
ffffffff81cb5c85-ffffffff81cb5cdf: tracing_start_sched_switch.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void tracing_start_sched_switch(int ops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_sched_switch.c (0)
Location: kernel/trace/trace_sched_switch.c:91
Inline: False
Direct callers:
  - kernel/trace/trace_sched_switch.c:tracing_start_tgid_record
  - kernel/trace/trace_sched_switch.c:tracing_start_cmdline_record
```
**Symbols:**

```
ffffffff8122d4a0-ffffffff8122d57f: tracing_start_sched_switch (STB_LOCAL)
ffffffff81e66ca5-ffffffff81e66cff: tracing_start_sched_switch.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void tracing_start_sched_switch(int ops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_sched_switch.c (ffffffff812791b0)
Location: kernel/trace/trace_sched_switch.c:91
Inline: False
Direct callers:
  - kernel/trace/trace_sched_switch.c:tracing_start_tgid_record
  - kernel/trace/trace_sched_switch.c:tracing_start_cmdline_record
```
**Symbols:**

```
ffffffff812791b0-ffffffff812792cf: tracing_start_sched_switch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void tracing_start_sched_switch(int ops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_sched_switch.c (ffffffff81290bf0)
Location: kernel/trace/trace_sched_switch.c:91
Inline: False
Direct callers:
  - kernel/trace/trace_sched_switch.c:tracing_start_tgid_record
  - kernel/trace/trace_sched_switch.c:tracing_start_cmdline_record
```
**Symbols:**

```
ffffffff81290bf0-ffffffff81290d0f: tracing_start_sched_switch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void tracing_start_sched_switch(int ops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_sched_switch.c (ffffffff812ac200)
Location: kernel/trace/trace_sched_switch.c:91
Inline: False
Direct callers:
  - kernel/trace/trace_sched_switch.c:tracing_start_tgid_record
  - kernel/trace/trace_sched_switch.c:tracing_start_cmdline_record
```
**Symbols:**

```
ffffffff812ac200-ffffffff812ac31f: tracing_start_sched_switch (STB_LOCAL)
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
void tracing_start_sched_switch(int ops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_sched_switch.c (ffff80001022f5e8)
Location: kernel/trace/trace_sched_switch.c:90
Inline: False
Direct callers:
  - kernel/trace/trace_sched_switch.c:tracing_start_tgid_record
  - kernel/trace/trace_sched_switch.c:tracing_start_cmdline_record
```
**Symbols:**

```
ffff80001022f5e8-ffff80001022f748: tracing_start_sched_switch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void tracing_start_sched_switch(int ops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_sched_switch.c (c046b2b8)
Location: kernel/trace/trace_sched_switch.c:90
Inline: False
Direct callers:
  - kernel/trace/trace_sched_switch.c:tracing_start_tgid_record
  - kernel/trace/trace_sched_switch.c:tracing_start_cmdline_record
```
**Symbols:**

```
c046b2b8-c046b3e8: tracing_start_sched_switch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void tracing_start_sched_switch(int ops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_sched_switch.c (c0000000002b8f60)
Location: kernel/trace/trace_sched_switch.c:90
Inline: False
Direct callers:
  - kernel/trace/trace_sched_switch.c:tracing_start_tgid_record
  - kernel/trace/trace_sched_switch.c:tracing_start_cmdline_record
```
**Symbols:**

```
c0000000002b8f60-c0000000002b9170: tracing_start_sched_switch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void tracing_start_sched_switch(int ops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_sched_switch.c (ffffffe00018764a)
Location: kernel/trace/trace_sched_switch.c:90
Inline: False
Direct callers:
  - kernel/trace/trace_sched_switch.c:tracing_start_tgid_record
  - kernel/trace/trace_sched_switch.c:tracing_start_cmdline_record
```
**Symbols:**

```
ffffffe00018764a-ffffffe00018778c: tracing_start_sched_switch (STB_LOCAL)
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
void tracing_start_sched_switch(int ops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_sched_switch.c (0)
Location: kernel/trace/trace_sched_switch.c:90
Inline: False
Direct callers:
  - kernel/trace/trace_sched_switch.c:tracing_start_tgid_record
  - kernel/trace/trace_sched_switch.c:tracing_start_cmdline_record
```
**Symbols:**

```
ffffffff811a9e90-ffffffff811a9f7c: tracing_start_sched_switch (STB_LOCAL)
ffffffff811aa088-ffffffff811aa0e2: tracing_start_sched_switch.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void tracing_start_sched_switch(int ops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_sched_switch.c (0)
Location: kernel/trace/trace_sched_switch.c:90
Inline: False
Direct callers:
  - kernel/trace/trace_sched_switch.c:tracing_start_tgid_record
  - kernel/trace/trace_sched_switch.c:tracing_start_cmdline_record
```
**Symbols:**

```
ffffffff8119ce10-ffffffff8119cefc: tracing_start_sched_switch (STB_LOCAL)
ffffffff8119d008-ffffffff8119d062: tracing_start_sched_switch.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void tracing_start_sched_switch(int ops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_sched_switch.c (0)
Location: kernel/trace/trace_sched_switch.c:90
Inline: False
Direct callers:
  - kernel/trace/trace_sched_switch.c:tracing_start_tgid_record
  - kernel/trace/trace_sched_switch.c:tracing_start_cmdline_record
```
**Symbols:**

```
ffffffff811a7c60-ffffffff811a7d4c: tracing_start_sched_switch (STB_LOCAL)
ffffffff811a7e58-ffffffff811a7eb2: tracing_start_sched_switch.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void tracing_start_sched_switch(int ops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_sched_switch.c (0)
Location: kernel/trace/trace_sched_switch.c:90
Inline: False
Direct callers:
  - kernel/trace/trace_sched_switch.c:tracing_start_tgid_record
  - kernel/trace/trace_sched_switch.c:tracing_start_cmdline_record
```
**Symbols:**

```
ffffffff811b5a00-ffffffff811b5aec: tracing_start_sched_switch (STB_LOCAL)
ffffffff811b5bf8-ffffffff811b5c52: tracing_start_sched_switch.cold (STB_LOCAL)
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
