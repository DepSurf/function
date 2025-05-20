# Function: <code>get_branch_type</code>

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
<summary>In <code>6.2</code>: ✅</summary>

```c
int get_branch_type(long unsigned int from, long unsigned int to, int abort, bool fused, int *offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/utils.c (ffffffff8100b0b0)
Location: arch/x86/events/utils.c:86
Inline: False
Direct callers:
  - arch/x86/events/utils.c:branch_type_fused
  - arch/x86/events/utils.c:branch_type
```
**Symbols:**

```
ffffffff8100b0b0-ffffffff8100b31f: get_branch_type (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int get_branch_type(long unsigned int from, long unsigned int to, int abort, bool fused, int *offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/utils.c (ffffffff8100a880)
Location: arch/x86/events/utils.c:86
Inline: False
Direct callers:
  - arch/x86/events/utils.c:branch_type_fused
  - arch/x86/events/utils.c:branch_type
```
**Symbols:**

```
ffffffff8100a880-ffffffff8100aaef: get_branch_type (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int get_branch_type(long unsigned int from, long unsigned int to, int abort, bool fused, int *offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/utils.c (ffffffff8100fff0)
Location: arch/x86/events/utils.c:87
Inline: False
Direct callers:
  - arch/x86/events/utils.c:branch_type_fused
  - arch/x86/events/utils.c:branch_type
```
**Symbols:**

```
ffffffff8100fff0-ffffffff8101026c: get_branch_type (STB_LOCAL)
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
