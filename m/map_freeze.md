# Function: <code>map_freeze</code>

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
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811d58f1)
Location: kernel/bpf/syscall.c:1152
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
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
In kernel/bpf/syscall.c (ffffffff811e23b8)
Location: kernel/bpf/syscall.c:1165
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int map_freeze(const union bpf_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811fceb0)
Location: kernel/bpf/syscall.c:1525
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
**Symbols:**

```
ffffffff811fceb0-ffffffff811fcfe7: map_freeze (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int map_freeze(const union bpf_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811fc170)
Location: kernel/bpf/syscall.c:1538
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
**Symbols:**

```
ffffffff811fc170-ffffffff811fc2a7: map_freeze (STB_LOCAL)
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
In kernel/bpf/syscall.c (ffffffff81201ba0)
Location: kernel/bpf/syscall.c:1539
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
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
In kernel/bpf/syscall.c (ffffffff81233c27)
Location: kernel/bpf/syscall.c:1607
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__sys_bpf
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int map_freeze(const union bpf_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/syscall.c (0)
Location: kernel/bpf/syscall.c:1851
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__sys_bpf
```
**Symbols:**

```
ffffffff81270d90-ffffffff81270f11: map_freeze (STB_LOCAL)
ffffffff81e68b6a-ffffffff81e68b7f: map_freeze.cold (STB_LOCAL)
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
In kernel/bpf/syscall.c (ffffffff812ccfc0)
Location: kernel/bpf/syscall.c:1885
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__sys_bpf
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int map_freeze(const union bpf_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/syscall.c (0)
Location: kernel/bpf/syscall.c:1962
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__sys_bpf
```
**Symbols:**

```
ffffffff812ee110-ffffffff812ee2b2: map_freeze (STB_LOCAL)
ffffffff820de792-ffffffff820de7bc: map_freeze.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int map_freeze(const union bpf_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/syscall.c (0)
Location: kernel/bpf/syscall.c:2002
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__sys_bpf
```
**Symbols:**

```
ffffffff8130ced0-ffffffff8130d072: map_freeze (STB_LOCAL)
ffffffff821ba686-ffffffff821ba6b0: map_freeze.cold (STB_LOCAL)
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
In kernel/bpf/syscall.c (ffff800010265018)
Location: kernel/bpf/syscall.c:1165
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
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
In kernel/bpf/syscall.c (c049770c)
Location: kernel/bpf/syscall.c:1165
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
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
In kernel/bpf/syscall.c (c000000000309c0c)
Location: kernel/bpf/syscall.c:1165
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
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
In kernel/bpf/syscall.c (ffffffe0001a0a1a)
Location: kernel/bpf/syscall.c:1165
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
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
In kernel/bpf/syscall.c (ffffffff811da9d8)
Location: kernel/bpf/syscall.c:1165
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
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
In kernel/bpf/syscall.c (ffffffff811cd798)
Location: kernel/bpf/syscall.c:1165
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
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
In kernel/bpf/syscall.c (ffffffff811d87a8)
Location: kernel/bpf/syscall.c:1165
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
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
In kernel/bpf/syscall.c (ffffffff811e6b32)
Location: kernel/bpf/syscall.c:1165
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
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
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
