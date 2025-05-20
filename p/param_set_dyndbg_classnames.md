# Function: <code>param_set_dyndbg_classnames</code>

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
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int param_set_dyndbg_classnames(const char *instr, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/dynamic_debug.c (0)
Location: lib/dynamic_debug.c:633
Inline: False
Direct callers:
  - lib/dynamic_debug.c:param_set_dyndbg_classes
```
**Symbols:**

```
ffffffff8188eb20-ffffffff8188ee06: param_set_dyndbg_classnames (STB_LOCAL)
ffffffff8208ce26-ffffffff8208ce96: param_set_dyndbg_classnames.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int param_set_dyndbg_classnames(const char *instr, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/dynamic_debug.c (0)
Location: lib/dynamic_debug.c:633
Inline: False
Direct callers:
  - lib/dynamic_debug.c:param_set_dyndbg_classes
```
**Symbols:**

```
ffffffff818d1080-ffffffff818d135f: param_set_dyndbg_classnames (STB_LOCAL)
ffffffff8210d1e1-ffffffff8210d251: param_set_dyndbg_classnames.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int param_set_dyndbg_classnames(const char *instr, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/dynamic_debug.c (0)
Location: lib/dynamic_debug.c:634
Inline: False
Direct callers:
  - lib/dynamic_debug.c:param_set_dyndbg_classes
```
**Symbols:**

```
ffffffff81923070-ffffffff8192334f: param_set_dyndbg_classnames (STB_LOCAL)
ffffffff821eb34e-ffffffff821eb3be: param_set_dyndbg_classnames.cold (STB_LOCAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
