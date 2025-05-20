# Function: <code>bpf_link_by_id</code>

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
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct bpf_link *bpf_link_by_id(u32 id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81201432)
Location: kernel/bpf/syscall.c:4159
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
**Symbols:**

```
ffffffff811fb550-ffffffff811fb5c4: bpf_link_by_id.part.0 (STB_LOCAL)
ffffffff81201760-ffffffff8120177c: bpf_link_by_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct bpf_link *bpf_link_by_id(u32 id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81201ef9)
Location: kernel/bpf/syscall.c:4183
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
**Symbols:**

```
ffffffff811fc270-ffffffff811fc2e4: bpf_link_by_id.part.0 (STB_LOCAL)
ffffffff81202620-ffffffff8120263c: bpf_link_by_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct bpf_link *bpf_link_by_id(u32 id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff812340d4)
Location: kernel/bpf/syscall.c:4386
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__sys_bpf
Direct callers:
  - kernel/bpf/syscall.c:__sys_bpf
```
**Symbols:**

```
ffffffff8122dba0-ffffffff8122dc14: bpf_link_by_id.part.0 (STB_LOCAL)
ffffffff81234640-ffffffff8123465c: bpf_link_by_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct bpf_link *bpf_link_by_id(u32 id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81276e91)
Location: kernel/bpf/syscall.c:4658
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:__sys_bpf
```
**Symbols:**

```
ffffffff81277c70-ffffffff81277cf3: bpf_link_by_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct bpf_link *bpf_link_by_id(u32 id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff812cd0a9)
Location: kernel/bpf/syscall.c:4710
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:__sys_bpf
```
**Symbols:**

```
ffffffff812ce080-ffffffff812ce103: bpf_link_by_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct bpf_link *bpf_link_by_id(u32 id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff812f4bfa)
Location: kernel/bpf/syscall.c:4893
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:__sys_bpf
```
**Symbols:**

```
ffffffff812f5610-ffffffff812f5693: bpf_link_by_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct bpf_link *bpf_link_by_id(u32 id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff813139f5)
Location: kernel/bpf/syscall.c:5208
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:__sys_bpf
Direct callers:
  - kernel/bpf/mprog.c:bpf_mprog_tuple_relative
```
**Symbols:**

```
ffffffff81314410-ffffffff81314493: bpf_link_by_id (STB_GLOBAL)
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
