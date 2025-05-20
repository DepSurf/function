# Function: <code>bpf_prog_attach_check_attach_type</code>

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
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811b3d84)
Location: kernel/bpf/syscall.c:1488
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_attach
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
In kernel/bpf/syscall.c (ffffffff811c4446)
Location: kernel/bpf/syscall.c:1682
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
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
In kernel/bpf/syscall.c (ffffffff811d5e36)
Location: kernel/bpf/syscall.c:1851
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
In kernel/bpf/syscall.c (ffffffff811e21d8)
Location: kernel/bpf/syscall.c:1874
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int bpf_prog_attach_check_attach_type(const struct bpf_prog *prog, enum bpf_attach_type attach_type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811fc390)
Location: kernel/bpf/syscall.c:2751
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:link_create
  - kernel/bpf/syscall.c:bpf_prog_attach
```
**Symbols:**

```
ffffffff811fc390-ffffffff811fc3fb: bpf_prog_attach_check_attach_type (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int bpf_prog_attach_check_attach_type(const struct bpf_prog *prog, enum bpf_attach_type attach_type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811fb4e0)
Location: kernel/bpf/syscall.c:2888
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:link_create
  - kernel/bpf/syscall.c:bpf_prog_attach
```
**Symbols:**

```
ffffffff811fb4e0-ffffffff811fb547: bpf_prog_attach_check_attach_type (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int bpf_prog_attach_check_attach_type(const struct bpf_prog *prog, enum bpf_attach_type attach_type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811fc200)
Location: kernel/bpf/syscall.c:2910
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:link_create
  - kernel/bpf/syscall.c:bpf_prog_attach
```
**Symbols:**

```
ffffffff811fc200-ffffffff811fc267: bpf_prog_attach_check_attach_type (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int bpf_prog_attach_check_attach_type(const struct bpf_prog *prog, enum bpf_attach_type attach_type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff8122db30)
Location: kernel/bpf/syscall.c:3093
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:link_create
  - kernel/bpf/syscall.c:bpf_prog_attach
```
**Symbols:**

```
ffffffff8122db30-ffffffff8122db97: bpf_prog_attach_check_attach_type (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bpf_prog_attach_check_attach_type(const struct bpf_prog *prog, enum bpf_attach_type attach_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff8126f720)
Location: kernel/bpf/syscall.c:3340
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:link_create
  - kernel/bpf/syscall.c:bpf_prog_attach
```
**Symbols:**

```
ffffffff8126f720-ffffffff8126f794: bpf_prog_attach_check_attach_type (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bpf_prog_attach_check_attach_type(const struct bpf_prog *prog, enum bpf_attach_type attach_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff812c5010)
Location: kernel/bpf/syscall.c:3374
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:link_create
  - kernel/bpf/syscall.c:bpf_prog_attach
```
**Symbols:**

```
ffffffff812c5010-ffffffff812c5084: bpf_prog_attach_check_attach_type (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bpf_prog_attach_check_attach_type(const struct bpf_prog *prog, enum bpf_attach_type attach_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff812ec140)
Location: kernel/bpf/syscall.c:3505
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:link_create
  - kernel/bpf/syscall.c:bpf_prog_attach
```
**Symbols:**

```
ffffffff812ec140-ffffffff812ec1c6: bpf_prog_attach_check_attach_type (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bpf_prog_attach_check_attach_type(const struct bpf_prog *prog, enum bpf_attach_type attach_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff8130a670)
Location: kernel/bpf/syscall.c:3809
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:link_create
  - kernel/bpf/syscall.c:bpf_prog_attach
```
**Symbols:**

```
ffffffff8130a670-ffffffff8130a76e: bpf_prog_attach_check_attach_type (STB_LOCAL)
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
In kernel/bpf/syscall.c (ffff800010265334)
Location: kernel/bpf/syscall.c:1874
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
In kernel/bpf/syscall.c (c0497338)
Location: kernel/bpf/syscall.c:1874
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
In kernel/bpf/syscall.c (c000000000309ef4)
Location: kernel/bpf/syscall.c:1874
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
In kernel/bpf/syscall.c (ffffffe0001a0c80)
Location: kernel/bpf/syscall.c:1874
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
In kernel/bpf/syscall.c (ffffffff811da7f8)
Location: kernel/bpf/syscall.c:1874
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
In kernel/bpf/syscall.c (ffffffff811cd5b8)
Location: kernel/bpf/syscall.c:1874
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
In kernel/bpf/syscall.c (ffffffff811d85c8)
Location: kernel/bpf/syscall.c:1874
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
In kernel/bpf/syscall.c (ffffffff811e694b)
Location: kernel/bpf/syscall.c:1874
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
