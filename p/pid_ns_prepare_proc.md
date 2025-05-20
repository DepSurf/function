# Function: <code>pid_ns_prepare_proc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int pid_ns_prepare_proc(struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/root.c (ffffffff8127a180)
Location: fs/proc/root.c:258
Inline: False
Direct callers:
  - kernel/pid.c:alloc_pid
```
**Symbols:**

```
ffffffff8127a180-ffffffff8127a1b0: pid_ns_prepare_proc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int pid_ns_prepare_proc(struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/root.c (ffffffff812a6e20)
Location: fs/proc/root.c:213
Inline: False
Direct callers:
  - kernel/pid.c:alloc_pid
```
**Symbols:**

```
ffffffff812a6e20-ffffffff812a6e50: pid_ns_prepare_proc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int pid_ns_prepare_proc(struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/root.c (ffffffff812bc700)
Location: fs/proc/root.c:214
Inline: False
Direct callers:
  - kernel/pid.c:alloc_pid
```
**Symbols:**

```
ffffffff812bc700-ffffffff812bc730: pid_ns_prepare_proc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int pid_ns_prepare_proc(struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/root.c (ffffffff812c9a80)
Location: fs/proc/root.c:217
Inline: False
Direct callers:
  - kernel/pid.c:alloc_pid
```
**Symbols:**

```
ffffffff812c9a80-ffffffff812c9ab0: pid_ns_prepare_proc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int pid_ns_prepare_proc(struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/root.c (ffffffff812ee310)
Location: fs/proc/root.c:218
Inline: False
Direct callers:
  - kernel/pid.c:alloc_pid
```
**Symbols:**

```
ffffffff812ee310-ffffffff812ee33d: pid_ns_prepare_proc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int pid_ns_prepare_proc(struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/root.c (ffffffff8131b380)
Location: fs/proc/root.c:210
Inline: False
Direct callers:
  - kernel/pid.c:alloc_pid
```
**Symbols:**

```
ffffffff8131b380-ffffffff8131b3ad: pid_ns_prepare_proc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int pid_ns_prepare_proc(struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/root.c (ffffffff81332410)
Location: fs/proc/root.c:210
Inline: False
Direct callers:
  - kernel/pid.c:alloc_pid
```
**Symbols:**

```
ffffffff81332410-ffffffff8133243d: pid_ns_prepare_proc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int pid_ns_prepare_proc(struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/root.c (ffffffff8135a2d0)
Location: fs/proc/root.c:302
Inline: False
Direct callers:
  - kernel/pid.c:alloc_pid
```
**Symbols:**

```
ffffffff8135a2d0-ffffffff8135a389: pid_ns_prepare_proc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int pid_ns_prepare_proc(struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/root.c (ffffffff81372500)
Location: fs/proc/root.c:301
Inline: False
Direct callers:
  - kernel/pid.c:alloc_pid
```
**Symbols:**

```
ffffffff81372500-ffffffff813725b9: pid_ns_prepare_proc (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int pid_ns_prepare_proc(struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/root.c (ffff80001043c8f8)
Location: fs/proc/root.c:301
Inline: False
Direct callers:
  - kernel/pid.c:alloc_pid
```
**Symbols:**

```
ffff80001043c8f8-ffff80001043ca24: pid_ns_prepare_proc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int pid_ns_prepare_proc(struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/root.c (c0602924)
Location: fs/proc/root.c:301
Inline: False
Direct callers:
  - kernel/pid.c:alloc_pid
```
**Symbols:**

```
c0602924-c0602a34: pid_ns_prepare_proc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int pid_ns_prepare_proc(struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/root.c (c000000000550640)
Location: fs/proc/root.c:301
Inline: False
Direct callers:
  - kernel/pid.c:alloc_pid
```
**Symbols:**

```
c000000000550640-c0000000005507bc: pid_ns_prepare_proc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int pid_ns_prepare_proc(struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/root.c (ffffffe0002d4a76)
Location: fs/proc/root.c:301
Inline: False
Direct callers:
  - kernel/pid.c:alloc_pid
```
**Symbols:**

```
ffffffe0002d4a76-ffffffe0002d4b58: pid_ns_prepare_proc (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int pid_ns_prepare_proc(struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/root.c (ffffffff8136aae0)
Location: fs/proc/root.c:301
Inline: False
Direct callers:
  - kernel/pid.c:alloc_pid
```
**Symbols:**

```
ffffffff8136aae0-ffffffff8136ab99: pid_ns_prepare_proc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int pid_ns_prepare_proc(struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/root.c (ffffffff8135b570)
Location: fs/proc/root.c:301
Inline: False
Direct callers:
  - kernel/pid.c:alloc_pid
```
**Symbols:**

```
ffffffff8135b570-ffffffff8135b629: pid_ns_prepare_proc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int pid_ns_prepare_proc(struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/root.c (ffffffff813685b0)
Location: fs/proc/root.c:301
Inline: False
Direct callers:
  - kernel/pid.c:alloc_pid
```
**Symbols:**

```
ffffffff813685b0-ffffffff81368669: pid_ns_prepare_proc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int pid_ns_prepare_proc(struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/root.c (ffffffff8137bc00)
Location: fs/proc/root.c:301
Inline: False
Direct callers:
  - kernel/pid.c:alloc_pid
```
**Symbols:**

```
ffffffff8137bc00-ffffffff8137bcb9: pid_ns_prepare_proc (STB_GLOBAL)
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
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
