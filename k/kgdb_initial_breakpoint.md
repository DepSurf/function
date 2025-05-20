# Function: <code>kgdb_initial_breakpoint</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff81f827d1)
Location: kernel/debug/debug_core.c:968
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_register_io_module
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff8113899e)
Location: kernel/debug/debug_core.c:968
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_register_io_module
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff8114272e)
Location: kernel/debug/debug_core.c:968
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_register_io_module
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff81143f63)
Location: kernel/debug/debug_core.c:969
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_register_io_module
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff81150c26)
Location: kernel/debug/debug_core.c:969
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_register_io_module
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff826fb620)
Location: kernel/debug/debug_core.c:969
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:opt_kgdb_wait
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff828b2516)
Location: kernel/debug/debug_core.c:1032
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:opt_kgdb_wait
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff828cb24a)
Location: kernel/debug/debug_core.c:1032
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:opt_kgdb_wait
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff828d372c)
Location: kernel/debug/debug_core.c:1020
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:opt_kgdb_wait
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void kgdb_initial_breakpoint();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff811993be)
Location: kernel/debug/debug_core.c:968
Inline: False
Direct callers:
  - kernel/debug/debug_core.c:opt_kgdb_wait
  - kernel/debug/debug_core.c:kgdb_register_io_module
  - kernel/debug/debug_core.c:dbg_late_init
```
**Symbols:**

```
ffffffff811993be-ffffffff811993e4: kgdb_initial_breakpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void kgdb_initial_breakpoint();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff81be4ad4)
Location: kernel/debug/debug_core.c:1007
Inline: False
Direct callers:
  - kernel/debug/debug_core.c:opt_kgdb_wait
  - kernel/debug/debug_core.c:kgdb_register_io_module
  - kernel/debug/debug_core.c:dbg_late_init
```
**Symbols:**

```
ffffffff81be4ad4-ffffffff81be4afa: kgdb_initial_breakpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void kgdb_initial_breakpoint();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff81bd6947)
Location: kernel/debug/debug_core.c:1006
Inline: False
Direct callers:
  - kernel/debug/debug_core.c:opt_kgdb_wait
  - kernel/debug/debug_core.c:kgdb_register_io_module
  - kernel/debug/debug_core.c:dbg_late_init
```
**Symbols:**

```
ffffffff81bd6947-ffffffff81bd696d: kgdb_initial_breakpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void kgdb_initial_breakpoint();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff81cb3945)
Location: kernel/debug/debug_core.c:1003
Inline: False
Direct callers:
  - kernel/debug/debug_core.c:opt_kgdb_wait
  - kernel/debug/debug_core.c:kgdb_register_io_module
  - kernel/debug/debug_core.c:dbg_late_init
```
**Symbols:**

```
ffffffff81cb3945-ffffffff81cb396b: kgdb_initial_breakpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void kgdb_initial_breakpoint();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff81e64795)
Location: kernel/debug/debug_core.c:1027
Inline: False
Direct callers:
  - kernel/debug/debug_core.c:opt_kgdb_wait
  - kernel/debug/debug_core.c:kgdb_register_io_module
  - kernel/debug/debug_core.c:dbg_late_init
```
**Symbols:**

```
ffffffff81e64795-ffffffff81e647c1: kgdb_initial_breakpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff83eb2171)
Location: kernel/debug/debug_core.c:1015
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:opt_kgdb_wait
  - kernel/debug/debug_core.c:kgdb_register_io_module
  - kernel/debug/debug_core.c:dbg_late_init
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff836d7121)
Location: kernel/debug/debug_core.c:1015
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:opt_kgdb_wait
  - kernel/debug/debug_core.c:kgdb_register_io_module
  - kernel/debug/debug_core.c:dbg_late_init
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff839095a1)
Location: kernel/debug/debug_core.c:1018
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:opt_kgdb_wait
  - kernel/debug/debug_core.c:kgdb_register_io_module
  - kernel/debug/debug_core.c:dbg_late_init
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffff80001144bdac)
Location: kernel/debug/debug_core.c:1020
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:opt_kgdb_wait
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
In kernel/debug/debug_core.c (c1526324)
Location: kernel/debug/debug_core.c:1020
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:opt_kgdb_wait
  - kernel/debug/debug_core.c:kgdb_register_io_module
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (c000000001371ad8)
Location: kernel/debug/debug_core.c:1020
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:opt_kgdb_wait
  - kernel/debug/debug_core.c:kgdb_register_io_module
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
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff828bc5dd)
Location: kernel/debug/debug_core.c:1020
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:opt_kgdb_wait
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff828b4c70)
Location: kernel/debug/debug_core.c:1020
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:opt_kgdb_wait
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff828cf360)
Location: kernel/debug/debug_core.c:1020
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:opt_kgdb_wait
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff828d475a)
Location: kernel/debug/debug_core.c:1020
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:opt_kgdb_wait
```
</details>
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
</ul>
