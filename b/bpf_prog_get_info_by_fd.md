# Function: <code>bpf_prog_get_info_by_fd</code>

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
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811934a2)
Location: kernel/bpf/syscall.c:1275
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:SyS_bpf
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
In kernel/bpf/syscall.c (ffffffff8119ec78)
Location: kernel/bpf/syscall.c:1554
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811b43d0)
Location: kernel/bpf/syscall.c:1853
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
```
**Symbols:**

```
ffffffff811b43d0-ffffffff811b4b6d: bpf_prog_get_info_by_fd.isra.25 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811c23f0)
Location: kernel/bpf/syscall.c:2079
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
```
**Symbols:**

```
ffffffff811c23f0-ffffffff811c2eec: bpf_prog_get_info_by_fd.isra.25 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811d2f70)
Location: kernel/bpf/syscall.c:2300
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
```
**Symbols:**

```
ffffffff811d2f70-ffffffff811d3b1f: bpf_prog_get_info_by_fd.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811df270)
Location: kernel/bpf/syscall.c:2323
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
```
**Symbols:**

```
ffffffff811df270-ffffffff811dfe92: bpf_prog_get_info_by_fd.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811fd4e0)
Location: kernel/bpf/syscall.c:3223
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
```
**Symbols:**

```
ffffffff811fd4e0-ffffffff811fdfbb: bpf_prog_get_info_by_fd.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811fc7b0)
Location: kernel/bpf/syscall.c:3390
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
```
**Symbols:**

```
ffffffff811fc7b0-ffffffff811fd291: bpf_prog_get_info_by_fd.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811fd0b0)
Location: kernel/bpf/syscall.c:3413
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
```
**Symbols:**

```
ffffffff811fd0b0-ffffffff811fdb95: bpf_prog_get_info_by_fd.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/syscall.c (0)
Location: kernel/bpf/syscall.c:3596
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
```
**Symbols:**

```
ffffffff8122f440-ffffffff8122feed: bpf_prog_get_info_by_fd.isra.0 (STB_LOCAL)
ffffffff81cb7b17-ffffffff81cb7b2b: bpf_prog_get_info_by_fd.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/syscall.c (0)
Location: kernel/bpf/syscall.c:3854
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:__sys_bpf
```
**Symbols:**

```
ffffffff81271fa0-ffffffff81272a99: bpf_prog_get_info_by_fd.isra.0 (STB_LOCAL)
ffffffff81e68c9f-ffffffff81e68cb3: bpf_prog_get_info_by_fd.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int bpf_prog_get_info_by_fd(struct file *file, struct bpf_prog *prog, const union bpf_attr *attr, union bpf_attr *uattr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/syscall.c (0)
Location: kernel/bpf/syscall.c:3897
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__sys_bpf
```
**Symbols:**

```
ffffffff812c7ee0-ffffffff812c8a1b: bpf_prog_get_info_by_fd (STB_LOCAL)
ffffffff8205f971-ffffffff8205f985: bpf_prog_get_info_by_fd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int bpf_prog_get_info_by_fd(struct file *file, struct bpf_prog *prog, const union bpf_attr *attr, union bpf_attr *uattr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/syscall.c (0)
Location: kernel/bpf/syscall.c:4033
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
```
**Symbols:**

```
ffffffff812ef3a0-ffffffff812efec9: bpf_prog_get_info_by_fd (STB_LOCAL)
ffffffff820de8be-ffffffff820de8d2: bpf_prog_get_info_by_fd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int bpf_prog_get_info_by_fd(struct file *file, struct bpf_prog *prog, const union bpf_attr *attr, union bpf_attr *uattr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/syscall.c (0)
Location: kernel/bpf/syscall.c:4370
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
```
**Symbols:**

```
ffffffff8130e180-ffffffff8130eca9: bpf_prog_get_info_by_fd (STB_LOCAL)
ffffffff821ba7b2-ffffffff821ba7c6: bpf_prog_get_info_by_fd.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/syscall.c (ffff800010261378)
Location: kernel/bpf/syscall.c:2323
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
```
**Symbols:**

```
ffff800010261378-ffff8000102621d4: bpf_prog_get_info_by_fd.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int bpf_prog_get_info_by_fd(struct bpf_prog *prog, const union bpf_attr *attr, union bpf_attr *uattr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (c0494098)
Location: kernel/bpf/syscall.c:2323
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
```
**Symbols:**

```
c0494098-c0494f18: bpf_prog_get_info_by_fd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/syscall.c (c000000000305ea0)
Location: kernel/bpf/syscall.c:2323
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
```
**Symbols:**

```
c000000000305ea0-c000000000306f0c: bpf_prog_get_info_by_fd.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/syscall.c (ffffffe00019e4aa)
Location: kernel/bpf/syscall.c:2323
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
```
**Symbols:**

```
ffffffe00019e4aa-ffffffe00019ee44: bpf_prog_get_info_by_fd.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811d7890)
Location: kernel/bpf/syscall.c:2323
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
```
**Symbols:**

```
ffffffff811d7890-ffffffff811d84b2: bpf_prog_get_info_by_fd.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811ca650)
Location: kernel/bpf/syscall.c:2323
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
```
**Symbols:**

```
ffffffff811ca650-ffffffff811cb272: bpf_prog_get_info_by_fd.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811d5660)
Location: kernel/bpf/syscall.c:2323
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
```
**Symbols:**

```
ffffffff811d5660-ffffffff811d6282: bpf_prog_get_info_by_fd.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811e39d0)
Location: kernel/bpf/syscall.c:2323
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
```
**Symbols:**

```
ffffffff811e39d0-ffffffff811e45f2: bpf_prog_get_info_by_fd.isra.0 (STB_LOCAL)
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
<b>Arch</b>
<ul>
</ul>
