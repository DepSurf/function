# Function: <code>bpf_trampoline_update</code>

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
<summary>In <code>5.8</code>: ✅</summary>

```c
int bpf_trampoline_update(struct bpf_trampoline *tr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/trampoline.c (ffffffff8121f240)
Location: kernel/bpf/trampoline.c:186
Inline: False
Direct callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_unlink_prog
  - kernel/bpf/trampoline.c:bpf_trampoline_link_prog
```
**Symbols:**

```
ffffffff8121f240-ffffffff8121f411: bpf_trampoline_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int bpf_trampoline_update(struct bpf_trampoline *tr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/trampoline.c (ffffffff81222bc0)
Location: kernel/bpf/trampoline.c:301
Inline: False
Direct callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_unlink_prog
  - kernel/bpf/trampoline.c:bpf_trampoline_link_prog
```
**Symbols:**

```
ffffffff81222bc0-ffffffff81222ddc: bpf_trampoline_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bpf_trampoline_update(struct bpf_trampoline *tr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/trampoline.c (ffffffff81227400)
Location: kernel/bpf/trampoline.c:331
Inline: False
Direct callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_unlink_prog
  - kernel/bpf/trampoline.c:bpf_trampoline_link_prog
```
**Symbols:**

```
ffffffff81227400-ffffffff81227879: bpf_trampoline_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int bpf_trampoline_update(struct bpf_trampoline *tr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/trampoline.c (0)
Location: kernel/bpf/trampoline.c:333
Inline: False
Direct callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_unlink_prog
  - kernel/bpf/trampoline.c:bpf_trampoline_link_prog
```
**Symbols:**

```
ffffffff8125f500-ffffffff8125faaa: bpf_trampoline_update (STB_LOCAL)
ffffffff81cb9349-ffffffff81cb93a4: bpf_trampoline_update.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int bpf_trampoline_update(struct bpf_trampoline *tr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/trampoline.c (0)
Location: kernel/bpf/trampoline.c:333
Inline: False
Direct callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_unlink_prog
  - kernel/bpf/trampoline.c:bpf_trampoline_link_prog
```
**Symbols:**

```
ffffffff812a9c70-ffffffff812aa21d: bpf_trampoline_update (STB_LOCAL)
ffffffff81e6a63d-ffffffff81e6a68c: bpf_trampoline_update.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int bpf_trampoline_update(struct bpf_trampoline *tr, bool lock_direct_mutex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/trampoline.c (0)
Location: kernel/bpf/trampoline.c:416
Inline: False
Direct callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_unlink_prog
  - kernel/bpf/trampoline.c:__bpf_trampoline_link_prog
  - kernel/bpf/trampoline.c:bpf_tramp_ftrace_ops_func
```
**Symbols:**

```
ffffffff81308dc0-ffffffff81309482: bpf_trampoline_update (STB_LOCAL)
ffffffff820617ba-ffffffff8206181e: bpf_trampoline_update.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int bpf_trampoline_update(struct bpf_trampoline *tr, bool lock_direct_mutex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/trampoline.c (0)
Location: kernel/bpf/trampoline.c:393
Inline: False
Direct callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_unlink_prog
  - kernel/bpf/trampoline.c:__bpf_trampoline_link_prog
  - kernel/bpf/trampoline.c:bpf_tramp_ftrace_ops_func
```
**Symbols:**

```
ffffffff81337ce0-ffffffff813382cb: bpf_trampoline_update (STB_LOCAL)
ffffffff820e0e68-ffffffff820e0ec4: bpf_trampoline_update.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int bpf_trampoline_update(struct bpf_trampoline *tr, bool lock_direct_mutex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/trampoline.c (0)
Location: kernel/bpf/trampoline.c:393
Inline: False
Direct callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_unlink_prog
  - kernel/bpf/trampoline.c:__bpf_trampoline_link_prog
  - kernel/bpf/trampoline.c:bpf_tramp_ftrace_ops_func
```
**Symbols:**

```
ffffffff8135dd80-ffffffff8135e3c6: bpf_trampoline_update (STB_LOCAL)
ffffffff821bd6a9-ffffffff821bd70c: bpf_trampoline_update.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool lock_direct_mutex</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
