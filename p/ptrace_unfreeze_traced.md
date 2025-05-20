# Function: <code>ptrace_unfreeze_traced</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/ptrace.c (ffffffff8108b4c0)
Location: kernel/ptrace.c:140
Inline: True
Inline callers:
  - kernel/ptrace.c:SyS_ptrace
  - kernel/ptrace.c:compat_SyS_ptrace
Direct callers:
  - kernel/ptrace.c:SyS_ptrace
  - kernel/ptrace.c:compat_SyS_ptrace
```
**Symbols:**

```
ffffffff8108b4c0-ffffffff8108b548: ptrace_unfreeze_traced.part.8 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/ptrace.c (ffffffff8108f72e)
Location: kernel/ptrace.c:139
Inline: True
Inline callers:
  - kernel/ptrace.c:compat_SyS_ptrace
  - kernel/ptrace.c:SyS_ptrace
Direct callers:
  - kernel/ptrace.c:compat_SyS_ptrace
  - kernel/ptrace.c:SyS_ptrace
```
**Symbols:**

```
ffffffff8108e1b0-ffffffff8108e238: ptrace_unfreeze_traced.part.10 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/ptrace.c (ffffffff810946ae)
Location: kernel/ptrace.c:177
Inline: True
Inline callers:
  - kernel/ptrace.c:compat_SyS_ptrace
  - kernel/ptrace.c:SyS_ptrace
Direct callers:
  - kernel/ptrace.c:compat_SyS_ptrace
  - kernel/ptrace.c:SyS_ptrace
```
**Symbols:**

```
ffffffff81092d80-ffffffff81092e09: ptrace_unfreeze_traced.part.14 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/ptrace.c (ffffffff81091788)
Location: kernel/ptrace.c:186
Inline: True
Inline callers:
  - kernel/ptrace.c:compat_SyS_ptrace
  - kernel/ptrace.c:SyS_ptrace
Direct callers:
  - kernel/ptrace.c:compat_SyS_ptrace
  - kernel/ptrace.c:SyS_ptrace
```
**Symbols:**

```
ffffffff81090170-ffffffff810901f8: ptrace_unfreeze_traced.part.12 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/ptrace.c (ffffffff81098618)
Location: kernel/ptrace.c:186
Inline: True
Inline callers:
  - kernel/ptrace.c:compat_SyS_ptrace
  - kernel/ptrace.c:SyS_ptrace
Direct callers:
  - kernel/ptrace.c:compat_SyS_ptrace
  - kernel/ptrace.c:SyS_ptrace
```
**Symbols:**

```
ffffffff81096fe0-ffffffff81097068: ptrace_unfreeze_traced.part.12 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void ptrace_unfreeze_traced(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff8109a400)
Location: kernel/ptrace.c:186
Inline: True
Direct callers:
  - kernel/ptrace.c:__x32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_sys_ptrace
  - kernel/ptrace.c:__x64_sys_ptrace
```
**Symbols:**

```
ffffffff8109a400-ffffffff8109a493: ptrace_unfreeze_traced (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void ptrace_unfreeze_traced(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810a2710)
Location: kernel/ptrace.c:186
Inline: True
Direct callers:
  - kernel/ptrace.c:__x32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_sys_ptrace
  - kernel/ptrace.c:__x64_sys_ptrace
```
**Symbols:**

```
ffffffff810a2710-ffffffff810a27a3: ptrace_unfreeze_traced (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/ptrace.c (ffffffff810a7ca8)
Location: kernel/ptrace.c:191
Inline: True
Inline callers:
  - kernel/ptrace.c:__x32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_sys_ptrace
  - kernel/ptrace.c:__x64_sys_ptrace
Direct callers:
  - kernel/ptrace.c:__x32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_sys_ptrace
  - kernel/ptrace.c:__x64_sys_ptrace
```
**Symbols:**

```
ffffffff810a73b0-ffffffff810a742e: ptrace_unfreeze_traced.part.0 (STB_LOCAL)
ffffffff810a8bf9-ffffffff810a8c0c: ptrace_unfreeze_traced.part.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/ptrace.c (ffffffff810ae2c8)
Location: kernel/ptrace.c:191
Inline: True
Inline callers:
  - kernel/ptrace.c:__x32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_sys_ptrace
  - kernel/ptrace.c:__x64_sys_ptrace
Direct callers:
  - kernel/ptrace.c:__x32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_sys_ptrace
  - kernel/ptrace.c:__x64_sys_ptrace
```
**Symbols:**

```
ffffffff810ad9d0-ffffffff810ada4a: ptrace_unfreeze_traced.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/ptrace.c (ffffffff810b605a)
Location: kernel/ptrace.c:191
Inline: True
Inline callers:
  - kernel/ptrace.c:__x32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_sys_ptrace
  - kernel/ptrace.c:__x64_sys_ptrace
Direct callers:
  - kernel/ptrace.c:__x32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_sys_ptrace
  - kernel/ptrace.c:__x64_sys_ptrace
```
**Symbols:**

```
ffffffff810b53f0-ffffffff810b546d: ptrace_unfreeze_traced.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/ptrace.c (ffffffff810b124a)
Location: kernel/ptrace.c:191
Inline: True
Inline callers:
  - kernel/ptrace.c:__x32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_sys_ptrace
  - kernel/ptrace.c:__x64_sys_ptrace
Direct callers:
  - kernel/ptrace.c:__x32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_sys_ptrace
  - kernel/ptrace.c:__x64_sys_ptrace
```
**Symbols:**

```
ffffffff810b05f0-ffffffff810b066d: ptrace_unfreeze_traced.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/ptrace.c (ffffffff810b257c)
Location: kernel/ptrace.c:208
Inline: True
Inline callers:
  - kernel/ptrace.c:__x32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_sys_ptrace
  - kernel/ptrace.c:__x64_sys_ptrace
Direct callers:
  - kernel/ptrace.c:__x32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_sys_ptrace
  - kernel/ptrace.c:__x64_sys_ptrace
```
**Symbols:**

```
ffffffff810b1b70-ffffffff810b1bed: ptrace_unfreeze_traced.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/ptrace.c (ffffffff810c484c)
Location: kernel/ptrace.c:208
Inline: True
Inline callers:
  - kernel/ptrace.c:__x64_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_sys_ptrace
  - kernel/ptrace.c:__x64_sys_ptrace
Direct callers:
  - kernel/ptrace.c:__x64_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_sys_ptrace
  - kernel/ptrace.c:__x64_sys_ptrace
```
**Symbols:**

```
ffffffff810c3d40-ffffffff810c3dba: ptrace_unfreeze_traced.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void ptrace_unfreeze_traced(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810da980)
Location: kernel/ptrace.c:213
Inline: False
Direct callers:
  - kernel/ptrace.c:__ia32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_sys_ptrace
  - kernel/ptrace.c:__x64_sys_ptrace
```
**Symbols:**

```
ffffffff810da980-ffffffff810daa29: ptrace_unfreeze_traced (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ptrace_unfreeze_traced(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810faa80)
Location: kernel/ptrace.c:213
Inline: False
Direct callers:
  - kernel/ptrace.c:__ia32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_sys_ptrace
  - kernel/ptrace.c:__x64_sys_ptrace
```
**Symbols:**

```
ffffffff810faa80-ffffffff810fab29: ptrace_unfreeze_traced (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ptrace_unfreeze_traced(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff81106c00)
Location: kernel/ptrace.c:214
Inline: False
Direct callers:
  - kernel/ptrace.c:__ia32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_sys_ptrace
  - kernel/ptrace.c:__x64_sys_ptrace
```
**Symbols:**

```
ffffffff81106c00-ffffffff81106ca9: ptrace_unfreeze_traced (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ptrace_unfreeze_traced(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff81110550)
Location: kernel/ptrace.c:203
Inline: False
Direct callers:
  - kernel/ptrace.c:__ia32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_sys_ptrace
  - kernel/ptrace.c:__x64_sys_ptrace
```
**Symbols:**

```
ffffffff81110550-ffffffff811105f9: ptrace_unfreeze_traced (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/ptrace.c (ffff8000101084b8)
Location: kernel/ptrace.c:191
Inline: True
Inline callers:
  - kernel/ptrace.c:__arm64_compat_sys_ptrace
  - kernel/ptrace.c:__arm64_sys_ptrace
Direct callers:
  - kernel/ptrace.c:__arm64_compat_sys_ptrace
  - kernel/ptrace.c:__arm64_sys_ptrace
```
**Symbols:**

```
ffff800010106da0-ffff800010106e84: ptrace_unfreeze_traced.part.0 (STB_LOCAL)
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
In kernel/ptrace.c (c036275c)
Location: kernel/ptrace.c:191
Inline: True
Inline callers:
  - kernel/ptrace.c:__se_sys_ptrace
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/ptrace.c (c00000000014fa68)
Location: kernel/ptrace.c:191
Inline: True
Inline callers:
  - kernel/ptrace.c:__se_compat_sys_ptrace
  - kernel/ptrace.c:__se_sys_ptrace
Direct callers:
  - kernel/ptrace.c:__se_compat_sys_ptrace
  - kernel/ptrace.c:__se_sys_ptrace
```
**Symbols:**

```
c00000000014eb10-c00000000014ec64: ptrace_unfreeze_traced.part.0 (STB_LOCAL)
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
In kernel/ptrace.c (ffffffe0000cc578)
Location: kernel/ptrace.c:191
Inline: True
Inline callers:
  - kernel/ptrace.c:__se_sys_ptrace
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/ptrace.c (ffffffff810a8638)
Location: kernel/ptrace.c:191
Inline: True
Inline callers:
  - kernel/ptrace.c:__x32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_sys_ptrace
  - kernel/ptrace.c:__x64_sys_ptrace
Direct callers:
  - kernel/ptrace.c:__x32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_sys_ptrace
  - kernel/ptrace.c:__x64_sys_ptrace
```
**Symbols:**

```
ffffffff810a7d40-ffffffff810a7dba: ptrace_unfreeze_traced.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/ptrace.c (ffffffff81097008)
Location: kernel/ptrace.c:191
Inline: True
Inline callers:
  - kernel/ptrace.c:__x32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_sys_ptrace
  - kernel/ptrace.c:__x64_sys_ptrace
Direct callers:
  - kernel/ptrace.c:__x32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_sys_ptrace
  - kernel/ptrace.c:__x64_sys_ptrace
```
**Symbols:**

```
ffffffff81096710-ffffffff81096784: ptrace_unfreeze_traced.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/ptrace.c (ffffffff810a7b98)
Location: kernel/ptrace.c:191
Inline: True
Inline callers:
  - kernel/ptrace.c:__x32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_sys_ptrace
  - kernel/ptrace.c:__x64_sys_ptrace
Direct callers:
  - kernel/ptrace.c:__x32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_sys_ptrace
  - kernel/ptrace.c:__x64_sys_ptrace
```
**Symbols:**

```
ffffffff810a72a0-ffffffff810a731a: ptrace_unfreeze_traced.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/ptrace.c (ffffffff810afcc8)
Location: kernel/ptrace.c:191
Inline: True
Inline callers:
  - kernel/ptrace.c:__x32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_sys_ptrace
  - kernel/ptrace.c:__x64_sys_ptrace
Direct callers:
  - kernel/ptrace.c:__x32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_sys_ptrace
  - kernel/ptrace.c:__x64_sys_ptrace
```
**Symbols:**

```
ffffffff810aed70-ffffffff810aedee: ptrace_unfreeze_traced.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
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
