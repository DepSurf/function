# Function: <code>bpf_lsm_task_prctl</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int bpf_lsm_task_prctl(int option, long unsigned int arg2, long unsigned int arg3, long unsigned int arg4, long unsigned int arg5);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff81238f70)
Location: include/linux/lsm_hook_defs.h:214
Inline: False
```
**Symbols:**

```
ffffffff81238f70-ffffffff81238f80: bpf_lsm_task_prctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bpf_lsm_task_prctl(int option, long unsigned int arg2, long unsigned int arg3, long unsigned int arg4, long unsigned int arg5);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff8123d760)
Location: include/linux/lsm_hook_defs.h:224
Inline: False
```
**Symbols:**

```
ffffffff8123d760-ffffffff8123d770: bpf_lsm_task_prctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bpf_lsm_task_prctl(int option, long unsigned int arg2, long unsigned int arg3, long unsigned int arg4, long unsigned int arg5);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff81278220)
Location: include/linux/lsm_hook_defs.h:224
Inline: False
```
**Symbols:**

```
ffffffff81278220-ffffffff81278230: bpf_lsm_task_prctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bpf_lsm_task_prctl(int option, long unsigned int arg2, long unsigned int arg3, long unsigned int arg4, long unsigned int arg5);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff812c8690)
Location: include/linux/lsm_hook_defs.h:222
Inline: False
```
**Symbols:**

```
ffffffff812c8690-ffffffff812c86a4: bpf_lsm_task_prctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bpf_lsm_task_prctl(int option, long unsigned int arg2, long unsigned int arg3, long unsigned int arg4, long unsigned int arg5);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff8132eb70)
Location: include/linux/lsm_hook_defs.h:230
Inline: False
```
**Symbols:**

```
ffffffff8132eb70-ffffffff8132eb84: bpf_lsm_task_prctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bpf_lsm_task_prctl(int option, long unsigned int arg2, long unsigned int arg3, long unsigned int arg4, long unsigned int arg5);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff8135f7e0)
Location: include/linux/lsm_hook_defs.h:231
Inline: False
```
**Symbols:**

```
ffffffff8135f7e0-ffffffff8135f7f4: bpf_lsm_task_prctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bpf_lsm_task_prctl(int option, long unsigned int arg2, long unsigned int arg3, long unsigned int arg4, long unsigned int arg5);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff81388600)
Location: include/linux/lsm_hook_defs.h:236
Inline: False
```
**Symbols:**

```
ffffffff81388600-ffffffff81388614: bpf_lsm_task_prctl (STB_GLOBAL)
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
