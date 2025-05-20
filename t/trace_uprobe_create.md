# Function: <code>trace_uprobe_create</code>

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
int trace_uprobe_create(int argc, const char **argv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_uprobe.c (0)
Location: kernel/trace/trace_uprobe.c:426
Inline: False
```
**Symbols:**

```
ffffffff811bdd10-ffffffff811be362: trace_uprobe_create (STB_LOCAL)
ffffffff811be5d4-ffffffff811be673: trace_uprobe_create.cold.27 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int trace_uprobe_create(int argc, const char **argv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_uprobe.c (0)
Location: kernel/trace/trace_uprobe.c:434
Inline: False
```
**Symbols:**

```
ffffffff811ccc60-ffffffff811cd390: trace_uprobe_create (STB_LOCAL)
ffffffff811ce1de-ffffffff811ce21d: trace_uprobe_create.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int trace_uprobe_create(int argc, const char **argv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_uprobe.c (0)
Location: kernel/trace/trace_uprobe.c:533
Inline: False
```
**Symbols:**

```
ffffffff811d9220-ffffffff811d9a04: trace_uprobe_create (STB_LOCAL)
ffffffff811da811-ffffffff811da83b: trace_uprobe_create.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int trace_uprobe_create(int argc, const char **argv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff811f5ef0)
Location: kernel/trace/trace_uprobe.c:533
Inline: False
```
**Symbols:**

```
ffffffff811f5ef0-ffffffff811f63f3: trace_uprobe_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int trace_uprobe_create(int argc, const char **argv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff811f4880)
Location: kernel/trace/trace_uprobe.c:533
Inline: False
```
**Symbols:**

```
ffffffff811f4880-ffffffff811f4dd5: trace_uprobe_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int trace_uprobe_create(const char *raw_command);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff811f3fb0)
Location: kernel/trace/trace_uprobe.c:719
Inline: True
```
**Symbols:**

```
ffffffff811f3fb0-ffffffff811f3fc2: trace_uprobe_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int trace_uprobe_create(const char *raw_command);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff81225300)
Location: kernel/trace/trace_uprobe.c:719
Inline: True
```
**Symbols:**

```
ffffffff81225300-ffffffff81225312: trace_uprobe_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int trace_uprobe_create(const char *raw_command);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff81265340)
Location: kernel/trace/trace_uprobe.c:717
Inline: True
```
**Symbols:**

```
ffffffff81265340-ffffffff8126535a: trace_uprobe_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int trace_uprobe_create(const char *raw_command);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff812b6f70)
Location: kernel/trace/trace_uprobe.c:723
Inline: True
```
**Symbols:**

```
ffffffff812b6f70-ffffffff812b6f8a: trace_uprobe_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int trace_uprobe_create(const char *raw_command);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff812da5c0)
Location: kernel/trace/trace_uprobe.c:723
Inline: True
```
**Symbols:**

```
ffffffff812da5c0-ffffffff812da5da: trace_uprobe_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int trace_uprobe_create(const char *raw_command);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff812f8810)
Location: kernel/trace/trace_uprobe.c:719
Inline: True
```
**Symbols:**

```
ffffffff812f8810-ffffffff812f882a: trace_uprobe_create (STB_LOCAL)
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
int trace_uprobe_create(int argc, const char **argv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffff800010258c68)
Location: kernel/trace/trace_uprobe.c:533
Inline: False
```
**Symbols:**

```
ffff800010258c68-ffff800010259388: trace_uprobe_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int trace_uprobe_create(int argc, const char **argv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (c048c6c8)
Location: kernel/trace/trace_uprobe.c:533
Inline: False
```
**Symbols:**

```
c048c6c8-c048cea0: trace_uprobe_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int trace_uprobe_create(int argc, const char **argv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (c0000000002fc500)
Location: kernel/trace/trace_uprobe.c:533
Inline: False
```
**Symbols:**

```
c0000000002fc500-c0000000002fd0c4: trace_uprobe_create (STB_LOCAL)
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
int trace_uprobe_create(int argc, const char **argv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_uprobe.c (0)
Location: kernel/trace/trace_uprobe.c:533
Inline: False
```
**Symbols:**

```
ffffffff811d1840-ffffffff811d2024: trace_uprobe_create (STB_LOCAL)
ffffffff811d2e31-ffffffff811d2e5b: trace_uprobe_create.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int trace_uprobe_create(int argc, const char **argv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_uprobe.c (0)
Location: kernel/trace/trace_uprobe.c:533
Inline: False
```
**Symbols:**

```
ffffffff811c4610-ffffffff811c4df4: trace_uprobe_create (STB_LOCAL)
ffffffff811c5c01-ffffffff811c5c2b: trace_uprobe_create.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int trace_uprobe_create(int argc, const char **argv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_uprobe.c (0)
Location: kernel/trace/trace_uprobe.c:533
Inline: False
```
**Symbols:**

```
ffffffff811cf610-ffffffff811cfdf4: trace_uprobe_create (STB_LOCAL)
ffffffff811d0c01-ffffffff811d0c2b: trace_uprobe_create.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int trace_uprobe_create(int argc, const char **argv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_uprobe.c (0)
Location: kernel/trace/trace_uprobe.c:533
Inline: False
```
**Symbols:**

```
ffffffff811dd8b0-ffffffff811de094: trace_uprobe_create (STB_LOCAL)
ffffffff811deec1-ffffffff811deeeb: trace_uprobe_create.cold (STB_LOCAL)
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
