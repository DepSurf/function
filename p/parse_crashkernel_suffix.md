# Function: <code>parse_crashkernel_suffix</code>

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
In kernel/kexec_core.c (ffffffff81f8114e)
Location: kernel/kexec_core.c:1175
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
In kernel/kexec_core.c (ffffffff81faa4ed)
Location: kernel/kexec_core.c:1222
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
In kernel/kexec_core.c (ffffffff81fe64f9)
Location: kernel/kexec_core.c:1224
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
In kernel/crash_core.c (ffffffff820c6aa0)
Location: kernel/crash_core.c:161
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
In kernel/crash_core.c (ffffffff826cf0d5)
Location: kernel/crash_core.c:162
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
In kernel/crash_core.c (ffffffff826f97ee)
Location: kernel/crash_core.c:162
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
In kernel/crash_core.c (ffffffff828b06c3)
Location: kernel/crash_core.c:162
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
In kernel/crash_core.c (ffffffff828c9277)
Location: kernel/crash_core.c:160
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
In kernel/crash_core.c (ffffffff828d17d5)
Location: kernel/crash_core.c:160
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int parse_crashkernel_suffix(char *cmdline, long long unsigned int *crash_size, const char *suffix);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/crash_core.c (ffffffff82cf2310)
Location: kernel/crash_core.c:160
Inline: False
```
**Symbols:**

```
ffffffff82cf2310-ffffffff82cf23d7: parse_crashkernel_suffix (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int parse_crashkernel_suffix(char *cmdline, long long unsigned int *crash_size, const char *suffix);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/crash_core.c (ffffffff82fdeda0)
Location: kernel/crash_core.c:162
Inline: False
```
**Symbols:**

```
ffffffff82fdeda0-ffffffff82fdee67: parse_crashkernel_suffix (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int parse_crashkernel_suffix(char *cmdline, long long unsigned int *crash_size, const char *suffix);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/crash_core.c (ffffffff831e98b2)
Location: kernel/crash_core.c:162
Inline: False
```
**Symbols:**

```
ffffffff831e98b2-ffffffff831e9979: parse_crashkernel_suffix (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int parse_crashkernel_suffix(char *cmdline, long long unsigned int *crash_size, const char *suffix);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/crash_core.c (ffffffff832cdee7)
Location: kernel/crash_core.c:164
Inline: False
```
**Symbols:**

```
ffffffff832cdee7-ffffffff832cdfae: parse_crashkernel_suffix (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int parse_crashkernel_suffix(char *cmdline, long long unsigned int *crash_size, const char *suffix);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/crash_core.c (ffffffff83481bd4)
Location: kernel/crash_core.c:164
Inline: False
```
**Symbols:**

```
ffffffff83481bd4-ffffffff83481c91: parse_crashkernel_suffix (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int parse_crashkernel_suffix(char *cmdline, long long unsigned int *crash_size, const char *suffix);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/crash_core.c (ffffffff83eaef70)
Location: kernel/crash_core.c:176
Inline: False
```
**Symbols:**

```
ffffffff83eaef70-ffffffff83eaf03d: parse_crashkernel_suffix (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int parse_crashkernel_suffix(char *cmdline, long long unsigned int *crash_size, const char *suffix);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/crash_core.c (ffffffff836d3fc0)
Location: kernel/crash_core.c:176
Inline: False
```
**Symbols:**

```
ffffffff836d3fc0-ffffffff836d408d: parse_crashkernel_suffix (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int parse_crashkernel_suffix(char *cmdline, long long unsigned int *crash_size, const char *suffix);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/crash_core.c (ffffffff83905fa0)
Location: kernel/crash_core.c:200
Inline: False
Direct callers:
  - kernel/crash_core.c:__parse_crashkernel
```
**Symbols:**

```
ffffffff83905fa0-ffffffff8390606d: parse_crashkernel_suffix (STB_LOCAL)
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
In kernel/crash_core.c (ffff800011449c10)
Location: kernel/crash_core.c:160
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
In kernel/crash_core.c (c1523e64)
Location: kernel/crash_core.c:160
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
In kernel/crash_core.c (c00000000136f0b8)
Location: kernel/crash_core.c:160
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
In kernel/crash_core.c (ffffffe00000afba)
Location: kernel/crash_core.c:160
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
In kernel/crash_core.c (ffffffff828ba686)
Location: kernel/crash_core.c:160
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
In kernel/crash_core.c (ffffffff828b2d19)
Location: kernel/crash_core.c:160
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
In kernel/crash_core.c (ffffffff828cd409)
Location: kernel/crash_core.c:160
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
In kernel/crash_core.c (ffffffff828d2803)
Location: kernel/crash_core.c:160
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
