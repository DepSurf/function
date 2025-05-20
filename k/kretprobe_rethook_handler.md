# Function: <code>kretprobe_rethook_handler</code>

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
<summary>In <code>5.19</code>: ✅</summary>

```c
void kretprobe_rethook_handler(struct rethook_node *rh, void *data, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff811eefd0)
Location: kernel/kprobes.c:2121
Inline: False
```
**Symbols:**

```
ffffffff811eefd0-ffffffff811ef04e: kretprobe_rethook_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void kretprobe_rethook_handler(struct rethook_node *rh, void *data, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff81235770)
Location: kernel/kprobes.c:2129
Inline: False
```
**Symbols:**

```
ffffffff81235770-ffffffff812357ee: kretprobe_rethook_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void kretprobe_rethook_handler(struct rethook_node *rh, void *data, long unsigned int ret_addr, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff8124c440)
Location: kernel/kprobes.c:2141
Inline: False
```
**Symbols:**

```
ffffffff8124c440-ffffffff8124c4c4: kretprobe_rethook_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void kretprobe_rethook_handler(struct rethook_node *rh, void *data, long unsigned int ret_addr, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff81266340)
Location: kernel/kprobes.c:2142
Inline: False
```
**Symbols:**

```
ffffffff81266340-ffffffff812663c4: kretprobe_rethook_handler (STB_LOCAL)
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
<code>long unsigned int ret_addr</code>
</li>
<li>
<b>Param reordered. </b>
<code>rh, data, regs</code> ➡️ <code>rh, data, ret_addr, regs</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
