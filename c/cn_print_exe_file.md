# Function: <code>cn_print_exe_file</code>

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
In fs/coredump.c (ffffffff8126f3e5)
Location: fs/coredump.c:127
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
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
In fs/coredump.c (ffffffff8129abc0)
Location: fs/coredump.c:151
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
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
In fs/coredump.c (ffffffff812af77f)
Location: fs/coredump.c:152
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
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
In fs/coredump.c (ffffffff812bcbdd)
Location: fs/coredump.c:154
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
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
In fs/coredump.c (ffffffff812e091f)
Location: fs/coredump.c:155
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
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
In fs/coredump.c (ffffffff8130cc22)
Location: fs/coredump.c:155
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
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
In fs/coredump.c (ffffffff8132259e)
Location: fs/coredump.c:155
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
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
In fs/coredump.c (ffffffff813495a0)
Location: fs/coredump.c:156
Inline: True
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
In fs/coredump.c (ffffffff81361840)
Location: fs/coredump.c:156
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int cn_print_exe_file(struct core_name *cn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/coredump.c (ffffffff813a7470)
Location: fs/coredump.c:156
Inline: False
Direct callers:
  - fs/coredump.c:format_corename
```
**Symbols:**

```
ffffffff813a7470-ffffffff813a7536: cn_print_exe_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int cn_print_exe_file(struct core_name *cn, bool name_only);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/coredump.c (ffffffff813b82c0)
Location: fs/coredump.c:156
Inline: False
Direct callers:
  - fs/coredump.c:format_corename
  - fs/coredump.c:format_corename
```
**Symbols:**

```
ffffffff813b82c0-ffffffff813b83b7: cn_print_exe_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int cn_print_exe_file(struct core_name *cn, bool name_only);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/coredump.c (ffffffff813bf3b0)
Location: fs/coredump.c:156
Inline: False
```
**Symbols:**

```
ffffffff813bf3b0-ffffffff813bf4a7: cn_print_exe_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int cn_print_exe_file(struct core_name *cn, bool name_only);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/coredump.c (ffffffff8140f1e0)
Location: fs/coredump.c:156
Inline: False
```
**Symbols:**

```
ffffffff8140f1e0-ffffffff8140f2d7: cn_print_exe_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int cn_print_exe_file(struct core_name *cn, bool name_only);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/coredump.c (ffffffff81484e40)
Location: fs/coredump.c:158
Inline: False
```
**Symbols:**

```
ffffffff81484e40-ffffffff81484f46: cn_print_exe_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int cn_print_exe_file(struct core_name *cn, bool name_only);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/coredump.c (ffffffff815183a0)
Location: fs/coredump.c:161
Inline: False
```
**Symbols:**

```
ffffffff815183a0-ffffffff815184a6: cn_print_exe_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int cn_print_exe_file(struct core_name *cn, bool name_only);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/coredump.c (ffffffff8154fcb0)
Location: fs/coredump.c:161
Inline: False
```
**Symbols:**

```
ffffffff8154fcb0-ffffffff8154fdb6: cn_print_exe_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int cn_print_exe_file(struct core_name *cn, bool name_only);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/coredump.c (ffffffff81585ae0)
Location: fs/coredump.c:161
Inline: False
```
**Symbols:**

```
ffffffff81585ae0-ffffffff81585c15: cn_print_exe_file (STB_LOCAL)
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
In fs/coredump.c (ffff800010427f2c)
Location: fs/coredump.c:156
Inline: True
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
In fs/coredump.c (c05f0e2c)
Location: fs/coredump.c:156
Inline: True
Inline callers:
  - fs/coredump.c:format_corename
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
In fs/coredump.c (c00000000053816c)
Location: fs/coredump.c:156
Inline: True
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
In fs/coredump.c (ffffffe0002c618a)
Location: fs/coredump.c:156
Inline: True
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
In fs/coredump.c (ffffffff81359e20)
Location: fs/coredump.c:156
Inline: True
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
In fs/coredump.c (ffffffff8134aad0)
Location: fs/coredump.c:156
Inline: True
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
In fs/coredump.c (ffffffff813578f0)
Location: fs/coredump.c:156
Inline: True
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
In fs/coredump.c (ffffffff8136afd0)
Location: fs/coredump.c:156
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool name_only</code>
</li>
</ul>
</details>
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
