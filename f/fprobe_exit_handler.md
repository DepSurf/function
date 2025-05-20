# Function: <code>fprobe_exit_handler</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void fprobe_exit_handler(struct rethook_node *rh, void *data, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/fprobe.c (ffffffff81268510)
Location: kernel/trace/fprobe.c:73
Inline: True
```
**Symbols:**

```
ffffffff81268510-ffffffff81268553: fprobe_exit_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void fprobe_exit_handler(struct rethook_node *rh, void *data, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/fprobe.c (ffffffff812ba740)
Location: kernel/trace/fprobe.c:73
Inline: True
```
**Symbols:**

```
ffffffff812ba740-ffffffff812ba783: fprobe_exit_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void fprobe_exit_handler(struct rethook_node *rh, void *data, long unsigned int ret_ip, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/fprobe.c (ffffffff812dde70)
Location: kernel/trace/fprobe.c:122
Inline: True
```
**Symbols:**

```
ffffffff812ddcd0-ffffffff812dde5b: fprobe_exit_handler.part.0 (STB_LOCAL)
ffffffff820ddf4b-ffffffff820ddf5f: fprobe_exit_handler.part.0.cold (STB_LOCAL)
ffffffff812dde70-ffffffff812ddea2: fprobe_exit_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void fprobe_exit_handler(struct rethook_node *rh, void *data, long unsigned int ret_ip, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/fprobe.c (ffffffff812fbf60)
Location: kernel/trace/fprobe.c:122
Inline: True
```
**Symbols:**

```
ffffffff812fbdc0-ffffffff812fbf4b: fprobe_exit_handler.part.0 (STB_LOCAL)
ffffffff821b9d69-ffffffff821b9d7d: fprobe_exit_handler.part.0.cold (STB_LOCAL)
ffffffff812fbf60-ffffffff812fbf92: fprobe_exit_handler (STB_LOCAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int ret_ip</code>
</li>
<li>
<b>Param reordered. </b>
<code>rh, data, regs</code> ➡️ <code>rh, data, ret_ip, regs</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
