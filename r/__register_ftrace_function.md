# Function: <code>__register_ftrace_function</code>

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
In kernel/trace/ftrace.c (ffffffff81144f1b)
Location: kernel/trace/ftrace.c:408
Inline: True
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
In kernel/trace/ftrace.c (ffffffff8114d83b)
Location: kernel/trace/ftrace.c:387
Inline: True
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
In kernel/trace/ftrace.c (ffffffff8115777b)
Location: kernel/trace/ftrace.c:387
Inline: True
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
In kernel/trace/ftrace.c (ffffffff8115aa0b)
Location: kernel/trace/ftrace.c:400
Inline: True
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
In kernel/trace/ftrace.c (ffffffff81167b7b)
Location: kernel/trace/ftrace.c:376
Inline: True
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
In kernel/trace/ftrace.c (ffffffff81176872)
Location: kernel/trace/ftrace.c:365
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __register_ftrace_function(struct ftrace_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811844a0)
Location: kernel/trace/ftrace.c:310
Inline: False
```
**Symbols:**

```
ffffffff811844a0-ffffffff8118452b: __register_ftrace_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int __register_ftrace_function(struct ftrace_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (0)
Location: kernel/trace/ftrace.c:307
Inline: False
```
**Symbols:**

```
ffffffff811923b3-ffffffff811923cb: __register_ftrace_function.cold (STB_LOCAL)
ffffffff81191240-ffffffff811912d5: __register_ftrace_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __register_ftrace_function(struct ftrace_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8119d260)
Location: kernel/trace/ftrace.c:308
Inline: False
```
**Symbols:**

```
ffffffff8119d260-ffffffff8119d2f9: __register_ftrace_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __register_ftrace_function(struct ftrace_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811b31c0)
Location: kernel/trace/ftrace.c:302
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:register_ftrace_function
  - kernel/trace/ftrace.c:register_ftrace_function_probe
```
**Symbols:**

```
ffffffff811b31c0-ffffffff811b328c: __register_ftrace_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __register_ftrace_function(struct ftrace_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811b0dd0)
Location: kernel/trace/ftrace.c:302
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:register_ftrace_function
  - kernel/trace/ftrace.c:register_ftrace_function_probe
```
**Symbols:**

```
ffffffff811b0dd0-ffffffff811b0e9c: __register_ftrace_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __register_ftrace_function(struct ftrace_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811b1820)
Location: kernel/trace/ftrace.c:302
Inline: False
```
**Symbols:**

```
ffffffff811b1820-ffffffff811b18ec: __register_ftrace_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __register_ftrace_function(struct ftrace_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811db6c0)
Location: kernel/trace/ftrace.c:302
Inline: False
```
**Symbols:**

```
ffffffff811db6c0-ffffffff811db78c: __register_ftrace_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __register_ftrace_function(struct ftrace_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81211750)
Location: kernel/trace/ftrace.c:299
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_startup
```
**Symbols:**

```
ffffffff81211750-ffffffff81211848: __register_ftrace_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __register_ftrace_function(struct ftrace_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8125ad00)
Location: kernel/trace/ftrace.c:299
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_startup
```
**Symbols:**

```
ffffffff8125ad00-ffffffff8125adf8: __register_ftrace_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __register_ftrace_function(struct ftrace_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff812721a0)
Location: kernel/trace/ftrace.c:330
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_startup
```
**Symbols:**

```
ffffffff812721a0-ffffffff81272298: __register_ftrace_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __register_ftrace_function(struct ftrace_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8128c690)
Location: kernel/trace/ftrace.c:330
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_startup
```
**Symbols:**

```
ffffffff8128c690-ffffffff8128c788: __register_ftrace_function (STB_GLOBAL)
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
int __register_ftrace_function(struct ftrace_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffff800010216108)
Location: kernel/trace/ftrace.c:308
Inline: False
```
**Symbols:**

```
ffff800010216108-ffff8000102161e4: __register_ftrace_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __register_ftrace_function(struct ftrace_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (c0454ebc)
Location: kernel/trace/ftrace.c:308
Inline: False
```
**Symbols:**

```
c0454ebc-c0454f90: __register_ftrace_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __register_ftrace_function(struct ftrace_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (c000000000297e40)
Location: kernel/trace/ftrace.c:308
Inline: False
```
**Symbols:**

```
c000000000297e40-c000000000297f50: __register_ftrace_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __register_ftrace_function(struct ftrace_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffe000175d38)
Location: kernel/trace/ftrace.c:308
Inline: False
```
**Symbols:**

```
ffffffe000175d38-ffffffe000175ddc: __register_ftrace_function (STB_GLOBAL)
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
int __register_ftrace_function(struct ftrace_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81195880)
Location: kernel/trace/ftrace.c:308
Inline: False
```
**Symbols:**

```
ffffffff81195880-ffffffff81195919: __register_ftrace_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __register_ftrace_function(struct ftrace_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81188990)
Location: kernel/trace/ftrace.c:308
Inline: False
```
**Symbols:**

```
ffffffff81188990-ffffffff81188a29: __register_ftrace_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __register_ftrace_function(struct ftrace_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81193650)
Location: kernel/trace/ftrace.c:308
Inline: False
```
**Symbols:**

```
ffffffff81193650-ffffffff811936e9: __register_ftrace_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __register_ftrace_function(struct ftrace_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811a1220)
Location: kernel/trace/ftrace.c:308
Inline: False
```
**Symbols:**

```
ffffffff811a1220-ffffffff811a12b9: __register_ftrace_function (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
