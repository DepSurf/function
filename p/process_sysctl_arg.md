# Function: <code>process_sysctl_arg</code>

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
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int process_sysctl_arg(char *param, char *val, const char *unused, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/proc/proc_sysctl.c (0)
Location: fs/proc/proc_sysctl.c:1748
Inline: False
```
**Symbols:**

```
ffffffff813c6930-ffffffff813c6af1: process_sysctl_arg (STB_LOCAL)
ffffffff813c94f7-ffffffff813c95f1: process_sysctl_arg.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int process_sysctl_arg(char *param, char *val, const char *unused, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/proc/proc_sysctl.c (0)
Location: fs/proc/proc_sysctl.c:1748
Inline: False
```
**Symbols:**

```
ffffffff813d88f0-ffffffff813d8aca: process_sysctl_arg (STB_LOCAL)
ffffffff81bebe82-ffffffff81bebf80: process_sysctl_arg.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int process_sysctl_arg(char *param, char *val, const char *unused, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/proc/proc_sysctl.c (0)
Location: fs/proc/proc_sysctl.c:1752
Inline: False
```
**Symbols:**

```
ffffffff813df7c0-ffffffff813df991: process_sysctl_arg (STB_LOCAL)
ffffffff81bddebf-ffffffff81bddfbd: process_sysctl_arg.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int process_sysctl_arg(char *param, char *val, const char *unused, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/proc/proc_sysctl.c (0)
Location: fs/proc/proc_sysctl.c:1752
Inline: False
```
**Symbols:**

```
ffffffff81431150-ffffffff81431329: process_sysctl_arg (STB_LOCAL)
ffffffff81cc82d6-ffffffff81cc83d4: process_sysctl_arg.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int process_sysctl_arg(char *param, char *val, const char *unused, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/proc/proc_sysctl.c (0)
Location: fs/proc/proc_sysctl.c:1821
Inline: False
```
**Symbols:**

```
ffffffff814ab170-ffffffff814ab355: process_sysctl_arg (STB_LOCAL)
ffffffff81e7aec3-ffffffff81e7afbd: process_sysctl_arg.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int process_sysctl_arg(char *param, char *val, const char *unused, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff81541020)
Location: fs/proc/proc_sysctl.c:1820
Inline: False
```
**Symbols:**

```
ffffffff81541020-ffffffff81541309: process_sysctl_arg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int process_sysctl_arg(char *param, char *val, const char *unused, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff815793b0)
Location: fs/proc/proc_sysctl.c:1594
Inline: False
```
**Symbols:**

```
ffffffff815793b0-ffffffff8157969b: process_sysctl_arg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int process_sysctl_arg(char *param, char *val, const char *unused, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff815b1be0)
Location: fs/proc/proc_sysctl.c:1596
Inline: False
```
**Symbols:**

```
ffffffff815b1be0-ffffffff815b1ecb: process_sysctl_arg (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
