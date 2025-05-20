# Function: <code>fetch_user_stack_address</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void fetch_user_stack_address(struct pt_regs *regs, void *dummy, void *dest);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff8116d200)
Location: kernel/trace/trace_probe.c:271
Inline: True
```
**Symbols:**

```
ffffffff8116d200-ffffffff8116d210: fetch_user_stack_address (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void fetch_user_stack_address(struct pt_regs *regs, void *dummy, void *dest);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff8117a6e0)
Location: kernel/trace/trace_probe.c:293
Inline: True
```
**Symbols:**

```
ffffffff8117a6e0-ffffffff8117a6f0: fetch_user_stack_address (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void fetch_user_stack_address(struct pt_regs *regs, void *dummy, void *dest);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff811861b0)
Location: kernel/trace/trace_probe.c:297
Inline: True
```
**Symbols:**

```
ffffffff811861b0-ffffffff811861c0: fetch_user_stack_address (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void fetch_user_stack_address(struct pt_regs *regs, void *dummy, void *dest);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (0)
Location: kernel/trace/trace_probe.c:298
Inline: False
```
**Symbols:**

```
ffffffff81189800-ffffffff81189810: fetch_user_stack_address (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void fetch_user_stack_address(struct pt_regs *regs, void *dummy, void *dest);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (0)
Location: kernel/trace/trace_probe.c:298
Inline: False
```
**Symbols:**

```
ffffffff81197480-ffffffff81197490: fetch_user_stack_address (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void fetch_user_stack_address(struct pt_regs *regs, void *dummy, void *dest);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (0)
Location: kernel/trace/trace_probe.c:298
Inline: False
```
**Symbols:**

```
ffffffff811acc80-ffffffff811acc8b: fetch_user_stack_address (STB_LOCAL)
```
</details>
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
</ul>
