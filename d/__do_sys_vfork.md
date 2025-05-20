# Function: <code>__do_sys_vfork</code>

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
long int __do_sys_vfork(const struct pt_regs *__unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a75b0)
Location: kernel/fork.c:2561
Inline: False
```
**Symbols:**

```
ffffffff810a75b0-ffffffff810a7606: __do_sys_vfork (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int __do_sys_vfork(const struct pt_regs *__unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a32b0)
Location: kernel/fork.c:2552
Inline: False
```
**Symbols:**

```
ffffffff810a32b0-ffffffff810a3308: __do_sys_vfork (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int __do_sys_vfork(const struct pt_regs *__unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a3f00)
Location: kernel/fork.c:2584
Inline: False
```
**Symbols:**

```
ffffffff810a3f00-ffffffff810a3f58: __do_sys_vfork (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int __do_sys_vfork(const struct pt_regs *__unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810b5720)
Location: kernel/fork.c:2677
Inline: False
```
**Symbols:**

```
ffffffff810b5720-ffffffff810b5778: __do_sys_vfork (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int __do_sys_vfork(const struct pt_regs *__unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810cbab0)
Location: kernel/fork.c:2754
Inline: False
```
**Symbols:**

```
ffffffff810cbab0-ffffffff810cbb1b: __do_sys_vfork (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int __do_sys_vfork(const struct pt_regs *__unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810e90b0)
Location: kernel/fork.c:2786
Inline: False
```
**Symbols:**

```
ffffffff810e90b0-ffffffff810e911b: __do_sys_vfork (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int __do_sys_vfork(const struct pt_regs *__unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810f4cd0)
Location: kernel/fork.c:3019
Inline: False
```
**Symbols:**

```
ffffffff810f4cd0-ffffffff810f4d3b: __do_sys_vfork (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int __do_sys_vfork(const struct pt_regs *__unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810fe070)
Location: kernel/fork.c:3009
Inline: False
```
**Symbols:**

```
ffffffff810fe070-ffffffff810fe0db: __do_sys_vfork (STB_LOCAL)
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
