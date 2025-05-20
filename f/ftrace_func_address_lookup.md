# Function: <code>ftrace_func_address_lookup</code>

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
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811676a1)
Location: kernel/trace/ftrace.c:5936
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_mod_address_lookup
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
In kernel/trace/ftrace.c (ffffffff811763a4)
Location: kernel/trace/ftrace.c:5922
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_mod_address_lookup
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
In kernel/trace/ftrace.c (ffffffff81183fe4)
Location: kernel/trace/ftrace.c:5882
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_mod_address_lookup
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
In kernel/trace/ftrace.c (ffffffff81190d84)
Location: kernel/trace/ftrace.c:5930
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_mod_address_lookup
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
In kernel/trace/ftrace.c (ffffffff8119cd84)
Location: kernel/trace/ftrace.c:5967
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_mod_address_lookup
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811b2d91)
Location: kernel/trace/ftrace.c:6460
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_mod_address_lookup
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811b0801)
Location: kernel/trace/ftrace.c:6598
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_mod_address_lookup
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811b11a1)
Location: kernel/trace/ftrace.c:6603
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_mod_address_lookup
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811db031)
Location: kernel/trace/ftrace.c:6604
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_mod_address_lookup
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81211018)
Location: kernel/trace/ftrace.c:7038
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_mod_address_lookup
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
const char *ftrace_func_address_lookup(struct ftrace_mod_map *mod_map, long unsigned int addr, long unsigned int *size, long unsigned int *off, char *sym);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81251f40)
Location: kernel/trace/ftrace.c:7154
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_mod_address_lookup
```
**Symbols:**

```
ffffffff81251f40-ffffffff81251fe3: ftrace_func_address_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
const char *ftrace_func_address_lookup(struct ftrace_mod_map *mod_map, long unsigned int addr, long unsigned int *size, long unsigned int *off, char *sym);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81269290)
Location: kernel/trace/ftrace.c:6969
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_mod_address_lookup
```
**Symbols:**

```
ffffffff81269290-ffffffff81269333: ftrace_func_address_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
const char *ftrace_func_address_lookup(struct ftrace_mod_map *mod_map, long unsigned int addr, long unsigned int *size, long unsigned int *off, char *sym);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff812833f0)
Location: kernel/trace/ftrace.c:6971
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_mod_address_lookup
```
**Symbols:**

```
ffffffff812833f0-ffffffff81283493: ftrace_func_address_lookup (STB_LOCAL)
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
In kernel/trace/ftrace.c (ffff800010215bb0)
Location: kernel/trace/ftrace.c:5967
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_mod_address_lookup
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
In kernel/trace/ftrace.c (c045495c)
Location: kernel/trace/ftrace.c:5967
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_mod_address_lookup
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
In kernel/trace/ftrace.c (c0000000002976c0)
Location: kernel/trace/ftrace.c:5967
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_mod_address_lookup
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffe000175872)
Location: kernel/trace/ftrace.c:5967
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_mod_address_lookup
```
</details>
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
In kernel/trace/ftrace.c (ffffffff811953a4)
Location: kernel/trace/ftrace.c:5967
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_mod_address_lookup
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
In kernel/trace/ftrace.c (ffffffff811884b4)
Location: kernel/trace/ftrace.c:5967
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_mod_address_lookup
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
In kernel/trace/ftrace.c (ffffffff81193174)
Location: kernel/trace/ftrace.c:5967
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_mod_address_lookup
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
In kernel/trace/ftrace.c (ffffffff811a0d0b)
Location: kernel/trace/ftrace.c:5967
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_mod_address_lookup
```
</details>
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
