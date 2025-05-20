# Function: <code>next_arg</code>

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
In kernel/params.c (ffffffff8109fa83)
Location: kernel/params.c:165
Inline: True
Inline callers:
  - kernel/params.c:parse_args
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
In kernel/params.c (ffffffff810a3131)
Location: kernel/params.c:165
Inline: True
Inline callers:
  - kernel/params.c:parse_args
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
In kernel/params.c (ffffffff810a81f1)
Location: kernel/params.c:165
Inline: True
Inline callers:
  - kernel/params.c:parse_args
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
char *next_arg(char *args, char **param, char **val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cmdline.c (ffffffff818eba60)
Location: lib/cmdline.c:199
Inline: False
Direct callers:
  - kernel/params.c:parse_args
```
**Symbols:**

```
ffffffff818eba60-ffffffff818ebb67: next_arg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
char *next_arg(char *args, char **param, char **val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cmdline.c (ffffffff81971a20)
Location: lib/cmdline.c:199
Inline: False
Direct callers:
  - kernel/params.c:parse_args
```
**Symbols:**

```
ffffffff81971a20-ffffffff81971b27: next_arg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
char *next_arg(char *args, char **param, char **val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cmdline.c (ffffffff819cddf0)
Location: lib/cmdline.c:199
Inline: False
Direct callers:
  - kernel/params.c:parse_args
```
**Symbols:**

```
ffffffff819cddf0-ffffffff819cdef5: next_arg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
char *next_arg(char *args, char **param, char **val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cmdline.c (ffffffff81a072b0)
Location: lib/cmdline.c:199
Inline: False
Direct callers:
  - kernel/params.c:parse_args
```
**Symbols:**

```
ffffffff81a072b0-ffffffff81a073b5: next_arg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
char *next_arg(char *args, char **param, char **val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cmdline.c (ffffffff81a76c20)
Location: lib/cmdline.c:201
Inline: False
Direct callers:
  - kernel/params.c:parse_args
```
**Symbols:**

```
ffffffff81a76c20-ffffffff81a76d27: next_arg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
char *next_arg(char *args, char **param, char **val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cmdline.c (ffffffff81aae030)
Location: lib/cmdline.c:201
Inline: False
Direct callers:
  - kernel/params.c:parse_args
```
**Symbols:**

```
ffffffff81aae030-ffffffff81aae137: next_arg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
char *next_arg(char *args, char **param, char **val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cmdline.c (ffffffff815e7cf0)
Location: lib/cmdline.c:201
Inline: False
Direct callers:
  - kernel/params.c:parse_args
```
**Symbols:**

```
ffffffff815e7cf0-ffffffff815e7df4: next_arg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
char *next_arg(char *args, char **param, char **val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cmdline.c (ffffffff8160ce50)
Location: lib/cmdline.c:214
Inline: False
Direct callers:
  - kernel/params.c:parse_args
```
**Symbols:**

```
ffffffff8160ce50-ffffffff8160cf54: next_arg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
char *next_arg(char *args, char **param, char **val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cmdline.c (ffffffff815f04c0)
Location: lib/cmdline.c:227
Inline: False
Direct callers:
  - kernel/params.c:parse_args
```
**Symbols:**

```
ffffffff815f04c0-ffffffff815f05ba: next_arg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
char *next_arg(char *args, char **param, char **val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cmdline.c (ffffffff8165d5a0)
Location: lib/cmdline.c:227
Inline: False
Direct callers:
  - kernel/params.c:parse_args
```
**Symbols:**

```
ffffffff8165d5a0-ffffffff8165d69a: next_arg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
char *next_arg(char *args, char **param, char **val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cmdline.c (ffffffff81776a90)
Location: lib/cmdline.c:227
Inline: False
Direct callers:
  - kernel/params.c:parse_args
```
**Symbols:**

```
ffffffff81776a90-ffffffff81776bba: next_arg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
char *next_arg(char *args, char **param, char **val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cmdline.c (ffffffff8201f530)
Location: lib/cmdline.c:227
Inline: False
Direct callers:
  - kernel/params.c:parse_args
```
**Symbols:**

```
ffffffff8201f530-ffffffff8201f65b: next_arg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
char *next_arg(char *args, char **param, char **val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cmdline.c (ffffffff8209f540)
Location: lib/cmdline.c:227
Inline: False
Direct callers:
  - kernel/params.c:parse_args
```
**Symbols:**

```
ffffffff8209f540-ffffffff8209f66b: next_arg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
char *next_arg(char *args, char **param, char **val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cmdline.c (ffffffff82177540)
Location: lib/cmdline.c:227
Inline: False
Direct callers:
  - kernel/params.c:parse_args
```
**Symbols:**

```
ffffffff82177540-ffffffff8217766b: next_arg (STB_GLOBAL)
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
char *next_arg(char *args, char **param, char **val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cmdline.c (ffff800010d84320)
Location: lib/cmdline.c:201
Inline: False
Direct callers:
  - kernel/params.c:parse_args
```
**Symbols:**

```
ffff800010d84320-ffff800010d84480: next_arg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
char *next_arg(char *args, char **param, char **val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cmdline.c (c0e7f830)
Location: lib/cmdline.c:201
Inline: False
Direct callers:
  - kernel/params.c:parse_args
```
**Symbols:**

```
c0e7f830-c0e7f9b0: next_arg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
char *next_arg(char *args, char **param, char **val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cmdline.c (c000000000ec3480)
Location: lib/cmdline.c:201
Inline: False
Direct callers:
  - kernel/params.c:parse_args
```
**Symbols:**

```
c000000000ec3480-c000000000ec3624: next_arg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
char *next_arg(char *args, char **param, char **val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cmdline.c (ffffffe0008ae8bc)
Location: lib/cmdline.c:201
Inline: False
Direct callers:
  - kernel/params.c:parse_args
```
**Symbols:**

```
ffffffe0008ae8bc-ffffffe0008ae9ca: next_arg (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
char *next_arg(char *args, char **param, char **val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cmdline.c (ffffffff81a4ce80)
Location: lib/cmdline.c:201
Inline: False
Direct callers:
  - kernel/params.c:parse_args
```
**Symbols:**

```
ffffffff81a4ce80-ffffffff81a4cf87: next_arg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
char *next_arg(char *args, char **param, char **val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cmdline.c (ffffffff81a09fb0)
Location: lib/cmdline.c:201
Inline: False
Direct callers:
  - kernel/params.c:parse_args
```
**Symbols:**

```
ffffffff81a09fb0-ffffffff81a0a0b7: next_arg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
char *next_arg(char *args, char **param, char **val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cmdline.c (ffffffff81ab9270)
Location: lib/cmdline.c:201
Inline: False
Direct callers:
  - kernel/params.c:parse_args
```
**Symbols:**

```
ffffffff81ab9270-ffffffff81ab9377: next_arg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
char *next_arg(char *args, char **param, char **val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cmdline.c (ffffffff81ac56c0)
Location: lib/cmdline.c:201
Inline: False
Direct callers:
  - kernel/params.c:parse_args
```
**Symbols:**

```
ffffffff81ac56c0-ffffffff81ac57c7: next_arg (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
