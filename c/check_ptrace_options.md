# Function: <code>check_ptrace_options</code>

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
int check_ptrace_options(long unsigned int data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810da900)
Location: kernel/ptrace.c:368
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_attach
```
**Symbols:**

```
ffffffff810da900-ffffffff810da976: check_ptrace_options (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int check_ptrace_options(long unsigned int data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810fa9f0)
Location: kernel/ptrace.c:368
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_attach
```
**Symbols:**

```
ffffffff810fa9f0-ffffffff810faa66: check_ptrace_options (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int check_ptrace_options(long unsigned int data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff81106b70)
Location: kernel/ptrace.c:369
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_attach
```
**Symbols:**

```
ffffffff81106b70-ffffffff81106be6: check_ptrace_options (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int check_ptrace_options(long unsigned int data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff811104c0)
Location: kernel/ptrace.c:358
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_attach
```
**Symbols:**

```
ffffffff811104c0-ffffffff81110536: check_ptrace_options (STB_LOCAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
