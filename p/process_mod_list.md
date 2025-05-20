# Function: <code>process_mod_list</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void process_mod_list(struct list_head *head, struct ftrace_ops *ops, char *mod, bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81159860)
Location: kernel/trace/ftrace.c:4000
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_module_enable
```
**Symbols:**

```
ffffffff81159860-ffffffff81159aa3: process_mod_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void process_mod_list(struct list_head *head, struct ftrace_ops *ops, char *mod, bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81166360)
Location: kernel/trace/ftrace.c:3968
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_module_enable
```
**Symbols:**

```
ffffffff81166360-ffffffff811665a3: process_mod_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void process_mod_list(struct list_head *head, struct ftrace_ops *ops, char *mod, bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81175080)
Location: kernel/trace/ftrace.c:3956
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_module_enable
```
**Symbols:**

```
ffffffff81175080-ffffffff811752ba: process_mod_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void process_mod_list(struct list_head *head, struct ftrace_ops *ops, char *mod, bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81182cc0)
Location: kernel/trace/ftrace.c:3915
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_module_enable
```
**Symbols:**

```
ffffffff81182cc0-ffffffff81182efa: process_mod_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void process_mod_list(struct list_head *head, struct ftrace_ops *ops, char *mod, bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8118fa30)
Location: kernel/trace/ftrace.c:3951
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_module_enable
```
**Symbols:**

```
ffffffff8118fa30-ffffffff8118fc7a: process_mod_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void process_mod_list(struct list_head *head, struct ftrace_ops *ops, char *mod, bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8119ba00)
Location: kernel/trace/ftrace.c:3975
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_module_enable
```
**Symbols:**

```
ffffffff8119ba00-ffffffff8119bc4a: process_mod_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void process_mod_list(struct list_head *head, struct ftrace_ops *ops, char *mod, bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811b1b60)
Location: kernel/trace/ftrace.c:4102
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:process_cached_mods
  - kernel/trace/ftrace.c:process_cached_mods
```
**Symbols:**

```
ffffffff811b1b60-ffffffff811b1ddf: process_mod_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void process_mod_list(struct list_head *head, struct ftrace_ops *ops, char *mod, bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811af5d0)
Location: kernel/trace/ftrace.c:4180
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:process_cached_mods
  - kernel/trace/ftrace.c:process_cached_mods
```
**Symbols:**

```
ffffffff811af5d0-ffffffff811af84f: process_mod_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void process_mod_list(struct list_head *head, struct ftrace_ops *ops, char *mod, bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811afe30)
Location: kernel/trace/ftrace.c:4180
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_module_enable
```
**Symbols:**

```
ffffffff811afe30-ffffffff811b00ae: process_mod_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void process_mod_list(struct list_head *head, struct ftrace_ops *ops, char *mod, bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811d9cc0)
Location: kernel/trace/ftrace.c:4181
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_module_enable
```
**Symbols:**

```
ffffffff811d9cc0-ffffffff811d9f2a: process_mod_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void process_mod_list(struct list_head *head, struct ftrace_ops *ops, char *mod, bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8120f590)
Location: kernel/trace/ftrace.c:4321
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_module_enable
```
**Symbols:**

```
ffffffff8120f590-ffffffff8120f80d: process_mod_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void process_mod_list(struct list_head *head, struct ftrace_ops *ops, char *mod, bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff812588e0)
Location: kernel/trace/ftrace.c:4342
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_module_enable
```
**Symbols:**

```
ffffffff812588e0-ffffffff81258b5b: process_mod_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void process_mod_list(struct list_head *head, struct ftrace_ops *ops, char *mod, bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8126fcb0)
Location: kernel/trace/ftrace.c:4497
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_module_enable
```
**Symbols:**

```
ffffffff8126fcb0-ffffffff8126ff2b: process_mod_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void process_mod_list(struct list_head *head, struct ftrace_ops *ops, char *mod, bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8128a160)
Location: kernel/trace/ftrace.c:4463
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_module_enable
```
**Symbols:**

```
ffffffff8128a160-ffffffff8128a3db: process_mod_list (STB_LOCAL)
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
void process_mod_list(struct list_head *head, struct ftrace_ops *ops, char *mod, bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffff800010214850)
Location: kernel/trace/ftrace.c:3975
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_module_enable
```
**Symbols:**

```
ffff800010214850-ffff800010214aa8: process_mod_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void process_mod_list(struct list_head *head, struct ftrace_ops *ops, char *mod, bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (c04535c4)
Location: kernel/trace/ftrace.c:3975
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_module_enable
```
**Symbols:**

```
c04535c4-c04537f8: process_mod_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void process_mod_list(struct list_head *head, struct ftrace_ops *ops, char *mod, bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (c000000000295950)
Location: kernel/trace/ftrace.c:3975
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_module_enable
```
**Symbols:**

```
c000000000295950-c000000000295df4: process_mod_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void process_mod_list(struct list_head *head, struct ftrace_ops *ops, char *mod, bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffe000174758)
Location: kernel/trace/ftrace.c:3975
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_module_enable
```
**Symbols:**

```
ffffffe000174758-ffffffe00017495e: process_mod_list (STB_LOCAL)
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
void process_mod_list(struct list_head *head, struct ftrace_ops *ops, char *mod, bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81194020)
Location: kernel/trace/ftrace.c:3975
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_module_enable
```
**Symbols:**

```
ffffffff81194020-ffffffff8119426a: process_mod_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void process_mod_list(struct list_head *head, struct ftrace_ops *ops, char *mod, bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81187130)
Location: kernel/trace/ftrace.c:3975
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_module_enable
```
**Symbols:**

```
ffffffff81187130-ffffffff8118737a: process_mod_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void process_mod_list(struct list_head *head, struct ftrace_ops *ops, char *mod, bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81191df0)
Location: kernel/trace/ftrace.c:3975
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_module_enable
```
**Symbols:**

```
ffffffff81191df0-ffffffff8119203a: process_mod_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void process_mod_list(struct list_head *head, struct ftrace_ops *ops, char *mod, bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8119f980)
Location: kernel/trace/ftrace.c:3975
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_module_enable
```
**Symbols:**

```
ffffffff8119f980-ffffffff8119fbca: process_mod_list (STB_LOCAL)
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
