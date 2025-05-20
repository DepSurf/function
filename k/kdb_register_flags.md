# Function: <code>kdb_register_flags</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int kdb_register_flags(char *cmd, kdb_func_t func, char *usage, char *help, short int minlen, kdb_cmdflags_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_main.c (ffffffff81133860)
Location: kernel/debug/kdb/kdb_main.c:2692
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd2
  - kernel/debug/kdb/kdb_main.c:kdb_register
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_bp.c:kdb_initbptab
  - kernel/debug/kdb/kdb_bp.c:kdb_initbptab
  - kernel/debug/kdb/kdb_bp.c:kdb_initbptab
  - kernel/debug/kdb/kdb_bp.c:kdb_initbptab
  - kernel/debug/kdb/kdb_bp.c:kdb_initbptab
  - kernel/debug/kdb/kdb_bp.c:kdb_initbptab
  - kernel/debug/kdb/kdb_bp.c:kdb_initbptab
  - kernel/trace/trace_kdb.c:kdb_ftrace_register
```
**Symbols:**

```
ffffffff81133860-ffffffff81133a31: kdb_register_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int kdb_register_flags(char *cmd, kdb_func_t func, char *usage, char *help, short int minlen, kdb_cmdflags_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_main.c (ffffffff8113bca0)
Location: kernel/debug/kdb/kdb_main.c:2692
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_register
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd2
  - kernel/debug/kdb/kdb_bp.c:kdb_initbptab
  - kernel/debug/kdb/kdb_bp.c:kdb_initbptab
  - kernel/debug/kdb/kdb_bp.c:kdb_initbptab
  - kernel/debug/kdb/kdb_bp.c:kdb_initbptab
  - kernel/debug/kdb/kdb_bp.c:kdb_initbptab
  - kernel/debug/kdb/kdb_bp.c:kdb_initbptab
  - kernel/debug/kdb/kdb_bp.c:kdb_initbptab
  - kernel/trace/trace_kdb.c:kdb_ftrace_register
```
**Symbols:**

```
ffffffff8113bca0-ffffffff8113be6d: kdb_register_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int kdb_register_flags(char *cmd, kdb_func_t func, char *usage, char *help, short int minlen, kdb_cmdflags_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_main.c (ffffffff81145a50)
Location: kernel/debug/kdb/kdb_main.c:2691
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_register
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd2
  - kernel/debug/kdb/kdb_bp.c:kdb_initbptab
  - kernel/debug/kdb/kdb_bp.c:kdb_initbptab
  - kernel/debug/kdb/kdb_bp.c:kdb_initbptab
  - kernel/debug/kdb/kdb_bp.c:kdb_initbptab
  - kernel/debug/kdb/kdb_bp.c:kdb_initbptab
  - kernel/debug/kdb/kdb_bp.c:kdb_initbptab
  - kernel/debug/kdb/kdb_bp.c:kdb_initbptab
  - kernel/trace/trace_kdb.c:kdb_ftrace_register
```
**Symbols:**

```
ffffffff81145a50-ffffffff81145c1d: kdb_register_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int kdb_register_flags(char *cmd, kdb_func_t func, char *usage, char *help, short int minlen, kdb_cmdflags_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_main.c (ffffffff811477e0)
Location: kernel/debug/kdb/kdb_main.c:2694
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_register
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd2
  - kernel/debug/kdb/kdb_bp.c:kdb_initbptab
  - kernel/debug/kdb/kdb_bp.c:kdb_initbptab
  - kernel/debug/kdb/kdb_bp.c:kdb_initbptab
  - kernel/debug/kdb/kdb_bp.c:kdb_initbptab
  - kernel/debug/kdb/kdb_bp.c:kdb_initbptab
  - kernel/debug/kdb/kdb_bp.c:kdb_initbptab
  - kernel/debug/kdb/kdb_bp.c:kdb_initbptab
  - kernel/trace/trace_kdb.c:kdb_ftrace_register
```
**Symbols:**

```
ffffffff811477e0-ffffffff811479b0: kdb_register_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int kdb_register_flags(char *cmd, kdb_func_t func, char *usage, char *help, short int minlen, kdb_cmdflags_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_main.c (ffffffff81154090)
Location: kernel/debug/kdb/kdb_main.c:2694
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_register
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd2
  - kernel/debug/kdb/kdb_bp.c:kdb_initbptab
  - kernel/debug/kdb/kdb_bp.c:kdb_initbptab
  - kernel/debug/kdb/kdb_bp.c:kdb_initbptab
  - kernel/debug/kdb/kdb_bp.c:kdb_initbptab
  - kernel/debug/kdb/kdb_bp.c:kdb_initbptab
  - kernel/debug/kdb/kdb_bp.c:kdb_initbptab
  - kernel/debug/kdb/kdb_bp.c:kdb_initbptab
  - kernel/trace/trace_kdb.c:kdb_ftrace_register
```
**Symbols:**

```
ffffffff81154090-ffffffff81154260: kdb_register_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int kdb_register_flags(char *cmd, kdb_func_t func, char *usage, char *help, short int minlen, kdb_cmdflags_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_main.c (ffffffff81163900)
Location: kernel/debug/kdb/kdb_main.c:2679
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_register
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd2
  - kernel/debug/kdb/kdb_bp.c:kdb_initbptab
  - kernel/debug/kdb/kdb_bp.c:kdb_initbptab
  - kernel/debug/kdb/kdb_bp.c:kdb_initbptab
  - kernel/debug/kdb/kdb_bp.c:kdb_initbptab
  - kernel/debug/kdb/kdb_bp.c:kdb_initbptab
  - kernel/debug/kdb/kdb_bp.c:kdb_initbptab
  - kernel/debug/kdb/kdb_bp.c:kdb_initbptab
  - kernel/trace/trace_kdb.c:kdb_ftrace_register
```
**Symbols:**

```
ffffffff81163900-ffffffff81163b03: kdb_register_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int kdb_register_flags(char *cmd, kdb_func_t func, char *usage, char *help, short int minlen, kdb_cmdflags_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_main.c (ffffffff8116fb20)
Location: kernel/debug/kdb/kdb_main.c:2659
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_register
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd2
  - kernel/debug/kdb/kdb_bp.c:kdb_initbptab
  - kernel/debug/kdb/kdb_bp.c:kdb_initbptab
  - kernel/debug/kdb/kdb_bp.c:kdb_initbptab
  - kernel/debug/kdb/kdb_bp.c:kdb_initbptab
  - kernel/debug/kdb/kdb_bp.c:kdb_initbptab
  - kernel/debug/kdb/kdb_bp.c:kdb_initbptab
  - kernel/debug/kdb/kdb_bp.c:kdb_initbptab
  - kernel/trace/trace_kdb.c:kdb_ftrace_register
```
**Symbols:**

```
ffffffff8116fb20-ffffffff8116fcf2: kdb_register_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int kdb_register_flags(char *cmd, kdb_func_t func, char *usage, char *help, short int minlen, kdb_cmdflags_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_main.c (ffffffff8117c8d0)
Location: kernel/debug/kdb/kdb_main.c:2658
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_register
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd2
  - kernel/debug/kdb/kdb_bp.c:kdb_initbptab
  - kernel/debug/kdb/kdb_bp.c:kdb_initbptab
  - kernel/debug/kdb/kdb_bp.c:kdb_initbptab
  - kernel/debug/kdb/kdb_bp.c:kdb_initbptab
  - kernel/debug/kdb/kdb_bp.c:kdb_initbptab
  - kernel/debug/kdb/kdb_bp.c:kdb_initbptab
  - kernel/debug/kdb/kdb_bp.c:kdb_initbptab
  - kernel/trace/trace_kdb.c:kdb_ftrace_register
```
**Symbols:**

```
ffffffff8117c8d0-ffffffff8117caab: kdb_register_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int kdb_register_flags(char *cmd, kdb_func_t func, char *usage, char *help, short int minlen, kdb_cmdflags_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_main.c (ffffffff81188750)
Location: kernel/debug/kdb/kdb_main.c:2658
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_register
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd2
  - kernel/debug/kdb/kdb_bp.c:kdb_initbptab
  - kernel/debug/kdb/kdb_bp.c:kdb_initbptab
  - kernel/debug/kdb/kdb_bp.c:kdb_initbptab
  - kernel/debug/kdb/kdb_bp.c:kdb_initbptab
  - kernel/debug/kdb/kdb_bp.c:kdb_initbptab
  - kernel/debug/kdb/kdb_bp.c:kdb_initbptab
  - kernel/debug/kdb/kdb_bp.c:kdb_initbptab
  - kernel/trace/trace_kdb.c:kdb_ftrace_register
```
**Symbols:**

```
ffffffff81188750-ffffffff8118892b: kdb_register_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int kdb_register_flags(char *cmd, kdb_func_t func, char *usage, char *help, short int minlen, kdb_cmdflags_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_main.c (ffffffff8119deb0)
Location: kernel/debug/kdb/kdb_main.c:2663
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_register
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd2
  - kernel/debug/kdb/kdb_bp.c:kdb_initbptab
  - kernel/debug/kdb/kdb_bp.c:kdb_initbptab
  - kernel/debug/kdb/kdb_bp.c:kdb_initbptab
  - kernel/debug/kdb/kdb_bp.c:kdb_initbptab
  - kernel/debug/kdb/kdb_bp.c:kdb_initbptab
  - kernel/debug/kdb/kdb_bp.c:kdb_initbptab
  - kernel/debug/kdb/kdb_bp.c:kdb_initbptab
  - kernel/trace/trace_kdb.c:kdb_ftrace_register
```
**Symbols:**

```
ffffffff8119deb0-ffffffff8119e0a0: kdb_register_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int kdb_register_flags(char *cmd, kdb_func_t func, char *usage, char *help, short int minlen, kdb_cmdflags_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_main.c (ffffffff8119aef0)
Location: kernel/debug/kdb/kdb_main.c:2663
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_register
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd2
  - kernel/debug/kdb/kdb_bp.c:kdb_initbptab
  - kernel/debug/kdb/kdb_bp.c:kdb_initbptab
  - kernel/debug/kdb/kdb_bp.c:kdb_initbptab
  - kernel/debug/kdb/kdb_bp.c:kdb_initbptab
  - kernel/debug/kdb/kdb_bp.c:kdb_initbptab
  - kernel/debug/kdb/kdb_bp.c:kdb_initbptab
  - kernel/debug/kdb/kdb_bp.c:kdb_initbptab
  - kernel/trace/trace_kdb.c:kdb_ftrace_register
```
**Symbols:**

```
ffffffff8119aef0-ffffffff8119b0cb: kdb_register_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int kdb_register_flags(char *cmd, kdb_func_t func, char *usage, char *help, short int minlen, kdb_cmdflags_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_main.c (ffffffff8119be80)
Location: kernel/debug/kdb/kdb_main.c:2635
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_register
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd2
  - kernel/trace/trace_kdb.c:kdb_ftrace_register
```
**Symbols:**

```
ffffffff8119be80-ffffffff8119bfb0: kdb_register_flags (STB_GLOBAL)
```
</details>
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
int kdb_register_flags(char *cmd, kdb_func_t func, char *usage, char *help, short int minlen, kdb_cmdflags_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_main.c (ffff800010200400)
Location: kernel/debug/kdb/kdb_main.c:2658
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_register
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd2
  - kernel/debug/kdb/kdb_bp.c:kdb_initbptab
  - kernel/debug/kdb/kdb_bp.c:kdb_initbptab
  - kernel/debug/kdb/kdb_bp.c:kdb_initbptab
  - kernel/debug/kdb/kdb_bp.c:kdb_initbptab
  - kernel/debug/kdb/kdb_bp.c:kdb_initbptab
  - kernel/debug/kdb/kdb_bp.c:kdb_initbptab
  - kernel/debug/kdb/kdb_bp.c:kdb_initbptab
  - kernel/trace/trace_kdb.c:kdb_ftrace_register
```
**Symbols:**

```
ffff800010200400-ffff800010200604: kdb_register_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int kdb_register_flags(char *cmd, kdb_func_t func, char *usage, char *help, short int minlen, kdb_cmdflags_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_main.c (c043e8d0)
Location: kernel/debug/kdb/kdb_main.c:2658
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_register
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd2
  - kernel/debug/kdb/kdb_bp.c:kdb_initbptab
  - kernel/debug/kdb/kdb_bp.c:kdb_initbptab
  - kernel/debug/kdb/kdb_bp.c:kdb_initbptab
  - kernel/debug/kdb/kdb_bp.c:kdb_initbptab
  - kernel/debug/kdb/kdb_bp.c:kdb_initbptab
  - kernel/debug/kdb/kdb_bp.c:kdb_initbptab
  - kernel/debug/kdb/kdb_bp.c:kdb_initbptab
  - kernel/trace/trace_kdb.c:kdb_ftrace_register
```
**Symbols:**

```
c043e8d0-c043eabc: kdb_register_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int kdb_register_flags(char *cmd, kdb_func_t func, char *usage, char *help, short int minlen, kdb_cmdflags_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_main.c (c000000000277c10)
Location: kernel/debug/kdb/kdb_main.c:2658
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_register
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd2
  - kernel/debug/kdb/kdb_bp.c:kdb_initbptab
  - kernel/debug/kdb/kdb_bp.c:kdb_initbptab
  - kernel/debug/kdb/kdb_bp.c:kdb_initbptab
  - kernel/debug/kdb/kdb_bp.c:kdb_initbptab
  - kernel/debug/kdb/kdb_bp.c:kdb_initbptab
  - kernel/debug/kdb/kdb_bp.c:kdb_initbptab
  - kernel/debug/kdb/kdb_bp.c:kdb_initbptab
  - kernel/trace/trace_kdb.c:kdb_ftrace_register
```
**Symbols:**

```
c000000000277c10-c0000000002780b0: kdb_register_flags (STB_GLOBAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
int kdb_register_flags(char *cmd, kdb_func_t func, char *usage, char *help, short int minlen, kdb_cmdflags_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_main.c (ffffffff81180d70)
Location: kernel/debug/kdb/kdb_main.c:2658
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_register
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd2
  - kernel/debug/kdb/kdb_bp.c:kdb_initbptab
  - kernel/debug/kdb/kdb_bp.c:kdb_initbptab
  - kernel/debug/kdb/kdb_bp.c:kdb_initbptab
  - kernel/debug/kdb/kdb_bp.c:kdb_initbptab
  - kernel/debug/kdb/kdb_bp.c:kdb_initbptab
  - kernel/debug/kdb/kdb_bp.c:kdb_initbptab
  - kernel/debug/kdb/kdb_bp.c:kdb_initbptab
  - kernel/trace/trace_kdb.c:kdb_ftrace_register
```
**Symbols:**

```
ffffffff81180d70-ffffffff81180f4b: kdb_register_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int kdb_register_flags(char *cmd, kdb_func_t func, char *usage, char *help, short int minlen, kdb_cmdflags_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_main.c (ffffffff81173eb0)
Location: kernel/debug/kdb/kdb_main.c:2658
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_register
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd2
  - kernel/debug/kdb/kdb_bp.c:kdb_initbptab
  - kernel/debug/kdb/kdb_bp.c:kdb_initbptab
  - kernel/debug/kdb/kdb_bp.c:kdb_initbptab
  - kernel/debug/kdb/kdb_bp.c:kdb_initbptab
  - kernel/debug/kdb/kdb_bp.c:kdb_initbptab
  - kernel/debug/kdb/kdb_bp.c:kdb_initbptab
  - kernel/debug/kdb/kdb_bp.c:kdb_initbptab
  - kernel/trace/trace_kdb.c:kdb_ftrace_register
```
**Symbols:**

```
ffffffff81173eb0-ffffffff8117408b: kdb_register_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int kdb_register_flags(char *cmd, kdb_func_t func, char *usage, char *help, short int minlen, kdb_cmdflags_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_main.c (ffffffff8117eb40)
Location: kernel/debug/kdb/kdb_main.c:2658
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_register
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd2
  - kernel/debug/kdb/kdb_bp.c:kdb_initbptab
  - kernel/debug/kdb/kdb_bp.c:kdb_initbptab
  - kernel/debug/kdb/kdb_bp.c:kdb_initbptab
  - kernel/debug/kdb/kdb_bp.c:kdb_initbptab
  - kernel/debug/kdb/kdb_bp.c:kdb_initbptab
  - kernel/debug/kdb/kdb_bp.c:kdb_initbptab
  - kernel/debug/kdb/kdb_bp.c:kdb_initbptab
  - kernel/trace/trace_kdb.c:kdb_ftrace_register
```
**Symbols:**

```
ffffffff8117eb40-ffffffff8117ed1b: kdb_register_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int kdb_register_flags(char *cmd, kdb_func_t func, char *usage, char *help, short int minlen, kdb_cmdflags_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_main.c (ffffffff8118c460)
Location: kernel/debug/kdb/kdb_main.c:2658
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_inittab
  - kernel/debug/kdb/kdb_main.c:kdb_register
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd2
  - kernel/debug/kdb/kdb_bp.c:kdb_initbptab
  - kernel/debug/kdb/kdb_bp.c:kdb_initbptab
  - kernel/debug/kdb/kdb_bp.c:kdb_initbptab
  - kernel/debug/kdb/kdb_bp.c:kdb_initbptab
  - kernel/debug/kdb/kdb_bp.c:kdb_initbptab
  - kernel/debug/kdb/kdb_bp.c:kdb_initbptab
  - kernel/debug/kdb/kdb_bp.c:kdb_initbptab
  - kernel/trace/trace_kdb.c:kdb_ftrace_register
```
**Symbols:**

```
ffffffff8118c460-ffffffff8118c63b: kdb_register_flags (STB_GLOBAL)
```
</details>
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
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
