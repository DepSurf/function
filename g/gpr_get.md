# Function: <code>gpr_get</code>

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
int gpr_get(struct task_struct *target, const struct user_regset *regset, unsigned int pos, unsigned int count, void *kbuf, void *ubuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm64/kernel/ptrace.c (ffff80001008b3e0)
Location: arch/arm64/kernel/ptrace.c:591
Inline: False
```
**Symbols:**

```
ffff80001008b3e0-ffff80001008b558: gpr_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int gpr_get(struct task_struct *target, const struct user_regset *regset, unsigned int pos, unsigned int count, void *kbuf, void *ubuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm/kernel/ptrace.c (c030bf44)
Location: arch/arm/kernel/ptrace.c:571
Inline: False
Direct callers:
  - arch/arm/kernel/ptrace.c:arch_ptrace
```
**Symbols:**

```
c030bf44-c030c018: gpr_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int gpr_get(struct task_struct *target, const struct user_regset *regset, unsigned int pos, unsigned int count, void *kbuf, void *ubuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/ptrace.c (c000000000016900)
Location: arch/powerpc/kernel/ptrace.c:337
Inline: False
Direct callers:
  - arch/powerpc/kernel/ptrace.c:arch_ptrace
```
**Symbols:**

```
c000000000016900-c000000000016ea4: gpr_get (STB_LOCAL)
```
</details>
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
<b>Arch</b>
<ul>
</ul>
