# Function: <code>handle_bus_lock</code>

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
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void handle_bus_lock(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (0)
Location: arch/x86/kernel/cpu/intel.c:1152
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:noist_exc_debug
```
**Symbols:**

```
ffffffff81bc77b4-ffffffff81bc77e2: handle_bus_lock.cold (STB_LOCAL)
ffffffff8104f6e0-ffffffff8104f735: handle_bus_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void handle_bus_lock(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (0)
Location: arch/x86/kernel/cpu/intel.c:1182
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:noist_exc_debug
```
**Symbols:**

```
ffffffff81c9b16e-ffffffff81c9b19c: handle_bus_lock.cold (STB_LOCAL)
ffffffff81057890-ffffffff81057911: handle_bus_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void handle_bus_lock(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (0)
Location: arch/x86/kernel/cpu/intel.c:1247
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:noist_exc_debug
```
**Symbols:**

```
ffffffff81e4a6a6-ffffffff81e4a6d4: handle_bus_lock.cold (STB_LOCAL)
ffffffff81063ba0-ffffffff81063c4b: handle_bus_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void handle_bus_lock(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (ffffffff81072cc0)
Location: arch/x86/kernel/cpu/intel.c:1432
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:noist_exc_debug
```
**Symbols:**

```
ffffffff81072cc0-ffffffff81072d94: handle_bus_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void handle_bus_lock(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (ffffffff810748a0)
Location: arch/x86/kernel/cpu/intel.c:1432
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:noist_exc_debug
```
**Symbols:**

```
ffffffff810748a0-ffffffff81074974: handle_bus_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void handle_bus_lock(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (ffffffff8107bd70)
Location: arch/x86/kernel/cpu/intel.c:1248
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:noist_exc_debug
```
**Symbols:**

```
ffffffff8107bd70-ffffffff8107be44: handle_bus_lock (STB_GLOBAL)
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
