# Function: <code>map_lookup_and_delete_elem</code>

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
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811c42e0)
Location: kernel/bpf/syscall.c:1013
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
In kernel/bpf/syscall.c (ffffffff811d5f3f)
Location: kernel/bpf/syscall.c:1090
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
In kernel/bpf/syscall.c (ffffffff811e279c)
Location: kernel/bpf/syscall.c:1103
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
int map_lookup_and_delete_elem(union bpf_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811fd2e0)
Location: kernel/bpf/syscall.c:1460
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
**Symbols:**

```
ffffffff811fd2e0-ffffffff811fd4da: map_lookup_and_delete_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int map_lookup_and_delete_elem(union bpf_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811fc5b0)
Location: kernel/bpf/syscall.c:1473
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
**Symbols:**

```
ffffffff811fc5b0-ffffffff811fc7aa: map_lookup_and_delete_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int map_lookup_and_delete_elem(union bpf_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811fceb0)
Location: kernel/bpf/syscall.c:1474
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
**Symbols:**

```
ffffffff811fceb0-ffffffff811fd0a7: map_lookup_and_delete_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int map_lookup_and_delete_elem(union bpf_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/syscall.c (0)
Location: kernel/bpf/syscall.c:1514
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__sys_bpf
```
**Symbols:**

```
ffffffff8122ec80-ffffffff8122efbe: map_lookup_and_delete_elem (STB_LOCAL)
ffffffff81cb7aa1-ffffffff81cb7af0: map_lookup_and_delete_elem.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int map_lookup_and_delete_elem(union bpf_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/syscall.c (0)
Location: kernel/bpf/syscall.c:1758
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__sys_bpf
```
**Symbols:**

```
ffffffff81271540-ffffffff812718b5: map_lookup_and_delete_elem (STB_LOCAL)
ffffffff81e68c23-ffffffff81e68c7a: map_lookup_and_delete_elem.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int map_lookup_and_delete_elem(union bpf_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/syscall.c (0)
Location: kernel/bpf/syscall.c:1792
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__sys_bpf
```
**Symbols:**

```
ffffffff812c7750-ffffffff812c7adc: map_lookup_and_delete_elem (STB_LOCAL)
ffffffff8205f8f3-ffffffff8205f94a: map_lookup_and_delete_elem.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int map_lookup_and_delete_elem(union bpf_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/syscall.c (0)
Location: kernel/bpf/syscall.c:1869
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__sys_bpf
```
**Symbols:**

```
ffffffff812eec20-ffffffff812eef96: map_lookup_and_delete_elem (STB_LOCAL)
ffffffff820de848-ffffffff820de897: map_lookup_and_delete_elem.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int map_lookup_and_delete_elem(union bpf_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/syscall.c (0)
Location: kernel/bpf/syscall.c:1909
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__sys_bpf
```
**Symbols:**

```
ffffffff8130d9e0-ffffffff8130dd56: map_lookup_and_delete_elem (STB_LOCAL)
ffffffff821ba73c-ffffffff821ba78b: map_lookup_and_delete_elem.cold (STB_LOCAL)
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
In kernel/bpf/syscall.c (ffff80001026584c)
Location: kernel/bpf/syscall.c:1103
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
In kernel/bpf/syscall.c (c04976ac)
Location: kernel/bpf/syscall.c:1103
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
In kernel/bpf/syscall.c (c00000000030a3b0)
Location: kernel/bpf/syscall.c:1103
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
In kernel/bpf/syscall.c (ffffffe0001a1116)
Location: kernel/bpf/syscall.c:1103
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
In kernel/bpf/syscall.c (ffffffff811dadbc)
Location: kernel/bpf/syscall.c:1103
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
In kernel/bpf/syscall.c (ffffffff811cdb7c)
Location: kernel/bpf/syscall.c:1103
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
In kernel/bpf/syscall.c (ffffffff811d8b8c)
Location: kernel/bpf/syscall.c:1103
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
In kernel/bpf/syscall.c (ffffffff811e6f16)
Location: kernel/bpf/syscall.c:1103
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
