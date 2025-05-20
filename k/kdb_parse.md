# Function: <code>kdb_parse</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int kdb_parse(const char *cmdstr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_main.c (ffffffff811363a0)
Location: kernel/debug/kdb/kdb_main.c:909
Inline: False
Direct callers:
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/kdb/kdb_main.c:kdb_exec_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
```
**Symbols:**

```
ffffffff811363a0-ffffffff81136a6e: kdb_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int kdb_parse(const char *cmdstr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_main.c (ffffffff8113e850)
Location: kernel/debug/kdb/kdb_main.c:909
Inline: False
Direct callers:
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_exec_defcmd
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
```
**Symbols:**

```
ffffffff8113e850-ffffffff8113eefe: kdb_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int kdb_parse(const char *cmdstr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_main.c (ffffffff81148620)
Location: kernel/debug/kdb/kdb_main.c:908
Inline: False
Direct callers:
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_exec_defcmd
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
```
**Symbols:**

```
ffffffff81148620-ffffffff81148cce: kdb_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int kdb_parse(const char *cmdstr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_main.c (ffffffff8114a3d0)
Location: kernel/debug/kdb/kdb_main.c:911
Inline: False
Direct callers:
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_exec_defcmd
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
```
**Symbols:**

```
ffffffff8114a3d0-ffffffff8114aadb: kdb_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int kdb_parse(const char *cmdstr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_main.c (ffffffff81156c50)
Location: kernel/debug/kdb/kdb_main.c:911
Inline: False
Direct callers:
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_exec_defcmd
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
```
**Symbols:**

```
ffffffff81156c50-ffffffff81157361: kdb_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int kdb_parse(const char *cmdstr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/debug/kdb/kdb_main.c (0)
Location: kernel/debug/kdb/kdb_main.c:911
Inline: False
Direct callers:
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_exec_defcmd
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
```
**Symbols:**

```
ffffffff81166efa-ffffffff81166f06: kdb_parse.cold.9 (STB_LOCAL)
ffffffff81165840-ffffffff81165f4e: kdb_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int kdb_parse(const char *cmdstr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/debug/kdb/kdb_main.c (0)
Location: kernel/debug/kdb/kdb_main.c:911
Inline: False
Direct callers:
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_exec_defcmd
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
```
**Symbols:**

```
ffffffff81173c5a-ffffffff81173c66: kdb_parse.cold.10 (STB_LOCAL)
ffffffff81172550-ffffffff81172c5d: kdb_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int kdb_parse(const char *cmdstr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/debug/kdb/kdb_main.c (0)
Location: kernel/debug/kdb/kdb_main.c:911
Inline: False
Direct callers:
  - kernel/debug/gdbstub.c:gdb_cmd_query
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_exec_defcmd
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
```
**Symbols:**

```
ffffffff81180a32-ffffffff81180a3e: kdb_parse.cold (STB_LOCAL)
ffffffff8117f310-ffffffff8117fa19: kdb_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int kdb_parse(const char *cmdstr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/debug/kdb/kdb_main.c (0)
Location: kernel/debug/kdb/kdb_main.c:911
Inline: False
Direct callers:
  - kernel/debug/gdbstub.c:gdb_cmd_query
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_exec_defcmd
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
```
**Symbols:**

```
ffffffff8118c8a2-ffffffff8118c8ae: kdb_parse.cold (STB_LOCAL)
ffffffff8118b190-ffffffff8118b887: kdb_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int kdb_parse(const char *cmdstr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_main.c (ffffffff8119fde0)
Location: kernel/debug/kdb/kdb_main.c:916
Inline: False
Direct callers:
  - kernel/debug/gdbstub.c:gdb_cmd_query
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_exec_defcmd
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
```
**Symbols:**

```
ffffffff8119fde0-ffffffff811a0361: kdb_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int kdb_parse(const char *cmdstr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_main.c (ffffffff8119cea0)
Location: kernel/debug/kdb/kdb_main.c:916
Inline: False
Direct callers:
  - kernel/debug/gdbstub.c:gdb_cmd_query
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_exec_defcmd
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
```
**Symbols:**

```
ffffffff8119cea0-ffffffff8119d425: kdb_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int kdb_parse(const char *cmdstr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_main.c (ffffffff8119db80)
Location: kernel/debug/kdb/kdb_main.c:909
Inline: False
Direct callers:
  - kernel/debug/gdbstub.c:gdb_cmd_query
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_exec_defcmd
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
```
**Symbols:**

```
ffffffff8119db80-ffffffff8119e09c: kdb_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int kdb_parse(const char *cmdstr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/debug/kdb/kdb_main.c (0)
Location: kernel/debug/kdb/kdb_main.c:915
Inline: False
Direct callers:
  - kernel/debug/gdbstub.c:gdb_cmd_query
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_exec_defcmd
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
```
**Symbols:**

```
ffffffff81cb3cf7-ffffffff81cb3d3b: kdb_parse.cold (STB_LOCAL)
ffffffff811c78e0-ffffffff811c7e25: kdb_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int kdb_parse(const char *cmdstr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/debug/kdb/kdb_main.c (0)
Location: kernel/debug/kdb/kdb_main.c:967
Inline: False
Direct callers:
  - kernel/debug/gdbstub.c:gdb_cmd_query
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_exec_defcmd
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
```
**Symbols:**

```
ffffffff81e64bb9-ffffffff81e64bf7: kdb_parse.cold (STB_LOCAL)
ffffffff811fb300-ffffffff811fb883: kdb_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int kdb_parse(const char *cmdstr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/debug/kdb/kdb_main.c (0)
Location: kernel/debug/kdb/kdb_main.c:967
Inline: False
Direct callers:
  - kernel/debug/gdbstub.c:gdb_cmd_query
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_exec_defcmd
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
```
**Symbols:**

```
ffffffff8205c885-ffffffff8205c8c3: kdb_parse.cold (STB_LOCAL)
ffffffff81242940-ffffffff81242ec3: kdb_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int kdb_parse(const char *cmdstr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/debug/kdb/kdb_main.c (0)
Location: kernel/debug/kdb/kdb_main.c:967
Inline: False
Direct callers:
  - kernel/debug/gdbstub.c:gdb_cmd_query
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_exec_defcmd
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
```
**Symbols:**

```
ffffffff820db1fb-ffffffff820db239: kdb_parse.cold (STB_LOCAL)
ffffffff812599b0-ffffffff81259f29: kdb_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int kdb_parse(const char *cmdstr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/debug/kdb/kdb_main.c (0)
Location: kernel/debug/kdb/kdb_main.c:966
Inline: False
Direct callers:
  - kernel/debug/gdbstub.c:gdb_cmd_query
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_exec_defcmd
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
```
**Symbols:**

```
ffffffff821b6f36-ffffffff821b6f74: kdb_parse.cold (STB_LOCAL)
ffffffff812738a0-ffffffff81273e19: kdb_parse (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int kdb_parse(const char *cmdstr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_main.c (ffff800010202480)
Location: kernel/debug/kdb/kdb_main.c:911
Inline: False
Direct callers:
  - kernel/debug/gdbstub.c:gdb_cmd_query
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_exec_defcmd
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
```
**Symbols:**

```
ffff800010202480-ffff800010202b58: kdb_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int kdb_parse(const char *cmdstr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_main.c (c0441490)
Location: kernel/debug/kdb/kdb_main.c:911
Inline: False
Direct callers:
  - kernel/debug/gdbstub.c:gdb_cmd_query
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_exec_defcmd
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
```
**Symbols:**

```
c0441490-c0441ba4: kdb_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int kdb_parse(const char *cmdstr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_main.c (c00000000027bf90)
Location: kernel/debug/kdb/kdb_main.c:911
Inline: False
Direct callers:
  - kernel/debug/gdbstub.c:gdb_cmd_query
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_exec_defcmd
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
```
**Symbols:**

```
c00000000027bf90-c00000000027cb7c: kdb_parse (STB_GLOBAL)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int kdb_parse(const char *cmdstr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/debug/kdb/kdb_main.c (0)
Location: kernel/debug/kdb/kdb_main.c:911
Inline: False
Direct callers:
  - kernel/debug/gdbstub.c:gdb_cmd_query
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_exec_defcmd
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
```
**Symbols:**

```
ffffffff81184ec2-ffffffff81184ece: kdb_parse.cold (STB_LOCAL)
ffffffff811837b0-ffffffff81183ea7: kdb_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int kdb_parse(const char *cmdstr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/debug/kdb/kdb_main.c (0)
Location: kernel/debug/kdb/kdb_main.c:911
Inline: False
Direct callers:
  - kernel/debug/gdbstub.c:gdb_cmd_query
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_exec_defcmd
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
```
**Symbols:**

```
ffffffff81178002-ffffffff8117800e: kdb_parse.cold (STB_LOCAL)
ffffffff811768f0-ffffffff81176fe7: kdb_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int kdb_parse(const char *cmdstr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/debug/kdb/kdb_main.c (0)
Location: kernel/debug/kdb/kdb_main.c:911
Inline: False
Direct callers:
  - kernel/debug/gdbstub.c:gdb_cmd_query
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_exec_defcmd
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
```
**Symbols:**

```
ffffffff81182c92-ffffffff81182c9e: kdb_parse.cold (STB_LOCAL)
ffffffff81181580-ffffffff81181c77: kdb_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int kdb_parse(const char *cmdstr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/debug/kdb/kdb_main.c (0)
Location: kernel/debug/kdb/kdb_main.c:911
Inline: False
Direct callers:
  - kernel/debug/gdbstub.c:gdb_cmd_query
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_exec_defcmd
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
```
**Symbols:**

```
ffffffff811905b2-ffffffff811905be: kdb_parse.cold (STB_LOCAL)
ffffffff8118eea0-ffffffff8118f597: kdb_parse (STB_GLOBAL)
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
