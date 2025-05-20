# Function: <code>kgdb_has_hit_break</code>

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
int kgdb_has_hit_break(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff81198e20)
Location: kernel/debug/debug_core.c:418
Inline: False
```
**Symbols:**

```
ffffffff81198e20-ffffffff81198e54: kgdb_has_hit_break (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int kgdb_has_hit_break(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff81196260)
Location: kernel/debug/debug_core.c:423
Inline: False
```
**Symbols:**

```
ffffffff81196260-ffffffff81196294: kgdb_has_hit_break (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int kgdb_has_hit_break(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff81197230)
Location: kernel/debug/debug_core.c:422
Inline: False
```
**Symbols:**

```
ffffffff81197230-ffffffff81197264: kgdb_has_hit_break (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int kgdb_has_hit_break(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff811c0d30)
Location: kernel/debug/debug_core.c:419
Inline: False
```
**Symbols:**

```
ffffffff811c0d30-ffffffff811c0dbb: kgdb_has_hit_break (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int kgdb_has_hit_break(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff811f42c0)
Location: kernel/debug/debug_core.c:420
Inline: False
```
**Symbols:**

```
ffffffff811f42c0-ffffffff811f435b: kgdb_has_hit_break (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int kgdb_has_hit_break(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff8123b170)
Location: kernel/debug/debug_core.c:408
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/core.c:can_probe
  - arch/x86/kernel/kprobes/opt.c:can_optimize
```
**Symbols:**

```
ffffffff8123b170-ffffffff8123b20b: kgdb_has_hit_break (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int kgdb_has_hit_break(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff81252180)
Location: kernel/debug/debug_core.c:408
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/core.c:can_probe
  - arch/x86/kernel/kprobes/opt.c:can_optimize
```
**Symbols:**

```
ffffffff81252180-ffffffff8125221b: kgdb_has_hit_break (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int kgdb_has_hit_break(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff8126bfd0)
Location: kernel/debug/debug_core.c:408
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/core.c:can_probe
  - arch/x86/kernel/kprobes/opt.c:can_optimize
```
**Symbols:**

```
ffffffff8126bfd0-ffffffff8126c06b: kgdb_has_hit_break (STB_GLOBAL)
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
