# Function: <code>disarm_all_kprobes</code>

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
In kernel/kprobes.c (ffffffff8112dd0d)
Location: kernel/kprobes.c:2351
Inline: True
Inline callers:
  - kernel/kprobes.c:write_enabled_file_bool
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
In kernel/kprobes.c (ffffffff81135f8e)
Location: kernel/kprobes.c:2351
Inline: True
Inline callers:
  - kernel/kprobes.c:write_enabled_file_bool
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
In kernel/kprobes.c (ffffffff8113fd0e)
Location: kernel/kprobes.c:2351
Inline: True
Inline callers:
  - kernel/kprobes.c:write_enabled_file_bool
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
In kernel/kprobes.c (ffffffff8114212f)
Location: kernel/kprobes.c:2439
Inline: True
Inline callers:
  - kernel/kprobes.c:write_enabled_file_bool
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
In kernel/kprobes.c (ffffffff8114eeef)
Location: kernel/kprobes.c:2443
Inline: True
Inline callers:
  - kernel/kprobes.c:write_enabled_file_bool
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
In kernel/kprobes.c (ffffffff8115d9da)
Location: kernel/kprobes.c:2510
Inline: True
Inline callers:
  - kernel/kprobes.c:write_enabled_file_bool
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
In kernel/kprobes.c (ffffffff8116a5fa)
Location: kernel/kprobes.c:2466
Inline: True
Inline callers:
  - kernel/kprobes.c:write_enabled_file_bool
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
In kernel/kprobes.c (ffffffff81177353)
Location: kernel/kprobes.c:2471
Inline: True
Inline callers:
  - kernel/kprobes.c:write_enabled_file_bool
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
In kernel/kprobes.c (ffffffff81183279)
Location: kernel/kprobes.c:2514
Inline: True
Inline callers:
  - kernel/kprobes.c:write_enabled_file_bool
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int disarm_all_kprobes();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (0)
Location: kernel/kprobes.c:2659
Inline: False
Direct callers:
  - kernel/kprobes.c:write_enabled_file_bool
```
**Symbols:**

```
ffffffff81197050-ffffffff81197159: disarm_all_kprobes (STB_LOCAL)
ffffffff811981a4-ffffffff811981df: disarm_all_kprobes.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int disarm_all_kprobes();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (0)
Location: kernel/kprobes.c:2709
Inline: False
Direct callers:
  - kernel/kprobes.c:write_enabled_file_bool
```
**Symbols:**

```
ffffffff811941d0-ffffffff811942d9: disarm_all_kprobes (STB_LOCAL)
ffffffff81be4a99-ffffffff81be4ad4: disarm_all_kprobes.cold (STB_LOCAL)
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
In kernel/kprobes.c (ffffffff81195258)
Location: kernel/kprobes.c:2714
Inline: True
Inline callers:
  - kernel/kprobes.c:write_enabled_file_bool
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
In kernel/kprobes.c (ffffffff811be139)
Location: kernel/kprobes.c:2708
Inline: True
Inline callers:
  - kernel/kprobes.c:write_enabled_file_bool
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
In kernel/kprobes.c (ffffffff811f1544)
Location: kernel/kprobes.c:2918
Inline: True
Inline callers:
  - kernel/kprobes.c:write_enabled_file_bool
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
In kernel/kprobes.c (ffffffff81237f54)
Location: kernel/kprobes.c:2925
Inline: True
Inline callers:
  - kernel/kprobes.c:write_enabled_file_bool
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
In kernel/kprobes.c (ffffffff8124f034)
Location: kernel/kprobes.c:2938
Inline: True
Inline callers:
  - kernel/kprobes.c:write_enabled_file_bool
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
In kernel/kprobes.c (ffffffff81268f64)
Location: kernel/kprobes.c:2923
Inline: True
Inline callers:
  - kernel/kprobes.c:write_enabled_file_bool
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
In kernel/kprobes.c (ffff8000101f81f4)
Location: kernel/kprobes.c:2514
Inline: True
Inline callers:
  - kernel/kprobes.c:write_enabled_file_bool
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
In kernel/kprobes.c (c0438a9c)
Location: kernel/kprobes.c:2514
Inline: True
Inline callers:
  - kernel/kprobes.c:write_enabled_file_bool
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
In kernel/kprobes.c (c00000000026f9e0)
Location: kernel/kprobes.c:2514
Inline: True
Inline callers:
  - kernel/kprobes.c:write_enabled_file_bool
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff8117b899)
Location: kernel/kprobes.c:2514
Inline: True
Inline callers:
  - kernel/kprobes.c:write_enabled_file_bool
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
In kernel/kprobes.c (ffffffff8116ea39)
Location: kernel/kprobes.c:2514
Inline: True
Inline callers:
  - kernel/kprobes.c:write_enabled_file_bool
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
In kernel/kprobes.c (ffffffff81179669)
Location: kernel/kprobes.c:2514
Inline: True
Inline callers:
  - kernel/kprobes.c:write_enabled_file_bool
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
In kernel/kprobes.c (ffffffff81186f79)
Location: kernel/kprobes.c:2514
Inline: True
Inline callers:
  - kernel/kprobes.c:write_enabled_file_bool
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
