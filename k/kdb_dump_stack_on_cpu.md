# Function: <code>kdb_dump_stack_on_cpu</code>

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
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void kdb_dump_stack_on_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/debug/debug_core.c (0)
Location: kernel/debug/debug_core.c:455
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_show_stack
```
**Symbols:**

```
ffffffff811994c6-ffffffff811994d0: kdb_dump_stack_on_cpu.cold (STB_LOCAL)
ffffffff81198fa0-ffffffff81198fef: kdb_dump_stack_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void kdb_dump_stack_on_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/debug/debug_core.c (0)
Location: kernel/debug/debug_core.c:471
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_show_stack
```
**Symbols:**

```
ffffffff81be4bec-ffffffff81be4bf6: kdb_dump_stack_on_cpu.cold (STB_LOCAL)
ffffffff81196540-ffffffff8119658f: kdb_dump_stack_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void kdb_dump_stack_on_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/debug/debug_core.c (0)
Location: kernel/debug/debug_core.c:470
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_show_stack
```
**Symbols:**

```
ffffffff81bd6a60-ffffffff81bd6a6a: kdb_dump_stack_on_cpu.cold (STB_LOCAL)
ffffffff811974f0-ffffffff8119753f: kdb_dump_stack_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void kdb_dump_stack_on_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/debug/debug_core.c (0)
Location: kernel/debug/debug_core.c:467
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_show_stack
```
**Symbols:**

```
ffffffff81cb3a7b-ffffffff81cb3a85: kdb_dump_stack_on_cpu.cold (STB_LOCAL)
ffffffff811c11a0-ffffffff811c12aa: kdb_dump_stack_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void kdb_dump_stack_on_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/debug/debug_core.c (0)
Location: kernel/debug/debug_core.c:468
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_show_stack
```
**Symbols:**

```
ffffffff81e648e7-ffffffff81e648f1: kdb_dump_stack_on_cpu.cold (STB_LOCAL)
ffffffff811f4770-ffffffff811f4891: kdb_dump_stack_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void kdb_dump_stack_on_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff8123b6b0)
Location: kernel/debug/debug_core.c:456
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_show_stack
```
**Symbols:**

```
ffffffff8123b6b0-ffffffff8123b7eb: kdb_dump_stack_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void kdb_dump_stack_on_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff812526c0)
Location: kernel/debug/debug_core.c:456
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_show_stack
```
**Symbols:**

```
ffffffff812526c0-ffffffff812527fb: kdb_dump_stack_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void kdb_dump_stack_on_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff8126c510)
Location: kernel/debug/debug_core.c:456
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_show_stack
```
**Symbols:**

```
ffffffff8126c510-ffffffff8126c64b: kdb_dump_stack_on_cpu (STB_GLOBAL)
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
