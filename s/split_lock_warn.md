# Function: <code>split_lock_warn</code>

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
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void split_lock_warn(long unsigned int ip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (0)
Location: arch/x86/kernel/cpu/intel.c:1085
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel.c:handle_user_split_lock
  - arch/x86/kernel/cpu/intel.c:handle_guest_split_lock
```
**Symbols:**

```
ffffffff8104dba0-ffffffff8104dbf6: split_lock_warn (STB_LOCAL)
ffffffff8104e617-ffffffff8104e641: split_lock_warn.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void split_lock_warn(long unsigned int ip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (0)
Location: arch/x86/kernel/cpu/intel.c:1086
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel.c:handle_user_split_lock
  - arch/x86/kernel/cpu/intel.c:handle_guest_split_lock
```
**Symbols:**

```
ffffffff8104d0d0-ffffffff8104d126: split_lock_warn (STB_LOCAL)
ffffffff81bd5182-ffffffff81bd51ac: split_lock_warn.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void split_lock_warn(long unsigned int ip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (0)
Location: arch/x86/kernel/cpu/intel.c:1089
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel.c:handle_user_split_lock
  - arch/x86/kernel/cpu/intel.c:handle_guest_split_lock
```
**Symbols:**

```
ffffffff8104ec50-ffffffff8104eca6: split_lock_warn (STB_LOCAL)
ffffffff81bc758a-ffffffff81bc75b4: split_lock_warn.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void split_lock_warn(long unsigned int ip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (0)
Location: arch/x86/kernel/cpu/intel.c:1119
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel.c:handle_user_split_lock
  - arch/x86/kernel/cpu/intel.c:handle_guest_split_lock
```
**Symbols:**

```
ffffffff81056cc0-ffffffff81056d16: split_lock_warn (STB_LOCAL)
ffffffff81c9ae7d-ffffffff81c9aea7: split_lock_warn.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void split_lock_warn(long unsigned int ip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (0)
Location: arch/x86/kernel/cpu/intel.c:1174
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel.c:handle_user_split_lock
  - arch/x86/kernel/cpu/intel.c:handle_guest_split_lock
```
**Symbols:**

```
ffffffff81062f30-ffffffff81063014: split_lock_warn (STB_LOCAL)
ffffffff81e4a3ba-ffffffff81e4a3de: split_lock_warn.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void split_lock_warn(long unsigned int ip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (ffffffff81071da0)
Location: arch/x86/kernel/cpu/intel.c:1346
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel.c:handle_user_split_lock
  - arch/x86/kernel/cpu/intel.c:handle_guest_split_lock
```
**Symbols:**

```
ffffffff81071da0-ffffffff81071eb9: split_lock_warn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void split_lock_warn(long unsigned int ip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (ffffffff81073990)
Location: arch/x86/kernel/cpu/intel.c:1346
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel.c:handle_user_split_lock
  - arch/x86/kernel/cpu/intel.c:handle_guest_split_lock
```
**Symbols:**

```
ffffffff81073990-ffffffff81073aa9: split_lock_warn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void split_lock_warn(long unsigned int ip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (ffffffff8107aed0)
Location: arch/x86/kernel/cpu/intel.c:1162
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel.c:handle_user_split_lock
  - arch/x86/kernel/cpu/intel.c:handle_guest_split_lock
```
**Symbols:**

```
ffffffff8107aed0-ffffffff8107afe9: split_lock_warn (STB_LOCAL)
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
