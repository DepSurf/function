# Function: <code>parse_crashkernel_mem</code>

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
In kernel/kexec_core.c (ffffffff81f8120a)
Location: kernel/kexec_core.c:1052
Inline: True
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
In kernel/kexec_core.c (ffffffff81faa59a)
Location: kernel/kexec_core.c:1099
Inline: True
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
In kernel/kexec_core.c (ffffffff81fe65a6)
Location: kernel/kexec_core.c:1101
Inline: True
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
In kernel/crash_core.c (ffffffff820c6b4f)
Location: kernel/crash_core.c:38
Inline: True
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
In kernel/crash_core.c (ffffffff826cf185)
Location: kernel/crash_core.c:38
Inline: True
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
In kernel/crash_core.c (ffffffff826f989e)
Location: kernel/crash_core.c:38
Inline: True
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
In kernel/crash_core.c (ffffffff828b0773)
Location: kernel/crash_core.c:38
Inline: True
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
In kernel/crash_core.c (ffffffff828c9324)
Location: kernel/crash_core.c:36
Inline: True
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
In kernel/crash_core.c (ffffffff828d1882)
Location: kernel/crash_core.c:36
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int parse_crashkernel_mem(char *cmdline, long long unsigned int system_ram, long long unsigned int *crash_size, long long unsigned int *crash_base);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/crash_core.c (ffffffff82cf23d7)
Location: kernel/crash_core.c:36
Inline: False
```
**Symbols:**

```
ffffffff82cf23d7-ffffffff82cf258e: parse_crashkernel_mem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int parse_crashkernel_mem(char *cmdline, long long unsigned int system_ram, long long unsigned int *crash_size, long long unsigned int *crash_base);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/crash_core.c (ffffffff82fdee67)
Location: kernel/crash_core.c:38
Inline: False
```
**Symbols:**

```
ffffffff82fdee67-ffffffff82fdf01e: parse_crashkernel_mem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int parse_crashkernel_mem(char *cmdline, long long unsigned int system_ram, long long unsigned int *crash_size, long long unsigned int *crash_base);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/crash_core.c (ffffffff831e9979)
Location: kernel/crash_core.c:38
Inline: False
```
**Symbols:**

```
ffffffff831e9979-ffffffff831e9b2d: parse_crashkernel_mem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int parse_crashkernel_mem(char *cmdline, long long unsigned int system_ram, long long unsigned int *crash_size, long long unsigned int *crash_base);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/crash_core.c (ffffffff832cdfae)
Location: kernel/crash_core.c:40
Inline: False
```
**Symbols:**

```
ffffffff832cdfae-ffffffff832ce162: parse_crashkernel_mem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int parse_crashkernel_mem(char *cmdline, long long unsigned int system_ram, long long unsigned int *crash_size, long long unsigned int *crash_base);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/crash_core.c (ffffffff83481c91)
Location: kernel/crash_core.c:40
Inline: False
```
**Symbols:**

```
ffffffff83481c91-ffffffff83481e3b: parse_crashkernel_mem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int parse_crashkernel_mem(char *cmdline, long long unsigned int system_ram, long long unsigned int *crash_size, long long unsigned int *crash_base);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/crash_core.c (ffffffff83eaf050)
Location: kernel/crash_core.c:43
Inline: False
```
**Symbols:**

```
ffffffff83eaf050-ffffffff83eaf231: parse_crashkernel_mem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int parse_crashkernel_mem(char *cmdline, long long unsigned int system_ram, long long unsigned int *crash_size, long long unsigned int *crash_base);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/crash_core.c (ffffffff836d40a0)
Location: kernel/crash_core.c:43
Inline: False
```
**Symbols:**

```
ffffffff836d40a0-ffffffff836d4281: parse_crashkernel_mem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int parse_crashkernel_mem(char *cmdline, long long unsigned int system_ram, long long unsigned int *crash_size, long long unsigned int *crash_base);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/crash_core.c (ffffffff83906080)
Location: kernel/crash_core.c:67
Inline: False
Direct callers:
  - kernel/crash_core.c:__parse_crashkernel
```
**Symbols:**

```
ffffffff83906080-ffffffff83906261: parse_crashkernel_mem (STB_LOCAL)
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
In kernel/crash_core.c (ffff800011449cac)
Location: kernel/crash_core.c:36
Inline: True
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
In kernel/crash_core.c (c1523f1c)
Location: kernel/crash_core.c:36
Inline: True
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
In kernel/crash_core.c (0)
Location: kernel/crash_core.c:36
Inline: True
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
In kernel/crash_core.c (ffffffe00000b048)
Location: kernel/crash_core.c:36
Inline: True
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
In kernel/crash_core.c (ffffffff828ba733)
Location: kernel/crash_core.c:36
Inline: True
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
In kernel/crash_core.c (ffffffff828b2dc6)
Location: kernel/crash_core.c:36
Inline: True
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
In kernel/crash_core.c (ffffffff828cd4b6)
Location: kernel/crash_core.c:36
Inline: True
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
In kernel/crash_core.c (ffffffff828d28b0)
Location: kernel/crash_core.c:36
Inline: True
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
