# Function: <code>clear_func_from_hashes</code>

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
In kernel/trace/ftrace.c (ffffffff811679fa)
Location: kernel/trace/ftrace.c:6060
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
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
In kernel/trace/ftrace.c (ffffffff8117663e)
Location: kernel/trace/ftrace.c:6046
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
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
In kernel/trace/ftrace.c (ffffffff81184283)
Location: kernel/trace/ftrace.c:6006
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
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
In kernel/trace/ftrace.c (ffffffff81191018)
Location: kernel/trace/ftrace.c:6054
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
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
In kernel/trace/ftrace.c (ffffffff8119d018)
Location: kernel/trace/ftrace.c:6087
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void clear_func_from_hashes(struct ftrace_init_func *func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811af3e0)
Location: kernel/trace/ftrace.c:6580
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
```
**Symbols:**

```
ffffffff811af3e0-ffffffff811af4a8: clear_func_from_hashes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void clear_func_from_hashes(struct ftrace_init_func *func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811acd90)
Location: kernel/trace/ftrace.c:6733
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
```
**Symbols:**

```
ffffffff811acd90-ffffffff811ace58: clear_func_from_hashes (STB_LOCAL)
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
In kernel/trace/ftrace.c (ffffffff811b153f)
Location: kernel/trace/ftrace.c:6738
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
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
In kernel/trace/ftrace.c (ffffffff811db3cf)
Location: kernel/trace/ftrace.c:6739
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
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
In kernel/trace/ftrace.c (ffffffff81211517)
Location: kernel/trace/ftrace.c:7173
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
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
In kernel/trace/ftrace.c (ffffffff8125aaaf)
Location: kernel/trace/ftrace.c:7289
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
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
In kernel/trace/ftrace.c (ffffffff81271f4f)
Location: kernel/trace/ftrace.c:7104
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
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
In kernel/trace/ftrace.c (ffffffff8128c440)
Location: kernel/trace/ftrace.c:7106
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
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
In kernel/trace/ftrace.c (ffff800010215ee8)
Location: kernel/trace/ftrace.c:6087
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
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
In kernel/trace/ftrace.c (c0454c84)
Location: kernel/trace/ftrace.c:6087
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
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
In kernel/trace/ftrace.c (c000000000297b70)
Location: kernel/trace/ftrace.c:6087
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
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
In kernel/trace/ftrace.c (ffffffe000175ae4)
Location: kernel/trace/ftrace.c:6087
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
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
In kernel/trace/ftrace.c (ffffffff81195638)
Location: kernel/trace/ftrace.c:6087
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
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
In kernel/trace/ftrace.c (ffffffff81188748)
Location: kernel/trace/ftrace.c:6087
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
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
In kernel/trace/ftrace.c (ffffffff81193408)
Location: kernel/trace/ftrace.c:6087
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
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
In kernel/trace/ftrace.c (ffffffff811a0fd8)
Location: kernel/trace/ftrace.c:6087
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
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
</ul>
