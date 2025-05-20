# Function: <code>btf_get_info_by_fd</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int btf_get_info_by_fd(const struct btf *btf, const union bpf_attr *attr, union bpf_attr *uattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811c9520)
Location: kernel/bpf/btf.c:2305
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
```
**Symbols:**

```
ffffffff811c9520-ffffffff811c964d: btf_get_info_by_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int btf_get_info_by_fd(const struct btf *btf, const union bpf_attr *attr, union bpf_attr *uattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811dce20)
Location: kernel/bpf/btf.c:2957
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
```
**Symbols:**

```
ffffffff811dce20-ffffffff811dcf4d: btf_get_info_by_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int btf_get_info_by_fd(const struct btf *btf, const union bpf_attr *attr, union bpf_attr *uattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811f2470)
Location: kernel/bpf/btf.c:3447
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
```
**Symbols:**

```
ffffffff811f2470-ffffffff811f25a6: btf_get_info_by_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int btf_get_info_by_fd(const struct btf *btf, const union bpf_attr *attr, union bpf_attr *uattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811feb80)
Location: kernel/bpf/btf.c:3458
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
```
**Symbols:**

```
ffffffff811feb80-ffffffff811fecc6: btf_get_info_by_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int btf_get_info_by_fd(const struct btf *btf, const union bpf_attr *attr, union bpf_attr *uattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81225f70)
Location: kernel/bpf/btf.c:4650
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
```
**Symbols:**

```
ffffffff81225f70-ffffffff812260b0: btf_get_info_by_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int btf_get_info_by_fd(const struct btf *btf, const union bpf_attr *attr, union bpf_attr *uattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/btf.c (0)
Location: kernel/bpf/btf.c:5655
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
```
**Symbols:**

```
ffffffff81be65d6-ffffffff81be65ee: btf_get_info_by_fd.cold (STB_LOCAL)
ffffffff8122c9d0-ffffffff8122cc3c: btf_get_info_by_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int btf_get_info_by_fd(const struct btf *btf, const union bpf_attr *attr, union bpf_attr *uattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/btf.c (0)
Location: kernel/bpf/btf.c:5848
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
```
**Symbols:**

```
ffffffff81bd82d6-ffffffff81bd82ee: btf_get_info_by_fd.cold (STB_LOCAL)
ffffffff81231790-ffffffff812319ed: btf_get_info_by_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int btf_get_info_by_fd(const struct btf *btf, const union bpf_attr *attr, union bpf_attr *uattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/btf.c (0)
Location: kernel/bpf/btf.c:5901
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
```
**Symbols:**

```
ffffffff81cb955f-ffffffff81cb9592: btf_get_info_by_fd.cold (STB_LOCAL)
ffffffff8126a740-ffffffff8126a98d: btf_get_info_by_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int btf_get_info_by_fd(const struct btf *btf, const union bpf_attr *attr, union bpf_attr *uattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/btf.c (0)
Location: kernel/bpf/btf.c:6634
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__sys_bpf
```
**Symbols:**

```
ffffffff81e6a8d9-ffffffff81e6a905: btf_get_info_by_fd.cold (STB_LOCAL)
ffffffff812b7570-ffffffff812b77c4: btf_get_info_by_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int btf_get_info_by_fd(const struct btf *btf, const union bpf_attr *attr, union bpf_attr *uattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/btf.c (0)
Location: kernel/bpf/btf.c:7125
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__sys_bpf
```
**Symbols:**

```
ffffffff820619cf-ffffffff820619e3: btf_get_info_by_fd.cold (STB_LOCAL)
ffffffff81318bb0-ffffffff81318e16: btf_get_info_by_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int btf_get_info_by_fd(const struct btf *btf, const union bpf_attr *attr, union bpf_attr *uattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/btf.c (0)
Location: kernel/bpf/btf.c:7224
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
```
**Symbols:**

```
ffffffff820e1085-ffffffff820e1099: btf_get_info_by_fd.cold (STB_LOCAL)
ffffffff813489d0-ffffffff81348c3c: btf_get_info_by_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int btf_get_info_by_fd(const struct btf *btf, const union bpf_attr *attr, union bpf_attr *uattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/btf.c (0)
Location: kernel/bpf/btf.c:7288
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
```
**Symbols:**

```
ffffffff821bd892-ffffffff821bd8a6: btf_get_info_by_fd.cold (STB_LOCAL)
ffffffff8136f100-ffffffff8136f36c: btf_get_info_by_fd (STB_GLOBAL)
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
int btf_get_info_by_fd(const struct btf *btf, const union bpf_attr *attr, union bpf_attr *uattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffff800010285c30)
Location: kernel/bpf/btf.c:3458
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
```
**Symbols:**

```
ffff800010285c30-ffff80001028611c: btf_get_info_by_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int btf_get_info_by_fd(const struct btf *btf, const union bpf_attr *attr, union bpf_attr *uattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (c04b61dc)
Location: kernel/bpf/btf.c:3458
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
```
**Symbols:**

```
c04b61dc-c04b646c: btf_get_info_by_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int btf_get_info_by_fd(const struct btf *btf, const union bpf_attr *attr, union bpf_attr *uattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (c000000000330b30)
Location: kernel/bpf/btf.c:3458
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
```
**Symbols:**

```
c000000000330b30-c000000000330d88: btf_get_info_by_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int btf_get_info_by_fd(const struct btf *btf, const union bpf_attr *attr, union bpf_attr *uattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffe0001baed4)
Location: kernel/bpf/btf.c:3458
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
```
**Symbols:**

```
ffffffe0001baed4-ffffffe0001bb008: btf_get_info_by_fd (STB_GLOBAL)
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
int btf_get_info_by_fd(const struct btf *btf, const union bpf_attr *attr, union bpf_attr *uattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811f71a0)
Location: kernel/bpf/btf.c:3458
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
```
**Symbols:**

```
ffffffff811f71a0-ffffffff811f72e6: btf_get_info_by_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int btf_get_info_by_fd(const struct btf *btf, const union bpf_attr *attr, union bpf_attr *uattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811e9ef0)
Location: kernel/bpf/btf.c:3458
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
```
**Symbols:**

```
ffffffff811e9ef0-ffffffff811ea036: btf_get_info_by_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int btf_get_info_by_fd(const struct btf *btf, const union bpf_attr *attr, union bpf_attr *uattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811f4f70)
Location: kernel/bpf/btf.c:3458
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
```
**Symbols:**

```
ffffffff811f4f70-ffffffff811f50b6: btf_get_info_by_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int btf_get_info_by_fd(const struct btf *btf, const union bpf_attr *attr, union bpf_attr *uattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81203490)
Location: kernel/bpf/btf.c:3458
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
```
**Symbols:**

```
ffffffff81203490-ffffffff812035d6: btf_get_info_by_fd (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
